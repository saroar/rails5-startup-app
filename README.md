# Rails 5 Start up Application 

Every Time you create new Rails 5 application you need to install some comment gem which we use for every rails application so i decide to create one application which i can use every time wheni start new rails project 

This is Gem list which i use every Rails Application 


* # A set of Rails responders to dry up your application 
gem 'responders', '~> 2.3' # rails g responders:install

* # Bootstrap 4 Ruby Gem for Rails / Sprockets and Compass
gem 'bootstrap', '~> 4.0.0.alpha4'
gem 'sass-rails', '~> 5.0'

* # Tooltips and popovers depend on tether for positioning
source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end

* # Form
gem 'simple_form', '~> 3.3', '>= 3.3.1'

* # Nested form
gem 'cocoon'

* # Slim template
gem 'slim-rails'

* # Annotate Rails classes with schema and routes info
gem 'annotate' # rails g annotate:install

* # Devise is a flexible authentication solution for Rails based on Warden
gem 'devise', '~> 4.2'

* # ActionView Record Tag Helpers for Rails 5
gem 'record_tag_helper', '~> 1.0'


* For developement and test 
group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'byebug', platform: :mri
  gem 'pry'
end
