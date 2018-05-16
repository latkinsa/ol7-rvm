# ol7-rvm
dockerfiles for ol7/rvm/rubies

Pre-built images are available at `latkinsa/ol7-rvm` docker repo:

* latkinsa/ol7-rvm:rvm-base - pre-installed rvm without any ruby versions
* latkinsa/ol7-rvm:ruby-1.9.3.y
* latkinsa/ol7-rvm:ruby-2.4.3.y

To re-build rubies from rvm-base, download libyaml and libyaml-devel packages and place them here:

libyaml-0.1.7-5.fc28.x86_64.rpm
libyaml-devel-0.1.7-5.fc28.x86_64.rpm

(or newer ones)
