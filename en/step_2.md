
<h2 class="c-project-heading--task">Find what needs fixing in the code</h2>
--- task ---
Look closely at the HTML and find what is wrong. There are a few bugs hiding in the code!
--- /task ---

<h2 class="c-project-heading--explainer">Detective mode: activated 🕵️</h2>

Let’s inspect the scrambled tiles more carefully. Some things are not quite right — and it's your job to fix them.

Have a look at this section of the code:

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 15
line_highlights: 15
---
<div class="tile"><img src="bert_sampson_tile_1_3.png" alt="Tile 8">
<div class="tile"><img src="bert_sampson_tile_2_2.png" alt="Tile 9"></div>
<div class="tile"><img src="bert_sampson_tile_0_0.png" alt="Tile 10"></div>
<div class="tile"><img src="bert_sampson_tile_1_1.png" alt="Tile 11"></div>
--- /code ---
</div>

🪲 Can you spot the problem?

One of the `<div>` elements is missing a closing tag. This can cause the layout to look strange or behave unexpectedly in the grid!

<div class="c-project-callout c-project-callout--tip">

### Tip

In an HTML document, every `<div>` must have a matching `</div>`. Missing one can cause problems with the layout!

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If a tile looks like it is inside another tile or not appearing where you expect, check that all `div` tags are correctly closed.

</div>
