# Music of Madagascar

A list of artists and genres from Madagascar.
See: [onja-madagascar.github.io/music-of-madagascar](https://onja-madagascar.github.io/music-of-madagascar/)

## About

This repo was started as a school project at [Onja.org](https://onja.org), as we love Malagasy music.

## How to contribute

## Development

Please make sure your editor has [EditorConfig](https://editorconfig.org) installed.

### Adding an artist

If you know of an artist that is not included in our list, please fork this repo, and create a pull-request.

In that PR, you'll need to do the following:

- Add the artist's page (in markdown) in the appropriate folder
- Add a link from the folder's `index.md` to your new page.

### Adding a genre

If you know of a genre that is not included in our list, please fork this repo, and create a pull-request.

In that PR, you'll need to do the following:

- Add the genre to `genres.md`

### If you notice a bug, or typo

Please let us know on [our Issues page](https://github.com/onja-madagascar/music-of-madagascar/issues) or fork, and then create a pull-request to fix the issue.

## Publishing updates

We use Github Pages to publish our work, using a simple markdown to HTML plugin in Jekyll.

To create an update, merge `master` into `gh-pages` like so:

```
git checkout master
git pull
git checkout gh-pages
git merge master
git push
```

After a few minutes the updates will be live on [onja-madagascar.github.io/music-of-madagascar](https://onja-madagascar.github.io/music-of-madagascar/)
