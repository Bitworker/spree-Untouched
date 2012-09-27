spree-Untouched
===============

Projekt: Spree Untouched
Type: Verkaufsplattform

Was wurde gemacht?

$ rails g spree:install (Installed generator to copy migrations, initializers and generate sample data)


Gitignore:

*.rbc
*.sassc
.sass-cache
capybara-*.html
.rspec
/.bundle
/vendor/bundle
/log/*
/tmp/*
/db/*.sqlite3
/public/system/*
/coverage/
/spec/tmp/*
**.orig
rerun.txt
pickle-email-*.html
.DS_Store
config/database.yml

Gems:

gem 'rails', '3.2.8'
gem 'mysql2'
gem 'spree', :git => 'git://github.com/spree/spree.git'

Clonen, was dann?

$ bundle exec rake db:migrate
$ bundle exec rake db:seed (testdaten)