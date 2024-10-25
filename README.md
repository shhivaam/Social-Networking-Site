# Setup Instructions for Ocean Social Networking Site

Follow these steps to set up the Ocean social networking site on your local machine:

## Prerequisites

- Ensure you have [XAMPP](https://www.apachefriends.org/index.html) installed on your system.

## Installation Steps

1. **Download the Project**
   - Download the ZIP file from the repository URL.

2. **Extract the Files**
   - Extract the downloaded ZIP file. You will get a folder named `ocean.com-master`.

3. **Move the Folder**
   - Move the extracted folder to `C:\xampp\htdocs`.

4. **Rename the Folder**
   - Rename the folder from `ocean.com-master` to `ocean`.

5. **Set Up the Database**
   - Open Chrome and navigate to [phpMyAdmin](http://localhost/phpmyadmin/).

   - **Create a New Database:**
     - Click on the "Databases" tab.
     - Enter `ocean` as the database name and click "Create".

   - **Import the Database:**
     - Click on the "Import" tab.
     - Click on the "Choose File" button.
     - Navigate to `C:\xampp\htdocs\ocean\database` and select the `ocean.sql` file.
     - Click on the "Go" button to import the database.

6. **Launch the Application**
   - Open a new tab in Chrome and enter `http://localhost/ocean`.

7. **Enjoy the Application!**
   - You can now explore and enjoy the Ocean social networking site.

## Troubleshooting

- If you encounter any issues, ensure that Apache and MySQL services are running in XAMPP.
