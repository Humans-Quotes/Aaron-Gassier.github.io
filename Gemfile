source "https://rubygems.org"

# Default theme for new Jekyll sites
gem "minima", "~> 2.5"

# GitHub Pages gem (uncomment if you want to use GitHub Pages)
gem "github-pages", "~> 228", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1"
end

# JRuby specific gem
platforms :jruby do
  gem "http_parser.rb", "~> 0.6.0"
end

gem "webrick", "~> 1.8"