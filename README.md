# Dive Man Comics

A free, mobile-friendly comic library and page-flip reader designed for GitHub Pages.

## Add Issue No. 1 pages

1. Export every comic page as a JPG at the same dimensions.
2. Name them in reading order: `001.jpg`, `002.jpg`, `003.jpg`, etc.
3. Put them in `issues/issue-1/pages/`.
4. Open `issues/issue-1/config.js` and list each image path.

Example:

```js
pages: [
  "pages/001.jpg",
  "pages/002.jpg",
  "pages/003.jpg"
]
```

## Page-turn library

The reader currently loads the open-source StPageFlip browser library from jsDelivr. This keeps the starter repository small and requires no build tools.

## Publish with GitHub Pages

Create a public repository, upload these files to the root of the `main` branch, then open:

**Settings → Pages → Deploy from a branch → main / root**

The site will appear at:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`
