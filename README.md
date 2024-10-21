# OnlineGame-Website-With-Database

## Overview
This project is a web-based application designed to manage and display character and mission information. It features responsive front-end components and dynamic back-end processing using PHP, JavaScript, HTML, and CSS.

## Features
- **Character and Mission Management:** Add, delete, and view characters and missions through the web interface.
- **Responsive Design:** The project utilizes CSS media queries to provide a responsive layout that adjusts for different screen sizes.
- **Interactive UI:** JavaScript-powered smooth scrolling, mobile-friendly navigation, and dynamic form handling.
- **Database Connectivity:** PHP scripts are used to interact with the database, handling mission and character data.

## File Structure
The project is organized as follows:

### PHP Files
- **`index.php`**: Main entry point for the web application. Displays the initial UI.
- **`character_handler.php`**: Handles character-related form submissions and displays character information.
- **`connectCharacters.php`**: Establishes a database connection for character-related operations.
- **`connectMissions.php`**: Establishes a database connection for mission-related operations.
- **`deleteCharacter.php`**: Deletes character records from the database.
- **`deleteMissions.php`**: Deletes mission records from the database.
- **`mission_logic.php`**: Contains logic related to mission processing and validation.

### JavaScript Files
- **`script.js`**: Contains all the JavaScript code for interactive behavior on the front-end, including navigation toggling, smooth scrolling, form submission handling, and various UI effects.

### CSS Files
- **`style.css`**: Defines the styling for the entire web application, including responsive layouts, animations, and hover effects.

## Setup Instructions

### Prerequisites
- **Web Server**: Apache, Nginx, or any local server environment like XAMPP or WAMP.
- **PHP**: Ensure PHP is installed on your server.
- **Database**: MySQL or any compatible database system.

## Usage
- **Add Characters and Missions:** Use the forms provided on the main page to add new characters and missions.
- **View and Manage:** The page dynamically updates with your inputs. Use the delete buttons to remove entries.

## License
This project is open-source and available 
