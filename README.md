# Project 0

Web Programming with Python and JavaScript

The website is a brief introduction to the Japanese Language. Since I need to use Japanese characters within
the page, I decided to specify the `UTF-8` character set within the head of the files.

## Pages

### `default.html`

> This serves as the main page of the website. The page contains information on the the structure of the language.

### `scripts.html`

> This section outlines the three main scripts used in the Japanese language. On page structure, this is the most complicated among the four since it utilizes the following:
>
>* bootstrap cards
>* bootstrap column classses
>* tables

### `jlpt.html`

>This section outlines the different levels on the JLPT. Depending on the display size, the headings for each level
>can appear either on the side or on top of its contents.

### `aboutme.html`

> This section contains a brief summary about me and several ways to contact me should the need arise.
  The contents of the page are enclosed in a grid changes the position of the items based on the screen size.
>
> Additionally, the social media icons serve as links to my profiles.

---

Inside the style folder are several `css` files that manage the style of the page with the same name. These css files are compiled from the related `scss` files in the same directory. For coherence in the apprearance of the whole website and additional sheet `style.scss` is also included, which all other `scss` files import.

The other folders contain media files used within in webpage.
