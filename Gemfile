source 'https://rubygems.org'

gemspec

# This is the version that ships with OS X 10.10, so be sure we test against it.
# At the same time, the 1.7.7 version won't install cleanly on Ruby > 2.2,
# so we use a fork that makes a trivial change to a macro invocation.
gem 'json', :git => 'https://github.com/segiddins/json.git', :branch => 'seg-1.7.7-ruby-2.2'

group :development do
  gem 'bacon'
  gem 'mocha', '< 1.5'
  gem 'mocha-on-bacon'
  gem 'prettybacon'
  gem 'rake', '~> 12.0'
  gem 'rexml', '~> 3.2.4'
  gem 'vcr'
  gem 'webmock'
  gem 'webrick', '~> 1.7.0'

  gem 'rubocop', '~> 0.38.0'
end

group :debugging do
  gem 'awesome_print'
  gem 'kicker'
  gem 'pry'
  gem 'rb-fsevent'
end
