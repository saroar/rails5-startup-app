# Rails 5 Start up Application 

Every Time i create new Rails 5 application i need to install some commen gem which i use for every rails applications so i decide to create one application which i and other rails programmer can use every time when i/other can use this app 

This is Gem list which i use every Rails Application 


A set of Rails responders to dry up your application
```ruby
gem 'responders', '~> 2.3' # rails g responders:install
```

Bootstrap 4 Ruby Gem for Rails / Sprockets and Compass
```ruby
gem 'bootstrap', '~> 4.0.0.alpha4'
gem 'sass-rails', '~> 5.0'
```

Tooltips and popovers depend on tether for positioning
```ruby
source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end
```
Form
```ruby
gem 'simple_form', '~> 3.3', '>= 3.3.1'
```

Nested form
```ruby
gem 'cocoon'
```

Slim template
```ruby
gem 'slim-rails'
```
Annotate Rails classes with schema and routes info
```ruby
gem 'annotate' # rails g annotate:install
```

Devise is a flexible authentication solution for Rails based on Warden
```ruby
gem 'devise', '~> 4.2'
```

ActionView Record Tag Helpers for Rails 5

```ruby
gem 'record_tag_helper', '~> 1.0'
```

For developement and test 
```ruby
group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'byebug', platform: :mri
  gem 'pry'
end
```
