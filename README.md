# D49 Webshell

## Description

D49 Webshell is a PHP-based web application that provides an interface for managing files and folders on a server directly through your browser. This application combines several features such as encrypted GET parameters, a hidden login system with a fake 404 page appearance, file and folder management, and shell command execution. The interface is inspired by neon aesthetics on a dark background, utilizing Bootstrap 5 for modern responsiveness and style.

## Key Features

- **Encrypted GET Parameters**  
  Secures data transmitted via the URL using the AES-256-CBC method.  
  - Uses a 32-character encryption key.
  - Provides functions to encrypt and decrypt GET parameters.

- **Hidden Login System**  
  Implements a session-based login mechanism disguised behind a fake 404 page to enhance security.  
  - The password is stored as an MD5 hash (it is recommended to use a stronger hashing algorithm for improved security).

- **File & Folder Management**  
  Allows users to perform various file operations directly from the web interface:
  - Displays a list of files and folders along with details such as size, permissions, and modification date.
  - Provides options to edit, rename, and delete files and folders.
  - Supports file uploads as well as the creation of new files or folders.
  - Features breadcrumb navigation for easy directory traversal.

- **Shell Command Execution**  
  Offers a simple terminal interface to execute shell commands within the active directory context.

- **Modern & Responsive Interface**  
  Utilizes Bootstrap 5 and custom CSS with a neon green color palette for a unique and user-friendly experience.

## Screenshots

### Before Login

![Before Login](https://i.imgur.com/0UR2xUj.png)

### After Login

![After Login](https://i.imgur.com/KWDsWqp.jpeg)

## Installation and Configuration

1. **Clone the Repository**  
   Clone this repository to your local directory:
   ```bash
   git clone https://github.com/username/repository-name.git
