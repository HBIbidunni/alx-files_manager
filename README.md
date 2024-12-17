# The ALX Project - Files Manager
--------------
This project provides a __simple and scalable file management system__ 
with user authentication, file storage in MongoDB, and Redis for managing user sessions. 
The system includes features such as __creating users__, __uploading files__, and 
__retrieving file information.__

## Features
- `User Authentication`: Secure user registration and login using hashed passwords.
- `File Upload`: Upload files and manage storage.
- `File Management`: List, retrieve, and delete files.
- `Sharing`: Generate public links to share files.
- `Folder Management`: Organize files into folders for better management.
- `Statistics`: Fetch user and file-related statistics.

##  Usuage
The main endpoints of the project are summarized below:

1)  __Authentication__:
- `POST /auth/register`: Register a new user.
- `POST /auth/login`: Log in a user.

2) __File Management__:
- `POST /files`: Upload a file.
- `GET /files/:id`: Retrieve a file by __ID__.
- `GET /files`: List all files for a user.
- `DELETE /files/:id`: Delete a file by __ID__.

3) __Folder Management__
- `POST /folders`: Create a new folder.
