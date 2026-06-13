# About

A small static multi-page HTML website dedicated to the Russian animated series **"Smeshariki"** ("Смешарики"). The site presents linguistic corpus research of each character on their own page, styled with custom CSS.

## Project structure

```
Smeshariki/
├── index.html        # Home page / entry point
├── repo.html         # Repository / project info page
├── ngram.html        # N-gram analysis page
├── barash.html       # Character analysis page: Barash
├── karich.html       # Character analysis page: Karich
├── kopatich.html     # Character analysis page: Kopatich
├── krosh.html        # Character analysis page: Krosh
├── losyash.html      # Character analysis page: Losyash
├── nyusha.html       # Character analysis page: Nyusha
├── pin.html          # Character analysis page: Pin
├── sovunya.html      # Character analysis page: Sovunya
├── yozhik.html       # Character analysis page: Yozhik
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
| `ngram.html` | N-grams analysis page page |
| `barash.html`, `karich.html`, `kopatich.html`, `krosh.html`, `losyash.html`, `nyusha.html`, `pin.html`, `sovunya.html`, `yozhik.html` | Individual analysis pages for each Smeshariki character |

## Contributing

This is an educational/fun project. Feel free to fork it and adapt it for your own use.

## License

No license has been specified for this repository.