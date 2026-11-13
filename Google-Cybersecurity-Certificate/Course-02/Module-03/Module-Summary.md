# Module 3 Summary: Logs and SIEM Tools

## 1. Why logs matter in cybersecurity

A **log** is a record of events that occur within a computer system, application, or network. Logs help organizations understand what happened, when it happened, and which system or account was involved.

Security professionals use logs to:
- Review account activity and access attempts
- Investigate unusual system or network behavior
- Identify possible security incidents
- Build a timeline of events during an investigation
- Support monitoring, troubleshooting, and compliance activities

A single log entry may provide only limited information. Reviewing events from multiple sources can reveal a more complete picture.

## 2. Common types of logs

### Firewall logs
Firewall logs record network traffic that a firewall allows or blocks. They can help identify unusual connection attempts, blocked traffic, and communication with unexpected addresses.

### Network logs
Network logs record activity and events across network devices and services. Depending on the source, they can help security teams understand connections, traffic patterns, and communication between systems.

### Server logs
Server logs record events on servers, such as requests, errors, service activity, and authentication-related events. They can help identify unusual access patterns or unexpected server behavior.

The exact information recorded depends on the device, operating system, application, and logging configuration.

## 3. SIEM: Security Information and Event Management

A **SIEM** solution collects and analyzes log data from different sources across an organization's technology environment.

A SIEM can help security teams:
- Bring log data together in one place
- Search and analyze events
- Correlate related activity from multiple systems
- Identify suspicious patterns and generate alerts
- Investigate possible security incidents
- Support reporting and compliance requirements

SIEM does not automatically mean every alert is a confirmed attack. Analysts need to review the context, validate the activity, and decide whether further investigation is required.

## 4. SIEM dashboards

A SIEM dashboard presents security information in a visual format. It may display event counts, alert trends, event severity, affected systems, login activity, or other monitoring information.

Dashboards help analysts quickly understand what is happening in an environment and decide where attention is needed. The value of a dashboard depends on useful data, appropriate detection rules, and correct interpretation.

## 5. SIEM platforms introduced in the module

### Splunk Cloud
Splunk Cloud is a cloud-hosted platform used to collect, search, analyze, and monitor machine-generated data, including logs.

### Splunk Enterprise
Splunk Enterprise is a platform organizations can deploy and manage in their own environment to collect, search, analyze, and monitor machine data.

### Chronicle
Chronicle is a cloud-native security analytics tool designed to retain, search, and analyze security data.

These products provide capabilities for working with security data, but their deployment models and features can differ.

## 6. Metrics

**Metrics** are measurable values used to evaluate how a system or application is performing. Examples include:
- **Response time:** How long a system takes to respond.
- **Availability:** The amount of time a service is accessible and working.
- **Failure rate:** How often a system or operation fails.

Metrics can help teams identify performance problems and understand whether services are operating as expected. They are not the same as individual log records, although logs and metrics can complement each other during troubleshooting and investigation.

## 7. Related incident response concepts

The module glossary also introduced several concepts connected to security operations:

- **Incident response:** The organized effort to identify, contain, investigate, and recover from a security incident.
- **Playbook:** Documented instructions that guide an operational or security response.
- **SOAR:** Security Orchestration, Automation, and Response. SOAR platforms connect tools and workflows to help automate parts of security operations.

A playbook describes what should happen; a SOAR platform may automate selected steps in that process. Human review and approval may still be important, especially for actions that could affect business operations.

## Key takeaway

Logs provide records of activity. SIEM platforms collect and analyze those records to help security teams monitor systems, investigate suspicious behavior, and identify potential incidents. Dashboards make important information easier to review, while metrics provide measurements of system performance.

This knowledge supports the broader security process: monitoring activity, recognizing possible threats, investigating evidence, and responding appropriately.