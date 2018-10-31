Initial NTP-Status integration include file.

This currently supports the standard ntpd package, which must be pre-installed, and as well as the
enhanced Linux one (where ntpq has a wide option). Needs more testing across OSes

Requires bash, will not work with default Bourne or Korn shells as it requires bash specific extensions.

How to use:

Download at least the XML file or use the remote "raw" URL direct from github for systems that have external
public access and once validated add an NTP-Status sampler to your chosen Managed Entities or into your
preferred infrastructure monitoring Type. 

Additionally the environment variable NTPHOST can be defined to query a remote host. Default is a localhost connection.

The PATH environment variable is defined in the default sampler as most users do not have ntpq in their default path.

TODO:
* Windows support for Meinberg NTPD
* Chrony support (Different sampler)

