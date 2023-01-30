To locally build and run this jekyll site...

Check you have the prerequisites from [this page](https://jekyllrb.com/docs/installation/).

Install jekyll and bundler:
```bash
gem install jekyll bundler
```

Install the local gems from the Gemfile:
```bash
bundle install
```

Update the local gems from the Gemfile if they were changed:
```bash
buncle update
```

Serve the jekyll site on http://localhost:4000.  Note, I had some issues with file edits not being picked up automatically by jekyll.  It turned out the --force-polling option helped with this.
```bash
bundle exec jekyll serve --force-polling
```