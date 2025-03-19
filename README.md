Overview
This project focuses on monitoring and analyzing authentication logs from Windows and SSH servers deployed on Vultr. Using Elastic Agents and Kibana, I built interactive dashboards to visualize login activity, track authentication patterns, and detect potential security threats. Custom alerting rules were configured to notify about suspicious login attempts, brute-force attacks, and unauthorized access.

Key Features

Log Collection & Ingestion: Configured Elastic Agents to collect authentication logs from:
* Windows Event Viewer (RDP & local logins)
* SSH logs (Linux authentication attempts)

✅ Custom Dashboards in Kibana: Built dashboards displaying:
* User IP Address
* Geolocation (Country of Login)
* Username of the Logged-in User
* Count of Authentication Events

✅ Real-time Alerting: Set up custom alerts in Kibana for:
* Multiple failed login attempts (potential brute-force attacks)
* Login attempts from unusual geolocations
* Unauthorized SSH access attempts

✅ Cloud Deployment: Managed authentication log collection on Vultr cloud-hosted servers.
* Technologies Used
* Vultr (Cloud Hosting)
* Elastic Stack (Elasticsearch, Kibana, Elastic Agents)
* Windows Event Viewer & SSH Logs

Example below.

Ref 1: Network Diagram
