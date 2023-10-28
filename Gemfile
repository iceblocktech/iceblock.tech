# frozen_string_literal: true

source 'https://rubygems.org'

gem 'http_parser.rb', '~> 0.6.0', platforms: [:jruby]
gem 'jekyll', '~> 4.3.2'
gem 'minima', '~> 2.5'
gem 'wdm', '~> 0.1.1', platforms: %i[mingw x64_mingw mswin]

group :jekyll_plugins do
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end
