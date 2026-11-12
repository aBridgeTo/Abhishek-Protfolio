# Abhishek Yadav · Portfolio

Personal portfolio site for Abhishek Yadav, Flutter and mobile tech lead based in Indore, India.

It is a single static page (`index.html`) with no build step and no dependencies. Fonts load from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository, for example `portfolio` or `<username>.github.io`.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. The site will be live at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` for a `<username>.github.io` repo).

To use a custom domain, add it under **Settings → Pages → Custom domain** and point your domain's DNS to GitHub Pages.

## Editing

All content and styles are in `index.html`:

- Projects: the `#work` section
- Experience: the `#changelog` section
- Contact links: the `#contact` block
- Colors and fonts: the `:root` tokens at the top of the `<style>` block
