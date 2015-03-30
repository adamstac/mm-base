require "rubygems"
require "bundler"

Bundler.setup

desc "Run Middleman server"
task :server do
  puts "*** Go, go, Middleman! ***"
  system "bundle exec Middleman server"
end

desc "Run Middleman build"
task :build do
  puts "*** Middleman build! ***"
  system "bundle exec Middleman build"
end

desc "Clear the build"
task :clear do
  puts "*** Middleman clear that build! ***"
  system "rm -Rfv build"
end

desc "Zip the build"
task :zip do
  puts "*** Middleman zip that build! ***"
  system "rm -Rf build.zip"
  system "zip -r build.zip build/*"
end
