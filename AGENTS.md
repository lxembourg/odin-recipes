# odin-recipes

A static HTML recipe site for the Recipes lesson of [The Odin Project](https://www.theodinproject.com). The repository is public, and GitHub Pages serves `main` at https://lxembourg.github.io/odin-recipes/, so changes pushed to `main` go live.

## Files

- `index.html`: links to each recipe page.
- `recipes/*.html`: one page per recipe.
- `images/`: recipe images. The files have no extension, and pages reference them by that exact name, such as `../images/pizza`.

## Run and verify

There is no build step, dependency, or test. Open `index.html` in a browser, or serve the folder with `python3 -m http.server`, and check that every link and image resolves.
