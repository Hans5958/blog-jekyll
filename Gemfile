# Batch command: 
# del /f /s /q Gemfile.lock && bundle install && bundle lock --add-platform ruby x86_64-linux

source "https://rubygems.org"

gem "jekyll", "~> 3.9.0" # stuck since using 3.9.0 plugins
group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-redirect-from"   
  gem "jekyll-sitemap"
  gem "jekyll-last-modified-at"
  gem "jekyll-feed"
  gem "jekyll-relative-links"
  gem "jekyll-default-layout"
  gem "jekyll-minifier"
  gem "jekyll-toc"
  # 3 only
  gem "jekyll-paginate-v2"
  gem "jekyll-commonmark-ghpages"
  gem "jekyll-git_metadata"
  gem "jekyll-autoprefixer" 
end
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Hotfix to avoid using "eventmachine (1.2.7-x64-mingw32)" which makes errors on Windows.
gem "eventmachine", "1.2.7", git: "https://github.com/eventmachine/eventmachine.git", tag: "v1.2.7"

# Hotfix to avoid execjs >= 2.8.0, which results a fatal error.
# https://github.com/rails/execjs/issues/99
gem "execjs", "2.7.0"