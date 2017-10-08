# AstroLib

a library of astronomy related packages

##  Installation

1.  clone/download this library and all of the packages in it
    *   Io, MCC may also be obtained from this github page

2.  the `AstroLib/` directory needs to be placed in the `PYTHONPATH`
```
export  PYTHONPATH="${PYTHONPATH}:/path_to_astrolib/AstroLib/"
```

3.  the `Scripts/` directory needs to be placed in `PATH`
```
export  PATH="${PATH}:/path_to_astrolib_scripts/Scripts/"
```

For each package in AstroLib, a README.md text file is included with specific
usage instructions for that package.

##  Upcoming Improvements

1.  the serialization of the *MCC* object
2.  many *MCC* functions need to be rewritten to script under the new system
3.  SExtractor tools need to be added to the new system

##  Known Issues

The MCC file, if too large, will break during the creation or add_catalog
processes.  On my personal laptop, this was true at about `600 MB`.  The code
will stop running and the existing file will become corrupt.  This is one
motivation for the rethinking of how the *MCC* object is serialized.
