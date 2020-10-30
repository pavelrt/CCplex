# CCplex
This package allows to import Cplex library into swift projects.

The file module.modulemap contains path to cplex headers.


## Package config file (pkg-config)
Configuration file for c/c++ compiler and linker.

Copy libcplex.cp to your pkg-config directory.
On OS X copy to: /usr/local/lib/pkgconfig
On linux copy to: /usr/lib/pkgconfig

Uncomment OS X libs or Linux libs depending on your platform.

1) Install cplex. (Preferably on path specified in module.modulemap file)
2) copy libcplex.cp file.
3) Add the following dependency into your Package.swift : .package(url: "git@github.com:pavelrt/CCplex.git", from: "12.7.2"),
4) import CCplex
