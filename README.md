# NodeJs, Express, EJS & MongoDB Blog

The project involves creating a website that serves as a blogging platform, designed for a single user (the admin) to publish, edit, and manage their blog posts. Key features of the site include:

- Home Page - Features an introduction to the admin, displays the latest blog posts, and provides a clean, user-friendly layout.
- Subpages:
    - About - Includes information about the admin and the purpose of the site.
    - Contact - Provides a contact form and other methods to get in touch.
- Dynamic Content - Blog posts are dynamically generated using a Node.js backend and stored in a MongoDB database.
- Admin Functionality - Allows only the admin to create, update, and delete blog posts.
- Responsive Design - The site is optimized for various devices, including desktops, tablets, and smartphones.
- Interactive Elements - Includes feature such as a search function for enhanced user engagement.

The website is built using Node.js, MongoDB, and EJS for templating, with CSS ensuring a modern and responsive design.

## You need:
- NodeJs
- Database (MongoDB) Free Cluster

## Setup Database
Sign up for MongoDB free database cluster:  [MongoDB](https://www.mongodb.com/)

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
JWT_SECRET=MySecretBlog
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm run dev
```

## Live
Check the site out on http://localhost:5000/
