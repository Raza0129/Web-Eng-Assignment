# Azure Bistro & Grill — Website

A 12-page restaurant website built with **pure HTML and CSS** (no JavaScript, no frameworks) as a web design assignment.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About Us | `about.html` |
| Menu | `menu.html` |
| Gallery | `gallery.html` |
| Our Chefs | `chefs.html` |
| Reservations | `reservations.html` |
| Events & Catering | `events.html` |
| Locations | `locations.html` |
| Testimonials | `testimonials.html` |
| Blog | `blog.html` |
| FAQ | `faq.html` |
| Contact | `contact.html` |

## Tech notes

- Single shared stylesheet: `assets/css/style.css`
- Mobile navigation menu and FAQ accordion are built with the CSS-only checkbox hack (no JavaScript used anywhere)
- Fully responsive layout (flexbox/grid with breakpoints for tablet and mobile)
- Images are represented with styled CSS placeholder blocks — swap `.media-block` divs for real `<img>` tags when real photography is available

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server, e.g.:

```
npx serve .
```

## Deployment (GitHub Pages)

1. Create a new public GitHub repository.
2. Push this folder to the repository's `main` branch.
3. In the repo settings, go to **Pages** → set source to the `main` branch, root folder.
4. Your live site will be available at `https://<username>.github.io/<repo-name>/`.
