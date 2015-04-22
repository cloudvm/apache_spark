source 'https://rubygems.org'

gem 'chef', '>= 11.18.6'
gem 'berkshelf', '~> 3.2'
gem 'stove', '~> 3.2'

group :test do
  gem 'chefspec', '~> 4.2'
  gem 'rspec', '~> 3.2'
  gem 'foodcritic', '~> 4.0'
  gem 'rubocop', '~> 0.27.1'
end

group :integration do
  gem 'test-kitchen', '~> 1.3'
  gem 'kitchen-vagrant'
end

group :documentation do
  gem 'yard', '~> 0.8'
  gem 'yard-chef'
end
