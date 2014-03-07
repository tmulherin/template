/*
#############################################################################################
#  
#  If creating from
#     Scratch: rails new sample_app --skip-test-unit --database=postgresql
#        - Create config/database.yml and add this code:
# ---------------------------------------------------------------------------------------------

development:
  adapter: sqlite3
  database: db/who?.sqlite3 # <-- Change me
  pool: 5
  timeout: 5000

test:
  adapter: sqlite3
  database: db/who?.sqlite3 # <-- Change me
  pool: 5
  timeout: 5000

production:
  adapter: postgresql
  encoding: unicode
  database: # <-- Add one
  pool: 5
  username: # <-- Add one
  password: # <-- Add one

# PostgreSQL. Versions 8.2 and up are supported.

  # Connect on a TCP socket. Omitted by default since the client uses a
  # domain socket that doesn't need configuration. Windows does not have
  # domain sockets, so uncomment these lines.
  #host: localhost

  # The TCP port the server listens on. Defaults to 5432.
  # If your server runs on a different port number, change accordingly.
  #port: 5432

  # Schema search path. The server defaults to $user,public
  #schema_search_path: myapp,sharedapp,public

  # Minimum log levels, in increasing order:
  #   debug5, debug4, debug3, debug2, debug1,
  #   log, notice, warning, error, fatal, and panic
  # Defaults to warning.
  #min_messages: notice

# Warning: The database defined as "test" will be erased and
# re-generated from your development database when you run "rake".
# Do not set this db to the same as development or production.
#----------------------------------------------------------------------------------------------
#
#        - Did you add/change database names in config/databases.yml?
#        - Replace .gitignore  
#        - Change title in application.html.erb
#        - bundle install / bundle update / bundle install
#        - rails generate rspec:install
#        - git init / commit
#        - Create Repository
#        - git remote add template_origin https://github.com/tmulherin/template.git
#        - git remote set-url template_origin https://github.com/tmulherin/template.git
#  
#############################################################################################
*/
Ruby 2.0.0

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.
