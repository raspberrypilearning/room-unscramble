
<h2 class="c-project-heading--task">See the room</h2>
--- task ---
Run the starter project and look at the room that appears. It looks a little... scrambled! 👀
--- /task ---

In this project, you are going to figure out how the image tiles work, then rearrange the HTML to fix the room! 🛠️

<h2 class="c-project-heading--explainer">Something's not quite right…</h2>

The tiles are in a grid, but the room image looks mixed up. The pieces are there, but not in the right places.

Look at lines 10 and 12.

What do you notice?  
- One tile is missing its `alt` text  
- Another tile has a typo in the filename — it says "tiel" instead of "tile"! 🐞

Fix those two lines.

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 6
line_highlights: 10, 12
---
<div class="grid">
    <div class="tile"><img src="bert_sampson_tile_1_0.png" alt="Tile 0"></div>
    <div class="tile"><img src="bert_sampson_tile_0_1.png" alt="Tile 1"></div>
    <div class="tile"><img src="bert_sampson_tile_2_0.png" alt="Tile 2"></div>
    <div class="tile"><img src="bert_sampson_tile_2_3.png" alt="Tile 3"></div>
    <div class="tile"><img src="bert_sampson_tile_0_3.png" alt="Tile 4"></div>
    <div class="tile"><img src="bert_sampson_tile_1_2.png" alt="Tile 5"></div>
</div>
--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

You can use the preview panel in the editor to see how your webpage looks as you make changes. Try scrolling down and checking how the tiles appear.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If some of the tiles are not showing, check the image `src` paths in the HTML. A small typo in the filename — like `tiel` instead of `tile` — can stop the image from loading!

</div>
