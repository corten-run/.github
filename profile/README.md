# Corten

Fast web apps: Rust on the server, plain JavaScript in the browser, and each doing the work it is fastest at.

Rust renders each page on the server, so the first page arrives as finished HTML, and links and forms work without JavaScript. In the browser, plain JavaScript does what the page can do with what it already has, and a small runtime swaps pages, patches forms and streams live data when the server is needed. One request handler serves the browser, native apps and AI agents.

- Repository: [corten-run/corten](https://github.com/corten-run/corten)
- Website: [corten.run](https://corten.run)
- Security reports: [private advisory](https://github.com/corten-run/corten/security/advisories/new)

Corten is built for and used in production by [Chase Sets](https://chasesets.com).
