## Overview

It's sample for Azure Service Bus JMS Spring Boot Starter.

These samples [Service Bus Queue Sample](./azure-servicebus-jms-queue-spring-boot-sample/) and [Service Bus Topic Sample](./azure-servicebus-jms-topic-spring-boot-sample/) respectively demonstrates how to use Spring JMS Queue and Topic for Azure Service Bus via the Starter.

Running these samples will be charged by Azure. You can check the usage and bill at this [link](https://azure.microsoft.com/en-us/account/).

## Usage

### Add the dependency

Snapshot built from [master](https://github.com/microsoft/azure-spring-boot) branch is available, add maven repositories configuration to your pom file as below.

```xml
<repositories>
  <repository>
    <id>nexus-snapshots</id>
    <url>https://oss.sonatype.org/content/repositories/snapshots/</url>
    <snapshots>
      <enabled>true</enabled>
      <updatePolicy>always</updatePolicy>
    </snapshots>
  </repository>
</repositories>
```

Release version of the starter is being prepared. You can check it in the homepage of [master](https://github.com/microsoft/azure-spring-boot) branch after it's updated.

### How to run

These modules [Service Bus Queue Sample](./azure-servicebus-jms-queue-spring-boot-sample/) and [Service Bus Topic Sample](./azure-servicebus-jms-topic-spring-boot-sample/) respectively demonstrates how to use Spring JMS Queue and Topic for Azure Service Bus via the Starter.

Please refer to specific `README` of related module for detail usage according to your needs.

* [README](./spring-jms-servicebus-sample/azure-servicebus-queue-spring-jms-sample/README.md) for Spring JMS for Azure Service Bus Queue usage

* [README](./spring-jms-servicebus-sample/azure-servicebus-topic-spring-jms-sample/README.md) for Spring JMS for Azure Service Bus Topic usage


## Allow telemetry
Microsoft would like to collect data about how users use this Spring boot starter. Microsoft uses this information to improve our tooling experience. Participation is voluntary. If you don't want to participate, just simply disable it by setting below configuration in `application.properties`.
```
azure.servicebus.allow-telemetry=false
```
Find more information about Azure Service Privacy Statement, please check [Microsoft Online Services Privacy Statement](https://www.microsoft.com/en-us/privacystatement/OnlineServices/Default.aspx). 
