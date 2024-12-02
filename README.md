# ImageRoulette
 ![App Screenshot](app.png)

This Flask-based web application enables users to upload multiple images, store them in personalized directories, and display them randomly with a timer-based option. Users must create accounts, log in securely, and upload images to their private space. The app automatically manages uploaded images by cleaning up files and directories upon logout or when they expire. It provides seamless navigation and functionality through interactive UI components styled with CSS and JavaScript.

# How to Use
1. **Setup:**
   
   (i) Clone the repository and navigate to the project folder
   
   (ii) Install dependencies with pip install -r requirements.txt

3. **Run the Application:**
   
    (i) To initialize the database, use:
   
         flask run
     This works only after triggering the __main__ block to ensure database creation

    (ii) Alternatively, use:
   
         python app.py
     This will automatically create the database if it doesn't exist and start the Flask development server

4. **Access the Application:**
    
    (i) Open your browser and navigate to localhost link
   
    (ii) Sign up or log in to access the image upload and random generator features

6. **Key Features:**
   
    (i) Secure User Management: Includes signup and login with hashed passwords
  
    (ii) Dynamic Content: Image uploads and random display with cleanup functionality
  
    (iii) Interactive Timer: Options to set intervals for displaying images
  
    (iv) Effortless Navigation: Clean and responsive design for user interaction
  
    (v) Feel free to modify the contact information or add any specific customization for your project
