# Proteus Mentis

Personal blog of Leo Cahya Dinendra, built with [Jekyll](https://jekyllrb.com/) and the [Minimal Mistakes](https://mmistakes.com/) remote theme.

Published at [https://leocd91.github.io](https://leocd91.github.io).

## Local development

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open <http://localhost:4000>.

### Note: `pathutil` patch for Ruby 3.0

On Ruby 3.0, `jekyll serve` fails with `no implicit conversion of Hash into Integer`
(a `pathutil` bug: it passes a kwargs hash positionally to `File.read`). The vendored gem
is patched at:

```text
vendor/bundle/ruby/3.0.0/gems/pathutil-0.16.2/lib/pathutil.rb
```

Replace `File.read(self, *args, kwd)` with `File.read(self, *args, **kwd)` (two places).
Re-apply after a fresh `bundle install`.

## Production build check

```bash
bundle exec jekyll clean
JEKYLL_ENV=production bundle exec jekyll build
```

## Publish

```bash
git add .
git commit -m "Update blog"
git push
```
