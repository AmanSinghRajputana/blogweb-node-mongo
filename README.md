# BlogWeb Node.js and MongoDB Website

This is a website project named "BlogWeb" that is built using Node.js, MongoDB, and frontend technologies such as HTML, CSS, and JavaScript. The project aims to provide a platform for users to create and manage their own blog posts.

## Installation

1. Clone the repository: `git clone https://github.com/AmanSinghRajputana/blogweb-node-mongo.git`
2. Navigate to the project directory: `cd blogweb-node-mongo`
3. Install the dependencies: `npm install`

## Configuration

Before running the application, you need to configure the MongoDB connection. Follow these steps:

1. Create a `.env` file in the root directory.
2. Add the following environment variables to the `.env` file:
   ```
   MONGODB_URI=<your-mongodb-uri>
   PORT=<your-preferred-port>
   ```
   Replace `<your-mongodb-uri>` with the MongoDB connection URI and `<your-preferred-port>` with the port number you want the application to run on.

## Usage

To start the application, run the following command: `npm start`

Once the server is running, you can access the website by visiting `http://localhost:<your-preferred-port>` in your web browser.

## Features
- Create, edit, and delete blog posts
- View blog posts by different categories or authors

## Technologies Used

- Node.js
- Express.js
- MongoDB
- HTML
- CSS
- JavaScript

## Contributing

If you would like to contribute to this project, feel free to submit a pull request. Any contributions are welcome!
