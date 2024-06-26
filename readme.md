# Express blog backend service.

## Tech Stack
- Express
- TypeScript
- FireStore

## How to run
- Clone repository from https://github.com/guesmia1228/blog-backend.git
- Install node_modules `yarn install`
- Rename .env.sample file to .env
- Create a new project in firebase and create service account credential json file and save it in the project root folder as `firebase-account.json`.


## Endpoints
- POST: `/auth/register` Register a new user
- POST: `/auth/login` Login a user
- GET: `/users` Get list of users
- POST `/users` Create a new user
- GET: `/posts` Get list of posts
- POST: `/posts` Create a new post
- GET: `/posts/:id` Get post for a given id
- PUT: `/posts/:id/ ` Update post for a given id
- POST: `/posts/:id/comment` Add comment to the post
- Like: `/posts/:id/like` Toggle liked for a user 