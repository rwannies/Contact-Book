Contact Book
Welcome to the Contact Book project — a modern, API-powered web application for managing contacts. Built with HTML, CSS, and JavaScript, this app allows users to add, edit, delete, and view contacts with a sleek, responsive interface, leveraging an external API for data storage and retrieval.
Table of Contents

Project Overview
Features
File Structure
Setup Instructions
Usage
Contributing
License
Contact

Project Overview
The Contact Book is a client-side web application that interacts with an external API to manage contact information, including names, mobile numbers, email addresses, and optional profile pictures. It features a user-friendly interface with dynamic page navigation, real-time contact updates, and error handling, making it ideal for personal contact management or as a learning project for API-driven web development.
Features

API Integration: Connects to an external API for contact storage and retrieval using an API key.
Contact Management: Add, edit, delete, and view contacts with details like first name, last name, mobile number, email, and profile picture.
Responsive Design: Optimized for both desktop and mobile devices with a clean, modern UI.
Dynamic Navigation: Seamlessly switch between API setup, contact list, add contact, and edit contact pages.
Error Handling: Displays user-friendly error and success messages for API interactions.
Local Storage: Stores API key locally for persistent access.
Interactive UI: Includes hover effects, contact cards, and avatar generation for contacts without profile pictures.

File Structure
Contact-Book/
├── index.html    # Main HTML file for the application
├── style.css     # Stylesheet for layout and design
├── script.js     # JavaScript for API interactions and functionality
└── README.md     # Project documentation



Setup Instructions

Clone the Repository:git clone https://github.com/rwannies/contact-book.git
cd contact-book


Open the Project:
No external dependencies are required as the project uses vanilla HTML, CSS, and JavaScript.
Open index.html in a web browser to start the application.


Optional: Local Server:
For a better development experience, use a local server (e.g., Live Server in VS Code or Python's HTTP server):python -m http.server 8000


Access the app at http://localhost:8000.


API Key:
On first load, enter an API key (e.g., appacademy@itvarsity.org as provided) to access the contact management features.
The API key is stored in local storage for subsequent visits.



Usage

API Setup:
Enter a valid API key in the initial setup page to unlock the contact management features.


View Contacts:
Browse the contact list displayed as cards with avatars, names, mobile numbers, and emails.
Use the "Refresh" button to reload contacts from the API.


Add a Contact:
Click "Add Contact" to open the form, fill in details (first name, last name, mobile, email, optional profile picture), and save.


Edit a Contact:
Click "Edit" on a contact card to modify its details and update via the API.


Delete a Contact:
Click "Delete" on a contact card and confirm to remove it from the API.


Responsive Layout: Use on any device for a consistent experience.



Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request to the main branch.

Please ensure your code follows best practices for HTML, CSS, and JavaScript, and test API interactions thoroughly. Add comments for clarity and document any new features.


License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or suggestions, contact the project maintainer at wanniesruche@gmail.com or open an issue on GitHub.
