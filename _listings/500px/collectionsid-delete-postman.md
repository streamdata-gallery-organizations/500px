{
  "info": {
    "name": "500px Delete Collections",
    "_postman_id": "ea10f507-dc50-4b1f-88ee-f5e6d11d1cd5",
    "description": "Deletes the collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Blogs",
      "item": [
        {
          "id": "268d7801-b1b2-49ed-a088-c126e3e1ad35",
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
              "id": "cd0a1a24-687e-4852-bdce-7eaa8320cc58"
            }
          ]
        },
        {
          "id": "43f5aafe-fef5-4e6e-b998-a06339e013cf",
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
              "id": "44794195-a95a-460d-85b6-0a0b76d7ac28"
            }
          ]
        },
        {
          "id": "0df79e76-248d-478a-a83b-e9bb90e2806b",
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
              "id": "be6243ff-e09d-4778-a6e7-9b729cd2f8b9"
            }
          ]
        },
        {
          "id": "a4a26373-db4f-472a-890b-f2c4dc78f6e9",
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
              "id": "6e70f880-09c4-47d5-9ba1-19ba4e9a450e"
            }
          ]
        },
        {
          "id": "f68f120e-a232-43ea-a4c1-196025021c93",
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
              "id": "60331de3-3c8b-4eed-9334-2e737600d999"
            }
          ]
        },
        {
          "id": "b354b713-8b50-4796-ba6e-965cd6a44ab1",
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
              "id": "66328c1d-9210-4717-910e-c2a08aab3e4f"
            }
          ]
        },
        {
          "id": "ff60b1f8-b341-4816-9e9c-9225d961ba3d",
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
              "id": "1b8cc351-5479-406a-a8c0-480c2fcf0b23"
            }
          ]
        },
        {
          "id": "c6c0969f-80ff-4b76-88f5-f92c55f1b6d3",
          "name": "getBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs?feature=%7B%7D&page=%7B%7D&rpp=%7B%7D&username=%7B%7D&user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of five recent (blogs) stories (maximum 100 per page)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a055e9d-164b-4f81-957e-a3e0ecf9a09d"
            }
          ]
        },
        {
          "id": "29350a80-f842-466f-8f50-cc051d2c0f79",
          "name": "postBlogs",
          "request": {
            "url": "http://api.500px.com/v1/blogs?body=%7B%7D&latitude=%7B%7D&longitude=%7B%7D&photo_ids=%7B%7D&tags=%7B%7D&title=%7B%7D",
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
              "id": "9e38d0d2-b41a-46cf-b1b8-a5753b85af1d"
            }
          ]
        },
        {
          "id": "f10e0405-1187-4076-9916-aca87c0cf7d6",
          "name": "getBlogs",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "blogs/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
              "id": "3bbc3789-9f6b-457f-9b8a-2dacc55f4838"
            }
          ]
        },
        {
          "id": "e759cb7f-e11e-4eeb-9f1d-c52d619ffca3",
          "name": "putBlogs",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "blogs/:id"
              ],
              "query": [
                {
                  "key": "body",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "latitude",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "longitude",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "photo_ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "title",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
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
              "id": "935d67b1-e906-4e64-bad4-e001486c5c7b"
            }
          ]
        },
        {
          "id": "a258b1bd-e4e6-45d7-9e51-821de9bc3da8",
          "name": "deleteBlogs",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "blogs/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
              "id": "c02331b8-d753-41d3-8daa-03027c33af95"
            }
          ]
        },
        {
          "id": "da317636-0b15-43b5-935d-fd384f29b2a2",
          "name": "getBlogsComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "blogs/:id/comments"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
              "id": "3e1fc1d4-6744-4991-b0ab-f70b379c776b"
            }
          ]
        },
        {
          "id": "f3c88dfd-48cf-4342-9597-9a24edb7d326",
          "name": "postBlogsComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "blogs/:id/comments"
              ],
              "query": [
                {
                  "key": "body",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
              "id": "f23c411b-5cb8-43c1-8ecf-aef04a476ef5"
            }
          ]
        }
      ]
    },
    {
      "name": "Collections",
      "item": [
        {
          "id": "7e2592a6-c01f-44c8-a0ad-c67e0b8fcacf",
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
              "id": "060c5582-dc9f-46e2-a8b4-583c9a8b9229"
            }
          ]
        },
        {
          "id": "766af50e-b8ef-410e-b09c-e4313a246bd8",
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
              "id": "81f3dcb3-2774-4134-81cf-dae6781902d7"
            }
          ]
        },
        {
          "id": "02cb2dcb-be67-4799-b197-f3a8f6075ee9",
          "name": "getCollections",
          "request": {
            "url": "http://api.500px.com/v1/collections/:id?image_size - Numerical size of the image to link to, 1 being the smallest and 4 being the largest. Multiple image sizes may be specified as image_size[]=2&amp;image_size[]=4.=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aaf25b9c-6a34-4f35-81d1-b1a2fe46e0bd"
            }
          ]
        },
        {
          "id": "20a762f7-3bdf-4422-bdff-2744d5ecd575",
          "name": "putCollections",
          "request": {
            "url": "http://api.500px.com/v1/collections/:id?id (required)=%7B%7D&kind=%7B%7D&path=%7B%7D&photo_ids=%7B%7D&position=%7B%7D&title=%7B%7D",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09baf1ef-37a4-4ac6-9567-75d91fa5c06b"
            }
          ]
        },
        {
          "id": "c87256fb-0f03-4258-8644-80d4b36d47a9",
          "name": "deleteCollections",
          "request": {
            "url": "http://api.500px.com/v1/collections/:id?Forkn      n      n        69=%7B%7D&Starn  nn    n      281=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cbce460-ed1b-414c-a604-bba9d2a01341"
            }
          ]
        },
        {
          "id": "37aba4e0-b3bd-44ee-8930-5b562a1cd5ab",
          "name": "getCollections",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "collections/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2c367c6-dd32-46a0-b1ca-e391eb85aebd"
            }
          ]
        },
        {
          "id": "86ca03ed-99ba-4ad1-bd8a-91ec29c1a212",
          "name": "putCollections",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "collections/:id"
              ],
              "query": [
                {
                  "key": "kind",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "path",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "photo_ids",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "position",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "title",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fc3671f-a334-4aa8-b2f5-bc7ce9a00d13"
            }
          ]
        },
        {
          "id": "ae7a58bf-00f6-492c-8187-85b389cdc9ba",
          "name": "deleteCollections",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "collections/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96693174-2441-497a-ae20-ffdd22bd6fb7"
            }
          ]
        }
      ]
    },
    {
      "name": "Comments",
      "item": [
        {
          "id": "90e2a60d-516d-46d1-a367-3cb1f433e0c8",
          "name": "postCommentsComments",
          "request": {
            "url": "http://api.500px.com/v1/comments/:id/comments?body (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a reply to an existing comment. Comments can only be nested one level deep, you cannot reply to a reply of a comment. If a comment has a non-null parent_id value then it cannot be replied to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8becdd6f-859e-4b0f-9dcb-c45097ace081"
            }
          ]
        }
      ]
    },
    {
      "name": "Photos",
      "item": [
        {
          "id": "69123079-7a8b-4b75-9ebc-6f75f89eceff",
          "name": "getPhotos",
          "request": {
            "url": "http://api.500px.com/v1/photos?exclude=%7B%7D&feature=%7B%7D&image_size=%7B%7D&include_states=%7B%7D&include_store=%7B%7D&only=%7B%7D&page=%7B%7D&rpp=%7B%7D&sort=%7B%7D&sort_direction=%7B%7D&tags=%7B%7D&username=%7B%7D&user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of twenty (up to one hundred) photos for a specified photo stream."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4ce9fbb-2e1e-444d-a396-1a80810f8c88"
            }
          ]
        },
        {
          "id": "381f13d9-42c0-4141-8ed0-9586e2f17608",
          "name": "postPhotos",
          "request": {
            "url": "http://api.500px.com/v1/photos?aperture=%7B%7D&camera=%7B%7D&category=%7B%7D&description=%7B%7D&focal_length=%7B%7D&iso=%7B%7D&latitude=%7B%7D&lens=%7B%7D&longitude=%7B%7D&name=%7B%7D&privacy=%7B%7D&shutter_speed=%7B%7D&tags=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new photo on behalf of the user, and receive an upload key in exchange."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50869e39-071f-4b9d-846c-6a63700042ae"
            }
          ]
        },
        {
          "id": "e55a00c4-1f43-46ff-904d-95dd603f61ae",
          "name": "getPhotos",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id?comments=%7B%7D&comments_page=%7B%7D&image_size=%7B%7D&tags=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns detailed information of a single photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d82ccba3-c641-4037-a204-24c0b9ff0011"
            }
          ]
        },
        {
          "id": "93b5b923-b33b-4d3d-9a75-bb1b71fce500",
          "name": "putPhotos",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id?add_tags: Comma-separated list of tags to add to this photos existing tags.=%7B%7D&aperture: Aperture value value for the photo, internally stored as string.=%7B%7D&camera: Make and model of the camera used to take this photo.=%7B%7D&category: Integer number of the category of the photo. See category mapping for exact values.=%7B%7D&crop: A hash containing keys x, x2, y, y2 and representing coordinates within which the thumbnail must be cropped. The crop is made using the top left corner as the origin. The points must be given relative to image size 4, an image of at most 900px=%7B%7D&description: Text description of the photo, up to 65535 characters in length.=%7B%7D&focal_length: Focal length value for the photo, internally stored as string.=%7B%7D&iso: Integer ISO value for the photo.=%7B%7D&latitude: Latitude of the location this photo was taken at represented by a decimal number.=%7B%7D&lens: Information about the lens used to take this photo.=%7B%7D&license_type: Integer number of the license type chosen for this photo. See license type mapping for exact values.=%7B%7D&longitude: Longitude of the location this photo was taken at represented by a decimal number.=%7B%7D&name: Title of the photo, up to 255 characters in length.=%7B%7D&nsfw: Boolean value indicating that the photo may contain not-safe-for-work content or content not suitable for minors.=%7B%7D&privacy: Integer value indicating that the photo should be shown (0) or hidden (1) on the users profile.=%7B%7D&remove_tags: Comma-separated list of tags to remove from this photos existing tags.=%7B%7D&shutter_speed: Shutter speed value for the photo, internally stored as string.=%7B%7D&tags: Comma-separated list of tags applicable to this photo.=%7B%7D",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the client application to update user-editable information on a photo.nnnResource URLnnhttps://api.500px.com/v1/photos/:idnnnnAuthenticationnnRequired; OAuth. The client application must use the OAuth access token issued for the owner of the photo to access this resouce.nnnParametersnnThe application must provide the ID of the photo to update in the URL of the request. The following parameters are recognized when included in the query string or POST body:nnnnname: Title of the photo, up to 255 characters in length.nndescription: Text description of the photo, up to 65535 characters in length.nncategory: Integer number of the category of the photo. See category mapping for exact values.nntags: Comma-separated list of tags applicable to this photo.nnadd_tags: Comma-separated list of tags to add to this photos existing tags.nnremove_tags: Comma-separated list of tags to remove from this photos existing tags.nnshutter_speed: Shutter speed value for the photo, internally stored as string.nnfocal_length: Focal length value for the photo, internally stored as string.nnaperture: Aperture value value for the photo, internally stored as string.nniso: Integer ISO value for the photo.nncamera: Make and model of the camera used to take this photo.nnlens: Information about the lens used to take this photo.nnlatitude: Latitude of the location this photo was taken at represented by a decimal number.nnlongitude: Longitude of the location this photo was taken at represented by a decimal number.nnnsfw: Boolean value indicating that the photo may contain not-safe-for-work content or content not suitable for minors.nnlicense_type: Integer number of the license type chosen for this photo. See license type mapping for exact values.nnprivacy: Integer value indicating that the photo should be shown (0) or hidden (1) on the users profile.nncrop: A hash containing keys x, x2, y, y2 and representing coordinates within which the thumbnail must be cropped. The crop is made using the top left corner as the origin. The points must be given relative to image size 4, an image of at most 900px on the larger side. The client application may skip this if the user does not wish to change photo thumbnail.nnnnImplementation detailsnnA parameter missing from the request will not be updated.  A parameter set to an empty string or null value will be interpreted as the user wishing to reset the value of the field to its default value.nnYou can use the add_tags and remove_tags parameters to manupulate a photos tags without having to send the complete list of tags in the request.nnnReturn formatnnA JSON object containing key photo, where photo is a Photo object in full format.nnnErrorsnnAll known errors cause the resource to return HTTP error code header together with a JSON array containing at least status and error keys describing the source of error.nnnn401: Invalid OAuth request: The request was refused because the OAuth signature is incorrect.nn404: Photo with ID not found: The photo ID provided is not known to the system.nn404: Photo with ID has been deleted: The photo has been deleted and can not be edited.nn404: Photo with ID belongs to a deactivated user: The photo belongs to a user that is no longer active and can not be edited.nn400: Bad photo category: An unrecognized photo category value has been provided.nn400: Bad license type: An unrecognized license type value has been provided."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e279e9c-c16f-46e0-ae1d-47e6552aed6e"
            }
          ]
        },
        {
          "id": "1c8331be-09a0-4580-ac86-e16f983f72ba",
          "name": "deletePhotos",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id?id (required)=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the photo from the Users library."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3800859e-ffd7-4cdf-9452-1057bd1819db"
            }
          ]
        },
        {
          "id": "ee81e46c-6226-4082-8fbd-31ebdc6a3e07",
          "name": "getPhotosComments",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/comments?id (required)=%7B%7D&nested - Include this parameter to return the comments in nested format.=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of twenty comments for the photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57ca3df8-af6b-4942-affc-26044e671bb0"
            }
          ]
        },
        {
          "id": "e01f1e0c-5a8f-4e3d-ba31-b8926fe19ac2",
          "name": "postPhotosComments",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/comments?body (required)=%7B%7D&id (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new comment for the photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88e521c2-d475-4c11-8113-2c4cbac86734"
            }
          ]
        },
        {
          "id": "c2370d1c-ef3c-4a90-b583-053d27612d34",
          "name": "postPhotosFavorite",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/favorite?id (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the photo to users list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e10fecaa-bd24-439f-bd81-cc2afda55db8"
            }
          ]
        },
        {
          "id": "061b2cea-a191-4710-982a-c4727267f8e2",
          "name": "deletePhotosFavorite",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/favorite?id (required)=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the photo to users list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d37ac26-edd1-4e88-af19-07266be4547a"
            }
          ]
        },
        {
          "id": "a1bbbcf2-fe8e-4db4-8847-900b24e5136f",
          "name": "getPhotosFavorites",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/favorites?page=%7B%7D&rpp=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all users that had favorite that photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2503efd-311d-451f-b884-3612af129232"
            }
          ]
        },
        {
          "id": "22bb2af5-f00a-44cb-8e1f-b562d2015cd5",
          "name": "postPhotosReport",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/report?id (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Allows to report a photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3e7d487-131d-4fd1-82ba-c3500090aa79"
            }
          ]
        },
        {
          "id": "02aa17ba-5e87-468f-ab34-5c2932f02302",
          "name": "postPhotosTags",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/tags?id (required)=%7B%7D&tags (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds tags to the photo. Accepts one or multiple coma separated tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a20635ae-5340-4b9e-8efe-5066db9ab82b"
            }
          ]
        },
        {
          "id": "15c792a5-26d2-418b-b28d-2f4ae6bd7107",
          "name": "deletePhotosTags",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/tags?id (required)=%7B%7D&tags (required)=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes tags from the photo. Accepts one or multiple coma separated tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5c2b37d-f5a0-440e-a91f-268fe045287d"
            }
          ]
        },
        {
          "id": "48cca647-7f18-4227-81c8-d276234d12ac",
          "name": "postPhotosVote",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/vote?id (required)=%7B%7D&vote (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the user to vote for a photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffaf9130-0db9-4bd0-a26b-8bfbf8a3e368"
            }
          ]
        },
        {
          "id": "a68625e9-458f-4b81-9d03-833bd34faa2f",
          "name": "getPhotosVotes",
          "request": {
            "url": "http://api.500px.com/v1/photos/:id/votes?page=%7B%7D&rpp=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all users that had liked this photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce0b2e4a-9ed1-4483-acbe-834002060156"
            }
          ]
        },
        {
          "id": "7348b3d3-8fdc-4431-9ae2-d956b6954748",
          "name": "getPhotosSearch",
          "request": {
            "url": "http://api.500px.com/v1/photos/search?comments_count u2014u00a0Sort by the number of comments, most commented first.=%7B%7D&created_at=%7B%7D&exclude=%7B%7D&favorites_count=%7B%7D&geo=%7B%7D&highest_rating=%7B%7D&image_size=%7B%7D&license_type -- Restrict the results to one or more license types.  Multiple types can be separated with a comma: license_type=1,4.=%7B%7D&only=%7B%7D&page=%7B%7D&rating=%7B%7D&rpp=%7B%7D&sort u2014u00a0Sort photos in the specified order. The following values are recognized:nnnn_score=%7B%7D&tag=%7B%7D&tags=%7B%7D&taken_at u2014u00a0Sort by the original date of the image extracted from metadata, most recent first (might not be available for all images).=%7B%7D&term=%7B%7D&times_viewed u2014u00a0Sort by the number of views, most viewed first.=%7B%7D&votes_count u2013 Sort by the number of votes, most voted on first.=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of twenty (up to one hundred) photos from search results for a specified tag, keyword, or location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba314620-d7a2-4b79-af9f-093c87681729"
            }
          ]
        },
        {
          "id": "0b8b463a-30a6-48a2-87b0-3718473bec1b",
          "name": "postPhotosUpload",
          "request": {
            "url": "http://api.500px.com/v1/photos/upload?aperture=%7B%7D&camera=%7B%7D&category=%7B%7D&description=%7B%7D&file=%7B%7D&file (required)  - Photo filename in JPG/JPEG, passed along with multipart/form-data.=%7B%7D&focal_length=%7B%7D&iso=%7B%7D&latitude=%7B%7D&lens=%7B%7D&longitude=%7B%7D&name=%7B%7D&privacy=%7B%7D&shutter_speed=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This is a new photo upload endpoint. It is currently in beta.nCreate a new photo on behalf of the user and upload a file.nfile parameter is passed in multipart/form-data, other parameters are passed as query parametrs or multipart/form-data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c931d2f-aa0f-4456-9e22-ae6637f83048"
            }
          ]
        },
        {
          "id": "15f37e61-d024-4f4f-927d-a22480b4818a",
          "name": "getPhotos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id"
              ],
              "query": [
                {
                  "key": "comments",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "comments_page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "image_size",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns detailed information of a single photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "020122ad-e5f7-46a1-8df9-f5caddb85980"
            }
          ]
        },
        {
          "id": "4f843539-74ba-4ef0-9e77-b3c0748fc04b",
          "name": "putPhotos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id"
              ],
              "query": [
                {
                  "key": "description",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f52be1a-ef90-4e77-bd42-868b511042ef"
            }
          ]
        },
        {
          "id": "bd30a7d5-32fb-45dd-963a-e21848c59387",
          "name": "deletePhotos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the photo from the User's library."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccac1f4e-d724-451c-abdd-c76f2516cb58"
            }
          ]
        },
        {
          "id": "52250e51-bcd8-4cc1-a0c0-62c370f1d7ba",
          "name": "getPhotosComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/comments"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a listing of twenty comments for the photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2209a7e-1c10-4f76-b6c5-a4265bb2d3b4"
            }
          ]
        },
        {
          "id": "80986bbf-3767-4c30-875a-68ab93c7cb35",
          "name": "postPhotosComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/comments"
              ],
              "query": [
                {
                  "key": "body",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new comment for the photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06d66af3-95f1-4837-8d97-b1ddf3e7382b"
            }
          ]
        },
        {
          "id": "a5ac6be7-17b6-4412-81e3-6374c344702f",
          "name": "getPhotosFavorite",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/favorite"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "rpp",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the photo from User's favorite list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "636d8743-0a90-48f1-8f1d-4e771430e2b7"
            }
          ]
        },
        {
          "id": "92080c36-f859-4e6b-87c5-3f943240f50e",
          "name": "postPhotosFavorite",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/favorite"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the photo to user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "282d81dd-cce3-4ea1-ae04-9dcfa445bfb2"
            }
          ]
        },
        {
          "id": "a84b0eaf-a262-4bac-939b-b62c390c117d",
          "name": "deletePhotosFavorite",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/favorite"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the photo to user's list of favorites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b21d51a2-f18a-424a-a4ea-ce3cd8f393a0"
            }
          ]
        },
        {
          "id": "9ed455ae-e4f7-4692-b423-c8f0237b37ef",
          "name": "getPhotosVotes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/votes"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "rpp",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the photo from User's favorite list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cafd9523-c5ae-4706-b61c-b6769b792dd4"
            }
          ]
        },
        {
          "id": "7ada42a7-e25a-40b1-b849-b359b7f0994f",
          "name": "postPhotosVote",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/vote"
              ],
              "query": [
                {
                  "key": "vote",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the user to vote for a photo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "747e0427-0325-4c93-badb-9d4898a55ebe"
            }
          ]
        },
        {
          "id": "187b1266-72f6-416e-8586-c97d4801bf51",
          "name": "postPhotosTags",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/tags"
              ],
              "query": [
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds tags to the photo. Accepts one or multiple coma separated tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "021b8ad8-cf99-462a-b10c-dd8d85a13d9f"
            }
          ]
        },
        {
          "id": "2ec8bd72-45f4-4e5e-b021-6281f0de3bf7",
          "name": "deletePhotosTags",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "photos/:id/tags"
              ],
              "query": [
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes tags from the photo. Accepts one or multiple coma separated tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d234f5d-2a5d-4d87-8475-db5b231a4763"
            }
          ]
        }
      ]
    },
    {
      "name": "Upload",
      "item": [
        {
          "id": "feedb289-cc01-48f7-bd98-08893e1cd071",
          "name": "postUpload",
          "request": {
            "url": "http://api.500px.com/v1/upload?access_key=%7B%7D&consumer_key=%7B%7D&file=%7B%7D&photo_id=%7B%7D&upload_key=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Allows an application to upload the photo file.nnNote that this endpoint is at the upload.500px.com domain, not the api.500px.com domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad6d06e6-0de0-4c25-84bc-b45b812da16e"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "1d23bf4f-18f5-4af1-82e4-3d9798a55f2f",
          "name": "getUsers",
          "request": {
            "url": "http://api.500px.com/v1/users",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the profile information for the current user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e329a8c-11f5-4a3d-a58d-6a89418a507a"
            }
          ]
        },
        {
          "id": "5c2bf216-c0f8-475a-afdd-1501ac4a7b44",
          "name": "getUsersFollowers",
          "request": {
            "url": "http://api.500px.com/v1/users/:id/followers?id (required)=%7B%7D&page=%7B%7D&rpp=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of users who follow the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fec67ada-dac0-44a5-98d9-b258c075f37f"
            }
          ]
        },
        {
          "id": "6aab56fc-4ba7-4bc2-9db5-b7081ad20dc3",
          "name": "getUsersFriends",
          "request": {
            "url": "http://api.500px.com/v1/users/:id/friends?id (required)=%7B%7D&page=%7B%7D&rpp=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of friends for the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e00f392-e340-4480-aff1-71695fe98c1e"
            }
          ]
        },
        {
          "id": "a5476c8e-e3bd-4559-9376-c2ad835ff6d9",
          "name": "postUsersFriends",
          "request": {
            "url": "http://api.500px.com/v1/users/:id/friends?id (required)=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add the user to the list of followers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dec6ea10-979a-443e-a5bd-ddc77a9a44b8"
            }
          ]
        },
        {
          "id": "0ee45ca8-b20e-45d7-9752-8388731ff532",
          "name": "deleteUsersFriends",
          "request": {
            "url": "http://api.500px.com/v1/users/:id/friends?id (required)=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the user from the list of followers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca460b49-7034-4fe1-b92b-6cd743a3b5e6"
            }
          ]
        },
        {
          "id": "556d1a28-3593-422a-8a35-2ef7eb5f78e4",
          "name": "getUsersSearch",
          "request": {
            "url": "http://api.500px.com/v1/users/search?page=%7B%7D&rpp=%7B%7D&term=%7B%7D&term (required)=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return listing of ten (up to one hundred) users from search results for a specified search term."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e76a56c2-0356-48f7-82f6-9c6cd327dc04"
            }
          ]
        },
        {
          "id": "15fc3e9a-aaa5-4918-86f1-7be800b86e13",
          "name": "getUsersShow",
          "request": {
            "url": "http://api.500px.com/v1/users/show?email=%7B%7D&id=%7B%7D&username=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the profile information for a specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34e18b35-201a-4590-b803-14fe15ae1b3a"
            }
          ]
        },
        {
          "id": "76d00c9c-ce1f-4ecb-a19b-aa83fe48a805",
          "name": "getUsersFriends",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "users/:id/friends"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "rpp",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of friends for the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df9cbddd-3cc2-47ad-8151-b04d90d86727"
            }
          ]
        },
        {
          "id": "38283e9a-dd77-4370-a49c-f0ca00dc4da4",
          "name": "postUsersFriends",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "users/:id/friends"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add the user to the list of followers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36a9cde6-5d59-4b1c-a7de-2dc8e0cf367c"
            }
          ]
        },
        {
          "id": "d88c465b-0e54-44ec-9494-ddfd7a35e048",
          "name": "deleteUsersFriends",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "users/:id/friends"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the user from the list of followers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ead791ee-53fb-4354-8fd5-11ed6f9bcc77"
            }
          ]
        },
        {
          "id": "e80f244c-1f8a-4d07-85fb-74d226797aaf",
          "name": "getUsersFollowers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.500px.com",
              "path": [
                "v1",
                "users/:id/followers"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of users who follow the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52219d44-1cb9-401c-9d2b-9cc2628fe043"
            }
          ]
        }
      ]
    }
  ]
}