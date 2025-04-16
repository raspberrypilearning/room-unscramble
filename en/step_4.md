
<h2 class="c-project-heading--task">Reorder the image tiles</h2>
--- task ---
Use the tile filenames to rearrange the <img> elements in the correct grid order.
--- /task ---

<h2 class="c-project-heading--explainer">Time to tidy up! 🧼</h2>

Now that you understand how the filenames work, you can fix the scrambled grid.

Your goal is to arrange the tiles in row order, from top to bottom and left to right.

Here’s what the correct layout should look like:

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 20
line_highlights: 21-33
---
<div class="grid">
    <div class="tile"><img src="bert_sampson_tile_0_0.png" alt="Tile 0,0"></div>
    <div class="tile"><img src="bert_sampson_tile_0_1.png" alt="Tile 0,1"></div>
    <div class="tile"><img src="bert_sampson_tile_0_2.png" alt="Tile 0,2"></div>
    <div class="tile"><img src="bert_sampson_tile_0_3.png" alt="Tile 0,3"></div>
    <div class="tile"><img src="bert_sampson_tile_1_0.png" alt="Tile 1,0"></div>
    <div class="tile"><img src="bert_sampson_tile_1_1.png" alt="Tile 1,1"></div>
    <div class="tile"><img src="bert_sampson_tile_1_2.png" alt="Tile 1,2"></div>
    <div class="tile"><img src="bert_sampson_tile_1_3.png" alt="Tile 1,3"></div>
    <div class="tile"><img src="bert_sampson_tile_2_0.png" alt="Tile 2,0"></div>
    <div class="tile"><img src="bert_sampson_tile_2_1.png" alt="Tile 2,1"></div>
    <div class="tile"><img src="bert_sampson_tile_2_2.png" alt="Tile 2,2"></div>
    <div class="tile"><img src="bert_sampson_tile_2_3.png" alt="Tile 2,3"></div>
</div>
--- /code ---
</div>

Each <img> tag is now in the correct position based on its filename. Nice work! 🧠

<div class="c-project-output">
<pre>A correctly ordered grid showing the full room image</pre>
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

You do not need to change any CSS — just rearrange the order of the tiles inside the <div class="grid">.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If your image still looks wrong, double-check the filename numbers and make sure each tile is inside its own <div class="tile">.

</div>
