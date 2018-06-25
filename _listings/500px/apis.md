---
name: 500px
x-slug: 500px
description: Connect, get inspired, and grow your skills.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
x-kinRank: "7"
x-alexaRank: "2275"
tags: 500px
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/apis.md
specificationVersion: "0.14"
apis:
- name: 500px Get Blogs
  x-api-slug: 500px
  description: Returns a listing of five recent stories (maximum 100 per page).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-get-openapi.md
- name: 500px Post Blogs
  x-api-slug: 500px
  description: Creates a new Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-post-openapi.md
- name: 500px Delete Blogs
  x-api-slug: 500px
  description: Deletes the story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/:id
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-delete-openapi.md
- name: 500px Get Blogs
  x-api-slug: 500px
  description: Returns detailed information of a single story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/:id
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-get-openapi.md
- name: 500px Put Blogs
  x-api-slug: 500px
  description: Updates the Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/:id
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-put-openapi.md
- name: 500px Get Blogs Comments
  x-api-slug: 500px
  description: Returns a listing of twenty comments for a specific Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/:id/comments
  tags: Blogs,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-get-openapi.md
- name: 500px Post Blogs Comments
  x-api-slug: 500px
  description: Creates a comment for the Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/:id/comments
  tags: Blogs,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-post-openapi.md
- name: 500px Get Collections
  x-api-slug: 500px
  description: Returns a listing of all Users collections and sets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collections-get-openapi.md
- name: 500px Post Collections
  x-api-slug: 500px
  description: Creates new a collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collections-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collections-post-openapi.md
- name: 500px Delete Collections
  x-api-slug: 500px
  description: Deletes collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/:id
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-delete-openapi.md
- name: 500px Get Collections
  x-api-slug: 500px
  description: Returns a collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/:id
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-get-openapi.md
- name: 500px Put Collections
  x-api-slug: 500px
  description: Updates collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/:id
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-put-openapi.md
- name: 500px Post Comments Comments
  x-api-slug: 500px
  description: Creates a reply to an existing comment. Comments can only be nested
    one level deep, you cannot reply to a reply of a comment. If a comment has a non-null
    parent_id value then it cannot be replied to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///comments/:id/comments
  tags: Comments,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/commentsidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/commentsidcomments-post-openapi.md
- name: 500px Get Photos
  x-api-slug: 500px
  description: Returns a listing of twenty (up to one hundred) photos for a specified
    photo stream.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photos-get-openapi.md
- name: 500px Post Photos
  x-api-slug: 500px
  description: Create a new photo on behalf of the user, and receive an upload key
    in exchange.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photos-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photos-post-openapi.md
- name: 500px Delete Photos
  x-api-slug: 500px
  description: Deletes the photo from the Users library.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-delete-openapi.md
- name: 500px Get Photos
  x-api-slug: 500px
  description: Returns detailed information of a single photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-get-openapi.md
