source 'https://rubygems.org'
ruby "2.2.4"

gem 'rails', '4.2.5.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'paperclip', '~> 5.0.0'
gem 'aws-sdk', '~> 2.3'
gem 'devise'

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'sqlite3'
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
