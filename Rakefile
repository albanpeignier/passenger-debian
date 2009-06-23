$:.unshift << "/home/alban/share/projects/tryphon.org/rake-debian-build/lib"

require 'debian/build'
include Debian::Build

require 'debian/build/config'

namespace "package" do

  Package.new(:passenger) do |t|
    t.version = '2.2.4'
    t.debian_increment = 1

    t.source_provider = TarballSourceProvider.new('http://rubyforge.org/frs/download.php/59007/passenger-#{version}.tar.gz')
  end

end

require 'debian/build/tasks'

