---
title: Apache HBase
permalink: /hbase
alternate_urls:
-   /apache_hbase
-   /apache-hbase
releasePolicyLink: https://hbase.apache.org/downloads.html
category: server-app
changelogTemplate: https://downloads.apache.org/hbase/{{"__LATEST__"}}/CHANGES.md
activeSupportColumn: false
eolColumn: Service Status
releaseDateColumn: true
releaseColumn: true
sortReleasesBy: 'releaseCycle'
iconSlug: NA
auto:
-   git: https://github.com/apache/hbase.git
    regex: '^rel\/(?<major>\d+)\.(?<minor>\d+)\.(?<patch>\d+)(\.(?<tiny>\d+))?$'
    template: "{{major}}.{{minor}}.{{patch}}{%if tiny%}.{{tiny}}{%endif%}"
releases:
# Uncomment when the first v3 stable release is out
#-   releaseCycle: "3.0"
#    eol: false
#    releaseDate: 2021-07-20
#    latest: "3.0.0-alpha-3"
#    latestReleaseDate: 2022-06-27
-   releaseCycle: "2.4"
    eol: false
    releaseDate: 2020-12-15
    latest: "2.4.13"
    latestReleaseDate: 2022-07-01
-   releaseCycle: "2.3"
    eol: 2022-03-17
    releaseDate: 2020-07-13
    latest: "2.3.7"
    latestReleaseDate: 2021-10-19
-   releaseCycle: "2.2"
    eol: 2021-01-07
    releaseDate: 2019-07-25
    latest: "2.2.7"
    latestReleaseDate: 2021-04-19
-   releaseCycle: "1.7"
    eol: false
    releaseDate: 2021-06-12
    latest: "1.7.2"
    latestReleaseDate: 2022-08-09

---

> [Apache HBase](https://hbase.apache.org/) is an open-source non-relational distributed database modeled after Google's Bigtable and written in Java. It's useful for random, real-time read/write access to Big Data. The project's goal is the hosting of very large tables -- billions of rows X millions of columns -- atop clusters of commodity hardware.

You must pick a supported release of Hadoop as per the [compatibility matrix](https://hbase.apache.org/book.html#hadoop)

No releases are scheduled in advance.