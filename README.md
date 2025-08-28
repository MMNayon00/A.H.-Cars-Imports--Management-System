A.H. Cars Imports - Management System
A simple, modern, and fully responsive web application designed for small car import businesses to manage inventory, track expenses, and calculate profitability. This application is built entirely with frontend technologies (HTML, CSS, and JavaScript) and uses the browser's local storage to save data, requiring no backend or database.

Link to Live Demo <!-- Add your GitHub Pages link here -->

Features
Add & Manage Cars: Easily add new cars to your inventory with essential details like name, model, registration number, and owner information.

Expense Tracking: Log unlimited expenses for each car, such as purchase cost, repairs, and transportation. The total expense is calculated automatically.

Profit & Loss Calculation: Enter the selling price for a car to instantly see the calculated profit or loss, highlighted in green for profit and red for loss.

Detailed Reporting: Generate a clean, professional, and printable report for each car that includes all details, a complete list of expenses, total costs, selling price, and final profit/loss.

Persistent Data: All data is saved directly in your browser's localStorage. You can close the tab or browser and your data will be waiting for you when you return.

Fully Responsive Design: The interface is optimized for all screen sizes, providing a seamless experience on desktops, tablets, and mobile phones.

Modern & Intuitive UI: A clean, user-friendly interface with icons and a logical layout makes managing your inventory effortless.

Safe Deletion: A confirmation step is included to prevent accidental deletion of car records.

Technologies Used
HTML5: For the structure and content of the application.

Tailwind CSS: For a modern, utility-first approach to styling and responsive design.

JavaScript (ES6+): For all the application logic, including data management, calculations, and DOM manipulation.

Feather Icons: For clean and simple icons used throughout the interface.

How to Use
Since this is a purely frontend application, you can run it directly in your browser without any special setup.

Download the Code:

Clone the repository: git clone https://github.com/your-username/your-repo-name.git

Or download the ZIP file from GitHub.

Open the File:

Navigate to the project directory.

Open the index.html file (or whatever you named the main HTML file) in any modern web browser like Google Chrome, Firefox, or Microsoft Edge.

That's it! The application is ready to use.

How It Works
The application stores all car and expense data as a JSON object in the browser's localStorage.

When you add, edit, or delete information, the JavaScript code updates this object.

The saveData() function is then called to write the updated object back to localStorage.

When you open or refresh the page, the application checks localStorage for any existing data and loads it, ensuring your information is always preserved on that specific computer and browser.
