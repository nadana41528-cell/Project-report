# Project-report
Acknowledgements
I would like to express my sincere gratitude to Tata Consultancy Services (TCS) and my institute for providing the opportunity to work on this industry-oriented project. I also thank my mentors and faculty members for their guidance and support throughout the project.
________________________________________
Objective and Scope
The objective of this project is to develop Python-based security automation tools that assist Security Operations Centers (SOCs) in handling large volumes of security alerts efficiently.
The scope includes log parsing, anomaly detection, threat intelligence enrichment, automated response actions, and security reporting.
________________________________________
Problem Statement
Modern SOC teams face alert fatigue due to the massive amount of security logs generated daily. Manual analysis leads to delayed responses and increased risk. There is a need for automated tools that can parse logs, detect threats, enrich alerts, and assist in faster incident response.
________________________________________
Existing Approaches
Traditional SOC operations rely heavily on manual log analysis and rule-based SIEM alerts. These approaches are time-consuming, error-prone, and not scalable. Lack of automation leads to delayed incident containment and inefficient threat prioritization.
________________________________________
Approach / Methodology – Tools and Technologies Used
The project follows a SOAR (Security Orchestration, Automation, and Response) methodology using Python.
Tools and technologies used:
•	Python 3.x
•	Regular Expressions (re)
•	JSON data handling
•	Simulated Threat Intelligence
•	Google Colab for development and execution
________________________________________
Workflow
1.	Collect and parse security logs
2.	Convert raw logs into structured data
3.	Apply detection rules to identify suspicious activity
4.	Enrich alerts using Threat Intelligence
5.	Trigger automated response actions
6.	Generate security reports for analyst review
________________________________________
Assumptions
•	Log data is simulated for academic purposes
•	Threat Intelligence is simulated due to API limitations
•	Automated response actions are safe prototypes
•	The system is designed for learning and demonstration
________________________________________
Implementation
Data Collection
Simulated Nginx web server logs were used as input data.
Processing Steps
•	Logs are parsed using regular expressions
•	Failed login attempts are counted per IP
•	Threshold-based detection identifies brute-force attacks
Diagrams / Tables
Component	Description
Log Parser	Extracts IP and status code
Detection Engine	Identifies brute-force attacks
