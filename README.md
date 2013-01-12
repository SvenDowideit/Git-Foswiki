
I just want to try the http://github.com/foswiki submodules, and am going to see where it leads me

perhaps in a new dir, we might start with 

   git foswiki init
   
which might do the same as

   git init
   git submodule add http://github.com/foswiki/core
   git submodule update --init
   
then we could

   git foswiki install developer
   
which might do a submodule version of 

   pseudo-install.pl developer
