---
menu:
  docs:
    parent: policies
title: Continuous monitoring strategy
---

The cloud.gov team conducts ongoing security monitoring and assessment of cloud.gov, based on the continuous monitoring process described in *NIST SP 800-137 Information Security Continuous Monitoring for Federal Information Systems and Organizations*. This is part of ensuring that we meet FedRAMP requirements.

This page documents policies and procedures related to cloud.gov continuous monitoring. It's adapted from the *Continuous Monitoring Strategy Guide* [available from FedRAMP](https://www.fedramp.gov/resources/documents-2016/).

## Overview

Within the FedRAMP Security Assessment Framework, once an authorization has been granted, cloud.gov’s security posture is monitored according to the assessment and authorization process.  Monitoring security controls is part of the overall risk management framework for information security and is a requirement for cloud.gov to maintain a security authorization that meets the FedRAMP requirements.  

Traditionally, this process has been referred to as “Continuous Monitoring” as noted in *NIST SP 800-137 Information Security Continuous Monitoring for Federal Information Systems and Organizations*.  Other NIST documents such as NIST SP 800-37, Revision 1 refer to “ongoing assessment of security controls”.  It is important to note that both the terms “Continuous Monitoring” and “Ongoing Security Assessments” mean essentially the same thing and should be interpreted as such.  

Performing ongoing security assessments determines whether the set of deployed security controls in a cloud information system remains effective in light of new exploits and attacks, and planned and unplanned changes that occur in the system and its environment over time.  To maintain an authorization that meets the FedRAMP requirements, cloud.gov must monitor their security controls, assess them on a regular basis, and demonstrate that the security posture of their service offering is continuously acceptable.  

Ongoing assessment of security controls results in greater control over the security posture of the cloud.gov system and enables timely risk-management decisions.  Security-related information collected through continuous monitoring is used to make recurring updates to the security assessment package.  Ongoing due diligence and review of security controls enables the security authorization package to remain current which allows agencies to make informed risk management decisions as they use cloud services.  

## Process

The FedRAMP continuous monitoring program is based on the continuous monitoring process described in *NIST SP 800-137, Information Security Continuous Monitoring for Federal Information Systems and Organization*.  The goal is to provide: (i) operational visibility; (ii) managed change control; (iii) and attendance to incident response duties.  For more information on incident response, review the *FedRAMP Incident Communications Procedure*.

The effectiveness of cloud.gov’s continuous monitoring capability supports ongoing authorization and reauthorization decisions.  Security-related information collected during continuous monitoring is used to make updates to the security authorization package.  Updated documents provide evidence that FedRAMP baseline security controls continue to safeguard the system as originally planned.  

As defined by the National Institute of Standards and Technology (NIST), the process for continuous monitoring includes the following initiatives:

* **Define** a continuous monitoring strategy based on risk tolerance that maintains clear visibility into assets and awareness of vulnerabilities and utilizes up-to-date threat information.  
* **Establish** measures, metrics, and status monitoring and control assessments frequencies that make known organizational security status and detect changes to information system infrastructure and environments of operation, and status of security control effectiveness in a manner that supports continued operation within acceptable risk tolerances.  
* **Implement** a continuous monitoring program to collect the data required for the defined measures and report on findings; automate collection, analysis and reporting of data where possible.
* **Analyze** the data gathered and **Report** findings accompanied by recommendations.  It may become necessary to collect additional information to clarify or supplement existing monitoring data.
* **Respond** to assessment findings by making decisions to either mitigate technical, management and operational vulnerabilities; or accept the risk; or transfer it to another authority.
* **Review** and **Update** the monitoring program, revising the continuous monitoring strategy and maturing measurement capabilities to increase visibility into assets and awareness of vulnerabilities; further enhance data driven control of the security of an organization’s information infrastructure; and increase organizational flexibility.

Security control assessments performed periodically validate whether stated security controls are implemented correctly, operating as intended, and meet FedRAMP baseline security controls.  Security status reporting provides federal officials with information necessary to make risk-based decisions and provides assurance to existing customer agencies regarding the security posture of the system.


## Roles and responsibilities

### Authorizing Official

