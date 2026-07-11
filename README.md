

Name: AYUSHI KUSHWAHA
ID:CITS6702
Company: CODTECH IT SOLUTIONS
Domain: Backend Web Development
Duration: July to August 2026
Mentor: NEELA SANTHOSH KUMAR

# RESTful Blog API using Flask

## Project Overview

This project is a RESTful Blog API developed using Python Flask. It provides CRUD (Create, Read, Update, Delete) operations for managing blog posts.

The API allows users to create new blogs, view existing blogs, update blog details, and delete blogs using HTTP methods.

--

## Technologies Used

* Python
* Flask Framework
* REST API
* JSON
* Postman for API Testing

---

## Features

* Welcome home route
* Get all blog posts
* Create a new blog post
* Get blog details using ID
* Update existing blog posts
* Delete blog posts
* JSON-based API responses

---

## Project Structure

```
Blog-REST-API/
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots/
```

---


## Installation and Setup

### 1. Clone the Repository

```
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to Project Folder

```
cd Blog-REST-API
```

### 3. Install Required Packages

```
pip install -r requirements.txt
```

### 4. Run the Application

```
python app.py
```

The server will start at:

```
http://127.0.0.1:5000/
```

---

# API Endpoints

## 1. Home Route

**GET**

```
/
```

Response:

```
Welcome to My Blog API!
```

---

## 2. Get All Blogs

**GET**

```
/blogs
```

Returns all available blog posts.

---

## 3. Create New Blog

**POST**

```
/blogs
```

Request Body:

```json
{
    "title":"My Blog",
    "content":"Blog content"
}
```

---

## 4. Get Blog By ID

**GET**

```
/blogs/<id>
```

Example:

```
/blogs/1
```

---

## 5. Update Blog

**PUT**

```
/blogs/<id>
```

Request Body:

```json
{
    "title":"Updated Title",
    "content":"Updated Content"
}
```

---

## 6. Delete Blog

**DELETE**

```
/blogs/<id>
```

Example:

```
/blogs/1
```

---

## Testing

The API was tested using Postman.

Tested operations:

* GET request
* POST request
* PUT request
* DELETE request

Screenshots of testing results are included in the screenshots folder.

---

## Future Improvements

* Add database integration using SQLite/MySQL
* Add user authentication
* Add JWT security
* Deploy API on cloud platforms
* Add frontend interface

---

## API Testing Screenshots
![image alt](https://github.com/ayushi-56/CODTECH-Task1/tree/7bbd2c79431984a198552bbee895e3c5d0e94c43/screenshots)



