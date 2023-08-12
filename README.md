# Prometheus-Init

## What is different HTTP status code and explain meaning of each of them ?

HTTP status codes are three-digit numbers that the server uses to communicate the outcome of a client's request to the client's browser. They provide information about the status of the requested resource or the outcome of the request itself. Here's an overview of some of the common HTTP status codes and their meanings:
  * 1xx (Informational Responses)
  * 2xx (Successful Responses)
  * 3xx (Redirection Responses)
  * 4xx (Client Error Responses)
  * 5xx (Server Error Responses)

## What database is used by Prometheus?
Prometheus uses a custom-built time-series database called the "Prometheus Time Series Database" (TSDB). This database is specifically designed to store and manage time-series data, which is a fundamental aspect of monitoring and observability.

TSDB is optimized for handling large amounts of time-series data collected from various sources, such as metrics from applications, servers, and other infrastructure components. It efficiently stores and indexes data, making it easy to query and retrieve historical and real-time metrics.

## What is the difference between different metrics types ( counter , gauge , histogram)?
In the context of monitoring and metrics collection, different metric types serve distinct purposes and provide varying insights into the behavior and performance of systems and applications. The three main types of metrics you mentioned are counters, gauges, and histograms. Here's an explanation of each:

* Counter:

A counter is a monotonically increasing value that represents a cumulative count of some event or occurrence over time.
Counters are typically used to track the number of times a specific event has happened, such as requests received, jobs completed, or errors encountered.
They are reset to zero when the process or application restarts.
Example: Tracking the number of HTTP requests made to a web server.

* Gauge:

A gauge is a metric that represents a single numerical value that can go up and down over time.
Gauges are used to measure the current state of something, such as a temperature reading, memory usage, or the number of active connections.
They are not reset or modified automatically; instead, their value is explicitly set by the application or monitoring system.
Example: Monitoring the current CPU usage percentage of a server.

* Histogram:

A histogram is used to measure the distribution of values within a given range and calculate statistics like percentiles.
Histograms divide a range of values into "buckets" and track the frequency of observations falling into each bucket.
They are useful for analyzing data distribution and understanding the spread and variability of values.
Histograms can provide insights into latency, request durations, and other metrics where you want to understand the distribution of values.
Example: Measuring the response times of API requests and calculating percentiles (e.g., 95th percentile response time).

## Install Prometheus on your local host

![Pro1 install](https://github.com/mohabalinassar/Prometheus-Init/assets/29493773/a25b4136-f921-4d7f-89c0-53d27dc9d22b)
![pro 2 targets ](https://github.com/mohabalinassar/Prometheus-Init/assets/29493773/b9a36816-bbe4-45b3-855f-c1e167a817be)


