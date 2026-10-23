# 💬 Mission 07 Reflection & Critical Analysis

> **Author:** Christopher Sean O. Gutierrez  
> **Role:** Cloud Operations / SRE Engineer — CloudNova Technologies  
> **Course:** CCM101 - Cloud Computing  

---

It is vital to check the host server's underlying hardware resources even if individual containers are running perfectly because containers share
the host operating system kernel and physical resource pool. If the host machine runs out of available RAM or disk storage due to background processes,
the kernel may trigger out-of-memory (OOM) killer routines or lock up file writes, causing container crashes regardless of internal container health.

If a user complains that they cannot log into a web application, the `docker logs` command helps solve the problem by providing an immediate, itemized history
of HTTP request codes, client IP addresses, and backend server exceptions. By analyzing these logs, an engineer can instantly identify whether users are
encountering client-side authorization failures, server-side database connection errors, or broken URL routing.

The primary difference between monitoring logs and monitoring metrics lies in the nature of the data collected. Log monitoring reviews discrete, historical
event records (such as text-based HTTP status codes and error messages), whereas metric monitoring tracks continuous numerical time-series data
(such as live CPU percentage, memory consumption rates, and network I/O throughput).

Large enterprise companies monitor thousands of containers simultaneously by deploying centralized observability stacks like Prometheus for automated metric
scraping and Grafana for visual dashboards, alongside log aggregation tools like ELK (Elasticsearch, Logstash, Kibana) to collect telemetry data across massive
distributed cloud clusters.

Finally, my ability to troubleshoot Linux environments has improved immensely. Transitioning from basic command execution to actively auditing system performance,
tracking live container stats, and parsing application error logs has transformed my technical workflow into a structured, evidence-based engineering practice.
