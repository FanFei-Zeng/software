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

However, `lesstif2-dev` cannot find anymore. `motif-devel` package must install to substitute the `lesstif2-dev`.


### debug

The radware has been installed, when runing the `gf3` and the other executable files, there are some error:
```
X Error of failed request: Badname (named color or font does not exist)
   Major opcode of failed request: 45 (X_OpenFont)
   Serial number of failed request: 58
   Current serial number in output stream: 59
```

Resolution:
Intall the `xorg fonts 100dpi` and `75dpi`. For Centos 7, run 
```
>>>sudo yum install xorg-x11-fonts
>>>sudo yum intall xorg-x11-fonts-100dpi
>>>sudo yum intall xorg-x11-fonts-75dpi
```
