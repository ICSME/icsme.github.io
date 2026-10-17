source "https://rubygems.org"

# Use the same Jekyll and plugin versions as GitHub Pages.
# To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# Required by `jekyll serve` on Ruby 3.0+.
gem "webrick"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
