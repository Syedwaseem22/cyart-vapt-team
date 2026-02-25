Vulnerability Assessment & Reporting Lab
Overview

This project demonstrates a structured vulnerability assessment process using Kali Linux and a vulnerable virtual machine. The objective is to simulate a real-world security testing workflow including environment setup, scanning, documentation, risk assessment, and reporting.

1. Setup Testing Environment
Tools Used

Kali Linux

Metasploitable 3

Vmware 

Steps Performed

Installed Kali Linux as the attacker machine.

Downloaded Metasploitable 3 from GitHub and deployed it as a vulnerable target VM.

Configured VirtualBox networking (Host-Only / Internal Network) to allow communication between VMs.

Verified connectivity using ping and basic network discovery.

2. Vulnerability Scanning
Tools Used

OpenVAS (Greenbone Vulnerability Manager)

Nikto (Web Server Scanner)

Steps Performed

OpenVAS Scan

sudo openvas-start


Launched OpenVAS from Kali Linux.

Created a target using the Metasploitable IP address.

Executed a full vulnerability scan.

Analyzed results including:

CVSS scores

CVE IDs

Affected services

Severity ratings

Nikto Scan

Performed web server scanning against the target IP.

Identified outdated services and misconfigurations.

3. Documentation of Findings
Tools Used

Google Sheets / Microsoft Excel

Screenshots

Recorded Information

Target IP address

Open ports

Running services

Vulnerability name

CVE ID

CVSS Score

Description

Severity level

Example Finding:

Service: Apache Tomcat

Issue: Outdated Version

Risk: Remote Code Execution

Screenshots of scan results were captured and stored for reporting.

4. Risk Assessment Practice
CVSS Scoring

Used the CVSS Calculator to:

Evaluate base score

Determine severity category

Understand impact metrics

Risk Prioritization

Applied a 3x3 Risk Matrix:

Likelihood	Impact	Risk Level
High	High	Critical
Medium	High	High
Low	Medium	Moderate

This helped prioritize remediation efforts.

5. Report Creation

A comprehensive report was created and exported as a PDF file.

Report Structure

Executive Summary

Overview of major risks

Overall security posture

High-level recommendations

Technical Details

Scan results

Screenshots

CVSS scores

CVE references

Remediation

Configuration hardening steps

Official vendor links

Outcome

This lab demonstrates the complete vulnerability assessment lifecycle:

Environment setup

Vulnerability discovery

Documentation

Risk evaluation

Professional reporting
