# Filesort
Sorts files from given directory by file extension (linux)

<<<<<<< HEAD
## TODO: 
* Add fancy output (if needed)
* Add flags 
* Add create destination directory option 
* Add ability to sort directory other than current working directory 
* Add verbose output 
* Customize output 
      
=======
# TODO: 
1. Add fancy output (if needed)
2. Add verbose output
3. Add create destination directory option 
4. Add ability to sort directory other than current working directory 
5. Add verbose output 
6. Customize output 
7. Add version output
8. Update this README with more detailed usage information
9. make default output directory the current directory for some erros

#usage:
filesort [-h] [-e EXT] [-f] [PATH] [DEST]

positional arguments:
  PATH                  sort this directory (default is current directory)
  DEST                  move files to this directory (ignored if sorting
                        entire folder)

optional arguments:
  -h, --help            show this help message and exit
  -e EXT, --extension EXT
                        sort by this file extension
  -f, --force           create destination directory if it doesn't exist


>>>>>>> sortfile_redo
