# simple-fs
A flat, persistent file system in C

1. Set umask to 022
2. Create the fs with desired configuration
3. Run tests.

How to compile and run
$ rm -f ./myfs.fs; g++ -w -c -g *.cc; g++ -g -w -o exe *.o -lpthread
