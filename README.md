llcd
====

## Générer le site en local

Dependencies:

- Ruby
  - Bundle

Setup:

```console
gem install jekyll bundler
bundle config set --local path 'vendor/bundle'
bundle install
```

Regenerate:

```bash
bundle exec jekyll build
bundle exec jekyll serve
```
