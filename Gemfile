source "https://rubygems.org"

# Same gem set as the GitHub Pages build (github-pages 232 needs Ruby < 4.0).
# Local preview:
#   export PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH LANG=en_US.UTF-8
#   bundle config set --local path vendor/bundle
#   bundle install && bundle exec jekyll serve
gem "github-pages", group: :jekyll_plugins

# No longer default gems in newer Rubies; Jekyll 3.x needs them locally.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "webrick"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
end
