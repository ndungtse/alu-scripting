# css_advanced

Styling the **SmileSchool** landing page to match the designer file (Figma).
This project picks up the semantic `index.html` from [html_advanced](../html_advanced) and adds all the visual style in `styles.css`, using only HTML and CSS.

![SmileSchool design](images/school_page.png)

## Files

| File | Description |
| --- | --- |
| `index.html` | The full page, copied from `html_advanced`, with `styles.css` imported in the `head` |
| `styles.css` | Every style of the page, organized by section |
| `images/` | Logo, photos, icons and the hero background exported from Figma |

## What each section looks like

| Task | Section | Key styles |
| --- | --- | --- |
| 2 | Header and banner | Centered 1100px header over a grayscale hero photo fading to navy, 120px title, rounded purple button, round avatars for the 4 pros |
| 3 | Quote | Purple background, round author photo on the left, quote with bold name and italic title on the right |
| 4 | Most popular tutorials | 4 rounded cards with a play button over the thumbnail, purple author and duration, 5-star rating |
| 5 | Free membership | Navy background, 4 centered items with the purple smile icon, register button |
| 6 | F.A.Q. | Light 60px title and a 2 by 2 grid of questions |
| 7 | Footer | Navy background, logo on the left, social links on the right, copyright centered underneath |

## Design tokens

| Token | Value |
| --- | --- |
| Font | Source Sans Pro (300, 400, 600, 700, italic) |
| Navy | `#071629` |
| Purple | `#c271ff` |
| Gray text | `#838a94` |

## Learning objectives

- What CSS is and how to add style to an element
- What a class and a selector are
- How to compute the specificity of a CSS selector
- What the box properties are (margin, border, padding, content)
- How the browser loads a webpage

## Resources

- [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/)
- [Specifics on CSS Specificity](https://css-tricks.com/specifics-on-css-specificity/)
- [CSS (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS)
