# Dreamverse Oracle

A polished, mobile-first interactive personality experience built with pure HTML, CSS, and JavaScript.

## Features

- Five-question visual personality journey
- Eight dynamic aura identities plus one secret result
- Interactive particle background
- Pointer-reactive cards and ambient motion
- Generated 1080×1350 aura card using Canvas
- Download and Web Share support
- Optional ambient audio generated with Web Audio API
- Responsive layout for iPhone, iPad, and desktop
- No framework, build step, database, or paid API

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/root`, then save.
6. GitHub will provide the public site URL.

## Customize

- Brand name and hero copy: `index.html`
- Colors and layout: `style.css`
- Questions, scoring, and aura results: `script.js`
- Each result contains its own name, tagline, description, traits, colors, and symbol.

## Technical Notes

The project intentionally uses browser-native APIs only. Google Fonts are the sole external dependency. Replace the font link with local or system fonts if you want a completely offline build.
