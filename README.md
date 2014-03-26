# vuri
A simple responsive two column CSS grid framework.

## What's so special about vuri?
- Uses HTML5 data attributes, thus keeping your grid seperate from your styles
- Two halves make a whole. Each row only has either one or two columns.
- A seperate `row` div to contain columns is not necessary
- Simple to learn because there's little to learn


## Usage
- Include `vuri.css` in your web page. Here's an example. Note the `data-` HTML attribute tags.

```
<!doctype html>
<html>
<head>
    <!-- Include vuri here -->
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
- The grid is initiated within any div/element that contains the `data-vuri` attribute. Do this just once.
- Each row can contain upto 2 columns. Either a single *whole* column or 2 *half* columns.
- A row with just one whole column is drawn in a div/element that contains the `data-vuri-whole` attribute.
- A row with two half columns are drawn in div/elements the contain the `data-vuri-half` attribute.


## Does using data attributes hurt the semantic layout of the web page?
No. All data attributes that begin with `data-` do not pose any semantic casualties to the web page.


## How do you say vuri
Say `vuri` like you'd say _hurry_ but with a _v_ instead of a _h_.

`vuri` is the Telugu word for paddy crop. Paddy crops are planted in a [beautiful grid like layout](https://www.flickr.com/photos/jasohill/5811407971).


### Notes
Help `vuri` mature by leaving feedback or reporting issues in this repo's issues section.


## Credits
- Written atop [Toast CSS](https://daneden.me/toast)
- Based on [Sam Soffes Grid System](http://sam.roon.io/my-grid-system)
