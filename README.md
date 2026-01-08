# beautiful-automatic-daily-recipe-book

A beautiful, interactive daily recipe book web application with an elegant green theme. Get a new recipe automatically each day!

![Recipe Book Preview](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

<img width="1891" height="1890" alt="image" src="https://github.com/user-attachments/assets/3ecd0746-44d5-42f7-98bf-b9419bf3c2fe" />

## ✨ Features

- **Automatic Daily Rotation**: Shows a different recipe each day based on the current date
- **7 Delicious Recipes**: Curated collection of easy-to-follow recipes
- **Beautiful Green Theme**: Calming, nature-inspired color scheme
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Browse through all recipes with next/previous buttons
- **Detailed Instructions**: Step-by-step cooking instructions with visual numbering
- **Chef's Tips**: Helpful cooking tips for each recipe
- **Recipe Metadata**: Clear display of prep time, cook time, and servings

## 🍽️ Recipe Collection

1. **Classic Vegetable Stir Fry** - Quick and healthy weeknight dinner
2. **Creamy Tomato Pasta** - Comfort food at its finest
3. **Honey Garlic Chicken** - Sweet and savory perfection
4. **Mediterranean Chickpea Salad** - Fresh and nutritious
5. **Beef Tacos with Guacamole** - Mexican favorite
6. **Lemon Herb Baked Salmon** - Elegant and healthy
7. **Vegetable Fried Rice** - Asian-inspired classic

## 🚀 Getting Started

### Prerequisites

No installation required! This is a pure HTML/CSS/JavaScript application that runs entirely in the browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/daily-recipe-book.git
```

2. Navigate to the project directory:
```bash
cd daily-recipe-book
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Alternatively, you can simply double-click the `index.html` file to open it in your default browser.

## 📖 Usage

- **View Today's Recipe**: The page automatically displays the recipe for the current day
- **Navigate Recipes**: Use the "Previous Day" and "Next Day" buttons to browse all recipes
- **Read Instructions**: Follow the numbered step-by-step instructions for perfect results
- **Check Ingredients**: All ingredients are clearly listed with quantities
- **Get Cooking Tips**: Don't miss the chef's tip at the bottom of each recipe!

## 🎨 Customization

### Adding New Recipes

Edit the `recipes` array in the JavaScript section:

```javascript
const recipes = [
    {
        title: "Your Recipe Name",
        prepTime: "15 minutes",
        cookTime: "20 minutes",
        servings: "4 servings",
        ingredients: [
            "Ingredient 1",
            "Ingredient 2",
            // Add more ingredients
        ],
        instructions: [
            "Step 1",
            "Step 2",
            // Add more steps
        ],
        tip: "Your helpful cooking tip here"
    },
    // Add more recipes
];
```

### Changing Colors

Modify the CSS gradient in the `body` style:

```css
background: linear-gradient(135deg, #1a4d2e 0%, #2d7a4f 100%);
```

Replace with your preferred color codes to customize the theme.

## 🌐 Deployment

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to Pages section
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/daily-recipe-book`

### Deploy to Netlify

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Deploy with default settings
4. Your site will be live instantly!

### Deploy to Vercel

```bash
npm i -g vercel
vercel
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-recipe`)
3. Add your recipe or improvement
4. Commit your changes (`git commit -m 'Add amazing new recipe'`)
5. Push to the branch (`git push origin feature/amazing-recipe`)
6. Open a Pull Request

### Recipe Submission Guidelines

- Include accurate prep and cook times
- Provide clear, step-by-step instructions
- List all ingredients with measurements
- Add a helpful cooking tip
- Test the recipe before submitting!

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Recipe inspiration from various cooking communities
- Design inspired by modern web aesthetics
- Built with love for home cooks everywhere

## 📧 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/daily-recipe-book](https://github.com/yourusername/daily-recipe-book)

---

⭐ **Star this repository if you found it helpful!** ⭐

Made with 💚 and fresh ingredients
