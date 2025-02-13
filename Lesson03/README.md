[User Experience - Spring 2025](https://github.com/arturomorarioja-kea/WD_UX_F25/blob/main/README.md)

# Lesson 3 - 13 February

## Homework exercise solution
- [Temperature converter](https://github.com/arturomorarioja/kea_js_temperature_converter_solution)

## In-class exercise

### Project Gutenberg - API consumption
Create an application that consumes the `books` endpoint of [Gutendex](https://gutendex.com/) (the Project Gutenberg API) and displays a series of book cards including book title, authors (notice that there can be more than one), cover image, description (there can be more than one, but just use the first one; notice that there can be no description, so account for it), and a link to the HTML version of the book in the Project Gutenberg page.

![image](https://github.com/user-attachments/assets/b4f998ca-b38f-4b34-8834-408653ce2729)

![image](https://github.com/user-attachments/assets/8f07ebae-4446-4482-b4ae-dd62c8a4caff)

[Proposed solution](https://github.com/arturomorarioja/js_project_gutenberg)

## Class takeaways

### HTML5
Check out the slide deck **HTML5**, with especial attention to:
- The difference between absolute and relative paths

### JavaScript
Check out:
- The slide deck **JavaScript - The DOM**, with especial attention to element creation
- The slide deck **JavaScript - API Consumption**, with especial attention to JSON and Fetch
- Code samples:
  - [Append strategies](https://github.com/arturomorarioja/js_append_strategies)
  - [Append strategies 2](https://github.com/arturomorarioja/js_append_strategies_v2)
  - [Document fragment](https://codepen.io/arturomorarioja/pen/QwLaVMj)
  - [Basic fetch](https://github.com/arturomorarioja/js_basic_fetch)

## Homework

### Project Gutenberg
Rework it at home. Make sure that you are using the correct syntax. Study the JSON data the API returns before using it, and make sure that you are following a sound strategy (e.g., checking whether you need to iterate a series of fetch requests or if you need to iterate the data that the fetch request provides).

### First Mandatory Assignment(https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344451)
- Do the [*Music CDs* exercise](https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344535). If you decide to submit, specify whether you want individual feedback
- Start working on the [*API consumption* exercise](https://kea-fronter.itslearning.com/LearningToolElement/ViewLearningToolElement.aspx?LearningToolElementId=1344536). Take the following into account
  - You need to sign up to [TMDB](https://www.themoviedb.org/signup) (The Movie DataBase) in order to get an API key
  - Find the endpoints you need in [TMDB's API Reference](https://developer.themoviedb.org/reference/intro/getting-started):
![image](https://github.com/user-attachments/assets/45b18cd9-aca3-4b46-bfa2-a90e44dd8bad)
  - Before implementing the corresponding `fetch()` requests, read each endpoint's documentation in the central and right side of the page
  - Try to optimize your code so that you do not need to make four independent `fetch()` requests
