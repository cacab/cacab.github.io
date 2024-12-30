source "https://rubygems.org"

# Use the latest version of github-pages that works with your Jekyll version.
# Consult https://pages.github.com/versions/ for compatibility.
gem "github-pages", "~> 228", group: :jekyll_plugins

# Specify Jekyll version compatible with GitHub Pages.
# You don't need to specify Jekyll explicitly if using github-pages.
# gem "jekyll", "~> 3.9.2"

gem "minima", "~> 2.5"

# Plugins for Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
