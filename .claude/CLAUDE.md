# raphroyjauvin.ca (portfolio site): instructions for Claude

This repo is Raph's live portfolio site. GitHub Pages publishes `main` to https://www.raphroyjauvin.ca/ as soon as a commit reaches it. There are no tests in between.

## Rules
- Never commit to `main`, push `main` or merge into it. Work on a branch. Push the branch only when Raph asks, and leave the review and merge to him.
- Keep agent and planning files off the site. Pages runs Jekyll, which publishes every `.md` file outside a dot-folder as a public page. Put notes in `.claude/`, never at the root or in `de/`, `fr/`, `files/` or `images/`.
- Change `CNAME` only when Raph asks. It points www.raphroyjauvin.ca at this site.
- The site has three languages: English (`index.html`), French (`fr/index.html`) and German (`de/index.html`), linked by `hreflang` tags. Make each content change in all three, unless Raph says otherwise. Keep `sitemap.xml` in step when pages are added or removed.
- Before you call a change done, serve the repo folder locally and check every page you changed, in each language.
