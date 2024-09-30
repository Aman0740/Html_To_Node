
### 1. **Homepage and Navigation:**
   - The homepage introduces the website with a welcome message and brief information about the platform’s functionality. Users can navigate to different sections using a header menu that links to pages like **Home**, **About**, **Contact**, and **Products**.
     
![home](https://github.com/user-attachments/assets/d153e641-495a-49a8-b724-24d5fd0cd55b)

![about](https://github.com/user-attachments/assets/599c1144-8990-475a-aceb-880fef6d1b91)

### 2. **Contact Form:**
   - A contact page is available where users can submit their **name**, **email**, and **message** via a form.
   - The data is processed and saved to a MongoDB database when submitted, allowing the site owner to receive and manage user inquiries.
![contact](https://github.com/user-attachments/assets/41213662-ed03-4da0-befe-d9b308ab0d4b)

### 3. **Product Catalog:**
   - Users can view a product catalog that lists products retrieved from a **MongoDB** database. Each product includes details like **name**, **price**, **description**, and an image.
   - The page provides an interface to add new products, edit existing ones, and delete products. All these actions update the MongoDB database accordingly.
![product](https://github.com/user-attachments/assets/a9bb6d6b-433d-4f38-bc61-53aa123de13e)

### 4. **Product Management:**
   - The application allows adding new products through a form where the user can provide details like the product name, price, description, and image URL.
   - Users can also edit a product’s details or delete a product entirely. This helps with managing and updating the product catalog dynamically.

### 5. **Backend Logic:**
   - **Express.js** is used to manage routing for various pages, including **home**, **about**, **contact**, and **product** pages.
   - The **contact** and **product** data are saved in MongoDB using **Mongoose**, a library that helps manage the database schema and interactions.

### 6. **Views and Templates:**
   - **EJS** templates are used to render dynamic content like the list of products or form submissions, making the site content-driven and responsive to changes in the database.

### 7. **Styling and Layout:**
   - Basic CSS styles are applied to ensure the application has a clean and simple layout. There is a focus on user experience with readable text, form input styling, and a visually appealing product display.
