OVERVIEW
========
ODR-DabMod is a DAB (Digital Audio Broadcasting) modulator compliant
to ETSI EN 300 401.

ODR-DabMod is a fork of CRC-DabMod, which was developed by the
Communications Research Center Canada and whose development has ceased.
The Opendigitalradio association now continues this project.

Short list of features:

- Reads ETI, outputs compliant COFDM I/Q
- Supports native DAB sample rate and can also
  resample to other rates
- supports all four DAB transmission modes
- Configuration file support, see doc/example.ini
- Integrated UHD output for USRP devices
  - Tested for B200, B100, USRP2, USRP1
  - With WBX daughterboard (where appropriate)
- Timestamping support required for SFN
- A FIR filter for improved spectrum mask
- Improvements in logging (log to file, to syslog)
- ETI sources: file (Raw, Framed and Streamed) and ZeroMQ
- A Telnet and ZeroMQ remote-control that can be used to change
  some parameters during runtime
- 8-bit signed I/Q output format, useful for the HackRF
- ZeroMQ PUB and REP output.

The src/ directory contains the source code of ODR-DabMod.

The doc/ directory contains the ODR-DabMod documentation, and an example
configuration file.

The lib/ directory contains source code of libraries needed to build
ODR-DabMod.

INSTALL
=======
See the INSTALL file for installation instructions.

LICENCE
=======
See the files LICENCE and COPYING

CONTACT
=======
Matthias P. Braendli <matthias [at] mpb [dot] li>
Pascal Charest <pascal [dot] charest [at] crc [dot] ca>

With thanks to other contributors listed in AUTHORS

http://opendigitalradio.org/
