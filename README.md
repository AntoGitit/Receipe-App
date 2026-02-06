# Recipe Muse 🍳

> Your personal culinary companion for discovering recipes from around the world

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-3-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

---

## 📋 Overview

**Recipe Muse** is a beautiful, single-page web application that helps users discover recipes based on their favorite cuisines. Built with vanilla HTML, CSS, and JavaScript, it requires no frameworks, no build tools, and no backend—just open the file in a browser and start cooking!

### ✨ Key Features

- 🎲 **Dynamic Welcome Messages** - Inspiring quotes, jokes, and haiku that change on every visit
- 🌍 **27+ World Cuisines** - From Italian to Thai, Mexican to Japanese
- 🔍 **Smart Type-Ahead Search** - Find cuisines quickly with auto-suggestions
- 📖 **Detailed Recipes** - Complete ingredients lists and step-by-step instructions
- ❤️ **Interactive Feedback** - Like, dislike, or favorite recipes
- ⭐ **Favorites Collection** - Save and manage your favorite recipes locally
- 📱 **Mobile Responsive** - Beautiful on all devices
- 🎨 **Distinctive Design** - Retro-modern cookbook aesthetic

---

## 🚀 Quick Start

### Option 1: Direct Use (No Setup Required)

1. Download `recipe-app.html`
2. Double-click the file to open it in your browser
3. Start exploring recipes!

### Option 2: Clone Repository

```bash
# Clone the repository
git clone https://github.com/yourusername/recipe-muse.git

# Navigate to directory
cd recipe-muse

# Open in browser
open recipe-app.html  # macOS
start recipe-app.html # Windows
xdg-open recipe-app.html # Linux
```

### Option 3: Serve Locally (Optional)

If you prefer to run a local server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server package)
npx http-server

# Then visit: http://localhost:8000/recipe-app.html
```

---

## 📖 Documentation

For detailed usage instructions, see [USER-DOCUMENTATION.md](USER-DOCUMENTATION.md)

---

## 🎯 How It Works

### User Flow

```
1. User arrives → Sees unique welcome message
2. User enters name + selects cuisine
3. User submits form
4. App generates personalized recipe
5. User can:
   - Like the recipe (👍)
   - Get another recipe (👎)
   - Add to favorites (⭐)
