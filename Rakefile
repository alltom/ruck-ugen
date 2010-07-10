require "rubygems"
require "rake"

begin
  require "jeweler"
  Jeweler::Tasks.new do |gem|
    gem.name = "ruck-ugen"
    gem.email = "tom@alltom.com"
    gem.homepage = "http://github.com/alltom/ruck-ugen"
    gem.authors = ["Tom Lieber"]
    gem.summary = %Q{ruck shreduler + mini audio unit generator framework inspired by ChucK}
    gem.description = <<-EOF
      A ruck shreduler and mini audio unit generator framework inspired by ChucK.
      Includes library for reading and writing multi-channel WAV files, and some
      basic audio filters.
    EOF
    gem.has_rdoc = false
    gem.add_dependency "ruck", ">= 0"
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end
