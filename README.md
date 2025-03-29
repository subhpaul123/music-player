# Music Player

A simple music player application built with Django. This project allows users to browse and play songs, view lyrics, and manage their music library.

## Features

- Browse through a list of songs with details like title, artist, and album art.
- Play audio files directly from the browser.
- Display synchronized lyrics as the song plays.
- Pagination for easy navigation through a large number of songs.
- Admin panel for managing songs (add, edit, delete).
- Responsive design for desktop and mobile devices.

## Technologies Used

- Django (Python web framework)
- SQLite (Database)
- HTML/CSS/JavaScript (Frontend)
- MediaElement.js (Audio player)

## Installation

### Prerequisites

- Python 3.13.2
- Django 2.2.4 or higher
- pip (Python package installer)

### Steps to Run the Project

1. **Clone the Repository**
    ```
   git clone https://github.com/subhpaul123/music-player.git
   cd musicPlayer
    ```

2.  **Create a Virtual Environment**
    ```
    python -m venv venv
    ```
    On macOS/Linux
    ```
    source venv/bin/activate  
    ``` 
    On Windows
    ```
    venv\Scripts\activate
    ```

3.  **Install Dependencies** Install the required packages using pip.
    ```
    pip install -r requirements.txt
    ```
4.  **Set Up the Database** Run the following commands to set up the database and apply migrations.
    ```
    python manage.py makemigrations App
    python manage.py migrate
    ```

5.  **Run the Development Server** Start the Django development server.
    ```
    python manage.py runserver
    ```

These features make the application a comprehensive music player, providing users with an engaging way to enjoy their favorite songs.
