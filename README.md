# SIEM-elk-suricata
home SOC lab using an ELK stack and Suricata for network monitoring and alerting

##  Goal
Build a home SOC lab to monitor network traffic and detect simulated attacks using ELK Stack and Suricata.

##  Tools Used
- Parrot OS (monitoring VM)
- Kali Linux (attacker VM)
- Metasploitable 2 (target VM)
- Suricata IDS
- ELK Stack (Elasticsearch, Logstash, Kibana)

##  Steps (so far)
1. Installed Suricata on monitoring VM.
2. Configured Logstash to ingest Suricata alerts.
3. Building Kibana dashboards to visualize alerts.
4. Simulated attacks from Kali VM (tests in progress).

##  Outcome
- Alerts captured for certain simulated attacks.

##  Learning
- Gained hands-on experience with SIEM tools.
- Learned basic workflow: attack → detect → log → visualize.
