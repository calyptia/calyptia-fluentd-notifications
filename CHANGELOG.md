# Calyptia Fluentd 1 changelog

## Release v1.4.0 - 2022/06/30

### News

* Upgrade Fluentd to v1.15.0
  * This version of Fluentd provides support for YAML configuration as well.
* Use the vanilla fluent-plugin-splunk-hec v1.12.13 which resloves Ruby 3 compatibility issues

### Core component

* Ubuntu Jammy / CentOS Stream 9
  * ruby 3.1.2
* Other platforms
  * ruby 3.0.4
* jemalloc 5.2.1
* fluentd v1.15.0 (update)

### Core gems

* bundler v2.3.11
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.3 (update)
* msgpack v1.5.2 (update)
* oj v3.13.14 (update)
* tzinfo v2.0.4
* tzinfo-data v1.2022.1
* async-http v0.56.6 (update)
* serverengine v2.3.0 (update)

### Bundled plugins and gems

* elasticsearch v8.3.0 (update)
* fluent-plugin-elasticsearch v5.2.3 (update)
* ruby-kafka v1.5.0 (update)
* fluent-plugin-kafka v0.17.5
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.3 (update)
* aws-sdk-core v3.131.2 (update)
* aws-sdk-s3 v1.114.0 (update)
* fluent-plugin-s3 v1.7.0 (update)
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.2.0 (update)
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.2
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v1.2.13 (update)
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2
* opensearch-ruby v2.0.0
* fluent-plugin-opensearch v1.0.7 (update)
* fluent-plugin-influxdb-v2 v1.9.0
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.7.1 - 2022/05/27

### News

* Bundle fluent-plugin-influxdb-v2
* Made to be compatible for fluent-bit metrics payload to update cmetrics to v0.3.0

### Core component

* Ubuntu Jammy / CentOS Stream 9
  * ruby 3.1.2
* Other platforms
  * ruby 3.0.4
* jemalloc 5.2.1
* fluentd v1.14.6

### Core gems

* bundler v2.3.11
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.2
* msgpack v1.5.1
* oj v3.13.11
* tzinfo v2.0.4
* tzinfo-data v1.2022.1
* async-http v0.56.5
* serverengine v2.2.5

### Bundled plugins and gems

* elasticsearch v8.1.2
* fluent-plugin-elasticsearch v5.2.2
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.5
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.130.1
* aws-sdk-s3 v1.113.0
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.2
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2
* opensearch-ruby v1.0.0
* fluent-plugin-opensearch v1.0.5 (update)
* fluent-plugin-influxdb-v2 v1.9.0 (new)
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.7 - 2022/04/28

### News

* Update Fluentd to v1.14.6
* Support CentOS Stream 9 and Ubuntu 22.04
* Update elasticsearch client gem to v8 series
* RPM: Remove .build-id directories

### Core component

* Ubuntu Jammy / CentOS Stream 9
  * ruby 3.1.2 (new)
* Other platforms
  * ruby 3.0.4 (update)
* jemalloc 5.2.1
* fluentd v1.14.6 (update)

### Core gems

* bundler v2.3.11 (update)
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.2 (update)
* msgpack v1.5.1 (update)
* oj v3.13.11
* tzinfo v2.0.4
* tzinfo-data v1.2022.1
* async-http v0.56.5
* serverengine v2.2.5

### Bundled plugins and gems

* elasticsearch v8.1.2 (update)
* fluent-plugin-elasticsearch v5.2.2 (update)
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.5
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.130.1
* aws-sdk-s3 v1.113.0
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.2
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2
* opensearch-ruby v1.0.0
* fluent-plugin-opensearch v1.0.4 (update)
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.6 - 2022/03/31

### News

* The end of March 2022 version of Calyptia-Fluentd

### Core component

* ruby 3.0.3
* jemalloc 5.2.1
* fluentd v1.14.5

### Core gems

* bundler v2.2.30
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.5
* oj v3.13.11
* tzinfo v2.0.4
* tzinfo-data v1.2022.1 (update)
* async-http v0.56.5
* serverengine v2.2.5

