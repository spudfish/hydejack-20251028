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
gem "jekyll", "~> 4.3"

gem "jekyll-theme-hydejack", "~> 9.1"

# If you are part of the ["Customers" team](https://github.com/orgs/hydecorp/teams/pro-customers),
# you can fetch the theme from a private repository.
# See [Deploy in the Hydejack Docs](https://hydejack.com/docs/deploy) for details.

# gem "jekyll-theme-hydejack", git: "https://github.com/hydecorp/hydejack-pro", tag: "pro/v9.2.0"

# IMPORTANT: The followign gem is used to compile math formulas to
# KaTeX during site building.
#
# There are a couple of things to know about this gem:
# *  It is not supported on GitHub Pages.
#    You have to build the site on your machine before uploading to GitHub,
#    or use a more permissive cloud building tool such as Netlify.
# *  You need some kind of JavaScript runtime on your machine.
#    Usually installing NodeJS will suffice.
#    For details, see <https://github.com/kramdown/math-katex#documentation>
#
# If you're using the MathJax math engine instead, free to remove the line below:
# gem "kramdown-math-katex"

# A JavaScript runtime for Ruby that helps with running the katex gem above.
# gem "duktape"

# Required for `jekyll serve` in Ruby 3
gem "webrick"

gem "logger"    # added by KC at set up as next version ruby 3.5 won't load this

# Uncomment when using the `--lsi` option for `jekyll build`
# gem "classifier-reborn"

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
