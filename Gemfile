source "https://rubygems.org"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "jekyll", "~> 3.9.0"
gem "github-pages","~> 212" , group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15.1"
end
