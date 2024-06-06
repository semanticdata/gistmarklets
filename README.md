# 🔖 GistMarklets

A little tool to provide a simple installation page for bookmarklets hosted as gists.
The gist is identified by placing its id in the hash.

Take a look at the [DEMO](https://semanticdata.github.io/gistmarklets/).

## jQuery Bookmarlet Helper

The [jQuery Bookmarlet Helper](jquery.bookmarklet.js) file is a small plugin to aid in installing bookmarklets.

```js
$('a.bookmarklet').bookmarklet();
```

An object can be passed in to customize the appearance of the arrow. The options available are color, position and linewidth:

```js
$('a').bookmarklet({color: 'ff0000', position: 300, linewidth: 5})
```

## 📅 Planned Changes

- ✅ Integrate jQuery Bookmarlet Helper into this repo instead of a submodule.
- ✅ Create new GitHub Workflow to publish the site using GitHub Actions.
- ✅ Migrate into a new `src/` folder, only leaving `index.html` in the root.
- Make it so you can use whole Gist URL instead of just the Gist ID.
- Investigate using a single file from a Gist.
  This would allow users to have a single Gist with multiple bookmarklets.

## 💜 Attributions

This repository is a fork of [GistMarklets](http://dschep.github.com/GistMarklets) by [Daniel Schep](https://schep.me/). It uses [jQuery-Bookmarklet](https://github.com/dschep/jQuery-Bookmarklet) found within [jquery.bookmarklet.js](jquery.bookmarklet.js).

## © License

Source code in this repository is available under the [MIT License](LICENSE).
