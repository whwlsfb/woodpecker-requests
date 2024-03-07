<h1 align="center">woodpecker-requests</h1>

<p align="center">
  <img title="portainer" src='https://img.shields.io/badge/version-0.2.2-brightgreen.svg' />
  <img title="portainer" src='https://img.shields.io/badge/java-1.8.*-yellow.svg' />
  <img title="portainer" src='https://img.shields.io/badge/license-MIT-red.svg' />
</p>


`woodpecker-requests`是基于 [requests](https://github.com/hsiafan/requests)
为woodpecker框架定制开发的httpclient库,目的是编写插件时能拥有像python requests一样的便利。特点为可以全局设置代理、全局设置UA等

---

build

```shell
mvn clean package -DskipTests
```

maven install

```shell
mvn install:install-file -Dfile=./target/woodpecker-requests-0.2.2.jar -DgroupId=me.gv7.woodpecker -DartifactId=woodpecker-requests -Dversion=0.2.2 -Dpackaging=jar
```
