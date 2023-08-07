### Cloing `master` branch of `depth=1` will work
[Build Instruction](https://openjdk.org/groups/build/doc/building.html)

```
For Building jdk9 required boot jdk is jdk8
For Building jdk-23 required boot jdk is 20/21/22
```

```
git clone https://git.openjdk.org/jdk/ --depth=1
cd jdk
bash configure --with-boot-jdk=/opt/jdk
make images
./build/*/images/jdk/bin/java -version
make run-test-tier1
```
