source 'https://rubygems.org'

gem 'rails', '3.2.14'

gem 'thin'
gem 'haml-rails'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.4'
  gem 'coffee-rails', '~> 3.2.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development  do
  gem 'debugger'
  gem 'better_errors'                             # only in this env! we dont want to show errors to users on production
  gem 'binding_of_caller'                         # enable the REPL and local/instance variable inspection.
end


group :development, :test  do
  gem 'mysql2'
  gem 'foreman'
  gem 'quiet_assets'                              # hiding assets lines in log 

end



gem 'jquery-rails'