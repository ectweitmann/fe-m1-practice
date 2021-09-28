## Chapter 3 and 4 Question Responses
1.
- **Ordered Lists**: are lists where each item in the list is numbered.
  - The ordered list is created with the `<ol>` element and each item in the list is contained in `<li></li>`.
- **Unordered Lists**: are lists that begin with a bullet point (rather than characters that indicate order.)
  - The unordered list is created with the `<ul>` element and each item in the list is contained in `<li></li>`.
- **Definition lists**: are made up of a set of terms along with the definitions for each of those terms.
  - The definition list is created with the `<dl>` element, inside you will usually see the elements `<dt>`
    (the definition term) and `<dd>` (the terms definition).
2. The basic structure is: `<a href="http://www.google.com">Google</a>`
  - Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and
    the closing `</a>` tag.
  - You specify which page you want to link to using the `href` attribute
3. The attribute you should include is the `target` attribute and you want to set its value to "_blank"
4. To link to a specific part of the same page:
  - You first need to identify the points in the page that the link will go to. You do this using the **id**
    **attribute** (which can be used on _every_ HTML element).
  - Next to link an element that uses an id attribute, you use the `<a>` element again. However, in this case,
    the value of the `href` attribute starts with the # symbol and is followed by the value of the id attribute of the element you want to link to.

## Chapter 10, 11, and 12 Question Responses
1. CSS allows you to create rules that specify how the content of an element should appear.
2. CSS stands for **Cascading Style Sheets**. In CSS the "cascade" is an algorithm that defines how to combine
   property values originating from different sources.
3. `p` (selector) `{font-family: Arial;}` (declaration).
  - A CSS rule contains two parts: a **selector** and a **declaration**
    - **Selectors**: indicate which element the rule applies to.
    - **Declarations**: sit inside curly brackets `{}` and indicate how the elements referred to in the
      selector should be styled. Made up of two parts:
      - **Properties**: indicate the aspects of the element you want to change. (e.g. color, font, width,
        height, and border)
      - **Values**: specify the settings you want to use for the chosen properties.
4. The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to
   style the page. It is an empty element and lives inside the `<head>` element. It should use three attributes:
   - `href`: this specifies the path to the CSS file (which is often placed in a folder called css or styles)
   - `type`: this attribute specifies the type of document being linked to. The value should be "text/css"
   - `rel`: this specifies the relationship between the HTML page and the file it is linked to. The value
     should be "stylesheet" when linking to a CSS file.
5. When building a site with more than one page, you should use an external CSS style sheet. This:
  - Allows all pages to use the same style rules (rather than repeating them in each page).
  - Keeps the content separate from how the page looks.
  - Means you can change the styles used across all pages by altering just one file (rather than each
    individual page).
6. **Hex Codes**: these are six-digit codes that represent the amount of red, green, and blue in a
   color, preceded by a pound or hash # sign.
7. The three parts of an HSL color property are **Hue**, **Saturation**, and **Lightness**.
  - **Hue**: the colloquial idea of color, is often represented as a color circle.
  - **Saturation**: the amount of gray in a color.
  - **Lightness**: the amount of white (lightness) or black (darkness) in a color.
8. The three main categories of typeface are: **serif**, **sans-serif**, and **monospace**.
  - **Serif**: have extra details on the ends of the main strokes of the letters.
  - **Sans-Serif**: have straight ends to letters, and therefore have much cleaner design.
  - **Monospace**: every letter in a monospace (or fixed-width) font is the same width. (Non-monospace
    fonts have different widths.)
9. The main three units used to specify font-size are: **pixels**, **percentages**, and **ems**.
  - **Pixels**: are commonly used because they allow web designers very precise control over how much space their text takes up (the number of pixels is followed by the letters "px").
  - **Percentages**: the default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px and 200% would be 32px.
  - **Ems**: an em is equivalent to the width of a letter "m".
