# MyBiKE — Bicycle Landing Page

A responsive one-page website for the MyBiKE urban bicycle brand. The project introduces visitors to the models, their prices, and benefits, and provides contact information. The goal of the project is to present the products in a visually appealing format and demonstrate responsive layout using HTML and SCSS.

## Demo

[View the website](https://freelinex.github.io/scss_bicycle-landing/)

## Technologies Used

- **HTML5** — page structure and contact form.
- **SCSS (Sass)** — styles, variables, nesting, and media queries.
- **CSS Flexbox** — layout of elements and responsive blocks.
- **BEM** — organization of CSS class names.
- **Parcel** and **@mate-academy/scripts** — local server and project build.
- **ESLint, Stylelint, Linthtml, and Prettier** — code validation and formatting.

## Running Locally

You'll need Git, Node.js, and npm to get started.

1. Clone the repository and navigate to the project folder:

   ```bash
   git clone https://github.com/freelinex/scss_bicycle-landing.git
   cd scss_bicycle-landing
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the local server:

   ```bash
   npm start
   ```

   Open the URL displayed in the terminal after startup in your browser.

Additional commands:

```bash
npm run build # Build the project
npm run lint  # Check HTML, SCSS, and JavaScript
```

## Features

- Responsive layout for smartphones, tablets, and computers.
- Full-screen CSS menu that locks page scrolling when opened.
- Anchor navigation and smooth scrolling to sections.
- Cards for three bicycle models with descriptions and prices.
- A section with photos and a description of the bicycles’ advantages.
- Animations when hovering over images, links, and buttons.
- A contact form with built-in browser validation for required fields and email. Fields are cleared after submission; data submission to the server is not implemented.
- Links to call, send an email, and view the address on a map.
- Styles are organized into SCSS files by blocks, with common values defined as variables.
