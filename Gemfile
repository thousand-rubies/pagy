# frozen_string_literal: true

source 'https://rubygems.org'

# we cannot use gemspec here because it would load pagy before simplecov so missing files from coverage
# gemspec

gem 'rake'

group :development do
  gem 'debase', '~> 0.2.5.beta'  # companion of ruby-debug-ide
  gem 'ruby-debug-ide'           # companion of debase
  gem 'solargraph'               # run the Solargraph rebuild command in VSC
end

group :test do
  gem 'activesupport', '>= 7.0.4.3'
  gem 'codecov', require: false
  gem 'i18n'
  gem 'minitest'
  gem 'minitest-reporters'
  gem 'oj', require: false     # false is for testing with or without it
  gem 'rack', '>= 3.0.0'
  gem 'rake-manifest'
  gem 'rematch'
  gem 'rubocop'
  gem 'rubocop-minitest'
  gem 'rubocop-packaging'
  gem 'rubocop-performance'
  gem 'rubocop-rake'
  gem 'simplecov', require: false
end

group :apps do
  gem 'puma', '>= 5.6.4'
  gem 'rerun'
  gem 'sinatra', '>= 2.2.3'
  gem 'sinatra-contrib', '>= 2.2.3'
  # gem 'slim'
  # gem 'haml'
end

group :performance do
  gem 'benchmark-ips'
  gem 'kalibera'
  gem 'memory_profiler'
end
