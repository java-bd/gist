## Benchmark JVM (Machine Utilizing All Cpu Cores)
```
import java.util.stream.*;
long start = System.currentTimeMillis();
long result = LongStream.range(1, 1_00_000_000_000L).parallel().filter(x -> x % 2 == 0).count();
long end = System.currentTimeMillis();
System.out.println("Count: " + result + ", Time: " + (end - start) + "ms");
```
### In Intel Core i7 Machine (11th Gen)
```
Count: 49999999999, Time: 15944ms
```
