source 'https://rubygems.org'

gem 'rails',        '5.0.0'
gem 'sass-rails',   '5.0.6'
gem 'uglifier',     '3.0.0'
gem 'coffee-rails', '4.2.1'
gem 'jquery-rails', '4.1.1'
gem 'turbolinks',   '5.0.0'
gem 'jbuilder',     '2.4.1'
gem 'bootstrap-sass', '~> 3.2.0'

# group :development, :test do
#   gem 'sqlite3', '1.3.11'
#   gem 'byebug',  '9.0.0', platform: :mri
# end

group :development do
    gem 'capistrano',         require: false
    gem 'capistrano-rvm',     require: false
    gem 'capistrano-rails',   require: false
    gem 'capistrano-bundler', require: false
    gem 'capistrano3-puma',   require: false
end

gem 'puma'

group :test do
  gem 'rails-controller-testing', '0.1.1'
  gem 'minitest-reporters',       '1.1.9'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
end

group :production do
  gem 'pg', '0.18.4'
end



# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
