source 'https://rubygems.org'

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'puma', '~> 3.0'
gem 'pg', group: :production # Heroku deploy
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'

# A set of Rails responders to dry up your application
gem 'responders', '~> 2.3' # rails g responders:install

# Bootstrap 4 Ruby Gem for Rails / Sprockets and Compass
gem 'bootstrap', '~> 4.0.0.alpha4'
gem 'sass-rails', '~> 5.0'

# Tooltips and popovers depend on tether for positioning
source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end

# form
gem 'simple_form', '~> 3.3', '>= 3.3.1'

# Nested form
gem 'cocoon'

# template
gem 'slim-rails'

# Annotate Rails classes with schema and routes info
gem 'annotate' # rails g annotate:install

# Devise is a flexible authentication solution for Rails based on Warden
gem 'devise', '~> 4.2'

# ActionView Record Tag Helpers for Rails 5
gem 'record_tag_helper', '~> 1.0'

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'byebug', platform: :mri
  gem 'pry'
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
