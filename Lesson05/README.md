[User Experience - Spring 2025](https://github.com/arturomorarioja-kea/WD_UX_F25/blob/main/README.md)

# Lesson 5 - 27 February

## First Mandatory Assignment exercise solutions
- [Restaurant](https://github.com/arturomorarioja/kea_css_restaurant_solution)
- [Music CDs](https://github.com/arturomorarioja/kea_js_music_cds_solution)

General feedback. Things to improve
- Code should be divided into folders. As projects tend to grow, file organisation can soon become unmanageable
- HTML5 code should not be mixed with XHTML code (e.g., it is `<img>`, not `<img />`
- Text should be inside a pair of `<p>` tags, not directly inside a landmark element (e.g., `<footer>`)
- Explore not-so-well-known HTML tags like `<blockquote>` or `<address>`
- The submit button in a form must always be either an `<input>` or a `<button>` of `type="submit"`, so that an event listener is added to the `submit` event of the form instead of to the `click` event of the button
- `<article>` is for groups of elements that are repeated (like cards or blog posts); <section> is for groups of elements that are not repeated (like a hero section or a descriptive text)
- When an element will repeat in the page (e.g., the delete row button), it should have a class instead of an id, as ids must be unique
- The appropriate `type` besides `text` must be used for `<input>` elements (e.g., `email`, `number`, `search`, `phone`)
- Always include some HTML input validation (e.g., `required`, `pattern`)
- CSS custom properties (variables) must be used for all colours and fonts, and they must be used consistently: just one hardcoded colour can cause grave problems regarding code maintainability
- In the listener of a form's submit event, input information must be gathered with `e.target.elementID` instead of `document.querySelector('#elementID')`. It is faster and more structured

## In-class exercise

### Colour palettes
Work in groups of 4. Find websites that use the following colour palettes (at least one website per palette):
- Monochromatic
- Complementary
- Analogous
- Triadic
- Tetradic

Show your findings to the class.

## Class takeaways

### Visual Design
Check out:
- The slide deck **Visual Design - Colours and Typography**

## Homework

### Stored Music CDs
Rework the [music CDs exercise](https://github.com/arturomorarioja/kea_js_music_cds_solution) but now storing the information in local storage.

### SPA Restaurant
Rework the [CSS Restaurant exercise](https://github.com/arturomorarioja/kea_css_restaurant_solution) but turning it into a Single Page Application (SPA)
