Render revealjs slides to embed in book project:
https://github.com/quarto-dev/quarto-cli/discussions/1433

Using this method it is possible to render the entire project and publish to netlify by uploading the _book folder directly.

Publishing to quarto.pub doesn't work properly because the revealjs slides don't render properly and are displayed as if they are pure markdown rather than converted into revealjs html slides.