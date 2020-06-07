# JEP 286: Local-Variable Type Inference

```java
package demo;

import java.util.List;

public class Example {

  public static void main( final String[] args ) {
    final List<String> a = List.of( "a", "b", "c" );
    final var b = List.of( "a", "b", "c" );
  }
}
```

```java
package demo;

import java.util.stream.Collectors;
import java.util.stream.Stream;

public class Example {

  public static void main( final String[] args ) {
    final var list = Stream.of( "a", "bb", "ccc" )
      .map( s -> new Object() {
        private final String string = s;
        private final int length = s.length();
      } )
      .collect( Collectors.toList() );

    for ( var item : list ) {
      System.out.printf( "The string %s is %d Unicode units long%n", item.string, item.length );
    }
  }
}
```
