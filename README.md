# Offline HTML Collection

A collection of self-contained static HTML files that run entirely in your browser. No server, no build step, no installation, and no internet connection needed once a file is downloaded.

## 🔗 Live Site

**[https://ajaygupta74.github.io/Static-Pages](https://ajaygupta74.github.io/Static-Pages/)**

Browse the folders on the live site and open any page directly.

## About

Every page in this repository is a standalone HTML file. Styles and scripts are included in the file itself, so each page works on its own.

- **Works offline:** save a page, or clone the whole repo, and open it in any modern browser.
- **Nothing to install:** no dependencies, frameworks, or build tools.
- **Private by design:** pages run locally in your browser and don't send data anywhere.
- **Easy to browse:** the home page lists all files and folders. Folders that contain an `index.html` open that page automatically.

## Use it offline

**Download the whole collection**

```bash
git clone https://github.com/ajaygupta74/Static-Pages
```

Then open any `.html` file by double-clicking it or dragging it into your browser.

**Download a single page**

Open the file on GitHub, click **Raw**, and save it (`Ctrl/Cmd + S`).

## Structure

```
.
├── index.html        # File and folder browser (home page)
├── some-folder/
│   └── index.html    # Opens automatically when the folder is visited
├── another-folder/   # No index.html, so its contents are listed
│   └── page.html
└── standalone.html
```
