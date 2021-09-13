# videosnarf

mirror of [videosnarf-0.63](http://ucsniff.sourceforge.net/videosnarf.html).

## Other woth mentioning mirrors

* https://github.com/bit4bit/videosnarf (added support G729 using bcg729)
* https://github.com/ypwangnexus/videosnarf (Adding usage for h264 analysis)

## Compilation

```
$ git clone https://github.com/tik0/videosnarf.git
$  cd videosnarf
$ ./configure
$ make
$ # Fix linking error
$ g++ -g -O2 -o videosnarf main.o stream.o videosnarf.o h264rtp.o g722_decode.o -lpcap
```
