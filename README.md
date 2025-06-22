# camera_catalogue_Django_app
The Camera Catalogue Django App showcases a collection of cameras with dynamic listings, detailed specifications, and interactive modals. Users can browse a responsive layout featuring a video carousel, "About Us" and "Contact" sections, and admin tools for managing data. Built with Django. 

The **Camera Catalogue Django App** is a web application for showcasing and managing camera details. Users can explore various camera models with dynamic listings, view detailed specifications, and interact with videos and images. Administrators can add and manage camera data via the Django admin panel.

---

## Features
- **Dynamic Camera Listings**: Display detailed camera cards with specifications.
- **Interactive Modals**: View camera details and images in pop-ups.
- **Video Carousel**: Highlight promotional or informational videos.
- **Responsive Design**: Accessible on all devices.
- **Admin Panel**: Manage camera data and media files.

---

## Installation and Setup

### 1. Clone or Download the Repository
Download the project as a ZIP file and extract it, or clone it using:
```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory
```bash
cd camera_catalogue
```

### 3. Install Dependencies
Make sure you have Python and `pip` installed. Create a virtual environment and install dependencies:
```bash
python -m venv env
source env/bin/activate    # For Windows: env\Scripts\activate
pip install -r requirements.txt
```

### 4. Apply Migrations
Run the following commands to set up the database:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser
Set up an admin user to manage camera data:
```bash
python manage.py createsuperuser
```
Follow the prompts to set a username, email, and password.

### 6. Add Media Data
- Log in to the admin panel at `http://127.0.0.1:8000/admin/`.
- Use the interface to upload camera details, images, and videos.

### 7. Run the Development Server
Start the server to view the app:
```bash
python manage.py runserver
```

Visit the application in your browser at: `http://127.0.0.1:8000/`.

---

## Project Structure
- **templates/index.html**: Main page displaying camera listings.
- **static/**: Contains CSS, JavaScript, and images.
- **media/**: Stores uploaded images and videos.
- **app/**: Core Django app for handling functionality and data.

---

## Usage
- **Main Page**: Displays all cameras dynamically.
- **Admin Panel**: Add or update camera data, images, and videos.

---

## Future Enhancements
- Add search and filter functionality.
- Enable user authentication for personalized experiences.
- Incorporate e-commerce features like a shopping cart.

---

## License
This project is licensed under the MIT License.
