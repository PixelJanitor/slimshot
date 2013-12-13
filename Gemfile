# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~>3.1.6"

# Using Slim for templating markup - http://slim-lang.com/
gem "slim"

# The Sass gem is already included as a middleman dependency

# Using the middleman-bourbon gem for Sass bourbon support - http://bourbon.io/
gem "middleman-bourbon"

# Using the jquery-middleman gem forked from jquery-rails - https://github.com/jasl/jquery-middleman
gem "jquery-middleman"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end
