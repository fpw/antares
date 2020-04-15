source "https://rubygems.org"
ruby RUBY_VERSION

gem "minimal-mistakes-jekyll"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

gem "rake", "~> 12"
gem "jekyll"

# If you have any plugins, put them here!
group :jekyll_plugins do
gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate-v2"
  gem "jekyll-seo-tag"
  gem "jekyll-compose", "~> 0.5"
  gem "jekyll-redirect-from"
  gem 'jekyll-asciidoc'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
