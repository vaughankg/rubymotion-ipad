# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Hello'
  app.device_family = [:ipad]
  app.deployment_target = "5.1"
  app.interface_orientations = [:landscape_left, :landscape_right]
end
