# Static site on Renode

Plain HTML and CSS served as they are by a Renode web host.

Your own notes go here, above or below the Renode block. The panel only ever rewrites the text between the two markers.

<!-- renode:start -->
<!-- Maintained by the Renode panel. Everything between these markers is replaced when the server's settings change; write your own notes outside them. -->
## Renode server

This repository started from a Renode starter template. When it is deployed to a Renode server with "Keep AI context in the repository" switched on, the panel replaces this block with that server's own details and adds `.renode/server.md`.

- The web host serves the repository as it is: `index.html` at the root is the home page. There is no build step and nothing to start.
- Do not add a server or a start script; the image already runs the web server, bound to the allocation.
- Everything in the web root is downloadable. Never commit or upload a `.env` or any secret here.
- Fix the files, not the startup command or the Docker image.
<!-- renode:end -->
