1. Make a Gemfile in the 2022 folder with the following lines
```bash
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
gem 'jekyll-feed', group: :jekyll_plugins
gem 'jekyll-seo-tag', group: :jekyll_plugins
gem 'jekyll-sitemap', group: :jekyll_plugins
#If you will be using ruby v3.2.2 with bundler v2.4.18 and jekyll v3.9.3, there's a chance of getting an error caused by missing webrick when running the jekyll serve, if that happens, add this line and run 'bundle update' again
gem 'webrick' 
```

2. Install Ruby on your machine if you don't have it yet. Alternatively, you can use [rvm](https://rvm.io). You can also use RBENV. The site uses Ruby 3.2.2.
3. Install Bundler if you don't have it yet.
```bash
gem install bundler
```

4. Install Jekyll dependencies.
```bash
bundle install
```

5. Run site locally.
```bash
bundle exec jekyll serve
```