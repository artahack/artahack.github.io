# Art-A-Hack

The back end of the [Art-A-Hack](https://artahack.io/) website.

This site builds using [Jekyll](https://jekyllrb.com/) and is hosted on [Github Pages](https://pages.github.com/). It is extended by a few custom plugins to [help manage](https://github.com/Art-A-Hack/art-a-hack.github.io/blob/source/app/_plugins/generate_sort_vars.rb) [collections](https://github.com/Art-A-Hack/art-a-hack.github.io/blob/source/app/_plugins/generate_linked_vars.rb) and [generate open graph metadata](https://github.com/Art-A-Hack/art-a-hack.github.io/blob/source/app/_plugins/generate_meta_tags.rb). It also uses a couple of Gems not [natively supported](https://pages.github.com/versions/) by Github Pages, and therefore the site uses a template [Github Actions](https://docs.github.com/en/actions) [Jekyll deployment workflow](https://github.com/testaah/testaah.github.io/blob/source-jekyll/.github/workflows/jekyll.yml) that was generated on selection of the "Github Actions" option under [repo settings] > Pages > Build and deployment > Source.

Use the site like any Jekyll site, for example to run the site locally:
```
git clone https://github.com/artahack/artahack.github.io
cd artahack.github.io
bundle exec jekyll serve
```

When you have made, previewed and committed your changes locally and are ready to put them live, use `git push`. You can then review the deployment progress in the repo's [Github Actions area](https://github.com/artahack/artahack.github.io/actions).