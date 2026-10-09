# AtomForge documentation

The AtomForge documentation site, built with [BookMD](https://github.com/atom-forge/bookmd) and published on GitHub Pages. Each package keeps its documentation as a book in its own repository; this site lists those books in `content/books.md` and builds them together.

## Add a package

1. In the package repository, add a `docs/book.md` entry with an `id` (for example `id: ui`) and its chapters.
2. Add one line to `content/books.md`: `"main@github.com/atom-forge/<package>/docs/book.md"`.
3. Commit to `main`. The *Deploy book* workflow rebuilds the site; run it by hand from the Actions tab when a package changes.

How it works: [BookMD manual](https://github.com/atom-forge/bookmd/blob/main/docs/book.md).
