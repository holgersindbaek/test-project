# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

require 'motion-cocoapods'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'test_project'

  # app.vendor_project('vendor/AsyncDisplayKit/AsyncDisplayKit', :static, :products => ['AsyncDisplayKit'], :force_load => true, :headers_dir => 'Headers')

  # Cocoapods
  app.pods do
    pod 'AsyncDisplayKit', '~> 1.1.1'
  end
end
