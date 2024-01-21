# InkChronicle - Dev Soni's Web Blog Application

* Project Overview:


  The *InkChronicle* is a web application that allows users to create, manage, and view blog posts. 
  It includes features for user registration, authentication, and authorization. 
  Users can create and publish blog posts, manage post categories, and view a list of published posts. 
  The application also supports user login/logout functionality and keeps track of user login history.

Key Features:

* User Authentication:

  Users can register for an account.
  Registered users can log in and log out of the system.
  User authentication is implemented using client sessions.
  Blog Post Management:

  Users can create and publish blog posts.
  Posts include a title, body, category, publication date, and a featured image.
  Users can view a list of all published posts and filter them by category.
  Latest published posts are displayed on the main blog page.

* Category Management:

  Users can view and manage post categories.
  Categories can be added, and existing categories can be deleted.

* User Interface:

  The application uses the Handlebars template engine for rendering views.
  The UI includes navigation links, active route highlighting, and a clean layout.
  Client-side and server-side form validations are implemented.
  Image Upload:

  Cloudinary is integrated for image uploading and hosting.
  User Login History:

  The application keeps track of user login history, including the user's IP address and user-agent information.

* Error Handling:

 Proper error handling is implemented throughout the application.

* Technologies Used:

```
Node.js
Express.js
Handlebars (View Engine)
Multer (File Upload)
Cloudinary (Image Hosting)
Client-Sessions (User Session Management)
```

How to Run?:

```
Clone the project repository.
Install dependencies using npm install.
Configure Cloudinary credentials.
Run the application using npm start.
Access the application at http://localhost:8080.
```

* Project Structure:

```
- public: Contains static files (CSS, images, etc.).
- views: Handlebars templates for rendering views.
- blog-service.js: Module for handling blog-related data and operations.
- auth-service.js: Module for user authentication and registration.
- app.js: Main application file with Express.js setup and routes.

 -Note: The project assumes a certain folder structure and dependencies. 
  Ensure that you have the required credentials for Cloudinary and necessary packages installed before running the application.
```
