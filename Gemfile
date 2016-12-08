source 'https://rubygems.org'
gem 'faster_require'
gem 'psych'
gem 'lookup_http'
gem 'thor'
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
  gem 'public_suffix', '1.4.6'
else
  gem 'json'
  gem 'data_mapper'
  gem 'public_suffix'
end
