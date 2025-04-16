
<h2 class="c-project-heading--task">Figure out what the filenames mean</h2>
--- task ---
Look at the tile image filenames and work out how the names tell you where each tile should go.
--- /task ---

<h2 class="c-project-heading--explainer">A secret code in every filename 🧩</h2>

Each tile image has a filename like:

```html
bert_sampson_tile_0_1.png
```

Let’s break that down:

- `bert_sampson` is the name of the image set
- `tile` means it’s part of the grid
- The numbers `_0_1` show the **row** and **column** where the tile should go!

So `tile_0_1` belongs in **row 0**, **column 1** — that’s the **second tile on the top row**.

Here’s an example set of tiles:

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 7-10
---
<div class="tile"><img src="bert_sampson_tile_0_0.png" alt="Tile 0,0"></div>
<div class="tile"><img src="bert_sampson_tile_0_1.png" alt="Tile 0,1"></div>
<div class="tile"><img src="bert_sampson_tile_0_2.png" alt="Tile 0,2"></div>
<div class="tile"><img src="bert_sampson_tile_0_3.png" alt="Tile 0,3"></div>
--- /code ---
</div>

These are all the tiles in the **top row**, going left to right.

<div class="c-project-callout c-project-callout--tip">

### Tip

The grid has **3 rows** and **4 columns** — the tile names help you place them in the correct order!

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If your layout looks wrong later, check that each tile is in the correct spot based on the numbers in its filename.

</div>
