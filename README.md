# Exposing Repository Token JavaScript Client

This example demonstrates a critical security risk where a simulated Bitbucket repository access token is accidentally embedded directly into client-side JavaScript. When served to a browser, this sensitive token becomes easily discoverable by anyone using developer tools. It highlights the danger of mismanaging tokens in Bitbucket Pipelines builds for JavaScript applications.

## Language

`html`

## How to Run

1. Save the code as `index.html`.
2. Open `index.html` in your web browser.
3. Open your browser's developer tools (usually F12 or Ctrl+Shift+I) and check the 'Console' tab and 'Sources' tab to see the exposed token.

## Original Article

This example accompanies the Turkish article: [Bitbucket Pipelines'da Depo Erişim Token'ları ile Güvenlik Riskleri: JavaScript Uygulamaları](https://fatihsoysal.com/blog/bitbucket-pipelinesda-depo-erisim-tokenlari-ile-guvenlik-riskleri-javascript-uygulamalari/).

## License

MIT — see [LICENSE](LICENSE).
