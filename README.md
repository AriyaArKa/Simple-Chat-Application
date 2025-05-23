﻿# Chat App -> tutorial project

A simple real-time chat application built with PHP, MySQL, and JavaScript. This project allows users to sign up, log in, and chat with other registered users.

## Features

- User authentication (Sign Up, Login, Logout)
- Real-time chat functionality
- Profile picture upload during sign-up
- Search for users to start a conversation
- Display of last seen and last message in conversations
- Responsive design using Bootstrap

## Installation

1. Clone the repository or download the source code.
2. Import the `chat_app_db` database into your MySQL server.
3. Update the database connection details in `app/db.conn.php`:
   ```php
   $sName = "localhost";
   $uName = "root";
   $pass = "your_password";
   $db_name = "chat_app_db";
   ```

## Project Structure

```
chat.php
home.php
index.php
logout.php
signup.php
app/
    db.conn.php
    ajax/
        getMessage.php
        insert.php
        search.php
        update_last_seen.php
    helpers/
        chat.php
        conversations.php
        last_chat.php
        opened.php
        timeAgo.php
        user.php
    http/
        auth.php
        signup.php
css/
    style.css
img/
    logo.jpg
uploads/
    [Uploaded profile pictures]
```

## Usage

1. Navigate to the application in your browser.
2. Sign up for a new account or log in with an existing account.
3. Start chatting with other users by searching for their username or selecting them from the conversation list.

## Technologies Used

- **Frontend**: HTML, CSS (Bootstrap), JavaScript (jQuery)
- **Backend**: PHP
- **Database**: MySQL

## Screenshots

### Login Page
![Login Page](img/login-ss.png)

### Sign Up Page
![Sign Up Page](img/signup-ss.png)

### Chat Page
![Chat Page](img/chat-ss1.png)
![Chat Page](img/chat-ss2.png)

## License

This project is open-source and available under the [MIT License](LICENSE).







- jQuery for AJAX functionality- Font Awesome for icons- Bootstrap for responsive design## Acknowledgments## Acknowledgments

- Bootstrap for responsive design
- Font Awesome for icons
- jQuery for AJAX functionality

