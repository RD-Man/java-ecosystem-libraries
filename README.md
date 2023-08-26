# Java生态资源大全

本项目统计了Java生态圈中的各种资源，包括库、框架、学习网站，并且按照其所属的领域进行了分类，方便大家查找。

## 目录

- [Web框架](#web-framework)
- [Rest框架](#rest-framework)
- [微服务框架](#microservice-framework)
- [微服务工具](#microservice-tool)
- [ORM框架](#orm-framework)
- [脚手架](#scaffold)
- [单元测试](#unit-test)
- [断言库](#assertions)
- [Mock框架](#mocks)
- [Mock工具](#mocks-lib)
- [数据Mock](#mocks-data)
- [BDD框架](#bdd)
- [自动化工具](#automation)
- [负载测试](#load)
- [测试库](#test-lib)
- [Java IDE](#ide)
- [构建工具](#build)
- [GUI程序](#gui)
- [开源JDK](#jdk)
- [性能分析](#profiler)
- [APM监控工具](#apm)
- [云原生](#cloud-native)
- [工具库](#utils)
- [依赖注入](#di)
- [AOP](#aop)
- [日志库](#log)
- [任务调度](#job)
- [业务流 & 规则引擎](#bpm)
- [响应式库](#reactive)
- [缓存库](#cache)
- [大数据框架](#bigdata)
- [PDF库](#pdf)
- [Excel库](#excel)
- [CSV库](#csv)
- [HTTP客户端库](#httpclient)
- [WebServer](#webserver)
- [Jakarta EE实现](#jakartaee)
- [RPC框架](#rpc)
- [消息中间件](#message)
- [图数据库](#graph-db)
- [嵌入式数据库](#embedded-db)
- [NoSQL数据库 & 其他](#nosql-db)
- [数据库连接池](#db-conn)
- [机器学习](#ml)
- [自然语言处理](#nlp)
- [深度学习](#dl)
- [遗传算法](#genetic)
- [专家系统](#expert-system)
- [并发编程](#concurrency)
- [安全](#security)
- [事务](#transaction)
- [模板引擎](#template-engine)
- [JSON库](#json)
- [Bean映射](#mapper)
- [CLI工具](#cli)
- [集合库](#collection)
- [函数式编程](#functional)
- [字节码操作](#bytecode)
- [图像处理](#image)
- [爬虫](#crawler)
- [数据处理](#data)
- [注解处理器](#annotation-processor)
- [事件总线](#event-bus)
- [Swagger](#swagger)
- [集群管理](#cluster-management)
- [代码分析](#code-analysis)
- [Maven插件](#maven)
- [注册中心](#registry)
- [限流库](#rate-limiting)
- [网关](#gateway)
- [SDK](#sdk)
- [区块链](#blockchain)
- [以太坊](#ethereum)
- [比特币](#bitcoin)
- [Spring生态](#spring)
- [Raft算法](#raft)
- [Paxos算法](#paxos)
- [分布式锁](#distributed-lock)

<h2 id="web-framework">Web框架</h2>

* [Spring MVC](https://github.com/spring-projects/spring-framework/tree/main/spring-webmvc)：Spring MVC是Spring生态中的Web框架。
* [Spring Boot](https://github.com/spring-projects/spring-boot)：用于快速开发Spring应用的脚手架框架。
* [Solon](https://github.com/noear/solon)：国产的轻量级Java Web框架。
* [Play](https://github.com/playframework/playframework)：Play框架结合了生产力和性能，可以轻松使用Java和Scala构建可扩展的Web应用程序。
* [Blade](https://github.com/lets-blade/blade)：国产的轻量级Web框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [Javalin](https://github.com/javalin/javalin)：简单而现代的Java和Kotlin Web框架。
* [Hilla](https://github.com/vaadin/hilla)：Java全栈框架，支持React和Lit/Web组件。
* [Ninja](https://github.com/ninjaframework/ninja)：Java的全栈Web框架。
* [Sofa-Boot](https://github.com/sofastack/sofa-boot)：蚂蚁开发的Spring Boot增强并与其完全兼容的框架，提供就绪性检查、类隔离等功能。
* [Grails](https://github.com/grails/grails-core)：Grails是一个用于使用Groovy编程语言构建Web应用程序的框架。
* [Vaadin](https://github.com/vaadin/framework)：Vaadin是用于现代Java Web应用程序的Java框架。
* [Jooby](https://github.com/jooby-project/jooby)：适用于Java和Kotlin的模块化Web框架。
* [Pippo](https://github.com/pippo-java/pippo)：Java开源的微型Web框架。
* [Spark](https://github.com/perwendel/spark)：一个简单的、富有表现力的Java Web框架。
* [Wicket](https://github.com/apache/wicket)：基于组件的Java Web框架。
* [Rife2](https://github.com/rife2/rife2)：全栈、无声明框架，可使用现代Java快速轻松地创建Web应用程序。
* [Tapestry](https://github.com/apache/tapestry-5)：Tapestry是一个面向组件的Java Web应用程序框架。
* [Ratpack](https://github.com/ratpack/ratpack)：一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [GWT](https://github.com/gwtproject/gwt)：快速构建和维护复杂但性能高的JavaScript前端应用程序的工具集。
* [Struts](https://github.com/apache/struts)：Apache Struts框架是一个用于创建Java Web应用程序的免费开源解决方案。
* [JavaLite](https://github.com/javalite/javalite)：一系列工具的集合框架。
* [Vraptor4](https://github.com/caelum/vraptor4)：一个基于Action的Web MVC框架，构建于CDI之上，用于快速且可维护的Java开发。
* [Takes](https://github.com/yegor256/takes)：面向对象的Java Web框架，没有NULL、静态方法、注解和可变对象。
* [Firefly](https://github.com/hypercube1024/firefly)：Firefly是一个异步Web框架，用于快速开发高性能Web应用程序。

<h2 id="rest-framework">Rest框架</h2>

* [Jersey](https://github.com/eclipse-ee4j/jersey)：Jersey是一个Eclipse基金会下的REST框架，提供JAX-RS等参考实现。
* [Dropwizard](https://github.com/dropwizard/dropwizard)：一个非常简单的库，用于构建生产就绪的RESTful Web服务。
* [Resteasy](https://github.com/resteasy/resteasy)：Jakarta RESTful Web服务规范的实现。
* [Bootique](https://github.com/bootique/bootique)：Bootique是一种最简单的Java启动器和集成技术，它旨在构建无容器的可运行Java应用程序。
* [Restx](https://github.com/restx/restx)：轻量级Java REST框架。
* [Restlet](https://github.com/restlet/restlet-framework-java)：Java REST API框架。
* [Rest.li](https://github.com/linkedin/rest.li)：领英开源的REST+JSON框架，用于使用动态发现和简单的异步API构建健壮、可扩展的服务架构。
* [Grumpyrest](https://github.com/MartinGeisse/grumpyrest)：没有注解/DI/响应式的Java REST框架。
* [Resty](https://github.com/Dreampie/Resty)：极简的REST框架。
* [RestExpress](https://github.com/RestExpress/RestExpress)：用于快速创建可扩展、Containerless、RESTful微服务的极简Java框架。
* [Apache-CXF](https://github.com/apache/cxf)： Apache CXF是一个开源框架，提供了用于方便地构建和开发Web Service的可靠基础架构。

<h2 id="microservice-framework">微服务框架</h2>

* [Spring Cloud](https://spring.io/projects/spring-cloud)：Spring生态中的微服务框架。
* [Dubbo](https://github.com/apache/dubbo)：阿里开源的RPC和微服务框架。
* [Micronaut](https://github.com/micronaut-projects/micronaut-core)：JVM平台上的微服务框架。
* [Quarkus](https://github.com/quarkusio/quarkus)：云原生时代的Java微服务框架。
* [Helidon](https://github.com/helidon-io/helidon)：用于编写微服务的Java库。
* [Spring Cloud Netflix](https://github.com/spring-cloud/spring-cloud-netflix)：Spring Cloud Netflix是Spring Cloud的子项目，提供了Netflix开源项目的整合。
* [Spring Cloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba)：阿里开源的Spring Cloud框架，提供一站式的微服务应用开发解决方案。
* [Spring Cloud GCP](https://github.com/GoogleCloudPlatform/spring-cloud-gcp)：集成了Google云功能的Spring Cloud框架，由Google提供。
* [Spring Cloud Tencent](https://github.com/Tencent/spring-cloud-tencent)：Spring Cloud Tencent是腾讯提供的基于Spring Cloud的服务治理框架。
* [Spring Cloud Azure](https://github.com/microsoft/spring-cloud-azure)：Spring Cloud Azure是微软开发的Spring Cloud框架，提供Spring与 Azure服务的无缝集成。
* [Spring Cloud AWS](https://github.com/awspring/spring-cloud-aws)：亚马逊提供的Spring Cloud框架。
* [Spring Cloud Huawei](https://github.com/huaweicloud/spring-cloud-huawei)：华为开源的使Spring Cloud开发微服务变得更加简单和高效的框架。
* [JHipster](https://github.com/jhipster/generator-jhipster)：JHipster是一个用于快速生成、开发和部署现代Web应用程序和微服务架构的开发平台。
* [Ktor](https://github.com/ktorio/ktor)：Ktor是一个Kotlin编写的用于创建微服务、Web应用程序等的异步框架。
* [MicroProfile](https://github.com/eclipse/microprofile)：MicroProfile是一个Eclipse基金会项目，用于将Jakarta EE等企业Java技术应用于分布式微服务体系结构并不断发展。
* [ServiceComb](https://github.com/apache/servicecomb-java-chassis)：ServiceComb是一个软件开发套件，用于快速开发Java微服务。
* [Axon](https://github.com/AxonFramework/AxonFramework)：JVM上的演化消息驱动微服务框架。
* [Lagom](https://github.com/lagom/lagom)：JVM平台上的响应式微服务框架。
* [Armeria](https://github.com/line/armeria)：适用于任何情况的首选微服务框架，来自Netty创始人。你可以利用你喜欢的技术构建任何类型的微服务，包括gRPC、Thrift、Kotlin、Retrofit、Reactive Stream、Spring Boot和Dropwizard。
* [Light-4j](https://github.com/networknt/light-4j)：快速、轻量级且更高效的微服务框架。
* [JClouds](https://github.com/apache/jclouds)：Apache jclouds是一个适用于Java平台的开源多云工具包，可让你自由地创建可跨云移植的应用程序，同时让你完全控制使用特定于云的功能。
* [Msf4j](https://github.com/wso2/msf4j)：适用于Java的WSO2微服务框架。
* [NutzBoot](https://github.com/nutzam/nutzboot)：可靠的企业级微服务框架，提供自动配置、嵌入式Web服务、分布式会话、服务治理、负载均衡、hystrix、RPC等解决方案。
* [piggymetrics](https://github.com/sqshq/piggymetrics)：使用Spring Boot、Spring Cloud和Docker的微服务架构。
* [Jupiter](https://github.com/fengjiachun/Jupiter)：Jupiter是一款性能非常不错的，轻量级的分布式服务框架。

<h2 id="microservice-tool">微服务工具</h2>

* [Conductor](https://github.com/Netflix/conductor)：微服务编排引擎，由Netflix开源。
* [Apollo](https://github.com/spotify/apollo)：用于编写可组合微服务的Java库，由Spotify开源。

<h2 id="orm-framework">ORM框架</h2>

* [Hibernate](https://github.com/hibernate/hibernate-orm)：老牌ORM框架。
* [Spring Data JPA](https://github.com/spring-projects/spring-data-jpa)：Spring生态中的JPA框架。
* [Mybatis](https://github.com/mybatis/mybatis-3)：Java的MyBatis SQL映射器框架。
* [Mybatis-Plus](https://github.com/baomidou/mybatis-plus)：国产Mybatis的封装框架。
* [Mybatis-Flex](https://github.com/mybatis-flex/mybatis-flex)：国产Mybatis增强框架。
* [Fluent-Mybatis](https://github.com/atool/fluent-mybatis)：国产Mybatis的封装框架。
* [EclipseLink](https://github.com/eclipse-ee4j/eclipselink)：Eclipse基金会下的JPA实现。
* [OpenJPA](https://github.com/apache/openjpa)：Apache基金会下的JPA实现。
* [APIJSON](https://github.com/Tencent/APIJSON)：腾讯开源的ORM库。
* [Blaze](https://github.com/Blazebit/blaze-persistence)：Blaze-Persistence是面向JPA提供程序的丰富Criteria API。
* [QueryDSL](https://github.com/querydsl/querydsl)：Querydsl是一个可以为多个后端(包括JPA、MongoDB和Java中的SQL)构建类型安全的类SQL查询的框架。
* [JOOQ](https://github.com/jOOQ/jOOQ)：jOOQ是一个内部DSL和源代码生成器，将SQL语言建模为类型安全的Java API，帮助编写更好的SQL。
* [Ebean](https://github.com/ebean-orm/ebean)：Ebean提供多个查询抽象级别ORM查询，与SQL、DTO查询、SqlQuery和JDBC混合。
* [ObjectiveSql](https://github.com/braisdom/ObjectiveSql)：使用Java语法编写SQL。
* [JPA-Streamer](https://github.com/speedment/jpa-streamer)：JPAstreamer是一个轻量级库，用于将JPA查询表达为Java Stream。
* [jdbi](https://github.com/jdbi/jdbi)：jdbi旨在提供Java中方便的表数据访问；包括模板化SQL、参数化和强类型查询以及Stream集成。
* [ORMLite](https://github.com/j256/ormlite-core)：精简版Java ORM。
* [Reladomo](https://github.com/goldmansachs/reladomo)：Reladomo是Java的企业级对象关系映射框架。
* [Cayenne](https://github.com/apache/cayenne)：Apache Cayenne是一个开源持久层框架，提供对象关系映射(ORM)和远程处理服务。
* [doma](https://github.com/domaframework/doma)：适用于Java 8+的面向DAO的数据库映射框架。
* [Jimmer](https://github.com/babyfish-ct/jimmer)：适用于Java和Kotlin的ORM框架。
* [JFinal](https://github.com/jfinal/jfinal)：国产的Web、ORM框架。
* [easy-query](https://github.com/xuejmnet/easy-query)：Java/Kotlin高性能轻量级JDBC查询解决方案，支持分表，数据库支持主从。
* [Nutz](https://github.com/nutzam/nutz)：包含全功能的ORM、Web框架。
* [database-all](https://github.com/gaarason/database-all)：Java 的Eloquent ORM。
* [bean-searcher](https://github.com/troyzhxu/bean-searcher)：专注于高级查询的只读ORM，天然支持连接表，并且避免DTO/VO转换，使得一行代码实现复杂查询成为可能。

<h2 id="scaffold">脚手架</h2>

* [hope-boot](https://github.com/java-aodeng/hope-boot)：一款现代化的脚手架项目。
* [spring-boot-plus](https://github.com/geekidea/spring-boot-plus)：Spring Boot Plus是一个简单易用、高速、高效、功能丰富的开源Spring Boot脚手架。
* [X-SpringBoot](https://github.com/yzcheng90/X-SpringBoot)：X-SpringBoot是一个轻量级的Java快速开发平台。
* [springcloud-thoth](https://github.com/SpringForAll/springcloud-thoth)：Spring Cloud脚手架。
* [lenosp](https://gitee.com/zzdevelop/lenosp)：lenosp是一个基于Spring Boot的脚手架。
* [SpringCloud](https://github.com/zhoutaoo/SpringCloud)：基于Spring Cloud 2.1的微服务开发脚手架。
* [liugh-parent](https://github.com/qq53182347/liugh-parent)：实现RESTful快速开发的后端脚手架。
* [es](https://github.com/zhangkaitao/es)：Java EE项目开发脚手架。
* [ballcat](https://github.com/ballcat-projects/ballcat)：一个快速开发脚手架，快速搭建企业级后台管理系统，并提供多种便捷starter进行功能扩展。
* [mall-tiny](https://github.com/macrozheng/mall-tiny)：一款基于Spring Boot + MyBatisPlus的快速开发脚手架。
* [AgileBoot-Back-End](https://github.com/valarchie/AgileBoot-Back-End)：规范易于二开的全栈基础快速开发脚手架。
* [Vole](https://github.com/gavenwangcn/vole)：Spring Cloud微服务商业脚手架。
* [SpringBoot_v2](https://gitee.com/bdj/SpringBoot_v2)：Spring Boot项目开发脚手架。
* [Slife](https://gitee.com/jamen/slife)：Spring Boot搭建的一个企业级快速开发脚手架。
* [vhr](https://gitee.com/lenve/vhr)：Spring Boot + Vue前后端分离的人力资源管理项目，可做常规企业级应用脚手架。
* [maozi-cloud-parent](https://github.com/1095071913/maozi-cloud-parent)：基于Spring Cloud Alibaba、Dubbo二开封装。

<h2 id="test">测试</h2>

这里主要是一些测试框架和工具库，包括单元测试、集成测试、性能测试等。

<h4 id="unit-test">单元测试</h4>

* [JUnit 4](https://github.com/junit-team/junit4)：Java的单元测试框架。
* [JUnit 5](https://github.com/junit-team/junit5)：JUnit的全新版本框架。
* [TestNG](https://github.com/testng-team/testng)：TestNG测试框架。
* [Spock](https://github.com/spockframework/spock)：基于Groovy的测试框架，支持数据驱动、Mock等功能。
* [Robolectric](https://github.com/robolectric/robolectric)：一个Android的单元测试框架。
* [Kotest](https://github.com/kotest/kotest)：强大、优雅且灵活的Kotlin测试框架，具有额外的断言、属性测试和数据驱动测试功能。
* [TestFX](https://github.com/TestFX/TestFX)：用于JavaFX的单元测试框架。
* [scalatest](https://github.com/scalatest/scalatest)：面向Scala和Java开发人员的测试工具。
* [utest](https://github.com/com-lihaoyi/utest)：用于Scala的测试框架。
* [munit](https://github.com/scalameta/munit)：具有可操作错误和可扩展API的Scala测试库。

<h4 id="assertions">断言库</h4>

* [AssertJ](https://github.com/assertj/assertj)：AssertJ是一个提供易于使用的丰富类型断言的库。
* [JsonAssert](https://github.com/skyscreamer/JSONassert)：用更少的代码编写JSON单元测试，非常适合测试REST接口。
* [Truth](https://github.com/google/truth)：Google出品的流式断言库。
* [Hamcrest](https://github.com/hamcrest/JavaHamcrest)：Hamcrest的Java版本。
* [BeanMatcher](https://github.com/orien/bean-matchers)：用于测试Java bean的Hamcrest匹配器。
* [Deepdive](https://github.com/jdlib/deepdive)：Java的流式断言库。
* [Fest](https://github.com/alexruiz/fest-assert-2.x)：流式断言库。
* [expekt](https://github.com/winterbe/expekt): Kotlin的BDD断言库。

<h4 id="mocks">Mock框架</h4>

* [Mockito](https://github.com/mockito/mockito)：Java中最热门的Mock框架。
* [PowerMock](https://github.com/powermock/powermock)：一个扩展Mockito的框架，支持Mock静态方法、构造函数、私有方法等。
* [Testable-Mock](https://github.com/alibaba/testable-mock)：Alibaba开发的Mock框架。
* [WireMock](https://github.com/wiremock/wiremock)：一个模拟HTTP服务的工具。
* [EasyMock](https://github.com/easymock/easymock)：一个比较古老的Mock库。
* [Mockk](https://github.com/mockk/mockk)：用于Kotlin的Mock框架。
* [ScalaMock](https://github.com/paulbutcher/ScalaMock)：原生Scala  Mock框架。
* [MockServer](https://github.com/mock-server/mockserver)：MockServer可以轻松模拟通过HTTP或HTTPS与用Java、JavaScript和Ruby编写的客户端集成的任何系统。
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver)：用于测试HTTP客户端的可编写脚本的Web服务器。
* [Jukito](https://github.com/ArcBees/Jukito)：JUnit、Guice和Mockito的组合。
* [JMockit](https://github.com/jmockit/jmockit1)：用于集成测试、Mock、伪造和代码覆盖率的高级Java库。
* [MockBukkit](https://github.com/MockBukkit/MockBukkit)：MockBukkit是bukkit的Mock框架，可以轻松地对Bukkit插件进行单元测试。

<h4 id="mocks-lib">Mock工具</h4>

* [Moco](https://github.com/dreamhead/moco)：设置存根服务器。
* [RabbitMQ Mock](https://github.com/fridujo/rabbitmq-mock)：RabbitMQ的Mock库。
* [flashback](https://github.com/linkedin/flashback)：Flashback旨在模拟HTTP和HTTPS资源(例如Web服务和REST API)以用于测试目的。
* [S3Mock](https://github.com/adobe/S3Mock)：AWS S3 API的简单Mock实现，可作为Docker镜像、TestContainer、JUnit 4 Rule、JUnit Jupiter扩展或TestNG监听器启动。
* [CastleMock](https://github.com/castlemock/castlemock)：CastleMock是一个Web应用程序，提供模拟RESTful API和SOAP Web Service的功能。
* [restito](https://github.com/mkotsur/restito)：用于测试Rest客户端的Mock框架。

<h4 id="mocks-data">数据Mock</h4>

* [Instancio](https://github.com/instancio/instancio)：为单元测试创建完全填充的对象的库。
* [Junit Data Provider](https://github.com/TNG/junit-dataprovider)：类似TestNG的JUnit数据提供者运行程序，具有许多附加功能。
* [DataFaker](https://github.com/datafaker-net/datafaker)：为JVM(Java、Kotlin、Groovy)生成测试数据的库。
* [Java Faker](https://github.com/DiUS/java-faker)：将流行的ruby faker gem带到Java。
* [MockNeat](https://github.com/nomemory/mockneat)：现代的测试数据生成库。
* [jfairy](https://github.com/Devskiller/jfairy)：Java测试数据生成器。
* [EasyRandom](https://github.com/j-easy/easy-random)：简单的随机Java beans/记录生成器。
* [Jmockdata](https://github.com/jsonzou/jmockdata)：生成随机Java数据的插件。
* [JMock](https://github.com/jmock-developers/jmock-library)：用于测试驱动开发的富有表现力的对象Mock库。
* [burst](https://github.com/square/burst)：用于不同测试数据的单元测试库。
* [EasyModeling](https://github.com/easymodeling/easy-modeling)：EasyModeling是一个Java注解处理器，可生成随机填充的对象以供测试使用。
* [beanmother](https://github.com/keepcosmos/beanmother)：用于将Java对象设置为测试数据的库。

<h4 id="bdd">BDD框架</h4>

* [Cucumber](https://github.com/cucumber/cucumber-jvm)：JVM上的Cucumber实现。
* [Karate](https://github.com/karatelabs/karate)：一个BDD框架，支持API测试、UI测试、Mock等。
* [Serenity](https://github.com/serenity-bdd/serenity-core)：Serenity BDD是一个测试自动化库，旨在使编写自动化验收测试变得更容易、更有趣。
* [Concordion](https://github.com/concordion/concordion)：Concordion是一个Java开源框架，可让你将需求的简单英语描述转变为自动化测试。它通常与示例需求说明(SbE)和行为驱动开发(BDD)流程一起使用。
* [yaks](https://github.com/citrusframework/yaks)：YAKS是一个在Kubernetes上启用云原生BDD测试的平台。
* [JBehave](https://github.com/jbehave/jbehave-core)：JBehave是一个适用于Java和所有JVM语言Groovy、Kotlin、Ruby、Scala的BDD框架。
* [JGiven](https://github.com/TNG/JGiven)：用纯Java进行行为驱动开发的框架。
* [Chorus](https://github.com/Chorus-bdd/Chorus)：分布式系统的可执行规范。
* [Lambda Behave](https://github.com/RichardWarburton/lambda-behave)：Java 8的现代测试和行为规范框架。
* [Spectrum](https://github.com/greghaskins/spectrum)：适用于Java 8的BDD风格测试运行器。受Jasmine、RSpec和Cucumber启发。

<h4 id="automation">自动化工具</h4>

* [Selenium](https://github.com/SeleniumHQ/selenium)：浏览器自动化框架和生态系统。
* [Playwright](https://github.com/microsoft/playwright-java)：Java版本的Playwright测试和自动化库。
* [Selenide](https://github.com/selenide/selenide)：Selenium的封装，提供了更简洁的API。
* [WebDriverManager](https://github.com/bonigarcia/webdrivermanager)：Java中Selenium WebDriver的自动化驱动程序管理和其他辅助工具。
* [ashot](https://github.com/pazone/ashot)：WebDriver屏幕截图工具。
* [Allure](https://github.com/allure-framework/allure2)：一款灵活、轻量级的多语言测试报告工具。
* [FitNesse](https://github.com/unclebob/fitnesse)：一个验收测试工具。
* [SoapUI](https://github.com/SmartBear/soapui)：免费、开源的跨平台API和Web Service功能测试解决方案。
* [Galen](https://github.com/galenframework/galen)：一个自动化的布局和页面响应测试框架。
* [FluentLenium](https://github.com/FluentLenium/FluentLenium)：FluentLenium是一个Web和移动自动化框架，它扩展了Selenium以编写可靠且有弹性的UI功能测试。
* [Citrus](https://github.com/citrusframework/citrus)：专注于消息集成的自动化集成测试框架。
* [Webtau](https://github.com/testingisdocumenting/webtau)：WebTau(Web测试自动化)是一个测试API、命令行工具和一个用于编写单元、集成和端到端测试的框架。
* [SeLion](https://github.com/paypal/SeLion)：自动化测试工具。
* [jdi-light](https://github.com/jdi-testing/jdi-light)：Java中强大的UI自动化测试框架。
* [ZeroCode](https://github.com/authorjapps/zerocode)：社区开发的免费开源微服务API自动化和负载测试框架，使用JUnit核心运行程序构建，适用于Http REST、SOAP、安全性、数据库、Kafka等。
* [SoloPi](https://github.com/alipay/SoloPi)：SoloPi是一个无线化、非侵入式的Android自动化工具。
* [rest-client](https://github.com/wisdom-projects/rest-client)：测试REST API的自动化工具，可以生成精美的测试报告和REST API文档。
* [rest-client](https://github.com/wiztools/rest-client)：用于测试HTTP/RESTful WebService的工具。
* [opentest](https://github.com/mcdcorp/opentest)：适用于Web应用程序、移动应用程序和API的开源测试自动化工具。

<h4 id="load">负载测试</h4>

* [JMeter](https://github.com/apache/jmeter)：Apache出品的GUI形式的开源负载测试工具。
* [Ngrinder](https://github.com/naver/ngrinder)：企业级性能测试解决方案。
* [Gatling](https://github.com/gatling/gatling)：更现代的负载测试工具，以代码的方式编写测试用例。

<h4 id="test-lib">测试库</h4>

* [Testcontainers](https://github.com/testcontainers/testcontainers-java)：一个用于在测试中启动Docker容器的库。
* [Rest Assured](https://github.com/rest-assured/rest-assured)：一个用于测试REST API的库。
* [ArchUnit](https://github.com/TNG/ArchUnit)：Java架构测试库，用于以纯Java指定和断言架构规则。
* [Pitest](https://github.com/hcoles/pitest)：最先进的JVM突变测试库。
* [Awaitility](https://github.com/awaitility/awaitility)：用于测试异步代码的库。
* [Microcks](https://github.com/microcks/microcks)：用于模拟和测试API和微服务的Kubernetes原生工具。
* [Embedded Redis](https://github.com/kstyrc/embedded-redis)：用于Java集成测试的Redis嵌入式服务器。
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit)：用于比较JSON的库。
* [EqualsVerifier](https://github.com/jqno/equalsverifier)：EqualsVerifier可用于Java单元测试来验证equals和hashCode方法的约定是否得到满足。
* [Database-Rider](https://github.com/database-rider/database-rider)：让数据库集成测试变得更简单的库。
* [Jqwik](https://github.com/jqwik-team/jqwik)：JUnit平台上基于属性的测试库。
* [Fixture Monkey](https://github.com/naver/fixture-monkey)：可以自动生成包括边缘情况的测试实例。
* [OpenTest4J](https://github.com/ota4j-team/opentest4j)：JVM开放测试联盟。
* [randomizedtesting](https://github.com/randomizedtesting/randomizedtesting)：随机测试工具。
* [XmlUnit](https://github.com/xmlunit/xmlunit)：XMLUnit是一个支持以多种方式测试XML输出的库。
* [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer)：JUnit 5扩展包，提供很多JUnit 5没有的Extension。
* [System Rules](https://github.com/stefanbirkner/system-rules)：用于测试使用java.lang.System的代码的JUnit Rule集合。
* [System Lambda](https://github.com/stefanbirkner/system-lambda)：用于测试使用java.lang.System的代码的函数集合。
* [System Stubs](https://github.com/webcompere/system-stubs)：Java系统资源的测试替身。
* [GreenMail](https://github.com/greenmail-mail-test/greenmail)：GreenMail是一个邮件服务器Mock库，允许开发人员测试基于电子邮件的应用程序、服务或系统，而无需访问实时邮件服务器。
* [Arquillian](https://github.com/arquillian/arquillian-core)：Arquillian提供了用于集成测试的组件模型，其中包括依赖注入和容器生命周期管理。
* [MicroShed](https://github.com/MicroShed/microshed-testing)：用于黑盒测试MicroProfile和Jakarta EE应用程序的测试框架。
* [JGotesting](https://github.com/tastapod/jgotesting)：受Go测试包启发的JUnit兼容测试工具。
* [Pact](https://github.com/pact-foundation/pact-jvm)：Pact的JVM版本，用于编写消费者驱动的契约测试。
* [wasabi](https://github.com/intuit/wasabi)：A/B测试工具，不再处于开发状态。
* [evosuite](https://github.com/EvoSuite/evosuite)：自动生成Java类的JUnit测试套件。
* [QuickTheories](https://github.com/quicktheories/QuickTheories)：Java 8基于属性的测试。
* [jwebunit](https://github.com/JWebUnit/jwebunit)：Java Web测试框架。
* [scalacheck](https://github.com/typelevel/scalacheck)：Scala基于属性的测试。
* [QuickPerf](https://github.com/quick-perf/quickperf)：QuickPerf是Java的一个测试库，用于快速评估和改进一些与性能相关的属性。

<h2 id="ide">Java IDE</h2>

* [IntelliJ IDEA](https://github.com/JetBrains/intellij-community)：Jetbrains开发的Java、Kotlin IDE。
* [Eclipse](https://github.com/eclipse-platform)：Eclipse下开源免费的Java IDE。
* [Visual Studio Code](https://code.visualstudio.com/)：微软开源的文本编辑器，也支持作为IDE开发Java。
* [Android Studio](https://developer.android.com/studio)：Google开发的Android开发IDE，基于Intellij引擎。
* [Apache NetBeans](https://github.com/apache/netbeans)：Apache下开源免费的Java IDE，最初由Oracle开发。
* [MyEclipse](https://www.genuitec.com/products/myeclipse/)：MyEclipse是一个基于Eclipse的商业Java IDE。
* [STS](https://github.com/spring-projects/sts4)：Spring官方出品的基于Eclipse的Java IDE。
* [JDeveloper](https://www.oracle.com/application-development/technologies/jdeveloper.html)：Oracle开发的Java IDE。
* [BlueJ](https://github.com/k-pet-group/BlueJ-Greenfoot)：专为初学者设计的免费Java开发环境。
* [JBuilder](https://borland-jbuilder.software.informer.com/)：Borland软件公司出品的Java集成编程环境，有不同功能程度的多个版本。
* [Consulo](https://github.com/consulo/consulo)：开源的可用于Java的IDE，基于Intellij引擎。
* [Greenfoot](https://www.greenfoot.org/home)：免费的Java集成开发环境。
* [DrJava](http://www.drjava.org/)：DrJava是一个简单、轻量级、交互式Java IDE。

<h2 id="build">构建工具</h2>

* [Apache Maven](https://github.com/apache/maven)：使用最广泛的Java构建工具。
* [Mvnd](https://github.com/apache/maven-mvnd)：提供更快的Maven构建。
* [Gradle](https://github.com/gradle/gradle)：灵活，快速的Java、Android构建工具。
* [Apache Ant](https://github.com/apache/ant)：古老的构建工具。
* [Bazel](https://github.com/bazelbuild/bazel)：快速、多语言且可扩展的构建系统，由Google开发。
* [Buck](https://github.com/facebook/buck)：一个快速构建系统，鼓励在各种平台和语言上创建小型、可重用的模块，由Facebook开发。
* [Sbt](https://github.com/sbt/sbt)：适用于Scala、Java的构建工具。
* [Bnd](https://github.com/bndtools/bnd)：用于构建OSGi包的工具，包括Eclipse、Maven和Gradle插件。

<h2 id="gui">GUI程序</h2>

* [DBeaver](https://github.com/dbeaver/dbeaver)：免费的通用数据库工具和SQL客户端。
* [JD-GUI](https://github.com/java-decompiler/jd-gui)：Java反编译器GUI。
* [FinalShell](https://www.hostbuf.com/)：国内开源的SSH客户端工具。
* [SoapUI](https://github.com/SmartBear/soapui)：SoapUI是一个免费、开源的跨平台API和Web Service功能测试解决方案。
* [ArgoUML](https://github.com/argouml-tigris-org/argouml)：一个用于绘制UML图的应用软件。
* [PlantUML](https://github.com/plantuml/plantuml)：可以通过纯文本的方式来生成UML图。
* [Luyten](https://github.com/deathmarine/Luyten)：Procyon的开源Java反编译器GUI。
* [Matlab](https://www.mathworks.com/products/matlab.html)：Matlab是一种用于算法开发、数据可视化、数据分析以及数值计算的高级技术计算语言和交互式环境，其GUI部分由Java开发。
* [Protege](https://github.com/protegeproject/protege)：Protege是一个免费的开源本体编辑器，支持最新的OWL 2.0标准。
* [AKHQ](https://github.com/tchiotludo/akhq)：用于Apache Kafka的Kafka GUI，用于管理主题、主题数据、消费者组、模式注册表、连接等等。
* [Gephi](https://github.com/gephi/gephi/)：可视化跨平台网络图形化操作程序。
* [PrettyZoo](https://github.com/vran-dev/PrettyZoo)：Zookeeper GUI，支持Win/Mac/Linux平台。
* [RedisClient](https://github.com/caoxinyu/RedisClient)：基于Java SWT和Jedis编写的Redis客户端GUI工具。
* [Jailer](https://github.com/Wisser/Jailer)：数据库子集和关系数据浏览工具。
* [blobsaver](https://github.com/airsquared/blobsaver)：用于自动保存SHSH blob的跨平台GUI和CLI应用程序。
* [Sonarqube](https://github.com/SonarSource/sonarqube)：SonarQube是一个开源的代码分析平台，可以用来持续分析和评测项目源代码的质量。
* [LibreOffice](https://github.com/LibreOffice/core)：一款开源的办公套件，包括文档处理、电子表格、演示文稿等功能。
* [Teambition](https://www.teambition.com/)：阿里旗下的项目协作工具。
* [Atlassian Confluence](https://www.atlassian.com/zh/software)：Confluence是一个专业的企业知识管理与协同软件。
* [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)：STM32CubeMX是ST公司推出的一种自动创建单片机工程及初始化代码的工具。
* [GeoGebra](https://www.geogebra.org/)：GeoGebra是一款动态数学(几何)软件，于2001年由Markus Hohenwarter在奥地利萨尔茨堡大学制作。
* [Logisim-evolution](https://github.com/logisim-evolution/logisim-evolution)：数字逻辑设计工具和模拟器。
* [Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas)：位图和表情符号字体创建和转换工具。
* [ImageJ](https://imagej.net/ij/index.html)：生物医学领域的图像处理软件。
* [Vivado](https://www.xilinx.com/products/design-tools/vivado.html)：Xilinx开发的用于HDL设计的合成和分析的软件套件，具有用于片上系统开发和高级综合的附加功能。
* [Citespace](https://citespace.podia.com/)：基于Java语言编写的可视化文献分析软件。
* [ArcTime](https://arctime.org/)：ArcTime是使用Java编写的免费跨平台字幕软件。
* [FreeMind](https://github.com/jiangxin/freemind-mmx)：FreeMind是一款免费开源的思维导图软件。
* [Xmind](https://xmind.app/)：Xmind是一款全功能的思维导图和头脑风暴软件。
* [DSTE](https://ai-solutions.com/dste/)：DSTE被约翰逊航天中心用作设计工具，为地月系统轨道上的载人栖息地任务进行轨道设计。
* [CuratOR](https://eizo-or.com/en/global/products/or-software/curator-caliop-vm/)：CuratorOR由德国EIZO GmbH开发，是一款用在医院手术室的应用程序。

<h2 id="jdk">开源JDK</h2>

* [Open JDK](https://github.com/openjdk/jdk)：Oracle开源的OpenJDK官方版本。
* [AWS Corretto](https://github.com/corretto/corretto-8)：亚马逊开源的JDK版本。
* [Eclipse Temurin](https://github.com/adoptium/temurin-build)：Eclipse基金会下的JDK版本。
* [Bellsoft Liberica](https://github.com/bell-sw/Liberica)：BellSoft开源的JDK版本。
* [GraalVM](https://github.com/oracle/graal)：Oracle开源的一个高性能JDK发行版，旨在加速用Java和其他JVM语言编写的应用程序的执行，并支持JavaScript、Ruby、Python和许多其他流行语言。
* [Microsoft JDK](https://github.com/microsoft/openjdk)：微软开源的JDK构建版本。
* [Azul Zulu](https://www.azul.com/zh-hans/core/)：Azul开源的JDK版本。
* [IBM Semeru](https://www.ibm.com/support/pages/java-sdk-downloads)：IBM开源的JDK版本。
* [Eclipse OpenJ9](https://github.com/eclipse-openj9/openj9)：适用于OpenJDK的Java虚拟机，针对占用空间小、启动快和高吞吐量进行了优化。
* [Redhat JDK](https://developers.redhat.com/products/openjdk/download)：Redhat开源的JDK版本。
* [JetBrains JDK](https://github.com/JetBrains/JetBrainsRuntime)：JetBrains开发的基于OpenJDK的运行时环境。
* [Alibaba Dragonwell](https://github.com/dragonwell-project/dragonwell8)：阿里开源的JDK版本。
* [Tencent Kona](https://github.com/Tencent/TencentKona-17)：腾讯开源的JDK版本。
* [Huawei bisheng](https://www.openeuler.org/zh/other/projects/bishengjdk/)：华为开源的JDK版本，代号毕昇。
* [Loongson JDK](https://github.com/loongson/jdk)：龙芯中科基于OpenJDK研制并发布的龙芯平台Java环境。
* [OpenLogic](https://www.openlogic.com/openjdk-downloads)：Openlogic开源的JDK版本。
* [SapMachine](https://github.com/SAP/SapMachine)：由SAP维护和支持的OpenJDK版本。
* [leJOS](https://lejos.sourceforge.io/)：乐高开发的JVM，基于leJOS开发的机器人曾经在国际空间站上运行，该VM很早就已经停止维护。
* [JamJVM](https://jamvm.sourceforge.net/)：一个比较小众的JVM。
* [Maxine VM](https://github.com/beehive-lab/Maxine-VM)：Java中的元循环VM。
* [Jikes RVM](https://github.com/JikesRVM/JikesRVM)：一个由Java开发的虚拟机，曾经为虚拟机技术前沿研究超过180篇出版物和36篇论文。
* [duppio](https://github.com/plasma-umass/doppio)：一个兼容POSIX的运行时系统以及一个用TypeScript编写的JVM。

<h2 id="profiler">性能分析</h2>

* [VisualVM](https://github.com/oracle/visualvm)：VisualVM是一款一体化Java故障排除工具。
* [Arthas](https://arthas.aliyun.com/)：阿里巴巴开源的Java诊断工具。
* [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html)：商业分析器。
* [YourKit](https://www.yourkit.com/features/)：商业分析器。
* [AppDynamics](https://www.appdynamics.com/)：服务性能监控/管理工具。
* [async-profiler](https://github.com/async-profiler/async-profiler)：该项目是一个低开销的Java采样分析器，不会遇到安全点偏差问题。
* [JVM-Profiler](https://github.com/uber-common/jvm-profiler)：可以将指标发送到Kafka、控制台输出或自定义报告器的JVM Profiler，由Uber开源。
* [TProfiler](https://github.com/alibaba/TProfiler)：TProfiler是一个可以在生产环境长期使用的性能分析工具，由阿里开源。
* [NetBeans Profiler](https://github.com/apache/netbeans/tree/master/profiler)：Apache NetBeans的内置分析器。
* [Bistoury](https://github.com/qunarcorp/bistoury)：Bistoury是去哪儿网开源的Java应用生产问题诊断工具，提供了一站式的问题诊断方案。
* [JMC](https://github.com/openjdk/jmc)：Oracle开源的一个生产时间分析和诊断工具套件。
* [GCToolkit](https://github.com/microsoft/gctoolkit)：GCToolkit是一组用于分析HotSpot Java垃圾回收(GC)日志文件的库，由微软开源。
* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)：Java HotSpot JIT编译器的日志分析器/可视化器，。
* [jHiccup](https://github.com/giltene/jHiccup)：提供平台中JVM暂停的日志和记录。
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils)：用于延迟测量和报告的实用程序。
* [JOL](https://github.com/openjdk/jol)：JOL(Java对象布局)是用于分析JVM中对象布局的微型工具箱。
* [Sematext](https://github.com/sematext/sematext-agent-java)：全栈基础设施监控工具。
* [JMX-Exporter](https://github.com/prometheus/jmx_exporter)：通过HTTP公开JMX Bean供Prometheus使用的工具。
* [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler)：没有安全点样本偏差的JVM采样分析器。
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler)：使用StatsD和其他指标后端的简单JVM分析器。
* [SJK](https://github.com/aragozin/jvm-tools)：SJK是一个用于JVM诊断、故障排除和分析的命令行工具。
* [MyPerf4J](https://github.com/LinShunKang/MyPerf4J)：一个针对高并发、低延迟应用设计的高性能Java性能监控和统计工具。
* [jvmtop](https://github.com/patric-r/jvmtop)：Java命令行监控工具，包括分析器。
* [GCeasy](https://gceasy.io/)：非常好用的在线分析GC日志的工具。
* [aprof](https://github.com/devexperts/aprof)：Java内存分配分析器。
* [Sniffy](https://github.com/sniffy/sniffy)：Java的交互式分析器、测试和混沌工程工具。
* [JavaMelody](https://github.com/javamelody/javamelody)：JavaMelody的目标是监控QA和生产环境中的Java或Java EE应用程序。
* [FastThread](https://fastthread.io/)：Java线程转储分析器。
* [Automon](https://github.com/stevensouza/automon)：Automon将AOP(AspectJ)的强大功能与已使用的监视或日志记录工具相结合，以声明方式监视Java代码、JDK和第三方库。
* [spring-boot-startup-report](https://github.com/maciejwalkowiak/spring-boot-startup-report)：Spring Boot启动报告库生成交互式Spring Boot应用程序启动报告，让你了解影响应用程序启动时间的因素，并可能有助于优化它。
* [spring-boot-user-beans](https://github.com/jabrena/spring-boot-user-beans)：一种直观的方式来提高开发人员减少内存中Bean数量的意识。
* [spring-startup-analyzer](https://github.com/linyimin0812/spring-startup-analyzer)：Spring Startup Analyzer生成交互式Spring应用程序启动报告，让你了解影响应用程序启动时间的因素并帮助优化它。


<h2 id="apm">APM监控工具</h2>

* [Apache SkyWalking](https://github.com/apache/skywalking)：Apache基金会下的应用程序性能监控系统，国产开源。
* [Pinpoint](https://github.com/pinpoint-apm/pinpoint)：采用Java语言编写的链路分析和应用性能监控系统，由韩国Naver 研发团队开源。
* [Cat](https://github.com/dianping/cat)：服务端项目基础组件，可以提供系统丰富的性能指标、健康状况、实时告警等，由美团点评开源。
* [Matrix](https://github.com/Tencent/matrix)：Matrix是微信开发的插件式、非侵入式APM系统。
* [Hertzbeat](https://github.com/dromara/hertzbeat)：开源实时监控系统，具有自定义监控、高性能集群和无代理功能，由dromara社区开源。
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM)：360开源的线上移动性能检测平台。
* [Scouter](https://github.com/scouter-project/scouter)：开源APM工具。
* [Femas](https://github.com/TencentFemas/femas)：基于Java Agent的微服务治理平台，由腾讯开源。
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor)：用于Java服务器应用程序性能监控的开源解决方案。
* [Glowroot](https://github.com/glowroot/glowroot)：易于使用，开销极低的Java APM。
* [BeeAPM](https://gitee.com/beetle082/bee-apm)：分布式跟踪和应用性能监控系统，基于Java Agent。
* [EasyAgent](https://github.com/megaease/easeagent)：Java系统的代理组件。
* [inspectIT](https://github.com/inspectIT/inspectIT)：inspectIT是领先的开源APM工具，用于分析Java应用程序。

<h2 id="cloud-native">云原生</h2>

* [Discovery](https://github.com/Nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移、多活。
* [Micrometer](https://github.com/micrometer-metrics/micrometer)：最流行的可观察性工具的应用程序可观察性门面。
* [Spring-Cloud-Kubernetes](https://github.com/spring-cloud/spring-cloud-kubernetes)：Kubernetes与Spring Cloud Discovery客户端、配置等集成。
* [HummerRisk](https://github.com/chaitin/HummerRisk)：HummerRisk是云原生安全平台，包括混合云安全治理和云原生安全检测。
* [SREWorks](https://github.com/alibaba/SREWorks)：云原生数智运维平台。
* [Siddhi](https://github.com/siddhi-io/siddhi)：流处理和复杂事件处理引擎。
* [Apache EventMesh](https://github.com/apache/eventmesh)：EventMesh是新一代无服务器事件中间件，用于构建分布式事件驱动应用程序。
* [PolarDB-X](https://github.com/polardb/polardbx-sql)：PolarDB-X是一款云原生分布式SQL数据库，专为高并发、海量存储、复杂查询场景而设计，由阿里开源。
* [PacBot](https://github.com/tmobile/pacbot)：PacBot是一个用于云持续合规性监控、合规性报告和安全自动化的平台。
* [MQCloud](https://github.com/sohutv/mqcloud)：RocketMQ企业级一站式服务平台。
* [Scoold](https://github.com/Erudika/scoold)：Scoold是一个面向团队的问答和知识共享平台。
* [iTranswarp](https://github.com/michaelliao/itranswarp)：功能齐全的CMS，包括博客、wiki、讨论等。由Spring Boot提供支持的云原生应用程序。
* [LINSTOR](https://github.com/LINBIT/linstor-server)：适用于容器、云和虚拟化的高性能软件定义块存储，与Docker、Kubernetes、Openstack、Proxmox等完全集成。
* [Mendmix](https://github.com/dromara/mendmix)：Mendmix提供了数据库、缓存、消息中间件、分布式定时任务、安全框架、网关以及主流产商云服务快速集成能力。
* [Apache Submarine](https://github.com/apache/submarine)：Submarine是云原生机器学习平台。
* [DataSophon](https://github.com/datavane/datasophon)：致力于快速实现大数据云原生平台的部署、管理、监控和自动化运维，帮助你快速构建稳定、高效、弹性、可扩展的大数据云原生平台。
* [Kogito](https://github.com/kiegroup/kogito-runtimes)：Kogito是一种云原生业务自动化技术，用于构建云就绪的业务应用程序。
* [OpenWMS.org](https://github.com/openwms/org.openwms)：开放式仓库管理系统。
* [JoyQueue](https://github.com/chubaostream/joyqueue)：具有高性能的云原生生产质量消息传递平台。
* [DataEase](https://gitee.com/fit2cloud-feizhiyun/DataEase)：DataEase是开源的数据可视化分析工具，帮助用户快速分析数据并洞察业务趋势，从而实现业务的改进与优化。
* [Smart-MQTT](https://gitee.com/smartboot/smart-mqtt)：一款开源的云原生分布式MQTT Broker服务器，支持海量物联网设备互联互通。
* [Firehose](https://github.com/raystack/firehose)：Firehose是一种可扩展、无代码、云原生服务，用于将实时流数据从Kafka加载到数据存储、数据湖和分析存储系统。
* [Dagger](https://github.com/raystack/dagger)：Dagger是一个易于使用、通过代码进行配置的云原生框架，构建在Apache Flink之上，用于实时流数据的状态处理。
* [EDDI](https://github.com/labsai/EDDI)：用于对话式AI API(例如ChatGPT)的提示和对话管理中间件。
* [GeoServer](https://github.com/geoserver/geoserver-cloud)：通过Docker化微服务在云中使用的GeoServer。
* [Starwhale](https://github.com/star-whale/starwhale)：MLOps/LLMOps平台。
* [KalDB](https://github.com/slackhq/kaldb)：KalDB是一个用于日志、跟踪和审计数据的云原生搜索和分析引擎。
* [XAP](https://github.com/xap/xap)：分布式、高度可扩展的内存数据网格。
* [Spring Boot Istio](https://github.com/piomin/spring-boot-istio)：用于与Kubernetes上的Istio集成的Spring Boot库。

<h2 id="utils">工具库</h2>

* [Guava](https://github.com/google/guava)：Google开源的Java工具库。
* [Apache Commons](https://github.com/apache/commons-lang)：Apache下的Java工具库。
* [Lombok](https://github.com/projectlombok/lombok)：对Java语法非常有用的补充，消除样板代码。
* [Hutool](https://github.com/dromara/hutool)：功能极其丰富的Java工具库，由dromara社区开源。
* [NullAway](https://github.com/uber/NullAway)：一种帮助消除Java代码中NullPointerExceptions(NPE)的工具，由Uber开源。
* [Cactoos](https://github.com/yegor256/cactoos)：面向对象的Java原始类型，作为Google Guava和Apache Commons的替代品。
* [jcommon](https://github.com/facebookarchive/jcommon)：Facebook开源的Java工具库，含并发、集合、统计/分析、配置、测试等功能。
* [immutables](https://github.com/immutables/immutables)：用于创建不可变对象和构建器的注解处理器。
* [Manifold](https://github.com/manifold-systems/manifold)：Manifold是一个Java编译器插件，其功能包括元编程、属性、扩展方法、运算符重载、模板、预处理器等。
* [record-builder](https://github.com/Randgalt/record-builder)：Java记录的记录构建器。
* [ph-commons](https://github.com/phax/ph-commons)：Java 11库，包含所有项目所需的大量实用程序类。
* [commons](https://github.com/twitter-archive/commons)：Twitter的JVM公共库，已弃用。
* [ModiTect](https://github.com/moditect/moditect)：Java 9模块系统工具库。
* [simple-binary-encoding](https://github.com/real-logic/simple-binary-encoding)：高性能消息编解码器。
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions)：VerbalExpressions 是一个Java库，可帮助构建困难的正则表达式。
* [JGit](https://eclipse.dev/jgit/)：可以用于操作Git存储库的纯Java实现。

<h2 id="di">依赖注入</h2>

* [Spring](https://github.com/spring-projects/spring-framework)：Spring生态中的依赖注入框架。
* [Guice](https://github.com/google/guice)：Guice是一个适用于Java 8及更高版本的轻量级依赖注入框架，由Google提供。
* [Dagger](https://github.com/google/dagger)：适用于Android和Java的快速依赖注入器。
* [Koin](https://github.com/InsertKoinIO/koin)：适用于Kotlin和Kotlin多平台的实用轻量级依赖注入框架。
* [picocontainer](https://github.com/picocontainer/picocontainer)：古老的Java依赖注入库。
* [avaje](https://github.com/avaje/avaje-inject)：面向服务端开发人员的基于APT的依赖注入。
* [eclipse-hk2](https://github.com/eclipse-ee4j/glassfish-hk2)：轻量级动态依赖注入框架。
* [deltaspike](https://github.com/apache/deltaspike)：Apache DeltaSpike是一套可移植的CDI扩展。
* [javax-inject](https://github.com/javax-inject/javax-inject)：JSR-330依赖注入标准。
* [CDI](https://www.cdi-spec.org/)：CDI规范，定义了一组强大的补充服务。
* [sisu](https://github.com/eclipse/sisu.inject)：Sisu是一个基于JSR330的模块化容器，支持类路径扫描、自动绑定和动态自动装配。
* [weld](https://github.com/weld/core)：Weld是CDI的参考实现。
* [scaldi](https://github.com/scaldi/scaldi)：轻量级Scala依赖注入库。
* [Kodein](https://github.com/kosi-libs/Kodein)：Kotlin依赖注入。
* [Transfuse](https://github.com/johncarl81/transfuse)：Google Android的依赖注入和集成框架。

<h2 id="aop">AOP</h2>

* [AspectJ](https://eclipse.dev/aspectj/)：一个易用的功能强大的AOP框架。
* [jvm-sandbox](https://github.com/alibaba/jvm-sandbox)：基于JVM的实时非侵入式AOP框架容器。
* [JBossAop](https://jbossaop.jboss.org/)：JBoss AOP是一个100%纯Java面向切面的框架，可在任何编程环境中使用或与我们的应用程序服务器紧密集成。
* [FastAop](https://github.com/fast-light/fastaop)：基于Java注解处理的轻量级高性能AOP框架，类似于Lombok。
* [Alliance](https://aopalliance.sourceforge.net/)：Alliance项目是几个对AOP和Java感兴趣的软件工程人员联合发起的开源项目。
* [VirtualXposed](https://github.com/android-hacker/VirtualXposed)：无需Root即可使用Xpose，解锁引导加载程序或修改系统镜像等。
* [Lancet](https://github.com/eleme/lancet)：面向Android App和SDK开发人员的轻量级快速AOP框架。
* [jcabi-aspects](https://github.com/jcabi/jcabi-aspects)：AspectJ Java切面的集合，促进面向切面的编程模式：日志记录、缓存、验证等。

<h2 id="log">日志库</h2>

* [Log4j](https://github.com/apache/logging-log4j1)：Log4j的初始版本，已经停止维护。
* [Log4j2](https://github.com/apache/logging-log4j2)：一个多功能、功能丰富、高效的Java日志记录API。
* [Logback](https://github.com/qos-ch/logback)：可靠、通用、快速且灵活的Java日志记录框架。
* [Slf4j](https://github.com/qos-ch/slf4j)：Java的简单日志门面。
* [Flogger](https://github.com/google/flogger)：适用于Java的流式日志记录API，由Google开发。
* [Commons-logging](https://github.com/apache/commons-logging)：Apache下的通用日志记录接口。
* [Logstash](https://github.com/elastic/logstash)：传输和处理日志、事件或其他数据。
* [twitter-util](https://github.com/twitter/util/tree/develop/util-logging)：Twitter开发的工具库。
* [Tinylog](https://github.com/tinylog-org/tinylog)：适用于Java、Kotlin、Scala和Android的轻量级日志框架。
* [Graylog](https://github.com/Graylog2/graylog2-server)：免费开放的日志管理。
* [blitz4j](https://github.com/Netflix/blitz4j)：用于固定异步日志记录的日志记录框架。
* [kotlin-logging](https://github.com/oshai/kotlin-logging)：Kotlin的轻量级多平台日志框架。
* [Jboss-logging](https://github.com/jboss-logging/jboss-logging)：JBoss开源的日志库。
* [scala-logging](https://github.com/lightbend-labs/scala-logging)：用于包装Slf4j的Scala的方便且高性能的日志记录库。
* [logger](https://github.com/orhanobut/logger)：简单、功能强大的Android记录器。
* [timber](https://github.com/JakeWharton/timber)：具有小型可扩展API的日志记录器。
* [plumelog](https://gitee.com/plumeorg/plumelog)：国产的分布式日志收集系统。
* [logbook](https://github.com/zalando/logbook)：用于HTTP请求和响应日志记录的可扩展Java库。
* [xLog](https://github.com/elvishew/xLog)：Android日志记录器，强大，灵活。
* [TLog](https://gitee.com/dromara/TLog)：dromara社区开源的轻量级分布式日志标记追踪框架。
* [JLog](https://gitee.com/jd-platform-opensource/jlog)：京东开源的海量日志搜集、传输、存储解决方案。
* [jobs](https://gitee.com/baomidou/jobs)：baomidou社区开源的分布式任务调度组件。

<h2 id="job">任务调度</h2>

* [xxl-job](https://github.com/xuxueli/xxl-job)：分布式任务调度平台。
* [Quartz](https://github.com/quartz-scheduler/quartz)：老牌任务调度框架。
* [elasticjob](https://github.com/apache/shardingsphere-elasticjob)：当当网开源的分布式任务调度框架，基于Quartz二次开发。
* [PowerJob](https://github.com/PowerJob/PowerJob)：具有分布式计算能力的企业作业调度中间件。
* [Spring Task](https://docs.spring.io/spring-framework/reference/integration/scheduling.html#scheduling-task-scheduler)：Spring提供的任务调度集成。
* [jobrunr](https://github.com/jobrunr/jobrunr)：一种在Java中执行后台处理的极其简单的方法，由持久存储支持。
* [schedulerx](https://www.aliyun.com/aliware/schedulerx)：阿里开发的基于Akka架构的分布式任务调度平台。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：调度任务的分布式锁。
* [disjob](https://gitee.com/dromara/disjob)：dromara开源的分布式任务调度框架。
* [light-job](light-task-scheduler)：国产分布式调度任务框架。
* [Saturn](https://github.com/vipshop/Saturn)：唯品会开源的分布式作业调度平台。
* [aurora](https://github.com/apache/aurora)：用于长时间运行的服务、cron作业和临时作业的Mesos框架，该项目在Apache基金会下已经退役。
* [db-scheduler](https://github.com/kagkarlsson/db-scheduler)：适用于Java的持久集群友好调度程序。
* [openjob](https://github.com/open-job/openjob)：分布式高性能任务调度框架。
* [Sundial](https://github.com/knowm/Sundial)：轻量级的作业调度框架。
* [android-job](https://github.com/evernote/android-job)：用于在后台处理任务的Android库，该项目不再维护。
* [jobx](https://github.com/datavane/jobx)：轻量级的任务调度库。
* [Cron4j](http://www.sauronsoftware.it/projects/cron4j/)：古老的Java平台调度程序。
* [job-dispatcher](https://gitee.com/daye_daye/job-dispatcher)：国产的基于事件的流程编排和调度引擎。

<h2 id="bpm">业务流 & 规则引擎</h2>

* [Activiti](https://github.com/Activiti/Activiti)：Activiti是一个轻量级工作流程和业务流程管理(BPM)平台，面向业务人员、开发人员和系统管理员。
* [Drools](https://github.com/kiegroup/drools)：Drools是Java的规则引擎、DMN引擎和复杂事件处理(CEP)引擎。
* [Camunda](https://github.com/camunda/camunda-bpm-platform)：使用BPMN和DMN实现工作流程和决策自动化的灵活框架。与Spring、Spring Boot、CDI集成。
* [Flowable](https://github.com/flowable/flowable-engine)：为开发人员、系统管理员和业务用户提供紧凑且高效的工作流程和业务流程管理(BPM)平台。
* [dolphinscheduler](https://github.com/apache/dolphinscheduler)：Apache DolphinScheduler是现代数据编排平台，以低代码敏捷创建高性能工作流程。
* [jbpm](https://github.com/kiegroup/jbpm)：业务流程管理(BPM)套件。
* [liteflow](https://github.com/dromara/liteflow)：dromara开源的轻量级、快速、稳定、可编程的基于组件的规则引擎/流程引擎。
* [piper](https://github.com/runabol/piper)：分布式工作流引擎。
* [zeebe](https://github.com/camunda/zeebe)：用于微服务编排的分布式工作流引擎。
* [compileflow](https://github.com/alibaba/compileflow)：阿里开源的高性能流程编排引擎。
* [bulbasaur](https://github.com/alibaba/bulbasaur)：阿里开源的可插拔的精简流程引擎，可快速实现流程、审批、业务失败重试等场景。
* [SmartEngine](https://github.com/alibaba/SmartEngine)：阿里开源的一个轻量级的业务编排引擎。
* [kestra](https://github.com/kestra-io/kestra)：Kestra是一个无限可扩展的编排和调度平台，可创建、运行、调度和监控数百万个复杂的管道。
* [azkaban](https://github.com/azkaban/azkaban)：工作流程管理器。
* [imixs-workflow](https://github.com/imixs/imixs-workflow)：用于业务流程管理的开源框架。
* [easy-rules](https://github.com/j-easy/easy-rules)：简单的Java规则引擎。
* [digdag](https://github.com/treasure-data/digdag)：工作负载自动化系统。
* [cadence](https://github.com/uber/cadence-java-client)：Cadence工作流服务的Java框架，由Uber开发。
* [openl-tablets](https://github.com/openl-tablets/openl-tablets)：业务规则管理系统。
* [agile-bpm](https://gitee.com/agile-bpm)：快速、简洁且强大的低代码流程开发平台。
* [TestHub](https://gitee.com/dromara/TestHub)：基于流程编排的国产自动化测试工具。
* [FlowLong](https://gitee.com/aizuda/flowlong)：国产开源的工作流引擎。

<h2 id="reactive">响应式库</h2>

* [RxJava](https://github.com/ReactiveX/RxJava)：JVM的Reactive扩展–一个使用Java VM的可观察序列编写异步和基于事件的程序的库。
* [Reactor](https://github.com/reactor/reactor-core)：JVM的非阻塞响应式基础。
* [Webflux](https://github.com/spring-projects/spring-framework/tree/main/spring-webflux)：Spring生态中基于Reactor的异步非阻塞Web框架。
* [Reactive Stream](https://github.com/reactive-streams/reactive-streams-jvm)：JVM的响应式流规范。
* [Vert.x](https://github.com/eclipse-vertx/vert.x)：一个用于在JVM上构建响应式应用程序的工具包。
* [Akka](https://github.com/akka/akka)：在JVM上构建高度并发、分布式和弹性的消息驱动应用程序。
* [RSocket](https://github.com/rsocket/rsocket-java)：RSocket的Java实现。
* [Agera](https://github.com/google/agera)：Android的响应式编程库。
* [Mobius](https://github.com/spotify/mobius)：用于管理状态演化和副作用的函数响应式框架。
* [Smallrye](https://github.com/smallrye/smallrye-mutiny)：直观的Java事件驱动响应式编程库。
* [AutoDispose](https://github.com/uber/AutoDispose)：RxJava流的自动绑定+处置。
* [Ratpack](https://github.com/ratpack/ratpack)：Ratpack是一个简单、功能强大的工具包，用于创建高性能Web应用程序。
* [Alibaba-RSocket-Broker](https://github.com/alibaba/alibaba-rsocket-broker)：Alibaba RSocket Broker是一款基于RSocket协议的响应式对等通讯系统，为通讯多方构建分布式的RPC、Pub/Sub、Streaming等通讯支持。
* [RSC](https://github.com/making/rsc)：RSocket Client CLI(RSC)旨在成为RSocket的curl。
* [Sqlbrite](https://github.com/square/sqlbrite)：SQLiteOpenHelper的轻量级包装器，它将响应式流语义引入SQL操作。
* [StorIO](https://github.com/pushtorefresh/storio)：SQLiteDatabase和ContentResolver的响应式API。
* [Rx-Preferences](https://github.com/f2prateek/rx-preferences)：Android的响应式SharedPreferences。
* [RxNetty](https://github.com/ReactiveX/RxNetty)：Netty响应式扩展适配器。
* [reactive-grpc](https://github.com/salesforce/reactive-grpc)：gRPC的响应式存根。
* [QBit](https://github.com/advantageous/qbit)：QBit是一个用于构建微服务的响应式编程库。
* [scalecube-services](https://github.com/scalecube/scalecube-services)：scalecube-services是一个高吞吐量、低延迟的响应式微服务库。
* [reactor-kafka](https://github.com/reactor/reactor-kafka)：Reactor响应式Kafka驱动程序。
* [reactive-audit](https://github.com/octo-online/reactive-audit)：旨在为项目实施中使用响应式架构提供帮助的审计工具。
* [Twitch4j](https://github.com/twitch4j/twitch4j)：模块化异步/同步/响应式Twitch API客户端/IRC客户端。
* [xoom-actors](https://github.com/vlingo/xoom-actors)：用于类型安全Actor模型的VLINGO XOOM平台SDK，使用Java和其他JVM语言提供响应式并发、高可扩展性、高吞吐量和弹性。

<h2 id="cache">缓存库</h2>

* [Guava](https://github.com/google/guava/tree/master/guava/src/com/google/common/cache)：Guava库提供的Java本地缓存工具。
* [Caffeine](https://github.com/ben-manes/caffeine)：Java的高性能缓存库。
* [Ehcache](https://github.com/ehcache/ehcache3)：一个纯Java的进程内缓存框架。
* [jetcache](https://github.com/alibaba/jetcache)：阿里开源的Java缓存框架。
* [DiskLruCache](https://github.com/JakeWharton/DiskLruCache)：基于磁盘的LRU缓存的Java实现，专门针对Android兼容性。
* [RxCache](https://github.com/VictorAlbertos/RxCache)：适用于Android和Java的响应式缓存库。
* [infinispan](https://github.com/infinispan/infinispan)：针对缓存的高并发键值对数据存储。
* [EVCache](https://github.com/Netflix/EVCache)：云分布式内存数据存储。
* [cache2k](https://github.com/cache2k/cache2k)：轻量级、高性能Java缓存。
* [AutoLoadCache](https://github.com/qiujiayu/AutoLoadCache)：基于AOP+注解等技术实现的高效的缓存管理解决方案
* [J2Cache](https://gitee.com/ld/J2Cache)：Java二级缓存框架，可以让应用支持两级缓存框架Ehcache(Caffeine) + redis。
* [RedisCache](https://gitee.com/darkidiot/RedisCache)：RedisCache是基于Jedis的SDK。

<h2 id="bigdata">大数据框架</h2>

* [Apache Hadoop](https://github.com/apache/hadoop)：Apache Hadoop软件库是一个框架，允许使用简单的编程模型跨计算机集群分布式处理大型数据集，由Yahoo开源。
* [Apache Flink](https://github.com/apache/flink)：Apache Flink是一个开源流处理框架，具有强大的流处理和批处理能力，由柏林工业大学发起的项目。
* [Apache Spark](https://github.com/apache/spark)：用于大规模数据处理的统一分析引擎，由加州大学柏克莱分校AMPLab开源。
* [Apache RocketMQ](https://github.com/apache/rocketmq)：云原生消息传递和流媒体平台，可以轻松构建事件驱动的应用程序，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：使用最广泛的分布式流平台，由LinkedIn开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：新一代云原生分布式消息流平台，由Yahoo开源。
* [Apache ShardingSphere](https://github.com/apache/shardingsphere)：分布式SQL事务和查询引擎，可在任何数据库上进行数据分片、扩展、加密等，由京东开源。
* [Apache Zookeeper](https://github.com/apache/zookeeper)：ZooKeeper是一个集中式服务，用于维护配置信息、命名、提供分布式同步、提供组服务。
* [Apache Pig](https://github.com/apache/pig)：基于Hadoop的大规模数据分析平台，由Yahoo开源。
* [Apache Beam](https://github.com/apache/beam)：Apache Beam是用于批处理和流数据处理的统一编程模型，由Google开源。
* [Apache Storm](https://github.com/apache/storm)：Apache Storm是一个分布式实时计算系统，由Twitter开源。
* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache SeaTunnel](https://github.com/apache/seatunnel)：下一代超高性能、分布式、海量数据集成工具，由中国通信学会开源技术委员会发起的项目。
* [Apache Zeppelin](https://github.com/apache/zeppelin)：基于Web的笔记本，支持使用SQL、Scala等进行数据驱动、交互式数据分析和协作文档。
* [Apache Hive](https://github.com/apache/hive)：基于Hadoop的一个数据仓库工具，可以将结构化的数据文件映射为一张数据库表，并提供类SQL查询功能，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，
* [Apache Iceberg](https://github.com/apache/iceberg)：Apache Iceberg是由Netflix开源的用于庞大分析数据集的开放表格式。
* [Apache Doris](https://github.com/apache/doris)：一个易于使用、高性能和统一的分析数据库，由百度开源。
* [Apache Hudi](https://github.com/apache/hudi)：新一代流式数据湖平台，由Uber开源。
* [Apache Calcite](https://github.com/apache/calcite)：Apache Calcite是一个动态数据管理框架。
* [Apache Nifi](https://github.com/apache/nifi)：Apache NiFi是一个易于使用、功能强大且可靠的系统，用于处理和分发数据，由美国国家安全局开源。
* [Apache Heron](https://github.com/apache/incubator-heron)：由Twitter开发的实时分析平台。
* [Apache Kylin](https://github.com/apache/kylin)：Apache Kylin是一个开源分布式分析引擎，由eBay贡献。
* [Apache StreamPark](https://github.com/apache/incubator-streampark)：简单易用的流媒体应用开发框架和运营平台。
* [Apache Linkis](https://github.com/apache/linkis)：Apache Linkis是一种计算中间件，充当上层应用程序和底层引擎(例如Apache Spark、Apache Hive和Apache Flink)之间的层，由微众开源。
* [Apache Flume](https://github.com/apache/flume)：由Cloudera软件公司产出的可分布式日志收集系统。
* [Apache Geode](https://github.com/apache/geode)：Apache Geode是一个数据管理平台，可在广泛分布的云架构中提供对数据密集型应用程序的实时、一致的访问，由GemStone开源。
* [Apache Gobblin](https://github.com/apache/gobblin)：用于流数据和批处理数据生态系统的分布式大数据集成框架，由LinkedIn开源。
* [Apache Parquet](https://github.com/apache/parquet-mr)：Apache Parquet是Hadoop生态系统中的任何项目都可以使用的列式存储格式，由Twitter和Cloudera共同开源。
* [Apache Ambari](https://github.com/apache/ambari)：基于Web的工具，用于安装、配置、管理和监视Hadoop集群，由Hortonworks开源。
* [Apache Drill](https://github.com/apache/drill)：Apache Drill是一个用于自描述数据的分布式MPP查询层，Google Dremel的开源版本。
* [Apache Bookkeeper](https://github.com/apache/bookkeeper)：一种可扩展、容错和低延迟的存储服务，针对仅附加工作负载进行了优化。
* [Apache Atlas](https://github.com/apache/atlas)：Apache Atlas框架是一组可扩展的核心基础治理服务-使企业能够有效地满足Hadoop内的合规性要求，并允许与整个企业数据生态系统集成，由Hortonworks开源。
* [Apache Sedona](https://github.com/apache/sedona)：处理大规模地理空间数据的集群计算框架。
* [Apache Paimon](https://github.com/apache/incubator-paimon)：Apache Paimon是一个流数据湖平台，支持高速数据摄取、变更数据跟踪和高效的实时分析。
* [Apache InLong](https://github.com/apache/inlong)：海量数据一站式全场景集成框架，由腾讯大数据团队开源。
* [Apache Accumulo](https://github.com/apache/accumulo)：Apache Accumulo是一种排序的分布式键/值存储，可提供强大、可扩展的数据存储和检索，由美国国家安全局开源。
* [Apache Phoenix](https://github.com/apache/phoenix)：Phoenix是一个Hbase的开源SQL引擎，由Salesforce开源。
* [Apache Oozie](https://github.com/apache/oozie)：基于工作流引擎的开源框架，是Hadoop平台的开源的工作流调度引擎，用来管理Hadoop作业，由Cloudera开源。
* [Apache Ozone](https://github.com/apache/ozone)：适用于Apache Hadoop的可扩展、冗余和分布式对象存储，由腾讯大数据团队开源。
* [Apache Celeborn](https://github.com/apache/incubator-celeborn)：Apache Celeborn是一种弹性且高性能的服务，用于洗牌和溢出数据，由阿里云开源。
* [Apache CarbonData](https://github.com/apache/carbondata)：高性能数据存储解决方案，由华为开源。
* [Apache Helix](https://github.com/apache/helix)：Helix是一个通用集群管理框架，用于自动管理节点集群上托管的分区、复制和分布式资源，由LinkedIn开源。
* [Apache Kyuubi](https://github.com/apache/kyuubi)：Apache Kyuubi是一个分布式多租户网关，用于在数据仓库和Lakehouse上提供无服务器SQL，由网易开源。
* [Piflow](https://github.com/cas-bigdatalab/piflow)：支持Spark的大数据流引擎，由科学大数据社区开源。
* [Hazelcast](https://github.com/hazelcast/hazelcast)：Hazelcast是一个实时流处理平台，可让你构建立即对数据采取操作的应用程序。
* [DataX](https://github.com/alibaba/DataX)：阿里开源的一个异构数据源离线同步工具。
* [BitSail](https://github.com/bytedance/bitsail)：BitSail是一个分布式高性能数据集成引擎，支持批量、流式和增量场景，由字节开源。
* [Scio](https://github.com/spotify/scio)：适用于Apache Beam和Google Cloud Dataflow的Scala API，由Spotify开源。
* [Presto](https://github.com/prestodb/presto)：用于大数据的分布式SQL查询引擎，由Facebook开源。
* [Voldemort](https://github.com/voldemort/voldemort)：Voldemort是一个分布式键值存储系统，Amazon Dynamo的开源克隆。
* [HiBench](https://github.com/Intel-bigdata/HiBench)：HiBench是一个大数据基准测试套件，由Intel开源。
* [ChunJun](https://github.com/DTStack/chunjun)：基于Flink的批流统一打造的数据同步工具，可以实现各种异构数据源之间的数据同步和计算，由袋鼠云开源。
* [DataHub](https://github.com/datahub-project/datahub)：由LinkedIn的数据团队开源的一款提供元数据搜索与发现的工具。
* [KnowStreaming](https://github.com/didi/KnowStreaming)：滴滴开源的Kafka运维管控平台。
* [Trino](https://github.com/trinodb/trino)：Trino是一个用于大数据的分布式SQL查询引擎，由Facebook开源。

<h2 id="file-parse">文件解析</h2>

这里包含用于解析各种文件格式的库，例如PDF、Word、Excel、CSV等。

<h4 id="pdf">PDF库</h4>

* [Apache PDFBox](https://pdfbox.apache.org/)：Apache下用于处理PDF文档的开源Java工具。
* [iText](https://github.com/itext/itext7)：一个易于使用的PDF函数库，用来编程创建PDF文件。
* [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)：本地托管的Web应用程序，允许你对PDF文件执行各种操作。
* [flyingsaucer](https://github.com/seam/reports)：Java EE的可移植扩展，提供用于从现有报告框架(JasperReports等)编译、填充和呈现报告(Excel、PDF等)的API。
* [OpenPDF](https://github.com/LibrePDF/OpenPDF)：OpenPDF是一个免费的Java库，用于使用LGPL和MPL开源许可证创建和编辑PDF文件。
* [x-easypdf](https://gitee.com/dromara/x-easypdf)：dromara开源的PDF文档库。
* [pdf2json](https://github.com/modesty/pdf2json)：一个PDF文件解析器，可将PDF二进制文件转换为基于文本的JSON，由PDF.JS的分支提供支持。
* [openhtmltopdf](https://github.com/danfickle/openhtmltopdf)：用于JVM的HTML到PDF的转换库，基于Flying Saucer和Apache PDF-BOX 2。
* [tabula-java](https://github.com/tabulapdf/tabula-java)：从PDF文件中提取表格的工具库。
* [PDFLayoutTextStripper](https://github.com/JonathanLink/PDFLayoutTextStripper)：将PDF文件转换为文本文件，同时保留原始PDF的布局。
* [Apache FOP](https://xmlgraphics.apache.org/fop/)：从XSL-FO创建PDF的库。
* [pdfcompare](https://github.com/red6/pdfcompare)：一个比较两个PDF文件的简单Java库。
* [JasperReports](https://github.com/TIBCOSoftware/jasperreports)：一个复杂的报表引擎。

<h4 id="excel">Excel库</h4>

* [Apache POI](https://github.com/apache/poi)：用于读写Microsoft Office二进制和OOXML文件格式的Java库。
* [EasyExcel](https://github.com/alibaba/easyexcel)：快速、简洁、解决大文件内存溢出的java处理Excel工具，由阿里开源。
* [autopoi](https://github.com/jeecgboot/autopoi)：国产的Excel和Word简易工具类，基于Apache POI。
* [docx4j](https://github.com/plutext/docx4j)：用于Word docx、Powerpoint pptx和Excel xlsx文件的基于JAXB的Java库。
* [myexcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入、导出、加密Excel等多项功能的工具包。
* [easypoi](https://gitee.com/lemur/easypoi)：国产的POI工具类。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：基于POI的Excel和Commons-CSV的CSV操作组件，大大减少代码量，提高开发效率。
* [fastexcel](https://github.com/dhatim/fastexcel)：快速生成和读取大Excel文件。
* [jxls](https://github.com/jxlsteam/jxls)：用于使用Excel模板创建Excel报告的Java库。
* [documents4j](https://github.com/documents4j/documents4j)：一个用于将文档转换为另一种文档格式的Java库。
* [xresloader](https://github.com/xresloader/xresloader)：跨平台Excel导表工具。
* [excel-streaming-reader](https://github.com/pjfanning/excel-streaming-reader)：使用Apache POI的流式Excel读取器的易于使用的实现。
* [cdc](https://gitlab.com/cdc-java/cdc-office)：与Office文档相关的实用程序。
* [auto-excel](https://github.com/feng-haitao/auto-excel)：Excel的快速导入和导出工具。

<h4 id="csv">CSV库</h4>

* [commons-csv](https://commons.apache.org/proper/commons-csv/)：Apache下的CSV操作库。
* [AdaptiveTableLayout](https://github.com/Cleveroad/AdaptiveTableLayout)：可以读取、编辑和写入CSV文件的库。
* [myexcel](https://github.com/liaochong/myexcel)：MyExcel是一个集导入、导出、加密Excel等多项功能的工具包，支持CSV文件。
* [super-csv](https://github.com/super-csv/super-csv)：一个快速、程序员友好、免费的Java CSV库。
* [FastCSV](https://github.com/osiegmar/FastCSV)：适用于Java的高性能CSV读取器和写入器。
* [Excel4j](https://gitee.com/Crab2Died/Excel4J)：基于POI的Excel和Commons-CSV的CSV操作组件，大大减少代码量，提高开发效率。
* [jackson-dataformats-text](https://github.com/FasterXML/jackson-dataformats-text)：支持通过Jackson抽象读取和写入CSV编码数据。
* [univocity-parsers](https://github.com/uniVocity/univocity-parsers)：速度最快功能最全的CSV开发库之一，同时支持TSV与固定宽度记录的读写。
* [scala-csv](https://github.com/tototoshi/scala-csv)：用于Scala的CSV读取器/写入器。
* [opencsv](https://opencsv.sourceforge.net/)：Opencsv是一个易于使用的Java CSV解析器库。
* [kotlin-csv](https://github.com/doyaaaaaken/kotlin-csv)：纯Kotlin CSV读取器/写入器。
* [flatpack](https://flatpack.sourceforge.net/)：积极开发的开源CSV库。
* [CSVeed](https://github.com/42BV/CSVeed)：轻量级、易于使用的基于Java的CSV实用程序。
* [Chronicle-Wire](https://github.com/OpenHFT/Chronicle-Wire)：支持多种格式的低垃圾Java序列化库。
* [javacsv](http://sourceforge.net/projects/javacsv)：Java CSV是一个小型快速开源Java库，用于读写CSV和纯分隔文本文件。
* [decs](https://github.com/diergo/decs)：Diergo Easy CSV Streamable：一个简单的Java 8 CSV解析器和生成器。
* [csv-utils](https://ostermiller.org/utils/CSV.html)：用于读取和写入CSV(逗号分隔值)文本文件的实用程序。

<h2 id="httpclient">HTTP客户端库</h2>

+ [Apache components-core](https://github.com/apache/httpcomponents-core)：Apache开源的HTTP客户端库。
+ [Apache components-client](https://github.com/apache/httpcomponents-client)：Apache开源的HTTP客户端库，相比components-core提供更流式的API。
+ [HttpAsyncClient](https://github.com/apache/httpasyncclient)：Apache开源的异步HTTP客户端库。
+ [Feign](https://github.com/OpenFeign/feign)：Feign是一个Java到HTTP客户端绑定器，其灵感来自于Retrofit、JAXRS-2.0和WebSocket。
+ [OkHttp](https://github.com/square/okhttp)：Square为JVM、Android和GraalVM精心设计的HTTP客户端。
+ [Retrofit](https://github.com/square/retrofit)：适用于Android和JVM的类型安全HTTP客户端。
+ [async-http-client](https://github.com/AsyncHttpClient/async-http-client)：适用于Java的异步HTTP和WebSocket客户端库。
+ [android-async-http](https://github.com/android-async-http/android-async-http)：适用于Android的异步、基于回调的HTTP客户端，构建于Apache的HttpClient库之上。
+ [google-http-java-client](https://github.com/googleapis/google-http-java-client)：Google开发的适用于Java的HTTP客户端库。
+ [Httpclientutil](https://github.com/Arronlong/httpclientutil)：基于HttpClient 4.4.1封装的工具类。
+ [rest-client](https://github.com/wisdom-projects/rest-client)：自动化测试REST API的工具，可以生成精美的测试报告和REST API文档。
+ [EasyHttp](https://github.com/getActivity/EasyHttp)：Android网络请求框架，简单易用。
+ [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)：基于HTTP协议，封装了OkHttp的网络请求框架，比Retrofit更简单易用。
+ [AndroidAsync](https://github.com/koush/AndroidAsync)：适用于Android的异步套接字、HTTP(s)和WebSocket库。基于NIO，而不是线程。
+ [chuck](https://github.com/jgilfelt/chuck)：适用于Android OkHttp客户端的应用内HTTP检查器。
+ [bilibili-android-client](https://github.com/HotBitmapGG/bilibili-android-client)：适用于Android的非官方BiliBili客户端。
+ [Unirest](https://github.com/Kong/unirest-java)：简化的轻量级HTTP客户端库。
+ [http-kit](https://github.com/http-kit/http-kit)：适用于Clojure的简单、高性能、事件驱动的HTTP客户端+服务器。
+ [Forest](https://github.com/dromara/forest)：由dromara社区开源的声明式HTTP客户端框架。
+ [jetty-reactive-httpclient](https://github.com/jetty-project/jetty-reactive-httpclient)：Jetty HttpClient的响应流包装器。
+ [jodd-http](https://github.com/oblac/jodd-http)：简单的Java HTTP客户端。
+ [esa-restclient](https://github.com/esastack/esa-restclient)：一个基于Netty的异步事件驱动的HTTP客户端。
+ [sslcontext-kickstart](https://github.com/Hakky54/sslcontext-kickstart)：一个轻量级库，用于配置基于SSLContext或其他属性(例如TrustManager、KeyManager或受信任证书)的 HTTP客户端或服务器，以通过SSLFactory提供的单向身份验证或双向身份验证通过SSL/TLS进行通信。

<h2 id="webserver">WebServer</h2>

* [Netty](https://github.com/netty/netty)：事件驱动的异步网络应用框架。
* [Apache Tomcat](https://github.com/apache/tomcat)：Apache Tomcat是Java Servlet、JavaServer Pages、Java EL和Java WebSocket技术的开源实现。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Helidon Nima](https://github.com/helidon-io/helidon/tree/helidon-3.x/webserver)：基于JDK虚拟线程的轻量级Web服务器。
* [Undertow](https://github.com/undertow-io/undertow)：高性能非阻塞Web服务器。
* [Wildfly](https://github.com/wildfly/wildfly)：WildFly应用服务器。
* [Weblogic](https://www.oracle.com/sg/java/weblogic/)：Oracle的商业应用服务器。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，由IBM提供。
* [Jetty](https://github.com/eclipse/jetty.project)：Jetty是一个轻量级、高度可扩展的基于Java的Web服务器和Servlet引擎。
* [Glassfish](https://github.com/eclipse-ee4j/glassfish)：Eclipse基金会下开源的Jakarta服务器。
* [Payara](https://github.com/payara/Payara)：Payara Server是一个开源中间件平台，支持在本地、云端或混合环境中可靠、安全地部署Java EE(Jakarta EE)和MicroProfile应用程序。
* [Apache Geronimo](https://geronimo.apache.org/)：Apache基金会下开源的Java EE服务器。
* [hella](https://github.com/bbeaupain/hella-http)：适用于Java的Hella快速HTTP服务器库。
* [microhttp](https://github.com/ebarlas/microhttp)：快速、可扩展、独立、单线程Java Web服务器。
* [Apache MINA](https://github.com/apache/mina)：Apache MINA是一个网络应用框架，可以帮助用户开发高性能和高可扩展性的网络应用程序。
* [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)：用纯Java编写的准系统WebSocket客户端和服务器实现。
* [ZIO](https://github.com/zio/zio)：一个类型安全、可组合的库，用于Scala中的异步和并发编程。
* [zfoo](https://github.com/zfoo-project/zfoo)：极致性能的Java服务器框架，RPC，游戏服务器框架，Web应用服务器框架。
* [Grizzly](https://github.com/eclipse-ee4j/grizzly)：Grizzly的目标是帮助开发人员使用NIO构建可扩展且强大的服务器，并提供扩展框架组件。
* [Reactor-Netty](https://github.com/reactor/reactor-netty)：TCP/HTTP/UDP/QUIC客户端/服务器，使用基于Netty的Reactor。
* [nanohttpd](https://github.com/NanoHttpd/nanohttpd)：微型、可轻松嵌入Java中的HTTP服务器。
* [nio-server](https://github.com/jjenkov/java-nio-server)：一个始终使用非阻塞IO的Java NIO服务器。
* [servicetalk](https://github.com/apple/servicetalk)：苹果开源的网络框架。
* [graphhopper](https://github.com/graphhopper/graphhopper)：OpenStreetMap的开源路由引擎，将其用作Java库或独立的Web服务器。
* [AndServer](https://github.com/yanzhenjie/AndServer)：Android平台的Web服务器和Web框架。
* [rapidoid](https://github.com/rapidoid/rapidoid)：极其快速、简单且功能强大的Java Web框架和HTTP服务器。
* [game-server](https://github.com/jzyong/game-server)：分布式Java游戏服务器，包括集群管理服务器、网关服务器、大厅服务器、游戏逻辑服务器。
* [restcommander](https://github.com/eBay/restcommander)：快速并行异步HTTP客户端即服务，用于监控和管理10000个Web服务器，由eBay开发。
* [webbit](https://github.com/webbit/webbit)：基于Java事件的WebSocket和HTTP服务器。
* [para](https://github.com/Erudika/para)：用于快速构建Web和移动应用程序的多租户后端服务器。
* [methanol](https://github.com/mizosoft/methanol)：Java的轻量级HTTP扩展。

<h2 id="jakartaee">Jakarta EE实现</h2>

* [Payara](https://github.com/payara/Payara)：Payara Server是一个开源中间件平台，支持在本地、云端或混合环境中可靠、安全地部署Java EE(Jakarta EE)和MicroProfile应用程序。
* [Apache TomEE](https://github.com/apache/tomee)：一个轻量级但功能强大的Java EE应用服务器，具有功能丰富的工具。
* [Piranha](https://github.com/piranhacloud/piranha)：现代云运行时。
* [Open Liberty](https://github.com/OpenLiberty/open-liberty)：Open Liberty是一个高度可组合、快速启动的动态应用程序服务器运行时环境，由IBM提供。
* [KumuluzEE](https://github.com/kumuluz/kumuluzee)：轻量级开源框架，用于使用标准Jakarta EE技术开发微服务并将Jakarta EE迁移到云原生架构。
* [Cricket](https://github.com/gskorupa/cricket)：Java微服务框架。
* [FlyingServer](http://www.antdb.net/flyingserver)：满足Jakarta EE 8规范的通用应用服务器中间件产品。
* [Apusic](https://www.apusic.com/list-117.html)：金蝶Apusic应用服务器是一款标准、安全、高效、集成并具丰富功能的企业级应用服务器软件，全面支持Jakarta EE 8/9的技术规范。
* [Eclipse Glassfish](https://github.com/eclipse-ee4j/glassfish)：Eclipse GlassFish是由Eclipse基金会赞助的Jakarta EE兼容实现。
* [FUJITSU](https://www.fujitsu.com/jp/software/interstage/apserver)：由富士通提供的兼容Jakarta EE规范的应用服务器。
* [IBM WebSphere](https://www.ibm.com/support/pages/node/6250961#asset/runtimes-wlp-javaee8)：由IBM提供的兼容Jakarta EE规范的应用服务器。
* [InforSuite AS](https://www.inforbus.com/as.html)：国内通过Jakarta EE 9、8及Java EE 8、7、6完整兼容认证的企业级中间件，由中创开发。
* [RedHat JBoss](https://www.redhat.com/en/technologies/jboss-middleware/application-platform)：RedHat提供的兼容Jakarta EE的企业应用平台。
* [Primeton AppServer](https://www.primeton.com/products/pas/)：支持Jakarta EE Platform 8国际标准规范支持Web容器所有特性，由普元提供。
* [WildFly](https://www.wildfly.org/downloads/)：WildFly是一款功能强大、模块化且轻量级的应用程序服务器。

<h2 id="rpc">RPC框架</h2>

* [Dubbo](https://github.com/apache/dubbo)：阿里开源的RPC和微服务框架。
* [gRPC](https://github.com/grpc/grpc-java)：Google RPC的Java实现，基于HTTP/2的RPC。
* [finagle](https://github.com/twitter/finagle)：推特开源的容错、协议无关的RPC系统。
* [starlight](https://github.com/baidu/starlight)：百度RPC、多协议、高性能RPC的Java实现。
* [motan](https://github.com/weibocom/motan)：一个跨语言远程过程调用(RPC)框架，用于快速开发高性能分布式服务，由微博开源。
* [Sofa-RPC](https://github.com/sofastack/sofa-rpc)：一个高性能、高扩展性、生产级的Java RPC框架，由蚂蚁金服开源。
* [pigeon](https://github.com/dianping/pigeon)：大众点评开源的RPC框架。
* [Apache Thrift](https://github.com/apache/thrift)：Thrift是一个由Facebook开源的轻量级、独立于语言的软件堆栈，用于点对点RPC实现的框架。
* [MSEC](https://github.com/Tencent/MSEC)：由腾讯QQ团队开源，它是一个后端DEV & OPS引擎，包括RPC、名称查找、负载均衡、监控、发布和容量管理。
* [octo-rpc](https://github.com/Meituan-Dianping/octo-rpc)：OCTO-RPC是支持Java和C++的企业级通信框架，在RPC服务之上扩展了丰富的服务治理功能，由美团开源。
* [DeFiBus](https://gitee.com/WeBank/DeFiBus)：由微众银行开源的分布式金融级消息总线，提供了RPC同步调用、MQ的异步事件通知、事件组播和广播等常用服务调用和消息模式。
* [pinpoint-rpc](https://github.com/pinpoint-apm/pinpoint/tree/master/rpc)：Naver开源的RPC框架，服务于Pinpoint。
* [TChannel](https://github.com/uber/tchannel-java)：TChannel协议的Java实现，由Uber开源。
* [TarsJava](https://github.com/TarsCloud/TarsJava)：Java语言框架RPC源码实现，在Tars基金会下开源。
* [Jprotobuf-rpc-socket](https://github.com/baidu/Jprotobuf-rpc-socket)：Protobuf RPC是一种基于TCP协议的二进制RPC通信协议的Java实现，由百度开源。
* [storm](https://github.com/nathanmarz/storm)：分布式和容错实时计算：流处理、连续计算、分布式RPC等。
* [NettyRpc](https://github.com/luxiaoxun/NettyRpc)：一个基于Netty、ZooKeeper和Spring的简单RPC框架。
* [koalas-rpc](https://gitee.com/dromara/koalas-rpc)：dromara社区开源的高可用可拓展的RPC框架。
* [xxl-rpc](https://github.com/xuxueli/xxl-rpc)：国产高性能、分布式RPC框架。
* [Turbo](https://github.com/hank-whu/turbo-rpc)：Turbo是一个超快速响应式RPC框架。
* [rpc-framework](https://github.com/Snailclimb/guide-rpc-framework)：一款基于Netty + Kyro + Zookeeper实现的自定义RPC框架。
* [NettyRPC](https://github.com/tang-jie/NettyRPC)：NettyRPC是基于Netty的高性能Java RPC服务器，使用kryo、hessian、protostuff支持消息序列化。

<h2 id="message">消息中间件</h2>

* [Apache RocketMQ](https://github.com/apache/rocketmq)：云原生消息传递和流媒体平台，可以轻松构建事件驱动的应用程序，由阿里开源。
* [Apache Kafka](https://github.com/apache/kafka)：使用最广泛的分布式流平台，由领英开源。
* [Apache Pulsar](https://github.com/apache/pulsar)：新一代云原生分布式消息流平台，由雅虎开源。
* [Apache ActiveMQ](https://github.com/apache/activemq)：一个比较传统的高性能消息代理。
* [BifroMQ](https://github.com/baidu/bifromq)：采用Serverless架构的MQTT代理实现，由百度开源。
* [QMQ](https://github.com/qunarcorp/qmq)：QMQ是去哪儿网内部广泛使用的消息中间件。
* [PMQ](https://github.com/ppdaicorp/pmq)：信也科技开源的轻量级分布式消息队列。
* [Paho](https://github.com/eclipse/paho.mqtt.java)：Eclipse Paho Java MQTT客户端库，Paho是一个Eclipse IoT项目。
* [JeroMQ](https://github.com/zeromq/jeromq)：ZeroMQ的Java版本。
* [HiveMQ](https://github.com/hivemq/hivemq-community-edition)：HiveMQ是一个基于Java的开源MQTT代理，完全支持MQTT 3.x和MQTT 5。
* [JGroups](https://github.com/belaban/JGroups)：JGroups是一个集群库，允许成员交换消息。
* [Apache Camel](https://github.com/apache/camel)：能够快速轻松地集成使用或生成数据的各种系统的开源框架。
* [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue)：Chronicle Queue是一个适用于高性能应用程序的持久低延迟消息传递框架。
* [HornetQ](https://github.com/hornetq/hornetq)：HornetQ是一个开源项目，用于构建多协议、可嵌入、高性能、集群、异步消息传递系统。

<h2 id="db">数据库</h2>

这里包含使用Java编写的数据库软件

<h4 id="search-engine">搜索引擎</h4>

* [ElasticSearch](https://github.com/elastic/elasticsearch)：免费开源的分布式、RESTful搜索引擎。
* [Apache Lucene](https://github.com/apache/lucene)：开源搜索引擎。
* [Solr](https://github.com/apache/solr)：Solr是一款流行、速度极快的开源搜索平台，基于Apache Lucene构建。
* [OpenSearch](https://github.com/opensearch-project/OpenSearch)：开源分布式RESTful搜索引擎。
* [yacy](https://github.com/yacy/yacy_search_server)：分布式点对点Web搜索引擎和Intranet搜索设备。
* [Fess](https://github.com/codelibs/fess)：Fess是非常强大且易于部署的企业搜索服务器。
* [OpenSearchServer](https://github.com/jaeksoft/opensearchserver)：开源企业级搜索引擎软件。

<h4 id="graph-db">图数据库</h4>

* [Neo4j](https://github.com/neo4j/neo4j)：使用最广泛的图数据库。
* [JanusGraph](https://github.com/JanusGraph/janusgraph)：开源的分布式图数据库。
* [Apache HugeGraph](https://github.com/apache/incubator-hugegraph)：支持超过100+十亿数据、高性能和可扩展性的图数据库(包括OLTP引擎和REST API和后端)，该项目正在Apache基金会下孵化，最早由百度开源。
* [Titan](https://github.com/thinkaurelius/titan)：分布式图数据库。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型。
* [Apache TinkerPop](https://github.com/apache/tinkerpop)：为图数据库(OLTP)和图分析系统(OLAP)提供图计算功能。
* [GraphJet](https://github.com/twitter/GraphJet)：GraphJet是一个实时图处理库。
* [GraphDB](https://www.ontotext.com/)：企业级RDF和图数据库，具有高效推理、集群和外部索引同步支持。它还支持通过SPARQL对知识图和GraphQL进行SQL JDBC访问。
* [Stardog](https://www.stardog.com/)：一款商业图数据库。
* [BlazeGraph](https://github.com/blazegraph/database)：一款开源的高性能图数据库。
* [TypeDB](https://github.com/vaticle/typedb)：TypeDB是一个强类型数据库，具有丰富且逻辑的类型系统。
* [Gaffer](https://github.com/gchq/Gaffer)：支持属性聚合的大规模实体和关系数据库，由英国政府通讯总部开源。
* [HyperGraphDB](https://github.com/hypergraphdb/hypergraphdb)：专为人工智能和语义Web项目设计的图数据库，也可以用作各种规模项目的嵌入式面向对象数据库。

<h4 id="embedded-db">嵌入式数据库</h4>

* [H2](https://github.com/h2database/h2database)：用Java编写的嵌入式RDBMS。
* [Apache Derby](https://github.com/apache/derby)：Derby是一个纯Java、基于标准的关系数据库引擎。
* [HSQLDB](https://hsqldb.org/)：HSQLDB是一个用Java编写的关系数据库引擎。
* [QuickIO](https://github.com/artbits/quickio)：Java嵌入式数据库。
* [MapDB](https://github.com/jankotek/mapdb)：MapDB提供由磁盘存储或堆外内存支持的并发映射、集合和队列。它是一个快速且易于使用的嵌入式Java数据库引擎。
* [ObjectBox](https://github.com/objectbox/objectbox-java)：Java和Android数据库-快速且轻量级，无需任何ORM。
* [Xodus](https://github.com/JetBrains/xodus)：JetBrains YouTrack和JetBrains Hub使用的事务性无模式嵌入式数据库。
* [SirixDB](https://github.com/sirixdb/sirix)：SirixDB 是一个嵌入式、时态、进化数据库系统，它使用仅附加方法来存储不可变的修订。
* [LMDB](https://github.com/lmdbjava/lmdbjava)：Java版闪电内存数据库(LMDB)：低延迟、事务性、排序、嵌入式、键值存储。
* [Nitrite](https://github.com/nitrite/nitrite-java)：Java嵌入式NoSQL文档存储。
* [JDBM3](https://github.com/jankotek/JDBM3)：嵌入式键值Java数据库。
* [HerdDB](https://github.com/diennea/herddb)：可嵌入JVM的分布式数据库。

<h4 id="nosql-db">NoSQL数据库 & 其他</h4>

* [Apache Cassandra](https://github.com/apache/cassandra)：Cassandra是一种高度可扩展的分区行存储，由Facebook开源。
* [Apache HBase](https://github.com/apache/hbase)：Apache HBase是一个开源、分布式、版本化、面向列的存储，
* [Apache IoTDB](https://github.com/apache/iotdb)：IoTDB是时序数据的数据管理系统，为用户提供数据采集、存储、分析等特定服务，该项目由清华大学主导，在Apache基金会下开源。
* [Apache Pinot](https://github.com/apache/pinot)：实时分布式OLAP数据存储，由领英开源。
* [Apache Druid](https://github.com/apache/druid)：高性能实时分析数据库，由MetaMarkets开源。
* [Apache Doris](https://github.com/apache/doris)：一个易于使用、高性能和统一的分析数据库，由百度开源。
* [Apache Ignite](https://github.com/apache/ignite)：分布式数据库，用于以内存速度进行高性能计算，由GridGain开源。
* [Apache Kylin](https://github.com/apache/kylin)：适用于大数据的极致OLAP引擎，由eBay开源。
* [OrientDB](https://github.com/orientechnologies/orientdb)：OrientDB是最通用的DBMS，在一个多模型产品中支持图、文档、响应式、全文和地理空间模型。
* [Paper](https://github.com/pilgr/Paper)：Paper是Android上Java/Kotlin对象的快速类NoSQL存储，具有自动模式迁移支持。
* [OpenLineage](https://github.com/OpenLineage/openlineage)：谱系元数据收集的开放标准。
* [QuestDB](https://github.com/questdb/questdb)：用于快速摄取和SQL查询的开源时间序列数据库。
* [CrateDB](https://github.com/crate/crate)：CrateDB是一个分布式且可扩展的SQL数据库，用于近乎实时地存储和分析大量数据，甚至可以进行复杂的查询。它与PostgreSQL兼容，并且基于Lucene。

<h2 id="db-conn">数据库连接池</h2>

* [Druid](https://github.com/alibaba/druid)：阿里云计算平台DataWorks团队出品，为监控而生的数据库连接池。
* [HikariCP](https://github.com/brettwooldridge/HikariCP)：可靠、高性能的JDBC连接池。
* [Apache commons-dbcp](https://github.com/apache/commons-dbcp)：Apache下开源的数据库连接池。
* [c3p0](https://github.com/swaldman/c3p0)：一个成熟的、高度并发的JDBC连接池库，支持缓存和重用PreparedStatements。
* [bonecp](https://github.com/wwadge/bonecp)：BoneCP是一种JDBC连接池实现，它通过最大限度地减少锁争用来实现高性能，从而为应用程序提供更大的吞吐量。
* [flexy-pool](https://github.com/vladmihalcea/flexy-pool)：可以向给定的连接池添加指标和故障转移策略，使其能够按需调整大小。
* [Agroal](https://github.com/agroal/agroal)：一个小巧的数据库连接池。
* [vibur-dbcp](https://github.com/vibur/vibur-dbcp)：并发和动态JDBC连接池。
* [jdbc-pool](https://tomcat.apache.org/tomcat-7.0-doc/jdbc-pool.html)：Tomcat JDBC连接池。

<h2 id="ai">人工智能</h2>

这里包含了Java里面人工智能领域相关的库。

<h4 id="ml">机器学习</h4>

* [Angel](https://github.com/Angel-ML/angel)：用于大规模机器学习的灵活且强大的参数服务器，由腾讯联合北京大学开源。
* [Spark-MLlib](https://github.com/apache/spark/tree/master/mllib)：MLlib是Apache Spark的可扩展机器学习库。
* [Alluxio](https://github.com/Alluxio/alluxio)：用于云中分析和机器学习的数据编排。
* [Smile](https://github.com/haifengl/smile)：Smile是一个使用Java和Scala编写的快速且全面的机器学习、NLP、线性代数、图形、插值和可视化系统。
* [Flink-ML](https://github.com/apache/flink-ml)：Apache Flink机器学习库。
* [Apache Mahout](https://github.com/apache/mahout)：Apache Mahout项目的目标是构建一个用于快速创建可扩展、高性能机器学习应用程序的环境。
* [Weka](https://git.cms.waikato.ac.nz/weka/weka)：Weka是用于数据挖掘任务的机器学习算法的集合。它包含用于数据准备、分类、回归、聚类、关联规则挖掘和可视化的工具。
* [Apache Samoa](https://github.com/apache/incubator-samoa)：Apache SAMOA是一个用于挖掘大数据流的平台。它是一个分布式流式机器学习(ML)框架，包含分布式流式机器学习算法的编程抽象。
* [Alink](https://github.com/alibaba/Alink)：Alink是基于Flink的机器学习算法平台，由阿里巴巴计算平台PAI团队开发。
* [SynapseML](https://github.com/microsoft/SynapseML)：SynapseML是一个开源库，可简化大规模可扩展机器学习(ML)管道的创建，由微软开源。
* [PredictionIO](https://github.com/apache/predictionio)：面向开发人员和ML工程师的机器学习服务器。
* [H2O](https://github.com/h2oai/h2o-2)：H2O是用于智能应用的机器学习API，它在大数据上对统计学、机器学习和数学进行了规模化。
* [Apache Submarine](https://github.com/apache/submarine)：Submarine是云原生机器学习平台。
* [grobid](https://github.com/kermitt2/grobid)：用于从学术文档中提取信息的机器学习软件。
* [EasyML](https://github.com/ICT-BDA/EasyML)：EasyML是一种基于数据流的通用系统，可简化将机器学习算法应用于现实世界任务的过程。
* [DeepDive](https://github.com/HazyResearch/deepdive)：斯坦福大学开发的信息抽取系统。
* [Oryx](https://github.com/OryxProject/oryx)：Apache Spark、Apache Kafka上的Lambda架构，用于实时大规模机器学习。
* [Seldon](https://github.com/SeldonIO/seldon-server)：基于Kubernetes构建的机器学习平台和推荐引擎。
* [Tribuo](https://github.com/oracle/tribuo)：Oracle开源的Java机器学习库。
* [aerosolve](https://github.com/airbnb/aerosolve)：一个从头开始设计的人性化机器学习库。
* [TransmogrifAI](https://github.com/salesforce/TransmogrifAI)：TransmogrifAI是一个AutoML库，用于在Apache Spark上构建模块化、可重用、强类型的机器学习工作流程，只需最少的手动调整。
* [QuickML](https://github.com/sanity/quickml)：Java中快速且易于使用的决策树学习器。
* [Datumbox](https://github.com/datumbox/datumbox-framework)：Datumbox是一个用Java编写的开源机器学习框架，可以快速开发机器学习和统计应用程序。
* [Dagli](https://github.com/linkedin/dagli)：用于定义机器学习模型的框架，包括特征生成和转换，如有向无环图(DAG)。
* [Meka](https://github.com/Waikato/meka)：使用Weka机器学习框架的多标签分类器和评估程序。
* [Mallet](https://github.com/mimno/Mallet)：MALLET是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用。
* [ojAlgo](https://github.com/optimatika/ojAlgo)：与数学、线性代数和优化有关的开源Java代码。
* [RapidMiner](https://rapidminer.com/)：RapidMiner是一个数据科学平台，通过GUI和Java API提供各种机器学习算法。
* [Moa](https://github.com/Waikato/moa)：MOA是一个用于大数据流挖掘的开源框架，它包括一系列机器学习算法(分类、回归、聚类、异常值检测、概念漂移检测和推荐系统)和评估工具。
* [Encog](https://github.com/jeffheaton/encog-java-core)：Encog是2008年创建的一个纯Java机器学习框架，用于支持遗传编程、NEAT/HyperNEAT和其他神经网络技术。
* [Neuroph](https://github.com/neuroph/neuroph)：Java神经网络框架。
* [ELKI](https://github.com/elki-project/elki)：用Java编写的开源数据挖掘软件。
* [SimpleDNN](https://github.com/KotlinNLP/SimpleDNN)：SimpleDNN是一个用Kotlin编写的机器学习轻量级开源库，旨在支持自然语言处理任务中的相关神经网络架构。
* [JSAT](https://github.com/EdwardRaff/JSAT)：Java统计分析工具，用于机器学习的Java库。
* [Java-ML](https://github.com/charliermarsh/java-ml)：多种机器学习分类算法的Java实现。
* [htm.java](https://github.com/numenta/htm.java)：Java中的分层临时内存实现-Numenta智能计算平台(NuPIC)的官方社区驱动Java端口。

<h4 id="nlp">自然语言处理</h4>

* [CoreNLP](https://github.com/stanfordnlp/CoreNLP)：一套Java核心NLP工具，用于标记化、句子分段、NER、解析、共指、情感分析等，由斯坦福开源。
* [OpenNLP](https://github.com/apache/opennlp)：Apache OpenNLP库是一个基于机器学习的工具包，用于处理自然语言文本。
* [CogCompNLP](https://github.com/CogComp/cogcomp-nlp)：CogComp的自然语言处理库。
* [FudanNLP](https://github.com/FudanNLP/fnlp)：中文自然语言处理工具包。
* [Lingua](https://github.com/pemistahl/lingua)：适用于Java和JVM的最准确的自然语言检测库，适用于长文本和短文本。
* [DKPro-Core](https://github.com/dkpro/dkpro-core)：基于Apache UIMA框架的自然语言处理(NLP)软件组件集合。
* [Mallet](https://github.com/mimno/Mallet)：MALLET是一个基于Java的包，用于统计自然语言处理、文档分类、聚类、主题建模、信息提取和其他文本机器学习应用。
* [Jcseg](https://github.com/lionsoul2014/jcseg)：Jcseg是一个用Java开发的轻量级NLP框架。
* [nlp-lang](https://github.com/NLPchina/nlp-lang)：这个项目是一个基本包，封装了大多数NLP项目中常用工具。
* [Mynlp](https://github.com/mayabot/mynlp)：一个生产级、高性能、模块化、可扩展的中文NLP工具包。
* [Apache UIMA](https://github.com/apache/uima-uimaj)：UIMA应用程序是分析大量非结构化信息以发现与最终用户相关的知识的软件系统。
* [ctakes](https://github.com/apache/ctakes)：Apache cTAKES 是一个用于临床文本的自然语言处理(NLP)平台。
* [Apache NLPCraft](https://github.com/apache/incubator-nlpcraft)：将自然语言转换为操作的API。
* [EasyAI](https://gitee.com/ldp_dpsmax/easyAi)：通过简单的API调用就可以实现常用的图像内物体的识别，定位等图像AI服务，及自然语言分类处理服务。

<h4 id="dl">深度学习</h4>

* [deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)：Eclipse Deeplearning4J(DL4J)生态系统是一组旨在支持基于JVM的深度学习应用程序的所有需求的项目。
* [djl](https://github.com/deepjavalibrary/djl)：Java中与引擎无关的深度学习框架，由亚马逊开源。
* [KotlinDL](https://github.com/Kotlin/kotlindl)：用Kotlin编写的高级深度学习API，受到Keras的启发。
* [multi-model-server](https://github.com/awslabs/multi-model-server)：用于服务神经网络模型进行推理的工具，由亚马逊开源。
* [neuralnetworks](https://github.com/ivan-vasilev/neuralnetworks)：Java深度学习算法和带有GPU加速的深度神经网络。
* [TonY](https://github.com/tony-framework/TonY)：TonY是一个在Apache Hadoop上本地运行深度学习作业的框架。
* [Porcupine](https://github.com/Picovoice/porcupine)：由深度学习提供支持的设备上唤醒词检测。
* [dl-on-flink](https://github.com/flink-extended/dl-on-flink)：旨在集成Flink和深度学习框架(例如TensorFlow、PyTorch等)，以在Flink集群上实现分布式深度学习训练和推理。
* [onyx](https://github.com/hanuor/onyx)：一个Android库，使用人工智能、机器学习和深度学习等技术来让开发人员理解他们在应用程序中显示的内容。
* [OpenDL](https://github.com/guoding83128/OpenDL)：Spark上的深度学习训练框架。
* [TensorDash](https://github.com/CleanPegasus/TensorDash)：TensorDash是一款应用程序，可让你远程监控深度学习模型的指标，并在模型训练完成或崩溃时通知你。
* [Omega-AI](https://gitee.com/iangellove/omega-ai)：基于Java打造的深度学习框架，帮助你快速搭建神经网络，实现训练或测试模型，引擎支持自动求导，多线程与GPU运算。
* [DLSF](https://github.com/Cloudslab/DLSF)：用于随机雾云计算环境的基于深度学习的调度程序。
* [dl_inference](https://github.com/wuba/dl_inference)：通用深度学习推理工具，可在生产环境中快速上线由TensorFlow、PyTorch、Caffe框架训练出的深度学习模型。

<h4 id="genetic">遗传算法</h4>

* [Jenetics](https://github.com/jenetics/jenetics)：Jenetics是一种用Java编写的高级遗传算法，它提供了遗传算法概念的清晰分离。
* [Watchmaker](https://github.com/dwdyer/watchmaker)：Watchmaker Framework是一个用Java实现遗传算法的框架。
* [ECJ 23](https://cs.gmu.edu/~eclab/projects/ecj/)：ECJ 23是一个基于Java的研究框架，为遗传算法提供强大的算法支持。
* [JGAP](https://sourceforge.net/projects/jgap/)：JGAP是作为Java框架提供的遗传编程组件。
* [Eva](https://github.com/decorators-squad/eva)：Eva是一个简单的Java OOP进化算法框架。

<h4 id="expert-system">专家系统</h4>

* [Apache Jena](https://github.com/apache/jena)：Apache Jena是一个开源Java框架，用于从RDF数据构建语义Web和链接数据应用程序。它提供了一个API来从RDF图中提取数据并写入RDF图中。
* [PowerLoom](https://www.isi.edu/isd/LOOM/PowerLoom/)：PowerLoom是一个用于创建智能、基于知识的应用程序的平台。
* [d3web](https://github.com/denkbares)：d3web是一个开源推理引擎，用于开发、测试问题解决知识并将其应用于给定的问题情况，其中已经包含许多算法。
* [Eye](https://github.com/eyereasoner/eye)：Eye是一个用于执行半逆向推理的开源推理引擎。
* [Tweety](https://github.com/TweetyProjectTeam/TweetyProject)：Tweety是用于人工智能和知识表示的逻辑方面的Java框架的集合。
* [OptaPlanner](https://github.com/kiegroup/optaplanner)：OptaPlanner是一个基于Java的约束求解器。

<h4 id="math">数学库</h4>

* [SuanShu](https://github.com/aaiyer/SuanShu)：SuanShu是一个Java数学库，用于数值分析、统计、求根、线性代数、优化等。

<h2 id="concurrency">并发编程</h2>

* [Disruptor](https://github.com/LMAX-Exchange/disruptor)：高性能线程间消息传递库。
* [Quasar](https://github.com/puniverse/quasar)：JVM上的Fiber、Channel和Actor实现。
* [JCTools](https://github.com/JCTools/JCTools)：用于JVM的Java并发工具，该项目旨在提供JDK目前缺少的一些并发数据结构。
* [asyncTool](https://gitee.com/jd-platform-opensource/asyncTool)：京东开源的多线程编排一站式解决方案。
* [thread-weaver](https://github.com/google/thread-weaver)：用于测试多线程代码的Java框架。
* [Kilim](https://github.com/kilim/kilim)：Java的轻量级线程，具有消息传递、NIO、HTTP和调度支持。
* [EA-Async](https://github.com/electronicarts/ea-async)：EA-Async在JVM中实现Async-Await方法，它允许程序员以顺序方式编写异步代码。
* [TransmittableThreadLocal](https://github.com/alibaba/transmittable-thread-local)：提供了一个增强的InheritableThreadLocal，即使使用线程池组件也可以在线程之间传输值，由阿里开源。
* [concurrentlinkedhashmap](https://github.com/ben-manes/concurrentlinkedhashmap)：Java的ConcurrentLinkedHashMap。
* [trickle](https://github.com/spotify/trickle)：用于编写异步代码的小型库，由Spotity开源。
* [jcstress](https://github.com/openjdk/jcstress)：jcstress是实验性工具和一套测试，用于帮助研究JVM、类库和硬件中并发支持的正确性。
* [jcommon](https://github.com/facebookarchive/jcommon)：并发、集合、统计/分析、配置、测试等，由Facebook开发。
* [Coroutines](https://github.com/esoco/coroutines)：协作并发的纯Java实现，又名协程。
* [Menagerie](https://github.com/sfines/menagerie)：基于ZooKeeper的Java并发库。
* [tascalate-concurrent](https://github.com/vsilaev/tascalate-concurrent)：阻塞可取消java.util.concurrent.CompletionStage的实现以及java.util.concurrent.ExecutorService的相关扩展。
* [Coroutines](https://github.com/offbynull/coroutines)：允许编写协程的Java工具包。
* [completable-futures](https://github.com/spotify/completable-futures)：Java 8中处理Future的实用程序，由Spotify开源。
* [DynamicTp](https://github.com/dromara/dynamic-tp)：基于配置中心的轻量级动态线程池，内置监控告警功能，集成常用中间件线程池管理，可通过SPI自定义扩展实现，由dromara社区开源。
* [TaskManager](https://github.com/iqiyi/TaskManager)：一种支持依赖关系、任务兜底策略的任务调度管理工具，由爱奇艺开发。
* [hippo4j](https://github.com/opengoofy/hippo4j)：国产异步线程池框架，支持线程池动态变更、监控、报警。
* [Gobrs-Async](https://gitee.com/dromara/gobrs-async)：多线程并发编程框架，由dromara社区开源。
* [fact-async](https://gitee.com/china2010pan/fact-async)：fact-async是一个基于Spring的异步并行框架。

<h2 id="security">安全</h2>

* [Spring Security](https://github.com/spring-projects/spring-security)：Spring生态提供的安全框架。
* [Apache Shiro](https://github.com/apache/shiro)：Apache下开源的功能强大且易于使用的Java安全框架，可以执行身份验证、授权、加密和会话管理。
* [Tink](https://github.com/google/tink)：Tink是一个多语言、跨平台、开源库，提供安全、易于正确使用且难以误用的加密API，由Google开源。
* [Keycloak](https://github.com/keycloak/keycloak)：Keycloak是适用于现代应用程序和服务的开源身份和访问管理解决方案，由RedHat基金会开源。
* [Pac4j](https://github.com/pac4j/pac4j)：简单而强大的Java安全框架，支持OAuth、CAS、SAML、OIDC、LDAP、JWT。
* [Sa-Token](https://github.com/dromara/sa-token)：由dromara社区开源的轻量级Java权限认证框架。
* [Sureness](https://github.com/dromara/sureness)：由dromara社区开源的一个简单高效的安全框架。
* [java-jwt](https://github.com/auth0/java-jwt)：JWT的Java实现。
* [ZAP](https://github.com/zaproxy/zaproxy)：可以在在开发和测试应用程序时自动查找Web应用程序中的安全漏洞，由专门的国际志愿者团队积极维护。
* [jjwt](https://github.com/jwtk/jjwt)：适用于Java和Android的JWT库。
* [ScribeJava](https://github.com/scribejava/scribejava)：适用于Java的简单OAuth库。
* [nimbus-jose-jwt](https://connect2id.com/products/nimbus-jose-jwt)：适用于Java和Android的JWT库。
* [fusionauth-jwt](https://github.com/FusionAuth/fusionauth-jwt)：一个简单易用的Java 8 JWT库。
* [MaxKey](https://github.com/dromara/MaxKey)：业界领先的IAM-IDaas身份管理和认证产品,支持OAuth2.x、OIDC、SAML2.0、JWT、CAS、SCIM等SSO标准协议，由dromara社区开源。
* [JustAuth](https://github.com/justauth/JustAuth)：第三方授权登录的工具类库。
* [UAA](https://github.com/cloudfoundry/uaa)：CloudFoundry用户帐户和身份验证(UAA)服务器。
* [Athenz](https://github.com/AthenZ/athenz)：Athenz是一个开源平台，用于动态基础设施中基于X.509证书的服务身份验证和细粒度访问控制。
* [Apereo CAS](https://github.com/apereo/cas)：集中认证服务平台，可用于企业内部单点登录系统。
* [JOAuth](https://github.com/twitter/joauth)：使用OAuth验证HTTP请求的Java库。
* [Passay](https://github.com/vt-middleware/passay)：Java的密码策略实现。
* [bc-java](https://github.com/bcgit/bc-java)：Bouncy Castle Java发行版。
* [Jasypt](https://github.com/jasypt/jasypt)：Jasypt是一个允许开发人员以最小的努力向项目添加基本加密功能的Java库。
* [Cryptomator](https://github.com/cryptomator/cryptomator)：对云中文件进行多平台透明客户端加密。
* [PicketLink](https://github.com/picketlink/picketlink)：PicketLink是一个用于保护Java EE应用程序的安全框架。
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck)：OWASP DependencyCheck是一种软件组合分析实用程序，可检测应用程序依赖中公开披露的漏洞。
* [sslcontext-kickstart](https://github.com/Hakky54/sslcontext-kickstart)：一个轻量级库，用于配置基于SSLContext或其他属性(例如TrustManager、KeyManager或受信任证书)的 HTTP客户端或服务器，以通过SSLFactory提供的单向身份验证或双向身份验证通过SSL/TLS进行通信。
* [okta](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter。
* [auth0-java](https://github.com/auth0/auth0-java)：Auth0平台的Java客户端库。
* [AppAuth](https://github.com/openid/AppAuth-Android)：用于与OAuth 2.0和OIDC提供商进行通信的Android客户端SDK。
* [jCasbin](https://github.com/casbin/jcasbin)：Java中支持ACL、RBAC、ABAC等访问控制模型的授权库。
* [Keywhiz](https://github.com/square/keywhiz)：Keywhiz是一个用于分发和管理密钥的系统。
* [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz)：密码强度估计器。
* [OACC](https://github.com/acciente/oacc-core)：是一个功能齐全的API，可强制执行和管理应用程序的身份验证和授权需求。
* [XXL-SSO](https://github.com/xuxueli/xxl-sso)：分布式单点登录框架。
* [smart-sso](https://github.com/a466350665/smart-sso)：SpringBoot SSO单点登录，OAuth2实现，支持App登录、分布式。
* [oxAuth](https://github.com/GluuFederation/oxAuth)：OAuth 2.0服务器和客户端；OIDC提供商(OP)和UMA授权服务器(AS)。
* [Janssen](https://github.com/JanssenProject/jans)：数字身份基础设施软件协作中心。
* [Vertx-Auth](https://github.com/eclipse-vertx/vertx-auth)：包含Vert.x和常见身份验证接口的身份验证实现。
* [jose4j](https://bitbucket.org/b_c/jose4j/src/master/)：一个健壮且易于使用的JWT和JOSE规范套件(JWS、JWE和JWK)的开源实现。
* [java-cas-client](https://github.com/apereo/java-cas-client)：Apereo Java CAS客户端库。
* [Bcrypt](https://github.com/patrickfav/bcrypt)：bcrypt密码哈希函数的Java独立实现。
* [joauth](https://github.com/twitter/joauth)：使用OAuth验证HTTP请求的Java库。

<h2 id="transaction">事务</h2>

* [Seata](https://github.com/seata/seata)：Seata是一个易于使用、高性能、开源的分布式事务解决方案，由阿里开源。
* [ByteTCC](https://github.com/liuyangming/ByteTCC)：ByteTCC是一个基于TCC(Try/Confirm/Cancel)机制的分布式事务管理器，它与JTA规范兼容。
* [Atomikos](https://github.com/atomikos/transactions-essentials)：Java的分布式事务管理库。
* [Narayana](https://github.com/jbosstm/narayana)：Narayana是一个事务工具包，为使用各种基于标准的事务协议开发的应用程序提供支持。
* [Bitronix](https://github.com/bitronix/btm)：Bitronix事务管理器(BTM)是JTA 1.1 API的简单但完整的实现。
* [AtlasDB](https://github.com/palantir/atlasdb)：事务分布式数据库层。
* [hmily](https://github.com/dromara/hmily)：分布式事务解决方案，由dromara社区开源。
* [TCC-Transaction](https://github.com/changmingxie/tcc-transaction)：开源的微服务架构下的TCC型分布式事务解决方案。
* [Multiverse](https://github.com/pveentjer/Multiverse)：JVM的软件事务内存实现。
* [tx-lcn](https://github.com/codingapi/tx-lcn)：LCN分布式事务框架，兼容Dubbo、Spring Cloud、Motan框架，支持各种关系数据库。
* [EasyTransaction](https://github.com/QNJR-GROUP/EasyTransaction)：分布式事务解决方案，统一使用TCC、SAGA、FMT、可靠消息、补偿等。
* [Servicecomb-pack](https://github.com/apache/servicecomb-pack)：提供TCC和Saga分布式事务协调解决方案，使用Alpha作为事务协调器，Omega作为事务代理，在Apache基金会下开源。
* [Raincat](https://github.com/dromara/raincat)：强一致分布式事务框架。
* [Scalardb](https://github.com/scalar-labs/scalardb)：通用事务管理器。
* [ByteJTA](https://github.com/liuyangming/ByteJTA)：ByteJTA是一个基于XA/2PC机制的分布式事务管理器，它与JTA规范兼容。
* [Myth](https://gitee.com/dromara/myth)：采用消息队列解决分布式事务的开源框架。

<h2 id="template-engine">模板引擎</h2>

* [Thymeleaf](https://github.com/thymeleaf/thymeleaf)：Thymeleaf是一个现代服务器端Java模板引擎，适用于Web和独立环境。
* [JSP](https://www.oracle.com/java/technologies/jspt.html)：JSP是Java应用程序最流行的视图技术之一，也是内置的模板引擎。
* [Apache FreeMarker](https://github.com/apache/freemarker)：FreeMarker是一个基于模板生成文本输出(从HTML到自动生成源代码的任何内容)的通用工具。
* [Pebble](https://github.com/PebbleTemplates/pebble)：Pebble是一个受Twig启发的Java模板引擎。
* [Groovy](http://groovy-lang.org/templating.html#_the_markuptemplateengine)：Groovy提供Markup模板引擎，该引擎基于构建器语法，可用于生成任何文本格式。
* [Apache Velocity](https://github.com/apache/velocity-engine)：Apache Velocity是一个用Java编写的通用模板引擎。
* [Mustache](https://github.com/spullara/mustache.java)：Mustache是一个支持许多其他编程语言的模板引擎。
* [Apache Tiles](https://github.com/apache/tiles)：适用于现代Java应用程序的免费开源模板框架。
* [Jade4j](https://github.com/neuland/jade4j)：用Java编写的jade实现，现在改成pug4j。
* [Handlebars.java](https://github.com/jknack/handlebars.java)：使用Java的无逻辑和语义Mustache模板。
* [Beetl](https://github.com/javamonkey/beetl2.0)：新一代的模板引擎，更简单易用。
* [Rocker](https://github.com/fizzed/rocker)：Java 8优化、内存高效、快速模板引擎生成静态类型、纯Java对象。
* [jinjava](https://github.com/HubSpot/jinjava)：基于Django模板语法的基于Java的模板引擎，适用于渲染Jinja模板。
* [HTTL](https://github.com/httl/httl)：HTTL是一个高性能的开源Java模板引擎，适用于动态HTML页面输出，可替代JSP页面，指令和Velocity相似。
* [HtmlFlow](https://github.com/xmlet/HtmlFlow/)：HtmlFlow是一种Java DSL，可以以流式的方式编写类型安全的HTML文档。
* [Chunk](https://github.com/tomj74/chunk-templates)：Chunk是一个Java模板引擎，适用于服务HTML或XML的应用程序。
* [Trimou](https://github.com/trimou/trimou)：Java中的Mustache/Handlebars模板引擎。
* [Rythm](https://github.com/rythmengine/rythmengine)：类似Razor、功能丰富、高性能且易于使用的Java模板引擎。
* [Liqp](https://github.com/bkiers/Liqp)：基于ANTLR的“Liquid模板”解析器和渲染引擎。

<h2 id="json">JSON库</h2>

* [Jackson](https://github.com/FasterXML/jackson-databind)：Java中使用最广泛的JSON库，也是Spring默认的JSON处理器。
* [Gson](https://github.com/google/gson)：由Google开源的一个JSON序列化/反序列化库。
* [Fastjson](https://github.com/alibaba/fastjson)：由阿里开源的一个JSON处理库，性能较好。
* [Moshi](https://github.com/square/moshi)：适用于Kotlin和Java的现代JSON库。
* [JsonPath](https://github.com/json-path/JsonPath)：JsonPath的实现版本。
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)：适用于Android的快速JSON解析和序列化库。
* [JSON-P](https://github.com/jakartaee/jsonp-api)：JSON-P是一个用于解析、构建、转换和查询JSON消息的属于Jakarta EE规范下的API。
* [Kryo](https://github.com/EsotericSoftware/kryo)：快速、高效、自动化的Java对象序列化和克隆库。
* [Eclipse Yasson](https://github.com/eclipse-ee4j/yasson)：由Eclipse开源的一个JSON处理库，也是JSR-367的官方参考实现。
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON)：高性能JSON解析器。
* [JsonLube](https://github.com/alibaba/JsonLube)：JsonLube可以在编译期自动生成JSON解析代码，用户使用方式更简单，同时能收获原生解析的性能，由阿里开发。
* [json-simple](https://github.com/fangyidong/json-simple)：非常简单的JSON库，可以用于编码和解码JSON文本。
* [JSON-Java](https://github.com/stleary/JSON-java)：Java中JSON包的参考实现。
* [json-io](https://github.com/jdereg/json-io)：小巧、轻量级的JSON和Java对象转换库。
* [Jsoniter](https://github.com/json-iterator/java)：Jsoniter(json-iterator)是Java和Go中可用的快速且灵活的JSON解析器。
* [Genson](https://github.com/owlike/genson)：Genson是一个完整的JSON转换库，提供完整的数据绑定、流媒体等等。
* [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo)：从JSON或JSON Schema生成Java类型，并标注这些类型以与Jackson、Gson等进行数据绑定。
* [DSL-JSON](https://github.com/ngs-doo/dsl-json)：高性能JVM JSON库，具有高级编译时数据绑定支持。
* [Ason](https://github.com/afollestad/ason)：提供JSON序列化功能的Java库，已经停止维护。
* [jsonld-java](https://github.com/jsonld-java/jsonld-java)：JSON-LD 1.0规范和JSON-LD-API 1.0规范的Java实现。
* [Jolt](https://github.com/bazaarvoice/jolt)：使用Java编写的JSON到JSON转换库。
* [ig-json-parser](https://github.com/Instagram/ig-json-parser)：用于Java项目的快速JSON解析器，由Instagram开源。
* [minimal-json](https://github.com/ralfstx/minimal-json)：一个快速、小型的Java JSON解析器和写入器。
* [Jfire-codejson](https://gitee.com/eric_ds/jfire-codejson)：性能非常高的JSON序列化和反序列化库。
* [Snack3](https://gitee.com/noear/snack3)：一个高性能的JsonPath框架，支持序列化反序列化、解析和转换、构建、查找、JsonPath查询。
* [Sawmill](https://github.com/logzio/sawmill)：Sawmill是一个JSON转换Java库。
* [OkJson](https://gitee.com/calvinwilliams/okjson)：Java编写的小巧、高效、灵活的JSON处理器。

<h2 id="mapper">Bean映射</h2>

* [MapStruct](https://github.com/mapstruct/mapstruct)：用于生成类型安全Bean映射器的注解处理器。
* [Dozer](https://github.com/DozerMapper/dozer)：一个强大的，通用的，灵活的，可重用的和可配置的开源映射框架。
* [ModelMapper](https://github.com/modelmapper/modelmapper)：智能对象映射库。
* [Orika](https://github.com/orika-mapper/orika)：更简单、更好、更快的Java Bean映射框架。
* [JMapper](https://github.com/jmapper-framework/jmapper-core)：集优雅、高性能和稳健性于一体的Java Bean映射器。
* [Selma](https://github.com/xebia-france/selma)：可以在编译时生成Java代码处理字段到字段映射的注解处理器。
* [BeanMapper](https://github.com/42BV/beanmapper)：用于根据Bean约定从一个Java类转换为名称相似的不同Java类的库。
* [Tamper](https://github.com/alibaba/tamper)：Tamper是一款处理Bean/Map进行属性复制映射的工具，支持递归、集合等深度映射。
* [ReMap](https://github.com/remondis-it/remap)：用于简化可测试对象映射的声明式映射库。
* [Bull](https://github.com/ExpediaGroup/bull)：Bull是一种Java Bean到Java Bean转换器，通用、灵活、可重用、可配置，并且速度非常快。
* [Datus](https://github.com/roookeee/datus)：Datus使你能够在流式的函数式API中定义两个数据结构之间的转换过程。

<h2 id="cli">CLI</h2>

* [Picocli](https://github.com/remkop/picocli)：Picocli是一个现代框架，用于轻松构建功能强大、用户友好、支持GraalVM的命令行应用程序。
* [SDKMAN](https://github.com/sdkman/sdkman-cli)：SDKMAN是一个用于在任何基于Unix的系统上管理多个软件开发套件的并行版本的工具。
* [JBang](https://github.com/jbangdev/jbang)：JBang是一个将脚本引入Java领域的框架。
* [JCommander](https://github.com/cbeust/jcommander)：基于Java 8注解的参数解析框架。
* [JLine](https://github.com/jline/jline3)：JLine是一个用于处理控制台输入的Java库。
* [Spring Shell](https://github.com/spring-projects/spring-shell)：Spring Shell可帮助你创建基于Spring的、针对CLI空间的生产级应用程序。
* [Lanterna](https://github.com/mabe02/lanterna)：Lanterna是一个Java库，允许你在纯文本环境中编写简单的半图形用户界面。
* [Just](https://github.com/maciejwalkowiak/just)：用于开发Spring Boot应用程序的命令行工具包。
* [JReleaser](https://github.com/jreleaser/jreleaser)：JReleaser是一个用于Java和非Java项目的自动化发布工具。
* [Jansi](https://github.com/fusesource/jansi)：Jansi是一个小型Java库，允许使用ANSI转义序列来格式化控制台输出，甚至可以在Windows上运行。
* [asciitable](https://github.com/vdmeer/asciitable)：文本表的几种实现，最初使用ASCII和UTF-8字符作为边框。
* [Crash](https://github.com/crashub/crash)：Crash是一个为扩展Java程序和Java虚拟机而设计的Shell。
* [Text-IO](https://github.com/beryx/text-io)：Text-IO是一个用于创建Java控制台应用程序的库，它可用于需要读取用户交互式输入的应用程序。
* [java-ascii-render](https://github.com/indvd00m/java-ascii-render)：纯Java的ASCII渲染器，没有外部依赖。
* [mcs](https://github.com/mthmulders/mcs)：可以从命令行搜索Maven中央仓库。
* [JD-Core](https://github.com/java-decompiler/jd-core)：JD-Core是一个用Java编写的Java反编译器。
* [jd-cli](https://github.com/intoolswetrust/jd-cli)：jd-cli是JD-Core项目的简单命令行包装器。
* [Airline](https://github.com/rvesse/airline)：基于Java注解的框架，用于解析类似Git的命令行结构，具有深度可扩展性。
* [jbock](https://github.com/jbock-java/jbock)：无反射命令行解析器。
* [Args4j](https://github.com/kohsuke/args4j)：Args4j是一个小型Java类库，可以轻松解析CUI应用程序中的命令行选项/参数。
* [Aesh](https://github.com/aeshell/aesh)：Aesh是一个用于处理控制台输入的Java库。
* [JeeSh](https://github.com/jeeshell/je2sh)：JVM可扩展和可嵌入Shell。
* [ConsoleUI](https://github.com/awegmann/consoleui)：微型Java库，可在基于ANSI控制台的终端上启用简单的UI元素。
* [progressbar](https://github.com/ctongfei/progressbar)：Java/JVM基于终端的进度条。

<h2 id="collection">集合库</h2>

* [Apache Commons Collections](https://github.com/apache/commons-collections)：Apache基金会下的开源Java集合工具库。
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections)：Eclipse Collections是一个Java集合框架，具有优化的数据结构和丰富、实用且流式的API。
* [Fastutil](https://github.com/vigna/fastutil)：Fastutil通过提供特定于类型的Map、Set、List和Queue来扩展Java集合框架。
* [HPPC](https://github.com/carrotsearch/hppc)：Java的高性能原始类型集合。
* [PCollections](https://github.com/hrldcpr/pcollections)：PCollections充当Java集合框架的持久且不可变的类似物。
* [CQEngine](https://github.com/npgall/cqengine)：集合查询引擎–是一个高性能Java集合，可以使用类似SQL的查询进行搜索，并且延迟极低。
* [Agrona](https://github.com/real-logic/agrona)：Java的高性能数据结构和实用方法。
* [Koloboke](https://github.com/leventov/Koloboke)：精心设计的Java集合框架扩展，具有原始类型特化等功能。
* [high-scale-lib](https://github.com/stephenc/high-scale-lib)：并发且高度可扩展的实用程序的集合。
* [Javolution](https://github.com/javolution/javolution)：用于实时和嵌入式系统的Java核心库。
* [Trove](https://bitbucket.org/trove4j/trove/src/master/)：为Java提供高速对象和原始集合。
* [Primitive-Collections](https://github.com/Speiger/Primitive-Collections)：一个原始集合库，可减少内存使用并提高性能。
* [Capsule](https://github.com/usethesource/capsule)：Capsule旨在成为Java 11+的成熟(不可变)集合库，完全围绕持久尝试构建。
* [LMAXCollections](https://github.com/LMAX-Exchange/LMAXCollections)：高性能集合库。
* [Paguro](https://github.com/GlenKPeterson/Paguro)：JVM的泛型、空安全、不可变集合和函数式转换。
* [pcj](https://github.com/pmem/pcj)：Java的持久集合库。

<h2 id="functional">函数式编程</h2>

* [Vavr](https://github.com/vavr-io/vavr)：Vavr是Java 8的对象函数语言扩展，旨在减少代码行数并提高代码质量。
* [StreamEx](https://github.com/amaembo/streamex)：对Java Stream API的增强库。
* [jOOL](https://github.com/jOOQ/jOOL)：为Java 8 Lambda提供了一些有用的扩展，
* [javatuples](https://github.com/javatuples/javatuples)：Java中元组的类型安全表示。
* [throwing-function](https://github.com/pivovarit/throwing-function)：支持受检异常的Java 8函数接口+适配器。
* [FunctionalJava](https://github.com/functionaljava/functionaljava)：Functional Java是一个开源库，促进Java中的函数式编程。
* [Cyclops](https://github.com/aol/cyclops)：一个先进且易于使用的平台，用于在Java 8中编写函数式应用程序。
* [Linq4j](https://github.com/julianhyde/linq4j)：LINQ的Java实现库。
* [Functional](https://github.com/io-fairy/functional)：提供更简单更好用的Java函数式编程接口。
* [Parallel-Collector](https://github.com/pivovarit/parallel-collectors)：可使用Stream API简化Java中的并行收集处理的工具包。
* [NoException](https://github.com/robertvazan/noexception)：用于以简洁、统一且架构干净的方式处理异常的Java库。
* [protonpack](https://github.com/poetix/protonpack)：Java Stream API的实用工具库。
* [Fugue](https://bitbucket.org/atlassian/fugue/src/master/)：Guava的函数式编程扩展。
* [lambda](https://github.com/palatable/lambda)：Java的函数式模式。
* [underscore-java](https://github.com/javadev/underscore-java)：Underscore.js的Java版本。
* [Faux-Pas](https://github.com/zalando/faux-pas)：一个简化Java函数式编程错误处理的库。
* [Lightweight-Stream-API](https://github.com/aNNiMON/Lightweight-Stream-API)：Java Stream API的扩展库。
* [linq](https://github.com/timandy/linq)：LINQ到对象转换的Java库。
* [Formulog](https://github.com/HarvardPL/formulog)：支持SMT查询和一阶函数编程的数据记录。
* [Purefun](https://github.com/tonivade/purefun)：Java函数式编程库。

<h2 id="bytecode">字节码操作</h2>

* [ASM](https://gitlab.ow2.org/asm/asm)：通用底层字节码操作和分析开发库。
* [Byte Buddy](https://github.com/raphw/byte-buddy)：Byte Buddy是一个代码生成和操作库，用于在Java应用程序运行时创建和修改Java类，而无需编译器的帮助。
* [Byteman](https://github.com/bytemanproject/byteman)：Byteman支持将副作用注入到Java程序中用于跟踪和测试应用程序行为的目的。
* [Javassist](https://github.com/jboss-javassist/javassist)：Java字节码工程工具包。
* [cglib](https://github.com/cglib/cglib)：用于生成和转换Java字节码的高级API。
* [ByteX](https://github.com/bytedance/ByteX)：字节开源的字节码插件开发平台。
* [allocation-instrumenter](https://github.com/google/allocation-instrumenter)：将字节码重写为工具分配站点的Java代理，由Google开源。
* [Soot](https://github.com/soot-oss/soot)：Soot是一个Java优化框架，提供了多种用于分析和转换Java字节码的中间表示形式。
* [Mixin](https://github.com/SpongePowered/Mixin)：Mixin是一个使用ASM的Java特征/混合和字节码编织框架。
* [RoboVM](https://github.com/MobiVM/robovm)：针对IOS、Mac OSX和Linux的JVM字节码AOT。
* [ByteKit](https://github.com/alibaba/bytekit)：Java字节码工具包，由阿里开发。
* [Caesium](https://github.com/sim0n/Caesium)：Java字节码混淆器。
* [proguard-core](https://github.com/Guardsquare/proguard-core)：用于读取、写入、分析和处理Java字节码的库。
* [DroidAssist](https://github.com/didi/DroidAssist)：一个基于Javassist的轻量级Android Studio Gradle插件，用于在Android中编辑字节码，由滴滴开源。

<h2 id="image">图像处理</h2>

* [Thumbnailator](https://github.com/coobird/thumbnailator)：Java的缩略图生成库。
* [Pngtastic](https://github.com/depsypher/pngtastic/)：一个纯Java PNG图像优化和操作库。
* [ImageJ](https://github.com/imagej/ImageJ)：用于处理和分析科学图像的公共领域软件。
* [OpenIMAJ](https://github.com/openimaj/openimaj)：OpenIMAJ是一个屡获殊荣的库和工具集合，用于多媒体(图像、文本、视频、音频等)内容分析和内容生成。
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys)：Java ImageIO的附加插件和扩展。
* [OpenCV](https://github.com/openpnp/opencv)：OpenCV(开源计算机视觉)是一个用于实时计算机视觉和图像处理的库。
* [Tess4j](https://github.com/nguyenq/tess4j)：Tesseract OCR API的Java JNA包装器。
* [imgscalr](https://github.com/rkalla/imgscalr)：简单的Java图像缩放库，实现Chris Campbell的增量缩放算法以及Java 2D的“最佳实践”图像缩放技术。
* [Marvin](https://github.com/gabrielarchanjo/marvin-framework)：Marvin图像处理框架提供实时处理图像和视频的功能。
* [JavaCV](https://github.com/bytedeco/javacv)： OpenCV、FFmpeg等的Java接口。
* [webcam-capture](https://github.com/sarxos/webcam-capture)：该库允许你直接从Java使用内置或外部网络摄像头，它旨在抽象常用的相机功能并支持各种捕获框架。
* [Picasso](https://github.com/square/picasso)：一个强大的Android图像下载和缓存库。
* [ZXing](https://github.com/zxing/zxing)：适用于Java、Android的ZXing条码扫描库。
* [image-comparison](https://github.com/romankh3/image-comparison)：可以比较2个相同大小的图像，并通过绘制矩形直观地显示差异。
* [xmlgraphics-batik](https://github.com/apache/xmlgraphics-batik)：Batik是一个基于Java的工具包，适用于处理可缩放矢量图形(SVG)格式的图像各种目的，例如观看、生成或操纵。
* [Luban](https://github.com/Curzibn/Luban)：Android图片压缩工具，仿微信朋友圈压缩策略。
* [PixelFlow](https://github.com/diwi/PixelFlow)：用于高性能GPU计算(GLSL)处理的Java库。
* [ImageJ2](https://github.com/imagej/imagej2)：Image的重写版本，用于多维图像数据，重点是科学成像。
* [BoofCV](https://github.com/lessthanoptimal/BoofCV)：用于SFM、校准、基准、跟踪、图像处理等的快速计算机视觉库。
* [Scrimage](https://github.com/sksamuel/scrimage)：Java、Scala和Kotlin图像处理库。
* [cv4j](https://github.com/imageprocessor/cv4j)：一个用纯Java实现的高质量、实时的图像处理和机器学习库。
* [ImgLib2](https://github.com/imglib/imglib2)：用于图像处理的通用下一代Java库。
* [Imglib](https://github.com/nackily/imglib)：一个轻量级的Java图像处理库，致力于简化对图像的常见处理。
* [AndroidLibyuvImageUtils](https://github.com/myrao/AndroidLibyuvImageUtils)：Android上的图像处理库，基于libyuv。
* [ImageCombiner](https://gitee.com/dromara/image-combiner)：ImageCombiner是一个专门用于Java服务端图片合成的工具。
* [image-plugin](https://gitee.com/hellokaton/image-plugin)：非常简单的图片处理插件，可快速集成在Web应用中。
* [imagetool](https://gitee.com/xshuai/imagetool)：一个简单的图片处理工具，支持图片压缩、图片水印、图片裁剪、图片旋转、图片格式转换等功能。

<h2 id="crawler">爬虫</h2>

* [crawler4j](https://github.com/yasserg/crawler4j)：Java开源网络爬虫库。
* [Apache Nutch](https://github.com/apache/nutch)：Apache Nutch是一个可扩展且可伸缩的网络爬虫库。
* [WebMagic](https://github.com/code4craft/webmagic)：用于Java的可扩展网络爬虫框架。
* [Jsoup](https://github.com/jhy/jsoup/)：Java HTML解析器，专为HTML编辑、清理、抓取和XSS安全而构建。
* [StormCrawler](https://github.com/DigitalPebble/storm-crawler)：基于Apache Storm的可扩展、成熟且多功能的网络爬虫库。
* [Sparkler](https://github.com/USCDataScience/sparkler)：在Apache Spark上运行的类似Apache Nutch的爬虫库。
* [Spider-Flow](https://github.com/ssssssss-team/spider-flow)：新一代爬虫平台，以图形化方式定义爬虫流程，不写代码即可完成爬虫。
* [WebCollector](https://github.com/CrawlScript/WebCollector)：WebCollector是一个基于Java的开源网络爬虫框架，提供了一些简单的网络爬虫接口。
* [Heritrix](https://github.com/internetarchive/heritrix3)：Heritrix是互联网档案馆的开源、可扩展、网络规模、档案质量的网络爬虫项目。
* [Gecco](https://github.com/xtuhcy/gecco)：易用的轻量化网络爬虫库。
* [SeimiCrawler](https://github.com/zhegexiaohuozi/SeimiCrawler)：一个简单、敏捷、分布式的支持Spring Boot的Java爬虫框架。
* [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler)：免费的数据库模式发现和理解工具。
* [FS-Crawler](https://github.com/dadoonet/fscrawler)：Elasticsearch文件系统爬虫。
* [zhihu-crawler](https://github.com/wycm/zhihu-crawler)：zhihu-crawler是一个基于Java的高性能、支持免费HTTP代理池、横向扩展、分布式爬虫项目。
* [XXL-Crawler](https://github.com/xuxueli/xxl-crawler)：Java分布式爬虫框架。
* [Jvppeteer](https://github.com/fanyong920/jvppeteer)：适用于Java的无头Chrome。
* [NetDiscovery](https://github.com/fengzhizi715/NetDiscovery)：NetDiscovery是一款基于Vert.x、RxJava 2等框架实现的通用爬虫框架/中间件。
* [Spiderman](https://gitee.com/l-weiwei/spiderman)：Java开源Web数据抽取工具。
* [XueQiuSuperSpider](https://github.com/decaywood/XueQiuSuperSpider)：雪球超级爬虫是基于雪球网、东方财富和同花顺实现的股票数据爬虫程序。
* [Crawljax](https://github.com/crawljax/crawljax)：Crawljax是一个自动爬取和测试现代Web应用程序的工具。
* [ACHE](https://github.com/VIDA-NYU/ache)：ACHE是一个用于特定域搜索的网络爬虫。
* [Spiderman2](https://gitee.com/l-weiwei/Spiderman2)：Spiderman的升级版，在性能、架构、易用性上有提升，支持分布式。
* [YayCrawler](https://gitee.com/shentong_012/YayCrawler)：分布式爬虫系统，简单使用，高级配置。
* [wind-bell](https://gitee.com/zhiyubujian/wind-bell)：轻量级的高效爬虫工具，配置简单，方便二次开发。
* [Crawler-Commons](https://github.com/crawler-commons/crawler-commons)：一组可重用的Java组件，实现任何网络爬虫通用的功能。
* [zongtui-webcrawler](https://gitee.com/zongtui/zongtui-webcrawler)：基于Hadoop思维的分布式网络爬虫。
* [vscrawler](https://gitee.com/virjar/vscrawler)：适合抓取封堵的爬虫框架。
* [Elves](https://github.com/hellokaton/elves)：轻量级爬虫框架的设计与实现。
* [MongooCrawler](https://gitee.com/coliza/MongooCrawler)：一款低入侵分布式爬虫框架，仅仅依赖少量第三方包，具有多进程多线程，集成反爬、验证码破解方案等特性。
* [CrawlerDemon](https://gitee.com/spirit_demon/CrawlerDemon)：基于Akka的高性能分布式爬虫框架。
* [ispider](https://github.com/xpleaf/ispider)：Java设计的分布式爬虫系统。

<h2 id="data">数据处理</h2>

* [JaVers](https://github.com/javers/javers)： Java的对象审计和差异框架。
* [java-LSH](https://github.com/tdebatty/java-LSH)：局部敏感哈希(LSH)的Java实现。
* [Chronicle-Map](https://github.com/OpenHFT/Chronicle-Map)：Chronicle Map是一种超快速、内存中、非阻塞键值存储，专为低延迟和/或多进程应用程序(例如交易和金融市场应用程序)而设计。

<h2 id="annotation-processor">注解处理器</h2>

* [Immutables](https://github.com/immutables/immutables)：用于创建不可变对象和构建器的注解处理器。
* [Derive4j](https://github.com/derive4j/derive4j)：Java 8注解处理器，用于派生代数数据类型构造函数、模式匹配等。
* [AndroidAnnotations](https://github.com/androidannotations/androidannotations)：快速的Android开发，维护方便。
* [DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch)：一个简单、基于注解的库，用于在Android上更好地处理深度链接。
* [jackson-annotations](https://github.com/FasterXML/jackson-annotations)：Jackson数据处理器的核心注解。
* [compile-testing](https://github.com/google/compile-testing)：javac和注解处理器的测试工具。
* [PaperParcel](https://github.com/grandstaish/paperparcel)：自动生成Java和Kotlin的Parcelable实现。
* [RAVE](https://github.com/uber-archive/rave)：使用Java注解处理的数据模型验证框架。
* [PojoBuilder](https://github.com/mkarneim/pojobuilder)：POJO构建器的Java代码生成器。
* [Moxy](https://github.com/moxy-community/Moxy)：Moxy是适用于Android的MVP库，具有增量注解处理器和ktx功能。
* [Jackdaw](https://github.com/vbauer/jackdaw)：可以简化开发的Java注解处理器。
* [ParcelablePlease](https://github.com/sockeqwe/ParcelablePlease)：用于生成Parcelable代码的注解处理器。
* [beanknife](https://github.com/vipcxj/beanknife)：用于自动生成数据传输对象(DTO)的注解处理器库。
* [Rest.Vertx](https://github.com/zandero/rest.vertx)：类似JAX-RS的注解处理器，适用于Vert.x Vertical。
* [FreeBuilder](https://github.com/inferred/FreeBuilder)：自动生成Java的Builder模式。

<h2 id="event-bus">事件总线</h2>

* [EventBus](https://github.com/greenrobot/EventBus)：适用于Android和Java的事件总线，简化了Activity、Fragments、Threads、Services等之间的通信。代码更少，质量更好。
* [MBassador](https://github.com/bennidi/mbassador)：MBassador是一个利用发布-订阅语义的高性能事件总线。
* [Otto](https://github.com/square/otto)：增强的基于Guava的事件总线，重点是Android支持。
* [Spring Cloud Bus](https://github.com/spring-cloud/spring-cloud-bus)：Spring Cloud事件总线。
* [LiveEventBus](https://github.com/JeremyLiao/LiveEventBus)：LiveEventBus是一款Android消息总线，基于LiveData，具有生命周期感知能力，支持Sticky、AndroidX、款进程。
* [ZBUS](https://gitee.com/openforce/zbus)：轻量级服务总线，面向高性能、低时延、高可用特性调优，支持RPC，消息队列服务。
* [RxBus](https://github.com/AndroidKnife/RxBus)：RxJava的事件总线。
* [HermesEventBus](https://github.com/Xiaofei-it/HermesEventBus)：用于在进程之间使用EventBus的库，在IPC或插件开发中很有用。
* [AndroidEventBus](https://github.com/hehonghui/AndroidEventBus)：适用于Android的轻量级事件总线库，简化了Activity、Fragments、Threads、Services等之间的通信。
* [Nakadi](https://github.com/zalando/nakadi)：分布式事件总线，在类似Kafka的队列之上实现RESTful API抽象。
* [DeFiBus](https://gitee.com/WeBank/DeFiBus)：基于开源消息中间件打造的安全可控的分布式金融级消息总线。
* [Low-Level-Design](https://github.com/InterviewReady/Low-Level-Design)：常见数据结构的低级设计，包括事件总线。

<h2 id="swagger">Swagger</h2>

* [swagger-core](https://github.com/swagger-api/swagger-core)：Swagger Core是OpenAPI规范的Java实现。
* [knife4j](https://gitee.com/xiaoym/knife4j)：Knife4j是一个集Swagger 2和OpenAPI 3为一体的增强解决方案。
* [Springfox](https://github.com/springfox/springfox)：使用Spring构建的API的自动化JSON API文档。
* [swagger-parser](https://github.com/swagger-api/swagger-parser)：Swagger Parser是Swagger工具之一，可以帮助我们解析OpenAPI文档并提取其各个组件。
* [springdoc-openapi](https://github.com/springdoc/springdoc-openapi)：Springdoc-openapi是一个用于Spring Boot项目的OpenAPI 3实现。
* [Swagger2Markup](https://github.com/Swagger2Markup/swagger2markup)：Swagger到AsciiDoc或Markdown转换器，通过将手写文档与自动生成的API文档相结合，简化最新RESTful API文档的生成。
* [spring-boot-starter-swagger](https://github.com/SpringForAll/spring-boot-starter-swagger)：个人开发的Spring Boot集成Swagger的Starter。
* [swagger2word](https://github.com/JMCuixy/swagger2word)：一个Swagger API文档转Word文档的工具项目。
* [CATS](https://github.com/Endava/cats)：CATS是一个REST API模糊器和OpenAPI端点的负面测试工具。
* [OpenAPI-diff](https://github.com/OpenAPITools/openapi-diff)：用于比较两个OpenAPI规范的实用程序。
* [SwaggerSocket](https://github.com/swagger-api/swagger-socket)：基于WebSocket的REST。
* [Swagger-Play](https://github.com/swagger-api/swagger-play)：这是一个在Play框架控制器中支持Swagger注解的模块。
* [validator-badge](https://github.com/swagger-api/validator-badge)：该项目在网站上显示“valid swagger”徽章，支持Swagger/OpenAPI 2.0和OpenAPI 3.x规范。
* [openapi-style-validator](https://github.com/OpenAPITools/openapi-style-validator)：可定制的样式验证器，可确保你的OpenAPI规范遵循你组织的标准。

<h2 id="cluster-management">集群管理</h2>

* [Aurora](https://github.com/apache/aurora)：Apache Aurora是一个Mesos框架，用于长时间运行服务和定时任务。
* [Singularity](https://github.com/HubSpot/Singularity)：Singularity是一种API和Web应用程序，用于运行和调度Apache Mesos任务，包括长时间运行的进程、计划作业和一次性任务。
* [CacheCloud](https://github.com/sohutv/cachecloud)：搜狐视频Redis私有云平台：支持Redis多种架构高效管理、有效降低大规模Redis运维成本，提升资源管控能力和利用率。
* [Kafka-UI](https://github.com/provectus/kafka-ui)：用于Apache Kafka管理的开源Web UI。
* [EFAK](https://github.com/smartloli/EFAK)：一个简单且高性能的监控系统，用于对kafka集群进行全面的监控和管理。
* [MSEC](https://github.com/Tencent/MSEC)：集群海量服务引擎。
* [Cruise-control](https://github.com/linkedin/cruise-control)：Cruise-control是同类中第一个完全自动化Kafka集群动态工作负载重新平衡和自我修复的工具，它通过简化Kafka集群的操作为Kafka用户提供了巨大的价值。
* [KCenter](https://github.com/xaecbd/KCenter)：KKafka中心是kafka集群管理维护、生产者/消费者监控、生态组件使用的统一平台。
* [Kafka-Sprout](https://github.com/oslabs-beta/Kafka-Sprout)：用于Kafka集群管理的Web GUI。

<h2 id="code-analysis">代码分析</h2>

* [Checkstyle](https://github.com/checkstyle/checkstyle)：Checkstyle是一种开发工具，可帮助程序员编写符合编码标准的Java代码。
* [Infer](https://github.com/facebook/infer)：适用于Java、C、C++和Objective-C的静态分析器。
* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)：免费开源交互式源浏览器。
* [ErrorProne](https://github.com/google/error-prone)：将常见的Java错误捕获为编译时错误。
* [PMD](https://github.com/pmd/pmd)：可扩展的多语言静态代码分析器。
* [SpotBugs](https://github.com/spotbugs/spotbugs)：一种静态分析工具，用于查找Java代码中的错误。
* [SonarJava](https://github.com/SonarSource/sonar-java)：用于Java代码质量和安全性的SonarSource静态分析器。
* [Spoon](https://github.com/INRIA/spoon)：Spoon是一个用于分析和转换Java源代码的元编程库。
* [FindBugs](https://github.com/findbugsproject/findbugs)：Findbugs是一款开源的Java源码静态分析工具。
* [jQAssistant](https://github.com/jQAssistant/jqassistant)：一个基于Neo4j数据库的依赖分析工具，支持分析Java、XML、JSON等格式的数据，并提供可视化界面和查询语言。
* [Dependency-Track](https://github.com/DependencyTrack/dependency-track)：Dependency-Track是一个智能组件分析平台，允许组织识别并降低软件供应链中的风险。
* [find-sec-bugs](https://github.com/find-sec-bugs/find-sec-bugs)：用于Java Web应用程序和Android应用程序安全审核的SpotBugs插件。
* [bytecode-viewer](https://github.com/Konloch/bytecode-viewer)： Java 8+ Jar和Android APK逆向工程套件。
* [Tai-e](https://github.com/pascal-lab/Tai-e)：一个易于学习/使用的Java静态分析框架。
* [Steady](https://github.com/eclipse/steady)：分析你的Java应用程序是否存在已知漏洞的开源依赖项，同时使用静态分析和测试来确定代码上下文和使用情况，以提高准确性。
* [mobsfscan](https://github.com/MobSF/mobsfscan)：mobsfscan是一个静态分析工具，可以在Android和IOS源代码中查找不安全的代码模式。
* [CK](https://github.com/mauricioaniche/ck)：通过静态分析获得Java代码的代码度量。
* [jspecify](https://github.com/jspecify/jspecify)：完全指定注解的工件，用于支持静态分析检查，从无效分析开始。
* [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)：识别并优先考虑Java代码库中你应该首先重构的上帝类和高度耦合类。
* [Qulice](https://github.com/yegor256/qulice)：Java项目的质量警察：Checkstyle、PMD和SpotBugs的聚合器。
* [jpeek](https://github.com/cqfn/jpeek)：Java代码内聚度指标的托管和命令行计算器。

<h2 id="Maven">Maven插件</h2>

* [frontend-maven-plugin](https://github.com/eirslett/frontend-maven-plugin)：可在本地下载/安装Node和NPM，运行NPM install、Grunt、Gulp和/或Karma。
* [docker-maven-plugin](https://github.com/spotify/docker-maven-plugin)：Docker的Maven插件，Spotify开源，该项目不再活跃。
* [docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin)：用于运行和创建Docker镜像的Maven插件。
* [jkube](https://github.com/eclipse/jkube)：在Kubernetes上构建和部署Java应用程序。
* [git-commit-id-maven-plugin](https://github.com/git-commit-id/git-commit-id-maven-plugin)：可以将构建时Git仓库信息包含到POJO/properties文件中。
* [android-maven-plugin](https://github.com/simpligility/android-maven-plugin)：用于Android应用程序开发等的Maven插件。
* [javafx-maven-plugin](https://github.com/javafx-maven-plugin/javafx-maven-plugin)：JavaFX的Maven插件。
* [swagger-maven-plugin](https://github.com/kongchen/swagger-maven-plugin)：该插件使你的Swagger注解项目能够在Maven构建阶段生成Swagger规范和可定制的模板化静态文档。
* [sonar-scanner-maven](https://github.com/SonarSource/sonar-scanner-maven)：用于Maven的SonarQube扫描器。
* [scala-maven-plugin](https://github.com/davidB/scala-maven-plugin)：用于在Maven中编译/测试/运行/记录Scala代码。
* [depgraph-maven-plugin](https://github.com/ferstl/depgraph-maven-plugin)：可生成各种格式(DOT、GML、PlantUML、JSON和Text)依赖关系图的Maven插件。
* [jmeter-maven-plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin)：JMeter Maven插件。
* [jaxb-tools](https://github.com/highsource/jaxb-tools)：用于XML模式编译的最先进的JAXB2 Maven插件。
* [modernizer-maven-plugin](https://github.com/gaul/modernizer-maven-plugin)：检测旧版Java API的使用。
* [javafx-maven-plugin](https://github.com/openjfx/javafx-maven-plugin)：用于运行JavaFX 11+应用程序的Maven插件。
* [versions-maven-plugin](https://github.com/mojohaus/versions)：用于管理项目POM中的工件版本。
* [asciidoctor-maven-plugin](https://github.com/asciidoctor/asciidoctor-maven-plugin)：通过JRuby使用Asciidoctor来处理项目内的AsciiDoc源文件。
* [fmt-maven-plugin](https://github.com/spotify/fmt-maven-plugin)：格式化Java代码的固定Maven插件。
* [os-maven-plugin](https://github.com/trustin/os-maven-plugin)：用于设置从${os.name}和${os.arch}属性检测到的各种有用属性。
* [native-build-tools](https://github.com/graalvm/native-build-tools)：适用于各种构建工具的本机镜像插件。
* [azure-maven-plugins](https://github.com/microsoft/azure-maven-plugins)：适用于Azure的Maven插件。
* [protoc-jar-maven-plugin](https://github.com/os72/protoc-jar-maven-plugin)：使用protoc-jar多平台可执行protoc JAR执行protobuf代码生成。
* [license-maven-plugin](https://github.com/mathieucarbou/license-maven-plugin)：用于管理源文件中的许可证标头。
* [appbundle-maven-plugin](https://github.com/federkasten/appbundle-maven-plugin)：可为OS X创建包含所有项目依赖项和必要元数据的应用程序包。
* [duplicate-finder-maven-plugin](https://github.com/basepom/duplicate-finder-maven-plugin)：用于查找重复类或资源的Maven插件。
* [gluonfx-maven-plugin](https://github.com/gluonhq/gluonfx-maven-plugin)：简化为Java/JavaFX Maven项目创建本机镜像的插件。
* [tomcat-maven-plugin](https://github.com/apache/tomcat-maven-plugin)：Apache Tomcat Maven插件。
* [exec-maven-plugin](https://github.com/mojohaus/exec-maven-plugin)：可以执行Java程序的Maven插件。
* [gwt-maven-plugin](https://github.com/tbroyer/gwt-maven-plugin)：使Maven构建GWT项目更加容易。
* [jshell-maven-plugin](https://github.com/johnpoth/jshell-maven-plugin)：Java Shell工具(JShell)的Maven插件。
* [mybatis-generator-yml-maven-plugin](https://github.com/javthon/mybatis-generator-yml-maven-plugin)：MyBatis Generator YML配置、Lombok插件、Swagger插件支持。
* [springdoc-openapi-maven-plugin](https://github.com/springdoc/springdoc-openapi-maven-plugin)：该插件的目的是在运行时生成JSON和YAML OpenAPI描述。
* [cucable-plugin](https://github.com/trivago/cucable-plugin)：简化并行运行Cucumber场景的Maven插件。
* [graphql-maven-plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project)：可以生成Java代码来加速客户端和服务器的开发。
* [web3j-maven-plugin](https://github.com/web3j/web3j-maven-plugin)：用于根据Solidity合约文件创建Java类。
* [aspectj-maven-plugin](https://github.com/mojohaus/aspectj-maven-plugin)：该插件使用AspectJ编译器ajc将AspectJ切面编织到类中。
* [app-maven-plugin](https://github.com/GoogleCloudPlatform/app-maven-plugin)：用于构建和部署Google App Engine应用程序的Maven插件。
* [mosec-maven-plugin](https://github.com/momosecurity/mosec-maven-plugin)：用于检测Maven项目的第三方依赖组件是否存在安全漏洞。
* [rewrite-maven-plugin](https://github.com/openrewrite/rewrite-maven-plugin)：OpenRewrite的Maven插件。
* [allure-maven](https://github.com/allure-framework/allure-maven)：根据测试结果生成Allure报告的Maven插件。
* [heroku-maven-plugin](https://github.com/heroku/heroku-maven-plugin)：用于将Java应用程序直接部署到Heroku，而无需推送到Git仓库。

<h2 id="registry">注册中心</h2>

* [Nacos](https://github.com/alibaba/nacos)：一个易于使用的动态服务发现、配置和服务管理平台，用于构建云原生应用程序，由阿里开源。
* [Apollo](https://github.com/apolloconfig/apollo)：可靠的配置管理系统，适用于微服务配置管理场景，由携程开源。
* [Eureka](https://github.com/Netflix/eureka)：用于弹性中间层负载均衡和故障转移的AWS服务注册中心，Netflix开源。
* [Pantheon](https://github.com/ProgrammerAnthony/Pantheon)：分布式微服务注册中心。
* [Nomulus](https://github.com/google/nomulus)：Google App Engine上的顶级域名注册服务。
* [SOFARegistry](https://github.com/sofastack/sofa-registry)：SOFARegistry是由蚂蚁金服提供支持的生产级、低延迟、高可用性服务注册中心。
* [flair-registry](https://github.com/viz-centric/flair-registry)：Flair BI的服务发现。

<h2 id="rate-limiting">限流库</h2>

* [Sentinel](https://github.com/alibaba/Sentinel)：面向云原生微服务的高可用流控防护组件，由阿里开源。
* [Hystrix](https://github.com/Netflix/Hystrix)：Hystrix是一个延迟和容错库，可以防止级联故障，由Netflix开源。
* [Resilience4j](https://github.com/resilience4j/resilience4j)：Resilience4j是一个专为Java 8和函数式编程设计的容错库。
* [Bucket4j](https://github.com/bucket4j/bucket4j)：Bucket4j是一个基于令牌桶算法的Java限流库。
* [RateLimiter4j](https://github.com/wangzheng0822/ratelimiter4j)：Java限流库/框架。
* [concurrency-limits](https://github.com/Netflix/concurrency-limits)：实现并集成了从TCP拥塞控制到自动检测服务并发限制的概念，以便以最佳延迟实现最佳吞吐量。
* [RateLimitJ](https://github.com/mokies/ratelimitj)：用于速率限制的Java库，提供可扩展的存储和应用程序框架适配器，该项目不再活跃。
* [token-bucket](https://github.com/bbeck/token-bucket)：令牌桶限速算法。
* [RedisRateLimiter](https://github.com/tangaiyun/RedisRateLimiter)：基于Redis的API访问速率限制器。
* [Neural](https://gitee.com/yu120/neural)：提供分布式限流、降级、熔断、重试和隔离的容错特性。
* [Discovery](https://gitee.com/nepxion/Discovery)：蓝绿灰度发布、路由、限流、熔断、降级、隔离、追踪、流量染色、故障转移。
* [SnowJena](https://github.com/onblog/SnowJena)：基于令牌桶算法实现的分布式无锁限流框架。

<h2 id="gateway">网关</h2>

* [Zuul](https://github.com/Netflix/zuul)：Zuul是一种网关服务，提供动态路由、监控、弹性、安全性等。
* [Apache ShenYu](https://github.com/apache/shenyu)：Apache ShenYu是一个Java原生API网关，用于服务代理、协议转换和API治理，由dromara社区创始人开源。
* [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway)：基于Spring Boot构建的网关，提供路由等功能。
* [SMSSync](https://github.com/ushahidi/SMSSync)：适用于Android的SMS网关。
* [FizzGate](https://github.com/fizzgate/fizz-gateway-node)：FizzGate是一个基于Java开发的微服务聚合网关。
* [VX-API-Gateway](https://gitee.com/mirren/VX-API-Gateway)：VX-API-Gateway是基于Vert.x开发的API网关，是一个全异步、高性能、可扩展、轻量级的API网关。
* [Haafiz](https://github.com/ProgrammerAnthony/Haafiz)：基于Netty、Disruptor、etcd等技术实现的开源网关。
* [SIA-Gateway](https://github.com/siaorg/sia-gateway)：基于Spring Cloud微服务生态体系下开发的一个分布式微服务网关系统。
* [Stargate](https://github.com/stargate/stargate)：Stargate是部署在客户端应用程序和Cassandra数据库之间的数据网关。
* [Eclipse Kura](https://github.com/eclipse/kura)：基于OSGi的M2M服务网关应用程序框架。
* [service-proxy](https://github.com/membrane/service-proxy)：用Java编写的REST、OpenAPI、GraphQL和SOAP的API网关。
* [Artio](https://github.com/real-logic/artio)：弹性高性能FIX和FIXP网关。
* [Choreo-Connect](https://github.com/wso2/product-microgateway)：Choreo Connect是一个云原生、开源且以开发人员为中心的API网关。
* [Liiklus](https://github.com/bsideup/liiklus)：基于事件的系统的响应式(RSocket/gRPC)网关。

<h2 id="sdk">SDK</h2>

* [Aliyun](https://github.com/aliyun/aliyun-openapi-java-sdk)：阿里云Java SDK。
* [TIMSDK](https://github.com/TencentCloud/TIMSDK)：腾讯云即时消息服务。
* [Azure](https://github.com/Azure/azure-sdk-for-java)：Azure Java SDK。
* [Azure IoT](https://github.com/Azure/azure-iot-sdk-java)：用于将设备连接到Microsoft Azure IoT服务的Java SDK。
* [Alipay](https://github.com/alipay/alipay-easysdk)：支付宝开放平台服务端SDK。
* [Tencent](https://github.com/TencentCloud/tencentcloud-sdk-java)：腾讯云API 3.0 Java SDK。
* [Kubernetes Operator](https://github.com/operator-framework/java-operator-sdk)：用于构建Kubernetes Operator的Java SDK。
* [Aliyun OSS](https://github.com/aliyun/aliyun-oss-java-sdk)：Aliyun OSS的Java SDK。
* [Aliyun OSS Android](https://github.com/aliyun/aliyun-oss-android-sdk)：阿里云对象存储服务Android SDK。
* [Aliyun log](https://github.com/aliyun/aliyun-log-java-sdk)：可以调用所有日志服务API的Java SDK。
* [aliyun-odps-java-sdk](https://github.com/aliyun/aliyun-odps-java-sdk)：面向Java开发者的ODPS SDK。
* [Volcengine](https://github.com/volcengine/volcengine-java-sdk)：火山引擎Java SDK。
* [WxJava](https://github.com/Wechat-Group/WxJava)：微信开发Java SDK，支持包括微信支付、开放平台、小程序、企业微信、公众号等的后端开发。
* [AWS](https://github.com/aws/aws-sdk-java-v2)：AWS官方的Java SDK。
* [AWS Encryption](https://github.com/aws/aws-encryption-sdk-java)：AWS加密SDK。
* [AWS IoT](https://github.com/aws/aws-iot-device-sdk-java)：用于从设备连接到AWS IoT的Java SDK。
* [AWS X-Ray](https://github.com/aws/aws-xray-sdk-java)：适用于Java的官方AWS X-Ray记录器SDK。
* [AWS C3R](https://github.com/aws/c3r)：C3R加密客户端和SDK。
* [Huawei](https://github.com/huaweicloud/huaweicloud-sdk-java-v3)：华为云Java SDK。
* [Huawei OBS](https://github.com/huaweicloud/huaweicloud-sdk-java-obs)：用于访问对象存储服务的OBS Java SDK。
* [Google App Engine](https://github.com/GoogleCloudPlatform/appengine-java-standard)：Google App Engine标准Java运行时：Prod运行时、本地devappserver、Cloud SDK Java组件、GAE API和GAE API模拟器。
* [DataflowTemplates](https://github.com/GoogleCloudPlatform/DataflowTemplates)：Google提供的Cloud Dataflow模板管道用于解决简单的云内数据任务。
* [Google Pub/Sub](https://github.com/GoogleCloudPlatform/pubsub)：Google Cloud Pub/Sub开源项目。
* [Google Map](https://github.com/googlemaps/android-maps-utils)：Android地图SDK实用程序库。
* [React-Native](https://github.com/facebookarchive/react-native-fbsdk)：针对Android和iOS的Facebook SDK的React Native包装器。
* [best-pay-sdk](https://github.com/Pay-Group/best-pay-sdk)：支付宝、微信支付SDK。
* [weixin-java-tools](https://github.com/chanjarster/weixin-java-tools)：微信公众号、企业号Java SDK。
* [weixin-popular](https://github.com/liyiorg/weixin-popular)：微信Java SDK(公众平台、开放平台、 商户平台、 服务商平台)。
* [Firebase Android](https://github.com/firebase/firebase-android-sdk)：Firebase安卓SDK。
* [lancet](https://github.com/eleme/lancet)：面向Android App和SDK开发人员的轻量级快速AOP框架。
* [MinIO](https://github.com/minio/minio-java)：用于Java的MinIO客户端SDK。
* [PayPal](https://github.com/paypal/PayPal-Android-SDK)：接入PayPal支付的Android SDK。

<h2 id="blockchain">区块链</h2>

* [web3j](https://github.com/web3j/web3j)：用于与以太坊客户端集成的轻量级Java和Android库。
* [ta4j](https://github.com/ta4j/ta4j)：用于技术分析的Java库。
* [token-core-android](https://github.com/consenlabs/token-core-android)：Android上的区块链私钥管理库。
* [md_blockchain](https://gitee.com/tianyalei/md_blockchain)：开源Java区块链平台，可做联盟链、私链使用，不适用于公链。
* [Keycard](https://github.com/status-im/status-keycard)：Keycard是在Javacard 3.0.4+上运行的BIP-32 HD钱包的实现。
* [Arbitrader](https://github.com/agonyforge/arbitrader)：市场中立的加密货币交易机器人。
* [Apache Tuweni](https://github.com/apache/incubator-tuweni)：Apache Tuweni是一组库和其他工具，可帮助使用Java和其他JVM语言开发区块链和其他去中心化软件。
* [FundRequest](https://github.com/FundRequest/platform)：FundRequest平台代码。
* [blockj](https://gitee.com/blackfox/blockj)：Java实现的一个简易区块链(联盟链)项目，包括加密工具、钱包、P2P传输、区块同步、网络共识等基础实现。
* [jdchain](https://gitee.com/jdchain/jdchain)：京东区块链是一个企业级的区块链框架系统，具有简洁、易用、可扩展和高性能的特点。
* [J2Chain](https://gitee.com/ld/J2Chain)：Java开发区块链的开源项目。
* [fex-wallet-app](https://gitee.com/koch/fex-wallet-app)：加密货币钱包，数字货币交易所，区块链数字资产管理工具。
* [fabric-sdk-java](https://github.com/hyperledger/fabric-sdk-java)：该项目提供了一个用于与Hyperledger Fabric区块链网络交互的低级API。
* [WeIdentity](https://github.com/WeBankBlockchain/WeIdentity)：基于区块链的符合W3C DID和Verifiable Credential规范的分布式身份解决方案。
* [WeEvent](https://github.com/WeBankBlockchain/WeEvent)：基于区块链的事件驱动架构。
* [WeBASE](https://github.com/WeBankBlockchain/WeBASE)：微众银行区块链应用软件扩展。
* [WeCross](https://github.com/WeBankBlockchain/WeCross)：WeCross跨链路由。
* [tokencore](https://github.com/GalaxySciTech/tokencore)：区块链钱包后端核心组件，支持多种区块链地址生成和离线签名。
* [nuls-v1](https://github.com/nuls-io/nuls-v1)：Nuls是一个全球区块链开源项目，是一个高度可定制的模块化区块链基础设施。
* [nuls-v2](https://github.com/nuls-io/nuls-v2)：NULS协议的官方Java实现。
* [Aion](https://github.com/aionnetwork/aion)：Aion网络-Java实现。
* [Blockchain](https://github.com/Will1229/Blockchain)：区块链的Java简单实现。
* [quilt](https://github.com/hyperledger-archives/quilt)：Interledger协议的实现。
* [simblock](https://github.com/dsg-titech/simblock)：开源区块链网络模拟器。
* [blockchain-java](https://github.com/wangweiX/blockchain-java)：Java中的简化区块链实现。
* [neow3j](https://github.com/neow3j/neow3j)：Neo区块链的Java/Kotlin/Android开发工具包。
* [coti-node](https://github.com/coti-io/coti-node)：COTI是第一个基于DAG的链协议，针对企业和稳定币进行了优化。
* [eosio](https://github.com/EOSIO/eosio-java)：用于与基于EOSIO的区块链集成的API。
* [Cardano](https://github.com/bloxbean/cardano-client-lib)：Java中的Cardano客户端库。
* [thunder](https://github.com/blockchain/thunder)：使用智能合约进行链下比特币支付。
* [Web3signer](https://github.com/Consensys/web3signer)：Web3Signer是一种开源签名服务，能够使用存储在外部保管库中或加密在磁盘上的私钥在多个平台(Ethereum1和2、Filecoin)上进行签名。
* [hedera-services](https://github.com/hashgraph/hedera-services)：Hedera公共账本的加密货币、代币、共识、文件和智能合约服务。
* [SmartJ](https://github.com/signum-network/signum-smartj)：Signum的Java智能合约。

<h2 id="ethereum">以太坊</h2>

* [ethereumj](https://github.com/ethereum/ethereumj)：以太坊黄皮书的Java实现。
* [besu](https://github.com/hyperledger/besu)：基于Java的企业级以太坊客户端。
* [teku](https://github.com/Consensys/teku)：以太坊2.0信标链的Java实现。
* [AlphaWallet](https://github.com/AlphaWallet/alpha-wallet-android)：先进的以太坊手机钱包。
* [Eventeum](https://github.com/eventeum/eventeum)：弹性以太坊事件监听器，可连接你的智能合约事件和后端微服务。
* [presto-ethereum](https://github.com/xiaoyao1991/presto-ethereum)：Presto以太坊连接器-以太坊上的SQL。
* [Trust](https://github.com/trustwallet/trust-wallet-android-source)：Android版以太坊钱包。
* [ETHWallet](https://github.com/DwyaneQ/ETHWallet)：像imToken这样的以太坊钱包。
* [securify](https://github.com/eth-sri/securify)：以太坊智能合约安全扫描器。
* [BitcoinWallet](https://github.com/terryjiao/BitcoinWallet)：比特币和以太坊钱包。
* [wuhanchain](https://github.com/BSN-DDC/wuhanchain)：BSN官方DDC智能合约和SDK基于开放许可的区块链-武汉链(以太坊)。

<h2 id="bitcoin">比特币</h2>

* [bitcoinj](https://github.com/bitcoinj/bitcoinj)：使用比特币的库。
* [bisq](https://github.com/bisq-network/bisq)：去中心化的比特币交易网络。
* [XChange](https://github.com/knowm/XChange)：XChange是一个Java库，提供简化的API，用于与60多个比特币和山寨币交易所进行交互，为交易和访问市场数据提供一致的接口。
* [bitcoin-wallet](https://github.com/bitcoin-wallet/bitcoin-wallet)：适用于Android设备的比特币钱包应用程序。
* [exchange-core](https://github.com/exchange-core/exchange-core)：使用Java编写的超快速匹配引擎，基于LMAX Disruptor、Eclipse Collections、Agrona、OpenHFT、LZ4 Java和Adaptive Radix Trees。
* [Crypto-Exchange](https://github.com/jammy928/CoinExchange_CryptoExchange_Java)：基于Spring Cloud微服务开发，可用于数字货币交易所的搭建和二次开发。
* [OBAndroid](https://github.com/omnilaboratory/OBAndroid)：OBAndroid是一款适用于Android设备的自我托管OmniBOLT闪电钱包。
* [Sparrow](https://github.com/sparrowwallet/sparrow)：Sparrow是一款现代桌面比特币钱包应用程序，支持大多数硬件钱包，并基于PSBT等通用标准构建，强调透明度和可用性。
* [Drongo](https://github.com/sparrowwallet/drongo)：一个Java比特币库。
* [BX-bot](https://github.com/gazbert/bxbot)：用Java编写的简单比特币交易机器人。
* [wallet-android](https://github.com/mycelium-com/wallet-android)：Android版Mycelium比特币钱包。
* [DiabloMiner](https://github.com/Diablo-D3/DiabloMiner)：比特币OpenCL矿工。
* [bither-android](https://github.com/bither/bither-android)：简单安全的比特币钱包。
* [warpexchange](https://github.com/michaelliao/warpexchange)：简单、超快的7x24交换。
* [Boilr](https://github.com/drpout/boilr)：比特币、加密货币、加密资产、期货和期权的价格警报。
* [CoinExchange](https://gitee.com/cexchange/CoinExchange)：开源数字货币合约交易所，基于Java开发的比特币交易所、BTC交易所、ETH交易所、数字货币交易所、交易平台、撮合交易引擎。

<h2 id="spring">Spring生态</h2>

* [spring-boot-admin](https://github.com/codecentric/spring-boot-admin)：用于管理Spring Boot应用程序的管理UI。
* [mybatis-spring-boot](https://github.com/mybatis/spring-boot-starter)：MyBatis与Spring Boot集成。
* [Spring-Initializr](https://github.com/spring-io/initializr)：Spring项目的快速生成器。
* [grpc-spring-boot-starter](https://github.com/yidongnan/grpc-spring-boot-starter)：gRPC框架的Spring Boot Starter模块。
* [grpc-spring-boot-starter](https://github.com/LogNet/grpc-spring-boot-starter)：gRPC的Spring Boot Starter模块。
* [retrofit-spring-boot-starter](https://github.com/LianjiaTech/retrofit-spring-boot-starter)：适用于Retrofit的Spring Boot Starter，支持快速集成和功能增强。
* [spring-boot-data-source-decorator](https://github.com/gavlyukovskiy/spring-boot-data-source-decorator)：Spring Boot与p6spy、datasource-proxy、flexy-pool和spring-cloud-sleuth集成。
* [redis-om-spring](https://github.com/redis/redis-om-spring)：Spring Data Redis扩展，可实现更好的搜索、文档模型等。
* [chatgpt-spring-boot-starter](https://github.com/linux-china/chatgpt-spring-boot-starter)：Spring Boot ChatGPT Starter。
* [spring-modulith](https://github.com/spring-projects/spring-modulith)：使用Spring Boot的模块化应用程序。
* [spring-data-jpa-entity-graph](https://github.com/Cosium/spring-data-jpa-entity-graph)：Spring Data JPA扩展允许在Repository上完全动态使用EntityGraph。
* [error-handling-spring-boot-starter](https://github.com/wimdeblauwe/error-handling-spring-boot-starter)：可配置的REST API错误处理。
* [okta-spring-boot](https://github.com/okta/okta-spring-boot)：Okta Spring Boot Starter。
* [spring-content](https://github.com/paulcwarren/spring-content)：Spring的云原生存储和企业内容服务(ECMS)。
* [spring-boot-logging](https://github.com/piomin/spring-boot-logging)：用于记录Spring Boot应用程序的HTTP请求/响应以及与Elastic Stack集成的库。
* [spring-boot-starter-calma](https://github.com/marvinSpring/spring-boot-starter-calma)：异常通知框架。
* [htmx-spring-boot](https://github.com/wimdeblauwe/htmx-spring-boot)：用于使用htmx的Spring Boot和Thymeleaf助手。
* [wiremock-spring-boot](https://github.com/maciejwalkowiak/wiremock-spring-boot)：WireMock Spring Boot极大地简化了基于Spring Boot和Junit 5的集成测试中的HTTP客户端测试。
* [djl-spring-boot-starter](https://github.com/deepjavalibrary/djl-spring-boot-starter)：DJL Spring Boot Starter。
* [spring-view-component](https://github.com/tschuehly/spring-view-component)：使用Spring创建服务器端ViewComponent的库。
* [narayana-spring-boot](https://github.com/snowdrop/narayana-spring-boot)：Narayana Spring Boot自动配置和Starter。
* [spring-test-dbunit](https://github.com/springtestdbunit/spring-test-dbunit)：Spring测试框架和DBUnit之间的集成。
* [aliyun-spring-boot](https://github.com/alibaba/aliyun-spring-boot)：阿里云服务Spring Boot Starter。
* [springwolf-core](https://github.com/springwolf/springwolf-core)：使用Spring Boot构建的异步API的自动化文档。
* [camel-spring-boot](https://github.com/apache/camel-spring-boot)：Apache Camel Spring Boot支持。
* [wicket-spring-boot](https://github.com/MarcGiffing/wicket-spring-boot)：Apache Wicket的Spring Boot Starter。
* [bitcoin-spring-boot-starter](https://github.com/theborakompanioni/bitcoin-spring-boot-starter)：使用Spring Boot编写企业比特币应用程序的工具。
* [bucket4j-spring-boot-starter](https://github.com/MarcGiffing/bucket4j-spring-boot-starter)：Bucket4j的Spring Boot Starter。
* [camunda-bpm-spring-boot-starter](https://github.com/camunda/camunda-bpm-spring-boot-starter)：Camunda的Spring Boot Starter。
* [charon-spring-boot-starter](https://github.com/mkopylec/charon-spring-boot-starter)：以Spring Boot Starter形式的反向代理实现。
* [desensitization-spring-boot](https://github.com/allurx/desensitization-spring-boot)：脱敏库与Spring Boot集成。
* [errors-spring-boot-starter](https://github.com/alimate/errors-spring-boot-starter)：Spring Boot的优雅错误处理。
* [recaptcha-spring-boot-starter](https://github.com/mkopylec/recaptcha-spring-boot-starter)：Google reCAPTCHA的Spring Boot Starter。
* [jade4j-spring-boot-starter](https://github.com/domix/jade4j-spring-boot-starter)：Spring Boot jade4j Starter。
* [resteasy-spring-boot](https://github.com/resteasy/resteasy-spring-boot)：RESTEasy Spring Boot Starter。
* [cxf-spring-boot-starter](https://github.com/codecentric/cxf-spring-boot-starter)：由Spring Boot和Apache CXF提供支持的企业和生产就绪SOAP Web Service。
* [spring-boot-starter-batch-web](https://github.com/codecentric/spring-boot-starter-batch-web)：由Spring Boot提供支持的企业就绪、生产就绪的批处理应用程序。
* [cassandre-trading-bot](https://github.com/cassandre-tech/cassandre-trading-bot)：在几分钟内创建Java加密货币交易机器人，Starter负责处理交易所连接、账户、订单、交易和头寸，以便可以专注于构建策略。
* [problem-spring-web](https://github.com/zalando/problem-spring-web)：用于处理Spring Web MVC中问题的库。
* [spring-ai](https://github.com/spring-projects-experimental/spring-ai)：Spring AI项目旨在简化包含人工智能功能的应用程序的开发，避免不必要的复杂性。

<h2 id="raft">Raft算法</h2>

* [SOFAJRaft](https://github.com/sofastack/sofa-jraft)：Raft共识算法的生产级Java实现。
* [raft-java](https://github.com/wenweihu86/raft-java)：Raft算法的简单Java实现。
* [Apache Ratis](https://github.com/apache/ratis)：Raft共识协议的开源Java实现。
* [dledger](https://github.com/openmessaging/dledger)：一个基于Raft的java库，用于构建高可用、高持久、强一致的提交日志。
* [lu-raft-kv](https://github.com/stateIs0/lu-raft-kv)：这是一个Java版本的Raft(CP) KV分布式存储实现。
* [Copycat](https://github.com/atomix/copycat)：Raft一致性算法的新颖实现。
* [jgroups-raft](https://github.com/belaban/jgroups-raft)：Raft共识协议在JGroups中的实现。
* [xraft](https://github.com/xnnyygn/xraft)：简单的Raft共识算法实现。
* [jraft](https://github.com/datatechnology/jraft)：简单的Raft共识算法实现。
* [MicroRaft](https://github.com/MicroRaft/MicroRaft)：Raft一致性算法在Java中的功能完整实现。
* [libraft](https://github.com/allengeorge/libraft)：Java中的Raft分布式共识协议。

<h2 id="paxos">Paxos算法</h2>

* [WPaxos](https://github.com/wuba/WPaxos)：Paxos共识算法的生产级Java实现。
* [WLock](https://github.com/wuba/WLock)：基于共识算法组件WPaxos的高可靠、高吞吐量的分布式锁服务。
* [Klein](https://github.com/shihuili1218/klein)：Klein是一个基于Paxos的分布式集合工具库，包括分布式ArrayList、分布式HashMap、分布式Cache、分布式锁等。
* [Paxos](https://github.com/jaksa76/paxos)：Paxos算法的Java实现。
* [URingPaxos](https://github.com/sambenz/URingPaxos)：高吞吐量原子多播协议。
* [PaxosImpl](https://github.com/hellolinjx/PaxosImpl)：Paxos算法的多线程实现。

<h2 id="distributed-lock">分布式锁</h2>

* [Redisson](https://github.com/redisson/redisson)：具有内存数据网格功能的简单Redis Java客户端，包含实现分布式锁的功能。
* [ShedLock](https://github.com/lukas-krecan/ShedLock)：计划任务的分布式锁。
* [klock](https://github.com/kekingcn/spring-boot-klock-starter)：基于Redis的分布式锁组件，简单方便快捷接入项目，使项目拥有分布式锁能力。
* [Distributed-Kit](https://github.com/yujiasun/Distributed-Kit)：基于Redis和Zookeeper分布式工具集，包括分布式锁实现。
* [Lock4j](https://gitee.com/baomidou/lock4j)：基于Spring AOP的声明式和编程式分布式锁，支持RedisTemplate、Redisson、Zookeeper。
* [amazon-dynamodb-lock-client](https://github.com/awslabs/amazon-dynamodb-lock-client)：构建在DynamoDB之上的通用分布式锁库，支持粗粒度和细粒度锁定。
* [Aquarius](https://github.com/Nepxion/Aquarius)：Aquarius是一款基于Redis + Zookeeper的分布式应用组件集合，包含分布式锁功能。
* [redis-distributed-lock](https://github.com/TaXueWWL/redis-distributed-lock)：Redis分布式锁工具包，提供纯Java方式调用，支持传统Spring工程，为Spring Boot应用提供了Starter，更方便快捷的调用。
* [distributed-lock](https://github.com/alturkovic/distributed-lock)：使用Spring进行分布式锁的简单实现。
* [DLock](https://github.com/baidu/dlock)：有效可靠的分布式锁。
* [jedis-lock](https://github.com/abelaska/jedis-lock)：Jedis分布式锁支持。
* [WLock](https://github.com/wuba/WLock)：基于共识算法组件WPaxos的高可靠、高吞吐量的分布式锁服务。
* [Distributor](https://gitee.com/HappyChicken/Distributor)：常用分布式组件：分布式锁、分布式序列、分布式限流等。
* [coody-elock](https://gitee.com/coodyer/coody-elock)：一款基于Redis订阅实现的分布式锁插件。
* [redis-shared-lock](https://gitee.com/lsongiu/redis-shared-lock)：基于Redis的分布式共享锁，使用注解的方式对方法加锁。
* [DistributedLock](https://github.com/wyzssw/DistributedLock)：Redis分布式锁实现。