Authorizing Officials and their teams (“AOs”) serve as the focal point for coordination of continuous monitoring activities for cloud.gov.  cloud.gov must coordinate with their AOs to send security control artifacts at various points in time.  The AOs monitor both the Plan of Action & Milestones (POA&M) and any major significant changes and reporting artifacts (such as vulnerability scan reports) associated with the cloud.gov service offering.  AOs use this information so that risk-based decisions can be made about ongoing authorization.  Agency customers must perform the following tasks in support of cloud.gov continuous monitoring:

* Notify cloud.gov if the agency becomes aware of an incident that cloud.gov has not yet reported.
* Provide a primary and secondary POC for cloud.gov and US-CERT as described in agency and cloud.gov Incident Response Plans.
* Notify US-CERT when cloud.gov reports an incident.
* Work with cloud.gov to resolve incidents; provide coordination with US-CERT if necessary. 
* Notify FedRAMP ISSO of cloud.gov incident activity. 
* Monitor security controls that are agency responsibilities.  
During incident response, both cloud.gov and leveraging agencies are responsible for coordinating incident handling activities together, and with US-CERT.  The team-based approach to incident handling ensures that all parties are informed and enables incidents to be closed as quickly as possible.

### FedRAMP PMO 

The FedRAMP Program Management Office (PMO) acts as the liaison for the Joint Authorization Board for ensuring that CSPs with a JAB P-ATO strictly adhere to their established Continuous Monitoring Plan.  The JAB and FedRAMP PMO only perform Continuous Monitoring activities for those CSPs that have a JAB P-ATO.

### Department of Homeland Security (DHS) 

The FedRAMP Policy Memo released by OMB defines the DHS FedRAMP responsibilities to include:

* Assisting government-wide and agency-specific efforts to provide adequate, risk-based and cost-effective cybersecurity.
* Coordinating cybersecurity operations and incident response and providing appropriate assistance.
* Developing continuous monitoring standards for ongoing cybersecurity of Federal information systems to include real-time monitoring and continuously verified operating configurations.
* Developing guidance on agency implementation of the Trusted Internet Connection (TIC) program for cloud services.  

The FedRAMP PMO works with DHS to incorporate DHS’s guidance into the FedRAMP program guidance and documents.  

## Third Party Assessment Organization (3PAO) 

Third Party Assessment Organizations (3PAO) are responsible for independently verifying and validating the control implementation and test results for cloud.gov in the continuous monitoring phase of the FedRAMP process.  Specifically, 3PAOs are responsible for:

* Assessing a defined subset of the security controls annually.  
* Submitting the assessment report to the ISSO one year after cloud.gov’s authorization date and each year thereafter.
* Performing announced penetration testing.
* Perform annual scans of web applications, databases, and operating systems.
* Assessing changed controls on an ad hoc basis as requested by the AOs for any changes made to the system by the cloud.gov.

In order to be effective in this role, 3PAOs are responsible for ensuring that the chain of custody is maintained for any 3PAO authored documentation.  3PAOs must also be able to vouch for the veracity and integrity of data provided by the cloud.gov for inclusion in 3PAO authored documentation.  As an example:

* If scans are performed by cloud.gov, the 3PAO must either be on site and observe cloud.gov performing the scans or be able to monitor or verify the results of the scans through other means documented and approved by the AO.
* Documentation provided to cloud.gov must be placed in a format that either cloud.gov cannot alter or that allows the 3PAO to verify the integrity of the document.

## cloud.gov team

### Team responsibilities

The cloud.gov team is responsible for implementing, verifying, and validating the cloud.gov continuous monitoring strategy.

The cloud.gov Program Manager coordinates the tasks needed for the continuous monitoring strategy. They guide the team in assigning necessary tasks to team members in an agile way, including individuals on the Cloud Operations sub-team. 

The cloud.gov team achieves its continuous monitoring strategy primarily by implementing and maintaining a suite of automated components, with some manual tasks to assist with documenting and reporting to people outside the core team.

### Automated components

The cloud.gov team has implemented a suite of automated components to provide continuous monitoring of the cloud.gov system:

