# Web Accessibility Playground

A small HTML/CSS playground to practice web accessibility concepts using the pages linked from `index.html`.

## Getting Started

This is a static site. From the project root, start any simple HTTP server and open `index.html`:

### Using Node.js

```bash
npm install -g http-server
http-server
# Then visit http://localhost:8080
```

### Using Python

```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

## Exercises (from index.html)

- **Demo: Lang Attribute Importance** – `lang-attribute-demo.html`
- **Demo: Color Contrast Issues** – `color-contrast-issues.html`
- **Demo: Alt Text and Accessible Labels** – `alt-text-demo.html`
- **Demo: make form accessible** – `screen-reader.html`
- **Demo: Visually Hidden Content** – `visually-hidden.html`
- **Demo: Focus Styles and Indicators** – `focus-styles.html`
- **Demo: Tab Trapping and Keyboard Navigation** – `tab-trapping.html`
- **Demo: ARIA Live** – `aria.html`

Open [index.html](index.html) in the browser to navigate between all of these.

## Accessibility Audits

You can run automated accessibility checks against the running site:

### Lighthouse

```bash
lighthouse http://127.0.0.1:8080 --only-categories=accessibility
```

### Unlighthouse

```bash
unlighthouse-ci --site http://127.0.0.1:8080 --budget 75 --build-static
```

## References

The **References** section on `index.html` links to `references.html`, which contains:

- Tools (Lighthouse, Unlighthouse, ESLint a11y plugin, axe VS Code linter, Wave, ANDI)
- Learning resources (WebDev Accessibility course, Unlighthouse accessibility guides, a11y Project checklist)
- Frameworks and libraries (Headless UI, React ARIA, Radix UI, shadcn/ui, PrimeNG, Angular Material)

Open [references.html](references.html) in the browser for direct links.
