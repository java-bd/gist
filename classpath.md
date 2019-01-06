## Intellij Classpath for Command Line Compile & Run for Windows and Linux
```sh
javac -d out/production/apidemo -cp lib/* src/*.java &
java -cp lib/*;out/production/apidemo/ Main
```
