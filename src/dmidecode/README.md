# Dmidecode: Desktop Management Interface table related utilities

Distributed under the terms of the [GNU GPL v2](https://github.com/X0rg/CPU-X/blob/master/src/dmidecode/LICENSE).


### CPU-X NOTE

This sofware has been patched to be used within CPU-X.  
You can find the official web page of this project here: http://savannah.nongnu.org/projects/dmidecode/  
This is based on dmidecode 3.0+[r36.77ac1e2](http://git.savannah.gnu.org/cgit/dmidecode.git/commit/?id=77ac1e2c087f85c962ad5adeb9e476a515aced76).

This software is used to retrieve following data:
* CPU tab
  * Package
  * Bus speed (fallback)
* Motherboard tab
  * Motherboard manufacturer
  * Motherboard model
  * Motherboard revision
  * BIOS brand
  * BIOS version
  * BIOS date
  * BIOS ROM size

You can reproduce the output of `dmidecode` command by using `cpu-x --dmidecode`.  
It will dump all DMI data on standard output.  
Note: you can increase dmidecode verbosity by using `cpu-x --verbose --dmidecode`.
