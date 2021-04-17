- **The goal** that my website aims to achieve, is to allow users to find a dish, and then easily view all instructions and equipment required to cook that dish.
- In terms of **demographics**, I will be building this app for anyone that is searching for a way to make the cooking process seamless. Anyone from a young child to a senior citizen should be able to use this site to cook something.
- The **data** that I will be using will come from the [Spoonacular API](https://spoonacular.com/food-api). I will use this API to get recipes, equipment, ingredients, images, and cooking tips to display to the user.
- In terms of functionality, the user should be able to see the type of dish that they might like to eat (American, Asian, etc...). Once they select a type, they should be able to see a list (sorted alphabetically) of all foods having that type. From there I will implement some basic filtering, allowing a user to display food by, min/max carbs, fat, or, calories. Once the user clicks on a dish, they will be taken to a page displaying a summary of the recipe, and the instructions to make it, in a clear, linear fashion. Also, there should be a box on the side of the page displaying ingredients, and equipment, (**Optional**) with the ability to check off what the user has already.
- The user should be able to sign-up so that they can save their favorite recipes.
- In my database, I will have a table containing all users that have signed up, a table containing a list of the names of the various recipes, and an id corresponding to that recipe id in the Spoonacular API. I will have a table containing [a list of 1000 of the most popular ingredients and their id's](https://spoonacular.com/food-api/docs#List-of-Ingredients). Somehow I will have to get a list of equipment into the database, or I can use the [functionality that the API provides](https://spoonacular.com/food-api/docs#Get-Recipe-Equipment-by-ID). I will also need a users_recipes table so that the app remembers a user's favorite recipes.
- The **stretch goal** for me would be providing a link to a website for every step of every recipe, which will give a how-to on that step.

