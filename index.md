## Play-it-Quiet is a CSS color scheme.
Play-it-Quiet on its own does nothing. It simply sets several variables for you to reference in your code.

## Play-it-Quiet provides no looks.
All Play-it-Quiet does is provide colors. You'll still have to manually apply the colors and themes to elements.

## Play-it-Quiet *will not* support SASS or Less.
If anyone else wants to, go right ahead, but I'd rather not support these languages as they hurt my ape brain.

## Play-it-Quiet is importable.
You can import it to your site by adding this tiny bit of code to your site:
```html
<link rel="stylesheet" href="https://videotoaster.github.io/Play-it-Quiet/piq.css" />
```
If you'd like to host it on your own, you can do that too.

## Play-it-Quiet is a WIP!
I'm still playing around with stuff and I plan to make a few things out of it:

* A [new.css](https://newcss.net) theme
* A CSS template for Play-it-Quiet
* ...more?

## Play-it-Quiet is dead-simple.
All of the colors you'll need are included.

Two shades of: red, green, blue, purple, orange, yellow, black, three shades of gray, and one shade of white are included.

The two-shade colors follow a format: `color-a` and `color-b`. B colors are darker than A colors. For instance:
```css
background-color: var(--bg-a);
color: var(--fg-a);
border: 2px solid var(--red-a);
```
Two of the three gray colors are `--bg-a` and `--bg-b`. The other one is `--fg-b`. White is `--fg-a`.
