# Installation

This plugin targets Alcatel IP Touch "extended edition" phones, i.e. the IP
Touch phones which are capable of running in SIP standalone mode. This plugin
can also be used to go from NOE to SIP mode. To be able to use SIP standalone
mode, the phone must run at least firmware NOE 4.xx.xx.

If you want to use the synchronize facility of the plugin, you must have
the python 'pexpect' module and the telnet executable installed on your
system.

The 'admin_password' config parameter is used for the telnet password
and the phone UI admin password. Note that if you modify the telnet password,
synchronize will not work until the phone gets synchronized, i.e. you may
have to manually telnet to the phone with the old password or restart the
phone from another way.
