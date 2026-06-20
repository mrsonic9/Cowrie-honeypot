# Cowrie Honeypot & ELK Stack Analysis

## Project Overview
This project focuses on the deployment of a **Cowrie honeypot** to capture and analyze SSH brute-force attacks. The logs are collected and processed using the **ELK Stack (Elasticsearch, Filebeat, Kibana)**, enabling real-time monitoring and visualization of security events.

## Key Features
* **Honeypot Deployment:** Set up and configured Cowrie in a home lab environment to simulate a vulnerable SSH server.
* **Automated Log Ingestion:** Utilized Filebeat to harvest, enrich, and forward honeypot logs into an Elasticsearch Data Stream.
* **Data Visualization:** Developed a custom Kibana dashboard to visualize attacker activity, including top-attempted passwords and connection attempts.
* **Defensive Security:** Implemented SIEM principles to monitor, audit, and analyze network-based attacks.

## Technologies Used
* **Honeypot:** Cowrie
* **Logging/Ingestion:** Filebeat
* **Data Storage/Analytics:** Elasticsearch
* **Visualization:** Kibana
* **Environment:** Linux (Ubuntu/Debian)

## Architecture
1. **Cowrie** captures brute-force SSH attempts and logs them in JSON format.
2. **Filebeat** monitors the Cowrie logs and pushes them into an Elasticsearch Data Stream.
3. **Elasticsearch** indexes the logs for fast retrieval and analysis.
4. **Kibana** provides the interface for visualizing the attack data through custom dashboards.

## Project Screenshots
<img width="1840" height="952" alt="image" src="https://github.com/user-attachments/assets/a2be8128-b1ad-46d7-879d-50b36e9c0d95" />