* **Metric types and system components that automatically monitor these metrics:** The cloud.gov system has automated components that continuously monitor system metrics:
	* Performance metrics:
		* **collectd**
	* Job / program health:
		* **BOSH Health Monitor (health-monitor)**
	* Malicious code detection:
		* **ClamAV:** detects trojans, viruses, malware and other malicious threats. This runs continuously; files are scanned when they are written/accessed.
		* **Code Climate:** scans all 18F or GSA-originated code for test coverage, complexity, duplication, and security, before being introduced into the production environment. When anyone proposes a change to an 18F-developed component that cloud.gov depends on (in the form of a GitHub pull request), the Code Climate service automatically runs its static analysis tool on the change.
	* Network intrusion detection:
		* **Snort:** continuously monitors network traffic, signatures and behaviors and raises alerts based on defined rules.
	* Intruder detection / file integrity:
		* **Tripwire:** Performs file alteration checks on all cloud.gov virtual machines on initial deploy and a daily basis thereafter, and records all data to CloudWatch logs.
	* Patch / vulnerability scanning:
		* **Nessus:** runs nightly to scan for OS vulnerabilities, application vulnerabilities, malware, and backdoors.
		* **OWASP ZAP:** runs nightly to scan for vulnerabilities.
* **Monitoring of the monitoring components:** The cloud.gov team uses BOSH as an automated way to continuously monitor the six monitoring components. (BOSH is an open source tool for release engineering, deployment, lifecycle management, and monitoring of distributed systems. BOSH allows individual developers and teams to easily version, package and deploy software in a reproducible manner.)
* **Continuous deployment of the monitoring components:** The cloud.gov team uses Concourse to provide automated continuous deployment of the components, to ensure the components stay up to date. In addition, one component, Nessus, has self-updating capabilities.
* **Static code analysis:** The cloud.gov team uses Code Climate to automate code scanning on all original projects that cloud.gov builds. Code Climate results are published on every pull request (code change).

### Manual components

The cloud.gov continuous monitoring strategy also includes manual tasks that are accomplished by team members, including:

* The cloud.gov team updates our POA&M document in an access-controlled GSA Google Drive document.
	* All cloud.gov system components are running on Amazon Web Services and tracked with BOSH or Terraform, so we generate the system inventory using those resources. Then we manually add the inventory to the POA&M document.
* The cloud.gov team submits deliverables to FedRAMP on time.

## Process areas

### Operational visibility

In order to maintain operational visibility, the cloud.gov continuous monitoring program provides reports to the AOs at least monthly. These deliverables include:

* Condition of previous assessment
* Weakness identified since the last assessment
* Known or suspected testing/continuous monitoring failure
* Control implementation that has changed since last assessment
* Newly discovered vulnerability, zero-day attack, or exploit
* Recommendation of Authorizing Official or Organization

### Change control

cloud.gov is a dynamic system in a constant state of change. Configuration management and change control processes help maintain the secure baseline configuration of the cloud.gov architecture.  Routine day-to-day changes are managed through the cloud.gov change management process described in the [configuration management plan]({{< relref "docs/ops/configuration-management.md" >}}).

cloud.gov notifies the AO with a minimum of 30 days before implementing any planned major significant changes, including an analysis of the potential security impact.

### Incident response

All cloud.gov incident response must be handled according to the [incident response guide]({{< relref "docs/ops/security-ir.md" >}}).

## Monthly reporting summary

As described in the FedRAMP requirements, cloud.gov must provide monthly reports of all vulnerability scanning to authorizing officials for review and tracking these vulnerabilities within the POA&Ms.  These deliverables are really a subset of the evidence required at time of authorization. In this vein, the analysis of these scan results should be performed in the same manner they were for time of authorization. In particular, this means:

* All scan findings must be documented (including low findings)
* Each unique vulnerability is tracked as an individual POA&M item
* Deviation requests must be submitted for any requested changes to scan findings (e.g. risk adjustments, false positives, and operational requirements)

We use our [Continuous Monitoring Checklist Template](https://github.com/18F/cg-product/blob/master/ConMonChecklist.md) to help us deliver these monthly updates.

On a monthly basis, Authorizing Officials will be monitoring these deliverables to ensure that cloud.gov maintains an appropriate risk posture – which typically means the risk posture stays at the level of authorization or improves. As a part of any authorization letter, cloud.gov is required to maintain a continuous monitoring program. This analysis on a monthly basis leads to a continuous authorization decision every month by Authorizing Officials.
