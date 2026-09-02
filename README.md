# android-developer-blueprint

A single page, no build tools required landing page that lays out how to become an Android developer as an actual blueprint. Drafting themed layout with a five stop roadmap, four mobile build tracks, and three field notes worth reading before you commit to a stack.

## Live preview

Enable GitHub Pages on this repository (Settings → Pages → Deploy from branch → main → /root) and the site will be live at `https://yourusername.github.io/android-developer-blueprint/`.

## What's inside

The page opens with a hero section styled like a technical drawing, complete with an animated leader line diagram pointing out the core Android skill set. Below that sits a five stop roadmap walking through the real sequence of becoming job ready, a grid of four build tracks covering Android, iOS, React Native and Flutter, and a set of three pinned field notes for further reading. The footer is built like an architect's title block instead of a generic link list.

## Tech stack

Just HTML and CSS in a single file, with a small amount of vanilla JavaScript free CSS animation for the hero diagram. Fonts are pulled from Google Fonts (Space Grotesk, Inter, and JetBrains Mono). No frameworks, no bundlers, no dependencies to install. Clone it and open `index.html` directly, or serve it with GitHub Pages.

## Structure

```
android-developer-blueprint/
├── index.html
└── README.md
```

## Design notes

The visual language borrows from architectural blueprints and technical drawings rather than the usual SaaS card layout, since the content itself is essentially a set of construction plans for a career. Dashed borders, title block footer, annotation style labels and a numbered sequence are all used because the content genuinely is a sequence, not as decoration.

## Customizing

Swap out the course and blog links inside `index.html` to point to your own content, update the color tokens at the top of the `<style>` block to reskin the palette, and edit the copy directly in the markup since everything lives in one file.

## License

Free to use and adapt for your own portfolio or training website.
