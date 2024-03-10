source "https://rubygems.org"

# Specify the Jekyll version
gem "github-pages", group: :jekyll_plugins

# Ensure consistent formatting and specify gem versions
# gem "concurrent-ruby", "~> 3.0"
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw]

# Uncomment the line below to use Jekyll native
gem "jekyll"

gem "webrick"

# Add platform-specific gem for Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Group Jekyll plugins together
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "hawkins"
end
