$:.unshift << "/home/alban/share/projects/tryphon.org/rake-debian-build/lib"

require 'debian/build'
include Debian::Build

require 'debian/build/config'

namespace "package" do

  Package.new(:passenger) do |t|
    t.version = '2.1.3'
    t.debian_increment = 1
  end

end

require 'debian/build/tasks'

