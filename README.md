# package-dotfiles

Keep all of your projects' dotfiles in sync by making them an installable/updatable package.

# Usage guide

* Fork this package and change the contents of the `files` directory to what you want to use in other projects.
* Publish it to a place you can `npm install` from (e.g. Github, BitBucket, even npm).
* In your project, install your forked package. It will copy everything under `files/` to your project root.
