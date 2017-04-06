## It's Faster. ##
There is nothing [faster](https://github.com/brettwooldridge/HikariCP/wiki/Benchmarks).  There is
nothing more [correct](https://github.com/brettwooldridge/HikariCP/wiki/Correctness).  HikariCP is a "zero-overhead"
production-quality connection pool.

Using a stub-JDBC implementation to isolate and measure the overhead of HikariCP, comparative benchmarks were
performed on a commodity PC.

<a href="https://github.com/brettwooldridge/HikariCP/wiki/HikariCP-bench-2.6.0.png"><img src="https://github.com/brettwooldridge/HikariCP/wiki/HikariCP-bench-2.6.0.png" width="680"/></a>

Just drop it in and let your code run like its pants are on fire.

_Java 8 maven artifact:_

    <dependency>
        <groupId>com.zaxxer</groupId>
        <artifactId>HikariCP</artifactId>
        <version>2.6.1</version>
        <scope>compile</scope>
    </dependency>

_Java 7 maven artifact:_

        <dependency>
            <groupId>com.zaxxer</groupId>
            <artifactId>HikariCP-java7</artifactId>
            <version>2.4.11</version>
            <scope>compile</scope>
        </dependency>

_Java 6 maven artifact:_

    <dependency>
        <groupId>com.zaxxer</groupId>
        <artifactId>HikariCP-java6</artifactId>
        <version>2.3.13</version>
        <scope>compile</scope>
    </dependency>

### Initialization and Configuration###

See the [main project page](https://github.com/brettwooldridge/HikariCP#initialization) for initialization examples.

You can find information about the [configuration properties here](https://github.com/brettwooldridge/HikariCP#configuration-knobs-baby).

### Support ###
Google discussion group [HikariCP here](https://groups.google.com/d/forum/hikari-cp).

### Requirements ###
* Java 6 and above
* slf4j library
