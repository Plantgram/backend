# Collections

## User
- **id**
- **user_name**
- **password**
- **init_date**
- **bio**
- **alias**
- **avatar**
- **header_image**
  - **color**
  - **image_url**
- **theme**
  - light/dark *boolean*
- **badges** *array*
- **following** *array*
- **followers** *array*
- **likes** *array of image URLs*
- **favorites** *array of image URLs*
- **comments_link** *array of links to users comments*
- **gardens** *array of gardens/albums*
- **plants** *array of images*

## Gardens *albums*
- **id**
- **user_name**
- **album_title** *array default album = main*
- **init_date**
- **album_url**
- **image_id** *array*

## Image
- **id**
- **user_name**
- **upload_date**
- **public** *boolean default true*
- **image_name** *array base64 encoded?*
- **image_url**
- **description**
- **image** *array buffer*
- **tags** *array*
- **likes** *int*
  - optional: **user** *store username/alias array*
- **dislikes** *int*
  - optional: **user** *store username/alias array*
- **comments** *array*
  - **username**
  - **date**
  - **text**
  - **comment_url**
  - **reaction_emoji** *array*
  
