Spelman Slate Branding – Option B (Full Theme)
===================================================

This folder contains an index.html file that uses the original Kingster/gdlr
markup from the Spelman site header/top bar/footer. It is meant for scenarios
where you want the Slate portal to look and behave very similarly to the main
website.

Important
---------

This option assumes you have access to the SAME CSS and JavaScript assets
that the public Spelman site uses, such as:

- kingster-style.css
- gdlr-core.css
- superfish.css
- font-awesome.min.css
- theme-responsive.css
- jquery.min.js
- superfish.min.js
- kingster-script.js
- gdlr-core.js

You MUST update the <link> and <script> tags near the top and bottom of
index.html to point to the actual file locations (on Slate, on a CDN, or on
GitHub Pages).

Files
-----

- index.html
    Includes:
      * Original Kingster top bar markup
      * Original Kingster main header & mega menus
      * Original Kingster footer structure
      * A placeholder <main id="slate-content"> area where Slate will inject content

How to Use with GitHub Pages
----------------------------

1. Create a new GitHub repository and upload this folder's contents.
2. Enable GitHub Pages for the repository (Settings → Pages).
3. Your GitHub Pages URL will look like:
       https://<username>.github.io/<reponame>/
4. Update the CSS and JS paths inside index.html so that they are reachable
   from your GitHub Pages site (or from another host you control).
5. Use the resulting URL in Slate wherever a branding layout is requested.

When to Use Option B
--------------------

Choose this option when:
- You want maximum visual fidelity with the main Spelman site.
- You (or your web team) are comfortable managing the extra CSS/JS assets.
- You don't mind relying on the original theme's dependencies.

If you want something lighter weight and easier to maintain, refer to
Option A (Simplified).
