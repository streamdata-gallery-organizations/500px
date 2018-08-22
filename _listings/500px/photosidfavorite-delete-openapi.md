---
swagger: "2.0"
x-collection-name: 500px
x-complete: 0
info:
  title: 500px Delete Photos Favorite
  description: Removes the photo to user's list of favorites.
  version: v1
host: api.500px.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /blogs/:
    get:
      summary: Get Blogs
      description: Returns a listing of five recent stories (maximum 100 per page).
      operationId: getBlogs
      x-api-path-slug: blogs-get
      parameters:
      - in: query
        name: feature
        description: Story stream to be retrieved
      - in: query
        name: feature (required)
        description: Story stream to be retrieved
      - in: query
        name: page
        description: Return a specific page in the story listing
      - in: query
        name: rpp
        description: The number of results to return
      - in: query
        name: user
        description: Return stories by a specific user, as displayed on [http://500px
      responses:
        200:
          description: OK
      tags:
      - Blogs
    post:
      summary: Post Blogs
      description: Creates a new Story.
      operationId: postBlogs
      x-api-path-slug: blogs-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the blog post
      - in: query
        name: latitude
        description: Latitude for the blog post
      - in: query
        name: longitude
        description: Longitude for the blog post
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values to post with the blog
      - in: query
        name: tags
        description: Comma separated list of tags
      - in: query
        name: title (required)
        description: Title for the blog post
      responses:
        200:
          description: OK
      tags:
      - Blogs
  /blogs/:id:
    delete:
      summary: Delete Blogs
      description: Deletes the story.
      operationId: deleteBlogs
      x-api-path-slug: blogsid-delete
      parameters:
      - in: query
        name: id (required)
        description: The Story ID to delete
      responses:
        200:
          description: OK
      tags:
      - Blogs
    get:
      summary: Get Blogs
      description: Returns detailed information of a single story.
      operationId: getBlogs
      x-api-path-slug: blogsid-get
      parameters:
      - in: query
        name: id (required) - Return information for the specific story.
      responses:
        200:
          description: OK
      tags:
      - Blogs
    put:
      summary: Put Blogs
      description: Updates the Story.
      operationId: putBlogs
      x-api-path-slug: blogsid-put
      parameters:
      - in: query
        name: body
        description: Content of the blog post
      - in: query
        name: id (required)
        description: The Blog Post ID to update
      - in: query
        name: latitude
        description: Latitude for the blog post
      - in: query
        name: longitude
        description: Longitude for the blog post
      - in: query
        name: photo_ids
        description: Comma separated list of Photo IDs for photos that are in the
          blog post
      - in: query
        name: tags
        description: Comma separated list of tags
      - in: query
        name: title
        description: Title for the blog post
      responses:
        200:
          description: OK
      tags:
      - Blogs
  /blogs/:id/comments:
    get:
      summary: Get Blogs Comments
      description: Returns a listing of twenty comments for a specific Story.
      operationId: getBlogsComments
      x-api-path-slug: blogsidcomments-get
      parameters:
      - in: query
        name: id (required)
        description: The Story ID to get comments for
      - in: query
        name: page
        description: Return a specific page in the comment listing
      responses:
        200:
          description: OK
      tags:
      - Blogs
      - Comments
    post:
      summary: Post Blogs Comments
      description: Creates a comment for the Story.
      operationId: postBlogsComments
      x-api-path-slug: blogsidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      - in: query
        name: id (required)
        description: The Story ID to create a comment for
      responses:
        200:
          description: OK
      tags:
      - Blogs
      - Comments
  /collections:
    get:
      summary: Get Collections
      description: Returns a listing of all Users collections and sets.
      operationId: getCollections
      x-api-path-slug: collections-get
      parameters:
      - in: query
        name: photos_per_collection_limit
        description: The number of photos included in each collection
      responses:
        200:
          description: OK
      tags:
      - Collections
    post:
      summary: Post Collections
      description: Creates new a collection.
      operationId: postCollections
      x-api-path-slug: collections-post
      parameters:
      - in: query
        name: kind
        description: 'Kind of the Collection to be created Recognized values: 1 -
          Portfolio Set (default), 2 - Profile Set'
      - in: query
        name: path
        description: Path where the collection will be accessible at 500px
      - in: query
        name: path (required)
        description: Path where the collection will be accessible at 500px
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values to post with the blog
      - in: query
        name: position
        description: Position of the collection in the list of collections
      - in: query
        name: title
        description: Title for the collection
      - in: query
        name: title (required)
        description: Title for the collection
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/:id:
    delete:
      summary: Delete Collections
      description: Deletes collection.
      operationId: deleteCollections
      x-api-path-slug: collectionsid-delete
      parameters:
      - in: query
        name: Forkn      n      n        69
      - in: query
        name: Starn  nn    n      281
      responses:
        200:
          description: OK
      tags:
      - Collections
    get:
      summary: Get Collections
      description: Returns a collection.
      operationId: getCollections
      x-api-path-slug: collectionsid-get
      parameters:
      - in: query
        name: image_size - Numerical size of the image to link to, 1 being the smallest
          and 4 being the largest. Multiple image sizes may be specified as image_size[]=2&amp;image_size[]=4.
      responses:
        200:
          description: OK
      tags:
      - Collections
    put:
      summary: Put Collections
      description: Updates collection.
      operationId: putCollections
      x-api-path-slug: collectionsid-put
      parameters:
      - in: query
        name: id (required)
        description: Collection ID
      - in: query
        name: kind
        description: Change kind of the Collection
      - in: query
        name: path
        description: Path where the collection will be accessible at 500px
      - in: query
        name: photo_ids
        description: Comma separated list of Photo ID values that are in this collection
      - in: query
        name: position
        description: Position of the collection in the list of collections
      - in: query
        name: title
        description: Title for the collection
      responses:
        200:
          description: OK
      tags:
      - Collections
  /comments/:id/comments:
    post:
      summary: Post Comments Comments
      description: Creates a reply to an existing comment. Comments can only be nested
        one level deep, you cannot reply to a reply of a comment. If a comment has
        a non-null parent_id value then it cannot be replied to.
      operationId: postCommentsComments
      x-api-path-slug: commentsidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Comments
  /photos:
    get:
      summary: Get Photos
      description: Returns a listing of twenty (up to one hundred) photos for a specified
        photo stream.
      operationId: getPhotos
      x-api-path-slug: photos-get
      parameters:
      - in: query
        name: exclude
        description: String name of the category to exclude photos by
      - in: query
        name: feature
        description: Photo stream to be retrieved
      - in: query
        name: image_size
        description: The photo size to be returned
      - in: query
        name: include_states
        description: If set to 1, returns state of the photo for the currently logged
          in user and authenticated request
      - in: query
        name: include_store
        description: If set to 1, returns market infomation about the photo
      - in: query
        name: only
        description: String name of the category to return photos from
      - in: query
        name: page
        description: Return a specific page in the photo stream
      - in: query
        name: rpp
        description: The number of results to return
      - in: query
        name: sort
        description: Sort photos in the specified order
      - in: query
        name: sort_direction
        description: Control the order of the sorting
      - in: query
        name: tags
        description: If set to 1, returns an array of tags for the photo
      - in: query
        name: username
        description: OR username for user Photo streeam
      - in: query
        name: user_id
        description: User ID user Photo streeam
      responses:
        200:
          description: OK
      tags:
      - Photos
    post:
      summary: Post Photos
      description: Create a new photo on behalf of the user, and receive an upload
        key in exchange.
      operationId: postPhotos
      x-api-path-slug: photos-post
      parameters:
      - in: query
        name: aperture
        description: Aperture value
      - in: query
        name: camera
        description: Make and model of the camera
      - in: query
        name: category
        description: A numerical ID for the Category of the photo
      - in: query
        name: description
        description: Description for the photo
      - in: query
        name: focal_length
        description: Focal length in millimetres, a string representing an integer
          value
      - in: query
        name: iso
        description: ISO value
      - in: query
        name: latitude
        description: Latitude, in decimal format
      - in: query
        name: lens
        description: Lens used to make this photo
      - in: query
        name: longitude
        description: Longitude, in decimal format
      - in: query
        name: name
        description: Title of the photo
      - in: query
        name: privacy
        description: Whether to hide the photo from the user profile on the website
      - in: query
        name: shutter_speed
        description: Shutter speed in seconds, represented by string containing a
          rational expression if the value is 1sec
      - in: query
        name: tags
        description: Comma-separated list of tags to apply to the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
  /photos/:id:
    delete:
      summary: Delete Photos
      description: Deletes the photo from the Users library.
      operationId: deletePhotos
      x-api-path-slug: photosid-delete
      parameters:
      - in: query
        name: id (required)
        description: The Photo ID to delete
      responses:
        200:
          description: OK
      tags:
      - Photos
    get:
      summary: Get Photos
      description: Returns detailed information of a single photo.
      operationId: getPhotos
      x-api-path-slug: photosid-get
      parameters:
      - in: query
        name: comments
        description: Return comments to the photo in the response
      - in: query
        name: comments_page
        description: Return the specified page from the comments listing
      - in: query
        name: image_size
        description: Numerical size of the image to link to, 1 being the smallest
          and 4 being the largest
      - in: query
        name: tags
        description: Returns an array of tags for the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
    put:
      summary: Put Photos
      description: 'Allows the client application to update user-editable information
        on a photo.nnnResource URLnnhttps://api.500px.com/v1/photos/:idnnnnAuthenticationnnRequired;
        OAuth. The client application must use the OAuth access token issued for the
        owner of the photo to access this resouce.nnnParametersnnThe application must
        provide the ID of the photo to update in the URL of the request. The following
        parameters are recognized when included in the query string or POST body:nnnnname:
        Title of the photo, up to 255 characters in length.nndescription: Text description
        of the photo, up to 65535 characters in length.nncategory: Integer number
        of the category of the photo. See category mapping for exact values.nntags:
        Comma-separated list of tags applicable to this photo.nnadd_tags: Comma-separated
        list of tags to add to this photos existing tags.nnremove_tags: Comma-separated
        list of tags to remove from this photos existing tags.nnshutter_speed: Shutter
        speed value for the photo, internally stored as string.nnfocal_length: Focal
        length value for the photo, internally stored as string.nnaperture: Aperture
        value value for the photo, internally stored as string.nniso: Integer ISO
        value for the photo.nncamera: Make and model of the camera used to take this
        photo.nnlens: Information about the lens used to take this photo.nnlatitude:
        Latitude of the location this photo was taken at represented by a decimal
        number.nnlongitude: Longitude of the location this photo was taken at represented
        by a decimal number.nnnsfw: Boolean value indicating that the photo may contain
        not-safe-for-work content or content not suitable for minors.nnlicense_type:
        Integer number of the license type chosen for this photo. See license type
        mapping for exact values.nnprivacy: Integer value indicating that the photo
        should be shown (0) or hidden (1) on the users profile.nncrop: A hash containing
        keys x, x2, y, y2 and representing coordinates within which the thumbnail
        must be cropped. The crop is made using the top left corner as the origin.
        The points must be given relative to image size 4, an image of at most 900px
        on the larger side. The client application may skip this if the user does
        not wish to change photo thumbnail.nnnnImplementation detailsnnA parameter
        missing from the request will not be updated.  A parameter set to an empty
        string or null value will be interpreted as the user wishing to reset the
        value of the field to its default value.nnYou can use the add_tags and remove_tags
        parameters to manupulate a photos tags without having to send the complete
        list of tags in the request.nnnReturn formatnnA JSON object containing key
        photo, where photo is a Photo object in full format.nnnErrorsnnAll known errors
        cause the resource to return HTTP error code header together with a JSON array
        containing at least status and error keys describing the source of error.nnnn401:
        Invalid OAuth request: The request was refused because the OAuth signature
        is incorrect.nn404: Photo with ID not found: The photo ID provided is not
        known to the system.nn404: Photo with ID has been deleted: The photo has been
        deleted and can not be edited.nn404: Photo with ID belongs to a deactivated
        user: The photo belongs to a user that is no longer active and can not be
        edited.nn400: Bad photo category: An unrecognized photo category value has
        been provided.nn400: Bad license type: An unrecognized license type value
        has been provided.'
      operationId: putPhotos
      x-api-path-slug: photosid-put
      parameters:
      - in: query
        name: 'add_tags: Comma-separated list of tags to add to this photos existing
          tags.'
      - in: query
        name: 'aperture: Aperture value value for the photo, internally stored as
          string.'
      - in: query
        name: 'camera: Make and model of the camera used to take this photo.'
      - in: query
        name: 'category: Integer number of the category of the photo. See category
          mapping for exact values.'
      - in: query
        name: 'crop: A hash containing keys x, x2, y, y2 and representing coordinates
          within which the thumbnail must be cropped. The crop is made using the top
          left corner as the origin. The points must be given relative to image size
          4, an image of at most 900px'
      - in: query
        name: 'description: Text description of the photo, up to 65535 characters
          in length.'
      - in: query
        name: 'focal_length: Focal length value for the photo, internally stored as
          string.'
      - in: query
        name: 'iso: Integer ISO value for the photo.'
      - in: query
        name: 'latitude: Latitude of the location this photo was taken at represented
          by a decimal number.'
      - in: query
        name: 'lens: Information about the lens used to take this photo.'
      - in: query
        name: 'license_type: Integer number of the license type chosen for this photo.
          See license type mapping for exact values.'
      - in: query
        name: 'longitude: Longitude of the location this photo was taken at represented
          by a decimal number.'
      - in: query
        name: 'name: Title of the photo, up to 255 characters in length.'
      - in: query
        name: 'nsfw: Boolean value indicating that the photo may contain not-safe-for-work
          content or content not suitable for minors.'
      - in: query
        name: 'privacy: Integer value indicating that the photo should be shown (0)
          or hidden (1) on the users profile.'
      - in: query
        name: 'remove_tags: Comma-separated list of tags to remove from this photos
          existing tags.'
      - in: query
        name: 'shutter_speed: Shutter speed value for the photo, internally stored
          as string.'
      - in: query
        name: 'tags: Comma-separated list of tags applicable to this photo.'
      responses:
        200:
          description: OK
      tags:
      - Photos
  /photos/:id/comments:
    get:
      summary: Get Photos Comments
      description: Returns a listing of twenty comments for the photo.
      operationId: getPhotosComments
      x-api-path-slug: photosidcomments-get
      parameters:
      - in: query
        name: id (required)
        description: The Photo ID to get comments for
      - in: query
        name: nested - Include this parameter to return the comments in nested format.
      - in: query
        name: page
        description: Return a specific page in the comment listing
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Comments
    post:
      summary: Post Photos Comments
      description: Creates a new comment for the photo.
      operationId: postPhotosComments
      x-api-path-slug: photosidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      - in: query
        name: id (required)
        description: The Photo ID to post comments for
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Comments
  /photos/:id/favorite:
    delete:
      summary: Delete Photos Favorite
      description: Removes the photo to users list of favorites.
      operationId: deletePhotosFavorite
      x-api-path-slug: photosidfavorite-delete
      parameters:
      - in: query
        name: id (required)
        description: ID of the photo to delete from list of favorites
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorite
    post:
      summary: Post Photos Favorite
      description: Adds the photo to users list of favorites.
      operationId: postPhotosFavorite
      x-api-path-slug: photosidfavorite-post
      parameters:
      - in: query
        name: id (required)
        description: ID of the photo the favorite is cast upon
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorite
  /photos/:id/favorites:
    get:
      summary: Get Photos Favorites
      description: Returns all users that had favorite that photo.
      operationId: getPhotosFavorites
      x-api-path-slug: photosidfavorites-get
      parameters:
      - in: query
        name: page
        description: Return a specific page in the photo stream
      - in: query
        name: rpp
        description: The number of results to return
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorites
  /photos/:id/report:
    post:
      summary: Post Photos Report
      description: Allows to report a photo.
      operationId: postPhotosReport
      x-api-path-slug: photosidreport-post
      parameters:
      - in: query
        name: id (required)
        description: ID of the photo to report
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Report
  /photos/:id/tags:
    delete:
      summary: Delete Photos Tags
      description: Removes tags from the photo. Accepts one or multiple coma separated
        tags.
      operationId: deletePhotosTags
      x-api-path-slug: photosidtags-delete
      parameters:
      - in: query
        name: id (required)
        description: The Photo ID to remove tags from
      - in: query
        name: tags (required)
        description: Coma separated tags
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Tags
    post:
      summary: Post Photos Tags
      description: Adds tags to the photo. Accepts one or multiple coma separated
        tags.
      operationId: postPhotosTags
      x-api-path-slug: photosidtags-post
      parameters:
      - in: query
        name: id (required)
        description: The Photo ID to add tags for
      - in: query
        name: tags (required)
        description: Coma separated tags
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Tags
  /photos/:id/vote:
    post:
      summary: Post Photos Vote
      description: Allows the user to vote for a photo.
      operationId: postPhotosVote
      x-api-path-slug: photosidvote-post
      parameters:
      - in: query
        name: id (required)
        description: ID of the photo the vote is cast upon
      - in: query
        name: vote (required)
        description: 'vote, values: 0 for dislike or 1 for like'
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Vote
  /photos/:id/votes:
    get:
      summary: Get Photos Votes
      description: Returns all users that had liked this photo.
      operationId: getPhotosVotes
      x-api-path-slug: photosidvotes-get
      parameters:
      - in: query
        name: page
        description: Return a specific page in the photo stream
      - in: query
        name: rpp
        description: The number of results to return
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Votes
  /photos/search:
    get:
      summary: Get Photos Search
      description: Returns a listing of twenty (up to one hundred) photos from search
        results for a specified tag, keyword, or location.
      operationId: getPhotosSearch
      x-api-path-slug: photossearch-get
      parameters:
      - in: query
        name: comments_count u2014u00a0Sort by the number of comments, most commented
          first.
      - in: query
        name: created_at
        description: 'Default: sort by time of upload, most recent first'
      - in: query
        name: exclude
        description: String name of the category to exclude from the results
      - in: query
        name: favorites_count
        description: Sort by the number of favorites, most favorited first
      - in: query
        name: geo
        description: A geo-location point of the format latitude,longitude,radius&lt;units&gt;
      - in: query
        name: highest_rating
        description: Sort by highest rating achieved, highest rated first
      - in: query
        name: image_size
        description: The photo size to be returned
      - in: query
        name: 'license_type -- Restrict the results to one or more license types.  Multiple
          types can be separated with a comma: license_type=1,4.'
      - in: query
        name: only
        description: String name of the category to return photos from
      - in: query
        name: page
        description: Return a specific page
      - in: query
        name: rating
        description: Sort by current rating, highest rated first
      - in: query
        name: rpp
        description: The number of results to return
      - in: query
        name: sort u2014u00a0Sort photos in the specified order. The following values
          are recognized:nnnn_score
        description: Sort by query score, best match first
      - in: query
        name: tag
        description: A complete tag string to search for
      - in: query
        name: tags
        description: Returns an array of tags for each photo
      - in: query
        name: taken_at u2014u00a0Sort by the original date of the image extracted
          from metadata, most recent first (might not be available for all images).
      - in: query
        name: term
        description: A keyword to search for
      - in: query
        name: times_viewed u2014u00a0Sort by the number of views, most viewed first.
      - in: query
        name: votes_count u2013 Sort by the number of votes, most voted on first.
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Search
  /photos/upload:
    post:
      summary: Post Photos Upload
      description: This is a new photo upload endpoint. It is currently in beta.nCreate
        a new photo on behalf of the user and upload a file.nfile parameter is passed
        in multipart/form-data, other parameters are passed as query parametrs or
        multipart/form-data.
      operationId: postPhotosUpload
      x-api-path-slug: photosupload-post
      parameters:
      - in: query
        name: aperture
        description: Aperture value
      - in: query
        name: camera
        description: Make and model of the camera
      - in: query
        name: category
        description: A numerical ID for the Category of the photo
      - in: query
        name: description
        description: Description for the photo
      - in: query
        name: file
        description: The multipart HTTP upload
      - in: query
        name: file (required)  - Photo filename in JPG/JPEG, passed along with multipart/form-data.
      - in: query
        name: focal_length
        description: Focal length in millimetres, a string representing an integer
          value
      - in: query
        name: iso
        description: ISO value
      - in: query
        name: latitude
        description: Latitude, in decimal format
      - in: query
        name: lens
        description: Lens used to make this photo
      - in: query
        name: longitude
        description: Longitude, in decimal format
      - in: query
        name: name
        description: Title of the photo
      - in: query
        name: privacy
        description: Whether to hide the photo from the user profile on the website
      - in: query
        name: shutter_speed
        description: Shutter speed in seconds, represented by string containing a
          rational expression if the value is 1sec
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Upload
  /upload:
    post:
      summary: Post Upload
      description: Allows an application to upload the photo file.nnNote that this
        endpoint is at the upload.500px.com domain, not the api.500px.com domain.
      operationId: postUpload
      x-api-path-slug: upload-post
      parameters:
      - in: query
        name: access_key
        description: Oauth token
      - in: query
        name: consumer_key
        description: Your application Consumer key
      - in: query
        name: file
        description: The multipart HTTP upload
      - in: query
        name: photo_id
        description: The ID of the photo the file is being uploaded for
      - in: query
        name: upload_key
        description: Upload key
      responses:
        200:
          description: OK
      tags:
      - Upload
  /users:
    get:
      summary: Get Users
      description: Returns the profile information for the current user.
      operationId: getUsers
      x-api-path-slug: users-get
      responses:
        200:
          description: OK
      tags:
      - Users
  /users/:id/followers:
    get:
      summary: Get Users Followers
      description: Returns a list of users who follow the specified user.
      operationId: getUsersFollowers
      x-api-path-slug: usersidfollowers-get
      parameters:
      - in: query
        name: id (required)
        description: ID of the user
      - in: query
        name: page
        description: Return the specified page of the resource
      - in: query
        name: rpp
        description: Results Per Page, default 20, max 100
      responses:
        200:
          description: OK
      tags:
      - Users
      - Followers
  /users/:id/friends:
    delete:
      summary: Delete Users Friends
      description: Removes the user from the list of followers.
      operationId: deleteUsersFriends
      x-api-path-slug: usersidfriends-delete
      parameters:
      - in: query
        name: id (required)
        description: ID of the User to remove from the followers list
      responses:
        200:
          description: OK
      tags:
      - Users
      - Friends
    get:
      summary: Get Users Friends
      description: Returns a list of friends for the specified user.
      operationId: getUsersFriends
      x-api-path-slug: usersidfriends-get
      parameters:
      - in: query
        name: id (required)
        description: Return information for the specified user ID
      - in: query
        name: page
        description: Return the specified page of the resource
      - in: query
        name: rpp
        description: Results Per Page, default 20, max 100
      responses:
        200:
          description: OK
      tags:
      - Users
      - Friends
    post:
      summary: Post Users Friends
      description: Add the user to the list of followers.
      operationId: postUsersFriends
      x-api-path-slug: usersidfriends-post
      parameters:
      - in: query
        name: id (required)
        description: ID of the User to add to the followers list
      responses:
        200:
          description: OK
      tags:
      - Users
      - Friends
  /users/search:
    get:
      summary: Get Users Search
      description: Return listing of ten (up to one hundred) users from search results
        for a specified search term.
      operationId: getUsersSearch
      x-api-path-slug: userssearch-get
      parameters:
      - in: query
        name: page
        description: Return the specified page of the resource
      - in: query
        name: rpp
        description: Results Per Page, default 20, max 100
      - in: query
        name: term
        description: A keyword to search for
      - in: query
        name: term (required)
        description: A keyword to search for
      responses:
        200:
          description: OK
      tags:
      - Users
      - Search
  /users/show:
    get:
      summary: Get Users Show
      description: Returns the profile information for a specified user.
      operationId: getUsersShow
      x-api-path-slug: usersshow-get
      parameters:
      - in: query
        name: email
        description: Return information for the user with the specified email address
      - in: query
        name: id
        description: Return information for the specified user ID
      - in: query
        name: username
        description: Return information for the user with the specified username
      responses:
        200:
          description: OK
      tags:
      - Users
      - Show
  /photos/{id}:
    get:
      summary: Get Photos
      description: Returns detailed information of a single photo.
      operationId: getPhotos
      x-api-path-slug: photosid-get
      parameters:
      - in: query
        name: comments
        description: Return comments to the photo in the response
      - in: query
        name: comments_page
        description: Return the specified page from the comments listing
      - in: path
        name: id
        description: The Photo ID
      - in: query
        name: image_size
        description: The photo size to be returned
      - in: query
        name: tags
        description: Returns an array of tags for the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
    put:
      summary: Put Photos
      description: Updates a photo.
      operationId: putPhotos
      x-api-path-slug: photosid-put
      parameters:
      - in: query
        name: description
        description: The description of the photo
      - in: path
        name: id
        description: The Photo ID
      - in: query
        name: name
        description: Title for the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
    delete:
      summary: Delete Photos
      description: Deletes the photo from the User's library.
      operationId: deletePhotos
      x-api-path-slug: photosid-delete
      parameters:
      - in: path
        name: id
        description: The Photo ID to delete
      responses:
        200:
          description: OK
      tags:
      - Photos
  /photos/{id}/comments:
    get:
      summary: Get Photos Comments
      description: Returns a listing of twenty comments for the photo.
      operationId: getPhotosComments
      x-api-path-slug: photosidcomments-get
      parameters:
      - in: path
        name: id
        description: The Photo ID
      - in: query
        name: page
        description: Return a specific page in the comment listing
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Comments
    post:
      summary: Post Photos Comments
      description: Creates a new comment for the photo.
      operationId: postPhotosComments
      x-api-path-slug: photosidcomments-post
      parameters:
      - in: query
        name: body
        description: Content of the comment
      - in: path
        name: id
        description: The Photo ID to post comments for
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Comments
  /photos/{id}/favorite:
    get:
      summary: Get Photos Favorite
      description: Deletes the photo from User's favorite list.
      operationId: getPhotosFavorite
      x-api-path-slug: photosidfavorite-get
      parameters:
      - in: path
        name: id
        description: The Photo ID
      - in: query
        name: page
        description: Return a specific page in the comment listing
      - in: query
        name: rpp
        description: The number of results to return
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorite
    post:
      summary: Post Photos Favorite
      description: Adds the photo to user's list of favorites.
      operationId: postPhotosFavorite
      x-api-path-slug: photosidfavorite-post
      parameters:
      - in: path
        name: id
        description: ID of the photo the favorite is cast upon
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorite
    delete:
      summary: Delete Photos Favorite
      description: Removes the photo to user's list of favorites.
      operationId: deletePhotosFavorite
      x-api-path-slug: photosidfavorite-delete
      parameters:
      - in: path
        name: id
        description: ID of the photo to delete from list of favorites
      responses:
        200:
          description: OK
      tags:
      - Photos
      - Favorite
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---