# AstroLib

a library of astronomy related packages

##  Installation

##  Upcoming Improvements

1.  the serialization of the *MCC* object

##  Known Issues

The MCC file, if too large, will break during the creation or add_catalog
processes.  On my personal laptop, this was true at about `600 MB`.  The code
will stop running and the existing file will become corrupt.  This is one
motivation for the rethinking of how the *MCC* object is serialized.
