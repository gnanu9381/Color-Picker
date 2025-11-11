# Color Picker

A simple and interactive web application that allows users to change the background color of the page by clicking on color buttons.

## 📋 Project Overview

Color Picker is a beginner-friendly JavaScript project that demonstrates basic DOM manipulation and event handling. Users can click on predefined color buttons to instantly change the page's background color, with the selected color's hex code displayed in real-time.

## ✨ Features

- **Interactive Color Selection**: Four predefined color buttons (Grey, Green, Blue, and Purple)
- **Live Color Display**: Shows the selected color's hex code in real-time
- **Responsive Design**: Built with Bootstrap 4 for a clean, responsive interface
- **Full-Screen Background**: Color changes apply to the entire viewport
- **Visual Feedback**: Clear button styling with color indicators

## 🎨 Available Colors

| Color | Hex Code | Button |
|-------|----------|--------|
| Grey | `#e0e0e0` | Button 1 |
| Green | `#6fcf97` | Button 2 |
| Blue | `#56ccf2` | Button 3 |
| Purple | `#bb6bd9` | Button 4 |

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling and layout
- **JavaScript (Vanilla)**: DOM manipulation and event handling
- **Bootstrap 4**: Responsive design framework
- **jQuery**: Lightweight utilities (via Bootstrap)

## 📁 Project Structure

```
Color-Picker/
├── index.html      # Main HTML file with page structure
├── script.js       # JavaScript functions for color changes
├── styles.css      # Custom CSS styling
└── README.md       # Project documentation
```

## 🚀 How to Use

1. Open `index.html` in your web browser
2. Click on any of the four color buttons
3. The background color will change immediately
4. The hex code of the selected color will be displayed below the buttons

## 💻 Code Overview

### JavaScript Functions

The `script.js` file contains four main functions:

- `changeBgToGreyAndUpdateText()`: Changes background to grey (#e0e0e0)
- `changeBgToGreenAndUpdateText()`: Changes background to green (#6fcf97)
- `changeBgToBlueAndUpdateText()`: Changes background to blue (#56ccf2)
- `changeBgToPurpleAndUpdateText()`: Changes background to purple (#bb6bd9)

Each function:
1. Updates the background color of the main container
2. Updates the displayed hex code in the UI

### CSS Classes

Key styling classes used in the project:

- `.button`: Base button styling with rounded corners and border
- `.color-picker-bgcontainer`: Main container with full viewport height
- `.heading-edit`: Large, bold heading styling
- `.text-edit`: Dark text container displaying the current color
- `.button-1`, `.button-2`, `.button-3`, `.button-4`: Individual button background colors

## 📚 Learning Concepts

This project is great for learning:

- ✅ DOM selection with `getElementById()`
- ✅ DOM manipulation with `style` property
- ✅ Event handling with `onclick` attributes
- ✅ Working with Bootstrap framework
- ✅ Basic HTML structure and semantics
- ✅ CSS styling and layout
- ✅ JavaScript functions and logic

## 🎓 Future Enhancements

Potential improvements for the project:

- Add a custom color picker input
- Generate random colors
- Add color history functionality
- Implement copy-to-clipboard for hex codes
- Add dark mode toggle
- Save selected color to localStorage
- Add smooth color transitions
- Include RGB and HSL color format options

## 📝 Notes

- The page uses "Open Sans" font family (via Bootstrap's default fonts)
- Full viewport height is utilized for the color display
- Color buttons are 100x100 pixels with 20px border radius
- The current color hex code is displayed with a blue highlight color (#49a6e9)

## 👨‍💻 Author

gnanu9381

## 📄 License

Feel free to use and modify this project for learning purposes.

---

**Enjoy exploring colors!** 🎨
