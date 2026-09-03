# IS Pathways

A complete static website for information systems students. Includes five career detail pages, a five-question career quiz with scored results, and 15 multiple-choice interview questions. Selecting a sample answer reveals its Bad, Good, or Great rating and the explanation from Orientation Brainstorming.pdf. Career details incorporate the supplied IS Career Tracks Guide.

## Publish with GitHub Pages

1. Create a GitHub repository named `is-pathways`. A public repository works with GitHub Free.
2. Upload the **contents of this folder** into the repository. `index.html` must be at the top level, not inside another folder. Extract the ZIP first; do not upload the ZIP itself as the website.
3. Commit the files to the `main` branch.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose **main** and **/(root)**, then click **Save**.
7. When deployment completes, return to Settings → Pages and use the published site link. Check the Actions tab if deployment reports an error.

For a repository named `is-pathways`, the usual address is `https://YOUR-USERNAME.github.io/is-pathways/`. Use the exact link GitHub displays.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: Entire website, including styles, quiz logic, career content, and interview questions.
- `.nojekyll`: Tells GitHub Pages to serve the static files without Jekyll processing. This dotfile may be hidden in your file browser.
- `.gitignore`: Keeps common operating-system files out of the repository.
- `README.md`: These instructions.

No installation, build command, database, API key, or separate PDF upload is needed. All pages use hash-based navigation in the same HTML file, so career and quiz links work under a repository URL.

## Preview and edit

Open `index.html` in a browser to preview. Edit this file to change the website. To publish updates, upload the revised `index.html` to the same repository and commit to `main`.

The quiz awards one point per answer, shows a primary result and three alternatives, and explains ties. Answers stay in the current page session and are not sent to a server.

This package prepares the site for publishing; creating a repository and enabling GitHub Pages are still required.
