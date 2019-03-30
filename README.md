# target_generate

this project is to generate moving targets, load targets set from ini file and generate their location points.

## Requirements
linux/C++

## How to build

target_generate works under Linux environments. I recommend a so-called out of source build which can be achieved by the following command sequence:

* mkdir build
* cd build
* cmake ../
* make -j<number-of-cores+1>

## How to use

Go to the bin diretory and launch the program with the following command:
```bash
./target_generate target_set.ini