- name: 500px Put Photos
  x-api-slug: 500px
  description: 'Allows the client application to update user-editable information
    on a photo.nnnResource URLnnhttps://api.500px.com/v1/photos/:idnnnnAuthenticationnnRequired;
    OAuth. The client application must use the OAuth access token issued for the owner
    of the photo to access this resouce.nnnParametersnnThe application must provide
    the ID of the photo to update in the URL of the request. The following parameters
    are recognized when included in the query string or POST body:nnnnname: Title
    of the photo, up to 255 characters in length.nndescription: Text description of
    the photo, up to 65535 characters in length.nncategory: Integer number of the
    category of the photo. See category mapping for exact values.nntags: Comma-separated
    list of tags applicable to this photo.nnadd_tags: Comma-separated list of tags
    to add to this photos existing tags.nnremove_tags: Comma-separated list of tags
    to remove from this photos existing tags.nnshutter_speed: Shutter speed value
    for the photo, internally stored as string.nnfocal_length: Focal length value
    for the photo, internally stored as string.nnaperture: Aperture value value for
    the photo, internally stored as string.nniso: Integer ISO value for the photo.nncamera:
    Make and model of the camera used to take this photo.nnlens: Information about
    the lens used to take this photo.nnlatitude: Latitude of the location this photo
    was taken at represented by a decimal number.nnlongitude: Longitude of the location
    this photo was taken at represented by a decimal number.nnnsfw: Boolean value
    indicating that the photo may contain not-safe-for-work content or content not
    suitable for minors.nnlicense_type: Integer number of the license type chosen
    for this photo. See license type mapping for exact values.nnprivacy: Integer value
    indicating that the photo should be shown (0) or hidden (1) on the users profile.nncrop:
    A hash containing keys x, x2, y, y2 and representing coordinates within which
    the thumbnail must be cropped. The crop is made using the top left corner as the
    origin. The points must be given relative to image size 4, an image of at most
    900px on the larger side. The client application may skip this if the user does
    not wish to change photo thumbnail.nnnnImplementation detailsnnA parameter missing
    from the request will not be updated.  A parameter set to an empty string or null
    value will be interpreted as the user wishing to reset the value of the field
    to its default value.nnYou can use the add_tags and remove_tags parameters to
    manupulate a photos tags without having to send the complete list of tags in the
    request.nnnReturn formatnnA JSON object containing key photo, where photo is a
    Photo object in full format.nnnErrorsnnAll known errors cause the resource to
    return HTTP error code header together with a JSON array containing at least status
    and error keys describing the source of error.nnnn401: Invalid OAuth request:
    The request was refused because the OAuth signature is incorrect.nn404: Photo
    with ID not found: The photo ID provided is not known to the system.nn404: Photo
    with ID has been deleted: The photo has been deleted and can not be edited.nn404:
    Photo with ID belongs to a deactivated user: The photo belongs to a user that
    is no longer active and can not be edited.nn400: Bad photo category: An unrecognized
    photo category value has been provided.nn400: Bad license type: An unrecognized
    license type value has been provided.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-put-openapi.md
- name: 500px Get Photos Comments
  x-api-slug: 500px
  description: Returns a listing of twenty comments for the photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/comments
  tags: Photos,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-get-openapi.md
- name: 500px Post Photos Comments
  x-api-slug: 500px
  description: Creates a new comment for the photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/comments
  tags: Photos,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-post-openapi.md
- name: 500px Delete Photos Favorite
  x-api-slug: 500px
  description: Removes the photo to users list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/favorite
  tags: Photos,Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-delete-openapi.md
- name: 500px Post Photos Favorite
  x-api-slug: 500px
  description: Adds the photo to users list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/favorite
  tags: Photos,Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-post-openapi.md
- name: 500px Get Photos Favorites
  x-api-slug: 500px
  description: Returns all users that had favorite that photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/favorites
  tags: Photos,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorites-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorites-get-openapi.md
- name: 500px Post Photos Report
  x-api-slug: 500px
  description: Allows to report a photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/report
  tags: Photos,Report
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidreport-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidreport-post-openapi.md
- name: 500px Delete Photos Tags
  x-api-slug: 500px
  description: Removes tags from the photo. Accepts one or multiple coma separated
    tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/tags
  tags: Photos,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-delete-openapi.md
- name: 500px Post Photos Tags
  x-api-slug: 500px
  description: Adds tags to the photo. Accepts one or multiple coma separated tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/tags
  tags: Photos,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-post-openapi.md
- name: 500px Post Photos Vote
  x-api-slug: 500px
  description: Allows the user to vote for a photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/vote
  tags: Photos,Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvote-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvote-post-openapi.md
- name: 500px Get Photos Votes
  x-api-slug: 500px
  description: Returns all users that had liked this photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/:id/votes
  tags: Photos,Votes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvotes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvotes-get-openapi.md
- name: 500px Get Photos Search
  x-api-slug: 500px
  description: Returns a listing of twenty (up to one hundred) photos from search
    results for a specified tag, keyword, or location.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/search
  tags: Photos,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photossearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photossearch-get-openapi.md
