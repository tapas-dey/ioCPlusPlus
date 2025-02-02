C++ io read/write is mostly done using the following two classes

**ofstream**: Stream class to write into files

**istream**: Stream class to read from file

**ioReadWrite.cpp** shows how you can write and read some custom data using binary format.
The reason to use binary format is to scale it up or do the read/write efficiently.

**ReadSourceDataByIndex** shows how one can read just one particular object data from the file, rather than loading everything into memory. 
