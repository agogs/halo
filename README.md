<h1><a href="#" target="_blank">Halo</a></h1>

> Halo may be the best Java blog system.

[![JDK](https://img.shields.io/badge/JDK-1.8-yellow.svg)](#)
[![GitHub release](https://img.shields.io/github/release/ruibaby/halo.svg)](https://github.com/ruibaby/halo/releases)
[![Travis CI](https://img.shields.io/travis/ruibaby/halo.svg)](https://travis-ci.org/ruibaby/halo)

------------------------------

## 目录

- [Introduction](#introduction)
- [Quickstart](#quickstart)
- [Demo](#demo)
- [Download](#download)
- [Docs](#docs)
- [Themes](#themes)
- [License](#license)
- [Todo](#todo)
- [Thanks](#thanks)

## Introduction 简介

**Halo** [ˈheɪloʊ]，meaning aura. Of course, you can also read it as a pinyin.

Light, simple, and powerful, using a blog system developed in Java.

> **Halo Communication Group:** 162747721

## Quickstart

```bash
git clone https://github.com/ruibaby/halo.git
cd halo
mvn clean package -Pprod
java -jar target/dist/halo/halo-xxx.jar
```

> **Note: If you use Idea, Eclipse and other IDEs to run, you need to install the Lombok plug-in.**

Let's start: http://localhost:8090

## Demo 演示

[Interface preview](https://halo-doc.ryanc.cc/preview)

[Ryan0up'S Blog](https://ryanc.cc)

[SNAIL BLOG](https://slogc.cc)

[Song Haozhi Blog](http://songhaozhi.com)

## Download

[Download](https://github.com/ruibaby/halo/releases) the latest archive and extract it. Go to that directory and run `java -jar halo-xxx.jar` to run the standalone application.

> **To deploy to a server, refer to the [Halo deployment tutorial](https://ryanc.cc/archives/halo-run)。**

## Docs

[Halo Document](https://halo-doc.ryanc.cc)

> **Documentation is constantly improving.**

## Themes

In addition to the built-in [Anatole](https://github.com/hi-caicai/farbox-theme-Anatole) and [Material](https://github.com/viosey/hexo-theme-material)，the following themes are not integrated in the project. If necessary, please upload it through the background and download it.

- [Vno](https://github.com/ruibaby/vno-halo) - A theme from Jekyll, author [Wei Wang](https://onevcat.com/)。
- [Hux](https://github.com/ruibaby/hux-halo) - A theme from Jekyll, by [Xuan Huang](https://huangxuan.me/)。

## License

[![license](https://img.shields.io/github/license/ruibaby/halo.svg)](https://github.com/ruibaby/halo/blob/master/LICENSE)

> **Halo uses the GPL-v3.0 protocol for open source. Please try to comply with open source agreements, even in China.**

## Todo

- [ ] Article reading statistics
- [ ] Article top
- [ ] Integration and pat cloud, seven cattle cloud and other cloud services

## Thanks

The birth of Halo cannot be separated from the following items:

- [IntelliJ IDEA](https://www.jetbrains.com/idea/)：Personally Considered the Most Powerful Java IDE, No One
- [Spring Boot](https://github.com/spring-projects/spring-boot)：Spring's Microservices Framework
- [Freemarker](https://freemarker.apache.org/)：Template Engine,
- [H2 Database](https://github.com/h2database/h2database)：Embedded Database, No Installation Required
- [Druid](https://github.com/alibaba/druid)：Connection Pool
- [Spring-data-jpa](https://github.com/spring-projects/spring-data-jpa.git)：Persistence layer framework that does not need to write sql statement
- [Ehcache](http://www.ehcache.org/)：Caching Framework
- [Lombok](https://www.projectlombok.org/)：Make Your Code More Compact
- [Apache Commons](http://commons.apache.org/)：A very handy Java tool library
- [oh-my-email](https://github.com/biezhi/oh-my-email)：may be the smallest Java mail sending library, support for CC, attachments, templates, etc.
- [AdminLTE](https://github.com/almasaeed2010/AdminLTE)：Bootstrap-based background template
- [Bootstrap](https://github.com/twbs/bootstrap.git)：The most widely used front-end ui framework
- [Animate](https://github.com/daneden/animate.css.git)：A very easy-to-use css library
- [Editor.md](https://github.com/pandao/editor.md.git)：Markdown front-end editor, unfortunately abandoned by the author
- [Editor.md](https://github.com/hawtim/editor.md)：Editor.md，Editor.md, the version that hawtim took over
- [Bootstrap-FileInput](https://github.com/kartik-v/bootstrap-fileinput.git)：one of the upload components that individuals think is best to use, none
- [Font-awesome](https://github.com/FortAwesome/Font-Awesome.git)：The most widely used font icon library
- [Jquery](https://github.com/jquery/jquery.git)：The most widely used JavaScript framework
- [Layer](https://github.com/sentsin/layer.git)：Personally think that the most practical and best-looking popup layer assembly, not one
- [Jquery-Toast](https://github.com/kamranahmedse/jquery-toast-plugin)：Message Alert Component
- [Pjax](https://github.com/defunkt/jquery-pjax.git)：pushState + ajax = pjax

