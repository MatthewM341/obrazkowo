source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.3'


gem 'rails', '~> 6.1.7', '>= 6.1.7.3'
gem 'sqlite3', '~> 1.4'
gem 'racc', '~> 1.4', '>= 1.4.14'
gem 'puma', '~> 6.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '>= 4.0'
# gem 'webpacker', '~> 0.1'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'rake', '~> 13.2', '>= 13.2.1'
# gem 'redis', '~> 4.0'
# gem 'bcrypt', '~> 3.1.7'

# gem 'image_processing', '~> 1.2'

gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  # gem 'rack-mini-profiler', '~> 2.0' # not yet packaged for Debian
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
