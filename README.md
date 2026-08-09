# Portfolio (React + Vite)

Personal portfolio website built with React.

## Run locally

```bash
npm install
npm run dev
```

Then open the URL shown in the terminal (usually http://localhost:5173).

## Customize your info

Edit **`src/data/portfolio.js`** — name, email, phone, LinkedIn, education, and projects.

### Project click redirect

Each project card opens its `url` in a new tab when clicked. Set:

```js
{
  title: "My App",
  url: "https://your-live-demo.com",   // opened on card click
  github: "https://github.com/you/repo",
  // ...
}
```

## Profile picture

Add your photo as **`public/profile.jpg`** (square, ~400×400 px or larger).

## Build for production

```bash
npm run build
npm run preview
```

## File structure

```
portfolio/
├── public/
│   └── profile.jpg       # Your photo
├── src/
│   ├── components/       # Navbar, Hero, Education, Projects, Contact, Footer
│   ├── data/
│   │   └── portfolio.js  # Edit your personal data here
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
└── package.json
```
