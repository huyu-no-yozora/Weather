# GrADS Manual


## Table of Contents(TOC)
<!--ts-->
* [Environmental Configuration](#environmental-configuration)
* [Fundamental Knowledge](#fundamental-knowledge)
  * [NetCDF Format or Binary Format](#netcdf-format-or-binary-format)
* [Fundamental Operation](#fundamental-operation)
  * [Boot and Exit](#boot-and-exit)
    * [Boot of GrADS](#boot-of-grads)
    * [Exit from GrADS](#exit-from-grads)
* [Analysis](#analysis)
    * [Contour Env](#contour-env)
    * [Shade Env](#shade-env)
* [GrADS Script](#grads-script)
* [Reference](#reference)
* [License](#license)
<!--te-->


-----------------------------

## Environmental Configuration
<kbd>Alt + D</kbd>を押してTerminalを複製。

## Fundamental Knowledge
### NetCDF Format or Binary Format

#### NetCDF


#### Binary
read a binary file as the big endian
```
option big_endian
```
read a binary file as the litte endian
```
option little_endian
```


## Fundamental Operation
### Boot and Exit

#### Boot of GrADS
booting by landscape mode
```bash
grads -l
```
#### Exit from GrADS
```bash
quit
```

## Analysis
### Contour Env
```
set gxout contour
```
### Shade Env
```
set gxout shade2
```

## GrADS Script
.gs file


## Reference
* [GrADS Offical HP](http://cola.gmu.edu/grads/)
* [Tohoku University](http://wind.gp.tohoku.ac.jp/index.php?%B8%F8%B3%AB%BE%F0%CA%F3/GrADS/GrADS%A4%CETips)


## License
<!-- <email@example.com> -->