- name: 500px Post Photos Upload
  x-api-slug: 500px
  description: This is a new photo upload endpoint. It is currently in beta.nCreate
    a new photo on behalf of the user and upload a file.nfile parameter is passed
    in multipart/form-data, other parameters are passed as query parametrs or multipart/form-data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/upload
  tags: Photos,Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosupload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosupload-post-openapi.md
- name: 500px Post Upload
  x-api-slug: 500px
  description: Allows an application to upload the photo file.nnNote that this endpoint
    is at the upload.500px.com domain, not the api.500px.com domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///upload
  tags: Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/upload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/upload-post-openapi.md
- name: 500px Get Users
  x-api-slug: 500px
  description: Returns the profile information for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/users-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/users-get-openapi.md
- name: 500px Get Users Followers
  x-api-slug: 500px
  description: Returns a list of users who follow the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/:id/followers
  tags: Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfollowers-get-openapi.md
- name: 500px Delete Users Friends
  x-api-slug: 500px
  description: Removes the user from the list of followers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/:id/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-delete-openapi.md
- name: 500px Get Users Friends
  x-api-slug: 500px
  description: Returns a list of friends for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/:id/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-get-openapi.md
- name: 500px Post Users Friends
  x-api-slug: 500px
  description: Add the user to the list of followers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/:id/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-post-openapi.md
- name: 500px Get Users Search
  x-api-slug: 500px
  description: Return listing of ten (up to one hundred) users from search results
    for a specified search term.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/search
  tags: Users,Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/userssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/userssearch-get-openapi.md
- name: 500px Get Users Show
  x-api-slug: 500px
  description: Returns the profile information for a specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/show
  tags: Users,Show
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersshow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersshow-get-openapi.md
- name: 500px Get Photos
  x-api-slug: 500px
  description: Returns detailed information of a single photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-get-openapi.md
- name: 500px Put Photos
  x-api-slug: 500px
  description: Updates a photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-put-openapi.md
- name: 500px Delete Photos
  x-api-slug: 500px
  description: Deletes the photo from the User's library.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}
  tags: Photos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosid-delete-openapi.md
- name: 500px Get Photos Comments
  x-api-slug: 500px
  description: Returns a listing of twenty comments for the photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/comments
  tags: Photos,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-get-openapi.md
- name: 500px Post Photos Comments
  x-api-slug: 500px
  description: Creates a new comment for the photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/comments
  tags: Photos,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidcomments-post-openapi.md
- name: 500px Get Photos Favorite
  x-api-slug: 500px
  description: Deletes the photo from User's favorite list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/favorite
  tags: Photos,Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-get-openapi.md
- name: 500px Post Photos Favorite
  x-api-slug: 500px
  description: Adds the photo to user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/favorite
  tags: Photos,Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-post-openapi.md
- name: 500px Delete Photos Favorite
  x-api-slug: 500px
  description: Removes the photo to user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/favorite
  tags: Photos,Favorite
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidfavorite-delete-openapi.md
- name: 500px Get Photos Votes
  x-api-slug: 500px
  description: Deletes the photo from User's favorite list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/votes
  tags: Photos,Votes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvotes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvotes-get-openapi.md
- name: 500px Post Photos Vote
  x-api-slug: 500px
  description: Allows the user to vote for a photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/vote
  tags: Photos,Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvote-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidvote-post-openapi.md
- name: 500px Post Photos Tags
  x-api-slug: 500px
  description: Adds tags to the photo. Accepts one or multiple coma separated tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/tags
  tags: Photos,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-post-openapi.md
- name: 500px Delete Photos Tags
  x-api-slug: 500px
  description: Removes tags from the photo. Accepts one or multiple coma separated
    tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///photos/{id}/tags
  tags: Photos,Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/photosidtags-delete-openapi.md
- name: 500px Get Users Friends
  x-api-slug: 500px
  description: Returns a list of friends for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/{id}/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-get-openapi.md
