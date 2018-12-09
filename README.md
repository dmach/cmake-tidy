Clean up CMakeLists.txt files:

* convert all commands to lower case
* remove spaces between commands and parenheses
* remove arguments in elseif, else and endif commands
* fix indentation


Usage:

    $ cmake-tidy [-h] [-i] PATH [PATH ...]


Example (single file):

    $ cmake-tidy -i CMakeLists.txt


Example (all CMakeLists under working directory):

    $ find -name 'CMakeLists.txt' -exec cmake-tidy -i {} \;
