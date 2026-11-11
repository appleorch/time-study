# Instructions for Claude

## Shipping changes

The app is served by GitHub Pages from `main`. After you finish and push a change,
do the following without asking first:

1. Open a pull request from your working branch into `main`.
2. Merge it (regular merge commit).

The owner doesn't want to open GitHub and do either step by hand.

## Version label

The bottom of `index.html` shows a version label (`.app-version`, e.g. "v8").
The owner uses it to see when GitHub Pages has updated. Bump it by one in every
change that ships.
