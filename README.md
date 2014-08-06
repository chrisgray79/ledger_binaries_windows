ledger_binaries_windows
=======================

Ledger 3.0.3 binaries for Windows 64-bit (compiled with mingw64 4.9.1).

Ledger is a powerful, double-entry accounting system. Ledger is writen by John Wiegley and released under the BSD license:
http://www.ledger-cli.org

It's the only financial software that meets all my needs.

It is compiled by myself. What may not be working in this version is:
- ids in XML output
- python interface
as I had to comment out casting 64-bit addresses to 32-bit integer type in that code.
But everything else seems to work great!
