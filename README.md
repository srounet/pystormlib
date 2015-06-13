PyStormLib - python wrapper for StormLib
========================================

PyStormLib is a python wrapper for StormLib [Zezula StormLib](http://www.zezula.net/en/mpq/stormlib.html) that manages MPQ files.
As of version 0.1 it works on Windows x86 and only covers a few functions of StormLib such as:

* **open_mpq_archive**(path): Opens a MPQ archive.

* **search**(mask): yields MPQFileData files matching a mask

* **read**(path): Reads and return the content of a file from an MPQ archive.

* **contains**(path): Search for a MPQ archive filename within the current opened MQP archive

* **extract**(path, destination): Extract a file from an MPQ archive.


Further worke
=============

If you want more functionalities or want it to work for x64 feel free to create issues.