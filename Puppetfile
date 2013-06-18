forge 'http://forge.puppetlabs.com/'

mod 'puppetlabs/stdlib', '~> 3.0'

mod 'gds_dns',
  :git => 'git://github.com/alphagov/puppet-gds_dns.git'

# These should actually be a Modulefile dep of gds_dns.
mod 'hosts',
  :git => 'git://github.com/alphagov/puppet-hosts.git'
mod 'resolvconf',
  :git => 'git://github.com/alphagov/puppet-resolvconf.git'
mod 'dnsmasq',
  :git => 'git://github.com/alphagov/puppet-dnsmasq.git',
  :ref => 'anchor_reload_and_resolvconf'
