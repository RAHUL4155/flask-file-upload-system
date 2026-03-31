# Flask File Upload System

A simple and clean File Upload Web Application built using Python Flask. This application allows users to upload, view, download, and delete files through a web interface.

---

## Features

* Upload files from browser
* View all uploaded files
* Download files
* Delete files
* Clean and modern UI

---

## Tech Stack

* Backend: Python, Flask
* Frontend: HTML, CSS
* Storage: Local file system (uploads folder)

---

## Project Structure

```id="y3l8mq"
flask-file-upload-system/
│── app.py
│── templates/
│   └── index.html
│── static/
│   └── style.css
│── uploads/
│── README.md
```

---

## How to Run

### 1. Install Dependencies

```bash id="j9u2sm"
pip install flask
```

### 2. Run the Application

```bash id="c3f8hv"
python app.py
```

### 3. Open in Browser

```id="5zv3bp"
http://127.0.0.1:5000
```

---

## Application Routes

* `/` → Upload file and view files
* `/download/<filename>` → Download file
* `/delete/<filename>` → Delete file

---

## Future Improvements

* Image preview before upload
* Upload progress bar
* Authentication system
* Cloud storage integration

---

## Reference

Flask Documentation: https://flask.palletsprojects.com/

---

## Author

Rahul
