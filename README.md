# package-dotfiles

Keep dotfiles consistent across your projects by making them an installable/updatable package.

# Usage guide

* Fork this package and change the contents of the `files` directory to what you want to use in other projects.
* Publish it to a place you can `npm install` from (e.g. Github, BitBucket, even npm).
* In your project, install your forked package. It will copy everything under `files/` to your project root.

# Note

npm [renames](https://github.com/npm/npm/issues/1862) `.gitignore` as `.npmignore` when bundling packages for installation. If you plan to place a `.gitignore` in your `files` directory, call it `gitignore` (without the dot), and the installer will restore the correct name when the file is copied across.
