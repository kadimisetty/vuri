# vuri
A simple responsive two column CSS grid framework.

## Why another grid system?
- Uses data attributes thus keeping your grid speerate from your styles
- A seperate `row` div to contain columns is not necessary
- Simple to learn because there's little to learn
- Two halves make a whole. Each row only has either one or two columns.

## Install
- Include `vuri.css` in your web page.

## Usage
An example page `index.html` that uses `vuri`. Note the `data-` HTML attribute tags.

```
<!doctype html>
<html>
<head>
    <!-- vuri -->
    <link rel="stylesheet" href="assets/styles/vuri.css">
</head>
<body>
    <div data-vuri>
        <header data-vuri-whole>
            <h1>Chucky Cheese</h1>
        </header>

        <section>
            <p data-vuri-half>One half goes here.</p>
            <p data-vuri-half>The other half goes here.</p>
        </section>

        <footer data-vuri-whole>
            <p>Have a nice day!</p>
        </footer>
    </div>
</body>

```

If you'd like more explanation - 
- The grid is initiatied within any div/element that contains the `data-vuri` data attribute.
- Each row can either contain a single *whole* column or 2 *half* columns.
- A row with just one whole column is drawn in a div/element that contains the `data-vuri-whole` data attribute.
- A row with two half columns are drawn in div/elements the contain the `data-vuri-half` data attribute.


## How do you say `vuri`
`vuri` is the Telugu word for paddy crop. Paddy crops are planted in a beautiful grid like layout.
Say `vuri` like _worry_ but with a _v_ instead of a _w_.


## Credits
- Written atop [Toast CSS](https://daneden.me/toast)
- Based on [Sam Soffes Grid System](http://sam.roon.io/my-grid-system)
