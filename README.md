# header_only_lib

Run with libs as first arg and outfile as second arg.

`./headerlib "/path/to/lib1 path/to/lib2" my_header_lib.h`

Works on mac :)
It's probably necessary to change the flags on grep and sed for linux. (`-E` on grep should be `-P` and `-i ''` is just `-i`)
