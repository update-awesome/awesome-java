# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Java frameworks, libraries and software.

## Contents

- [Projects](#projects)
  - [Bean Mapping](#bean-mapping)
  - [Build](#build)
  - [Bytecode Manipulation](#bytecode-manipulation)
  - [Caching](#caching)
  - [CLI](#cli)
  - [Cluster Management](#cluster-management)
  - [Code Analysis](#code-analysis)
  - [Code Coverage](#code-coverage)
  - [Code Generators](#code-generators)
  - [Compiler-compiler](#compiler-compiler)
  - [Computer Vision](#computer-vision)
  - [Configuration](#configuration)
  - [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
  - [CSV](#csv)
  - [Data Structures](#data-structures)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [Dependency Injection](#dependency-injection)
  - [Development](#development)
  - [Distributed Applications](#distributed-applications)
  - [Distributed Transactions](#distributed-transactions)
  - [Distribution](#distribution)
  - [Document Processing](#document-processing)
  - [Financial](#financial)
  - [Formal Verification](#formal-verification)
  - [Functional Programming](#functional-programming)
  - [Game Development](#game-development)
  - [Geospatial](#geospatial)
  - [GUI](#gui)
  - [High Performance](#high-performance)
  - [HTTP Clients](#http-clients)
  - [Hypermedia Types](#hypermedia-types)
  - [IDE](#ide)
  - [Imagery](#imagery)
  - [Introspection](#introspection)
  - [Job Scheduling](#job-scheduling)
  - [JSON](#json)
  - [JVM and JDK](#jvm-and-jdk)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microservice](#microservice)
  - [Miscellaneous](#miscellaneous)
  - [Mobile Development](#mobile-development)
  - [Monitoring](#monitoring)
  - [Native](#native)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [ORM](#orm)
  - [PaaS](#paas)
  - [PDF](#pdf)
  - [Performance analysis](#performance-analysis)
  - [Platform](#platform)
  - [Processes](#processes)
  - [Reactive libraries](#reactive-libraries)
  - [REST Frameworks](#rest-frameworks)
  - [Science](#science)
  - [Search](#search)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server](#server)
  - [Template Engine](#template-engine)
  - [Testing](#testing)
  - [Utility](#utility)
  - [Version Managers](#version-managers)
  - [Web Crawling](#web-crawling)
  - [Web Frameworks](#web-frameworks)
  - [Workflow Orchestration Engines](#workflow-orchestration-engines)
- [Resources](#resources)
  - [Related Awesome Lists](#awesome-lists)
  - [Communities](#communities)
  - [Frontends](#frontends)
  - [Influential Books](#influential-books)
  - [Podcasts and Screencasts](#podcasts-and-screencasts)
  - [People](#people)
  - [Websites](#websites)

## Projects

### Bean Mapping

_Frameworks that ease bean mapping._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> ![](https://img.shields.io/github/last-commit/doov-io/doov) [dOOv](https://github.com/doov-io/doov) - Provides fluent API for typesafe domain model validation and mapping. It uses annotations, code generation and a type safe DSL to make bean validation and mapping fast and easy.
- <code>&nbsp;&nbsp;&nbsp;190</code> ![](https://img.shields.io/github/last-commit/jmapper-framework/jmapper-core) [JMapper](https://github.com/jmapper-framework/jmapper-core) - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.
- <code>&nbsp;&nbsp;5100</code> ![](https://img.shields.io/github/last-commit/mapstruct/mapstruct) [MapStruct](https://github.com/mapstruct/mapstruct) - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.
- <code>&nbsp;&nbsp;1971</code> ![](https://img.shields.io/github/last-commit/modelmapper/modelmapper) [ModelMapper](https://github.com/modelmapper/modelmapper) - Intelligent object mapping library that automatically maps objects to each other.
- <code>&nbsp;&nbsp;1156</code> ![](https://img.shields.io/github/last-commit/orika-mapper/orika) [Orika](https://github.com/orika-mapper/orika) - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;94</code> ![](https://img.shields.io/github/last-commit/remondis-it/remap) [reMap](https://github.com/remondis-it/remap) - Lambda and method handle-based mapping which requires code and not annotations if objects have different names.
- <code>&nbsp;&nbsp;&nbsp;208</code> ![](https://img.shields.io/github/last-commit/xebia-france/selma) [Selma](https://github.com/xebia-france/selma) - Annotation processor-based bean mapper.

### Build

_Tools that handle the build cycle and dependencies of an application._

- [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
- [Bazel](https://bazel.build) - Tool from Google that builds code quickly and reliably.
- <code>&nbsp;&nbsp;8245</code> ![](https://img.shields.io/github/last-commit/facebook/buck) [Buck](https://github.com/facebook/buck) - Encourages the creation of small, reusable modules consisting of code and resources.
- [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

_Libraries to manipulate bytecode programmatically._

- [ASM](https://asm.ow2.io) - All-purpose, low-level bytecode manipulation and analysis.
- [Byte Buddy](https://bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
- <code>&nbsp;12896</code> ![](https://img.shields.io/github/last-commit/Konloch/bytecode-viewer) [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) - Java 8 Jar & Android APK reverse engineering suite. (GPL-3.0-only)
- [Byteman](https://byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting. (LGPL-2.1-or-later)
- <code>&nbsp;&nbsp;4336</code> ![](https://img.shields.io/github/last-commit/cglib/cglib) [cglib](https://github.com/cglib/cglib) - Bytecode generation library.
- <code>&nbsp;&nbsp;3482</code> ![](https://img.shields.io/github/last-commit/jboss-javassist/javassist) [Javassist](https://github.com/jboss-javassist/javassist) - Tries to simplify bytecode editing.
- <code>&nbsp;&nbsp;&nbsp;844</code> ![](https://img.shields.io/github/last-commit/SpongePowered/Mixin) [Mixin](https://github.com/SpongePowered/Mixin) - Manipulate bytecode at runtime using real Java code.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;57</code> ![](https://img.shields.io/github/last-commit/nicolasmanic/perses) [Perses](https://github.com/nicolasmanic/perses) - Dynamically injects failure/latency at the bytecode level according to principles of chaos engineering.

### Caching

_Libraries that provide caching facilities._

- [cache2k](https://cache2k.org) - In-memory high performance caching library.
- <code>&nbsp;11425</code> ![](https://img.shields.io/github/last-commit/ben-manes/caffeine) [Caffeine](https://github.com/ben-manes/caffeine) - High-performance, near-optimal caching library.
- [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
- [Infinispan](https://infinispan.org) - Highly concurrent key/value datastore used for caching.

### CLI

_Libraries for everything related to the CLI._

- <code>&nbsp;&nbsp;&nbsp;378</code> ![](https://img.shields.io/github/last-commit/vdmeer/asciitable) [ASCII Table](https://github.com/vdmeer/asciitable) - Library to draw tables in ASCII.
- <code>&nbsp;&nbsp;&nbsp;848</code> ![](https://img.shields.io/github/last-commit/airlift/airline) [Airline](https://github.com/airlift/airline) - Annotation-based framework for parsing Git-like command-line arguments.
- [args4j](http://args4j.kohsuke.org) - Small library to parse command-line arguments.
- <code>&nbsp;&nbsp;&nbsp;890</code> ![](https://img.shields.io/github/last-commit/fusesource/jansi) [Jansi](https://github.com/fusesource/jansi) - ANSI escape codes to format console output.
- <code>&nbsp;&nbsp;&nbsp;133</code> ![](https://img.shields.io/github/last-commit/indvd00m/java-ascii-render) [Java ASCII Render](https://github.com/indvd00m/java-ascii-render) - Graphical primitives for the console.
- [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/jbock-java/jbock) [jbock](https://github.com/jbock-java/jbock) - Reflectionless command line parser.
- [Jexer](https://gitlab.com/klamonte/jexer) - Advanced console (and Swing) text user interface (TUI) library, with mouse-draggable windows, built-in terminal window manager, and sixel image support. Looks like [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).
- <code>&nbsp;&nbsp;1043</code> ![](https://img.shields.io/github/last-commit/jline/jline3) [JLine](https://github.com/jline/jline3) - Includes features from modern shells like completion or history.
- [JOpt Simple](https://jopt-simple.github.io/jopt-simple/) - Fluent parser that uses the POSIX#getopt and GNU#getopt_long syntaxes.
- [picocli](https://picocli.info) - ANSI colors and styles in usage help with annotation-based POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.
- <code>&nbsp;&nbsp;&nbsp;270</code> ![](https://img.shields.io/github/last-commit/beryx/text-io) [Text-IO](https://github.com/beryx/text-io) - Aids the creation of full console-based applications.
- <code>&nbsp;&nbsp;1836</code> ![](https://img.shields.io/github/last-commit/mabe02/lanterna) [Lanterna](https://github.com/mabe02/lanterna) - Easy console text-GUI library, similar to curses. (LGPL-3.0-only)

### Cluster Management

_Frameworks that can dynamically manage applications inside of a cluster._

- [Apache Aurora](https://aurora.apache.org) - Mesos framework for long-running services and cron jobs.
- [Singularity](http://getsingularity.com) - Mesos framework that makes deployment and operations easy. It supports web services, background workers, scheduled jobs, and one-off tasks.

### Code Analysis

_Tools that provide metrics and quality measurements._

- <code>&nbsp;&nbsp;6985</code> ![](https://img.shields.io/github/last-commit/checkstyle/checkstyle) [Checkstyle](https://github.com/checkstyle/checkstyle) - Static analysis of coding conventions and standards. (LGPL-2.1-or-later)
- <code>&nbsp;&nbsp;5927</code> ![](https://img.shields.io/github/last-commit/google/error-prone) [Error Prone](https://github.com/google/error-prone) - Catches common programming mistakes as compile-time errors.
- <code>&nbsp;13209</code> ![](https://img.shields.io/github/last-commit/facebook/infer) [Infer](https://github.com/facebook/infer) - Modern static analysis tool for verifying the correctness of code.
- [jQAssistant](https://jqassistant.org) - Static code analysis with Neo4J-based query language. (GPL-3.0-only)
- <code>&nbsp;&nbsp;3094</code> ![](https://img.shields.io/github/last-commit/uber/NullAway) [NullAway](https://github.com/uber/NullAway) - Eliminates NullPointerExceptions with low build-time overhead.
- <code>&nbsp;&nbsp;3809</code> ![](https://img.shields.io/github/last-commit/pmd/pmd) [PMD](https://github.com/pmd/pmd) - Source code analysis for finding bad coding practices.
- <code>&nbsp;&nbsp;&nbsp;877</code> ![](https://img.shields.io/github/last-commit/SonarSource/sonar-java) [SonarJava](https://github.com/SonarSource/sonar-java) - Static analyzer for SonarQube & SonarLint. (LGPL-3.0-only)
- [Sourcetrail](https://www.sourcetrail.com) - Visual source code navigator.
- <code>&nbsp;&nbsp;1313</code> ![](https://img.shields.io/github/last-commit/INRIA/spoon) [Spoon](https://github.com/INRIA/spoon) - Library for analyzing and transforming Java source code.
- <code>&nbsp;&nbsp;2695</code> ![](https://img.shields.io/github/last-commit/spotbugs/spotbugs) [Spotbugs](https://github.com/spotbugs/spotbugs) - Static analysis of bytecode to find potential bugs. (LGPL-2.1-only)

### Code Coverage

_Frameworks and tools that enable code coverage metrics collection for test suites._

- [Clover](https://www.atlassian.com/software/clover) - Relies on source-code instrumentation instead of bytecode instrumentation.
- [Cobertura](https://cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only)
- [JaCoCo](https://www.eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

_Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness._

- <code>&nbsp;&nbsp;&nbsp;133</code> ![](https://img.shields.io/github/last-commit/sviperll/adt4j) [ADT4J](https://github.com/sviperll/adt4j) - JSR-269 code generator for algebraic data types.
- <code>&nbsp;&nbsp;9695</code> ![](https://img.shields.io/github/last-commit/google/auto) [Auto](https://github.com/google/auto) - Generates factory, service, and value classes.
- [Bootify ![c]](https://bootify.io) - Browser-based Spring Boot app generation with JPA model and REST API.
- <code>&nbsp;&nbsp;&nbsp;790</code> ![](https://img.shields.io/github/last-commit/inferred/FreeBuilder) [FreeBuilder](https://github.com/inferred/FreeBuilder) - Automatically generates the Builder pattern.
- <code>&nbsp;&nbsp;&nbsp;104</code> ![](https://img.shields.io/github/last-commit/verhas/javageci) [Geci](https://github.com/verhas/javageci) - Discovers files that need generated code, updates automatically and writes to the source with a convenient API.
- [Immutables](https://immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
- <code>&nbsp;&nbsp;9530</code> ![](https://img.shields.io/github/last-commit/square/javapoet) [JavaPoet](https://github.com/square/javapoet) - API to generate source files.
- <code>&nbsp;19445</code> ![](https://img.shields.io/github/last-commit/jhipster/generator-jhipster) [JHipster](https://github.com/jhipster/generator-jhipster) - Yeoman source code generator for Spring Boot and AngularJS.
- [Joda-Beans](https://www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
- [JPA Buddy ![c]](https://www.jpa-buddy.com) - Plugin for IntelliJ IDEA. Provides visual tools for generating JPA entities, Spring Data JPA repositories, Liquibase changelogs and SQL scripts. Offers automatic Liquibase/Flyway script generation by comparing model to DB, and reverse engineering JPA entities from DB tables.
- [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.
- <code>&nbsp;&nbsp;&nbsp;275</code> ![](https://img.shields.io/github/last-commit/Randgalt/record-builder) [Record-Builder](https://github.com/Randgalt/record-builder) - Companion builder class, withers and templates for Java records.
- [Telosys](https://www.telosys.org/) - Simple and light code generator available as an Eclipse Plugin and also as a CLI.

### Compiler-compiler

_Frameworks that help to create parsers, interpreters or compilers._

- [ANTLR](https://www.antlr.org) - Complex full-featured framework for top-down parsing.
- [JavaCC](https://javacc.github.io/javacc/) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
- [JFlex](https://jflex.de) - Lexical analyzer generator.

### Computer Vision

_Libraries which seek to gain high level information from images and videos._

- [BoofCV](https://boofcv.org) - Library for image processing, camera calibration, tracking, SFM, MVS, 3D vision, QR Code and much more.
- [ImageJ](https://imagej.net/ImageJ) - Medical image processing application with an API.
- <code>&nbsp;&nbsp;5812</code> ![](https://img.shields.io/github/last-commit/bytedeco/javacv) [JavaCV](https://github.com/bytedeco/javacv) - Java interface to OpenCV, FFmpeg, and much more.

### Configuration

_Libraries that provide external configuration._

- <code>&nbsp;&nbsp;&nbsp;460</code> ![](https://img.shields.io/github/last-commit/line/centraldogma) [centraldogma](https://github.com/line/centraldogma) - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.
- <code>&nbsp;&nbsp;&nbsp;542</code> ![](https://img.shields.io/github/last-commit/cfg4j/cfg4j) [cfg4j](https://github.com/cfg4j/cfg4j) - Modern configuration library for distributed apps written in Java.
- <code>&nbsp;&nbsp;5576</code> ![](https://img.shields.io/github/last-commit/lightbend/config) [config](https://github.com/lightbend/config) - Configuration library supporting Java properties, JSON or its human optimized superset HOCON.
- <code>&nbsp;&nbsp;&nbsp;225</code> ![](https://img.shields.io/github/last-commit/SpongePowered/Configurate) [Configurate](https://github.com/SpongePowered/Configurate) - Configuration library with support for various configuration formats and transformations.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/shyiko/dotenv) [dotenv](https://github.com/shyiko/dotenv) - Twelve-factor configuration library which uses environment-specific files.
- [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/mariomac/kaconf) [KAConf](https://github.com/mariomac/kaconf) - Annotation-based configuration system for Java and Kotlin.
- [microconfig](https://microconfig.io) - Configuration system designed for microservices which helps to separate configuration from code. The configuration for different services can have common and specific parts and can be dynamically distributed.
- <code>&nbsp;&nbsp;&nbsp;851</code> ![](https://img.shields.io/github/last-commit/lviggiano/owner) [owner](https://github.com/lviggiano/owner) - Reduces boilerplate of properties.

### Constraint Satisfaction Problem Solver

_Libraries that help with implementing optimization and satisfiability problems._

- [Choco](https://choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
- <code>&nbsp;&nbsp;&nbsp;189</code> ![](https://img.shields.io/github/last-commit/radsz/jacop) [JaCoP](https://github.com/radsz/jacop) - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. (AGPL-3.0)
- [OptaPlanner](https://www.optaplanner.org) - Business planning and resource scheduling optimization solver.

### CSV

_Frameworks and libraries that simplify reading/writing CSV data._

- <code>&nbsp;&nbsp;&nbsp;364</code> ![](https://img.shields.io/github/last-commit/osiegmar/FastCSV) [FastCSV](https://github.com/osiegmar/FastCSV) - Performance-optimized, dependency-free and RFC 4180 compliant.
- <code>&nbsp;&nbsp;&nbsp;194</code> ![](https://img.shields.io/github/last-commit/FasterXML/jackson-dataformat-csv) [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) - Jackson extension for reading and writing CSV.
- [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
- [Super CSV](https://super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.
- <code>&nbsp;&nbsp;&nbsp;830</code> ![](https://img.shields.io/github/last-commit/uniVocity/univocity-parsers) [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.

### Data Structures

_Efficient and specific data structures._

- [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
- [Apache Orc](https://orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
- [Apache Parquet](https://parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
- [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
- <code>&nbsp;&nbsp;&nbsp;495</code> ![](https://img.shields.io/github/last-commit/bulldog2011/bigqueue) [Big Queue](https://github.com/bulldog2011/bigqueue) - Fast and persistent queue based on memory-mapped files.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;48</code> ![](https://img.shields.io/github/last-commit/LiveRamp/HyperMinHash-java) [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) - Probabilistic data structure for computing union, intersection, and set cardinality in loglog space.
- <code>&nbsp;&nbsp;&nbsp;690</code> ![](https://img.shields.io/github/last-commit/hrldcpr/pcollections) [Persistent Collection](https://github.com/hrldcpr/pcollections) - Persistent and immutable analogue of the Java Collections Framework.
- <code>&nbsp;53920</code> ![](https://img.shields.io/github/last-commit/protocolbuffers/protobuf) [Protobuf](https://github.com/protocolbuffers/protobuf) - Google's data interchange format.
- <code>&nbsp;&nbsp;2588</code> ![](https://img.shields.io/github/last-commit/RoaringBitmap/RoaringBitmap) [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) - Fast and efficient compressed bitmap.
- <code>&nbsp;&nbsp;2603</code> ![](https://img.shields.io/github/last-commit/real-logic/simple-binary-encoding) [SBE](https://github.com/real-logic/simple-binary-encoding) - Simple Binary Encoding, one of the fastest message formats around.
- <code>&nbsp;&nbsp;2405</code> ![](https://img.shields.io/github/last-commit/square/tape) [Tape](https://github.com/square/tape) - Lightning-fast, transactional, file-based FIFO.
- <code>&nbsp;&nbsp;3736</code> ![](https://img.shields.io/github/last-commit/square/wire) [Wire](https://github.com/square/wire) - Clean, lightweight protocol buffers.

### Database

_Everything that simplifies interactions with the database._

- [Apache Calcite](https://calcite.apache.org) - Dynamic data management framework. It contains many of the pieces that comprise a typical database management system.
- [Apache Drill](https://drill.apache.org) - Distributed, schema on-the-fly, ANSI SQL query engine for Big Data exploration.
- [Apache Phoenix](https://phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
- <code>&nbsp;&nbsp;&nbsp;184</code> ![](https://img.shields.io/github/last-commit/arangodb/arangodb-java-driver) [ArangoDB](https://github.com/arangodb/arangodb-java-driver) - ArangoDB Java driver.
- <code>&nbsp;&nbsp;2393</code> ![](https://img.shields.io/github/last-commit/OpenHFT/Chronicle-Map) [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.
- [Debezium](https://debezium.io/) - Low latency data streaming platform for change data capture.
- [druid](https://druid.apache.org) - High-performance, column-oriented, distributed data store.
- <code>&nbsp;&nbsp;&nbsp;344</code> ![](https://img.shields.io/github/last-commit/eXist-db/exist) [eXist](https://github.com/eXist-db/exist) - NoSQL document database and application platform. (LGPL-2.1-only)
- <code>&nbsp;&nbsp;&nbsp;927</code> ![](https://img.shields.io/github/last-commit/vladmihalcea/flexy-pool) [FlexyPool](https://github.com/vladmihalcea/flexy-pool) - Brings metrics and failover strategies to the most common connection pooling solutions.
- [Flyway](https://flywaydb.org) - Simple database migration tool.
- [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
- <code>&nbsp;16649</code> ![](https://img.shields.io/github/last-commit/brettwooldridge/HikariCP) [HikariCP](https://github.com/brettwooldridge/HikariCP) - High-performance JDBC connection pool.
- [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
- <code>&nbsp;10377</code> ![](https://img.shields.io/github/last-commit/xetorthio/jedis) [Jedis](https://github.com/xetorthio/jedis) - Small client for interaction with Redis, with methods for commands.
- <code>&nbsp;&nbsp;2096</code> ![](https://img.shields.io/github/last-commit/searchbox-io/Jest) [Jest](https://github.com/searchbox-io/Jest) - Client for the Elasticsearch REST API.
- <code>&nbsp;&nbsp;&nbsp;134</code> ![](https://img.shields.io/github/last-commit/justinsb/jetcd) [jetcd](https://github.com/justinsb/jetcd) - Client library for etcd.
- <code>&nbsp;&nbsp;&nbsp;631</code> ![](https://img.shields.io/github/last-commit/my2iu/Jinq) [Jinq](https://github.com/my2iu/Jinq) - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ).
- [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
- <code>&nbsp;&nbsp;5290</code> ![](https://img.shields.io/github/last-commit/Meituan-Dianping/Leaf) [Leaf](https://github.com/Meituan-Dianping/Leaf) - Distributed ID generate service.
- [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
- [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
- <code>&nbsp;&nbsp;&nbsp;670</code> ![](https://img.shields.io/github/last-commit/vorburger/MariaDB4j) [MariaDB4j](https://github.com/vorburger/MariaDB4j) - Launcher for MariaDB that requires no installation or external dependencies.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;11</code> ![](https://img.shields.io/github/last-commit/arkanovicz/modality) [Modality](https://github.com/arkanovicz/modality) - Lightweight ORM with database reverse engineering features.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/mhewedy/spring-data-jpa-mongodb-expressions) [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions) - Allows you to use MongoDB query language to query your relational database.
- [Trino](https://trino.io) - Distributed SQL query engine for big data.
- <code>&nbsp;&nbsp;8360</code> ![](https://img.shields.io/github/last-commit/questdb/questdb) [QuestDB](https://github.com/questdb/questdb) - High-performance SQL database for time series. Supports InfluxDB line protocol, PostgreSQL wire protocol, and REST.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6</code> ![](https://img.shields.io/github/last-commit/querystream/querystream) [QueryStream](https://github.com/querystream/querystream) - Build JPA Criteria queries using a Stream-like API.
- [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
- <code>&nbsp;11276</code> ![](https://img.shields.io/github/last-commit/realm/realm-java) [Realm](https://github.com/realm/realm-java) - Mobile database to run directly inside phones, tablets or wearables.
- <code>&nbsp;18756</code> ![](https://img.shields.io/github/last-commit/redisson/redisson) [Redisson](https://github.com/redisson/redisson) - Allows for distributed and scalable data structures on top of a Redis server.
- <code>&nbsp;&nbsp;3092</code> ![](https://img.shields.io/github/last-commit/requery/requery) [requery](https://github.com/requery/requery) - Modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform.
- <code>&nbsp;&nbsp;1996</code> ![](https://img.shields.io/github/last-commit/speedment/speedment) [Speedment](https://github.com/speedment/speedment) - Database access library that utilizes Java 8's Stream API for querying.
- [Vibur DBCP](https://www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.
- <code>&nbsp;&nbsp;&nbsp;982</code> ![](https://img.shields.io/github/last-commit/JetBrains/xodus) [Xodus](https://github.com/JetBrains/xodus) - Highly concurrent transactional schema-less and ACID-compliant embedded database.

### Date and Time

_Libraries related to handling date and time._

- [Almanac Converter](https://github.com/chrisengelsma/almanac-converter) - Simple conversion between different calendar systems.
- <code>&nbsp;&nbsp;&nbsp;573</code> ![](https://img.shields.io/github/last-commit/ical4j/ical4j) [iCal4j](https://github.com/ical4j/ical4j) - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models.
- [Jollyday](http://jollyday.sourceforge.net) - Determines the holidays for a given year, country/name and eventually state/region.
- <code>&nbsp;&nbsp;&nbsp;335</code> ![](https://img.shields.io/github/last-commit/ThreeTen/threeten-extra) [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) - Additional date-time classes that complement those in JDK 8.
- <code>&nbsp;&nbsp;&nbsp;364</code> ![](https://img.shields.io/github/last-commit/MenoData/Time4J) [Time4J](https://github.com/MenoData/Time4J) - Advanced date and time library. (LGPL-2.1-only)

### Dependency Injection

_Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm._

- [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
- [Dagger](https://dagger.dev/) - Compile-time injection framework without reflection.
- <code>&nbsp;&nbsp;&nbsp;332</code> ![](https://img.shields.io/github/last-commit/zsoltherpai/feather) [Feather](https://github.com/zsoltherpai/feather) - Ultra-lightweight, JSR-330-compliant dependency injection library.
- <code>&nbsp;&nbsp;&nbsp;806</code> ![](https://img.shields.io/github/last-commit/Netflix/governator) [Governator](https://github.com/Netflix/governator) - Extensions and utilities that enhance Google Guice.
- <code>&nbsp;10944</code> ![](https://img.shields.io/github/last-commit/google/guice) [Guice](https://github.com/google/guice) - Lightweight and opinionated framework that completes Dagger.
- [HK2](https://javaee.github.io/hk2/) - Lightweight and dynamic dependency injection framework.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;50</code> ![](https://img.shields.io/github/last-commit/vanillasource/jaywire) [JayWire](https://github.com/vanillasource/jaywire) - Lightweight dependency injection framework. (LGPL-3.0-only)

### Development

_Augmentation of the development process at a fundamental level._

- [AspectJ](https://www.eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
- [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime. (GPL-2.0-only)
- <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/zalando/faux-pas) [Faux Pas](https://github.com/zalando/faux-pas) - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions.
- <code>&nbsp;&nbsp;1800</code> ![](https://img.shields.io/github/last-commit/HotswapProjects/HotswapAgent) [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) - Unlimited runtime class and resource redefinition. (GPL-2.0-only)
- <code>&nbsp;&nbsp;4159</code> ![](https://img.shields.io/github/last-commit/javaparser/javaparser) [JavaParser](https://github.com/javaparser/javaparser) - Parse, modify and generate Java code.
- <code>&nbsp;&nbsp;&nbsp;286</code> ![](https://img.shields.io/github/last-commit/javaparser/javasymbolsolver) [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) - Symbol solver.
- <code>&nbsp;&nbsp;1244</code> ![](https://img.shields.io/github/last-commit/manifold-systems/manifold) [Manifold](https://github.com/manifold-systems/manifold) - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.
- [NoException](https://noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;68</code> ![](https://img.shields.io/github/last-commit/rainerhahnekamp/sneakythrow) [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow) - Ignores checked exceptions without bytecode manipulation. Can also be used inside Java 8 stream operations.
- [Tail](https://kag0.github.io/tail) - Enable infinite recursion using tail call optimization.

### Distributed Applications

_Libraries and frameworks for writing distributed and fault-tolerant applications._

- [Apache Geode](https://geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
- [Apache Storm](https://storm.apache.org) - Realtime computation system.
- [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
- [Atomix](https://atomix.io) - Fault-tolerant distributed coordination framework.
- [Axon](https://axoniq.io) - Framework for creating CQRS applications.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;41</code> ![](https://img.shields.io/github/last-commit/mtakaki/dropwizard-circuitbreaker) [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) - Circuit breaker design pattern for Dropwizard. (GPL-2.0-only)
- <code>&nbsp;&nbsp;3696</code> ![](https://img.shields.io/github/last-commit/jhalterman/failsafe) [Failsafe](https://github.com/jhalterman/failsafe) - Simple failure handling with retries and circuit breakers.
- <code>&nbsp;&nbsp;4802</code> ![](https://img.shields.io/github/last-commit/hazelcast/hazelcast) [Hazelcast](https://github.com/hazelcast/hazelcast) - Highly scalable in-memory datagrid with a free open-source version.
- [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
- [Quasar](http://docs.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.
- <code>&nbsp;&nbsp;7873</code> ![](https://img.shields.io/github/last-commit/resilience4j/resilience4j) [resilience4j](https://github.com/resilience4j/resilience4j) - Functional fault tolerance library.
- <code>&nbsp;&nbsp;&nbsp;543</code> ![](https://img.shields.io/github/last-commit/scalecube/scalecube-services) [ScaleCube Services](https://github.com/scalecube/scalecube-services) - Embeddable Cluster-Membership library based on SWIM and gossip protocol.
- <code>&nbsp;11872</code> ![](https://img.shields.io/github/last-commit/Netflix/zuul) [Zuul](https://github.com/Netflix/zuul) - Gateway service that provides dynamic routing, monitoring, resiliency, security, and more.

### Distributed Transactions

_Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures._

- [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
- <code>&nbsp;&nbsp;&nbsp;396</code> ![](https://img.shields.io/github/last-commit/bitronix/btm) [Bitronix](https://github.com/bitronix/btm) - Simple but complete implementation of the JTA 1.1 API.
- [Narayana](https://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards. (LGPL-2.1-only)
- <code>&nbsp;21947</code> ![](https://img.shields.io/github/last-commit/seata/seata) [Seata](https://github.com/seata/seata) - Delivers high performance and easy to use distributed transaction services under a microservices architecture.

### Distribution

_Tools that handle the distribution of applications in native formats._

- <code>&nbsp;&nbsp;&nbsp;255</code> ![](https://img.shields.io/github/last-commit/artipie/artipie) [Artipie](https://github.com/artipie/artipie) - Binary artifact management toolkit which hosts them on the file system or S3.
- [Boxfuse ![c]](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
- <code>&nbsp;&nbsp;1145</code> ![](https://img.shields.io/github/last-commit/puniverse/capsule) [Capsule](https://github.com/puniverse/capsule) - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
- [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
- [Cloudsmith ![c]](https://cloudsmith.io) - Fully managed package management SaaS with support for Maven/Gradle/SBT with a free tier.
- <code>&nbsp;&nbsp;&nbsp;451</code> ![](https://img.shields.io/github/last-commit/threerings/getdown) [Getdown](https://github.com/threerings/getdown) - A system for deploying Java applications to end-user computers and keeping them up to date. Developed as an alternative to Java Web Start.
- [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
- <code>&nbsp;&nbsp;&nbsp;503</code> ![](https://img.shields.io/github/last-commit/fvarrui/JavaPackager) [JavaPackager](https://github.com/fvarrui/JavaPackager) - Maven and Gradle plugin which provides an easy way to package Java applications in native Windows, Mac OS X or GNU/Linux executables, and generate installers for them.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code> ![](https://img.shields.io/github/last-commit/cilki/jlink.online) [jlink.online](https://github.com/cilki/jlink.online) - Builds optimized runtimes over HTTP.
- [Nexus ![c]](https://www.sonatype.com) - Binary management with proxy and caching capabilities.
- <code>&nbsp;&nbsp;2331</code> ![](https://img.shields.io/github/last-commit/libgdx/packr) [packr](https://github.com/libgdx/packr) - Packs JARs, assets and the JVM for native distribution on Windows, Linux and macOS.
- <code>&nbsp;&nbsp;&nbsp;106</code> ![](https://img.shields.io/github/last-commit/brianm/really-executable-jars-maven-plugin) [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) - Maven plugin for making self-executing JARs.

### Document Processing

_Libraries that assist with processing office document formats._

- [Apache POI](https://poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
- [documents4j](https://documents4j.com/#/) - API for document format conversion using third-party converters such as MS Word.
- [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.
- <code>&nbsp;&nbsp;&nbsp;376</code> ![](https://img.shields.io/github/last-commit/dhatim/fastexcel) [fastexcel](https://github.com/dhatim/fastexcel) - High performance library to read and write large Excel (XLSX) worksheets.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;65</code> ![](https://img.shields.io/github/last-commit/creditdatamw/zerocell) [zerocell](https://github.com/creditdatamw/zerocell) - Annotation-based API for reading data from Excel sheets into POJOs with focus on reduced overhead.

### Financial

_Libraries related to the financial domain._

- <code>&nbsp;&nbsp;&nbsp;342</code> ![](https://img.shields.io/github/last-commit/cassandre-tech/cassandre-trading-bot) [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot) - Trading bot framework.
- <code>&nbsp;&nbsp;&nbsp;500</code> ![](https://img.shields.io/github/last-commit/paritytrading/parity) [Parity](https://github.com/paritytrading/parity) - Platform for trading venues.
- <code>&nbsp;&nbsp;&nbsp;262</code> ![](https://img.shields.io/github/last-commit/paritytrading/philadelphia) [Philadelphia](https://github.com/paritytrading/philadelphia) - Low-latency financial information exchange.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;38</code> ![](https://img.shields.io/github/last-commit/square/connect-java-sdk) [Square](https://github.com/square/connect-java-sdk) - Integration with the Square API.
- <code>&nbsp;&nbsp;&nbsp;599</code> ![](https://img.shields.io/github/last-commit/stripe/stripe-java) [Stripe](https://github.com/stripe/stripe-java) - Integration with the Stripe API.
- <code>&nbsp;&nbsp;1468</code> ![](https://img.shields.io/github/last-commit/ta4j/ta4j) [ta4j](https://github.com/ta4j/ta4j) - Library for technical analysis.

### Formal Verification

_Formal-methods tools: proof assistants, model checking, symbolic execution, etc._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/ksen007/janala2) [CATG](https://github.com/ksen007/janala2) - Concolic unit testing engine. Automatically generates unit tests using formal methods.
- [Checker Framework](https://checkerframework.org) - Pluggable type systems. Includes nullness types, physical units, immutability types and more. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Daikon](https://plse.cs.washington.edu/daikon/) - Detects likely program invariants and generates JML specs based on those invariants.
- <code>&nbsp;&nbsp;&nbsp;376</code> ![](https://img.shields.io/github/last-commit/javapathfinder/jpf-core) [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core) - JVM formal verification tool containing a model checker and more. Created by NASA.
- [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
- [KeY](https://www.key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification. (GPL-2.0-or-later)
- [OpenJML](http://www.openjml.org) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers. (GPL-2.0-only)

### Functional Programming

_Libraries that facilitate functional programming._

- <code>&nbsp;&nbsp;1220</code> ![](https://img.shields.io/github/last-commit/aol/cyclops) [Cyclops](https://github.com/aol/cyclops) - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
- <code>&nbsp;&nbsp;&nbsp;533</code> ![](https://img.shields.io/github/last-commit/derive4j/derive4j) [derive4j](https://github.com/derive4j/derive4j) - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. (GPL-3.0-only)
- [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
- [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
- <code>&nbsp;&nbsp;1909</code> ![](https://img.shields.io/github/last-commit/jOOQ/jOOL) [jOOλ](https://github.com/jOOQ/jOOL) - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.
- <code>&nbsp;&nbsp;&nbsp;458</code> ![](https://img.shields.io/github/last-commit/poetix/protonpack) [protonpack](https://github.com/poetix/protonpack) - Collection of stream utilities.
- <code>&nbsp;&nbsp;1842</code> ![](https://img.shields.io/github/last-commit/amaembo/streamex) [StreamEx](https://github.com/amaembo/streamex) - Enhances Java 8 Streams.
- [Vavr](https://www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

_Frameworks that support the development of games._

- [FXGL](https://almasb.github.io/FXGL/) - JavaFX Game Development Framework.
- [JBox2D](http://www.jbox2d.org/) - Port of the renowned C++ 2D physics engine.
- [jMonkeyEngine](https://jmonkeyengine.org) - Game engine for modern 3D development.
- [libGDX](https://libgdx.com) - All-round cross-platform, high-level framework.
- [Litiengine](https://litiengine.com/) - AWT-based, lightweight 2D game engine.
- [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.
- [Mini2Dx](https://mini2dx.org) - Beginner-friendly, master-ready framework for rapidly prototyping and building 2D games.

### Geospatial

_Libraries for working with geospatial data and algorithms._

- [Apache SIS](https://sis.apache.org) - Library for developing geospatial applications.
- <code>&nbsp;&nbsp;&nbsp;368</code> ![](https://img.shields.io/github/last-commit/davidmoten/geo) [Geo](https://github.com/davidmoten/geo) - GeoHash utilities in Java.
- [GeoTools](https://geotools.org) - Library that provides tools for geospatial data. (LGPL-2.1-only)
- <code>&nbsp;&nbsp;3614</code> ![](https://img.shields.io/github/last-commit/graphhopper/graphhopper) [GraphHopper](https://github.com/graphhopper/graphhopper) - Road-routing engine. Used as a Java library or standalone web service.
- [H2GIS](http://www.h2gis.org) - Spatial extension of the H2 database. (LGPL-3.0-only)
- [Jgeohash](https://astrapi69.github.io/jgeohash/) - Library for using the GeoHash algorithm.
- <code>&nbsp;&nbsp;&nbsp;959</code> ![](https://img.shields.io/github/last-commit/mapsforge/mapsforge) [Mapsforge](https://github.com/mapsforge/mapsforge) - Map rendering based on OpenStreetMap data. (LGPL-3.0-only)
- <code>&nbsp;&nbsp;&nbsp;825</code> ![](https://img.shields.io/github/last-commit/locationtech/spatial4j) [Spatial4j](https://github.com/locationtech/spatial4j) - General-purpose spatial/geospatial library.

### GUI

_Libraries to create modern graphical user interfaces._

- [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Successor of Swing.
- [Scene Builder](https://gluonhq.com/products/scene-builder/) - Visual layout tool for JavaFX applications.
- [SWT](https://www.eclipse.org/swt/) - Graphical widget toolkit.

### High Performance

_Everything about high-performance computation, from collections to specific libraries._

- <code>&nbsp;&nbsp;2248</code> ![](https://img.shields.io/github/last-commit/real-logic/Agrona) [Agrona](https://github.com/real-logic/Agrona) - Data structures and utility methods that are common in high-performance applications.
- [Disruptor](https://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
- <code>&nbsp;&nbsp;1913</code> ![](https://img.shields.io/github/last-commit/eclipse/eclipse-collections) [Eclipse Collections](https://github.com/eclipse/eclipse-collections) - Collections framework inspired by Smalltalk.
- [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
- [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.
- <code>&nbsp;&nbsp;2910</code> ![](https://img.shields.io/github/last-commit/JCTools/JCTools) [JCTools](https://github.com/JCTools/JCTools) - Concurrency tools currently missing from the JDK.
- <code>&nbsp;&nbsp;&nbsp;955</code> ![](https://img.shields.io/github/last-commit/leventov/Koloboke) [Koloboke](https://github.com/leventov/Koloboke) - Carefully designed extension of the Java Collections Framework with primitive specializations and more.

### HTTP Clients

_Libraries that assist with creating HTTP requests and/or binding responses._

- [Apache HttpComponents](https://hc.apache.org/) - A toolset of low level Java components focused on HTTP and associated protocols.
- <code>&nbsp;&nbsp;5928</code> ![](https://img.shields.io/github/last-commit/AsyncHttpClient/async-http-client) [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) - Asynchronous HTTP and WebSocket client library.
- <code>&nbsp;&nbsp;7974</code> ![](https://img.shields.io/github/last-commit/OpenFeign/feign) [Feign](https://github.com/OpenFeign/feign) - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
- <code>&nbsp;&nbsp;1227</code> ![](https://img.shields.io/github/last-commit/googleapis/google-http-java-client) [Google HTTP Client](https://github.com/googleapis/google-http-java-client) - Pluggable HTTP transport abstraction with support for java.net.HttpURLConnection, Apache HTTP Client, Android, Google App Engine, XML, Gson, Jackson and Protobuf.
- <code>&nbsp;&nbsp;&nbsp;128</code> ![](https://img.shields.io/github/last-commit/mizosoft/methanol) [methanol](https://github.com/mizosoft/methanol) - HTTP client extensions library.
- [restQL-java](https://github.com/b2wdigital/restQL-java) - Microservice query language that fetches information from multiple services.
- [Retrofit](https://square.github.io/retrofit/) - Typesafe REST client.
- <code>&nbsp;&nbsp;4222</code> ![](https://img.shields.io/github/last-commit/Netflix/ribbon) [Ribbon](https://github.com/Netflix/ribbon) - Client-side IPC library that is battle-tested in cloud.
- <code>&nbsp;&nbsp;&nbsp;225</code> ![](https://img.shields.io/github/last-commit/zalando/riptide) [Riptide](https://github.com/zalando/riptide) - Client-side response routing for Spring's RestTemplate.
- <code>&nbsp;&nbsp;2260</code> ![](https://img.shields.io/github/last-commit/Kong/unirest-java) [unirest-java](https://github.com/Kong/unirest-java) - Simplified, lightweight HTTP client library.

### Hypermedia Types

_Libraries that handle serialization to hypermedia types._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/blackdoor/hate) [hate](https://github.com/blackdoor/hate) - Builds hypermedia-friendly objects according to HAL specification.
- <code>&nbsp;&nbsp;&nbsp;353</code> ![](https://img.shields.io/github/last-commit/jsonld-java/jsonld-java) [JSON-LD](https://github.com/jsonld-java/jsonld-java) - JSON-LD implementation.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;22</code> ![](https://img.shields.io/github/last-commit/eserating-chwy/siren4j) [Siren4J](https://github.com/eserating-chwy/siren4j) - Library for the Siren specification.

### IDE

_Integrated development environments that try to simplify several aspects of development._

- [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
- [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
- [jGRASP](https://www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
- [NetBeans](https://netbeans.apache.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
- [Recaf](https://www.coley.software/Recaf/) - Bytecode editor.
- [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

_Libraries that assist with the creation, evaluation or manipulation of graphical images._

- <code>&nbsp;&nbsp;1108</code> ![](https://img.shields.io/github/last-commit/rkalla/imgscalr) [Imgscalr](https://github.com/rkalla/imgscalr) - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.
- <code>&nbsp;&nbsp;1148</code> ![](https://img.shields.io/github/last-commit/nguyenq/tess4j) [Tess4J](https://github.com/nguyenq/tess4j) - JNA wrapper for Tesseract OCR API.
- <code>&nbsp;&nbsp;4084</code> ![](https://img.shields.io/github/last-commit/coobird/thumbnailator) [Thumbnailator](https://github.com/coobird/thumbnailator) - High-quality thumbnail generation library.
- <code>&nbsp;&nbsp;1423</code> ![](https://img.shields.io/github/last-commit/haraldk/TwelveMonkeys) [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) - Collection of plugins that extend the number of supported image file formats.
- <code>&nbsp;29405</code> ![](https://img.shields.io/github/last-commit/zxing/zxing) [ZXing](https://github.com/zxing/zxing) - Multi-format 1D/2D barcode image processing library.
- <code>&nbsp;&nbsp;&nbsp;201</code> ![](https://img.shields.io/github/last-commit/romankh3/image-comparison) [image-comparison](https://github.com/romankh3/image-comparison) - Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison. Can be used for automation qa tests.

### Introspection

_Libraries that help make the Java introspection and reflection API easier and faster to use._

- <code>&nbsp;&nbsp;2199</code> ![](https://img.shields.io/github/last-commit/classgraph/classgraph) [ClassGraph](https://github.com/classgraph/classgraph) - ClassGraph (formerly FastClasspathScanner) is an uber-fast, ultra-lightweight, parallelized classpath scanner and module scanner for Java, Scala, Kotlin and other JVM languages.
- <code>&nbsp;&nbsp;2575</code> ![](https://img.shields.io/github/last-commit/jOOQ/jOOR) [jOOR](https://github.com/jOOQ/jOOR) - jOOR stands for jOOR Object Oriented Reflection. It is a simple wrapper for the java.lang.reflect package.
- [Mirror](http://projetos.vidageek.net/mirror/mirror/) - Mirror was created to bring light to a simple problem, usually named ReflectionUtil, which is on almost all projects that rely on reflection to do advanced tasks.
- [Objenesis](http://objenesis.org) - Allows dynamic instantiation without default constructor, e.g. constructors which have required arguments, side effects or throw exceptions.
- <code>&nbsp;&nbsp;1316</code> ![](https://img.shields.io/github/last-commit/EsotericSoftware/reflectasm) [ReflectASM](https://github.com/EsotericSoftware/reflectasm) - ReflectASM is a very small Java library that provides high performance reflection by using code generation.
- <code>&nbsp;&nbsp;4097</code> ![](https://img.shields.io/github/last-commit/ronmamo/reflections) [Reflections](https://github.com/ronmamo/reflections) - Reflections scans your classpath, indexes the metadata, allows you to query it on runtime and may save and collect that information for many modules within your project.

### Job Scheduling

_Libraries for scheduling background jobs._

- <code>&nbsp;&nbsp;&nbsp;864</code> ![](https://img.shields.io/github/last-commit/jobrunr/jobrunr) [JobRunr](https://github.com/jobrunr/jobrunr) - Job scheduling library which utilizes lambdas for fire-and-forget, delayed and recurring jobs. Guarantees execution by single scheduler instance using optimistic locking. Has features for persistence, minimal dependencies and is embeddable.
- <code>&nbsp;&nbsp;4943</code> ![](https://img.shields.io/github/last-commit/quartz-scheduler/quartz) [Quartz](https://github.com/quartz-scheduler/quartz) - Feature-rich, open source job scheduling library that can be integrated within virtually any Java application.
- <code>&nbsp;&nbsp;&nbsp;252</code> ![](https://img.shields.io/github/last-commit/knowm/Sundial) [Sundial](https://github.com/knowm/Sundial) - Lightweight framework to simply define jobs, define triggers and start the scheduler.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;86</code> ![](https://img.shields.io/github/last-commit/Coreoz/Wisp) [Wisp](https://github.com/Coreoz/Wisp) - Simple library with minimal footprint and straightforward API.
- <code>&nbsp;&nbsp;&nbsp;556</code> ![](https://img.shields.io/github/last-commit/kagkarlsson/db-scheduler) [db-scheduler](https://github.com/kagkarlsson/db-scheduler) - Persistent and cluster-friendly scheduler.
- <code>&nbsp;&nbsp;&nbsp;547</code> ![](https://img.shields.io/github/last-commit/j-easy/easy-batch) [easy-batch](https://github.com/j-easy/easy-batch) - Set up batch jobs with simple processing pipelines. Records are read in sequence from a data source, processed in pipeline and written in batches to a data sink.
- <code>&nbsp;&nbsp;2363</code> ![](https://img.shields.io/github/last-commit/lukas-krecan/ShedLock) [shedlock](https://github.com/lukas-krecan/ShedLock) - Makes sure that your scheduled tasks are executed at most once at the same time. If a task is being executed on one node, it acquires a lock which prevents execution of the same task from another node or thread.

### JSON

_Libraries for serializing and deserializing JSON to and from Java objects._

- <code>&nbsp;&nbsp;&nbsp;787</code> ![](https://img.shields.io/github/last-commit/ngs-doo/dsl-json) [DSL-JSON](https://github.com/ngs-doo/dsl-json) - JSON library with advanced compile time databinding.
- [Genson](http://genson.io) - Powerful and easy-to-use Java-to-JSON conversion library.
- <code>&nbsp;20780</code> ![](https://img.shields.io/github/last-commit/google/gson) [Gson](https://github.com/google/gson) - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
- <code>&nbsp;&nbsp;&nbsp;443</code> ![](https://img.shields.io/github/last-commit/brettwooldridge/HikariJSON) [HikariJSON](https://github.com/brettwooldridge/HikariJSON) - High-performance JSON parser, 2x faster than Jackson.
- <code>&nbsp;&nbsp;&nbsp;346</code> ![](https://img.shields.io/github/last-commit/FasterXML/jackson-modules-java8) [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) - Set of Jackson modules for Java 8 datatypes and features.
- <code>&nbsp;&nbsp;&nbsp;196</code> ![](https://img.shields.io/github/last-commit/zalando/jackson-datatype-money) [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.
- <code>&nbsp;&nbsp;7346</code> ![](https://img.shields.io/github/last-commit/FasterXML/jackson) [Jackson](https://github.com/FasterXML/jackson) - Similar to GSON, but offers performance gains if you need to instantiate the library more often.
- <code>&nbsp;&nbsp;&nbsp;295</code> ![](https://img.shields.io/github/last-commit/jdereg/json-io) [JSON-io](https://github.com/jdereg/json-io) - Convert Java to JSON. Convert JSON to Java. Pretty print JSON. Java JSON serializer.
- [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.
- <code>&nbsp;&nbsp;3238</code> ![](https://img.shields.io/github/last-commit/bluelinelabs/LoganSquare) [LoganSquare](https://github.com/bluelinelabs/LoganSquare) - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.
- <code>&nbsp;&nbsp;8157</code> ![](https://img.shields.io/github/last-commit/square/moshi) [Moshi](https://github.com/square/moshi) - Modern JSON library, less opinionated and uses built-in types like List and Map.
- <code>&nbsp;&nbsp;&nbsp;178</code> ![](https://img.shields.io/github/last-commit/eclipse-ee4j/yasson) [Yasson](https://github.com/eclipse-ee4j/yasson) - Binding layer between classes and JSON documents similar to JAXB.
- <code>&nbsp;24254</code> ![](https://img.shields.io/github/last-commit/alibaba/fastjson) [fastjson](https://github.com/alibaba/fastjson) - Very fast processor with no additional dependencies and full data binding.
- <code>&nbsp;&nbsp;1199</code> ![](https://img.shields.io/github/last-commit/bazaarvoice/jolt) [Jolt](https://github.com/bazaarvoice/jolt) - JSON to JSON transformation tool.
- <code>&nbsp;&nbsp;6873</code> ![](https://img.shields.io/github/last-commit/json-path/JsonPath) [JsonPath](https://github.com/json-path/JsonPath) - Extract data from JSON using XPATH-like syntax.
- <code>&nbsp;&nbsp;&nbsp;239</code> ![](https://img.shields.io/github/last-commit/jsurfer/JsonSurfer) [JsonSurfer](https://github.com/jsurfer/JsonSurfer) - Streaming JsonPath processor dedicated to processing big and complicated JSON data.

### JVM and JDK

_Current implementations of the JVM/JDK._

- [Adopt Open JDK](https://adoptopenjdk.net) - Community-driven OpenJDK builds, including both HotSpot and OpenJ9.
- <code>&nbsp;&nbsp;1203</code> ![](https://img.shields.io/github/last-commit/ReadyTalk/avian) [Avian](https://github.com/ReadyTalk/avian) - JVM with JIT, AOT modes and iOS port.
- [Corretto](https://aws.amazon.com/corretto/) - No-cost, multiplatform, production-ready distribution of OpenJDK by Amazon. (GPL-2.0-only WITH Classpath-exception-2.0)
- <code>&nbsp;&nbsp;3522</code> ![](https://img.shields.io/github/last-commit/alibaba/dragonwell8) [Dragonwell8](https://github.com/alibaba/dragonwell8) - Downstream version of OpenJDK optimized for online e-commerce, financial, logistics applications.
- <code>&nbsp;16862</code> ![](https://img.shields.io/github/last-commit/oracle/graal) [Graal](https://github.com/oracle/graal) - Polyglot embeddable JVM. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Liberica JDK](https://bell-sw.com) - Built from OpenJDK, thoroughly tested and passed the JCK. (GPL-2.0-only WITH Classpath-exception-2.0)
- <code>&nbsp;&nbsp;2857</code> ![](https://img.shields.io/github/last-commit/eclipse/openj9) [OpenJ9](https://github.com/eclipse/openj9) - High performance, enterprise-calibre, flexibly licensed, openly-governed cross-platform JVM extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project.
- [Open JDK](https://openjdk.java.net) - Open JDK community home. (GPL-2.0-only WITH Classpath-exception-2.0)
- <code>&nbsp;&nbsp;1208</code> ![](https://img.shields.io/github/last-commit/codenameone/CodenameOne) [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) - VM with non-blocking, concurrent GC for iOS. (GPL-2.0-only WITH Classpath-exception-2.0)
- [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution. (GPL-2.0-only WITH Classpath-exception-2.0)
- [SAP Machine](https://sap.github.io/SapMachine/) - SAP's no-cost, rigorously tested and JCK-verified OpenJDK friendly fork. (GPL-2.0-only WITH Classpath-exception-2.0)
- [Zulu](https://www.azul.com/products/zulu-community/) - OpenJDK builds for Windows, Linux, and macOS. (GPL-2.0-only WITH Classpath-exception-2.0)

### Logging

_Libraries that log the behavior of an application._

- [Apache Log4j 2](https://logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/tersesystems/echopraxia) [Echopraxia](https://github.com/tersesystems/echopraxia) - API designed around structured logging, rich context, and conditional logging. There are Logback and Log4J2 implementations, but Echopraxia's API is completely dependency-free, meaning it can be implemented with any logging API.
- [Graylog](https://www.graylog.org) - Open-source aggregator suited for extended role and permission management. (GPL-3.0-only)
- [Kibana](https://www.elastic.co/kibana) - Analyzes and visualizes log files. Some features require payment.
- [Logback](http://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
- <code>&nbsp;&nbsp;1084</code> ![](https://img.shields.io/github/last-commit/zalando/logbook) [Logbook](https://github.com/zalando/logbook) - Extensible, open-source library for HTTP request and response logging.
- [Logstash](https://www.elastic.co/logstash) - Tool for managing log files.
- <code>&nbsp;&nbsp;1636</code> ![](https://img.shields.io/github/last-commit/p6spy/p6spy) [p6spy](https://github.com/p6spy/p6spy) - Enables logging for all JDBC transactions without changes to the code.
- [SLF4J](http://www.slf4j.org) - Abstraction layer/simple logging facade.
- [tinylog](https://tinylog.org/v2/) - Lightweight logging framework with static logger class.
- <code>&nbsp;&nbsp;&nbsp;179</code> ![](https://img.shields.io/github/last-commit/zalando/opentracing-toolbox) [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox) - Collection of libraries that build on top of OpenTracing and provide extensions and plugins to existing instrumentations.

### Machine Learning

_Tools that provide specific statistical algorithms for learning from data._

- [Apache Flink](https://flink.apache.org) - Fast, reliable, large-scale data processing engine.
- [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
- [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
- [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
- [DJL](https://djl.ai) - High-level and engine-agnostic framework for deep learning.
- [H2O ![c]](https://www.h2o.ai) - Analytics engine for statistics over big data.
- <code>&nbsp;&nbsp;&nbsp;733</code> ![](https://img.shields.io/github/last-commit/EdwardRaff/JSAT) [JSAT](https://github.com/EdwardRaff/JSAT) - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. (GPL-3.0-only)
- <code>&nbsp;&nbsp;2077</code> ![](https://img.shields.io/github/last-commit/BayesWitnesses/m2cgen) [m2cgen](https://github.com/BayesWitnesses/m2cgen) - CLI tool to transpile models into native code.
- [oj! Algorithms](https://www.ojalgo.org/) - High-performance mathematics, linear algebra and optimisation needed for data science, machine learning and scientific computing.
- <code>&nbsp;&nbsp;1797</code> ![](https://img.shields.io/github/last-commit/OryxProject/oryx) [Oryx 2](https://github.com/OryxProject/oryx) - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.
- <code>&nbsp;&nbsp;1329</code> ![](https://img.shields.io/github/last-commit/siddhi-io/siddhi) [Siddhi](https://github.com/siddhi-io/siddhi) - Cloud native streaming and complex event processing engine.
- <code>&nbsp;&nbsp;5494</code> ![](https://img.shields.io/github/last-commit/haifengl/smile) [Smile](https://github.com/haifengl/smile) - Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
- [Tribuo](https://tribuo.org/) - Provides tools for classification, regression, clustering, model development and interfaces with other libraries such as scikit-learn, pytorch and TensorFlow.
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization. (GPL-3.0-only)

### Messaging

_Tools that help send messages between clients to ensure protocol independency._

- <code>&nbsp;&nbsp;5955</code> ![](https://img.shields.io/github/last-commit/real-logic/Aeron) [Aeron](https://github.com/real-logic/Aeron) - Efficient, reliable, unicast and multicast message transport.
- [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
- [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
- [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
- [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
- [Apache RocketMQ](https://rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
- [Apache Qpid](https://qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
- <code>&nbsp;23906</code> ![](https://img.shields.io/github/last-commit/greenrobot/EventBus) [EventBus](https://github.com/greenrobot/EventBus) - Simple publish/subscribe event bus.
- [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.
- <code>&nbsp;&nbsp;2117</code> ![](https://img.shields.io/github/last-commit/zeromq/jeromq) [JeroMQ](https://github.com/zeromq/jeromq) - Implementation of ZeroMQ.
- <code>&nbsp;&nbsp;&nbsp;828</code> ![](https://img.shields.io/github/last-commit/zalando/nakadi) [Nakadi](https://github.com/zalando/nakadi) - Provides a RESTful API on top of Kafka.
- <code>&nbsp;&nbsp;1061</code> ![](https://img.shields.io/github/last-commit/rabbitmq/rabbitmq-java-client) [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) - RabbitMQ client.
- <code>&nbsp;&nbsp;2291</code> ![](https://img.shields.io/github/last-commit/igniterealtime/Smack) [Smack](https://github.com/igniterealtime/Smack) - Cross-platform XMPP client library.
- <code>&nbsp;&nbsp;&nbsp;404</code> ![](https://img.shields.io/github/last-commit/nats-io/nats.java) [NATS client](https://github.com/nats-io/nats.java) - NATS client.

### Microservice

_Tools for creating and managing microservices._

- [ActiveRPC](https://rpc.activej.io) - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
- [Apollo](https://spotify.github.io/apollo/) - Libraries for writing composable microservices.
- <code>&nbsp;&nbsp;3560</code> ![](https://img.shields.io/github/last-commit/line/armeria) [Armeria](https://github.com/line/armeria) - Asynchronous RPC/REST client/server library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC.
- <code>&nbsp;&nbsp;&nbsp;394</code> ![](https://img.shields.io/github/last-commit/Ecwid/consul-api) [consul-api](https://github.com/Ecwid/consul-api) - Client for the Consul API: a distributed, highly available and datacenter-aware registry/discovery service.
- <code>&nbsp;11212</code> ![](https://img.shields.io/github/last-commit/Netflix/eureka) [Eureka](https://github.com/Netflix/eureka) - REST-based service registry for resilient load balancing and failover.
- [Helidon](https://helidon.io) - Two-style approach for writing microservices: Functional-reactive and as an implementation of MicroProfile.
- [Micronaut](https://micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.
- [Nacos](https://nacos.io) - Dynamic service discovery, configuration and service management platform for building cloud native applications.
- [Quarkus](https://quarkus.io) - Kubernetes stack tailored for the HotSpot and Graal VM.
- <code>&nbsp;18889</code> ![](https://img.shields.io/github/last-commit/alibaba/Sentinel) [Sentinel](https://github.com/alibaba/Sentinel) - Flow control component enabling reliability, resilience and monitoring for microservices.

### Miscellaneous

_Everything else._

- <code>&nbsp;&nbsp;1484</code> ![](https://img.shields.io/github/last-commit/npgall/cqengine) [CQEngine](https://github.com/npgall/cqengine) - Ultra-fast, SQL-like queries on Java collections.
- <code>&nbsp;74322</code> ![](https://img.shields.io/github/last-commit/iluwatar/java-design-patterns) [Design Patterns](https://github.com/iluwatar/java-design-patterns) - Implementation and explanation of the most common design patterns.
- <code>&nbsp;&nbsp;1054</code> ![](https://img.shields.io/github/last-commit/ff4j/ff4j) [FF4J](https://github.com/ff4j/ff4j) - Feature Flags for Java.
- <code>&nbsp;17072</code> ![](https://img.shields.io/github/last-commit/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. (No explicit license)
- <code>&nbsp;&nbsp;5876</code> ![](https://img.shields.io/github/last-commit/google/j2objc) [J2ObjC](https://github.com/google/j2objc) - Java-to-Objective-C translator for porting Android libraries to iOS.
- [JBake](https://jbake.org) - Static website generator.
- <code>&nbsp;&nbsp;1172</code> ![](https://img.shields.io/github/last-commit/rampatra/jbot) [JBot](https://github.com/rampatra/jbot) - Framework for building chatbots. (GPL-3.0-only)
- [JCuda](http://jcuda.org) - JCuda offers Java bindings for CUDA and CUDA-related libraries.
- <code>&nbsp;&nbsp;2144</code> ![](https://img.shields.io/github/last-commit/google/jimfs) [Jimfs](https://github.com/google/jimfs) - In-memory file system.
- [JObfuscator![c]](https://www.pelock.com/products/jobfuscator) - Source code obfuscator.
- [Joda-Money](https://www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
- [JPad](http://jpad.io) - Snippet runner.
- <code>&nbsp;&nbsp;1287</code> ![](https://img.shields.io/github/last-commit/cincheo/jsweet) [jsweet](https://github.com/cincheo/jsweet) - Source transpiler to TypeScript/JavaScript.
- <code>&nbsp;&nbsp;1577</code> ![](https://img.shields.io/github/last-commit/takari/maven-wrapper) [Maven Wrapper](https://github.com/takari/maven-wrapper) - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven.
- <code>&nbsp;&nbsp;&nbsp;372</code> ![](https://img.shields.io/github/last-commit/membrane/service-proxy) [Membrane Service Proxy](https://github.com/membrane/service-proxy) - Open-source, reverse-proxy framework.
- <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/Guichaguri/MinimalFTP) [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) - Lightweight, small and customizable FTP server.
- <code>&nbsp;15613</code> ![](https://img.shields.io/github/last-commit/winterbe/java8-tutorial) [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) - Popular Java 8 guide.
- <code>&nbsp;&nbsp;&nbsp;310</code> ![](https://img.shields.io/github/last-commit/gaul/modernizer-maven-plugin) [Modernizer](https://github.com/gaul/modernizer-maven-plugin) - Detect uses of legacy Java APIs.
- <code>&nbsp;&nbsp;4923</code> ![](https://img.shields.io/github/last-commit/OctoLinker/OctoLinker) [OctoLinker](https://github.com/OctoLinker/OctoLinker) - Browser extension which allows to navigate through code on GitHub more efficiently.
- [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
- <code>&nbsp;&nbsp;&nbsp;224</code> ![](https://img.shields.io/github/last-commit/sizovs/pipelinr) [PipelinR](https://github.com/sizovs/pipelinr) - Small utility library for using handlers and commands with pipelines.
- <code>&nbsp;&nbsp;&nbsp;809</code> ![](https://img.shields.io/github/last-commit/takari/polyglot-maven) [Polyglot for Maven](https://github.com/takari/polyglot-maven) - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/Kartikvk1996/RR4J) [RR4J](https://github.com/Kartikvk1996/RR4J) - RR4J is a tool that records java bytecode execution and later allows developers to replay locally.
- <code>&nbsp;&nbsp;&nbsp;964</code> ![](https://img.shields.io/github/last-commit/bbottema/simple-java-mail) [Simple Java Mail](https://github.com/bbottema/simple-java-mail) - Mailing with a clean and fluent API.
- <code>&nbsp;&nbsp;&nbsp;343</code> ![](https://img.shields.io/github/last-commit/smooks/smooks) [Smooks](https://github.com/smooks/smooks) - Framework for fragment-based message processing. (Apache-2.0 OR LGPL-3.0-or-later)
- [Togglz](https://www.togglz.org) - Implementation of the Feature Toggles pattern.
- <code>&nbsp;&nbsp;&nbsp;555</code> ![](https://img.shields.io/github/last-commit/jhalterman/typetools) [TypeTools](https://github.com/jhalterman/typetools) - Tools for resolving generic types.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/SvenEwald/xmlbeam) [XMLBeam](https://github.com/SvenEwald/xmlbeam) - Processes XML by using annotations or XPath within code.
- <code>&nbsp;&nbsp;&nbsp;208</code> ![](https://img.shields.io/github/last-commit/yWorks/yGuard) [yGuard](https://github.com/yWorks/yGuard) - Obfuscation via renaming and shrinking.

### Mobile Development

_Tools for creating or managing mobile applications._

- [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps. (GPL-2.0-only WITH Classpath-exception-2.0)
- [MobileUI](https://mobileui.dev) - Cross-platform framework for developing mobile apps with native UI in Java and Kotlin.
- [Multi-OS Engine](https://multi-os-engine.org) - Open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.

### Monitoring

_Tools that monitor applications in production._

- <code>&nbsp;&nbsp;&nbsp;552</code> ![](https://img.shields.io/github/last-commit/stevensouza/automon) [Automon](https://github.com/stevensouza/automon) - Combines the power of AOP with monitoring and/or logging tools.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;52</code> ![](https://img.shields.io/github/last-commit/zalando/failsafe-actuator) [Failsafe Actuator](https://github.com/zalando/failsafe-actuator) - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment.
- [Glowroot](https://glowroot.org) - Open-source Java APM.
- [inspectIT](https://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
- [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
- <code>&nbsp;&nbsp;2521</code> ![](https://img.shields.io/github/last-commit/javamelody/javamelody) [JavaMelody](https://github.com/javamelody/javamelody) - Performance monitoring and profiling.
- <code>&nbsp;&nbsp;&nbsp;482</code> ![](https://img.shields.io/github/last-commit/jaegertracing/jaeger-client-java) [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) - Jaeger client.
- <code>&nbsp;&nbsp;1675</code> ![](https://img.shields.io/github/last-commit/jmxtrans/jmxtrans) [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.
- [Jolokia](https://jolokia.org) - JMX over REST.
- <code>&nbsp;&nbsp;7518</code> ![](https://img.shields.io/github/last-commit/dropwizard/metrics) [Metrics](https://github.com/dropwizard/metrics) - Expose metrics via JMX or HTTP and send them to a database.
- <code>&nbsp;&nbsp;&nbsp;314</code> ![](https://img.shields.io/github/last-commit/DataDog/dd-trace-java) [Datadog ![c]](https://github.com/DataDog/dd-trace-java) - Modern monitoring & analytics.
- <code>&nbsp;&nbsp;&nbsp;150</code> ![](https://img.shields.io/github/last-commit/lorenzoongithub/nudge4j) [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Remote developer console from the browser for Java 8 via bytecode injection.
- <code>&nbsp;12125</code> ![](https://img.shields.io/github/last-commit/naver/pinpoint) [Pinpoint](https://github.com/naver/pinpoint) - Open-source APM tool.
- <code>&nbsp;&nbsp;1717</code> ![](https://img.shields.io/github/last-commit/prometheus/client_java) [Prometheus](https://github.com/prometheus/client_java) - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
- <code>&nbsp;&nbsp;&nbsp;809</code> ![](https://img.shields.io/github/last-commit/getsentry/sentry-java) [Sentry ![c]](https://github.com/getsentry/sentry-java) - Integration with <code>&nbsp;30637</code> ![](https://img.shields.io/github/last-commit/getsentry/sentry) [Sentry](https://github.com/getsentry/sentry), an application error tracking and performance analysis platform.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;19</code> ![](https://img.shields.io/github/last-commit/sematext/sematext-agent-java) [SPM ![c]](https://github.com/sematext/sematext-agent-java) - Performance monitor with distributing transaction tracing for JVM apps.
- <code>&nbsp;&nbsp;1672</code> ![](https://img.shields.io/github/last-commit/stagemonitor/stagemonitor) [Stagemonitor](https://github.com/stagemonitor/stagemonitor) - Open-source performance monitoring and transaction tracing for JVM apps.
- <code>&nbsp;&nbsp;&nbsp;152</code> ![](https://img.shields.io/github/last-commit/palantir/Sysmon) [Sysmon](https://github.com/palantir/Sysmon) - Lightweight platform monitoring tool for Java VMs.
- [zipkin](https://zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native

_For working with platform-specific native libraries._

- <code>&nbsp;&nbsp;&nbsp;403</code> ![](https://img.shields.io/github/last-commit/Syncleus/aparapi) [Aparapi](https://github.com/Syncleus/aparapi) - Converts bytecode to OpenCL which allows execution on GPUs.
- <code>&nbsp;&nbsp;3805</code> ![](https://img.shields.io/github/last-commit/bytedeco/javacpp) [JavaCPP](https://github.com/bytedeco/javacpp) - Provides efficient and easy access to native C++.
- <code>&nbsp;&nbsp;7078</code> ![](https://img.shields.io/github/last-commit/java-native-access/jna) [JNA](https://github.com/java-native-access/jna) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.
- <code>&nbsp;&nbsp;&nbsp;976</code> ![](https://img.shields.io/github/last-commit/jnr/jnr-ffi) [JNR](https://github.com/jnr/jnr-ffi) - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama).

### Natural Language Processing

_Libraries that specialize in processing text._

- <code>&nbsp;&nbsp;&nbsp;440</code> ![](https://img.shields.io/github/last-commit/CogComp/cogcomp-nlp) [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) - Provides common annotators for plain text input. (Research and Academic Use License)
- [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis. (GPL-3.0-or-later)
- [DKPro](https://dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
- [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

_Libraries for building network servers._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code> ![](https://img.shields.io/github/last-commit/CiscoSE/commons-networking) [Commons-networking](https://github.com/CiscoSE/commons-networking) - Client for server-sent events (SSE).
- <code>&nbsp;&nbsp;&nbsp;602</code> ![](https://img.shields.io/github/last-commit/puniverse/comsat) [Comsat](https://github.com/puniverse/comsat) - Integrates standard Java web-related APIs with Quasar fibers and actors.
- <code>&nbsp;37121</code> ![](https://img.shields.io/github/last-commit/apache/dubbo) [Dubbo](https://github.com/apache/dubbo) - High-performance RPC framework.
- [Grizzly](https://javaee.github.io/grizzly/) - NIO framework. Used as a network layer in Glassfish.
- <code>&nbsp;&nbsp;9608</code> ![](https://img.shields.io/github/last-commit/grpc/grpc-java) [gRPC](https://github.com/grpc/grpc-java) - RPC framework based on protobuf and HTTP/2.
- <code>&nbsp;&nbsp;1711</code> ![](https://img.shields.io/github/last-commit/EsotericSoftware/kryonet) [KryoNet](https://github.com/EsotericSoftware/kryonet) - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo.
- [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
- [Netty](https://netty.io) - Framework for building high-performance network applications.
- <code>&nbsp;&nbsp;&nbsp;203</code> ![](https://img.shields.io/github/last-commit/airlift/drift) [Drift](https://github.com/airlift/drift) - Easy-to-use, annotation-based library for creating Thrift clients and serializable types.
- <code>&nbsp;&nbsp;&nbsp;735</code> ![](https://img.shields.io/github/last-commit/apple/servicetalk) [ServiceTalk](https://github.com/apple/servicetalk) - Framework built on Netty with APIs tailored to specific protocols and support for multiple programming paradigms.
- <code>&nbsp;&nbsp;2081</code> ![](https://img.shields.io/github/last-commit/hierynomus/sshj) [sshj](https://github.com/hierynomus/sshj) - Programmatically use SSH, SCP or SFTP.
- <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/marianobarrios/tls-channel) [TLS Channel](https://github.com/marianobarrios/tls-channel) - Implements a ByteChannel interface over SSLEngine, enabling easy-to-use (socket-like) TLS.
- [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly. (LGPL-2.1-only)
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/slub/urnlib) [urnlib](https://github.com/slub/urnlib) - Represent, parse and encode URNs, as in RFC 2141. (GPL-3.0-only)

### ORM

_APIs that handle the persistence of objects._

- [Apache Cayenne](https://cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
- <code>&nbsp;&nbsp;&nbsp;308</code> ![](https://img.shields.io/github/last-commit/domaframework/doma) [Doma](https://github.com/domaframework/doma) - Database access framework that verifies and generates source code at compile time using annotation processing as well as native SQL templates called two-way SQL.
- [Ebean](https://ebean.io) - Provides simple and fast data access.
- [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
- [Hibernate](http://hibernate.org/orm/) - Robust and widely used, with an active community. (LGPL-2.1-only)
- <code>&nbsp;17053</code> ![](https://img.shields.io/github/last-commit/mybatis/mybatis-3) [MyBatis](https://github.com/mybatis/mybatis-3) - Couples objects with stored procedures or SQL statements.
- <code>&nbsp;&nbsp;1168</code> ![](https://img.shields.io/github/last-commit/braisdom/ObjectiveSql) [ObjectiveSql](https://github.com/braisdom/ObjectiveSql) - ActiveRecord ORM for rapid development and convention over configuration.
- <code>&nbsp;&nbsp;&nbsp;276</code> ![](https://img.shields.io/github/last-commit/permazen/permazen) [Permazen](https://github.com/permazen/permazen) - Language-natural persistence layer.
- <code>&nbsp;&nbsp;&nbsp;406</code> ![](https://img.shields.io/github/last-commit/arnaudroger/SimpleFlatMapper) [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) - Simple database and CSV mapper.

### PaaS

_Java platform as a service._

- [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - AWS-based, with support for Tomcat and Jetty.
- [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - Serverless computation.
- [Google Cloud ![c]](https://cloud.google.com) - Google's cloud infrastructure.
- [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
- [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/) - Microsoft's cloud infrastructure.
- [OpenShift ![c]](https://www.openshift.com) - Provides additionally an on-premise solution.

### PDF

_Tools to help with PDF files._

- [Apache FOP](https://xmlgraphics.apache.org/fop/) - Creates PDFs from XSL-FO.
- [Apache PDFBox](https://pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
- [Dynamic Jasper](http://dynamicjasper.com) - Abstraction layer to JasperReports. (LGPL-3.0-only)
- <code>&nbsp;&nbsp;&nbsp;154</code> ![](https://img.shields.io/github/last-commit/dynamicreports/dynamicreports) [DynamicReports](https://github.com/dynamicreports/dynamicreports) - Simplifies JasperReports. (LGPL-3.0-only)
- [Eclipse BIRT](https://www.eclipse.org/birt) - Report engine for creating PDF and other formats (DOCX, XLSX, HTML, etc) using Eclipse-based visual editor.
- <code>&nbsp;&nbsp;1691</code> ![](https://img.shields.io/github/last-commit/flyingsaucerproject/flyingsaucer) [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) - XML/XHTML and CSS 2.1 renderer. (LGPL-2.1-or-later)
- [iText ![c]](https://itextpdf.com/en) - Creates PDF files programmatically.
- [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine. (LGPL-3.0-only)
- <code>&nbsp;&nbsp;1407</code> ![](https://img.shields.io/github/last-commit/danfickle/openhtmltopdf) [Open HTML to PDF](https://github.com/danfickle/openhtmltopdf) - Properly supports modern PDF standards based on flyingsaucer and Apache PDFBox.
- <code>&nbsp;&nbsp;2288</code> ![](https://img.shields.io/github/last-commit/LibrePDF/OpenPDF) [OpenPDF](https://github.com/LibrePDF/OpenPDF) - Open-source iText fork. (LGPL-3.0-only & MPL-2.0)
- <code>&nbsp;&nbsp;1363</code> ![](https://img.shields.io/github/last-commit/tabulapdf/tabula-java) [Tabula](https://github.com/tabulapdf/tabula-java) - Extracts tables from PDF files.

### Performance analysis

_Tools for performance analysis, profiling and benchmarking._

- [fastThread ![c]](https://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
- [GCeasy ![c]](https://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
- <code>&nbsp;&nbsp;1187</code> ![](https://img.shields.io/github/last-commit/jvm-profiling-tools/honest-profiler) [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) - Low-overhead, bias-free sampling profiler.
- <code>&nbsp;&nbsp;&nbsp;611</code> ![](https://img.shields.io/github/last-commit/giltene/jHiccup) [jHiccup](https://github.com/giltene/jHiccup) - Logs and records platform JVM stalls.
- <code>&nbsp;&nbsp;2625</code> ![](https://img.shields.io/github/last-commit/AdoptOpenJDK/jitwatch) [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) - Analyze the JIT compiler optimisations made by the HotSpot JVM.
- [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM. (GPL-2.0 only WITH Classpath-exception-2.0)
- <code>&nbsp;&nbsp;&nbsp;432</code> ![](https://img.shields.io/github/last-commit/LatencyUtils/LatencyUtils) [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) - Utilities for latency measurement and reporting.

### Platform

_Frameworks that are suites of multiple libraries encompassing several categories._

#### Apache Commons

- [BCEL](http://commons.apache.org/proper/commons-bcel/) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
- [BeanUtils](http://commons.apache.org/proper/commons-beanutils/) - Easy-to-use wrappers around the Java reflection and introspection APIs.
- [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/) - Redesign of Commons BeanUtils.
- [BSF](http://commons.apache.org/proper/commons-bsf/) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
- [Chain](http://commons.apache.org/proper/commons-chain/) - Chain of Responsibility pattern implementation.
- [ClassScan](http://commons.apache.org/sandbox/commons-classscan/) - Find Class interfaces, methods, fields, and annotations without loading.
- [CLI](http://commons.apache.org/proper/commons-cli/) - Command-line arguments parser.
- [CLI2](http://commons.apache.org/sandbox/commons-cli2/) - Redesign of Commons CLI.
- [Codec](http://commons.apache.org/proper/commons-codec/) - General encoding/decoding algorithms, e.g. phonetic, base64 or URL.
- [Collections](http://commons.apache.org/proper/commons-collections/) - Extends or augments the Java Collections Framework.
- [Compress](http://commons.apache.org/proper/commons-compress/) - Defines an API for working with tar, zip and bzip2 files.
- [Configuration](http://commons.apache.org/proper/commons-configuration/) - Reading of configuration/preferences files in various formats.
- [Convert](http://commons.apache.org/sandbox/commons-convert/) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
- [CSV](http://commons.apache.org/proper/commons-csv/) - Component for reading and writing comma separated value files.
- [Daemon](http://commons.apache.org/proper/commons-daemon/) - Alternative invocation mechanism for unix-daemon-like java code.
- [DBCP](http://commons.apache.org/proper/commons-dbcp/) - Database connection pooling services.
- [DbUtils](http://commons.apache.org/proper/commons-dbutils/) - JDBC helper library.
- [Digester](http://commons.apache.org/proper/commons-digester/) - XML-to-Java-object mapping utility.
- [Email](http://commons.apache.org/proper/commons-email/) - Library for sending e-mail from Java.
- [Exec](http://commons.apache.org/proper/commons-exec/) - API for dealing with external process execution and environment management in Java.
- [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - File upload capability for your servlets and web applications.
- [Finder](http://commons.apache.org/sandbox/commons-finder/) - Java library inspired by the UNIX find command.
- [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/) - Java library for working with flat data structures.
- [Functor](http://commons.apache.org/proper/commons-functor/) - Function that can be manipulated as an object, or an object representing a single, generic function.
- [Graph](http://commons.apache.org/sandbox/commons-graph/) - General purpose graph APIs and algorithms.
- [I18n](http://commons.apache.org/sandbox/commons-i18n/) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
- [Id](http://commons.apache.org/sandbox/commons-id/) - Id is a component used to generate identifiers.
- [Imaging](http://commons.apache.org/proper/commons-imaging/) - Image library.
- [IO](http://commons.apache.org/proper/commons-io/) - Collection of I/O utilities.
- [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/) - Continuation implementation to capture the state of the application.
- [JCI](http://commons.apache.org/proper/commons-jci/) - Java Compiler Interface.
- [JCS](http://commons.apache.org/proper/commons-jcs/) - Java Caching System.
- [Jelly](http://commons.apache.org/proper/commons-jelly/) - XML based scripting and processing engine.
- [Jexl](http://commons.apache.org/proper/commons-jexl/) - Expression language which extends the Expression Language of the JSTL.
- [JNet](http://commons.apache.org/sandbox/commons-jnet/) - JNet allows to use dynamically register url stream handlers through the java.net API.
- [JXPath](http://commons.apache.org/proper/commons-jxpath/) - Utilities for manipulating Java Beans using the XPath syntax.
- [Lang](http://commons.apache.org/proper/commons-lang/) - Provides extra functionality for classes in java.lang.
- [Logging](https://commons.apache.org/proper/commons-logging/) - Wrapper around a variety of logging API implementations.
- [Math](http://commons.apache.org/proper/commons-math/) - Lightweight, self-contained mathematics and statistics components.
- [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
- [Nabla](http://commons.apache.org/sandbox/commons-nabla/) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
- [Net](http://commons.apache.org/proper/commons-net/) - Collection of network utilities and protocol implementations.
- [OGNL](http://commons.apache.org/proper/commons-ognl/) - Object-graph navigation language.
- [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/) - Interface to signing and verifying data using OpenPGP.
- [Performance](http://commons.apache.org/sandbox/commons-performance/) - Small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
- [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.
- [Pool](http://commons.apache.org/proper/commons-pool/) - Generic object pooling component.
- [Proxy](http://commons.apache.org/proper/commons-proxy/) - Library for creating dynamic proxies.
- [RDF](https://commons.apache.org/proper/commons-rdf/) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
- [RNG](https://commons.apache.org/proper/commons-rng/) - Commons Rng provides implementations of pseudo-random numbers generators.
- [SCXML](http://commons.apache.org/proper/commons-scxml/) - Implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
- [Validator](http://commons.apache.org/proper/commons-validator/) - Framework to define validators and validation rules in an xml file.
- [VFS](http://commons.apache.org/proper/commons-vfs/) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
- [Weaver](http://commons.apache.org/proper/commons-weaver/) - Provides an easy way to enhance (weave) compiled bytecode.

#### Other

- [CUBA Platform](https://www.cuba-platform.com/) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
- <code>&nbsp;&nbsp;3397</code> ![](https://img.shields.io/github/last-commit/networknt/light-4j) [Light-4J](https://github.com/networknt/light-4j/) - Fast, lightweight and productive microservices framework with built-in <code>&nbsp;&nbsp;&nbsp;279</code> ![](https://img.shields.io/github/last-commit/networknt/light-oauth2) [security](https://github.com/networknt/light-oauth2/).
- <code>&nbsp;&nbsp;&nbsp;179</code> ![](https://img.shields.io/github/last-commit/OrienteerBAP/Orienteer) [Orienteer](https://github.com/OrienteerBAP/Orienteer/) - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications.
- [Spring](https://spring.io/projects/) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

_Libraries that help the management of operating system processes._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/vorburger/ch.vorburger.exec) [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) - Convenient API around Apache Commons Exec.
- <code>&nbsp;&nbsp;&nbsp;771</code> ![](https://img.shields.io/github/last-commit/zeroturnaround/zt-exec) [zt-exec](https://github.com/zeroturnaround/zt-exec) - Provides a unified API to Apache Commons Exec and ProcessBuilder.
- <code>&nbsp;&nbsp;&nbsp;105</code> ![](https://img.shields.io/github/last-commit/zeroturnaround/zt-process-killer) [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) - Stops processes started from Java or the system processes via PID.

### Reactive libraries

_Libraries for developing reactive applications._

- [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
- <code>&nbsp;&nbsp;4334</code> ![](https://img.shields.io/github/last-commit/reactive-streams/reactive-streams-jvm) [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) - Provides a standard for asynchronous stream processing with non-blocking backpressure.
- <code>&nbsp;&nbsp;4060</code> ![](https://img.shields.io/github/last-commit/reactor/reactor-core) [Reactor](https://github.com/reactor/reactor-core) - Library for building reactive fast-data applications.
- <code>&nbsp;45955</code> ![](https://img.shields.io/github/last-commit/ReactiveX/RxJava) [RxJava](https://github.com/ReactiveX/RxJava) - Allows for composing asynchronous and event-based programs using observable sequences.
- [vert.x](https://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

_Frameworks specifically for creating RESTful services._

- <code>&nbsp;&nbsp;8152</code> ![](https://img.shields.io/github/last-commit/dropwizard/dropwizard) [Dropwizard](https://github.com/dropwizard/dropwizard) - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
- [Elide](https://elide.io) - Opinionated framework for JSON- or GraphQL-APIs based on a JPA data model.
- [Jersey](https://jersey.github.io) - JAX-RS reference implementation.
- <code>&nbsp;&nbsp;&nbsp;935</code> ![](https://img.shields.io/github/last-commit/aol/micro-server) [Microserver](https://github.com/aol/micro-server) - Convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
- [Rapidoid](https://www.rapidoid.org) - Simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
- <code>&nbsp;&nbsp;2186</code> ![](https://img.shields.io/github/last-commit/linkedin/rest.li) [rest.li](https://github.com/linkedin/rest.li) - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.
- [RESTEasy](https://resteasy.github.io) - Fully certified and portable implementation of the JAX-RS specification.
- <code>&nbsp;&nbsp;&nbsp;933</code> ![](https://img.shields.io/github/last-commit/RestExpress/RestExpress) [RestExpress](https://github.com/RestExpress/RestExpress) - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance.
- <code>&nbsp;&nbsp;&nbsp;627</code> ![](https://img.shields.io/github/last-commit/restlet/restlet-framework-java) [Restlet Framework](https://github.com/restlet/restlet-framework-java) - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API.
- [Spark](http://sparkjava.com) - Sinatra inspired framework.
- [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
- <code>&nbsp;&nbsp;1802</code> ![](https://img.shields.io/github/last-commit/springdoc/springdoc-openapi) [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) - Automates the generation of API documentation using Spring Boot projects.
- [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

_Libraries for scientific computing, analysis and visualization._

- [BioJava](https://biojava.org/) - Facilitates processing biological data by providing algorithms, file format parsers, sequencing and 3D visualization commonly used in bioinformatics.
- <code>&nbsp;&nbsp;&nbsp;333</code> ![](https://img.shields.io/github/last-commit/GSI-CS-CO/chart-fx) [Chart-FX](https://github.com/GSI-CS-CO/chart-fx) - Scientific charting library with focus on performance optimised real-time data visualisation at 25 Hz update rates for large data sets.
- [DataMelt](https://jwork.org/dmelt/) - Environment for scientific computation, data analysis and data visualization. (GPL-3.0-or-later)
- <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/Erdos-Graph-Framework/Erdos) [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) - Modular, light and easy graph framework for theoretic algorithms.
- [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
- [JFreeChart](http://www.jfree.org/jfreechart/) - 2D chart library for Swing, JavaFX and server-side applications. (LGPL-2.1-only)
- <code>&nbsp;&nbsp;2086</code> ![](https://img.shields.io/github/last-commit/jgrapht/jgrapht) [JGraphT](https://github.com/jgrapht/jgrapht) - Graph library that provides mathematical graph-theory objects and algorithms.
- <code>&nbsp;&nbsp;&nbsp;632</code> ![](https://img.shields.io/github/last-commit/jgraph/jgraphx) [JGraphX](https://github.com/jgraph/jgraphx) - Library for visualizing (mainly Swing) and interacting with node-edge graphs.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/logic-ng/LogicNG) [LogicNG](https://github.com/logic-ng/LogicNG) - Library for creating, manipulating and solving Boolean and Pseudo-Boolean formulas.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/MinesJTK/jtk) [Mines Java Toolkit](https://github.com/MinesJTK/jtk) - Library for geophysical scientific computation, visualization and digital signal analysis.
- <code>&nbsp;&nbsp;&nbsp;218</code> ![](https://img.shields.io/github/last-commit/zavtech/morpheus-core) [Morpheus](https://github.com/zavtech/morpheus-core) - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;89</code> ![](https://img.shields.io/github/last-commit/jfree/orson-charts) [Orson-Charts](https://github.com/jfree/orson-charts) - Generates a wide variety of 3D charts that can be displayed with Swing and JavaFX or exported to PDF, SVG, PNG and JPEG. (GPL-3.0-only)
- <code>&nbsp;&nbsp;2882</code> ![](https://img.shields.io/github/last-commit/jtablesaw/tablesaw) [Tablesaw](https://github.com/jtablesaw/tablesaw) - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data.
- <code>&nbsp;&nbsp;1264</code> ![](https://img.shields.io/github/last-commit/knowm/XChart) [XChart](https://github.com/knowm/XChart) - Light-weight library for plotting data. Many customizable chart types are available.

### Search

_Engines that index documents for search and analysis._

- [Apache Lucene](https://lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
- [Apache Solr](https://lucene.apache.org/solr/) - Enterprise search engine optimized for high-volume traffic.
- [Elasticsearch](https://www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;46</code> ![](https://img.shields.io/github/last-commit/haeungun/indexer4j) [Indexer4j](https://github.com/haeungun/indexer4j) - Simple and light full text indexing and searching library.

### Security

_Libraries that handle security, authentication, authorization or session management._

- [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
- [Cryptomator](https://cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud. (GPL-3.0-only)
- <code>&nbsp;&nbsp;&nbsp;207</code> ![](https://img.shields.io/github/last-commit/hdiv/hdiv) [Hdiv](https://github.com/hdiv/hdiv) - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks.
- <code>&nbsp;&nbsp;8246</code> ![](https://img.shields.io/github/last-commit/jwtk/jjwt) [jjwt](https://github.com/jwtk/jjwt) - JSON web token for Java and Android.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/BastiaanJansen/jwt-java) [jwt-java](https://github.com/BastiaanJansen/jwt-java) - Easily create and parse JSON Web Tokens and create customized JWT validators using a fluent API.
- <code>&nbsp;&nbsp;&nbsp;139</code> ![](https://img.shields.io/github/last-commit/auth0/jwks-rsa-java) [Jwks RSA](https://github.com/auth0/jwks-rsa-java) - JSON Web Key Set parser.
- <code>&nbsp;&nbsp;&nbsp;204</code> ![](https://img.shields.io/github/last-commit/abstractj/kalium) [Kalium](https://github.com/abstractj/kalium) - Binding for the Networking and Cryptography (NaCl) library.
- [Keycloak](https://www.keycloak.org) - Integrated SSO and IDM for browser apps and RESTful web services.
- <code>&nbsp;&nbsp;2486</code> ![](https://img.shields.io/github/last-commit/square/keywhiz) [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets.
- <code>&nbsp;&nbsp;&nbsp;228</code> ![](https://img.shields.io/github/last-commit/GoSimpleLLC/nbvcxz) [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) - Advanced password strength estimation.
- [OACC](http://oaccframework.org) - Provides permission-based authorization services.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/BastiaanJansen/OTP-Java) [OTP-Java](https://github.com/BastiaanJansen/OTP-Java) - One-time password generator library according to RFC 4226 (HOTP) and RFC 6238 (TOTP).
- <code>&nbsp;&nbsp;2136</code> ![](https://img.shields.io/github/last-commit/pac4j/pac4j) [pac4j](https://github.com/pac4j/pac4j) - Security engine.
- <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/Password4j/password4j) [Password4j](https://github.com/Password4j/password4j) - User-friendly cryptographic library that supports Argon2, Bcrypt, Scrypt, PBKDF2 and various other cryptographic hash functions.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;42</code> ![](https://img.shields.io/github/last-commit/tersesystems/securitybuilder) [SecurityBuilder](https://github.com/tersesystems/securitybuilder) - Fluent Builder API for JCA and JSSE classes and especially X.509 certificates.
- <code>&nbsp;&nbsp;&nbsp;219</code> ![](https://img.shields.io/github/last-commit/Hakky54/sslcontext-kickstart) [SSLContext-Kickstart](https://github.com/Hakky54/sslcontext-kickstart) - High-level SSL context builder for configuring HTTP clients with SSL/TLS.
- <code>&nbsp;&nbsp;1495</code> ![](https://img.shields.io/github/last-commit/cossacklabs/themis) [Themis](https://github.com/cossacklabs/themis) - Multi-platform high-level cryptographic library provides easy-to-use encryption for protecting sensitive data: secure messaging with forward secrecy, secure data storage (AES256GCM); suits for building end-to-end encrypted applications.
- <code>&nbsp;12273</code> ![](https://img.shields.io/github/last-commit/google/tink) [Tink](https://github.com/google/tink) - Provides a simple and misuse-proof API for common cryptographic tasks.

### Serialization

_Libraries that handle serialization with high efficiency._

- <code>&nbsp;17739</code> ![](https://img.shields.io/github/last-commit/google/flatbuffers) [FlatBuffers](https://github.com/google/flatbuffers) - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.
- <code>&nbsp;&nbsp;1449</code> ![](https://img.shields.io/github/last-commit/RuedigerMoeller/fast-serialization) [FST](https://github.com/RuedigerMoeller/fast-serialization) - JDK-compatible, high-performance object graph serialization.
- <code>&nbsp;&nbsp;5371</code> ![](https://img.shields.io/github/last-commit/EsotericSoftware/kryo) [Kryo](https://github.com/EsotericSoftware/kryo) - Fast and efficient object graph serialization framework.
- <code>&nbsp;&nbsp;1272</code> ![](https://img.shields.io/github/last-commit/msgpack/msgpack-java) [MessagePack](https://github.com/msgpack/msgpack-java) - Efficient binary serialization format.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;13</code> ![](https://img.shields.io/github/last-commit/marcospassos/java-php-serializer) [PHP Serializer](https://github.com/marcospassos/java-php-serializer) - Serializing objects in the PHP serialization format.

### Server

_Servers specifically used to deploy applications._

- [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
- [Apache TomEE](https://tomee.apache.org) - Tomcat plus Java EE.
- [Jetty](https://www.eclipse.org/jetty/) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
- <code>&nbsp;&nbsp;6291</code> ![](https://img.shields.io/github/last-commit/NanoHttpd/nanohttpd) [nanohttpd](https://github.com/NanoHttpd/nanohttpd) - Tiny, easily embeddable HTTP server.
- [WildFly](https://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support. (LGPL-2.1-only)

### Template Engine

_Tools that substitute expressions in a template._

- [Freemarker](https://freemarker.apache.org) - Library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data.
- [Handlebars.java](https://jknack.github.io/handlebars.java/) - Logicless and semantic Mustache templates.
- <code>&nbsp;&nbsp;&nbsp;702</code> ![](https://img.shields.io/github/last-commit/neuland/jade4j) [Jade4J](https://github.com/neuland/jade4j) - Implementation of Pug (formerly known as Jade).
- <code>&nbsp;&nbsp;&nbsp;&nbsp;16</code> ![](https://img.shields.io/github/last-commit/verhas/jamal) [Jamal](https://github.com/verhas/jamal) - Extendable template engine embedded into Maven/JavaDoc, supporting multiple extensions (Groovy, Ruby, JavaScript, JShell, PlantUml) with support for snippet handling.
- <code>&nbsp;&nbsp;&nbsp;367</code> ![](https://img.shields.io/github/last-commit/casid/jte) [jte](https://github.com/casid/jte) - Compiles to classes, and uses an easy syntax, several features to make development easier and provides fast execution and a small footprint.
- <code>&nbsp;&nbsp;&nbsp;298</code> ![](https://img.shields.io/github/last-commit/jtwig/jtwig) [Jtwig](https://github.com/jtwig/jtwig) - Modular, configurable and fully tested template engine.
- [Pebble](https://pebbletemplates.io) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
- <code>&nbsp;&nbsp;&nbsp;652</code> ![](https://img.shields.io/github/last-commit/fizzed/rocker) [Rocker](https://github.com/fizzed/rocker) - Optimized, memory efficient and speedy template engine producing statically typed, plain objects.
- <code>&nbsp;&nbsp;&nbsp;791</code> ![](https://img.shields.io/github/last-commit/antlr/stringtemplate4) [StringTemplate](https://github.com/antlr/stringtemplate4) - Template engine for generating source code, web pages, emails, or any other formatted text output.
- [Thymeleaf](https://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

_Tools that test from model to the view._

#### Asynchronous

_Tools that simplify testing asynchronous services._

- <code>&nbsp;&nbsp;2963</code> ![](https://img.shields.io/github/last-commit/awaitility/awaitility) [Awaitility](https://github.com/awaitility/awaitility) - DSL for synchronizing asynchronous operations.
- <code>&nbsp;&nbsp;&nbsp;395</code> ![](https://img.shields.io/github/last-commit/jhalterman/concurrentunit) [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) - Toolkit for testing multi-threaded and asynchronous applications.
- [GreenMail](http://www.icegreen.com/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL. (GPL-2.0-only)
- <code>&nbsp;&nbsp;&nbsp;141</code> ![](https://img.shields.io/github/last-commit/SpectoLabs/hoverfly-java) [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services.
- <code>&nbsp;&nbsp;5840</code> ![](https://img.shields.io/github/last-commit/intuit/karate) [Karate](https://github.com/intuit/karate) - DSL that combines API test-automation, mocks and performance-testing making testing REST/HTTP services easy.
- <code>&nbsp;&nbsp;5801</code> ![](https://img.shields.io/github/last-commit/rest-assured/rest-assured) [REST Assured](https://github.com/rest-assured/rest-assured) - DSL for easy testing of REST/HTTP services.

#### BDD

_Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD._

- <code>&nbsp;&nbsp;2432</code> ![](https://img.shields.io/github/last-commit/cucumber/cucumber-jvm) [Cucumber](https://github.com/cucumber/cucumber-jvm) - Provides a way to describe features in a plain language which customers can understand.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;98</code> ![](https://img.shields.io/github/last-commit/ctco/cukes) [Cukes-REST](https://github.com/ctco/cukes) - Collection of Gherkin steps for REST-service testing using Cucumber.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;45</code> ![](https://img.shields.io/github/last-commit/j8spec/j8spec) [J8Spec](https://github.com/j8spec/j8spec) - Follows a Jasmine-like syntax.
- [JBehave](https://jbehave.org) - Extensively configurable framework that describes stories.
- [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.
- <code>&nbsp;&nbsp;&nbsp;248</code> ![](https://img.shields.io/github/last-commit/RichardWarburton/lambda-behave) [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English.
- <code>&nbsp;&nbsp;&nbsp;615</code> ![](https://img.shields.io/github/last-commit/serenity-bdd/serenity-core) [Serenity BDD](https://github.com/serenity-bdd/serenity-core) - Automated Acceptance testing and reporting library that works with Cucumber, JBehave and JUnit to make it easier to write high quality executable specifications.

#### Fixtures

_Everything related to the creation and handling of random data._

- <code>&nbsp;&nbsp;&nbsp;111</code> ![](https://img.shields.io/github/last-commit/keepcosmos/beanmother) [Beanmother](https://github.com/keepcosmos/beanmother) - Sets up beans from YAML fixtures.
- <code>&nbsp;&nbsp;&nbsp;409</code> ![](https://img.shields.io/github/last-commit/six2six/fixture-factory) [Fixture Factory](https://github.com/six2six/fixture-factory) - Generates fake objects from a template.
- <code>&nbsp;&nbsp;&nbsp;694</code> ![](https://img.shields.io/github/last-commit/Devskiller/jfairy) [jFairy](https://github.com/Devskiller/jfairy) - Fake data generator.
- <code>&nbsp;&nbsp;&nbsp;162</code> ![](https://img.shields.io/github/last-commit/randomizedtesting/randomizedtesting) [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.
- <code>&nbsp;&nbsp;3438</code> ![](https://img.shields.io/github/last-commit/DiUS/java-faker) [Java Faker](https://github.com/DiUS/java-faker) - Port of Ruby's fake data generator.

#### Frameworks

_Provide environments to run tests for a specific use case._

- <code>&nbsp;&nbsp;2139</code> ![](https://img.shields.io/github/last-commit/TNG/ArchUnit) [ArchUnit](https://github.com/TNG/ArchUnit) - Test library for specifying and asserting architecture rules.
- [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
- [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
- [Citrus](https://citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
- [Gatling](https://gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
- [JUnit](https://junit.org/junit5/) - Common testing framework.
- [jqwik](https://jqwik.net) - Engine for property-based testing built on JUnit 5.
- <code>&nbsp;&nbsp;&nbsp;915</code> ![](https://img.shields.io/github/last-commit/DiUS/pact-jvm) [Pact JVM](https://github.com/DiUS/pact-jvm) - Consumer-driven contract testing.
- [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

_Libraries that provide custom matchers._

- [AssertJ](https://joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
- [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Matchers that can be combined to create flexible expressions of intent.
- [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
- [Truth](https://truth.dev) - Google's fluent assertion and proposition framework.
- <code>&nbsp;&nbsp;&nbsp;256</code> ![](https://img.shields.io/github/last-commit/xmlunit/xmlunit) [XMLUnit](https://github.com/xmlunit/xmlunit) - Simplifies testing for XML output.

#### Miscellaneous

_Other stuff related to testing._

- <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/Hakky54/console-captor) [ConsoleCaptor](https://github.com/Hakky54/console-captor) - Captures console output for unit testing purposes.
- <code>&nbsp;&nbsp;&nbsp;232</code> ![](https://img.shields.io/github/last-commit/TNG/junit-dataprovider) [junit-dataprovider](https://github.com/TNG/junit-dataprovider) - TestNG-like data provider/runner for JUnit.
- <code>&nbsp;&nbsp;&nbsp;178</code> ![](https://img.shields.io/github/last-commit/Hakky54/log-captor) [LogCaptor](https://github.com/Hakky54/log-captor) - Captures log entries for unit testing purposes.
- <code>&nbsp;&nbsp;&nbsp;227</code> ![](https://img.shields.io/github/last-commit/MutabilityDetector/MutabilityDetector) [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) - Reports whether instances of a given class are immutable.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;71</code> ![](https://img.shields.io/github/last-commit/nidi3/raml-tester) [raml-tester](https://github.com/nidi3/raml-tester) - Tests if a request/response matches a given RAML definition.
- <code>&nbsp;&nbsp;5839</code> ![](https://img.shields.io/github/last-commit/testcontainers/testcontainers-java) [TestContainers](https://github.com/testcontainers/testcontainers-java) - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.
- [pojo-tester](https://www.pojo.pl) - Automatically performs tests on basic POJO methods. (LGPL-3.0-only)

#### Mocking

_Tools which mock collaborators to help testing single, isolated units._

- [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
- <code>&nbsp;12785</code> ![](https://img.shields.io/github/last-commit/mockito/mockito) [Mockito](https://github.com/mockito/mockito) - Mocking framework that lets you write tests with a clean and simple API.
- [MockServer](https://www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
- <code>&nbsp;&nbsp;3922</code> ![](https://img.shields.io/github/last-commit/dreamhead/moco) [Moco](https://github.com/dreamhead/moco) - Concise web services for stubs and mocks.
- <code>&nbsp;&nbsp;3777</code> ![](https://img.shields.io/github/last-commit/powermock/powermock) [PowerMock](https://github.com/powermock/powermock) - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers.
- [WireMock](http://wiremock.org) - Stubs and mocks web services.

### Utility

_Libraries which provide general utility functions._

- <code>&nbsp;28876</code> ![](https://img.shields.io/github/last-commit/alibaba/arthas) [Arthas](https://github.com/alibaba/arthas) - Allows to troubleshoot production issues for applications without modifying code or restarting servers.
- <code>&nbsp;&nbsp;1449</code> ![](https://img.shields.io/github/last-commit/vladimir-bukhtoyarov/bucket4j) [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) - Rate limiting library based on token-bucket algorithm.
- <code>&nbsp;&nbsp;&nbsp;655</code> ![](https://img.shields.io/github/last-commit/yegor256/cactoos) [cactoos](https://github.com/yegor256/cactoos) - Collection of object-oriented primitives.
- [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others. (LGPL-2.1-or-later)
- <code>&nbsp;&nbsp;1275</code> ![](https://img.shields.io/github/last-commit/PatMartin/Dex) [Dex](https://github.com/PatMartin/Dex) - Java/JavaFX tool capable of powerful ETL and data visualization.
- <code>&nbsp;&nbsp;1629</code> ![](https://img.shields.io/github/last-commit/embulk/embulk) [Embulk](https://github.com/embulk/embulk) - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
- <code>&nbsp;&nbsp;&nbsp;&nbsp;21</code> ![](https://img.shields.io/github/last-commit/vorburger/ch.vorburger.fswatch) [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService.
- <code>&nbsp;&nbsp;4735</code> ![](https://img.shields.io/github/last-commit/gephi/gephi) [Gephi](https://github.com/gephi/gephi) - Cross-platform for visualizing and manipulating large graph networks. (GPL-3.0-only)
- <code>&nbsp;44207</code> ![](https://img.shields.io/github/last-commit/google/guava) [Guava](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.
- [JADE](http://jade.tilab.com) - Framework and environment for building and debugging multi-agent systems. (LGPL-2.0-only)
- [Java Diff Utils](https://java-diff-utils.github.io/java-diff-utils/) - Utilities for text or data comparison and patching.
- <code>&nbsp;&nbsp;2556</code> ![](https://img.shields.io/github/last-commit/VerbalExpressions/JavaVerbalExpressions) [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) - Library that helps with constructing difficult regular expressions.
- [JGit](https://www.eclipse.org/jgit/) - Lightweight, pure Java library implementing the Git version control system.
- <code>&nbsp;&nbsp;&nbsp;659</code> ![](https://img.shields.io/github/last-commit/minio/minio-java) [minio-java](https://github.com/minio/minio-java) - Provides simple APIs to access any Amazon S3-compatible object storage server.
- [Protégé](https://protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.
- <code>&nbsp;&nbsp;&nbsp;380</code> ![](https://img.shields.io/github/last-commit/javadev/underscore-java) [Underscore-java](https://github.com/javadev/underscore-java) - Port of Underscore.js functions.

### Version Managers

_Utilities that help create the development shell environment and switch between different Java versions._

- <code>&nbsp;&nbsp;2287</code> ![](https://img.shields.io/github/last-commit/shyiko/jabba) [jabba](https://github.com/shyiko/jabba) - Java Version Manager inspired by nvm. Supports macOS, Linux and Windows.
- <code>&nbsp;&nbsp;4196</code> ![](https://img.shields.io/github/last-commit/jenv/jenv) [jenv](https://github.com/jenv/jenv) - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and macOS.
- <code>&nbsp;&nbsp;4599</code> ![](https://img.shields.io/github/last-commit/sdkman/sdkman-cli) [SDKMan](https://github.com/sdkman/sdkman-cli) - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.

### Web Crawling

_Libraries that analyze the content of websites._

- [Apache Nutch](https://nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
- <code>&nbsp;&nbsp;4256</code> ![](https://img.shields.io/github/last-commit/yasserg/crawler4j) [Crawler4j](https://github.com/yasserg/crawler4j) - Simple and lightweight web crawler.
- [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
- [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.
- <code>&nbsp;10329</code> ![](https://img.shields.io/github/last-commit/code4craft/webmagic) [webmagic](https://github.com/code4craft/webmagic) - Scalable crawler with downloading, url management, content extraction and persistent.

### Web Frameworks

_Frameworks that handle the communication between the layers of a web application._

- [ActiveJ](https://activej.io) - Lightweight asynchronous framework built from the ground up for developing high-performance web applications.
- [Apache Tapestry](https://tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
- [Apache Wicket](https://wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
- <code>&nbsp;&nbsp;5603</code> ![](https://img.shields.io/github/last-commit/lets-blade/blade) [Blade](https://github.com/lets-blade/blade) - Lightweight, modular framework that aims to be elegant and simple.
- [Bootique](https://bootique.io) - Minimally opinionated framework for runnable apps.
- [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
- [Jooby](http://www.jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
- [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
- [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
- [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
- [PrimeFaces](https://www.primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
- [Ratpack](https://ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
- <code>&nbsp;&nbsp;&nbsp;717</code> ![](https://img.shields.io/github/last-commit/yegor256/takes) [Takes](https://github.com/yegor256/takes) - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability.
- [Vaadin](https://vaadin.com) - Event-driven framework that uses standard web components. Server-side architecture with Ajax on the client side.

### Workflow Orchestration Engines

- [Cadence](https://cadenceworkflow.io) - Stateful code platform from Uber.
- <code>&nbsp;&nbsp;5108</code> ![](https://img.shields.io/github/last-commit/flowable/flowable-engine) [flowable](https://github.com/flowable/flowable-engine) - Compact and efficient workflow and business process management platform.
- [Temporal](https://temporal.io) - Microservice orchestration platform, forked from Cadence but gRPC based.

## Resources

### Related Awesome Lists

_Awesome Lists related to the Java & JVM ecosystem._

- <code>&nbsp;&nbsp;&nbsp;296</code> ![](https://img.shields.io/github/last-commit/gunnarmorling/awesome-annotation-processing) [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing)
- <code>&nbsp;&nbsp;&nbsp;332</code> ![](https://img.shields.io/github/last-commit/neomatrix369/awesome-graal) [Awesome Graal](https://github.com/neomatrix369/awesome-graal)
- <code>&nbsp;&nbsp;&nbsp;378</code> ![](https://img.shields.io/github/last-commit/ksoichiro/awesome-gradle) [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle)
- <code>&nbsp;&nbsp;2582</code> ![](https://img.shields.io/github/last-commit/mhrimaz/AwesomeJavaFX) [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX)
- <code>&nbsp;&nbsp;1758</code> ![](https://img.shields.io/github/last-commit/deephacks/awesome-jvm) [Awesome JVM](https://github.com/deephacks/awesome-jvm)
- <code>&nbsp;10935</code> ![](https://img.shields.io/github/last-commit/mfornos/awesome-microservices) [Awesome Microservices](https://github.com/mfornos/awesome-microservices)
- <code>&nbsp;&nbsp;3012</code> ![](https://img.shields.io/github/last-commit/marmelab/awesome-rest) [Awesome REST](https://github.com/marmelab/awesome-rest)
- <code>&nbsp;&nbsp;&nbsp;775</code> ![](https://img.shields.io/github/last-commit/christian-bromann/awesome-selenium) [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium)
- <code>&nbsp;&nbsp;1423</code> ![](https://img.shields.io/github/last-commit/ciandcd/awesome-ciandcd) [ciandcd](https://github.com/ciandcd/awesome-ciandcd)
- <code>&nbsp;&nbsp;5196</code> ![](https://img.shields.io/github/last-commit/Vedenin/useful-java-links) [Useful Java Links](https://github.com/Vedenin/useful-java-links)
- <code>&nbsp;&nbsp;1028</code> ![](https://img.shields.io/github/last-commit/code-review-checklists/java-concurrency) [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency)
- <code>&nbsp;&nbsp;2640</code> ![](https://img.shields.io/github/last-commit/s4kibs4mi/java-developer-roadmap) [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap)

### Communities

_Active discussions._

- [r/java](https://www.reddit.com/r/java/) - Subreddit for the Java community.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.
- [VirtualJUG](https://virtualjug.com) - Virtual Java User Group.

### Frontends

_Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one._

- [java.libhunt.com](https://java.libhunt.com)

### Influential Books

_Books that made a big impact and are still worth reading._

- [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
- [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
- [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

_Something to look at or listen to while programming._

- [A Bootiful Podcast](https://bootifulpodcast.fm)
- [Inside Java](https://inside.java/podcast) (Official)
- [Java Off Heap](http://www.javaoffheap.com)
- [The Java Council](https://virtualjug.com/#podcast)
- [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### People

#### Twitter

_Active accounts to follow. Descriptions from Twitter._

- [Adam Bien](https://twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
- [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
- [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
- [Arun Gupta](https://twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
- [Brian Goetz](https://twitter.com/BrianGoetz) - Java Language Architect at Oracle.
- [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
- [Chris Richardson](https://twitter.com/crichardson) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, \*POJOs in Action- author.
- [Ed Burns](https://twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
- [Eugen Paraschiv](https://twitter.com/baeldung) - Author of the Spring Security Course.
- [Heinz Kabutz](https://twitter.com/heinzkabutz) - Java Champion, speaker, author of The Java Specialists' Newsletter, concurrency performance expert.
- [Holly Cummins](https://twitter.com/holly_cummins) - Technical Lead of IBM London's Bluemix Garage, Java Champion, developer, author, JavaOne rockstar.
- [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
- [Java EE](https://twitter.com/Java_EE) - Official Java EE Twitter account.
- [Java Magazine](https://twitter.com/Oraclejavamag) - Official Java Magazine account.
- [Java](https://twitter.com/java) - Official Java Twitter account.
- [Javin Paul](https://twitter.com/javinpaul) - Well-known Java blogger.
- [Josh Long](https://twitter.com/starbuxman) - Spring Advocate at Pivotal, author of O'Reilly's Cloud Native Java- and Building Microservices with Spring Boot, JavaOne Rock Star.
- [Lukas Eder](https://twitter.com/lukaseder) - Java Champion, speaker, Founder and CEO Data Geekery (jOOQ).
- [Mani Sarkar](https://twitter.com/theNeomatrix369) - Java champion, Polyglot, Software Crafter involved with @graalvm, AI/ML/DL, Data Science, Developer communities, speaker & blogger. Creator of couple of awesome lists like this one.
- [Mario Fusco](https://twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
- [Mark Heckler](https://twitter.com/MkHeck) - Pivotal Principal Technologist and Developer Advocate, conference speaker, published author, and Java Champion, focusing on Internet of Things and the cloud.
- [Mark Reinhold](https://twitter.com/mreinhold) - Chief Architect, Java Platform Group, Oracle.
- [Markus Eisele](https://twitter.com/myfear) - Java EE evangelist, Red Hat.
- [Martijn Verburg](https://twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
- [Martin Thompson](https://twitter.com/mjpt777) - Pasty faced performance gangster.
- [Monica Beckwith](https://twitter.com/mon_beck) - Performance consultant, JavaOne Rock Star.
- [OpenJDK](https://twitter.com/OpenJDK) - Official OpenJDK account.
- [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
- [Randy Shoup](https://twitter.com/randyshoup) - Stitch Fix VP Engineering, speaker, JavaOne Rock Star.
- [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
- [Sander Mak](https://twitter.com/Sander_Mak) - Java Champion, author.
- [Simon Maple](https://twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
- [Spencer Gibb](https://twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
- [Stephen Colebourne](https://twitter.com/jodastephen) - Java Champion, speaker.
- [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.
- [Venkat Subramaniam](https://twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.
- [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) - Java Champion working on Hypersistence Optimizer, database aficionado, author of High-Performance Java Persistence book.

#### Other

- [Groundbreakers](https://apexapps.oracle.com/pls/apex/f?p=119297:3::::::) - Oracle ACEs, Groundbreaker Ambassadors and Java Champions.

### Websites

_Sites to read._

- [Baeldung](https://www.baeldung.com)
- [Dzone](https://dzone.com)
- [foojay.io](https://foojay.io)
- [Google Java Style](https://google.github.io/styleguide/javaguide.html)
- [InfoQ](https://www.infoq.com)
- [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
- [Java, SQL, and jOOQ](https://blog.jooq.org)
- [Java.net](https://community.oracle.com/community/java)
- [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
- [JavaWorld](https://www.javaworld.com)
- [JAXenter](https://jaxenter.com)
- [RebelLabs](https://zeroturnaround.com/rebellabs)
- [OverOps Blog](https://blog.overops.com)
- [TheServerSide.com](http://www.theserverside.com)
- [Vanilla Java](https://vanilla-java.github.io)
- [Voxxed](https://www.voxxed.com)

## Contributing

Contributions are very welcome!

Please have a look at the <code>&nbsp;31854</code> ![](https://img.shields.io/github/last-commit/akullpp/awesome-java) [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) guidelines and <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/akullpp/awesome-java-lint) [the validation tools](https://github.com/akullpp/awesome-java-lint).

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg
