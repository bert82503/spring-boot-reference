# Spring Boot Reference Guide

This file serves as your book's preface, a great place to describe your book's content and ideas.

《Spring Boot参考指南》翻译笔记，避免PDF格式的参考指南版本升级而丢失先前注释的重点内容，解决重复性做笔记的问题。

官方文档：[1.5.4.RELEASE](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/ "Spring Boot Reference Guide 1.5.4.RELEASE")

---

##### Table of Contents

## [**I. Spring Boot Documentation**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-documentation.html)

## [**II. Getting started**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/getting-started.html)

## [**III. Using Spring Boot**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/using-boot.html)

## [**IV. Spring Boot features**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features.html)

### [**23. SpringApplication**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html)

#### [**23.1. Startup failure**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#_startup_failure)

#### [**23.2. Customizing the Banner**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-banner)

#### [**23.3. Customizing SpringApplication**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-customizing-spring-application)

#### [**23.4. Fluent builder API**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-fluent-builder-api)

#### [**23.5. Application events and listeners**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-application-events-and-listeners)

#### [**23.6. Web environment**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-web-environment)

#### [**23.7. Accessing application arguments**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-application-arguments)

#### [**23.8. Using the ApplicationRunner or CommandLineRunner**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-command-line-runner)

#### [**23.9. Application exit**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-application-exit)

#### [**23.10. Admin features**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-spring-application.html#boot-features-application-admin)

### [**24. Externalized Configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html)

#### [**24.1. Configuring random values**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-random-values)

#### [**24.2. Accessing command line properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-command-line-args)

#### [**24.3. Application property files**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-application-property-files)

#### [**24.4. Profile-specific properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-profile-specific-properties)

#### [**24.5. Placeholders in properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-placeholders-in-properties)

#### [**24.6. Using YAML instead of Properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-yaml)

```
        [24.6.1. Loading YAML](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-loading-yaml)

        [24.6.2. Exposing YAML as properties in the Spring Environment](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-exposing-yaml-to-spring)

        [24.6.3. Multi-profile YAML documents](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-multi-profile-yaml)

        [24.6.4. YAML shortcomings](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-yaml-shortcomings)

        [24.6.5. Merging YAML lists](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-complex-type-merge)
```

#### [**24.7. Type-safe Configuration Properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-typesafe-configuration-properties)

```
        [24.7.1. Third-party configuration](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-3rd-party-configuration)

        [24.7.2. Relaxed binding](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-relaxed-binding)

        [24.7.3. Properties conversion](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-conversion)

        [24.7.4. @ConfigurationProperties Validation](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-validation)

        [24.7.5. @ConfigurationProperties vs. @Value](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-external-config.html#boot-features-external-config-vs-value)
```

### [**25. Profiles**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-profiles.html)

#### [**25.1. Adding active profiles**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-profiles.html#boot-features-adding-active-profiles)

#### [**25.2. Programmatically setting profiles**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-profiles.html#boot-features-programmatically-setting-profiles)

#### [**25.3. Profile-specific configuration files**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-profiles.html#boot-features-profile-specific-configuration)

### [**40. Monitoring and management over JMX**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-jmx.html)

### [**41. Testing**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html)

#### [**41.1. Test scope dependencies**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-test-scope-dependencies)

#### [**41.2. Testing Spring applications**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-applications)

#### [**41.3. Testing Spring Boot applications**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications)

```
        [41.3.1. Detecting test configuration](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-detecting-config)

        [41.3.2. Excluding test configuration](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-excluding-config)

        [41.3.3. Working with random ports](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-working-with-random-ports)

        [41.3.4. Mocking and spying beans](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-mocking-beans)

        [41.3.5. Auto-configured tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-tests)

        [41.3.6. Auto-configured JSON tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-json-tests)

        [41.3.7. Auto-configured Spring MVC tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-mvc-tests)

        [41.3.8. Auto-configured Data JPA tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-jpa-test)

        [41.3.9. Auto-configured JDBC tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-jdbc-test)

        [41.3.10. Auto-configured Data MongoDB tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-mongo-test)

        [41.3.11. Auto-configured REST clients](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-rest-client)

        [41.3.12. Auto-configured Spring REST Docs tests](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-testing-autoconfigured-rest-docs)

        [41.3.13. Using Spock to test Spring Boot applications](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-testing-spring-boot-applications-with-spock)
```

#### [**41.4. Test utilities**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-test-utilities)

