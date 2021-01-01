source "https://rubygems.org"
gem "jekyll", "~> 3.9.0"
# gem "minima", "~> 2.5"
# gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-archives"
  # gem "jekyll-commonmark"
  gem "jekyll-paginate-v2"
  gem 'jekyll-commonmark-ghpages'
  # gem 'github-pages-health-check', '1.16.1'
  gem 'jekyll-redirect-from'   
  gem 'jekyll-sitemap'
  gem 'jekyll-feed'
  gem 'jekyll-seo-tag'
  # gem 'jekyll-github-metadata'
  # gem 'jekyll-avatar'
  # gem 'jekyll-remote-theme'
  gem 'jemoji'
  gem 'jekyll-relative-links'
  gem 'jekyll-optional-front-matter'
  gem 'jekyll-default-layout'
end
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
