# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "git-audio-commit"
  gem.homepage = "http://github.com/seangeo/git-audio-commit"
  gem.license = "MIT"
  gem.summary = %Q{Attach audio files to git commits.}
  gem.description = %Q{}
  gem.email = "seangeo@gmail.com"
  gem.authors = ["Sean Geoghegan"]
  gem.executables = ["git-audio-commit", "git-say-log"]
end
Jeweler::RubygemsDotOrgTasks.new
