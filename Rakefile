# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './lib/stompserver.rb'

Hoe.new('stompserver', StompServer::VERSION) do |p|
  p.rubyforge_name = 'stompserver'
  p.summary = 'A very light messaging server'
  p.description = p.paragraphs_of('README.txt', 2..4).join("\n\n")
  p.url = p.paragraphs_of('README.txt', 0).first.split(/\n/)[1..-1]
  p.changes = p.paragraphs_of('History.txt', 0..1).join("\n\n")
  p.email = "phurley@gmail.com"
  p.author = ["Patrick Hurley"]  
  p.extra_deps = [
                  ["eventmachine", ">= 5.0.0"], 
                  ["hoe", ">= 1.1.1"]
                 ]
end

# vim: syntax=Ruby