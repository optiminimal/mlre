# mlre

This an adaption of tehn's mlr script.

mlre started as a personal project to learn to code. Understanding more about the architecure and basics of lua, norns scripts and softcut sparked many ideas. These additional features are built around the original script, so the core of mlr remains unchanged.

I'd like to point out that there might be some bits of code that might be messy/redundant or features that could be coded more efficiently/elegantly. PR's are welcome.

Also, this wouldn't have been possible without the countless contributions made by many members of ////////! Studying other scripts and comments on the forum and discord channel have been, and will continue to be, **an immense source of knowlage**! 

A special thanks to **tehn** for creating mlr and **zebra** for softcut, answering questions and some very helpful lines of code. Also a great thanks to **justmat**, **infinitedigits** and **dan_derks** for inspiration, support, answering questions and some very helpful lines of code.

## arc support

Enc 2 displays the selected track.

Use the lowest row on your grid to toggle alt mode. 
_(left: toggle all encoders, right: toggle each encoder individually)_
### Enc 1: 
- scrub audio buffer
- start/stop audio (alt mode)

Loop on:
- edit loop start
- edit loop end (alt mode)

### Enc 2:
- speed
- reverse (alt mode)

the lower half indicates the selected track

### Enc 3:
- rate slew
- speed mod (alt mode)

### Enc 4:
- volume
- panning (alt mode)

#### arc support for original mlr by [NiklasKramer](https://github.com/NiklasKramer/mlr_Arc)

### Documentation: [mlre user guide](https://github.com/sonocircuit/mlre/blob/main/docs/MLRE_USER%20GUIDE%201.3.4.pdf)

## Roadmap:
- cleanup and bugfixes   
- re-write lfos
