source "https://rubygems.org"
ruby "3.4.7"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.4.1"

gem "jekyll-theme-hydejack", "~> 9.2.1"

# Required for `jekyll serve` in Ruby 3
gem "webrick"

gem "logger"    # added by KC at set up as next version ruby 3.5 won't load this

group :jekyll_plugins do    #If you remove a plugin from here, remove it from _config.yml too.
  gem "jekyll-include-cache"    #Hydejack uses this; speeds up includes
  gem "jekyll-seo-tag"          # useful 2025 1101 per ChatGPT cleanup for SiteLeaf
  gem "jekyll-sitemap"          # useful 2025 1101 per same
  gem "jekyll-redirect-from"    # handy when you rename pages/sections
#  gem "jekyll-default-layout"          # restore later if needed
#  gem "jekyll-feed"                 # for blog sites
#  gem "jekyll-paginate"            # for blog sites, not needed for Ta's site
#  gem "jekyll-readme-index"            # restore later if needed
#  gem "jekyll-optional-front-matter"   # restore later if needed
#  gem "jekyll-relative-links"          # restore later if needed
#  gem "jekyll-titles-from-headings"    # restore later if needed

  # Non-Github Pages plugins:
#  gem "jekyll-last-modified-at"     # restore for stamping an updated on date
#  gem "jekyll-compose"         # restore for convenience commands for posts/pages
end

gem 'wdm' if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?
