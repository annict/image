source 'https://rubygems.org'

ruby '2.2.0'

gem 'rails', '4.2.0'

gem 'action_args'
gem 'dragonfly', '1.0.7'
gem 'dragonfly-s3_data_store'
gem 'paper_trail'
gem 'pg'
gem 'unicorn'

group :development, :test do
  gem 'awesome_print'
  gem 'figaro'
  gem 'hirb-unicode'
  gem 'hirb'
  gem 'pry-byebug'
  gem 'pry-coolline'
  gem 'pry-rails'
  gem 'rails-flog', require: 'flog'
  gem 'rspec-rails'
end

group :development do
  gem 'aws-sdk'
  gem 'quiet_assets'
  gem 'spring'
  gem 'thin'
  gem 'web-console', '2.0.0.beta4'
end

group :production do
  gem 'bugsnag'
  gem 'rails_12factor'
end