```
        [41.4.1. ConfigFileApplicationContextInitializer](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-configfileapplicationcontextinitializer-test-utility)

        [41.4.2. EnvironmentTestUtils](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-environment-test-utilities)

        [41.4.3. OutputCapture](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-output-capture-test-utility)

        [41.4.4. TestRestTemplate](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-testing.html#boot-features-rest-templates-test-utility)
```

### [**44. Creating your own auto-configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html)

#### [**44.1. Understanding auto-configured beans**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-understanding-auto-configured-beans)

#### [**44.2. Locating auto-configuration candidates**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-locating-auto-configuration-candidates)

#### [**44.3. Condition annotations**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-condition-annotations)

```
        [44.3.1. Class conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-class-conditions)

        [44.3.2. Bean conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-bean-conditions)

        [44.3.3. Property conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-property-conditions)

        [44.3.4. Resource conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-resource-conditions)

        [44.3.5. Web application conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-web-application-conditions)

        [44.3.6. SpEL expression conditions](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-spel-conditions)
```

#### [**44.4. Creating your own starter**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-custom-starter)

```
        [44.4.1. Naming](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-custom-starter-naming)

        [44.4.2. Autoconfigure module](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-custom-starter-module-autoconfigure)

        [44.4.3. Starter module](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-developing-auto-configuration.html#boot-features-custom-starter-module-starter)
```

### [**45. What to read next**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/boot-features-whats-next.html)

## [**V. Spring Boot Actuator: Production-ready features**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready.html)

### [**46. Enabling production-ready features**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-enabling.html)

### [**47. Endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html)

#### [**47.1. Customizing endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-customizing-endpoints)

#### [**47.2. Hypermedia for actuator MVC endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-endpoint-hypermedia)

#### [**47.3. CORS support**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-endpoint-cors)

#### [**47.4. Adding custom endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-customizing-endpoints-programmatically)

#### [**47.5. Health information**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-health)

#### [**47.6. Security with HealthIndicators**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#_security_with_healthindicators)

```
        [47.6.1. Auto-configured HealthIndicators](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#_auto_configured_healthindicators)

        [47.6.2. Writing custom HealthIndicators](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#_writing_custom_healthindicators)
```

#### [**47.7. Application information**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info)

```
        [47.7.1. Auto-configured InfoContributors](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info-autoconfigure)

        [47.7.2. Custom application info information](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info-env)

        [47.7.3. Git commit information](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info-git)

        [47.7.4. Build information](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info-build)

        [47.7.5. Writing custom InfoContributors](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-endpoints.html#production-ready-application-info-custom)
```

### [**48. Monitoring and management over HTTP**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html)

#### [**48.1. Accessing sensitive endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-sensitive-endpoints)

#### [**48.2. Customizing the management endpoint paths**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-customizing-management-server-context-path)

#### [**48.3. Customizing the management server port**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-customizing-management-server-port)

#### [**48.4. Configuring management-specific SSL**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-management-specific-ssl)

#### [**48.5. Customizing the management server address**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-customizing-management-server-address)

#### [**48.6. Disabling HTTP endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-disabling-http-endpoints)

#### [**48.7. HTTP health endpoint format and access restrictions**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-monitoring.html#production-ready-health-access-restrictions)

### [**49. Monitoring and management over JMX**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html)

#### [**49.1. Customizing MBean names**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html#production-ready-custom-mbean-names)

#### [**49.2. Disabling JMX endpoints**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html#production-ready-disable-jmx-endpoints)

#### [**49.3. Using Jolokia for JMX over HTTP**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html#production-ready-jolokia)

```
        [49.3.1. Customizing Jolokia](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html#production-ready-customizing-jolokia)

        [49.3.2. Disabling Jolokia](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-jmx.html#production-ready-disabling-jolokia)
```

### [**52. Metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html)

#### [**52.1. System metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-system-metrics)

#### [**52.2. DataSource metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-datasource-metrics)

#### [**52.3. Cache metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-datasource-cache)

#### [**52.4. Tomcat session metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-session-metrics)

#### [**52.5. Recording your own metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-recording-metrics)

#### [**52.6. Adding your own public metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-public-metrics)

#### [**52.7. Special features with Java 8**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-repositories)

#### [**52.8. Metric writers, exporters and aggregation**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-writers)

```
        [52.8.1. Example: Export to Redis](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-writers-export-to-redis)

        [52.8.2. Example: Export to Open TSDB](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-writers-export-to-open-tsdb)

        [52.8.3. Example: Export to Statsd](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-writers-export-to-statsd)

        [52.8.4. Example: Export to JMX](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-writers-export-to-jmx)
```

