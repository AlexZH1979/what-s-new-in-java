# What's new in Java

| Java                        | Status                                                    |
| --------------------------- | --------------------------------------------------------- |
| [Java 8](#java-8-lts)       | **Supportd until March 2022**                             |
| [Java 9](#java-9-non-lts)   | Not Supported, switch to [Java 11](#java-11-lts)          |
| [Java 10](#java-10-non-lts) | Not Supported, switch to [Java 11](#java-11-lts)          |
| [Java 11](#java-11-lts)     | **Supported until September 2023**                        |
| [Java 12](#java-12-non-lts) | Not Supported, switch to [Java 14](#java-14-non-lts)      |
| [Java 13](#java-13-non-lts) | Not Supported, switch to [Java 14](#java-14-non-lts)      |
| [Java 14](#java-14-non-lts) | **Current Latest Relase, supportd until Septemnber 2020** |
| [Java 15](#java-15-non-lts) | Preview                                                   |

## Java 8 (LTS)

The [Java SE 8 Platform](https://openjdk.java.net/projects/jdk8/) was defined by [JSR 337](https://www.jcp.org/en/jsr/detail?id=337) in the Java Community Process.

|             | Dates      |
| ----------- | ---------- |
| Released On | March 2014 |
| End of life | March 2022 |

### New Features

--/-- 126 Lambda Expressions & Virtual Extension Methods
138 Autoconf-Based Build System
160 Lambda-Form Representation for Method Handles
161 Compact Profiles
162 Prepare for Modularization
164 Leverage CPU Instructions for AES Cryptography
174 Nashorn JavaScript Engine
176 Mechanical Checking of Caller-Sensitive Methods
179 Document JDK API Support and Stability
vm/-- 142 Reduce Cache Contention on Specified Fields
vm/gc 122 Remove the Permanent Generation
173 Retire Some Rarely-Used GC Combinations
vm/rt 136 Enhanced Verification Errors
147 Reduce Class Metadata Footprint
148 Small VM
171 Fence Intrinsics
core/-- 153 Launch JavaFX Applications
core/lang 101 Generalized Target-Type Inference
104 Annotations on Java Types
105 DocTree API
106 Add Javadoc to javax.tools
117 Remove the Annotation-Processing Tool (apt)
118 Access to Parameter Names at Runtime
120 Repeating Annotations
139 Enhance javac to Improve Build Speed
172 DocLint
core/libs 103 Parallel Array Sorting
107 Bulk Data Operations for Collections
109 Enhance Core Libraries with Lambda
112 Charset Implementation Improvements
119 javax.lang.model Implementation Backed by Core Reflection
135 Base64 Encoding & Decoding
149 Reduce Core-Library Memory Usage
150 Date & Time API
155 Concurrency Updates
170 JDBC 4.2
177 Optimize java.text.DecimalFormat.format
178 Statically-Linked JNI Libraries
180 Handle Frequent HashMap Collisions with Balanced Trees
core/i18n 127 Improve Locale Data Packaging and Adopt Unicode CLDR Data
128 BCP 47 Locale Matching
133 Unicode 6.2
core/net 184 HTTP URL Permissions
core/sec 113 MS-SFU Kerberos 5 Extensions
114 TLS Server Name Indication (SNI) Extension
115 AEAD CipherSuites
121 Stronger Algorithms for Password-Based Encryption
123 Configurable Secure Random-Number Generation
124 Enhance the Certificate Revocation-Checking API
129 NSA Suite B Cryptographic Algorithms
130 SHA-224 Message Digests
131 PKCS#11 Crypto Provider for 64-bit Windows
140 Limited doPrivileged
166 Overhaul JKS-JCEKS-PKCS12 Keystores
web/jaxp 185 Restrict Fetching of External XML Resources

## Java 9 (non-LTS)

The [Java SE 9 Platform](https://openjdk.java.net/projects/jdk9/) was defined by [JSR 379](https://www.jcp.org/en/jsr/detail?id=379) in the Java Community Process.

|             | Dates          |
| ----------- | -------------- |
| Released On | September 2017 |
| End of life | March 2018     |

### New Features

| JEP                                          | Description                                                                                                                                                              |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [JEP 102](https://openjdk.java.net/jeps/102) | [Process API Updates](Java%209/JEP%20102%20-%20Process%20API%20Updates.md)                                                                                               |
| [JEP 110](https://openjdk.java.net/jeps/110) | [HTTP 2 Client](Java%209/JEP%20110%20-%20HTTP%202%20Client.md)                                                                                                           |
| [JEP 143](https://openjdk.java.net/jeps/143) | [Improve Contended Locking](Java%209/JEP%20143%20-%20Improve%20Contended%20Locking.md)                                                                                   |
| [JEP 158](https://openjdk.java.net/jeps/158) | [Unified JVM Logging](Java%209/JEP%20158%20-%20Unified%20JVM%20Logging.md)                                                                                               |
| [JEP 165](https://openjdk.java.net/jeps/165) | [Compiler Control](Java%209/JEP%20165%20-%20Compiler%20Control.md)                                                                                                       |
| [JEP 193](https://openjdk.java.net/jeps/193) | [Variable Handles](Java%209/JEP%20193%20-%20Variable%20Handles.md)                                                                                                       |
| [JEP 197](https://openjdk.java.net/jeps/197) | [Segmented Code Cache](Java%209/JEP%20197%20-%20Segmented%20Code%20Cache.md)                                                                                             |
| [JEP 199](https://openjdk.java.net/jeps/199) | [Smart Java Compilation, Phase Two](Java%209/JEP%20199%20-%20Smart%20Java%20Compilation,%20Phase%20Two.md)                                                               |
| [JEP 200](https://openjdk.java.net/jeps/200) | [The Modular JDK](Java%209/JEP%20200%20-%20The%20Modular%20JDK.md)                                                                                                       |
| [JEP 201](https://openjdk.java.net/jeps/201) | [Modular Source Code](Java%209/JEP%20201%20-%20Modular%20Source%20Code.md)                                                                                               |
| [JEP 211](https://openjdk.java.net/jeps/211) | [Elide Deprecation Warnings on Import Statements](Java%209/JEP%20211%20-%20Elide%20Deprecation%20Warnings%20on%20Import%20Statements.md)                                 |
| [JEP 212](https://openjdk.java.net/jeps/212) | [Resolve Lint and Doclint Warnings](Java%209/JEP%20212%20-%20Resolve%20Lint%20and%20Doclint%20Warnings.md)                                                               |
| [JEP 213](https://openjdk.java.net/jeps/213) | [Milling Project Coin](Java%209/JEP%20213%20-%20Milling%20Project%20Coin.md)                                                                                             |
| [JEP 214](https://openjdk.java.net/jeps/214) | [Remove GC Combinations Deprecated in JDK 8](Java%209/JEP%20214%20-%20Remove%20GC%20Combinations%20Deprecated%20in%20JDK%208.md)                                         |
| [JEP 215](https://openjdk.java.net/jeps/215) | [Tiered Attribution for javac](Java%209/JEP%20215%20-%20Tiered%20Attribution%20for%20javac.md)                                                                           |
| [JEP 216](https://openjdk.java.net/jeps/216) | [Process Import Statements Correctly](Java%209/JEP%20216%20-%20Process%20Import%20Statements%20Correctly.md)                                                             |
| [JEP 217](https://openjdk.java.net/jeps/217) | [Annotations Pipeline 2.0](Java%209/JEP%20217%20-%20Annotations%20Pipeline%202.0.md)                                                                                     |
| [JEP 219](https://openjdk.java.net/jeps/219) | [Datagram Transport Layer Security (DTLS)](Java%209/JEP%20219%20-%20Datagram%20Transport%20Layer%20Security%20%28DTLS%29.md)                                             |
| [JEP 220](https://openjdk.java.net/jeps/220) | [Modular Run-Time Images](Java%209/JEP%20220%20-%20Modular%20Run-Time%20Images.md)                                                                                       |
| [JEP 221](https://openjdk.java.net/jeps/221) | [Simplified Doclet API](Java%209/JEP%20221%20-%20Simplified%20Doclet%20API.md)                                                                                           |
| [JEP 222](https://openjdk.java.net/jeps/222) | [jshell: The Java Shell (Read-Eval-Print Loop)](Java%209/JEP%20222%20-%20jshell%3A%20The%20Java%20Shell%20%28Read-Eval-Print%20Loop%29.md)                               |
| [JEP 223](https://openjdk.java.net/jeps/223) | [New Version-String Scheme](Java%209/JEP%20223%20-%20New%20Version-String%20Scheme.md)                                                                                   |
| [JEP 224](https://openjdk.java.net/jeps/224) | [HTML5 Javadoc](Java%209/JEP%20224%20-%20HTML5%20Javadoc.md)                                                                                                             |
| [JEP 225](https://openjdk.java.net/jeps/225) | [Javadoc Search](Java%209/JEP%20225%20-%20Javadoc%20Search.md)                                                                                                           |
| [JEP 226](https://openjdk.java.net/jeps/226) | [UTF-8 Property Files](Java%209/JEP%20226%20-%20UTF-8%20Property%20Files.md)                                                                                             |
| [JEP 227](https://openjdk.java.net/jeps/227) | [Unicode 7.0](Java%209/JEP%20227%20-%20Unicode%207.0.md)                                                                                                                 |
| [JEP 228](https://openjdk.java.net/jeps/228) | [Add More Diagnostic Commands](Java%209/JEP%20228%20-%20Add%20More%20Diagnostic%20Commands.md)                                                                           |
| [JEP 229](https://openjdk.java.net/jeps/229) | [Create PKCS12 Keystores by Default](Java%209/JEP%20229%20-%20Create%20PKCS12%20Keystores%20by%20Default.md)                                                             |
| [JEP 231](https://openjdk.java.net/jeps/231) | [Remove Launch-Time JRE Version Selection](Java%209/JEP%20231%20-%20Remove%20Launch-Time%20JRE%20Version%20Selection.md)                                                 |
| [JEP 232](https://openjdk.java.net/jeps/232) | [Improve Secure Application Performance](Java%209/JEP%20232%20-%20Improve%20Secure%20Application%20Performance.md)                                                       |
| [JEP 233](https://openjdk.java.net/jeps/233) | [Generate Run-Time Compiler Tests Automatically](Java%209/JEP%20233%20-%20Generate%20Run-Time%20Compiler%20Tests%20Automatically.md)                                     |
| [JEP 235](https://openjdk.java.net/jeps/235) | [Test Class-File Attributes Generated by javac](Java%209/JEP%20235%20-%20Test%20Class-File%20Attributes%20Generated%20by%20javac.md)                                     |
| [JEP 236](https://openjdk.java.net/jeps/236) | [Parser API for Nashorn](Java%209/JEP%20236%20-%20Parser%20API%20for%20Nashorn.md)                                                                                       |
| [JEP 237](https://openjdk.java.net/jeps/237) | [Linux/AArch64 Port](Java%209/JEP%20237%20-%20Linux/AArch64%20Port.md)                                                                                                   |
| [JEP 238](https://openjdk.java.net/jeps/238) | [Multi-Release JAR Files](Java%209/JEP%20238%20-%20Multi-Release%20JAR%20Files.md)                                                                                       |
| [JEP 240](https://openjdk.java.net/jeps/240) | [Remove the JVM TI hprof Agent](Java%209/JEP%20240%20-%20Remove%20the%20JVM%20TI%20hprof%20Agent.md)                                                                     |
| [JEP 241](https://openjdk.java.net/jeps/241) | [Remove the jhat Tool](Java%209/JEP%20241%20-%20Remove%20the%20jhat%20Tool.md)                                                                                           |
| [JEP 243](https://openjdk.java.net/jeps/243) | [Java-Level JVM Compiler Interface](Java%209/JEP%20243%20-%20Java-Level%20JVM%20Compiler%20Interface.md)                                                                 |
| [JEP 244](https://openjdk.java.net/jeps/244) | [TLS Application-Layer Protocol Negotiation Extension](Java%209/JEP%20244%20-%20TLS%20Application-Layer%20Protocol%20Negotiation%20Extension.md)                         |
| [JEP 245](https://openjdk.java.net/jeps/245) | [Validate JVM Command-Line Flag Arguments](Java%209/JEP%20245%20-%20Validate%20JVM%20Command-Line%20Flag%20Arguments.md)                                                 |
| [JEP 246](https://openjdk.java.net/jeps/246) | [Leverage CPU Instructions for GHASH and RSA](Java%209/JEP%20246%20-%20Leverage%20CPU%20Instructions%20for%20GHASH%20and%20RSA.md)                                       |
| [JEP 247](https://openjdk.java.net/jeps/247) | [Compile for Older Platform Versions](Java%209/JEP%20247%20-%20Compile%20for%20Older%20Platform%20Versions.md)                                                           |
| [JEP 248](https://openjdk.java.net/jeps/248) | [Make G1 the Default Garbage Collector](Java%209/JEP%20248%20-%20Make%20G1%20the%20Default%20Garbage%20Collector.md)                                                     |
| [JEP 249](https://openjdk.java.net/jeps/249) | [OCSP Stapling for TLS](Java%209/JEP%20249%20-%20OCSP%20Stapling%20for%20TLS.md)                                                                                         |
| [JEP 250](https://openjdk.java.net/jeps/250) | [Store Interned Strings in CDS Archives](Java%209/JEP%20250%20-%20Store%20Interned%20Strings%20in%20CDS%20Archives.md)                                                   |
| [JEP 251](https://openjdk.java.net/jeps/251) | [Multi-Resolution Images](Java%209/JEP%20251%20-%20Multi-Resolution%20Images.md)                                                                                         |
| [JEP 252](https://openjdk.java.net/jeps/252) | [Use CLDR Locale Data by Default](Java%209/JEP%20252%20-%20Use%20CLDR%20Locale%20Data%20by%20Default.md)                                                                 |
| [JEP 253](https://openjdk.java.net/jeps/253) | [Prepare JavaFX UI Controls & CSS APIs for Modularization](Java%209/JEP%20253%20-%20Prepare%20JavaFX%20UI%20Controls%20&%20CSS%20APIs%20for%20Modularization.md)         |
| [JEP 254](https://openjdk.java.net/jeps/254) | [Compact Strings](Java%209/JEP%20254%20-%20Compact%20Strings.md)                                                                                                         |
| [JEP 255](https://openjdk.java.net/jeps/255) | [Merge Selected Xerces 2.11.0 Updates into JAXP](Java%209/JEP%20255%20-%20Merge%20Selected%20Xerces%202.11.0%20Updates%20into%20JAXP.md)                                 |
| [JEP 256](https://openjdk.java.net/jeps/256) | [BeanInfo Annotations](Java%209/JEP%20256%20-%20BeanInfo%20Annotations.md)                                                                                               |
| [JEP 257](https://openjdk.java.net/jeps/257) | [Update JavaFX/Media to Newer Version of GStreamer](Java%209/JEP%20257%20-%20Update%20JavaFX/Media%20to%20Newer%20Version%20of%20GStreamer.md)                           |
| [JEP 258](https://openjdk.java.net/jeps/258) | [HarfBuzz Font-Layout Engine](Java%209/JEP%20258%20-%20HarfBuzz%20Font-Layout%20Engine.md)                                                                               |
| [JEP 259](https://openjdk.java.net/jeps/259) | [Stack-Walking API](Java%209/JEP%20259%20-%20Stack-Walking%20API.md)                                                                                                     |
| [JEP 260](https://openjdk.java.net/jeps/260) | [Encapsulate Most Internal APIs](Java%209/JEP%20260%20-%20Encapsulate%20Most%20Internal%20APIs.md)                                                                       |
| [JEP 261](https://openjdk.java.net/jeps/261) | [Module System](Java%209/JEP%20261%20-%20Module%20System.md)                                                                                                             |
| [JEP 262](https://openjdk.java.net/jeps/262) | [TIFF Image I/O](Java%209/JEP%20262%20-%20TIFF%20Image%20I/O.md)                                                                                                         |
| [JEP 263](https://openjdk.java.net/jeps/263) | [HiDPI Graphics on Windows and Linux](Java%209/JEP%20263%20-%20HiDPI%20Graphics%20on%20Windows%20and%20Linux.md)                                                         |
| [JEP 264](https://openjdk.java.net/jeps/264) | [Platform Logging API and Service](Java%209/JEP%20264%20-%20Platform%20Logging%20API%20and%20Service.md)                                                                 |
| [JEP 265](https://openjdk.java.net/jeps/265) | [Marlin Graphics Renderer](Java%209/JEP%20265%20-%20Marlin%20Graphics%20Renderer.md)                                                                                     |
| [JEP 266](https://openjdk.java.net/jeps/266) | [More Concurrency Updates](Java%209/JEP%20266%20-%20More%20Concurrency%20Updates.md)                                                                                     |
| [JEP 267](https://openjdk.java.net/jeps/267) | [Unicode 8.0](Java%209/JEP%20267%20-%20Unicode%208.0.md)                                                                                                                 |
| [JEP 268](https://openjdk.java.net/jeps/268) | [XML Catalogs](Java%209/JEP%20268%20-%20XML%20Catalogs.md)                                                                                                               |
| [JEP 269](https://openjdk.java.net/jeps/269) | [Convenience Factory Methods for Collections](Java%209/JEP%20269%20-%20Convenience%20Factory%20Methods%20for%20Collections.md)                                           |
| [JEP 270](https://openjdk.java.net/jeps/270) | [Reserved Stack Areas for Critical Sections](Java%209/JEP%20270%20-%20Reserved%20Stack%20Areas%20for%20Critical%20Sections.md)                                           |
| [JEP 271](https://openjdk.java.net/jeps/271) | [Unified GC Logging](Java%209/JEP%20271%20-%20Unified%20GC%20Logging.md)                                                                                                 |
| [JEP 272](https://openjdk.java.net/jeps/272) | [Platform-Specific Desktop Features](Java%209/JEP%20272%20-%20Platform-Specific%20Desktop%20Features.md)                                                                 |
| [JEP 273](https://openjdk.java.net/jeps/273) | [DRBG-Based SecureRandom Implementations](Java%209/JEP%20273%20-%20DRBG-Based%20SecureRandom%20Implementations.md)                                                       |
| [JEP 274](https://openjdk.java.net/jeps/274) | [Enhanced Method Handles](Java%209/JEP%20274%20-%20Enhanced%20Method%20Handles.md)                                                                                       |
| [JEP 275](https://openjdk.java.net/jeps/275) | [Modular Java Application Packaging](Java%209/JEP%20275%20-%20Modular%20Java%20Application%20Packaging.md)                                                               |
| [JEP 276](https://openjdk.java.net/jeps/276) | [Dynamic Linking of Language-Defined Object Models](Java%209/JEP%20276%20-%20Dynamic%20Linking%20of%20Language-Defined%20Object%20Models.md)                             |
| [JEP 277](https://openjdk.java.net/jeps/277) | [Enhanced Deprecation](Java%209/JEP%20277%20-%20Enhanced%20Deprecation.md)                                                                                               |
| [JEP 278](https://openjdk.java.net/jeps/278) | [Additional Tests for Humongous Objects in G1](Java%209/JEP%20278%20-%20Additional%20Tests%20for%20Humongous%20Objects%20in%20G1.md)                                     |
| [JEP 279](https://openjdk.java.net/jeps/279) | [Improve Test-Failure Troubleshooting](Java%209/JEP%20279%20-%20Improve%20Test-Failure%20Troubleshooting.md)                                                             |
| [JEP 280](https://openjdk.java.net/jeps/280) | [Indify String Concatenation](Java%209/JEP%20280%20-%20Indify%20String%20Concatenation.md)                                                                               |
| [JEP 281](https://openjdk.java.net/jeps/281) | [HotSpot C++ Unit-Test Framework](Java%209/JEP%20281%20-%20HotSpot%20C++%20Unit-Test%20Framework.md)                                                                     |
| [JEP 282](https://openjdk.java.net/jeps/282) | [jlink: The Java Linker](Java%209/JEP%20282%20-%20jlink%3A%20The%20Java%20Linker.md)                                                                                     |
| [JEP 283](https://openjdk.java.net/jeps/283) | [Enable GTK 3 on Linux](Java%209/JEP%20283%20-%20Enable%20GTK%203%20on%20Linux.md)                                                                                       |
| [JEP 284](https://openjdk.java.net/jeps/284) | [New HotSpot Build System](Java%209/JEP%20284%20-%20New%20HotSpot%20Build%20System.md)                                                                                   |
| [JEP 285](https://openjdk.java.net/jeps/285) | [Spin-Wait Hints](Java%209/JEP%20285%20-%20Spin-Wait%20Hints.md)                                                                                                         |
| [JEP 287](https://openjdk.java.net/jeps/287) | [SHA-3 Hash Algorithms](Java%209/JEP%20287%20-%20SHA-3%20Hash%20Algorithms.md)                                                                                           |
| [JEP 288](https://openjdk.java.net/jeps/288) | [Disable SHA-1 Certificates](Java%209/JEP%20288%20-%20Disable%20SHA-1%20Certificates.md)                                                                                 |
| [JEP 289](https://openjdk.java.net/jeps/289) | [Deprecate the Applet API](Java%209/JEP%20289%20-%20Deprecate%20the%20Applet%20API.md)                                                                                   |
| [JEP 290](https://openjdk.java.net/jeps/290) | [Filter Incoming Serialization Data](Java%209/JEP%20290%20-%20Filter%20Incoming%20Serialization%20Data.md)                                                               |
| [JEP 291](https://openjdk.java.net/jeps/291) | [Deprecate the Concurrent Mark Sweep (CMS) Garbage Collector](Java%209/JEP%20291%20-%20Deprecate%20the%20Concurrent%20Mark%20Sweep%20%28CMS%29%20Garbage%20Collector.md) |
| [JEP 292](https://openjdk.java.net/jeps/292) | [Implement Selected ECMAScript 6 Features in Nashorn](Java%209/JEP%20292%20-%20Implement%20Selected%20ECMAScript%206%20Features%20in%20Nashorn.md)                       |
| [JEP 294](https://openjdk.java.net/jeps/294) | [Linux/s390x Port](Java%209/JEP%20294%20-%20Linux/s390x%20Port.md)                                                                                                       |
| [JEP 295](https://openjdk.java.net/jeps/295) | [Ahead-of-Time Compilation](Java%209/JEP%20295%20-%20Ahead-of-Time%20Compilation.md)                                                                                     |
| [JEP 297](https://openjdk.java.net/jeps/297) | [Unified arm32/arm64 Port](Java%209/JEP%20297%20-%20Unified%20arm32-arm64%20Port.md)                                                                                     |
| [JEP 298](https://openjdk.java.net/jeps/298) | [Remove Demos and Samples](Java%209/JEP%20298%20-%20Remove%20Demos%20and%20Samples.md)                                                                                   |
| [JEP 299](https://openjdk.java.net/jeps/299) | [Reorganize Documentation](Java%209/JEP%20299%20-%20Reorganize%20Documentation.md)                                                                                       |

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
