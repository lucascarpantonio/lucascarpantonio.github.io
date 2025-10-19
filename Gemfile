source "https://rubygems.org"

# Compatibilità con la versione usata da GitHub Actions
ruby "3.3.0"

gem "jekyll", "~> 4.3"
gem "jekyll-theme-chirpy", "~> 6.3"

# Plugin comuni supportati da GitHub Pages
gem "jekyll-feed", "~> 0.17"
gem "jekyll-seo-tag", "~> 2.8"
gem "jekyll-paginate"
gem "jekyll-sitemap"
gem "jekyll-archives"
gem "webrick"
gem "kramdown-parser-gfm"

# Fix per build remote su GitHub Actions
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end