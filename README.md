# cloud-toolkit-creplica

![Build](https://github.com/meiMingle/cloud-toolkit-creplica/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)

## 待办列表
- [ ] 重建依赖列表

- [ ] 重建Host功能

- [ ] 重建Cloud View功能

- [ ] 重建应用观测&热部署功能

- [ ] 去除非必要的依赖



<!-- Plugin description -->
这是一个基于Alibaba Cloud Toolkit创建的仿制品，本项目的诞生得益于该项目以apache 2.0协议发布。
<!-- Plugin description end -->

## 原项目依赖整理列表

| libs  | GAV（kotlin） | 描述 |
| ---- | :--: | ---- |
|activation-1.1.1.jar| implementation("javax.activation:activation:1.1.1") | javabean相关 |
|aliyun-java-sdk-codeup-0.1.2.jar| implementation("com.aliyun:aliyun-java-sdk-codeup:0.1.2") | codeup相关 |
|aliyun-java-sdk-core-4.6.0.jar| implementation("com.aliyun:aliyun-java-sdk-core:4.6.0") |    |
|aliyun-java-sdk-cr-4.1.1.jar|    |    |
|aliyun-java-sdk-cs-4.7.15.jar|    |    |
|aliyun-java-sdk-devops-rdc-1.9.0.jar|    |    |
|aliyun-java-sdk-ecs-4.18.0.jar|    |    |
|aliyun-java-sdk-edas-3.26.12.foract-SNAPSHOT.jar|    |    |
|aliyun-java-sdk-fc-1.8.14.jar|    |    |
|aliyun-java-sdk-fc-open-1.0.1.jar|    |    |
|aliyun-java-sdk-mpca-inner-1.0.0.jar|    |    |
|aliyun-java-sdk-mse-3.0.25.jar|    |    |
|aliyun-java-sdk-ram-3.0.0.jar|    |    |
|aliyun-java-sdk-rds-2.3.2.jar|    |    |
|aliyun-java-sdk-resourcemanager-1.0.0.jar|    |    |
|aliyun-java-sdk-ros-3.2.1.jar|    |    |
|aliyun-java-sdk-sae-1.0.1.jar|    |    |
|aliyun-java-sdk-sts-3.0.0.jar|    |    |
|aliyun-log-0.6.33.jar|    |    |
|aliyun-sdk-oss-3.1.0.jar|    |    |
|annotations-17.0.0.jar|    |    |
|antlr4-runtime-4.7.jar|    |    |
|aopalliance-1.0.jar|    |    |
|aopalliance-repackaged-2.4.0-b34.jar|    |    |
|app-observer-server-1.0.33-SNAPSHOT.jar|    |    |
|asm-7.1.jar|    |    |
|asm-analysis-5.0.3.jar|    |    |
|asm-commons-5.0.3.jar|    |    |
|asm-tree-5.0.3.jar|    |    |
|asm-util-5.0.3.jar|    |    |
|asn-one-0.5.0.jar|    |    |
|bcpkix-jdk15on-1.68.jar|    |    |
|bcprov-ext-jdk15on-1.61.jar|    |    |
|bcprov-jdk15on-1.70.jar|    |    |
|builder-annotations-0.18.0.jar|    |    |
|c3p0-0.9.5.4.jar|    |    |
|checker-qual-3.8.0.jar|    |    |
|client-java-5.0.0.jar|    |    |
|client-java-api-5.0.0.jar|    |    |
|client-java-proto-5.0.0.jar|    |    |
|cloudapitest-connect-1.0.0-SNAPSHOT.jar|    |    |
|commons-1.1.8-SNAPSHOT.jar|    |    |
|commons-beanutils-1.9.2.jar|    |    |
|commons-codec-1.11.jar|    |    |
|commons-collections-3.2.2.jar|    |    |
|commons-compress-1.21.jar|    |    |
|commons-csv-1.6.jar|    |    |
|commons-digester-1.8.1.jar|    |    |
|commons-io-2.6.jar|    |    |
|commons-lang-2.6.jar|    |    |
|commons-lang3-3.8.1.jar|    |    |
|commons-logging-1.2.jar|    |    |
|commons-net-3.6.jar|    |    |
|commons-validator-1.6.jar|    |    |
|commons-vfs2-2.3.jar|    |    |
|converter-gson-2.3.0.jar|    |    |
|docker-client-8.16.0.jar|    |    |
|docker-java-api-3.2.2.jar|    |    |
|docker-java-core-3.2.2.jar|    |    |
|docker-java-transport-3.2.2.jar|    |    |
|docker-java-transport-okhttp-3.2.2.jar|    |    |
|dubbo-2.7.3.jar|    |    |
|eddsa-0.3.0.jar|    |    |
|error_prone_annotations-2.5.1.jar|    |    |
|ezmorph-1.0.6.jar|    |    |
|failureaccess-1.0.1.jar|    |    |
|fastjson-1.2.68.noneautotype.jar|    |    |
|fluent-hc-4.5.7.jar|    |    |
|freemarker-2.3.25-incubating.jar|    |    |
|google-http-client-1.39.2.jar|    |    |
|gradle-tooling-api-5.0.jar|    |    |
|grpc-context-1.27.2.jar|    |    |
|gson-2.8.9.jar|    |    |
|guava-30.1.1-jre.jar|    |    |
|guice-4.2.2.jar|    |    |
|hk2-api-2.4.0-b34.jar|    |    |
|hk2-locator-2.4.0-b34.jar|    |    |
|hk2-utils-2.4.0-b34.jar|    |    |
|httpasyncclient-4.0.2.jar|    |    |
|httpclient-4.5.13.jar|    |    |
|httpcore-4.4.15.jar|    |    |
|httpcore-nio-4.3.2.jar|    |    |
|httpmime-4.5.7.jar|    |    |
|ini4j-0.5.4.jar|    |    |
|istack-commons-runtime-4.0.1.jar|    |    |
|j2objc-annotations-1.3.jar|    |    |
|jackson-annotations-2.13.2.jar|    |    |
|jackson-core-2.13.2.jar|    |    |
|jackson-databind-2.13.2.2.jar|    |    |
|jackson-dataformat-xml-2.13.2.jar|    |    |
|jackson-dataformat-yaml-2.13.2.jar|    |    |
|jackson-datatype-guava-2.13.2.jar|    |    |
|jackson-jaxrs-base-2.13.2.jar|    |    |
|jackson-jaxrs-json-provider-2.13.2.jar|    |    |
|jackson-module-jaxb-annotations-2.13.2.jar|    |    |
|jakarta.activation-2.0.1.jar|    |    |
|jakarta.activation-api-1.2.1.jar|    |    |
|jakarta.xml.bind-api-3.0.1.jar|    |    |
|javacc-5.0.jar|    |    |
|java-gitlab-api-1.2.5.jar|    |    |
|javassist-3.24.0-GA.jar|    |    |
|javax.annotation-api-1.3.2.jar|    |    |
|javax.inject-1.jar|    |    |
|javax.inject-2.4.0-b34.jar|    |    |
|javax.ws.rs-api-2.0.1.jar|    |    |
|jaxb-core-2.3.0.jar|    |    |
|jaxb-core-3.0.2.jar|    |    |
|jaxb-impl-2.3.0.jar|    |    |
|jaxb-runtime-3.0.2.jar|    |    |
|jcommander-1.72.jar|    |    |
|jdom2-2.0.6.jar|    |    |
|jersey-apache-connector-2.22.2.jar|    |    |
|jersey-client-2.22.2.jar|    |    |
|jersey-common-2.22.2.jar|    |    |
|jersey-entity-filtering-2.22.2.jar|    |    |
|jersey-guava-2.22.2.jar|    |    |
|jersey-media-json-jackson-2.22.2.jar|    |    |
|jffi-1.2.15.jar|    |    |
|jffi-1.2.15-native.jar|    |    |
|jiconfont-1.0.0.jar|    |    |
|jiconfont-font_awesome-4.7.0.1.jar|    |    |
|jiconfont-swing-1.0.1.jar|    |    |
|jmustache-1.14.jar|    |    |
|jna-5.5.0.jar|    |    |
|jna-platform-5.5.0.jar|    |    |
|jnr-constants-0.9.8.jar|    |    |
|jnr-enxio-0.16.jar|    |    |
|jnr-ffi-2.1.4.jar|    |    |
|jnr-posix-3.0.35.jar|    |    |
|jnr-unixsocket-0.18.jar|    |    |
|jnr-x86asm-1.0.2.jar|    |    |
|joda-convert-1.2.jar|    |    |
|joda-time-2.9.3.jar|    |    |
|jsch-0.1.55.jar|    |    |
|json-lib-2.4-jdk15.jar|    |    |
|jsr305-3.0.2.jar|    |    |
|junit-3.8.2.jar|    |    |
|jzlib-1.1.3.jar|    |    |
|kotlin-stdlib-1.7.0.jar|    |    |
|kotlin-stdlib-common-1.7.0.jar|    |    |
|kotlin-stdlib-jdk7-1.7.0.jar|    |    |
|kotlin-stdlib-jdk8-1.7.0.jar|    |    |
|listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar|    |    |
|log4j-api-2.11.2.jar|    |    |
|log4j-core-2.11.2-sec.jar|    |    |
|logback-classic-1.2.3.jar|    |    |
|logback-core-1.2.3.jar|    |    |
|logging-interceptor-2.7.5.jar|    |    |
|lz4-1.3.0.jar|    |    |
|mchange-commons-java-0.2.15.jar|    |    |
|miglayout-core-5.1.jar|    |    |
|miglayout-swing-5.1.jar|    |    |
|minio-8.4.3.jar|    |    |
|mysql-connector-java-5.1.47.jar|    |    |
|nacos-api-1.1.1.jar|    |    |
|nacos-client-1.1.1.jar|    |    |
|nacos-common-1.1.1.jar|    |    |
|netty-all-4.1.65.Final.jar|    |    |
|netty-buffer-4.1.67.Final.jar|    |    |
|netty-codec-4.1.67.Final.jar|    |    |
|netty-codec-dns-4.1.67.Final.jar|    |    |
|netty-codec-http2-4.1.67.Final.jar|    |    |
|netty-codec-http-4.1.67.Final.jar|    |    |
|netty-codec-socks-4.1.67.Final.jar|    |    |
|netty-common-4.1.67.Final.jar|    |    |
|netty-handler-4.1.67.Final.jar|    |    |
|netty-handler-proxy-4.1.67.Final.jar|    |    |
|netty-resolver-4.1.67.Final.jar|    |    |
|netty-resolver-dns-4.1.67.Final.jar|    |    |
|netty-transport-4.1.67.Final.jar|    |    |
|okhttp-2.7.5.jar|    |    |
|okhttp-4.8.1.jar|    |    |
|okhttp-ws-2.7.5.jar|    |    |
|okio-jvm-2.7.0.jar|    |    |
|opencensus-api-0.28.0.jar|    |    |
|opencensus-contrib-http-util-0.28.0.jar|    |    |
|opentracing-api-0.33.0.jar|    |    |
|opentracing-noop-0.33.0.jar|    |    |
|opentracing-util-0.33.0.jar|    |    |
|org.jacoco.agent-0.8.7-runtime.jar|    |    |
|org.json-chargebee-1.0.jar|    |    |
|osgi-resource-locator-1.0.1.jar|    |    |
|p3c-pmd-2.0.0.jar|    |    |
|pmd-core-6.15.0.jar|    |    |
|pmd-java-6.15.0.jar|    |    |
|pmd-vm-6.15.0.jar|    |    |
|protobuf-java-3.4.0.jar|    |    |
|resourcecify-annotations-0.18.0.jar|    |    |
|retrofit-2.3.0.jar|    |    |
|saxon-9.1.0.8.jar|    |    |
|saxon-9.1.0.8-dom.jar|    |    |
|searchableOptions-2022.9.1-222.jar|    |    |
|simpleclient-0.5.0.jar|    |    |
|simple-xml-safe-2.7.1.jar|    |    |
|siphash-1.0.0.jar|    |    |
|slf4j-api-1.7.32.jar|    |    |
|snakeyaml-1.30.jar|    |    |
|snappy-java-1.1.8.4.jar|    |    |
|spring-aop-4.3.16.RELEASE.jar|    |    |
|spring-beans-4.3.16.RELEASE.jar|    |    |
|spring-context-4.3.16.RELEASE.jar|    |    |
|spring-core-4.3.16.RELEASE.jar|    |    |
|spring-expression-4.3.16.RELEASE.jar|    |    |
|sqlite-jdbc-3.32.3.3.jar|    |    |
|sshj-0.31.0.jar|    |    |
|stax2-api-4.2.1.jar|    |    |
|sundr-codegen-0.18.0.jar|    |    |
|sundr-core-0.18.0.jar|    |    |
|swagger-annotations-1.5.12.jar|    |    |
|**`toolkit-intellij-2022.9.1-222.jar`**| 插件入口 |    |
|txw2-3.0.2.jar|    |    |
|vertx-auth-common-4.1.2.jar|    |    |
|vertx-bridge-common-4.1.2.jar|    |    |
|vertx-codegen-4.1.3.jar|    |    |
|vertx-config-4.1.2.jar|    |    |
|vertx-config-yaml-4.1.2.jar|    |    |
|vertx-core-4.1.3.jar|    |    |
|vertx-health-check-4.1.2.jar|    |    |
|vertx-jdbc-client-4.1.2.jar|    |    |
|vertx-lang-kotlin-4.1.2.jar|    |    |
|vertx-service-factory-4.1.3.jar|    |    |
|vertx-sql-client-4.1.2.jar|    |    |
|vertx-web-4.1.2.jar|    |    |
|vertx-web-common-4.1.2.jar|    |    |
|vfsjfilechooser2-0.2.8.jar|    |    |
|woodstox-core-6.2.7.jar|    |    |
|zt-exec-1.11.jar|    |    |
