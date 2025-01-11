# **📚 Library Management System**

A **Library Management** web application built using **HTML**, **CSS**, **Python**, and the **Django Framework**. This project allows for easy management of a library's inventory by providing features to add, view, edit, and delete book records.

## **🌟 Features**
- **Book Display**:  
  Displays all books in a card layout categorized by genres.  

- **CRUD Operations**:  
  - **Add New Books**: Create detailed book records.  
  - **Edit Book Data**: Modify book details by clicking on the book's name.  
  - **Delete Books**: Remove outdated or unavailable book entries.  

- **Dynamic User Interface**:  
  Provides a responsive and user-friendly interface for interacting with the system.  

---

## **💻 Tech Stack**
### **Frontend**
- HTML5  
- CSS3  

### **Backend**
- Python  
- Django Framework  

### **Database**
- SQLite (Django's default database)

---

## **📂 Project Structure**

├── library_management/    # Main Django project  <br>
│   ├── settings.py        # Project settings  <br>
│   ├── urls.py            # URL routing for the project  <br>
│   └── wsgi.py            # WSGI application setup  <br>
├── app/                   # Main application folder for library management  <br>
│   ├── migrations/        # Database migrations  <br>
│   ├── templates/         # HTML templates for rendering  <br>
│   ├── static/            # CSS, JS, and other static files  <br>
│   ├── models.py          # Database models for book information <br> 
│   ├── views.py           # Business logic for book CRUD operations  <br>
│   ├── forms.py           # Custom forms for adding/editing book data  <br>
│   └── urls.py            # App-specific routing configuration  <br>
└── manage.py              # Django management script  <br>



## **🚦 Application Flow**
### **Key Views** (`views.py`):
1. **Index (`index`)**  
   Displays the list of books available in the library.  

2. **Add Book (`create`)**  
   Add a new book record through a user-friendly form.  

3. **Edit Book (`edit`)**  
   Edit details like name, author, price, genre, quantity, and rating.  

4. **Delete Book (`display`)**  
   Delete an existing book record from the database. 

# UI/UX

![Screenshot 2024-12-22 113135](https://github.com/user-attachments/assets/2e8d4c2e-f0e8-4a04-93e2-2e467f9b49fc)
![Screenshot 2024-12-22 113206](https://github.com/user-attachments/assets/9794d3e2-9085-42eb-92ac-512c324bdbc5)
![Screenshot 2024-12-22 113226](https://github.com/user-attachments/assets/5e9cfe3b-82b0-4a0c-aba6-3e76c55bb7ea)
![Screenshot 2024-12-22 113239](https://github.com/user-attachments/assets/f1b42945-c43b-4811-953a-71f11fde6e76)
![Screenshot 2024-12-22 113259](https://github.com/user-attachments/assets/cf2dac08-0015-4afb-aef5-491c1fee6a62)
