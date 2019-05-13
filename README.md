# About
A blog on my data adventures

This blog is built with [blogdown](https://github.com/rstudio/blogdown) and [Hugo](https://gohugo.io/), using the [Minimo](https://github.com/MunifTanjim/minimo) theme. I deploy my blog using [Netlify](https://netlify.com/). 

All blog posts are released under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

### Update submodule flow

Don't change submodule files from within blog repo.
Make changes in the [Minimo fork](https://github.com/jeroenboeye/minimo) and once pushed run this command within the blog repo:

`git submodule foreach git pull origin master`.

Note that it takes a while for the RStudio IDE to discover these changes. Once it does, commit and push the new submodule hash.

If original Minimo repo is updated, see [docs on upstream merge](https://help.github.com/en/articles/syncing-a-fork).