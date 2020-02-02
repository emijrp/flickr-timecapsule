# flickr-timecapsule

Some of my pictures on Flickr, resized to < 100 KB to fit [GitHub Arctic Code Vault](https://archiveprogram.github.com/) filesize limit.

My pictures are CC-BY-SA licensed.

## Technical details

Useful command to resize all pictures in a directory:

find . -maxdepth 1 -iname "*.jpg" | xargs -L1 -I{} convert -define jpeg:extent=90kb "{}" "{}"

Be careful, it overwrites files.

## Example image

![](/im/Archivo_Municipal-9101424836.jpg)
