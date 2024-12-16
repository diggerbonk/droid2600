# Updates in 2024

The last formal release of Droid2600 was build #16 in January 2011. At this time, 
Android Froyo would have been state of the art, and I think I was developing 
against Eclair. 

    Froyo: Android version 2.2, API Level 8
    Eclair: Android version 2.0/2.1, API level 5/6/7

I had also made minor modifications of the Stella sources, those are still 
available on google code.

    https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/droid2600/stella-2010-08-09-droid2600-15.tar.gz


# Set up Build Environment for 2011-style Era Build

   See: https://apilevels.com/
   See also: https://developer.android.com/tools/releases/sdk-tools

   Android Target: Gingerbread
   API Level: 10
   

   Prerequisites:

   Java JDK
   
      * Java SE 7 (a.k.a. 1.7) was state of the art in the 2011 time frame, 
        java 1.8 works and is readily available for Fedora. so use 1.8 
        and use the 'alternatives' tool to configure Fedora to use that 
        version (but see the Fixes / Modifications below)

   Apache Ant

      Seems to be the supported build system before SDK v24 (2014)
      The goal is to migrate to Gradle, but for now it's Ant. Version 1.8 or later 
      is requred according to the docs.

   Android SDK.

   Fixes / Modifications

       zipalign, in the old SDK tools package, is 32 bits and needs libraries that
       are packed with with, I ended up pointing to one in a newer SDK:

       export PATH=$PATH:/home/trent/soft/android-sdk/build-tools/25.0.2/

       Make sure the build.xml and uibuild.xml files in <sdk>/tools/ant/ have 
       java set to 1.7 

# Set up for 
