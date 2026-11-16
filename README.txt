PEAKSTATE — GITHUB PAGES PACKAGE

CONTENTS
- index.html: the complete website (HTML, CSS and JavaScript in one file)
- .nojekyll: tells GitHub Pages to publish the files as-is

PUBLISHING STEPS
1. Extract this ZIP on your computer.
2. Open your GitHub repository.
3. Upload index.html and .nojekyll directly into the repository ROOT.
   Do not upload the ZIP itself, and do not leave the files inside an extra folder.
4. Commit the changes to the main branch.
5. Open repository Settings > Pages.
6. Under Build and deployment, choose Deploy from a branch.
7. Select branch main and folder /(root), then Save.
8. Wait for the Pages deployment to finish. The URL is shown in Settings > Pages.

IMPORTANT
- The repository must have Pages enabled.
- On GitHub Free, use a public repository for GitHub Pages.
- If Pages shows a red deployment error, open Actions, select the failed Pages run,
  and read the first red error message. That message identifies a GitHub account or
  repository configuration issue rather than a problem in this single-file website.
- The website stores tracker data in the current browser using localStorage.
  Data does not automatically sync between devices.
