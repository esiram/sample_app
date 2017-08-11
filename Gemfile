source 'https://rubygems.org'

###These items commented out when creating the tutorials app as of chapter 3.-es8/1/17###
#git_source(:github) do |repo_name|
#  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
#  "https://github.com/#{repo_name}.git"
#end

#gem 'therubyracer', platforms: :ruby

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'rails', '~> 5.1.2'
gem 'bootstrap-sass', '3.3.7'
gem 'puma', '3.9.1'
gem 'sass-rails', '5.0.6'
gem 'uglifier', '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks', '5.0.1'
gem 'jbuilder', '2.7.0'


group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug', '9.0.6', platform: :mri
end

group :development do
  gem 'web-console', '3.5.1'
  gem 'listen', '3.0.8'
  gem 'spring', '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'rails-controller-testing', '1.0.2'
  gem 'minitest-reporters', '1.1.14'
  gem 'guard', '2.13.0'
  gem 'guard-minitest', '2.4.4'
end

group :production do
  gem 'pg', '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
