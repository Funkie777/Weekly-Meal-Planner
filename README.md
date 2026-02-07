# Weekly Dinner Planner

A simple web-based meal planner that generates 4 weekday dinner menus with recipes and a consolidated Waitrose shopping list. Download recipes and shopping lists as images for easy sharing and meal planning apps.

## Features

- **15 High-Protein Meals**: Each meal targets 820-880 calories with 42-48g protein per serving
- **Random Weekly Generator**: Get 4 different meals each week from the full database
- **Detailed Recipes**: Step-by-step cooking instructions for each meal
- **Shopping List**: Auto-generated Waitrose shopping list organized by department
- **Download as Images**: Export recipes and shopping lists as PNG images for iPhone
- **Selective Download**: Choose which recipes to download with checkboxes
- **Calorie Details**: Each image includes full calorie and protein information
- **Print-Friendly**: Clean print layout for physical meal planning
- **Mobile Responsive**: Works on phones, tablets, and desktop

## How to Use

1. **Open the file**: Simply open `meal-planner.html` or `index.html` in any web browser
2. **Generate a week**: Click "Generate New Week" to get 4 random dinner meals
3. **Select meals**: Use checkboxes to select which recipes you want
4. **Download options**:
   - **Download All Recipes**: Get all 4 recipes as separate PNG images
   - **Download Selected**: Get only checked recipes as PNG images
   - **Download Grocery List**: Get the shopping list as a PNG image
5. **Upload to meal planner**: Save images to iPhone and upload to your preferred meal planning app

## Download Features

Each downloaded recipe image includes:
- Meal name and day number
- Calories and protein per serving
- Full ingredient list (serves 2)
- Step-by-step cooking method

Shopping list image includes:
- All ingredients organized by department
- Total number of meals
- Average calories per meal

## Meals Included

The planner includes 15 different meals:
- Garlic Butter Chicken with Roast Potatoes
- Beef Stir-Fry with Rice Noodles
- Baked Salmon with Sweet Potato and Greens
- Pork Chops with Mash and Green Beans
- Turkey and Vegetable Stir-Fry
- Chicken Fajita Bowl with Rice
- Beef Mince with Couscous
- Pan-Fried Sea Bass with New Potatoes
- Lamb Kofta with Greek Salad
- Prawn and Chorizo Paella
- Thai Green Curry with Chicken
- Mediterranean Baked Cod
- Spicy Sausage Pasta
- Teriyaki Salmon with Noodles
- Chicken Shawarma with Flatbread

## Technical Details

- No installation required
- No backend or database needed
- Works offline once downloaded (except for image download feature which needs html2canvas CDN)
- Pure HTML/CSS/JavaScript
- All data stored in the file itself
- Uses html2canvas library for image generation

## Customization

To add or modify meals, edit the `mealDatabase` array in the JavaScript section at the bottom of the HTML file. Each meal object requires:
- `name`: Meal title
- `calories`: Calorie count per serving (number)
- `protein`: Protein in grams (string with "g")
- `ingredients`: Array of ingredient objects with `item`, `qty`, and `category`
- `method`: Array of cooking steps

## Browser Compatibility

Works best in modern browsers (Chrome, Safari, Firefox, Edge). Image download feature requires JavaScript enabled.

## License

Free to use and modify for personal use.

