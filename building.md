
### For Building jdk9 required boot jdk is jdk8
```
sudo apt-get install libx11-dev libxext-dev libxrender-dev libxtst-dev libxt-dev

sudo apt-get install libx11-dev libxext-dev libxrender-dev libxrandr-dev libxtst-dev libxt-dev

sudo apt-get install libcups2-dev

sudo apt-get install libfreetype6-dev

sudo apt-get install libasound2-dev

sudo apt-get install libelf-dev

sudo apt-get install libfontconfig1-dev

Change Default Java

sudo update-alternatives --config java

// https://wiki.openjdk.java.net/display/Build/Supported+Build+Platforms

// http://hg.openjdk.java.net/jdk/jdk11/raw-file/tip/doc/building.html

// https://github.com/openjdk/jdk/blob/master/doc/building.md

bash configure
make images
./build/*/images/jdk/bin/java -version
make run-test-tier1
```
