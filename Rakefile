# -*- coding: utf-8 -*-
$:.unshift('/Library/RubyMotion/lib')
require 'motion/project/template/ios'
require 'bundler'
require './lib/motion-blitz'

Bundler.require :default

Motion::Project::App.setup do |app|
  app.name = 'motion-blitz'

  app.pods do
    pod 'SVProgressHUD', :git => 'https://github.com/SVProgressHUD/SVProgressHUD.git', :tag => "2.0-beta8"
  end
end
