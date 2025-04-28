
<h2 class="c-project-heading--task">Close the div</h2>
--- task ---
Make the room appear as a 4 x 3 grid.
--- /task ---

<h2 class="c-project-heading--explainer">Detective mode: activated 🕵️</h2>

Inspect the scrambled tiles more carefully. 

🪲 Can you spot the problem?

One of the `<div>` elements is missing a closing tag. This can cause the layout to look strange or behave unexpectedly in the grid.

Close the `<div>` on line 15.

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 15
line_highlights: 15
---
<div class="tile"><img src="bert_sampson_tile_1_3.png" alt="Tile 8"></div>
<div class="tile"><img src="bert_sampson_tile_2_2.png" alt="Tile 9"></div>
<div class="tile"><img src="bert_sampson_tile_0_0.png" alt="Tile 10"></div>
<div class="tile"><img src="bert_sampson_tile_1_1.png" alt="Tile 11"></div>
--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

In an HTML document, every `<div>` must have a matching `</div>`.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If a tile looks like it is inside another tile or not appearing where you expect, check that all `div` tags are closed correctly.

</div>
