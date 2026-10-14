# Static site on Renode

Plain HTML and CSS for a Renode **Web Hosting** server (LumenWEB), already
following every Renode rule:

- `index.html` sits at the root of the repository, which is what the web host
  serves as the home page.
- There is nothing to build and nothing to start: the image's own web server
  serves the files as they are.
- No secrets: everything in the web root can be downloaded by a visitor.

## Deploy on Renode

1. Create your own repository from this template (**Use this template** on GitHub, or **Start from a template** on the panel's GitHub tab).
2. Order a server that runs it: a **Web Hosting** plan.
3. On the server's **GitHub** tab, connect GitHub and pick the new repository and its `main` branch, then **Deploy**.
4. Every push, with "Restart the server when someone pushes" on, or every save on the GitHub tab, places the files again.
5. Start the server. The console shows the install, then the app.

If you later move to a bundler (Vite, Astro, ...), commit the built output and
point the GitHub tab's *Where to put the code* at it, or build into the root.