### Bundled plugins and gems

* elasticsearch v7.17.1 (update)
* fluent-plugin-elasticsearch v5.2.1 (update)
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.5 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.130.0
* aws-sdk-s3 v1.113.0
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2
* opensearch-ruby v1.0.0
* fluent-plugin-opensearch v1.0.2
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.5 - 2022/02/28

### News

* Update Fluentd version to v1.14.5
* Including fixes for fluent-plugin-opensearch
* Update to Elasticsearch 8 compatible fluent-plugin-elasticsearch

### Core component

* ruby 3.0.3
* jemalloc 5.2.1
* fluentd v1.14.5

### Core gems

* bundler v2.2.30
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.5 (update)
* oj v3.13.11
* tzinfo v2.0.4
* tzinfo-data v1.2021.5
* async-http v0.56.5
* serverengine v2.2.5 (update)

### Bundled plugins and gems

* elasticsearch v7.16.1
* fluent-plugin-elasticsearch v5.2.0 (update)
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.4 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.127.0 (update)
* aws-sdk-s3 v1.113.0 (update)
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2
* opensearch-ruby v1.0.0
* fluent-plugin-opensearch v1.0.2 (update)
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.4 - 2022/01/28

### News

* Bundle fluent-plugin-opensearch v1.0.1
  * Now, we support Fluentd event sending into OpenSearch.
* Migrate to use Rocky Linux image to build RPMs for RHEL 8

### Core component

* ruby 3.0.3
* jemalloc 5.2.1
* fluentd v1.14.4

### Core gems

* bundler v2.2.30
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.13.11
* tzinfo v2.0.4
* tzinfo-data v1.2021.5
* async-http v0.56.5
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.16.1
* fluent-plugin-elasticsearch v5.1.4
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.3
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.125.2
* aws-sdk-s3 v1.111.1
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0
* fluent-plugin-in-http-splunk-hec v0.1.0.rc2 (update)
* opensearch-ruby v1.0.0 (new)
* fluent-plugin-opensearch v1.0.1 (new)
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.3 - 2022/01/11

### News

* Update Ruby to 3.0.3
* Update Fluentd to v1.14.4
* Bundle fluent-plugin-in-http-splunk-hec v0.1.0.rc1

### Core component

* ruby 3.0.3 (udpate)
* jemalloc 5.2.1
* fluentd v1.14.4 (update)

### Core gems

* bundler v2.2.30
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.13.11 (update)
* tzinfo v2.0.4
* tzinfo-data v1.2021.5
* async-http v0.56.5
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.16.1 (update)
* fluent-plugin-elasticsearch v5.1.4
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.3
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.125.2 (update)
* aws-sdk-s3 v1.111.1 (udpate)
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v1.2.9 with Ruby 3 patch (update)
* fluent-plugin-cmetrics v0.1.0 (update)
* fluent-plugin-in-http-splunk-hec v0.1.0.rc1 (new)
* rdkafka v0.11.1

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.4 (update)
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.2 - 2021/11/29

### News

* Update Fluentd to v1.14.3 including in_tail watcher fix.
* Update win32-service gem to handle fluent-ctl commmands entirely on Windows.

### Core component

* ruby 3.0.2
* jemalloc 5.2.1
* fluentd v1.14.3

### Core gems

* bundler v2.2.30
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.13.9
* tzinfo v2.0.4
* tzinfo-data v1.2021.5
* async-http v0.56.5
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.15.0
* fluent-plugin-elasticsearch v5.1.4 (update)
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.3 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.123.0 (update)
* aws-sdk-s3 v1.107.0 (update)
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v0
* fluent-plugin-cmetrics v0.1.0.rc8
* rdkafka v0.11.1 (update)

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.3
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.1 - 2021/11/01

### News

* Update using Fluentd to v1.14.2 vanilla
* Update Elasticsearch related gems and plugin
  * Note that this version does not support OpenSearch.

### Core component

* ruby 3.0.2
* jemalloc 5.2.1
* fluentd v1.14.2 vanilla source (5126eba90ab4deb77e9deca691dfd68f835bd456)

