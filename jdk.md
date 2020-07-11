## Oracle JDK Install and set alternative default
```sh
sudo dpkg -i jdk-14.0.1_linux-x64_bin.deb 
sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-14.0.1/bin/java 1
sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-14.0.1/bin/javac 1
java --version
javac --version
```

## Set Environmental Variables
* `/etc/environment`
```sh
JAVA_HOME="/usr/lib/jvm/jdk-14.0.1"
ANDROID_SDK_ROOT="/opt/android/sdk"
```

## Flutter android config
```sh
flutter config --android-sdk /opt/android/sdk/
```
