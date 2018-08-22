{
  "info": {
    "name": "500px Post Collections",
    "_postman_id": "7def2da6-4238-4a5f-a7b0-efe48a569b90",
    "description": "Creates new a collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Blogs",
      "item": [
        {
          "id": "906e69cb-a2ba-4236-9d90-9adb3f75aa45",
          "name": "getBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs/?feature=%7B%7D&feature (required)=%7B%7D&page=%7B%7D&rpp=%7B%7D&user=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of five recent stories (maximum 100 per page)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd803b64-0d98-4a92-8667-fb69f8215140"
            }
          ]
        },
        {
          "id": "20d7681f-f55d-4a56-aa77-730e391e8b24",
          "name": "postBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs/?body (required)=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&photo_ids=%7B%7D&tags=%7B%7D&title (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "beeffdc4-ee78-43b3-9618-d01a074f2d30"
            }
          ]
        },
        {
          "id": "182168f0-f1c8-4423-bdc8-c55c5e65b2ca",
          "name": "getBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs/:id?id (required) - Return information for the specific story.=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns detailed information of a single story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4673e4f-4696-4b0c-9fb3-25193f79df36"
            }
          ]
        },
        {
          "id": "9fb1e7af-adab-499e-824c-1fb388799854",
          "name": "putBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs/:id?body=%7B%7D&id (required)=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&photo_ids=%7B%7D&tags=%7B%7D&title=%7B%7D",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the Story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0d99509-3ea1-4d02-8421-9f2d76d3b94e"
            }
          ]
        },
        {
          "id": "80c6fc8e-defd-4ce0-b6f0-febef15ef7dc",
          "name": "deleteBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs/:id?id (required)=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bc7c3d9-050c-4b22-9aa8-6bf970420d8e"
            }
          ]
        },
        {
          "id": "59ae6d15-606e-48cb-9d20-2d456fd585c9",
          "name": "getBlogsComments",
          "request": {
            "url": "http://api.500px.com/v1/blogs/:id/comments?id (required)=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of twenty comments for a specific Story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef5d43fd-6ea6-4f62-badd-b8f1aa23ef31"
            }
          ]
        },
        {
          "id": "0b0c20b9-1b20-4fcf-afe9-126d79b4f79b",
          "name": "postBlogsComments",
          "request": {
            "url": "http://api.500px.com/v1/blogs/:id/comments?body (required)=%7B%7D&id (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a comment for the Story."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11c3bcf1-bc7f-4fe0-b76e-e861d02f21c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Collections",
      "item": [
        {
          "id": "28355938-406c-4a30-b656-12835a09d7db",
          "name": "getCollections",
          "request": {
            "url": "http://api.500px.com/v1/collections?photos_per_collection_limit=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of all Users collections and sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef52e431-b6e9-4cb1-bb99-e09cae01b6dc"
            }
          ]
        },
        {
          "id": "4f7a6170-59cc-4b5a-b059-6d2b5fe8d3c4",
          "name": "postCollections",
          "request": {
            "url": "http://api.500px.com/v1/collections?kind=%7B%7D&path=%7B%7D&path (required)=%7B%7D&photo_ids=%7B%7D&position=%7B%7D&title=%7B%7D&title (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates new a collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85e085f8-80f8-48f0-b167-2a61c5b441e3"
            }
          ]
        }
      ]
    }
  ]
}