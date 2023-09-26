## RADWARE 
RadWare is a software package for interactive graphical analysis of gamma-ray coincidence data. It was developed by David Radford of the Physics Division at Oak Ridge National Laboratory.

The package can be download from [https://radware.phy.ornl.gov/](https://radware.phy.ornl.gov/)

Before install the software, some package is needed.

```
gcc
make
libreadline-dev (readline-devel for centos)
libgtk2.0-dev (gtk2-devel for centos)
lesstif2-dev
```

However, `lesstif2-dev` cannot find anymore. `motif` package must install to substitute the `lesstif2-dev`.
