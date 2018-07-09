# CCplex
This package provides modulemap for Cplex. It just contains paths to cplex library.
## Module map
The file module.modulemap contains path to cplex header.


## Package config file
Configuration file for compiler and linker.

Remember to copy libcplex.cp to pkg-config directory .
On OS X copy to: /usr/local/lib/pkgconfig
On linux copy to: /usr/lib/pkgconfig

Remember to uncomment OS X libs or Linux libs depending on your platform.
