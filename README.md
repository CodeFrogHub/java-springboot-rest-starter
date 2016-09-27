# springboot-starter

## info links

* [spring-boot-heroku-demo](https://github.com/kissaten/spring-boot-heroku-demo)

## Liquibase ([http://www.liquibase.org/](http://www.liquibase.org/))

```
buildscript {
  repositories {
    maven {
      url "https://plugins.gradle.org/m2/"
    }
  }
  dependencies {
    classpath "gradle.plugin.org.liquibase:liquibase-gradle-plugin:1.2.1"
  }
}

apply plugin: "org.liquibase.gradle"
```
