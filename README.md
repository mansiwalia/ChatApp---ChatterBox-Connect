# ChatterBox Connect - Real Time Chat App

**ChatterBox Connect** A real-time chat application designed for seamless communication, featuring secure user authentication, dynamic user interaction, and an intuitive interface.

## Demo Link Of Project
You can watch a demo of this project on my [LinkedIn profile](https://www.linkedin.com/feed/update/urn:li:activity:7237048455922085888/).

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Deployed Links](#deployed-links)
7. [Contributing](#contributing)
8. [License](#license)

## Features

### User Authentication:
- **Secure Registration and Login**: - Users must sign up with their email and password.
                                     - Existing users can log in securely. 
- **Session Management**: Maintains user sessions to keep them logged in across pages.

### Chat Functionality::
- **Real-Time Messaging:**: Users can send and receive messages instantly.
- **User Status:**: Displays online/offline status dynamically.
- **User List:**: Shows a list of all signed-up users with profile images and full names.

### Database Management:::
- **Message Storage:**: Messages are stored in a database to maintain chat history.
- **User Data:**: Stores user credentials and status securely.        

## Technologies Used

The project is built using the **PHP** with the following key technologies:

- **Frontend:**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Libraries/Technologies**: AJAX for seamless communication between frontend and backend.
- **Database**: MYSQL
- **Server Environment**: Apache (via XAMPP/WAMP)
- **Tools**: Visual Studio Code

## Project Structure

### `/Root Directory`
- **index.php**: User login/registration page.
- **chat.php**: Main chat interface for logged-in users.
- **api folder**: Backend scripts for handling requests like user authentication and message management.
- **db_connect.php**: Database connection script.
- **uploads/**: Directory for storing user profile images.
  
### `/Key Directories and Files:`
- **api/**: Backend scripts for database interactions.
- **css/ **: Custom stylesheets for enhanced UI.
- **js/**: JavaScript files for added interactivity.

## Getting Started

To get the project up and running locally, follow these steps:

### Prerequisites

- Install XAMPP or WAMP for local server hosting.
- Basic knowledge of PHP and MySQL.


### Installation

# 1. Clone the repository:
git clone git clone https://github.com/mansiwalia/chatterbox-connect.git

# 2. Set Up the Project:
Move the project files to the htdocs directory of your XAMPP installation.

# 3. Database Configuration:
- Open phpMyAdmin and create a new database named chatterbox.
- Import the chatterbox.sql file (available in the project repository).

# 4. Edit the Database Connection:
# Update db_connect.php with your database credentials:
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "chatterbox";


# 5. Start the Local Server:
- Launch XAMPP/WAMP and start the Apache and MySQL modules.
- Navigate to (http://localhost/chatterbox-connect.)


## Usage

- **User Registration and Login:**:
- New users can register by providing their full name, email, password, and profile picture.
- Existing users can log in to access the chat interface.
  
- **Chat Functionality:**:
- Users can view other online users and send real-time messages.
- Chats are displayed dynamically, with updated user statuses.


## Contributing
Contributions are welcome! If you’d like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

