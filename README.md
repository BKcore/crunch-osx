# crunch-osx

A version of the Crunch DXT compressor that compiles on OSX (from: https://code.google.com/p/crunch/)

# Compilation

Note that you'll need g++ 4.8+, this does not work with clang.

```
cd crnlib
CXX=/path/to/g++4.8+ make
mv crnlib/crunch bin_osx/crunch
```

# Tested on

- OSX 10.9.5 / g++ 4.8
