source 'https://rubygems.org'
gem 'faster_require'
gem 'psych'
gem 'lookup_http'
gem 'thor'
gem "puppet", ENV['PUPPET_GEM_VERSION'] || '~> 4.8.0'
gem "deep_merge"
gem "sinatra"
gem "dm-sqlite-adapter"

group(:development, :test) do
  gem 'rake'
  gem 'rspec-core'
  gem 'rspec'
  gem 'mocha'
end

# JSON must be 1.x on Ruby 1.9
if RUBY_VERSION < '2.0'
  gem 'json', '~> 1.8'
  #gem 'json_pure', '~> 1.8'
  gem 'data_mapper', '~> 1.2'
else
  gem 'json'
  gem 'data_mapper'
end