#### [**52.9. Aggregating metrics from multiple sources**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metric-aggregation)

#### [**52.10. Dropwizard Metrics**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-dropwizard-metrics)

#### [**52.11. Message channel integration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-metrics.html#production-ready-metrics-message-channel-integration)

### [**53. Auditing**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-auditing.html)

### [**54. Tracing**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-tracing.html)

#### [**54.1. Custom tracing**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-tracing.html#production-ready-custom-tracing)

### [**55. Process monitoring**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-process-monitoring.html)

#### [**55.1. Extend configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-process-monitoring.html#production-ready-process-monitoring-configuration)

#### [**55.2. Programmatically**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-process-monitoring.html#production-ready-process-monitoring-programmatically)

### [**56. Cloud Foundry support**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-cloudfoundry.html)

#### [**56.1. Disabling extended Cloud Foundry actuator support**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-cloudfoundry.html#production-ready-cloudfoundry-disable)

#### [**56.2. Cloud Foundry self signed certificates**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-cloudfoundry.html#production-ready-cloudfoundry-ssl)

#### [**56.3. Custom security configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-cloudfoundry.html#production-ready-cloudfoundry-custom-security)

### [**57. What to read next**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/production-ready-whats-next.html)

## [**IX. ‘How-to’ guides**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto.html)

### [**71. Spring Boot application**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html)

#### [**71.1. Create your own FailureAnalyzer**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html#howto-failure-analyzer)

#### [**71.2. Troubleshoot auto-configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html#howto-troubleshoot-auto-configuration)

#### [**71.3. Customize the Environment or ApplicationContext before it starts**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html#howto-customize-the-environment-or-application-context)

#### [**71.4. Build an ApplicationContext hierarchy \(adding a parent or root context\)**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html#howto-build-an-application-context-hierarchy)

#### [**71.5. Create a non-web application**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-spring-boot-application.html#howto-create-a-non-web-application)

### [**72. Properties & configuration**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html)

#### [**72.1. Automatically expand properties at build time**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-automatic-expansion)

```
        [72.1.1. Automatic property expansion using Maven](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-automatic-expansion-maven)

        [72.1.2. Automatic property expansion using Gradle](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-automatic-expansion-gradle)
```

#### [**72.2. Externalize the configuration of SpringApplication**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-externalize-configuration)

#### [**72.3. Change the location of external properties of an application**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-change-the-location-of-external-properties)

#### [**72.4. Use ‘short’ command line arguments**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-use-short-command-line-arguments)

#### [**72.5. Use YAML for external properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-use-yaml-for-external-properties)

#### [**72.6. Set the active Spring profiles**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-set-active-spring-profiles)

#### [**72.7. Change configuration depending on the environment**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-change-configuration-depending-on-the-environment)

#### [**72.8. Discover built-in options for external properties**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-properties-and-configuration.html#howto-discover-build-in-options-for-external-properties)

### [**73. Embedded servlet containers**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html)

#### [**73.1. Add a Servlet, Filter or Listener to an application**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-add-a-servlet-filter-or-listener)

```
        [73.1.1. Add a Servlet, Filter or Listener using a Spring bean](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-add-a-servlet-filter-or-listener-as-spring-bean)

            [Disable registration of a Servlet or Filter](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-disable-registration-of-a-servlet-or-filter)

        [73.1.2. Add Servlets, Filters, and Listeners using classpath scanning](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-add-a-servlet-filter-or-listener-using-scanning)
```

#### [**73.2. Change the HTTP port**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-change-the-http-port)

#### [**73.3. Use a random unassigned HTTP port**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-user-a-random-unassigned-http-port)

#### [**73.4. Discover the HTTP port at runtime**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-discover-the-http-port-at-runtime)

#### [**73.5. Configure SSL**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-configure-ssl)

#### [**73.6. Configure Access Logging**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-configure-accesslogs)

#### [**73.7. Use behind a front-end proxy server**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-use-tomcat-behind-a-proxy-server)

```
        [73.7.1. Customize Tomcat’s proxy configuration](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-customize-tomcat-behind-a-proxy-server)
```

#### [**73.8. Configure Tomcat**](http://docs.spring.io/spring-boot/docs/1.5.4.RELEASE/reference/html/howto-embedded-servlet-containers.html#howto-configure-tomcat)



