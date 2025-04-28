
<h2 class="c-project-heading--task">Reorder the grid tiles</h2>
--- task ---
Use the tile filenames to rearrange the tiles in the correct order.
--- /task ---

<h2 class="c-project-heading--explainer">Time to tidy up! 🧼</h2>

Each image tile has a filename like:

```html
bert_sampson_tile_0_1.png
```

Let’s break that down:

- `bert_sampson` is the name of the image set
- `tile` means it’s part of the grid
- The numbers `_0_1` show the **row** and **column** where the tile should appear!

So `tile_0_1` should appear in **row 0**, **column 1** — that’s the **second tile** on the **top row**.

Here is the correct layout for the **top row** of tiles, going left to right:

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 6
line_highlights: 7-10
---
<div class="grid">
  <div class="tile"><img src="bert_sampson_tile_0_0.png" alt="Tile 10"></div>
  <div class="tile"><img src="bert_sampson_tile_0_1.png" alt="Tile 1"></div>
  <div class="tile"><img src="bert_sampson_tile_0_2.png" alt="Tile 7"></div>
  <div class="tile"><img src="bert_sampson_tile_0_3.png" alt="Tile 4"></div>
--- /code ---
</div>

Rearrange all rows to unscramble the room.

<div class="c-project-callout c-project-callout--tip">

### Tip

The grid has **3 rows** (0, 1 and 2) and **4 columns** (0, 1 , 2 and 3).

The tile names help you place them in the correct order!

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If your layout looks wrong later, check that each tile is in the correct place based on the numbers in its filename.

</div>
