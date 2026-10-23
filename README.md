# COESENTIA

Two intelligences. A shared future.

An independent editorial website exploring identity, consciousness and human–AI partnership.

## Website

Intended public address: https://coesentia.github.io/

Repository: `coesentia/coesentia.github.io`. GitHub Pages publishes the `main` branch from `/ (root)`. No build step, paid domain or package installation is required.

## Design and implementation

Responsive HTML, CSS and JavaScript adapted from the supplied COESENTIA visual reference. The ivory, black and copper palette, original reference artwork and editorial content structure are preserved. The intertwined C mark is an SVG interpretation; type uses system fonts. Artwork is framed from the supplied composite reference and can be replaced with individual production exports later. Rights remain with their respective owners; no open-source asset license is asserted.

Navigation links to Explore, Watch, Listen, About and the newsletter. Content cards open accessible development notes. Essays, film and audio have not yet been released.

## Newsletter

Signup remains visibly pending until a genuine hosted form is connected. No addresses are collected by the current site.

Create a dedicated COESENTIA list and hosted double-opt-in form in the project's Brevo account. Set its public HTTPS form URL in `config.js` under `newsletterUrl`. No passwords or API keys belong in this repository. Before activation, update `privacy.html` with the actual provider, project operator and public privacy contact. Test signup, confirmation, list membership and unsubscribe with the owner's email before inviting subscribers.

Official form guide: https://help.brevo.com/hc/en-us/articles/208771869-Create-a-sign-up-form-in-Brevo

## Files

- `index.html`: homepage and content dialogs
- `styles.css`: desktop and mobile presentation
- `app.js`: dialog interactions and newsletter activation
- `config.js`: public newsletter form configuration
- `mark.svg`, `reference.jpeg`: supplied identity and artwork implementation
- `privacy.html`: current privacy notice
- `.nojekyll`: static GitHub Pages publishing

## Validation

Review desktop and mobile layouts, keyboard navigation, dialog opening and Escape dismissal, all artwork, the privacy link and the newsletter state after every substantive change. Use relative paths so the site remains portable.
