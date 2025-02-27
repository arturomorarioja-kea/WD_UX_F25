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
- In the listener of a form's submit event, input information must be gathered with `e.target.elementID` instead of `document.querySelector(`#elementID`). It is faster and more structured

[--> Food Repo. Make the about page a dialog. Responsiveness. clamp()]: #
[--> Show code samples Append strategies 1 & 2, Document fragment, Basic fetch]: #
[--> Show sessionStorage and localStorage]: #
[--> Show code samples CSS3 Background(https://codepen.io/arturomorarioja/pen/xxQqRgY), CSS3 Responsive Font and Image(https://codepen.io/arturomorarioja/pen/MWzpJjG)]: #

[## In-class exercise]: #

[### Colour palettes]: #
[Work in groups of 4. Find websites that use the following colour palettes (at least one website per palette):]: #
[- Monochromatic]: #
[- Complementary]: #
[- Analogous]: #
[- Triadic]: #
[- Tetradic]: #

[Show your findings to the class.]: #

[## Class takeaways]: #

[### JavaScript]: #
[Check out:]: #
[- The slide deck **Introduction to JavaScript**, with especial attention to ES modules]: #
[- Code samples:]: #
[-->  - Append strategies(https://github.com/arturomorarioja/js_append_strategies)]: #
[-->  - Append strategies 2(https://github.com/arturomorarioja/js_append_strategies_v2)]: #
[-->  - Document fragment(https://codepen.io/arturomorarioja/pen/QwLaVMj)]: #
[-->  - Basic fetch(https://github.com/arturomorarioja/js_basic_fetch)]: #
[  - API consumption(https://github.com/arturomorarioja/kea_js_api_consumption)]: #
[  - ES Modules(https://github.com/arturomorarioja/js_modules)]: #

[### Visual Design]: #
[Check out:]: #
[- The slide deck **Visual Design - Colours and Typography**]: #

[## Homework]: #

[### Stored Music CDs]: #
[Rework the music CDs exercise(https://github.com/arturomorarioja/kea_js_music_cds_solution) but now storing the information in local storage.]: #
[Proposed solution(https://github.com/arturomorarioja/kea_js_stored_music_cds_solution)]: #

[### SPA Restaurant]: #
[Rework the CSS Restaurant exercise(https://github.com/arturomorarioja/kea_css_restaurant_solution) but turning it into a Single Page Application (SPA)]: #
[Proposed solution(https://github.com/arturomorarioja/kea_css_restaurant_spa)]: #
