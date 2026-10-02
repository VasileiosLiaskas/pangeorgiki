# Styling instructions

- Write all authored styles in SCSS. Do not add or edit CSS source files, inline `style` attributes, or `<style>` blocks.
- Keep SCSS source files in `scss/`. Use `main.scss` as the entry point and underscore-prefixed partials for shared styles.
- Organize SCSS into focused partials and use variables, mixins, and nesting only where they improve clarity.
- Browsers do not load SCSS directly. Compile `scss/main.scss` to `css/styles.css`, which is the stylesheet linked by `index.html`.
- Treat the compiled CSS as generated output: do not edit it by hand, and keep it in sync with the SCSS source.
