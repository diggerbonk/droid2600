# Updates in 2024

The last formal release of Droid2600 was build #16 in January 2011. At this time, 
Android Froyo would have been state of the art, and I think I was developing 
against Eclair. 

    Froyo: Android version 2.2, API Level 8
    Eclair: Android version 2.0/2.1, API level 5/6/7

I had also made minor modifications of the Stella sources, those are still 
available on google code.

    https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/droid2600/stella-2010-08-09-droid2600-15.tar.gz


# Environment

   zipalign, in the old SDK tools package, is 32 bits and needs libraries that
   are packed with with, I ended up pointing to one in a newer SDK:

   export PATH=$PATH:/home/trent/soft/android-sdk/build-tools/25.0.2/

   # in teh following file i had to update the java version
   $ vi /home/trent/soft/android-sdk/tools/ant/build.xml
