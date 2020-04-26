source 'https://gems.ruby-china.com/'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem "nokogiri", ">= 1.10.8"
gem 'wdm', '>= 0.1.0' if Gem.win_platform?