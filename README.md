# Ramadan 2025 Calendar

This is a **Ramadan 2025 Calendar** web application that displays a calendar for the month of Ramadan, showing daily Quranic verses and Duas for each day. The user can click on a date to view a popup with the corresponding verse and Dua.

## Features
- Displays a Ramadan calendar for 2025.
- Provides a Quranic verse for each day.
- Includes a daily Dua for every day of Ramadan.
- Interactive UI with hover effects and popup messages.
- Responsive design that works on different screen sizes.

## Technologies Used
- **HTML**: Structure of the web page.
- **CSS**: Styling and layout design.
- **JavaScript**: Dynamic calendar generation and event handling.

## Installation & Usage
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-repo/ramadan-calendar.git
   cd ramadan-calendar
   ```
2. **Open the Project:**
   - Simply open `index.html` in your browser.
   - Ensure `style.css` is in the same directory for proper styling.

## How It Works
- When the page loads, it generates a calendar with clickable days.
- Each click triggers a popup displaying a random Quranic verse and a specific Dua for that day.
- The user can close the popup and select other days.

## File Structure
```
📂 ramadan-calendar
│── 📜 index.html       # Main HTML file
│── 📜 style.css        # Stylesheet
│── 📜 script.js        # JavaScript logic
│── 📜 README.md        # Documentation
```

## Known Issues & Fixes
- **Dua not displaying properly?** Ensure the `duas` array is correctly indexed in `script.js`:
  ```js
  const dailyDua = duas[this.dataset.day - 1] || "Dua not available.";
  ```

## Future Enhancements
- Add prayer times integration.
- Include a Hijri calendar conversion.
- Provide multilingual support.

## Contribution
Feel free to submit issues or pull requests to improve the project!

## License
This project is open-source and free to use.

---
🌙 **Ramadan Mubarak! May this Ramadan bring peace and blessings to all.**
