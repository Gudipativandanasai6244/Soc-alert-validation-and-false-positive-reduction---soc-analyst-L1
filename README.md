# Soc-alert-validation-and-false-positive-reduction-Lab---soc-analyst-L1
SOC Alert Validation and False Positive Reduction using Splunk SIEM. Investigated security alerts, analyzed event logs, validated false positives, and documented SOC Analyst L1 incident investigation workflow.

# SOC Alert Validation and False Positive Reduction using Splunk,Microsoft Sentinel,Kusto Query Language

## Project Overview

This project demonstrates SOC Alert Validation and False Positive Reduction using Splunk SIEM. The objective is to monitor security events, investigate alerts, analyze event details, and determine whether an alert is a true positive or a false positive. The project simulates the day-to-day responsibilities of a SOC Analyst L1.

---

## Objectives

* Monitor security events using Splunk
* Investigate suspicious alerts
* Analyze timestamps, sources, and event details
* Validate true positives and false positives
* Improve alert accuracy through investigation
* Document SOC investigation workflow

---

## Tools Used

* Splunk Enterprise
* Microsoft sentinel
* kusto query language
* Windows Event Logs
* Windows Operating System
* GitHub

---

## Project Workflow

Log Collection

↓

Log Monitoring

↓

Alert Detection

↓

Event Investigation

↓

Alert Validation

↓

False Positive Reduction

↓

Documentation

---

## Alert Investigation Process

### 1. Timestamp Analysis

Reviewed the timestamp to determine when the activity occurred and identify any unusual activity patterns.

### 2. Source Analysis

Verified the source of the event to identify the system or service that generated the alert.

### 3. Account Analysis

Reviewed the associated user account to determine whether the activity originated from a legitimate user or system account.

### 4. Event Details Analysis

Examined the event message and event details to understand the activity that triggered the alert.

---

## False Positive Validation

During the investigation, event details, timestamps, sources, and account information were analyzed to determine whether the alert indicated malicious activity.

Example:

* Alert Triggered: Security Event Detected
* Investigation Result: Legitimate system activity
* Classification: False Positive

This process helps reduce unnecessary alerts and allows security teams to focus on genuine threats.

---

## Skills Demonstrated

* SIEM Monitoring
* Security Event Analysis
* Alert Validation
* False Positive Reduction
* Incident Investigation
* Log Analysis
* Security Monitoring
* SOC Operations

---

## Screenshots

Add screenshots here:

1. Splunk Dashboard
2. Event Search Results
3. Alert Investigation
4. False Positive Validation

---

## Project Outcome

Successfully monitored security events, investigated alerts, validated false positives, and documented findings using Splunk SIEM. This project demonstrates foundational SOC Analyst L1 skills in security monitoring, alert investigation, and incident analysis.

## Sample Output

### Search Query

index=*

### Result

Total Events Found: 428 Events

The search returned multiple system and process-related events collected by Splunk.

---

### Event Investigation Example

Event Type: Security Monitoring Event

Source: Windows Event Logs

Host: Local Machine

Event Description: Security-related system activity detected

---

### Alert Validation Process

Investigation Steps:

1. Reviewed the event timestamp.
2. Verified the event source.
3. Examined available account information.
4. Analyzed event details.
5. Correlated findings with observed system activity.

---

### Investigation Result

No malicious indicators were identified during the investigation.

The observed activity appeared consistent with legitimate system operations.

Classification: False Positive

---

### Outcome

* Successfully monitored security events using Splunk.
* Investigated alerts and reviewed event details.
* Performed alert validation and false positive analysis.
* Documented the SOC investigation workflow.
* Demonstrated SIEM monitoring and incident investigation skills.

Project Status: Completed Successfully


---

## Author

Vandhana Sai

Aspiring SOC Analyst | Cybersecurity Enthusiast
