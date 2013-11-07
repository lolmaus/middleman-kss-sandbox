# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~>3.2.0"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

gem 'middleman-kss'


# Sass stuff

# Runs `gem` for each element in the array with require: false
[ "oily_png",
  ["singularitygs",  "~> 1.1.2"],
  ["breakpoint",     "~> 2.0.7"],
  "toolkit",
  "sass-globbing"
].each do |dep|
  dep = [dep] unless dep.is_a? Array
  dep << { require: false }
  gem *dep
end
