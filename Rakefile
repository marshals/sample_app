#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'annotate/tasks'

ENV['position_in_class']   = "before"
ENV['position_in_fixture'] = "before"
ENV['show_indexes']        = "false"
ENV['include_version']     = "false"
ENV['exclude_tests']       = "false"
ENV['exclude_fixtures']    = "false"
ENV['skip_on_db_migrate']  = "false"

SampleApp::Application.load_tasks
