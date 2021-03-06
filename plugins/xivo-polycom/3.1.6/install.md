# Installation

WARNING: you SHOULD NOT use this plugin if your phones are using BootROM
version 2.5.x or ealier.

WARNING: you SHOULD NOT use this plugin if your phones are not using the SIP
Application 3.1.6.0017 AND you don't plan on upgrading your phone to this
version.


This plugin is targeting Polycom phones in version 3.1.6.0017, i.e. Polycom
phones using the SIP Application 3.1.6.0017.

SIP Application 3.1.6.0017 necessitate the following BootROM version:
- 2.6.1 or later for IP301, IP501 and IP600
- 3.1.0 or later for IP601
- 3.1.2 or later for IP4000.

This is why this plugin is also targeting Polycom phones using BootROM in
version 4.1.4.0122, which is the latest BootROM that all the targeted phones
support.

The problem is, it's not possible to upgrade the BootROM from version 2.5.x
or earlier to version 4.1.4.0122.

It's important to only use phones that are using the SIP Application 3.1.6.0017
since the sip.cfg and phone1.cfg configuration file are strongly tied to this
particular version of the SIP application. That's why you should either
download the firmware files of this plugin or you should make sure your phones
are using SIP Application 3.1.6.0017, or you might have incorrect behavior.
