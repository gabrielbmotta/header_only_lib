# header_only_lib

Gets all c/cpp code in the specified directories and makes puts them in a single header file, ordering them based on inter-file dependencies.

Run with path to source directories as first arg and output file as second arg.

`./headerlib "/path/to/lib1 path/to/lib2" my_header_lib.h`

Works on mac :)
It's probably necessary to change the flags on grep and sed for linux. (`-E` on grep should be `-P` and `-i ''` is just `-i`)