### Core gems

* bundler v2.2.30 (update)
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.13.9 (update)
* tzinfo v2.0.4
* tzinfo-data v1.2021.5 (update)
* async-http v0.56.5
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.15.0 (update)
* fluent-plugin-elasticsearch v5.1.1 (update)
* ruby-kafka v1.4.0
* fluent-plugin-kafka v0.17.2 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.121.5 (update)
* aws-sdk-s3 v1.104.0 (update)
* fluent-plugin-s3 v1.6.1
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2
* fluent-plugin-webhdfs v1.5.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14
* fluent-plugin-metrics-cmetrics v0.1.1
* fluent-plugin-calyptia-monitoring v0.1.3
* fluent-plugin-splunk-hec v1.2.7 with patched
* fluent-plugin-cmetrics v0.1.0.rc8 (update)
* rdkafka v0.10.0

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.3
* fluent-plugin-windows-eventlog v0.8.1

## Release v1.3.0 - 2021/09/29

### News

* Bundle fluent-plugin-cmetrics plugin for extracting/parsing cmetrics msgpack payload
* Support in\_tail file metrics on Fluentd
* Bundle fluent-plugin-splunk-hec patched version for Ruby 3

### Core component

* ruby 3.0.2
* jemalloc 5.2.1
* fluentd v1.14.1 vanilla source (6a3b2216c13b55861c8679a0c2e02436f426774f)

### Core gems

* bundler v2.2.24
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.13.8 (update)
* tzinfo v2.0.4
* tzinfo-data v1.2021.2 (update)
* async-http v0.56.5 (update)
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.13.3
* fluent-plugin-elasticsearch v5.1.0 (update)
* ruby-kafka v1.4.0 (update)
* fluent-plugin-kafka v0.17.1 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.121.1 (update)
* aws-sdk-s3 v1.103.0 (update)
* fluent-plugin-s3 v1.6.1 (update)
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.10.2 (update)
* fluent-plugin-webhdfs v1.5.0 (update)
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.14 (update)
* fluent-plugin-metrics-cmetrics v0.1.1 (update)
* fluent-plugin-calyptia-monitoring v0.1.2 (update)
* fluent-plugin-splunk-hec v1.2.7 with patched (new)
* fluent-plugin-cmetrics v0.1.0.rc5 (new)
* rdkafka v0.10.0 (update)

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.3 (update)
* fluent-plugin-windows-eventlog v0.8.1 (update)

## Release v1.2.1 - 2021/08/13

### News

This is point release for macOS and Windows to bundle Calyptia plugin configuration generator.

### Core component

* ruby 3.0.2
* jemalloc 5.2.1
* fluentd 1.13.3 with metrics plugin extension (b28f7d70dac657cb390aabc56dcfee8857975b4b)

### Core gems

* bundler v2.2.24
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.11.5
* tzinfo v2.0.4
* tzinfo-data v1.2021.1
* async-http v0.56.3
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.13.3
* fluent-plugin-elasticsearch v5.0.5
* ruby-kafka v1.3.0
* fluent-plugin-kafka v0.16.3
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.2
* aws-sdk-core v3.117.0
* aws-sdk-s3 v1.96.1
* fluent-plugin-s3 v1.6.0
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.9.0
* fluent-plugin-webhdfs v1.4.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.13
* fluent-plugin-metrics-cmetrics v0.1.0.rc3
* fluent-plugin-calyptia-monitoring v0.1.0.rc8 (update)
* rdkafka v0.9.0

On Linux

* systemd-journal v1.4.2
* fluent-plugin-systemd v1.0.5
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.2
* fluent-plugin-windows-eventlog v0.8.0

## Release v1.2.0 - 2021/07/21

### News

* Support metrics plugin mechianism on Fluentd
* Bundle cmetrics extension and its dependencies for Fluentd
* Bundle Calyptia monitoring plugin

### Core component

* ruby 3.0.2
* jemalloc 5.2.1
* fluentd 1.13.3 with metrics plugin extension

### Core gems

