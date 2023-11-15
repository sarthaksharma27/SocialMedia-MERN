
# Social Media Project

![Screenshot from 2023-11-09 16-02-32](https://github.com/sarthaksharma27/SocialMedia-MERN/assets/130299888/6e98aeb7-8e4f-496a-b524-0837d960457f)

This project is a social media built using the MERN stack (MongoDB, Express, React, Node.js). It offers functionalities similar to popular social media platforms, allowing users to create profiles, post updates, follow other users, like and comment on posts, and more.
## Features

- **User Authentication:** Securely sign up, log in, and log out.
- **Profile Management:** Create and edit user profiles.
- **Post Creation:** Create, edit, and delete posts.
- **Interactions:** Like and comment on posts.
- **Follow System:** Follow other users and see their posts on the feed.
## Tech Stack

**Frontend:**
- React
- Redux (optional)

**Backend:**
- Node.js
- Express

**Database:**
- MongoDB

**Authentication:**
- JWT (JSON Web Tokens)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in server folder

  ```bash
   MONGO_URL=YOUR_MONGO_ATLAS_URL
   JWT_SECRET=MAKE_YOUR_SECRET
   PORT=PORT
```


# Installation


## Install server dependencies

```bash
 cd server
 npm install
 nodemon index.js
```

## Install client dependencies

```bash
 cd ../client
 npm install
 npm run dev
```

    
