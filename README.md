# [Aminebeh awesome blog](https://aminebeh.github.io/)

This blog is powered by [hugo](https://gohugo.io/about/) and hosted on [github pages](https://pages.github.com/)


## Themes
For this blog we use the hugo theme [papermod](https://github.com/adityatelange/hugo-PaperMod)
The theme is installed by creating a `PaperMod` subtree on the the [themes](./themes/PaperMod/) directory

### How to's

- Install a theme

```sh
git subtree add --prefix themes/{theme_name} {theme_repository} {theme_branch:-master} --squash
```
> Pull theme in themes directory using [subtree]()

```sh
echo 'theme = "{theme_name}"' >> config.toml
```
> Add theme to hugo config

- Update the theme
```sh
git subtree pull --prefix themes/{theme_name} {theme_repository} {theme_branch:-master} --squash
```