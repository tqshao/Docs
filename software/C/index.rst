

Including files
================
There are 2 kinds of include directives:

    * double quoted ones (#include "xyz.h")

        *  the working directory

    * angle bracket ones (#include <xyz.h>)

        * usually /usr/include/.

Other Notes
^^^^^^^^^^^^

    * Place the header file in the same directory as your .c file and use -I. when compiling
    * You shouldn't place your header files in /usr/include that is meant for the system headers.

Useful resources
^^^^^^^^^^^^^^^^^^

    * https://stackoverflow.com/questions/27660713/including-header-file-from-static-library
