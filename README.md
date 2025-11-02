# NRV framework website
This repository contains the NRV  website.

## Editing this website
To edit this website:

1) Make a new branch (if you have access to push to this repo) or a new fork.

2) Make your changes in your branch/fork.

3) Open a pull request.

If you think something on the website should be change, but you're not sure how to do it,
please [open an issue](https://github.com/nrv-framework/NRV-website/issues) describing the change you
would like to suggest.

## Structure of this repo

### Website pages
The website is generated from of the content of `.md` files in the main folder and
subfolders (excluding `README.md`). Markdown and HTML can be included in these files.
LaTeX-style maths can be included between `\\(` and `\\)` for inline maths; or `$$` and `$$`
for a block of maths.

At the start of each `.md` file, page setting can be given between two lines containing only `---`.
For example, `index.md` starts with:

```
---
title: NRV Framework
subtitle: logo
---
```

The `title` is displayed at the top of the page, with the `subtitle` (optional) below it. The
`image` will be used as the background of the header; if no image is given, a default image will
be used. The `layout` is used to select which layout the page uses: this can currently only be `default`
(for a default style page). If `layout`
is not set, then `default` will be used. `permalink` sets the url of the page: for example, if set to 
`/foo/`, the page would be available at `https://nrv-framework.org/foo/`.

### Assets
Files in the `assets` folder will be included as part of the website. Images and other files can
be included in this folder.

### Navigation bar
The links included in the navigation bar are defined in [`_data/navbar.yml`](https://github.com/nrv-framework.org/NRV-website/blob/main/_data/navbar.yml).
Each link is given a `title`, which will be displayed in the navigation bar; and a `page` which will be linked to.
`page` should either be an external url (starting `http://` or `https://`) or a permalink of a page (starting `/`).


## Testing and building the website

### Testing
The prerequisites for testing is to install Docker.

The website can then be tested by running:

```bash
docker-compose up
```

The website is then served locally (so it can then be opened in a browser) by running:

### Building
the building and deployement of the website is automatized with Github action