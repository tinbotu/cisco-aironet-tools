miscellaneous plugins and tools for Cisco Aironet and NEC IX2000 Router
-----------------------------------------------------------------------


munin
=====

- snmp__aironet_dot11_

  a plugin monitoring IEEE802.11 statistics on Cisco Aironet.

  .. image:: http://cache.gyazo.com/9da72832b6f98c1167460b01bc7aaa5e.png


- snmp__aironet_clients_multi

  a plugin monitoring count of active clients, bridges, repeaters on Cisco Aironet.
  
  .. image:: http://cache.gyazo.com/c3f2c49b8acb12c2c72c987e0c6816cf.png


- snmp__ix2015_arpcache_entries_counts

  a plugin monitoring count of entries arp cache on NEC IX2000 series.
  
  .. image:: http://cache.gyazo.com/f1ccb379b0f4c5100bf7dd2203633399.png


- snmp__ix2015_temperature

  a plugin monitoring temperature of NEC IX2000 series.

  .. image:: http://cache.gyazo.com/57ab7296fdc3ecc7014e1b7e46222150.png



cacti
=====

- cacti-cisco-dot11-statictits.pl

  a plugin monitoring IEEE802.11 statistics on Cisco Aironet.

  *(sorry no sample image, see above version of munin)*


- cacti-ix2015-napt-entries.pl

  a plugin monitoring counts of NAPT entries on NEC IX2000 router series.

  .. image:: http://cache.gyazo.com/1fbcaacbb0a654d12069d3187d24bcbd.png


tools
=====
- disconnectLinkLocalAddressV4.pl

  This script help to disconnect IPv4 link local addres e.g. 169.254.x.x, from Cisco Aironet series.

  why?

  IPv4 link local address can happen to appear, this case that, the client associated to access point was unable to get from DHCP server. it may occurs if the access point reach capacity.

  The point is that client has 169.254 will lose internet connection and cannot resume until the user disables wifi once manually. unfortunately This is indiscernible for users.
