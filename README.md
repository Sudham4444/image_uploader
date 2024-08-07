# Image Uploader

## Overview

The **Image Uploader** is a Django-based web application that allows users to upload images. This project provides a simple and intuitive interface for uploading and managing images.

## Features

- **Upload Images**: Users can upload images through a web form.
- **View Uploaded Images**: Uploaded images can be viewed on the application.
- **Basic Error Handling**: Handles common errors related to file uploads.

## Installation

### Prerequisites

- Python 3.6 or higher
- Django 4.x
- Virtual Environment (recommended)

### Steps to Set Up

1. **Clone the Repository**

     ```bash
     git clone https://github.com/PrathameshPC77/imageuploader.git

2. Navigate to the Project Directory

     ```bash
     cd imageuploader

3. Create and Activate a Virtual Environment

     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`

4. Install Dependencies

   ```bash
   pip install -r requirements.txt

5. Apply Database Migrations

   ```bash
   python manage.py migrate

6. Create a Superuser (Optional, for admin access)

   ```bash
   python manage.py createsuperuser

7. Run the Development Server

   ```bash
   python manage.py runserver

8. Access the Application

   Open your web browser and go to http://127.0.0.1:8000/ to access the application.

## Configuration
`Database:` This project uses SQLite by default. You can configure a different database in settings.py if needed.

`Media Files:` Ensure that the MEDIA_URL and MEDIA_ROOT are correctly set in settings.py to handle file uploads.

## Usage

`Upload Images:` Go to the main page to upload an image.

`View Images:` After uploading, images will be displayed on the page.

 ## Deployment
 
To deploy this application, follow the platform-specific deployment instructions. Ensure that you have configured media file storage correctly and set up environment variables as needed.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or issues, please contact sudhamsingh2412@gmail.com.
