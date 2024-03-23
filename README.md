EJOY 2D
=======

ubuntu 22.04

* install glew

```
sudo apt-get install libglew-dev
```

* install freetype

```
sudo apt-get install libfreetype6-dev
```

* install font

path `posix/winfont.c` pre define font, you can change font. put font in dir, then

```
fc-cache -f -v
```
* make 
* ./ej2d examples/ex01.lua to test