require 'rake/clean'

require 'jasmine-headless-webkit'
require 'jasmine/headless/task'

require 'cucumber'
require 'cucumber/rake/task'

include Rake::DSL if defined?(Rake::DSL)

Jasmine::Headless::Task.new
Cucumber::Rake::Task.new

task :default => ['jasmine:headless', 'cucumber']

