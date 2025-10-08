# archive-infotainment-app

A web application for browsing and streaming public domain content from Archive.org. Access thousands of movies, TV shows, music, audiobooks, radio programs, and podcasts. I previously worked for a company that built Hospital Infotainment systems, this is an homage to those days and a lot of great retro content from Archive.org.

<img width="1919" height="955" alt="image" src="https://github.com/user-attachments/assets/4f3aab06-dec8-427d-99e2-df50399a5aec" />

## ✨ Features

- **📺 Multi-Media Support**: Browse movies, TV shows, music, audiobooks, old-time radio, and podcasts
- **🎨 Modern UI**: Sleek, futuristic design with glassmorphism effects and smooth animations
- **🔍 Smart Categorization**: Content organized by genres with intelligent filtering
- **▶️ Built-in Player**: Stream content directly without leaving the app
- **🖼️ Lazy Loading**: Optimized image loading with retry logic for better performance
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **⚡ Fast Navigation**: Instant switching between content types
- **🌐 No Backend Required**: 100% client-side application - just open and use

## 🚀 Demo

[[Live Demo](#)https://www.infiniteloopers.com/ArchiveInfo/]

## 💻 Usage

1. **Browse Content**: Click on any category (Movies, TV Shows, Music, etc.) from the main navigation
2. **Filter by Genre**: Use the genre tabs to narrow down your search
3. **Play Content**: Click the "Play" button on any item to stream it in the modal player
4. **View Details**: Click "Details" to open the item's page on Archive.org
5. **Scroll to Top**: Use the floating button in the bottom-right to quickly return to the top

## 🛠️ Technology Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with custom properties, gradients, and animations
- **Vanilla JavaScript** - No frameworks, pure ES6+ JavaScript
- **Archive.org API** - Content fetching and metadata
- **Intersection Observer API** - Efficient lazy loading

## 🔧 How It Works

The application uses Archive.org's Advanced Search API to fetch content:

```javascript
// Example API call structure
https://archive.org/advancedsearch.php?q=[query]&fl[]=identifier,title,description&output=json
```

Content is categorized based on metadata subjects and organized into genres. The app maintains state in memory and provides smooth navigation between different content types.

## 📋 Content Sources

All content is sourced from Archive.org's public domain collections:
- **Movies**: Feature Films & Classic Cinema
- **TV Shows**: Classic TV from the 60s and 70s
- **Music**: Live concerts, Grateful Dead archive, and music collections
- **Audiobooks**: Poetry and literature recordings
- **Radio**: Old Time Radio programs
- **Podcasts**: Various podcast collections

## 🎨 Customization

You can easily customize the app by modifying:

- **Colors**: Update CSS custom properties in the `<style>` section
- **Content Sources**: Modify the `CONTENT_TYPES` object to change queries
- **Genres**: Add or remove genre categories in the genre mappings
- **Layout**: Adjust grid columns, spacing, and responsive breakpoints

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

- Content provided by [Archive.org](https://archive.org) - a non-profit digital library
- Icons: Emoji icons from standard Unicode set

## ⚖️ Legal

This application only streams content from Archive.org's public domain and freely available collections. All content rights belong to their respective owners. This is an unofficial third-party interface and is not affiliated with or endorsed by Archive.org.

## 🐛 Bug Reports

Found a bug? Please open an issue on GitHub with:
- Description of the bug
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)
- Browser and OS information

## 💬 Support

If you like this project, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features

---
