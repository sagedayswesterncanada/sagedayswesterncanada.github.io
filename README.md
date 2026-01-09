# Website

Source for our website
[https://sagedayswesterncanada.github.io](https://sagedayswesterncanada.github.io).

## Technical aspects

Only prerequisite is [Hugo](https://gohugo.io/).

### Theme

The theme is [Terminal](https://github.com/panr/hugo-theme-terminal). It was
installed as a [git
submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules):

```
git submodule add -f https://github.com/panr/hugo-theme-terminal.git themes/terminal
git commit -am "Add Terminal theme as a git submodule"
```

To update the theme, simply `cd` into the directory and `git pull`, and then
`git commit` in the main repo.

### Test the website

Go this directory, run `hugo server`, and open the given address (usually
`http://localhost:1313/`) in your browser.

If you want to export the site and send it to somebody who doesn't have hugo,
compile it with `hugo --baseURL "/"`, and send the `public/` folder.

### Publish the website

The `master` branch is automatically deployed with a *GitHub Action*. The
GitHub action was automatically created; from the *Actions* tab of the
repository, click on *New workflow*, and search for the one for Hugo.
