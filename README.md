Task 3
1. Installation and Prerequisites
​Requirements: A dedicated machine or VM with two network interface cards (NICs), root privileges, and a network that supports traffic mirroring (SPAN or tap).
​Process: Instructions cover installing dependencies (like libpcap and pcre), compiling Snort from source, and installing the Data Acquisition (DAQ) library.
​### 2. Configuration and Rule Management
​Rules: Snort uses text-based signatures to detect anomalies. The guide details how to download community rules and configure the snort.conf file.
​Customization: It includes an example of a custom rule to detect ICMP (ping) flood attacks.
​Variables: Instructions on setting HOME_NET to define the internal network being protected.
​### 3. Monitoring and Response
​Execution: How to run Snort in daemon mode for continuous background monitoring.
​IPS Integration: Transitioning from passive detection (IDS) to active prevention (IPS) using Barnyard2 for log processing or integrating with iptables for automated IP blocking.
​### 4. Visualization and Maintenance
​Dashboards: Suggestions for visualizing attacks using the ELK Stack (Elasticsearch, Logstash, Kibana), Splunk, or Grafana.
​Updates: Recommendations to use tools like Pulled Pork to keep detection rules current.
​Testing: Encourages ethical testing of the setup using tools.
