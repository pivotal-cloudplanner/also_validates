#!/usr/bin/env rake
require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new do |t|
  t.rspec_opts == ["--color"]
end

desc "Run the specs"
task :default => ["spec"]
