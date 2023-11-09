Social Media Clone using MERN Stack
This project is a social media clone built using the MERN stack (MongoDB, Express, React, Node.js). It offers functionalities similar to popular social media platforms, allowing users to create profiles, post updates, follow other users, like and comment on posts, and more.

![Screenshot from 2023-11-09 16-02-32](https://github.com/sarthaksharma27/SocialMedia-MERN/assets/130299888/6e98aeb7-8e4f-496a-b524-0837d960457f)


Table of Contents
Features
Installation
Usage
Tech Stack
Contributing
License
Features
User Authentication: Sign up, log in, and log out securely.
Profile Management: Create and edit user profiles.
Post Creation: Create, edit, and delete posts.
Interactions: Like and comment on posts.
Follow System: Follow other users and see their posts on the feed.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/social-media-clone.git
cd social-media-clone
Install dependencies:

bash
Copy code
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Set up environment variables:

Create a .env file in the server directory and add the necessary environment variables, such as MongoDB connection string, JWT secret, etc.

Run the application:

bash
Copy code
# Start the server
cd server
nodemon index.js

# Start the client
cd ../client
npm run dev
Access the application at http://localhost:3000.

Usage
Register an account or use the provided demo account.
Create a profile, make posts, follow users, like and comment on posts.
Tech Stack
Frontend: React, Redux (optional)
Backend: Node.js, Express
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
Contributing
Feel free to contribute to this project by forking it and creating a pull request. Any suggestions or improvements are welcome.

License
This project is licensed under the MIT License.
