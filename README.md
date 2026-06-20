Project Title: Honeypot Deployment & ELK Stack Log Analysis
Description

This project involves the deployment of a Cowrie honeypot to capture and analyze SSH brute-force attacks. The logs are ingested into an ELK (Elasticsearch, Logstash/Filebeat, Kibana) stack, allowing for real-time visualization and security event monitoring.
Key Features

    Honeypot Setup: Deployed and configured a Cowrie honeypot to simulate a vulnerable SSH server.

    Log Ingestion: Used Filebeat to securely harvest and forward honeypot logs into an Elasticsearch data stream.

    Data Visualization: Built a custom Kibana dashboard to visualize attacker activity, including login attempts and password analysis.

    Security Analysis: Implemented defensive security techniques to monitor and audit network events in a controlled home lab environment.

Technologies Used

    Honeypot: Cowrie

    Logging: Filebeat

    SIEM: Elasticsearch, Kibana (ELK Stack)

    Environment: Linux-based home lab
