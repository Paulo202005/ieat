source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'devise' # novo
gem 'jbuilder', '~> 2.7'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.3'
gem 'sass-rails', '>= 6'
gem 'sidekiq'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.0'

group :development, :test do
  # gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'pry'  
  gem 'rspec'
  gem 'rspec-rails'
  gem 'shoulda-matchers'  
end

group :development do 
  gem 'listen' # novo / 3.2
  gem 'spring-watcher-listen' #novo / 2.0.0
  gem 'spring' # novo
  gem 'web-console', '>= 4.1.0'  
  gem 'rack-mini-profiler', '~> 2.0' # diferente do curso  
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
