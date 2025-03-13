[User Experience - Spring 2025](https://github.com/arturomorarioja-kea/WD_UX_F25/blob/main/README.md)

# Lesson 7 - 13 March

## Class takeaways

### JavaScript
Check out:
- The slide decks **npm** and **ESLint**
- Remember to never submit the `node_modules` folder to any kind of code repo

## Homework

### ESLint
Incorporate ESLint to your projects and try different rules. Use the [ESLint configuration file sample](https://github.com/arturomorarioja/eslint_sample) for inspiration.

### Food Repo
Patiently read the code that we added today to the [Food Repo](https://github.com/arturomorarioja/js_food_repo_ux_f25). Analyse the approach to each of the problems we have solved:
- Using a `<dialog>` that must be available for several pages
- Using `<a>` for links that take the user to another page and `<button>` for actions that do not take the user to another page
- Reorganising the CSS files so that each page's file imports the general styles
- Making recipe cards clickable without having block elements inside inline elements (e.g., `<div>` inside `<a>`)
- Allowing clicking on each recipe card to take the user to `recipe.htm` passing along the recipe ID as a GET parameter (`recipe.htm?id=<recipe_id>`)
- Reading the GET parameter with `window.location.search` and `URLSearchParams`
- Fetching a different API endpoint (`/lookup.php`) to gather information about a specific recipe
- Iterating over the list of ingredients extracting only the existing ones
Try to do it on your own.

### [First Mandatory Assignment](https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344451)
- Deliver the [*API Consumption* exercise]([https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344535](https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344536))
  
The deadline is on 2/4, but I will only provide individual feedback to those who submit before Wednesday and only if you specify in your delivery that you want individual feedback.
