# What's new in Java

| Java                        | Status                                               |
| --------------------------- | ---------------------------------------------------- |
| [Java 8](#java-8-lts)       |                                                      |
| [Java 9](#java-9-non-lts)   | Not Supported, switch to [Java 11](#java-11-lts)     |
| [Java 10](#java-10-non-lts) | Not Supported, switch to [Java 11](#java-11-lts)     |
| [Java 11](#java-11-lts)     |                                                      |
| [Java 12](#java-12-non-lts) | Not Supported, switch to [Java 14](#java-14-non-lts) |
| [Java 13](#java-13-non-lts) | Not Supported, switch to [Java 14](#java-14-non-lts) |
| [Java 14](#java-14-non-lts) |                                                      |
| [Java 15](#java-15-non-lts) | Preview                                              |

## Java 8 (LTS)

## Java 9 (non-LTS)

## Java 10 (non-LTS)

The [Java SE 10 Platform](https://openjdk.java.net/projects/jdk/10/) was defined by [JSR 383](https://www.jcp.org/en/jsr/detail?id=383) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | March 2018     |
| End of life | September 2018 |

### New Features

| JEP                                          | Description                                                                                                                                             |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [JEP 286](https://openjdk.java.net/jeps/286) | [Local-Variable Type Inference](Java%2010/JEP%20286%20-%20Local-Variable%20Type%20Inference.md)                                                         |
| [JEP 296](https://openjdk.java.net/jeps/296) | [Consolidate the JDK Forest into a Single Repository](Java%2010/JEP%20296%20-%20Consolidate%20the%20JDK%20Forest%20into%20a%20Single%20Repository.md)   |
| [JEP 304](https://openjdk.java.net/jeps/304) | [Garbage-Collector Interface](Java%2010/JEP%20304%20-%20Garbage-Collector%20Interface.md)                                                               |
| [JEP 307](https://openjdk.java.net/jeps/307) | [Parallel Full GC for G1](Java%2010/JEP%20307%20-%20Parallel%20Full%20GC%20for%20G1.md)                                                                 |
| [JEP 310](https://openjdk.java.net/jeps/310) | [Application Class-Data Sharing](Java%2010/JEP%20310%20-%20Application%20Class-Data%20Sharing.md)                                                       |
| [JEP 312](https://openjdk.java.net/jeps/312) | [Thread-Local Handshakes](Java%2010/JEP%20312%20-%20Thread-Local%20Handshakes.md)                                                                       |
| [JEP 313](https://openjdk.java.net/jeps/313) | [Remove the Native-Header Generation Tool (`javah`)](Java%2010/JEP%20313%20-%20Remove%20the%20Native-Header%20Generation%20Tool%20%28%60javah%60%29.md) |
| [JEP 314](https://openjdk.java.net/jeps/314) | [Additional Unicode Language-Tag Extensions](Java%2010/JEP%20314%20-%20Additional%20Unicode%20Language-Tag%20Extensions.md)                             |
| [JEP 316](https://openjdk.java.net/jeps/316) | [Heap Allocation on Alternative Memory Devices](Java%2010/JEP%20316%20-%20Heap%20Allocation%20on%20Alternative%20Memory%20Devices.md)                   |
| [JEP 317](https://openjdk.java.net/jeps/317) | [Experimental Java-Based JIT Compiler](Java%2010/JEP%20317%20-%20Experimental%20Java-Based%20JIT%20Compiler.md)                                         |
| [JEP 319](https://openjdk.java.net/jeps/319) | [Root Certificates](Java%2010/JEP%20319%20-%20Root%20Certificates.md)                                                                                   |
| [JEP 322](https://openjdk.java.net/jeps/322) | [Time-Based Release Versioning](Java%2010/JEP%20322%20-%20Time-Based%20Release%20Versioning.md)                                                         |

## Java 11 (LTS)

The [Java SE 11 Platform](https://openjdk.java.net/projects/jdk/11/) was defined by [JSR 384](https://www.jcp.org/en/jsr/detail?id=384) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | September 2018 |
| End of life | September 2023 |

### New Features

| JEP                                          | Description                                                                                                                                            |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [JEP 181](https://openjdk.java.net/jeps/181) | [Nest-Based Access Control](Java%2011/JEP%20181%20-%20Nest-Based%20Access%20Control.md)                                                                |
| [JEP 309](https://openjdk.java.net/jeps/309) | [Dynamic Class-File Constants](Java%2011/JEP%20309%20-%20Dynamic%20Class-File%20Constants.md)                                                          |
| [JEP 315](https://openjdk.java.net/jeps/315) | [Improve Aarch64 Intrinsics](Java%2011/JEP%20315%20-%20Improve%20Aarch64%20Intrinsics.md)                                                              |
| [JEP 318](https://openjdk.java.net/jeps/318) | [Epsilon: A No-Op Garbage Collector](Java%2011/JEP%20318%20-%20Epsilon%3A%20A%20No-Op%20Garbage%20Collector.md)                                        |
| [JEP 320](https://openjdk.java.net/jeps/320) | [Remove the Java EE and CORBA Modules](Java%2011/JEP%20320%20-%20Remove%20the%20Java%20EE%20and%20CORBA%20Modules.md)                                  |
| [JEP 321](https://openjdk.java.net/jeps/321) | [HTTP Client (Standard)](Java%2011/JEP%20321%20-%20HTTP%20Client%20%28Standard%29.md)                                                                  |
| [JEP 323](https://openjdk.java.net/jeps/323) | [Local-Variable Syntax for Lambda Parameters](Java%2011/JEP%20323%20-%20Local-Variable%20Syntax%20for%20Lambda%20Parameters.md)                        |
| [JEP 324](https://openjdk.java.net/jeps/324) | [Key Agreement with Curve25519 and Curve448](Java%2011/JEP%20324%20-%20Key%20Agreement%20with%20Curve25519%20and%20Curve448.md)                        |
| [JEP 327](https://openjdk.java.net/jeps/327) | [Unicode 10](Java%2011/JEP%20327%20-%20Unicode%2010.md)                                                                                                |
| [JEP 328](https://openjdk.java.net/jeps/328) | [Flight Recorder](Java%2011/JEP%20328%20-%20Flight%20Recorder.md)                                                                                      |
| [JEP 329](https://openjdk.java.net/jeps/329) | [ChaCha20 and Poly1305 Cryptographic Algorithms](Java%2011/JEP%20329%20-%20ChaCha20%20and%20Poly1305%20Cryptographic%20Algorithms.md)                  |
| [JEP 330](https://openjdk.java.net/jeps/330) | [Launch Single-File Source-Code Programs](Java%2011/JEP%20330%20-%20Launch%20Single-File%20Source-Code%20Programs.md)                                  |
| [JEP 331](https://openjdk.java.net/jeps/331) | [Low-Overhead Heap Profiling](Java%2011/JEP%20331%20-%20Low-Overhead%20Heap%20Profiling.md)                                                            |
| [JEP 332](https://openjdk.java.net/jeps/332) | [Transport Layer Security (TLS) 1.3](Java%2011/JEP%20332%20-%20Transport%20Layer%20Security%20%28TLS%29%201.3.md)                                      |
| [JEP 333](https://openjdk.java.net/jeps/333) | [ZGC: A Scalable Low-Latency Garbage Collector (Experimental)](Java%2011/JEP%20333%20-%20ZGC%3A%20A%20Scalable%20Low-Latency%20Garbage%20Collector.md) |
| [JEP 335](https://openjdk.java.net/jeps/335) | [Deprecate the Nashorn JavaScript Engine](Java%2011/JEP%20335%20-%20Deprecate%20the%20Nashorn%20JavaScript%20Engine.md)                                |
| [JEP 336](https://openjdk.java.net/jeps/336) | [Deprecate the Pack200 Tools and API](Java%2011/JEP%20336%20-%20Deprecate%20the%20Pack200%20Tools%20and%20API.md)                                      |

## Java 12 (non-LTS)

The [Java SE 12 Platform](https://openjdk.java.net/projects/jdk/12/) was defined by [JSR 386](https://www.jcp.org/en/jsr/detail?id=386) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | March 2019     |
| End of life | September 2019 |

### New Features

| JEP                                          | Description                                                                                                                                                                 |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [JEP 189](https://openjdk.java.net/jeps/189) | [Shenandoah: A Low-Pause-Time Garbage Collector (Experimental)](Java%2012/JEP%20189%20-%20Shenandoah%3A%20A%20Low-Pause-Time%20Garbage%20Collector%20%28Experimental%29.md) |
| [JEP 230](https://openjdk.java.net/jeps/230) | [Microbenchmark Suite](Java%2012/JEP%20230%20-%20Microbenchmark%20Suite.md)                                                                                                 |
| [JEP 325](https://openjdk.java.net/jeps/325) | [Switch Expressions (Preview)](Java%2012/JEP%20325%20-%20Switch%20Expressions%20%28Preview%29.md)                                                                           |
| [JEP 334](https://openjdk.java.net/jeps/334) | [JVM Constants API](Java%2012/JEP%20334%20-%20JVM%20Constants%20API.md)                                                                                                     |
| [JEP 340](https://openjdk.java.net/jeps/340) | [One AArch64 Port, Not Two](Java%2012/JEP%20340%20-%20One%20AArch64%20Port%2C%20Not%20Two.md)                                                                               |
| [JEP 341](https://openjdk.java.net/jeps/341) | [Default CDS Archives](Java%2012/JEP%20341%20-%20Default%20CDS%20Archives.md)                                                                                               |
| [JEP 344](https://openjdk.java.net/jeps/344) | [Abortable Mixed Collections for G1](Java%2012/JEP%20344%20-%20Abortable%20Mixed%20Collections%20for%20G1.md)                                                               |
| [JEP 346](https://openjdk.java.net/jeps/346) | [Promptly Return Unused Committed Memory from G1](Java%2012/JEP%20346%20-%20Promptly%20Return%20Unused%20Committed%20Memory%20from%20G1.md)                                 |

## Java 13 (non-LTS)

The [Java SE 13 Platform](https://openjdk.java.net/projects/jdk/13/) was defined by [JSR 388](https://www.jcp.org/en/jsr/detail?id=388) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | September 2019 |
| End of life | March 2020     |

### New Features

| JEP                                          | Description                                                                                                 |
| -------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| [JEP 350](https://openjdk.java.net/jeps/350) | [Dynamic CDS Archives](Java%2013/JEP%20350%20-%20Dynamic%20CDS%20Archives.md)                               |
| [JEP 351](https://openjdk.java.net/jeps/351) | [ZGC: Uncommit Unused Memory](Java%2013/JEP%20351%20-%20ZGC%3A%20Uncommit%20Unused%20Memory.md)             |
| [JEP 353](https://openjdk.java.net/jeps/353) | [Reimplement the Legacy Socket API](Java%2013/JEP%20353%20-%20Reimplement%20the%20Legacy%20Socket%20API.md) |
| [JEP 354](https://openjdk.java.net/jeps/354) | [Switch Expressions (Preview)](Java%2013/JEP%20354%20-%20Switch%20Expressions%20%28Preview%29.md)           |
| [JEP 355](https://openjdk.java.net/jeps/355) | [Text Blocks (Preview)](Java%2013/JEP%20355%20-%20Text%20Blocks%20%28Preview%29.md)                         |

## Java 14 (non-LTS)

The [Java SE 14 Platform](https://openjdk.java.net/projects/jdk/14/) was defined by [JSR 388](https://www.jcp.org/en/jsr/detail?id=388) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | March 2020     |
| End of life | September 2020 |

### New Features

| JEP                                          | Description                                                                                                                                                         |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [JEP 305](https://openjdk.java.net/jeps/305) | [Pattern Matching for instanceof (Preview)](Java%2014/JEP%20305%20-%20Pattern%20Matching%20for%20instanceof%20%28Preview%29.md)                                     |
| [JEP 343](https://openjdk.java.net/jeps/343) | [Packaging Tool (Incubator)](Java%2014/JEP%20343%20-%20Packaging%20Tool%20%28Incubator%29.md)                                                                       |
| [JEP 345](https://openjdk.java.net/jeps/345) | [NUMA-Aware Memory Allocation for G1](Java%2014/JEP%20345%20-%20NUMA-Aware%20Memory%20Allocation%20for%20G1.md)                                                     |
| [JEP 349](https://openjdk.java.net/jeps/349) | [JFR Event Streaming](Java%2014/JEP%20349%20-%20JFR%20Event%20Streaming.md)                                                                                         |
| [JEP 352](https://openjdk.java.net/jeps/352) | [Non-Volatile Mapped Byte Buffers](Java%2014/JEP%20352%20-%20Non-Volatile%20Mapped%20Byte%20Buffers.md)                                                             |
| [JEP 358](https://openjdk.java.net/jeps/358) | [Helpful NullPointerExceptions](Java%2014/JEP%20358%20-%20Helpful%20NullPointerExceptions.md)                                                                       |
| [JEP 359](https://openjdk.java.net/jeps/359) | [Records (Preview)](Java%2014/JEP%20359%20-%20Records%20%28Preview%29.md)                                                                                           |
| [JEP 361](https://openjdk.java.net/jeps/361) | [Switch Expressions (Standard)](Java%2014/JEP%20361%20-%20Switch%20Expressions%20%28Standard%29.md)                                                                 |
| [JEP 362](https://openjdk.java.net/jeps/362) | [Deprecate the Solaris and SPARC Ports](Java%2014/JEP%20362%20-%20Deprecate%20the%20Solaris%20and%20SPARC%20Ports.md)                                               |
| [JEP 363](https://openjdk.java.net/jeps/363) | [Remove the Concurrent Mark Sweep (CMS) Garbage Collector](Java%2014/JEP%20363%20-%20Remove%20the%20Concurrent%20Mark%20Sweep%20%28CMS%29%20Garbage%20Collector.md) |
| [JEP 364](https://openjdk.java.net/jeps/364) | [ZGC on macOS](Java%2014/JEP%20364%20-%20ZGC%20on%20macOS.md)                                                                                                       |
| [JEP 365](https://openjdk.java.net/jeps/365) | [ZGC on Windows](Java%2014/JEP%20365%20-%20ZGC%20on%20Windows,md)                                                                                                   |
| [JEP 366](https://openjdk.java.net/jeps/366) | [Deprecate the ParallelScavenge + SerialOld GC Combination](Java%2014/JEP%20366%20-%20Deprecate%20the%20ParallelScavenge%20%2B%20SerialOld%20GC%20Combination.md)   |
| [JEP 367](https://openjdk.java.net/jeps/367) | [Remove the Pack200 Tools and API](Java%2014/JEP%20367%20-%20Remove%20the%20Pack200%20Tools%20and%20API.md)                                                         |
| [JEP 368](https://openjdk.java.net/jeps/368) | [Text Blocks (Second Preview)](Java%2014/JEP%20368%20-%20Text%20Blocks%20%28Second%20Preview%29.md)                                                                 |
| [JEP 370](https://openjdk.java.net/jeps/370) | [Foreign-Memory Access API (Incubator)](Java%2014/JEP%20370%20-%20Foreign-Memory%20Access%20API%20%28Incubator%29.md)                                               |

## Java 15 (non-LTS)

The [Java SE 15 Platform](https://openjdk.java.net/projects/jdk/15/) was defined by [JSR 390](https://www.jcp.org/en/jsr/detail?id=390) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | September 2020 |
| End of life | March 2021     |

### New Features

| JEP                                          | Description                                                                                                                                     |
| -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [JEP 339](https://openjdk.java.net/jeps/339) | [Edwards-Curve Digital Signature Algorithm (EdDSA)](Java%2015/JEP%20339%20-%20Edwards-Curve%20Digital%20Signature%20Algorithm%20%28EdDSA%29.md) |
| [JEP 360](https://openjdk.java.net/jeps/360) | [Sealed Classes (Preview)](Java%2015/JEP%20360%20-%20Sealed%20Classes%20%28Preview%29.md)                                                       |
| [JEP 371](https://openjdk.java.net/jeps/371) | [Hidden Classes](Java%2015/JEP%20371%20-%20Hidden%20Classes.md)                                                                                 |
| [JEP 372](https://openjdk.java.net/jeps/372) | [Remove the Nashorn JavaScript Engine](Java%2015/JEP%20372%20-%20Remove%20the%20Nashorn%20JavaScript%20Engine.md)                               |
| [JEP 373](https://openjdk.java.net/jeps/373) | [Reimplement the Legacy DatagramSocket API](Java%2015/JEP%20373%20-%20Reimplement%20the%20Legacy%20DatagramSocket%20API.md)                     |
| [JEP 374](https://openjdk.java.net/jeps/374) | [Disable and Deprecate Biased Locking](Java%2015/JEP%20374%20-%20Disable%20and%20Deprecate%20Biased%20Locking.md)                               |
| [JEP 375](https://openjdk.java.net/jeps/375) | [Pattern Matching for instanceof (Second Preview)](Java%2015/JEP%20375%20-%20Pattern%20Matching%20for%20instanceof%20%28Second%20Preview%29.md) |
| [JEP 377](https://openjdk.java.net/jeps/377) | [ZGC: A Scalable Low-Latency Garbage Collector](Java%2015/JEP%20377%20-%20ZGC%3A%20A%20Scalable%20Low-Latency%20Garbage%20Collector.md)         |
| [JEP 378](https://openjdk.java.net/jeps/378) | [Text Blocks](Java%2015/JEP%20378%20-%20Text%20Blocks.md)                                                                                       |
| [JEP 379](https://openjdk.java.net/jeps/379) | [Shenandoah: A Low-Pause-Time Garbage Collector](Java%2015/JEP%20379%20-%20Shenandoah%3A%20A%20Low-Pause-Time%20Garbage%20Collector.md)         |
| [JEP 381](https://openjdk.java.net/jeps/381) | [Remove the Solaris and SPARC Ports](Java%2015/JEP%20381%20-%20Remove%20the%20Solaris%20and%20SPARC%20Ports.md)                                 |
| [JEP 383](https://openjdk.java.net/jeps/383) | [Foreign-Memory Access API (Second Incubator)](Java%2015/JEP%20383%20-%20Foreign-Memory%20Access%20API%20%28Second%20Incubator%29.md)           |
| [JEP 384](https://openjdk.java.net/jeps/384) | [Records (Second Preview)](Java%2015/JEP%20384%20-%20Records%20%28Second%20Preview%29.md)                                                       |
| [JEP 385](https://openjdk.java.net/jeps/385) | [Deprecate RMI Activation for Removal](Java%2015/JEP%20385%20-%20Deprecate%20RMI%20Activation%20for%20Removal.md)                               |
