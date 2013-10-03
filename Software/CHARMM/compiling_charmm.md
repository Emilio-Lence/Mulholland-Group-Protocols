###Compiling CHARMM

\#In the CHARMM source directory
\#First clean up the build directory \(equivalent to \"make clean\"\)
$rm -r lib/\*                     
$rm -r exec/\*                    
$rm build/gnu/pref.dat

!then compile charmm 
$./install.com gnu xlarge

###Compiling in parallel (required for use with EVB/RPMD)

$./install.com gnu MPICH E

you will be asked to enter the absolute path to the mpi 
include files and mpi libraries

on curie they are here:
/users/pb4941/local/mpp/mpich2-install/include
/users/pb4941/local/mpp/mpich2-install/lib
