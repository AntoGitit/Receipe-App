# Recipe Muse - User Documentation

Welcome to **Recipe Muse**, your personal culinary companion! This guide will help you get started with the app and make the most of its features.

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [Features Overview](#features-overview)
3. [How to Use the App](#how-to-use-the-app)
4. [Managing Favorites](#managing-favorites)
5. [Tips & Tricks](#tips--tricks)
6. [Troubleshooting](#troubleshooting)

---

## Getting Started

### Installation & Setup

Recipe Muse is a single-file web application that runs entirely in your browser. No server, no installation, no dependencies required!

**Steps to Run:**

1. **Save the File**: Download or save the `recipe-app.html` file to your computer
2. **Open in Browser**: Double-click the file or right-click and select "Open with" → your preferred browser
3. **That's it!** The app will load and you're ready to cook

**Supported Browsers:**
- Google Chrome (recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari
- Any modern web browser with JavaScript enabled

---

## Features Overview

### 🎯 Core Features

#### 1. **Dynamic Welcome Messages**
Every time you visit the home page, you'll be greeted with a different inspirational message! These include:
- Cooking quotes
- Food jokes
- Haiku poetry about food
- Motivational messages

#### 2. **Personalized Experience**
- Enter your first name
- Select your favorite cuisine from 27+ options worldwide
- Get recipe recommendations tailored to your taste

#### 3. **Smart Cuisine Search**
Type-ahead search functionality helps you find cuisines quickly:
- Start typing (e.g., "Ita..." for Italian)
- Matching cuisines appear instantly
- Click to select from the dropdown

#### 4. **Recipe Recommendations**
Get detailed recipes including:
- **Ingredients list** - Everything you need
- **Step-by-step instructions** - Easy to follow
- **Timing information** - Prep time, cook time, and servings
- **Visual organization** - Clean, readable format

#### 5. **Recipe Interactions**
Three ways to respond to each recipe:
- **👍 Like** - Show you enjoyed the recipe
- **👎 Not for me** - Get a different recipe from the same cuisine
- **⭐ Add to Favorites** - Save for later

#### 6. **Favorites Collection**
- Save unlimited recipes to your personal collection
- View all favorites in a beautiful grid layout
- Quick access to saved recipes
- Remove recipes you no longer need

---

## How to Use the App

### Step 1: Arrive at the Home Page

When you first open Recipe Muse, you'll see:
- A colorful header with the app name
- A unique welcome message (changes each visit!)
- Two navigation buttons: **Home** and **Favorites**

### Step 2: Enter Your Information

Fill out the simple form:

**First Name:**
- Type your first name in the text field
- This personalizes your experience

**Favorite Cuisine:**
- Click in the "Favorite Cuisine" field
- Start typing the name of your preferred cuisine
- Select from the dropdown suggestions that appear
- Available cuisines include:
  - Italian, Chinese, Mexican, Japanese, Indian, Thai
  - French, Greek, Spanish, Korean, Vietnamese, Turkish
  - Lebanese, Moroccan, Brazilian, American, Caribbean
  - Ethiopian, German, Portuguese, Russian, Malaysian
  - Indonesian, Peruvian, British, Mediterranean, Middle Eastern

### Step 3: Get Your Recipe

1. Click the **"Get My Recipe"** button
2. Wait for the brief animation (✨ Crafting your perfect recipe...)
3. Your personalized recipe appears!

### Step 4: Review Your Recipe

Each recipe card displays:

**Recipe Header:**
- Recipe name in large, elegant font
- Preparation time (⏱️)
- Cooking time (🔥)
- Number of servings (🍽️)

**Ingredients Section:**
- Complete list of all ingredients
- Quantities specified
- Easy to scan bullet list

**Instructions Section:**
- Numbered, step-by-step directions
- Clear, concise language
- Professional cooking techniques

### Step 5: Interact with the Recipe

You have three options:

**👍 Like Button:**
- Click to show you like the recipe
- Button changes to "❤️ Loved it!"
- Visual feedback confirms your choice

**👎 Not for me Button:**
- Click if the recipe isn't what you want
- Instantly generates a new recipe from the same cuisine
- Keep clicking until you find the perfect match

**⭐ Add to Favorites Button:**
- Click to save the recipe to your favorites
- Button turns orange and displays "⭐ Favorited"
- Recipe is now permanently saved (until you remove it)

---

## Managing Favorites

### Viewing Your Favorites

1. Click the **"Favorites"** button in the navigation bar
2. All saved recipes appear in a grid layout
3. Each card shows:
   - Recipe name
   - Cuisine type
   - Prep and cook times

### Opening a Favorite Recipe

1. Click on any recipe card in the Favorites page
2. You'll automatically return to the Home page
3. The full recipe details will be displayed
4. You can interact with it (like, dislike, or unfavorite)

### Removing from Favorites

**Method 1 - From Favorites Page:**
- Click "Remove from favorites" link on any recipe card
- Recipe is immediately removed from your collection

**Method 2 - From Recipe View:**
- When viewing a favorited recipe on the Home page
- Click the "⭐ Favorited" button to unfavorite it
- The button changes back to "⭐ Add to Favorites"

### Data Persistence

Your favorites are stored locally in your browser using `localStorage`:
- ✅ Favorites persist even after closing the browser
- ✅ No account or login required
- ✅ Data stays private on your device
- ⚠️ Clearing browser data will delete your favorites
- ⚠️ Favorites are device-specific (not synced across devices)

---

## Tips & Tricks

### Getting the Most Out of Recipe Muse

1. **Try Different Cuisines**
   - Don't stick to one cuisine type
   - Each cuisine has multiple recipes in the database
   - Explore and discover new favorites!

2. **Build Your Collection**
   - Save recipes you want to try later
   - Create your personal cookbook
   - Mix different cuisines in your favorites

3. **Finding Inspiration**
   - Refresh the page to see a new welcome message
   - Use the welcome messages as cooking inspiration
   - Come back daily for new quotes and haiku!

4. **Recipe Discovery**
   - If you don't like a recipe, click "Not for me"
   - You'll get a different recipe instantly
   - Keep exploring until you find the perfect dish

5. **Quick Access**
   - Bookmark the HTML file in your browser
   - Add it to your desktop for easy access
   - Open it whenever you need recipe inspiration

### Keyboard Navigation

- **Tab**: Move between form fields
- **Enter**: Submit the form
- **Spacebar**: Click buttons when focused
- **Escape**: Close cuisine dropdown

---

## Troubleshooting

### Common Issues & Solutions

**Problem: Page won't load**
- **Solution**: Make sure JavaScript is enabled in your browser
- **Solution**: Try a different browser
- **Solution**: Check that the HTML file isn't corrupted

**Problem: Cuisine dropdown doesn't appear**
- **Solution**: Make sure you're typing at least one character
- **Solution**: Click directly in the input field
- **Solution**: Try typing the full cuisine name and pressing Enter

**Problem: Favorites aren't saving**
- **Solution**: Check if browser is in private/incognito mode (localStorage won't persist)
- **Solution**: Ensure cookies and local storage are enabled
- **Solution**: Try clearing browser cache and reloading

**Problem: Recipe doesn't generate**
- **Solution**: Make sure you filled in both fields (name and cuisine)
- **Solution**: Select a cuisine from the dropdown suggestions
- **Solution**: Refresh the page and try again

**Problem: Welcome message doesn't change**
- **Solution**: Hard refresh the page (Ctrl+F5 or Cmd+Shift+R)
- **Solution**: Close and reopen the browser tab

---

## Technical Information

### Browser Requirements
- Modern browser (released within last 2 years)
- JavaScript enabled
- LocalStorage support
- Minimum screen width: 320px (mobile compatible)

### File Information
- **File name**: recipe-app.html
- **File type**: Single HTML file (includes CSS and JavaScript)
- **Size**: ~32KB
- **Dependencies**: None (completely standalone)
- **Internet required**: No (runs 100% offline)

### Data Storage
- Uses browser's localStorage API
- Maximum storage: ~5MB (more than enough for hundreds of recipes)
- Data format: JSON
- Privacy: All data stays on your device

---

## Feature Highlights

### What Makes Recipe Muse Special?

✨ **Beautiful Design**
- Retro-modern cookbook aesthetic
- Warm, inviting color palette
- Professional typography
- Smooth animations and transitions

🎨 **Thoughtful UX**
- Clean, intuitive interface
- No clutter or confusion
- Mobile-responsive design
- Accessible and easy to use

🍳 **Quality Content**
- Authentic recipes from around the world
- Clear, professional instructions
- Realistic cooking times
- Tested ingredient ratios

💾 **Zero Setup**
- No installation required
- No account creation
- No internet needed after first load
- Complete privacy

---

## Future Enhancements (Ideas for Expansion)

While the current version is complete and functional, here are ways you could enhance it:

- Add more recipes to each cuisine
- Include recipe photos
- Add ingredient substitution suggestions
- Create a shopping list feature
- Add recipe rating system
- Include dietary filters (vegetarian, vegan, gluten-free)
- Add recipe search functionality
- Include nutritional information

---

## Credits

**Recipe Muse** was created as a beginner-friendly web application to help you discover and save delicious recipes from around the world.

**Design Philosophy**: Clean, warm, and inviting—like a cherished cookbook passed down through generations.

---

## Need Help?

If you encounter any issues not covered in this documentation:

1. Check that your browser is up to date
2. Try the app in a different browser
3. Make sure JavaScript is enabled
4. Clear your browser cache and try again

---

## Enjoy Cooking! 🍳👨‍🍳👩‍🍳

We hope Recipe Muse inspires you to try new cuisines and create delicious meals. Happy cooking!

---

*Last updated: February 2026*
*Version: 1.0*