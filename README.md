# Open Bazar

Online marketplace for Nepal (PWA: HTML/JS + Firebase).

## GitHub Pages (free hosting)
1. Create a new GitHub repository (e.g. `open-bazar`).
2. Upload ALL files of this package to the repository root (index.html must be at the top level).
3. Repository -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch `main` / folder `/ (root)` -> Save.
4. After 1-2 minutes the site is at `https://YOUR-USERNAME.github.io/open-bazar/`.
5. Firebase Console -> Authentication -> Settings -> Authorized domains -> add `YOUR-USERNAME.github.io`.
6. Firebase Console -> Firestore -> Rules -> paste `firestore.rules` -> Publish.
7. Open the site and log in once with the owner Gmail first (claims the admin role).

Note: GitHub Pages ignores `_headers`; security rules come from the CSP meta tag in index.html and from Firestore rules.
