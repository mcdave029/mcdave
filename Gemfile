source 'https://rubygems.org'

gem 'rails', '3.2.18'
gem 'jquery-rails'
gem 'execjs'
gem 'therubyracer'
gem 'bootstrap-sass', '~> 3.1.1'

group :production do
	gem 'pg'
end

group :development, :test do
	gem 'sqlite3'
end

group :assets do
  	gem 'coffee-rails', '~> 3.2.1'
  	gem 'uglifier', '>= 1.0.3'
  	gem 'sprockets-rails', '=2.0.0.backport1'
	gem 'sprockets', '=2.2.2.backport2'
	gem 'sass-rails', github: 'guilleiguaran/sass-rails', branch: 'backport'
end
