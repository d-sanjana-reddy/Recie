# Recipe Finder

An interactive web app that helps you discover recipes based on the ingredients you already have. Just type in your ingredients, and the app fetches delicious recipe suggestions using the **Edamam Recipe API**. It’s a fun way to minimize food waste and explore new meal ideas.

---

## Features

- Search recipes by entering ingredients (comma-separated)  
- Clean, modern UI built with **Tailwind CSS**  
- Responsive design (works on desktop and mobile)  
- Recipe cards with images, cuisine type, and source  
- Click on a recipe card to view detailed ingredients and instructions  
- Modal popup with link to the full recipe  

---

## Tech Stack

- HTML5 – Structure  
- Tailwind CSS – Styling  
- Vanilla JavaScript – Functionality  
- Edamam Recipe API – Recipe data  

---

## Demo Preview



---

## Setup & Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/recipe-finder.git
   cd recipe-finder
2. Open the application in your browser:
   ```bash
   open RecipeFinder.html
- On Windows, just double-click `RecipeFinder.html`.
- Get your free API credentials from [Edamam Developer](https://developer.edamam.com/).
- Configure your keys by editing `RecipeFinder.html` and replacing the placeholders:
  ```javascript
  const APP_ID = 'YOUR_APP_ID';
  const APP_KEY = 'YOUR_APP_KEY';

---

## Project Structure
  recipe-finder/  
  │── RecipeFinder.html   # Main application file  
  │── README.md           # Documentation  

---

## Future Enhancements

- Save favorite recipes locally  
- Add filters (diet type, calories, cuisine)  
- Deploy to GitHub Pages or Netlify for live use  