6. User can view all favorites in dedicated page
```

### Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Custom styling with CSS variables
- **JavaScript (ES6)** - Vanilla JS, no frameworks
- **LocalStorage API** - Client-side data persistence

---

## 🗂️ File Structure

```
recipe-muse/
│
├── recipe-app.html          # Main application (single file)
├── USER-DOCUMENTATION.md    # Complete user guide
└── README.md               # This file
```

---

## 🎨 Design Features

### Color Palette
- **Cream** (#FFF8F0) - Main background
- **Burnt Orange** (#D4692A) - Primary accent
- **Deep Green** (#2C5234) - Secondary accent
- **Sage** (#8B9D83) - Supporting color
- **Gold** (#C9A959) - Favorite highlights

### Typography
- **Playfair Display** - Headers and elegant text
- **Karla** - Body text and UI elements

### Animations
- Smooth fade-in transitions
- Slide-in recipe cards
- Hover effects on interactive elements
- Animated navigation underlines

---

## 🍽️ Available Cuisines

The app includes recipes from the following cuisines:

| Region | Cuisines |
|--------|----------|
| **European** | Italian, French, Greek, Spanish, German, Portuguese, British, Mediterranean |
| **Asian** | Chinese, Japanese, Indian, Thai, Korean, Vietnamese, Malaysian, Indonesian |
| **Middle Eastern** | Turkish, Lebanese, Moroccan, Middle Eastern |
| **Americas** | Mexican, American, Brazilian, Caribbean, Peruvian |
| **African** | Ethiopian |
| **International** | Russian |

---

## 📦 Features Breakdown

### 1. Welcome System
- Pool of 15+ unique messages
- Randomly selected on each page load
- Includes quotes, jokes, and haiku

### 2. Cuisine Search
- Type-ahead functionality
- Filters 27+ cuisines in real-time
- Click-to-select dropdown
- Handles partial matches

### 3. Recipe Generation
- Organized by cuisine type
- Random selection from cuisine-specific recipes
- Detailed ingredient lists
- Step-by-step instructions
- Timing and serving information

### 4. Interaction System
- **Like**: Visual feedback, changes button state
- **Dislike**: Generates new recipe instantly
- **Favorite**: Saves to localStorage, persists across sessions

### 5. Favorites Management
- Grid layout for easy browsing
- Quick-view recipe cards
- One-click access to full recipes
- Remove from favorites functionality
- Empty state with helpful message

---

## 🔧 Customization

### Adding New Recipes

Edit the `recipeDatabase` object in the JavaScript section:

```javascript
const recipeDatabase = {
    'italian': [
        {
            name: 'Your Recipe Name',
            prepTime: '15 mins',
            cookTime: '30 mins',
            servings: '4',
            ingredients: [
                'Ingredient 1',
                'Ingredient 2',
                // ...
            ],
            instructions: [
                'Step 1',
                'Step 2',
                // ...
            ]
        }
    ]
};
```

### Adding New Cuisines

1. Add to the `cuisines` array:
```javascript
const cuisines = [
    'Italian', 'Chinese', // ... existing
    'NewCuisine' // Add here
];
```

2. Add recipes to `recipeDatabase`:
```javascript
const recipeDatabase = {
    // ... existing
    'newcuisine': [ /* recipes */ ]
};
```

### Modifying Welcome Messages

Edit the `welcomeMessages` array:

```javascript
const welcomeMessages = [
    "Your custom message here",
    "Another message",
    // ...
];
```

---

## 🌐 Browser Support

| Browser | Minimum Version |
|---------|----------------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |

**Required Features:**
- JavaScript ES6 support
- LocalStorage API
- CSS Grid and Flexbox
- CSS Custom Properties (variables)

---

## 📱 Mobile Support

Recipe Muse is fully responsive and works beautifully on:
- 📱 Smartphones (320px and up)
- 📱 Tablets (768px and up)
- 💻 Laptops (1024px and up)
- 🖥️ Desktops (1440px and up)

---

## 🐛 Known Limitations

1. **Data Sync**: Favorites are device-specific (not synced across devices)
2. **Browser Data**: Clearing browser data will delete favorites
3. **Offline Images**: No recipe images included (could be added)
4. **Recipe Count**: Limited recipes per cuisine (easy to expand)

---

## 🔮 Future Enhancement Ideas

Potential features for version 2.0:

- [ ] Recipe images
- [ ] Print-friendly recipe view
- [ ] Shopping list generator
- [ ] Ingredient substitution suggestions
- [ ] Dietary filters (vegetarian, vegan, gluten-free)
- [ ] Recipe rating system
- [ ] Recipe search functionality
- [ ] Nutritional information
- [ ] Cooking timer integration
- [ ] Recipe sharing capabilities
- [ ] Multi-language support
- [ ] Dark mode toggle

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Maintain the existing code style
- Test on multiple browsers
- Update documentation as needed
- Keep the single-file architecture
- Ensure mobile responsiveness

---

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2026 Recipe Muse

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👥 Author

Created with ❤️ for beginners learning web development

---

## 📞 Support

Having issues? Check out:
- [User Documentation](USER-DOCUMENTATION.md) - Detailed usage guide
- [GitHub Issues](https://github.com/yourusername/recipe-muse/issues) - Report bugs or request features

---

## 🙏 Acknowledgments

- Google Fonts for Playfair Display and Karla typefaces
- Inspiration from classic cookbook designs
- The global cooking community

---

## ⭐ Star This Repository

If you find Recipe Muse helpful, please give it a star! It helps others discover the project.

---

**Happy Cooking!** 🍳👨‍🍳👩‍🍳

---

*Built with vanilla HTML, CSS, and JavaScript—no frameworks, no dependencies, just pure web development.*