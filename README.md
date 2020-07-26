
## GetDESI

code for downloading jpg images of DESI data.

This is a modified version of this [code](https://github.com/canorve/sdss_jpg)

you can introduce a file of galaxies (name,ra,dec) and obtain the images
of that list of galaxies (or any other object).


## Quick Example:

To test and download an image:
```
 import GetDESI
 GetDESI.simg()
```
It will download and display an image from DESI.

you can set RA, DEC, image size. Just follow this example:

```
GetDESI.simg(ra=37.228,dec=0.37, scale=0.396, width=512, height=512,
    savename=None, init_download=True,show=True)
```

To download multiple images using a file with coordinates:
```
GetDESI.DownFile(file, scale=0.396, width=512, height=512, show=False):
```
