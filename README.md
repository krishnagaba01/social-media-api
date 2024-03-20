# Social Media API

This repository contains the source code for a comprehensive Social Media API developed using Node.js with Express.js and MongoDB. The API covers fundamental CRUD operations as well as advanced features like authentication, commenting, story upload, image upload, messaging, likes, blocking functionality, and JWT authentication.

## Features

- **User Registration and Authentication:** Implement user registration and authentication using JWT tokens for secure access.
- **CRUD Operations:** Enable basic CRUD operations for users, posts, comments, stories, and messages.
- **Commenting:** Allow users to comment on posts and stories.
- **Story Upload:** Implement functionality for users to upload and share stories.
- **Image Upload:** Enable users to upload images for their posts, stories, or profile pictures.
- **Messaging:** Implement private messaging between users.
- **Likes:** Allow users to like posts and stories.
- **Blocking Functionality:** Implement blocking functionality for users to block other users.
- **JWT Authentication:** Secure API endpoints with JSON Web Token (JWT) authentication.

## Requirements

- Node.js
- Express.js
- MongoDB
- bcrypt (for password hashing)
- JWT (for authentication)
- multer (for handling file uploads)

## API Endpoints

- User Registration: `POST /api/register`
- User Login: `POST /api/login`
- Create Post: `POST /api/posts`
- Update Post: `PUT /api/posts/:postId`
- Delete Post: `DELETE /api/posts/:postId`
- Create Comment: `POST /api/posts/:postId/comments`
- Create Story: `POST /api/stories`
- Update Story: `PUT /api/stories/:storyId`
- Delete Story: `DELETE /api/stories/:storyId`
- Upload Image: `POST /api/upload`
- Send Message: `POST /api/messages`
- Like Post/Story: `POST /api/posts/:postId/like` or `POST /api/stories/:storyId/like`
- Block User: `POST /api/users/:userId/block`

## Deployment

The API can be deployed to cyclic for accessibility.


## Test User

To test the API, you can use the following test user credentials:

- **Username:** testuser
- **Password:** test123

### API Login URL

You can login using the provided test user credentials via the following URL:

[Login URL](https://easy-red-stingray-wig.cyclic.app/api/auth/login)
