# Personal Blog Website

This is a personal blog website where you can write, read, and delete blogs. It has been developed using EJS, Express.js, and MongoDB.

## Installation

To run this project locally, follow these steps:

1. Clone the repository using Git:

   ```bash
   git clone https://github.com/ashutosh0111/Blog-Website.git
   ```

2. Navigate to the project's root directory:

   ```bash
   cd Blog-Website
   ```

3. Install the required Node.js packages by running:

   ```bash
   npm install
   ```

4. Add your MongoDB database address to the `MONGODB_URI` variable in the `app.js` file. Replace `YOUR_MONGODB_URI` with your actual MongoDB connection string.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your web browser and access the website at [http://localhost:3000](http://localhost:3000).

## Usage

Once the application is running, you can use it to:

- **Write a Blog**: Click on the "New Blog" button to create a new blog post. Fill in the required information, including the title and content of your blog, and then click the "Publish" button.

- **Read Blogs**: All published blogs will be displayed on the home page. Click on a blog title to view the full blog post.

- **Delete Blogs**: To delete a blog post, click the "Delete" button on the blog post you want to remove. Be cautious, as deleted blogs cannot be recovered.

## Technologies Used

- EJS (Embedded JavaScript) for templating
- Express.js for the web application framework
- MongoDB for database storage

## Contributing

If you would like to contribute to this project or report issues, please visit the [GitHub repository](https://github.com/ashutosh0111/Blog-Website).

---

Enjoy writing and sharing your blogs on your personal blog website!