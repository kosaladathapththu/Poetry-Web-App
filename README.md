# Poet Portfolio — Setup Guide

## Folder Structure
```
poet-portfolio/
├── index.html          ← Home page
├── poems.html          ← All poems list
├── about.html          ← About page
├── contact.html        ← Contact page
├── netlify.toml        ← Netlify config
├── css/
│   └── style.css       ← All styles (edit colors/fonts here)
├── images/
│   ├── poet-photo.jpg  ← Hero photo (replace this!)
│   └── about-photo.jpg ← About page photo (replace this!)
└── poems/
    └── morning-light.html  ← Template for each poem
```

## How to Add a New Poem

1. Copy `poems/morning-light.html` → rename to `poems/your-poem-title.html`
2. Edit the poem content inside the file
3. Add a row in `poems.html` pointing to the new file
4. Done!

## How to Deploy to Netlify (Free)

1. Create a free account at https://github.com and push this folder as a repo
2. Go to https://netlify.com → "Add new site" → "Import from GitHub"
3. Select your repo → Deploy
4. Your site is live at: `https://your-name.netlify.app`

## How to Set Up the Contact Form (Free)

1. Go to https://formspree.io → create free account
2. Create a new form → copy the form ID (looks like: xpzgwkqr)
3. Open `contact.html` → find `YOUR_FORM_ID` → replace with your ID
4. Form submissions will go directly to your email.

## Customization

- **Poet name**: Find & replace "Poet Name" across all files
- **Colors**: Edit CSS variables in `css/style.css` under `:root`
- **Fonts**: Change font links in `<head>` of each HTML file
- **Poems**: Each poem is a standalone `.html` file in the `/poems/` folder
