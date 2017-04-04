## chainpoint.github.io

This is a [Jekyll](https://jekyllrb.com/docs/quickstart/) [Github pages](https://help.github.com/articles/using-jekyll-with-pages/) site which provides the content for the [https://www.chainpoint.org](https://www.chainpoint.org) website.

### Development

Install Yarn and `node_modules` dependencies

```
brew install yarn
yarn
```

Install/Update gem dependencies

```
bundle install
bundle update
```

Start the local Jekyll dev server, recompiling all assets on change

```
bundle exec jekyll serve --config _config.yml --safe --watch --profile --incremental
```

### Deployment

Merge work in progress to `master` branch and `git push`.
Github pages will deploy almost instantly.