* bundler v2.2.24 (update)
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.11.5
* tzinfo v2.0.4
* tzinfo-data v1.2021.1
* async-http v0.56.3
* serverengine v2.2.4

### Bundled plugins and gems

* elasticsearch v7.13.3 (update)
* fluent-plugin-elasticsearch v5.0.5 (update)
* ruby-kafka v1.3.0
* fluent-plugin-kafka v0.16.3
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.1
* aws-sdk-core v3.117.0
* aws-sdk-s3 v1.96.1
* fluent-plugin-s3 v1.6.0
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.9.0
* fluent-plugin-webhdfs v1.4.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.13
* fluent-plugin-metrics-cmetrics v0.1.0.rc3 (new)
* fluent-plugin-calyptia-monitoring v0.1.0.rc6 (new)
* rdkafka v0.9.0 (update)

On Linux

* systemd-journal v1.4.2 (update)
* fluent-plugin-systemd v1.0.5 (update)
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3
* fluent-plugin-parser-winevt_xml v0.2.2
* fluent-plugin-windows-eventlog v0.8.0

## Release v1.1.0 - 2021/06/30

### News

* Update plugins for better Ruby 3 support.
* Support plugin metrics on Input/Filter. And more plugin metrics support on Output.
* Start to bundle fluent-plugin-detect-exceptions

### Core component

* ruby 3.0.1
* jemalloc 5.2.1
* fluentd 1.13.1 (update)

### Core gems

* bundler v2.2.20 (udpate)
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.11.5
* tzinfo v2.0.4
* tzinfo-data v1.2021.1
* async-http v0.56.3 (update)
* serverengine v2.2.4 (update)

### Bundled plugins and gems

* elasticsearch v7.13.1 (update)
* fluent-plugin-elasticsearch v5.0.4 (update)
* ruby-kafka v1.3.0
* fluent-plugin-kafka v0.16.3 (update)
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.1
* aws-sdk-core v3.114.3 (update)
* aws-sdk-s3 v1.96.1 (update)
* fluent-plugin-s3 v1.6.0
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.9.0
* fluent-plugin-webhdfs v1.4.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* fluent-plugin-detect-exceptions v0.0.13 (new)
* rdkafka v0.8.1

On Linux

* systemd-journal v1.3.3
* fluent-plugin-systemd v1.0.2
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.3 (udpate)
* fluent-plugin-parser-winevt_xml v0.2.2
* fluent-plugin-windows-eventlog v0.8.0

## Release v1.0.0 - 2021/05/04

### News

The initial public release.

### Core component

* ruby 3.0.1
* jemalloc 5.2.1
* fluentd 1.12.3

### Core gems

* bundler v2.2.16
* cool.io v1.7.1
* sigdump v0.2.4
* yajl-ruby v1.4.1
* msgpack v1.4.2
* oj v3.11.5
* tzinfo v2.0.4
* tzinfo-data v1.2021.1
* async-http v0.54.1
* serverengine v0

### Bundled plugins and gems

* elasticsearch v7.12.0
* fluent-plugin-elasticsearch v5.0.3
* ruby-kafka v1.3.0
* fluent-plugin-kafka v0.16.1
* prometheus-client v2.1.0
* fluent-plugin-prometheus v2.0.1
* aws-sdk-core v3.114.0
* aws-sdk-s3 v1.93.1
* fluent-plugin-s3 v1.6.0
* fluent-diagtool v1.0.1
* td-client v1.0.8
* fluent-plugin-td v1.1.0
* webhdfs v0.9.0
* fluent-plugin-webhdfs v1.4.0
* fluent-plugin-record-modifier v2.1.0
* fluent-plugin-rewrite-tag-filter v2.4.0
* fluent-plugin-sd-dns v0.1.0
* fluent-plugin-flowcounter-simple v0.1.0
* rdkafka v0.8.1

On Linux

* systemd-journal v1.3.3
* fluent-plugin-systemd v1.0.2
* fluent-plugin-utmpx v0.5.0

On Windows

* winevt_c v0.9.2
* fluent-plugin-parser-winevt_xml v0.2.2
* fluent-plugin-windows-eventlog v0.8.0
