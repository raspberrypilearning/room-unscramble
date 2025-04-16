
<h2 class="c-project-heading--task">Add your own creative CSS styles</h2>
--- task ---
Use the <style> section to customise the page and make it your own!
--- /task ---

<h2 class="c-project-heading--explainer">Make it fancy 💅</h2>

Your layout is now working — great job! Now it is time to give your webpage a creative twist.

Try editing the `style.css` file in the editor. You could:

- Add a fun colour to the heading
- Change the font style
- Use a different border for the tiles
- Add a background colour or gradient

Here’s an example:

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2-5
---
h1 {
    color: teal;
    font-family: "Comic Sans MS", cursive, sans-serif;
    text-shadow: 2px 2px #ffcc00;
    text-align: center;
}
--- /code ---
</div>

Have fun making the page your own!

<div class="c-project-callout c-project-callout--tip">

### Tip

You can style any part of the page using CSS — try changing the tile borders, background colour, or text fonts!

To find the `style.css` file, click on the <strong>file icon</strong> to open the <strong>Project files</strong> tab:

<img src="../images/file-icon.png" alt="File icon used to open the Project files tab" width="32"/>

</div>

<div class="c-project-callout c-project-callout--try">

### Try this

Try giving your tiles a rainbow look! You can change the border colour of different tiles like this:

    .tile:nth-child(1) img {
        border-color: red;
    }

    .tile:nth-child(2) img {
        border-color: orange;
    }

    .tile:nth-child(3) img {
        border-color: yellow;
    }

Keep going with more colours to make a rainbow grid!

</div>
