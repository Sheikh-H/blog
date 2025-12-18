# frozen_string_literal: true

source "https://rubygems.org"

# Ensure compatibility with jekyll-theme-chirpy
gem 'jekyll', '~> 3.10.0'

# Pin to a compatible version of github-pages (>= 228)
gem "github-pages"

# jekyll-theme-chirpy version compatible with jekyll >= 4.3
gem "jekyll-theme-chirpy", "~> 7.4", ">= 7.4.1"

gem "html-proofer", "~> 5.0", group: :test

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem 'ffi', '~> 1.17'
gem 'nokogiri', '~> 1.18'

gem "wdm", "~> 0.2.0", :platforms => [:windows]

gem 'bigdecimal'

gem 'jekyll-sitemap'

# Update liquid to match the required version for github-pages >= 228
gem 'liquid', '4.0.4'

# Update kramdown to the required version for github-pages >= 228
gem 'kramdown', '2.4.0'

# Downgrade jekyll-sass-converter to 1.5.2 to match github-pages >= 228
gem 'jekyll-sass-converter', '1.5.2'
