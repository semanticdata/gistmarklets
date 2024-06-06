# 🔖 GistMarklets

A small tool designed to simplify the creation of **Bookmarklets** from [GitHub Gists](https://gists.github.com/). You can achieve this simply by providing the Gist ID.

<p align=center>
<br />
<img src="https://img.shields.io/badge/Check%20out%20the%20Demo-F0E68C?style=for-the-badge&link=https%3A%2F%2Fsemanticdata.github.io%2Fgistmarklets%2F" alt="demo" height="34px"; />
</p>

## 🖼 Screenshot

<div align=center>

| ![screenshot](screenshot.png) |
| --- |
</div>

## 🔎 jQuery Bookmarlet Helper

The [jQuery Bookmarlet Helper](jquery.bookmarklet.js) file is a small plugin to help installing bookmarklets.

```js
$('a.bookmarklet').bookmarklet();
```

An object can be passed in to customize the appearance of the arrow. The options available are color, position and linewidth:

```js
$('a').bookmarklet({color: 'ff0000', position: 300, linewidth: 5})
```

## 🗺 Roadmap

| Change description |       |
| ------------------ | :---: |
| Integrate [jQuery-Bookmarklet](https://github.com/dschep/jQuery-Bookmarklet) into [jquery.bookmarklet.js](jquery.bookmarklet.js). | ✔ |
| Create new GitHub Workflow to publish the site using GitHub Actions.                                                              | ✔ |
| Migrate into a new `src/` folder, only leaving `index.html` in the root.                                                          | ✔ |
| Refactor HTML, CSS, and JS code.                                                                                                  | ⏳ |
| Add option to provide a full Gist URL as well as the Gist ID.                                                                     | ⏳ |
| Investigate using a single file from a Gist.[^1]                                                                                  | ⏳ |

## 💜 Attributions

This repository is a fork of [GistMarklets](https://github.com/dschep/GistMarklets). Unfortunately, the upstream repository hasn't been updated in over 8 years.[^2]  
That said, thank you [Daniel Schep](https://schep.me/) for making it available for others to use.

## © License

Source code in this repository is available under the [MIT License](LICENSE).

[^1]: This would enable users to have a single Gist with multiple bookmarklets.
[^2]: [GistMarklets](https://github.com/dschep/GistMarklets) [last commit](https://github.com/dschep/GistMarklets/commit/c7d4a41e941753387ccee69cf63f0ed568b5accf) was on July 28, 2016.
