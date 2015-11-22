# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

# Include tasks from other gems included in your Gemfile
#
# For documentation on these, see for example:
#
#   https://github.com/capistrano/rvm
#   https://github.com/capistrano/rbenv
#   https://github.com/capistrano/chruby
#   https://github.com/capistrano/bundler
#   https://github.com/capistrano/rails
#   https://github.com/capistrano/passenger
#
#require 'capistrano/rvm'
require 'capistrano/rbenv'
require 'capistrano/rails'
# require 'capistrano/chruby'
#require 'capistrano/bundler'
#require 'capistrano/rails/assets'
#require 'capistrano/rails/migrations'
require 'capistrano/passenger'

set :rbenv_type, :user
set :rbenv_ruby, '2.2.3'

#set :rvm_type, :user                     # Defaults to: :auto
#set :rvm_ruby_version, '2.2.3-p173'      # Defaults to: 'default

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
