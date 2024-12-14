$ cd ~/soft/
$ wget https://dl.google.com/android/ndk/android-ndk-r9d-linux-x86_64.tar.bz2
$ tar xjvf android-ndk-r9d-linux-x86_64.tar.bz2
$ ln -s android-ndk-r9d android-ndk
$ mkdir android-sdk
#$ cd android-sdk
#$ wget https://dl.google.com/android/repository/commandlinetools-linux-11076708_latest.zip
#$ unzip commandlinetools-linux-11076708_latest.zip
#$ ./cmdline-tools/bin/sdkmanager --sdk_root=/home/trent/soft/android-sdk --include_obsolete --list
#$ ./cmdline-tools/bin/sdkmanager --sdk_root=/home/trent/soft/android-sdk --install "platforms;android-4"
## installing build tools 19.0.3 because it was from around the same time as android 4 (kitkat)
#$ ./cmdline-tools/bin/sdkmanager --sdk_root=/home/trent/soft/android-sdk --install "build-tools;19.0.3"
#$ ./cmdline-tools/bin/sdkmanager --sdk_root=/home/trent/soft/android-sdk --install tools
$ cd ~/soft
$ wget https://dl.google.com/android/archives/android-sdk-linux_x86-1.6_r1.tgz
$ tar xzvf android-sdk-linux_x86-1.6_r1.tgz
$ ln -s android-sdk-linux_x86-1.6_r1 android-sdk

