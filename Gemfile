# frozen_string_literal: true

source 'http://rubygems.org'
# Sinatra is a DSL for quickly creating web applications in Ruby with minimal
# effort.

ruby '3.3.4'

gem 'sinatra', '>= 4.1.0'
# This Sinatra plugin supports the full CORS spec including automatic support for CORS preflight (OPTIONS) requests. It uses CORS security best practices. The plugin logs to the default logger to guide you in setting things up properly. It will tell you why a CORS request failed and tell you how to fix it.
gem 'sinatra-cors', '~> 1.2'
# A wonderfully simple way to load your code
# Pg is the Ruby interface to the {PostgreSQL RDBMS}[http://www.postgresql.org/]
gem 'pg', '~> 1.2', '>= 1.2.3'
# Rake is a Make-like program implemented in Ruby. Tasks and dependencies are
# specified in standard Ruby syntax
gem 'rake', '~> 13.0', '>= 13.0.6'
# Puma is a simple, fast, threaded, and highly concurrent HTTP 1.1 server
# for Ruby/Rack applications. Puma is intended for use in both development and
# production environments. It's great for highly concurrent Ruby
# implementations such as Rubinius and JRuby as well as as providing process
# worker support to support CRuby well.
gem 'puma', '6.5.0'
# A plain-Ruby implementation of GraphQL.
gem 'graphql', '2.4.8'
# The Database Toolkit for Ruby
gem 'sequel', '~> 5.50'
# Container-agnostic automatic constructor injection
gem 'dry-auto_inject', '~> 0.8.0'


group :development, :test do
  gem 'pry', '0.14.2'
  gem 'bundle-audit'
  # Meta package that requires several pry extensions.
  gem 'foreman', '0.88.1'
  # Process manager for applications with multiple components
  gem 'pry-meta'
  # BDD for Ruby
  gem 'rspec', '~> 3.9'
  # Reloading Rack development server
  gem 'shotgun'
  # Loads environment variables from `.env`.
  gem 'dotenv', '3.1.7'
end
