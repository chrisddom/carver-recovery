A utility based on Scalpel that uses file carving was produced to recover files.

## Recover lost files ##

# [Standalone Application 1.0](http://code.google.com/p/carver-recovery/downloads/detail?name=Portable_Executable.zip&can=2&q=) #
[Documentation](http://code.google.com/p/carver-recovery/downloads/detail?name=Help.pdf&can=2&q=) [Sourcecode](http://code.google.com/p/carver-recovery/downloads/detail?name=Source.zip&can=2&q=)

### Benefits ###
  * Recover files from images of disks that have severely damaged or erased disks


## How it works ##
  * Running Scalpel (http://www.digitalforensicssolutions.com/Scalpel/) with a customized config file against the image
  * Then running Exif tool against MSOffice files to discover their file type from meta data
  * Presenting the results with the required information (type, size, hashes etc.)


## About ##
Created by Christopher Doman (http://www.christopherdoman.com) for the DC3 Forensics Challenge 2012 (http://www.dc3.mil/challenge/2012). Created on quite a short schedule, so please consider this beta software and inform me of any bugs.

![http://carver-recovery.googlecode.com/files/screenshot.png](http://carver-recovery.googlecode.com/files/screenshot.png)