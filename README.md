# Jialiang Wang Website

This is a static personal website designed to be hosted on GitHub Pages at:

```text
https://jialiangw219.github.io/
```

## Preview locally

Open `index.html` in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository named `jialiangw219.github.io`.
2. Commit and push these files:

```bash
git add .
git commit -m "Create personal website"
git remote add origin https://github.com/jialiangw219/jialiangw219.github.io.git
git push -u origin main
```

3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select `main` and `/ (root)`, then save.

GitHub will publish the site at `https://jialiangw219.github.io/`.
