source 'https://rubygems.org'

gem 'rails', '4.2.6'

#BEM
gem 'rails_blocks'

#Authorization
gem 'devise'
gem 'omniauth'
gem 'omniauth-vkontakte'

#utils
gem 'paper_trail'
gem 'paranoia', '~> 2.0'
gem 'config'
gem 'roboto'
gem 'simple_form'
#gem 'admino'
#gem 'responders'
gem 'russian'
#gem 'acts-as-taggable-on'


#CSS
gem 'sassc-rails'
#gem 'sass-rails'
gem 'sass'
gem 'sprockets'
gem 'sprockets-rails', '~> 2.3.3'
gem 'autoprefixer-rails'
gem 'normalize-rails'
gem 'bourbon'
gem 'neat'
gem 'inline_svg'

#JS
#gem 'selectize-rails'
#gem 'bower-rails'
gem 'jquery-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'client_side_validations', git: 'https://github.com/DavyJonesLocker/client_side_validations.git'
#must be after simple_form & client_side_validations
gem 'client_side_validations-simple_form', git: 'https://github.com/DavyJonesLocker/client_side_validations-simple_form.git'
#gem 'jquery-validation-rails'
gem 'modernizr-rails'

#HTML
gem 'slim-rails'

gem 'phony_rails'
gem 'enum_help' #Help ActiveRecord::Enum feature to work fine with I18n and simple_form
#gem 'pundit'
#gem 'cancan'

#IMAGES
#gem 'paperclip', '~> 4.2'
#gem 'paperclip-meta'

#HELPERS
gem 'kaminari'
gem 'gaffe'
gem 'truncate_html'
gem 'browser'
#gem 'redcarpet'
gem 'draper'

#SEO
gem 'sitemap_generator'

#profiling
gem 'newrelic_rpm'

#database
gem 'pg'
#gem 'pg_search'
gem 'schema_plus'

#mails
#gem 'premailer-rails'
#gem 'sidekiq'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
#gem 'jbuilder', '~> 2.0'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',					group: :doc

group :development do
	gem 'quiet_assets'
	gem 'better_errors'
	gem 'binding_of_caller'
	gem 'rails-dev-boost'
	
	gem 'bullet' #kill n+1 queries
	
	#security
	gem 'brakeman'
	
	#gem 'rspec-routes_coverage'
	#deployment
	gem 'capistrano',				 require: false
	gem 'capistrano-rvm',		 require: false
	gem 'capistrano-rails',	 require: false
	gem 'capistrano-bundler', require: false
	gem 'capistrano-passenger', require: false
	gem 'capistrano-faster-assets', '~> 1.0', require: false
	gem 'capistrano-git-submodule-strategy', '~> 0.1', :github => 'ekho/capistrano-git-submodule-strategy'
end

group :development, :test do
	gem 'rspec', '~> 3.1'
	gem 'rspec-rails', '~> 3.0'
	gem 'factory_girl_rails', '~> 4.0'
	gem 'capybara'
	gem 'culerity'
	gem 'database_cleaner'
	gem 'poltergeist'
	#gem 'selenium-webdriver'
	gem 'shoulda-matchers'
	gem 'jasmine-rails'
	gem 'guard-jasmine'
	
	gem 'rb-fsevent',require: false if RUBY_PLATFORM =~ /Darwin/
	gem 'spring-commands-rspec'
	
	gem 'guard-livereload',  :require => false
	gem 'rack-livereload'
	gem 'guard', require: false
	gem 'guard-bundler', require: false
	gem 'terminal-notifier', require: false
	gem 'terminal-notifier-guard', require: false
	gem 'guard-rspec', require: false
	
	# Call 'byebug' anywhere in the code to stop execution and get a debugger console
	gem 'byebug'
	# Access an IRB console on exception pages or by using <%= console %> in views
	gem 'web-console', '~> 2.0'

	# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
	gem 'spring'
	gem 'launchy'
end

group :development, :test, :staging, :production do
	gem 'faker'
end

group :profile do
	gem 'ruby-prof'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
