# Portfolio
# Student Web Development Portfolio

A responsive portfolio website and collection of front-end assignments created as part of a first-year BCA web development curriculum. The project presents an introduction, learning journey, skills, assignment previews, and contact section, with individual HTML pages for coursework projects.

## Features

- Portfolio landing page with Home, About, Skills, Assignments, and Contact sections
- Assignment gallery linking to individual coursework pages
- Practice projects covering semantic HTML, CSS layouts, forms, images, iframes, tables, and animation
- Responsive styling with Flexbox and CSS Grid
- External typography and icon resources

## Technology

- HTML5
- CSS3
- Google Fonts: Bricolage Grotesque and Figtree
- Font Awesome 6.4
- Unsplash-hosted images

## Project structure

```text
.
├── index.html
├── style.css
├── Assignment_Page.html
├── assignement-newspaper/
├── assignemnt-dynamic-gallery/
├── assignment-animation/
├── assignment-background/
├── assignment-box-plotting/
├── assignment-flexbox/
├── assignment-iframe/
├── assignment-link/
├── assignment-login/
├── assignment-profilecard/
├── assignment-table/
└── picture/
```

The assignment folder names match the provided project files, including their original spelling.

## Run locally

1. Download or clone the repository.
2. Keep the folders and files in their existing relative locations.
3. Open `index.html` in a web browser.
4. Select **Assignments** to browse the coursework pages.

No build step or package installation is required. An internet connection is needed for the externally hosted fonts, icons, and images.

## Deploy with GitHub Pages

1. Push the project to a GitHub repository.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the branch containing the project and select the root (`/`) folder.
5. Save the settings and open the Pages URL shown on the same screen.

Because `index.html` is in the repository root, it can serve as the site’s home page.

## Notes

- Keep the project folders together when moving or publishing the files; assignment pages and previews use relative paths.
- The contact form is a front-end layout only. It does not send messages unless it is connected to a form service or backend.
- Review contact information, school details, and social links in the HTML before making the repository public.

## License

No license is currently included. Add a `LICENSE` file if you want to specify how others may use or redistribute this project.