- name: 500px Post Users Friends
  x-api-slug: 500px
  description: Add the user to the list of followers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/{id}/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-post-openapi.md
- name: 500px Delete Users Friends
  x-api-slug: 500px
  description: Removes the user from the list of followers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/{id}/friends
  tags: Users,Friends
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfriends-delete-openapi.md
- name: 500px Get Users Followers
  x-api-slug: 500px
  description: Returns a list of users who follow the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///users/{id}/followers
  tags: Users,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/usersidfollowers-get-openapi.md
- name: 500px Get Blogs
  x-api-slug: 500px
  description: Returns a listing of five recent (blogs) stories (maximum 100 per page).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-get-openapi.md
- name: 500px Post Blogs
  x-api-slug: 500px
  description: Creates a new Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogs-post-openapi.md
- name: 500px Get Blogs
  x-api-slug: 500px
  description: Returns detailed information of a single story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/{id}
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-get-openapi.md
- name: 500px Put Blogs
  x-api-slug: 500px
  description: Creates a new Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/{id}
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-put-openapi.md
- name: 500px Delete Blogs
  x-api-slug: 500px
  description: Deletes the story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/{id}
  tags: Blogs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsid-delete-openapi.md
- name: 500px Get Blogs Comments
  x-api-slug: 500px
  description: Returns a listing of twenty comments for a specific Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/{id}/comments
  tags: Blogs,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-get-openapi.md
- name: 500px Post Blogs Comments
  x-api-slug: 500px
  description: Creates a comment for the Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///blogs/{id}/comments
  tags: Blogs,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/blogsidcomments-post-openapi.md
- name: 500px Get Collections
  x-api-slug: 500px
  description: Returns the collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/{id}
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-get-openapi.md
- name: 500px Put Collections
  x-api-slug: 500px
  description: Updates collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/{id}
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-put-openapi.md
- name: 500px Delete Collections
  x-api-slug: 500px
  description: Deletes the collection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1///collections/{id}
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/collectionsid-delete-openapi.md
- name: 500px
  x-api-slug: 500px
  description: 500px is a photographic community powered by creative people from all
    over the world that lets you share and discover inspiring photographs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/291-500px.jpg
  humanURL: http://500px.com
  baseURL: http://api.500px.com//v1/
  tags: 500px
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/500px/master/_listings/500px/openapi.md
x-common:
- type: x-android-sdk
  url: https://github.com/500px/500px-android-sdk
- type: x-application-management
  url: https://500px.com/settings/applications
- type: x-base
  url: https://api.500px.com
- type: x-console
  url: https://apigee.com/vova/embed/console/api500px
- type: x-crunchbase
  url: http://www.crunchbase.com/company/500px
- type: x-crunchbase
  url: https://crunchbase.com/organization/500px
- type: x-developer
  url: http://developers.500px.com/
- type: x-github
  url: https://github.com/500px
- type: x-ios-sdk
  url: https://github.com/500px/500px-iOS-api
- type: x-meetups
  url: http://www.meetup.com/500px/
- type: x-php-library
  url: https://github.com/500px/api-documentation/blob/master/examples/PHP/PHP.md
- type: x-pricing
  url: https://marketplace.500px.com/pricing
- type: x-privacy
  url: https://500px.com/privacy
- type: x-python-library
  url: https://github.com/500px/PxMagic
- type: x-ruby-library
  url: https://github.com/500px/api-documentation/blob/master/examples/Ruby/xauth.rb
- type: x-selfservice-registration
  url: https://500px.com/login?r=%2Fsettings%2Fapplications%3Ffrom%3Ddevelopers
- type: x-terms-of-service
  url: https://github.com/500px/api-documentation/blob/master/basics/terms_of_use.md
- type: x-twitter
  url: https://twitter.com/500px
- type: x-website
  url: http://500px.com
- type: x-website
  url: https://www.youtube.com
- type: x-website
  url: http://youtube.com
- type: x-website
  url: http://500px.com/
- type: x-youtube
  url: http://www.youtube.com/user/the500px
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---