# Assignment #1 — HTML & CSS Basics

A multi-page website by **Arailym Amangeldi** (SE-2528), covering Tasks 1–4 of the assignment.

## Pages

| File              | Task   | Description                                                                                                                                    |
| ----------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| `index.html`      | Task 1 | Personal page: hero section with photo and intro, an "About me" band, and three skill/achievement cards                                        |
| `layout.html`     | Task 2 | Header / navbar / sidebar / content / footer layout built with `<div>` + CSS floats (no Flexbox/Grid). Sidebar links jump to matching sections |
| `tribute.html`    | Task 3 | Tribute page for actor Park Bo Gum                                                                                                             |
| `table-form.html` | Task 4 | Styled grades table (rowspan/colspan, alternating rows, highlighted row) and a feedback form                                                   |

All four pages share one stylesheet, `styles.css`, and the same sticky navigation bar so you can move between tasks.

## Design

- **Colors:** deep maroon `#280b0c` on white, with a soft blush pink as the accent/hover color.
- **Fonts:** Bebas Neue for big headings, Montserrat for navigation, Inter for body text.
- `<meta name="color-scheme" content="light only">` is set on every page so browsers/editors don't auto-invert it into dark mode.

## Images

Located in `images/`:

- `profile.jpg` — photo used in the Task 1 hero section
- `profile-about.jpg` — photo used in the Task 1 "About me" band
- `parkbogum.jpg` — photo used on the tribute page
  Replace these with your own files (keep the same names) to update the photos.

## Running locally

Open `index.html` in a browser, or serve the folder with VS Code's Live Server extension.

## Publishing to GitHub Pages

1. Create a new GitHub repository and push all these files (make sure `index.html` is in the repo root).
2. Go to **Settings → Pages** in the repository.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then save.
4. Your site will be published at `https://your-username.github.io/your-repo-name`.
