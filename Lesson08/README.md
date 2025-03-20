[User Experience - Spring 2025](https://github.com/arturomorarioja-kea/WD_UX_F25/blob/main/README.md)

# Lesson 8 - 20 March

[--> hang Lisa Maria Martin's audit xls in Teams]: #

## First Mandatory Assignment exercise solution
- [API Consumption](https://github.com/arturomorarioja/js_tmdb)

General feedback. Things to improve:
- Do never use absolute paths (e.g., `"/img"`). Use relative paths instead (e.g., `"img"` or `"./img"`)
- Try to avoid the use of `innerHTML` when injecting variable values that come from external sources (e.g., user input, an external API). Use a `<template>` and `cloneNode()` instead
- Because of the same reason, try to use `innerText` or `textContent` instead of `innerHTML` if you can avoid it
- HTML5 code should not be mixed with XHTML code (e.g., it is `<img>`, not `<img />`)
- CSS custom properties (variables) must be used for all colours and fonts, and they must be used consistently: just one hardcoded colour can cause grave problems regarding code maintainability
- Do not expose your private API key in a public GitHub repo. Anyone can steal it and try to attack TMDB on your behalf
- We are using JavaScript modules, so `DOMContentLoaded` is not necessary. Modules are loaded deferredly by default, so they will start executing only after the DOM content has been loaded

## In-class exercise
- Run performance tests on https://landonhotel.com/ (sample website by LinkedIn Learning) and https://www.berlingske.dk/. Analyse the results and figure out potential performance problems. Use the following:
  - Google Lighthouse
  - [Web Page Test](https://www.webpagetest.org/). Use a slow connection (3G from Mumbai)
  - [Pingdom](https://tools.pingdom.com/). Test from "Pacific - Australia - Sydney"

[## Class takeaways]: #
[Check out the following slide decks:]: #
[- **Performance and Sustainability**]: #
[- **Information Architecture - Site Structure**]: #
[Code samples:]: #
[- Deferred CSS load(https://github.com/arturomorarioja/css3_deferred)]: #
[- Responsive font and image(https://codepen.io/arturomorarioja/pen/MWzpJjG)]: #
[- Lazy loading of images in HTML5(https://github.com/arturomorarioja/html5_lazy_loading)]: #
[- ES Modules(https://github.com/arturomorarioja/js_modules), v2(https://github.com/arturomorarioja/js_modules_v2), v3(https://github.com/arturomorarioja/js_modules_v3)]: #
[- JavaScript lazy loading with `import()`(https://github.com/arturomorarioja/js_import)]: #

[## Homework]: #

[### Information Architecture]: #
[Create a sitemap for a popular website of your choice (not one with too many information levels, though). Use the sitemap format that you think more appropriate.]: #
[Work in groups of 4.]: #
[Send me a pdf file with your sitemap on Teams, so that next week we can discuss your work]: #

[### Performance and Sustainability]: #
[Run performance tests on your own websites. Find performance errors and fix them.]: #

[### Food Repo]: #
[Next week we are adding another API, this one internal, for user and favourites management. Find it here(https://github.com/arturomorarioja/food_repo_users_api_v2) and check out its endpoint and installation explanations at `README.md`]: #
