blueblock-android
============

This is the android port of the blueblock game 

Feel free to contribute with pull requests to the original project by Gabriele or to this one if you have any android 
specific improvements in mind.

Play store link: 


##Building

If you want to build from source just do 

    git clone --recursive https://github.com/FrameMen/blueblock-android.git 
    cd blueblock-android/
    ./gradlew build

### With Docker
    git clone --recursive https://github.com/FrameMen/blueblock-android.git 
    cd blueblock-android/
    docker run --tty --interactive --volume=$(pwd):/opt/workspace --workdir=/opt/workspace jacekmarchwicki/android:java7  /bin/sh -c "android update sdk --all --no-ui --filter build-tools-19.1.0,android-19 ; ./gradlew build"
    
### With Eclipse

1. Copy `https://github.com/FrameMen/blueblock-android.git` to clipboard
2. File -> Import -> Git / Projects from Git -> Clone URI
3. Paste URI from clipboard (if it did not appeared automatically)
4. Next> Next> **Check "Clone submodules"**
5. Next> select "Import existing project"       

