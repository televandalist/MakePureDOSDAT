# Make Pure DOS DAT
This is a simple tool to generate data file XML entries from DOSZ files.

## Usage
Just launch the tool in the command prompt with one or more DOSZ files as its argument(s):
```sh
MakePureDOSDAT PathToFile.dosz PathToAnotherFile.dosz
```

Or to export the output to a file instead of writing it to the console:
```sh
MakePureDOSDAT PathToFile.dosz PathToAnotherFile.dosz >MyPureDOSDAT.xml
```

## Download
You can find the download for Windows under the [Releases page](../../releases/latest).  

For other platforms, see the section below on how to compile the command line tool.

## Compiling
On Windows you can use Visual Studio to compile the command line tool.

For other platforms use either `./build-gcc.sh` or `build-clang.sh` to compile the tool for your system.

## License
Make Pure DOS DAT is available under the [Unlicense](http://unlicense.org/) (public domain).
