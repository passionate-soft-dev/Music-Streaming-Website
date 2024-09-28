# 🎶 Music Streaming Website

## Introduction
Welcome to the **Music Streaming Website**, a platform built using Laravel where users can listen to their favorite music, create playlists, and explore new tunes. This project is designed to offer a smooth and engaging music streaming experience.

## Features
- 🎵 Stream music from a vast collection of tracks.
- 📑 Create and manage custom playlists.
- 🔍 Search for songs, albums, and artists.
- ❤️ Add songs to your favorites.
- 🎚 User-friendly music player with play, pause, next, and previous functionality.
- 🔥 Explore trending and top-rated tracks.
- 🛠 Admin dashboard for managing tracks, albums, and users.

## Technologies Used
- **Backend**: Laravel (PHP Framework)
- **Frontend**: Blade, HTML, CSS, JavaScript
- **Database**: MySQL
- **Authentication**: Laravel Authentication with user roles (Admin and User)
- **Storage**: Local storage for music files
- **Player**: Custom JavaScript audio player

## Setup and Installation

### Prerequisites
- PHP >= 8.0
- Composer
- MySQL
- Node.js & NPM

### Installation Steps
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/music-streaming-website.git
    cd music-streaming-website
    ```

2. **Install Dependencies**:
    - Install PHP dependencies:
      ```bash
      composer install
      ```
    - Install NPM dependencies:
      ```bash
      npm install && npm run dev
      ```

3. **Setup Environment**:
    - Create a `.env` file by copying the example:
      ```bash
      cp .env.example .env
      ```
    - Update database credentials and other environment settings in `.env`.

4. **Generate Application Key**:
    ```bash
    php artisan key:generate
    ```

5. **Run Migrations and Seed Data**:
    ```bash
    php artisan migrate --seed
    ```

6. **Start the Development Server**:
    ```bash
    php artisan serve
    ```

## Admin Dashboard
Admins can manage:
- 🎶 Tracks
- 📁 Albums
- 👥 Users

The admin dashboard provides functionalities to add, update, and delete tracks and manage user accounts.

## License
This project is licensed under the MIT License.