source 'https://rubygems.org'
ruby RUBY_VERSION

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages'], group: :jekyll_plugins
gem 'jekyll-sitemap', versions['jekyll-sitemap'], group: :jekyll_plugins
gem 'minima', versions['minima']

#leaving assets and font-awesome for future use
#gem 'jekyll-assets
#gem 'font-awesome-sass'
