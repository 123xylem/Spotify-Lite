# 🎵 Spotify-Lite

Full-stack Spotify clone built with PHP, JavaScript, and MySQL. Features music playback, playlists, and user management.

## Tech Stack
- PHP 
- CSS 
- JavaScript 
- MySQL

## Features
- 🎧 Music playback
- 👤 User authentication
- 📱 Responsive design
- 📑 Playlist management
- 🎸 Artist pages
- 💿 Album views
- 🔍 Search functionality
- ⚙️ User settings

## Local Setup

### Prerequisites
- PHP 7.4+
- MySQL
- Web server (Apache/Nginx)

### Installation
1. Clone repo
```bash
git clone https://github.com/your-username/spotify-lite.git
```

2. Import database
```bash
mysql -u root -p < spotify.sql
```

3. Configure database connection
```php
// includes/config.php
$db = new PDO("mysql:host=localhost;dbname=spotify", "user", "password");
```

4. Start server
```bash
php -S localhost:8000
```

5. Visit `http://localhost:8000`

## Project Structure
  spotify-lite/
  ├── assets/ # Static files
  ├── includes/ # PHP components
  ├── .php # Page controllers
  └── spotify.sql # Database schema

  
## Key Files
- `index.php` - Main entry
- `browse.php` - Music browser
- `playlist.php` - Playlist manager
- `search.php` - Search functionality
- `settings.php` - User settings

## Contributing
1. Fork repo
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## Credits
Built for Muso.ga with help from Reece Kenney

## License
MIT
