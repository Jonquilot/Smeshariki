# About

A small static multi-page HTML website dedicated to the Russian animated series **"Smeshariki"** ("Смешарики"). The site presents linguistic corpus research of each character on their own page, styled with custom CSS.

## Project structure

```
Smeshariki/
├── index.html        # Home page / entry point
├── repo.html         # Repository / project info page
├── ngram.html        # N-gram analisys page
├── barash.html       # Character analisys page: Barash
├── karich.html       # Character analisys page: Karich
├── kopatich.html     # Character analisys page: Kopatich
├── krosh.html        # Character analisys page: Krosh
├── losyash.html      # Character analisys page: Losyash
├── nyusha.html       # Character analisys page: Nyusha
├── pin.html          # Character analisys page: Pin
├── sovunya.html      # Character analisys page: Sovunya
├── yozhik.html       # Character analisys page: Yozhik
├── styles/           # Website UI elements
    ├── fonts/        # Font collection
    ├── imgs/         # Images used on the website
    └── style.css     # CSS stylesheets for the site
└── README.md
```

## CSS overview

### Root variables

- `div`     — color for the main div
- `text`    — color for the main text
- `nav_act` — color for current navigation link

### Tags specifications

- `@font-face` — custom font import
- `body`       — font, background, align and padding set
- `td`         — padding set
- `a`          — size and font color set
- `a:hover`    — font color set
- `li::marker` — marker color matched with text color

### Classes

- `header1`        — main text headings
- `nav_link`       — page link in upper havigation bar
- `nav_link:hover` — color for hovered link
- `nav_current`    — current page link in upper navigation bar
- `nav_table`      — table for upper navigation bar
- `main_div`       — div for main content
- `decor`          — decorational images
- `mini`           — scroll to top icon
- `frame`          — images of participants
- `portrait`       — images of characters on their analysis page
- `text`           — main text

## Tech stack

- **HTML** — page structure and content
- **CSS** — styling, located in the `styles/` directory

No build tools, frameworks, or external dependencies are required.

## Getting started

Since the site is built with plain HTML and CSS, no installation or build step is needed.

1. For modification:
   ```bash
   git clone https://github.com/Jonquilot/Smeshariki.git
   ```
2. For utilization:
    open the link: https://jonquilot.github.io/Smeshariki/

## Pages overview

| Page | Description |
|---|---|
| `index.html` | Main landing page of the site |
| `repo.html` | Project/repository information page |
| `ngram.html` | Additional content page |
| `barash.html`, `karich.html`, `kopatich.html`, `krosh.html`, `losyash.html`, `nyusha.html`, `pin.html`, `sovunya.html`, `yozhik.html` | Individual pages for each Smeshariki character |

## Contributing

This is an educational/fun project. Feel free to fork it and adapt it for your own use.

## License

No license has been specified for this repository.