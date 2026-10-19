# goit-markup-hw-06

GoIT Fullstack HTML/CSS homework #6: **responsive layout**.

The project is the landing page of **WebStudio**, a fictional web studio ("Effective Solutions for Your Business"), built from the course mockup. Each homework in the `goit-markup-hw-0X` series builds on the previous one.

**Live page:** [https://vladyslav-humenskyi.github.io/goit-markup-hw-06/](https://vladyslav-humenskyi.github.io/goit-markup-hw-06/)

## What's done

- Mobile-first responsive layout with breakpoints at **768px** (tablet) and **1158px** (desktop)
- Mobile menu with open and close buttons for small screens
- Retina images: `srcset` for content images and `image-set()` for the hero background (`@2x` files)
- Modal contact form, footer subscription form, SVG sprite icons and hover effects carried over from homework #5

## Structure

```
index.html
css/
  main.css         imports all the files below
  common.css       shared styles
  header.css  hero.css  features.css  team.css  portfolio.css  footer.css
  modal.css        backdrop, modal and contact form
  mobile-menu.css  mobile menu
images/
  icons.svg        SVG sprite
  *@2x.jpg         retina versions of images
```

## Run locally

No build step. Open `index.html` in a browser or serve the folder with a static server such as VS Code Live Server.
