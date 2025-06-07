# Best-recipe-
const favoriteRecipe = {
  recipeTitle: "Шоколадный торт",
  servings: 8,
  ingredients: [
    "2 яйца",
    "200 г сахара",
    "100 г муки",
    "50 г какао",
    "1 ч.л. разрыхлителя",
    "100 мл молока",
    "100 г масла"
  ],
  directions: "Смешайте все ингредиенты, вылейте в форму и выпекайте при 180°C 30 минут."
};

console.log(`Название рецепта: ${favoriteRecipe.recipeTitle}`);
console.log(`Порции: ${favoriteRecipe.servings}`);
console.log("Ингредиенты:");
for (let i = 0; i < favoriteRecipe.ingredients.length; i++) {
  console.log(`- ${favoriteRecipe.ingredients[i]}`);
}
console.log(`Инструкция: ${favoriteRecipe.directions}`);
