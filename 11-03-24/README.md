
---


## Usage

1. Copy the following HTML code and paste it into your HTML file:

   ```html
   <p></p><p a></p><p c></p><p d></p>
   ```

2. Copy the following CSS code and paste it into your CSS file:

   ```css
   *{background:#FAD;color:#8B0}
   p{width:100px;height:20px;margin:100px 142px;box-shadow:0 0 0 21px}
   [a]{width:180px;margin:-80px 102px}
   [c]{width:260px;margin:100px 62px}
   [d]{transform:rotate(90deg);margin:-160px 142px;box-shadow:106px 0,-106px 0}
   ```

3. Open your HTML file in a web browser to see the circular paragraphs with shadow effects.

## Explanation

The provided code consists of multiple HTML paragraph elements `<p></p>`, each with custom attributes `a`, `c`, and `d`, and accompanying CSS styles to achieve the following:

- Each paragraph is styled with a specific width, height, margin, and box-shadow to create the desired appearance.
- The `*` selector sets the background color of the entire page to a light pink (`#FAD`) and text color to a dark pink (`#8B0`).
- The paragraphs are positioned and styled differently using CSS attribute selectors (`[a]`, `[c]`, `[d]`), allowing for varied appearances and positions on the page.
- The `transform: rotate(90deg)` property is used to rotate the paragraph with attribute `d` by 90 degrees, creating a vertical layout.

This setup results in multiple circular paragraphs with shadow effects displayed on the page, each with its unique styling and position.

--- 

Feel free to adjust the content and formatting according to your preferences.