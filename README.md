# Prometheus_preparation

## Interesting links 
- https://github.com/Al-HusseinHameedJasim/prometheus-certified-associate
- https://github.com/prometheus/docs#contributing-changes
- https://github.com/walidshaari/PrometheusCertifiedAssociate

For me this is the most interesting web-page with several links to the different parts of the exam.
- https://ravikirans.com/prometheus-certified-associate-pca-study-guide/

### Observability Concepts 18%

- Metrics

    - [Metric types](https://prometheus.io/docs/concepts/metric_types/)

    - [An introduction to Prometheus metrics and performance monitoring](https://www.redhat.com/sysadmin/introduction-prometheus-metrics-and-performance-monitoring)

    - [A Deep Dive Into the Four Types of Prometheus Metrics](https://www.timescale.com/blog/four-types-prometheus-metrics-to-collect/)

- Understand logs and events

    - [Monitoring and Debugging Prometheus](https://training.promlabs.com/training/monitoring-and-debugging-prometheus/logs/standard-error-logs)

    - [Are detailed logs available in Prometheus?](https://stackoverflow.com/questions/60014600/are-detailed-logs-availble-in-prometheus)

- Tracing and Spans

    - [A beginner’s guide to distributed tracing and how it can increase an application’s performance](https://grafana.com/blog/2021/01/25/a-beginners-guide-to-distributed-tracing-and-how-it-can-increase-an-applications-performance/)

    - [Using Prometheus Exemplars to jump from metrics to traces in Grafana](https://vbehar.medium.com/using-prometheus-exemplars-to-jump-from-metrics-to-traces-in-grafana-249e721d4192)

    - [Generate metrics from spans](https://grafana.com/docs/tempo/latest/metrics-generator/span_metrics/)

- Push vs Pull

    - [Pull or Push: How to Select Monitoring Systems?](https://www.alibabacloud.com/blog/pull-or-push-how-to-select-monitoring-systems_599007#:~:text=The%20Pull%20method%20is%20to,of%20each%20client%20are%20different.)

    - [Prometheus Monitoring: The Pull Approach](https://network-insight.net/2022/06/29/prometheus-monitoring-the-pull-approach/#:~:text=Prometheus%20uses%20a%20pull%20approach,you%20use%20the%20federate%20option.)

    - [Push Vs. Pull in Monitoring Systems](https://giedrius.blog/2019/05/11/push-vs-pull-in-monitoring-systems/)

    - [Prometheus and the Debate Over ‘Push’ Versus ‘Pull’ Monitoring](https://thenewstack.io/exploring-prometheus-use-cases-brian-brazil/)

- Service Discovery

    - [Enable Prometheus Native Service Discovery](https://docs.sysdig.com/en/docs/sysdig-monitor/integrations/working-with-integrations/custom-integrations/collect-prometheus-metrics/enable-prometheus-native-service-discovery/#:~:text=Prometheus%20service%20discovery%20is%20a,you%20do%20for%20native%20Prometheus.)

    - [Prometheus service discovery](https://docs.victoriametrics.com/sd_configs.html)

- Basics of SLOs, SLAs, and SLIs

    - [SLA vs. SLO vs. SLI Differences](https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli#:~:text=An%20SLI%20(service%20level%20indicator,actual%20measurement%20of%20your%20uptime.))

    - [Implementing SLOs using Prometheus](https://docs.bitnami.com/tutorials/implementing-slos-using-prometheus/)

    - [Implementing SLI/SLO-based Continuous Delivery Quality Gates using Prometheus](https://developer.harness.io/tutorials/service-reliability/slo-prometheus/)

    - [Manage SLOs using Prometheus metrics](https://mattermost.com/blog/sloth-for-slo-monitoring-and-alerting-with-prometheus/
    )

    - [How We Use Sloth to Do SLO Monitoring and Alerting with Prometheus ](https://mattermost.com/blog/sloth-for-slo-monitoring-and-alerting-with-prometheus/)

### Prometheus fundamentals 20%

- System Architecture

    - [Prometheus Architecture Explained](https://scoutapm.com/blog/prometheus-architecture)

    - [Introduction to Prometheus](https://training.promlabs.com/training/introduction-to-prometheus/prometheus-an-overview/system-architecture)

- Configuration and Scraping

    - [Configuration](https://prometheus.io/docs/prometheus/latest/configuration/configuration/)

    - [Scraping application metrics with Prometheus](https://codeblog.dotsandbrackets.com/scraping-application-metrics-prometheus/)

- Understanding Prometheus Limitations

    - [5 Challenges with Prometheus Monitoring](https://chronosphere.io/platform/outgrowing-prometheus-monitoring/)

    - [Challenges using Prometheus at scale](https://sysdig.com/blog/challenges-scale-prometheus/)

- Data Model and Labels

    - [Data model | Prometheus](https://prometheus.io/docs/concepts/data_model/)

    - [Introduction to Prometheus](https://training.promlabs.com/training/introduction-to-prometheus/prometheus-an-overview/time-series-data-model)

    - [Trying to understand the Prometheus data model in a more simplified way](https://stackoverflow.com/questions/73686756/trying-to-understand-prometheus-data-model-in-a-more-simplified-way-and-how-does)

    - [Metric and label naming](https://prometheus.io/docs/practices/naming/#labels)

    - [Prometheus Cheat Sheet – Basics (Metrics, Labels, Time Series, Scraping)](https://iximiuz.com/en/posts/prometheus-metrics-labels-time-series/)

    - [Labels – Prometheus](https://www.oreilly.com/library/view/prometheus-up/9781492034131/ch05.html)

- Exposition Format

    - [Exposition formats](https://github.com/Showmax/prometheus-docs/blob/master/content/docs/instrumenting/exposition_formats.md)

    - [Exposition – Prometheus](https://www.oreilly.com/library/view/prometheus-up/9781492034131/ch04.html)
### PromQL 28%

Selecting Data

Selecting Data in PromQL

Time series selectors

Rates and Derivatives

How does the Prometheus rate() function works?

Query functions | rate

The Good, The Bad, And Alerting on Derivatives

Aggregating over time

Prometheus – Moving Average, Max, Min, etc (Aggregation Over Time)

Query functions | Aggregating over time

Aggregating over dimensions

Aggregation operators

Prometheus Querying – Breaking Down PromQL

Binary operators

Binary operators

PromQL Operators

Histograms

Histograms and summaries

How does a Prometheus Histogram work?

Timestamp Metrics

Prometheus metrics with timestamp

Adding timestamps to Gauge Metric

Filter metrics based on a timestamp

### Instrumentation and Exporters 16%

Client Libraries

Client libraries

Writing client libraries

Prometheus Client Libraries

Instrumentation

Prometheus instrumentation library for Python applications

Instrumentation

Exporters

Exporters and integrations

Writing exporters

Prometheus exporters

Structuring and naming metrics

Metric and label naming

Instrumenting Applications | Naming metrics

### Alerting & Dashboarding 18%

Dashboarding basics

The Best Prometheus Dashboards

Consoles and dashboards

Creating Grafana Dashboards for Prometheus

Grafana Prometheus Dashboard

Configuring Alerting rules

Alerting rules

The Guide To Prometheus Alerting

Understand and Use Alertmanager

Alertmanager

Prometheus Alertmanager

Prometheus Alerting with AlertManager

Alerting basics (when, what, and why)

What to alert on?

The Guide To Prometheus Alerting