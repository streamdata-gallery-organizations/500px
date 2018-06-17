---
swagger: "2.0"
x-collection-name: 500px
x-complete: 0
info:
  title: 500px Get Photos
  description: Returns a listing of twenty (up to one hundred) photos for a specified
    photo stream.
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