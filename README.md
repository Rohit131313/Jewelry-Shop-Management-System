# **Jewelry Shop Management System**

## **Overview**

Welcome to the Jewelry Shop Management System, a comprehensive web application designed to facilitate the management of a jewelry store. This system incorporates both front-end and back-end development technologies to create an attractive and user-friendly interface for customers and an efficient admin panel for store management.

## **Table of Contents**

- [**Folder Structure**](#folder-structure)
- [**Technologies Used**](#technologies-used)
- [**Features**](#features)
- [**Installation**](#installation)
- [**Support and Issues**](#support-and-issues)

## **Folder Structure**

### **1. Public Folder**

#### **Displayimage Folder:**

Contains images that are permanently present on the user interface (UI) of the website.

#### **Upload Folders (e.g., UploadBracelets, UploadEarrings, UploadNecklace, UploadMixed, UploadRings):**

Each folder contains images of specific jewelry types. Admins can upload or change images in these folders to display them in the gallery webpage of the website.

### **2. Src Folder**

#### **Db Folder:**

- **Conn.js:**
  Connects the code to MongoDB using Mongoose.
  Establishes a connection to the MongoDB cluster.

- **Models Folder:**
  - **Contactus.js:**
    Defines the schema and creates a Mongoose collection for storing contact form submissions.
  - **Orders.js:**
    Defines the schema and creates a Mongoose collection for storing customer orders.
  - **Upload Files (e.g., UploadBracelets.js, UploadEarrings.js, UploadMixed.js, UploadNecklace.js, UploadRings.js):**
    Each file defines the schema and creates a Mongoose collection for storing images of specific jewelry types.

- **App.js:**
  Contains the code for the Node.js server.
  Configures routes, handles HTTP requests, and connects to the MongoDB database.
  Manages the logic for image uploads, order submissions, and other functionalities.

### **3. Template Folder**

#### **Partial Folder:**

Contains reusable HBS (Handlebars) templates for common UI elements.

#### **Views Folder:**

Contains HBS files for each webpage, defining the dynamic content and structure.

## **Technologies Used**

- **Front-end Development:**
  - HTML, CSS, JavaScript
  - Embedded JavaScript (EJS) for rendering dynamic views

- **Back-end Development:**
  - Node.js and Express.js for server-side development

- **Database:**
  - MongoDB for storing and managing customer orders and product images

- **Image Upload:**
  - Multer library for handling image uploads

## **Features**

1. **Front-end Development:**
   - Utilized HTML, CSS, and JavaScript to create an engaging and user-friendly interface for customers.
   - Implemented dynamic image display for jewelry products, allowing customers to view the latest additions.

2. **Back-end Development:**
   - Implemented the server-side using Node.js and Express.js to handle requests and responses efficiently.
   - Created a robust back-end system for seamless communication between the front-end and the database.

3. **Database Integration:**
   - Integrated MongoDB to store and manage customer orders and other relevant data securely.
   - Ensured reliable data storage and retrieval for efficient order processing.

4. **User Order Functionality:**
   - Enabled customers to place orders seamlessly through a user-friendly interface.
   - All order details are securely stored in the MongoDB database, providing a reliable record of customer transactions.

5. **Admin Panel:**
   - Developed an admin panel to facilitate easy management of jewelry product displays.
   - Admins can upload images for rings, necklaces, and other jewelry products, ensuring an up-to-date product catalog.

6. **Dynamic Image Display:**
   - Implemented a feature to display jewelry images uploaded by the admin on the website.
   - Ensured that the website reflects the latest product offerings, maintaining an engaging and dynamic user experience.

7. **Contact Form:**
   - Incorporated a contact form to enable customers to raise queries and seek support from the shop owner.
   - Provided a direct communication channel to enhance customer support and satisfaction.

## **Installation**

1. Clone the repository: `git clone https://github.com/Rohit131313/Jewelry-Shop-Management-System.git`
2. Navigate to the project directory: `cd Jewelry-Shop-Management-System`
3. Install dependencies: `npm install`
4. Set up MongoDB and update database configuration in `src/db/conn.js`.
5. Run the application: `npm start`
6. Access the application at [http://localhost:4200](http://localhost:4200) in your web browser.

