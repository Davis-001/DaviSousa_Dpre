source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.8'

gem 'rails', '~> 6.0.6', '>= 6.0.6.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
# gem 'bcrypt', '~> 3.1.7'
gem 'bootsnap', '>= 1.4.2', require: false
# gem 'bundler', '~> 2.2', '>= 2.2.33'

#CSS
gem 'bootstrap'
gem "mini_portile2"
gem 'nokogiri', '~> 1.15', '>= 1.15.2'

# Java Script
gem 'jquery-rails'



#Variaveis de ambiente
gem 'figaro'
#Formulario simples
gem 'simple_form'
#Gerenciamento de usuario
gem 'devise'
# Engine html
gem 'haml'
gem 'haml-rails'
gem 'html2haml'

# Paginação
# gem 'kaminari'
# gem 'kaminari-bootstrap'

#Busca
# gem 'ransack'

# Melhorar select
# gem 'select2-rails'
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # gems adicionadas à aplicação
  gem 'kaminari'
  gem 'pry'
  gem 'pry-rails'
  gem 'awesome_print'
  gem 'rspec-rails'


end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'mailcatcher'
  gem 'erb2haml'

end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
