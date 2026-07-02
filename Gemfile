source "https://rubygems.org"

# Modern Jekyll directly (not the github-pages metagem, which pins ancient
# Liquid that's incompatible with Ruby 3.2+). GitHub Pages will still build
# the site fine on its end using its own pinned versions.
gem "jekyll", "~> 4.4"

gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :jekyll_plugins do
  gem "jekyll-sitemap"
end

gem "webrick", "~> 1.7"

# Gems removed from Ruby 3.4+/4.0 default stdlib that Jekyll still expects.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "ostruct"
gem "mutex_m"
gem "fiddle"
