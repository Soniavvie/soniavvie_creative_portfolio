# Sonia Vivietta — Portfolio

A static site: one `index.html` plus an `assets` folder of images and videos. No build step or dependencies.

## Preview locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Publish with GitHub + Vercel
1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload everything in this folder (drag the files into the repo page, or use `git push`).
3. In Vercel, choose **Add New → Project**, import the repository, keep the framework preset as **Other**, and click **Deploy**.
4. Your site will be live at `your-project.vercel.app`. You can add a custom domain in the project settings.

## Editing
- Text lives in `index.html`. Each project is an `<article>` with an `id` (e.g. `id="pathfind"`).
- Colours are set at the top of the `<style>` block (`--blue`, `--paper`, `--ink`).
- To swap an image, replace the file in `assets/img/` with one of the same name.
