source "https://rubygems.org"

# Matches the Jekyll version and plugins that GitHub Pages uses.
# Run the site locally with: bundle exec jekyll serve
gem "github-pages", "~> 232", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-include-cache"
  gem "jekyll-feed"
end

# No longer bundled with Ruby 3.4+, but Jekyll still needs them.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "webrick"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
