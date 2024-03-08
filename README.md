# Profile

# Project Scenario: Completing Penetration Test & Report for SimCorp


## About our team (EDIT)

Insert a few sentences about what/who Red Team Robinhood is.


## Team Members 

- William Baur:

 <img width="239" alt="Screen Shot 2024-03-08 at 2 26 33 PM" src="https://github.com/RedTeamRobinhood/Profile/assets/139098353/bf227cef-c9c4-4341-97cf-ef0c62726bdd">

  Cybersecurity professional, DePaul University graduate, and Marine Corps Veteran 12 years of service as a Tactical data systems administrator. Experience in networking, Active Directory, Windows, Linux, and Unix operating systems. Leadership roles in both the corporate and military environments, working with C-level executives and Generals.

  [LinkedIn](https://www.linkedin.com/in/williamrbaur/) [GitHub](https://github.com/Wrbaur)

- Renona Gay:

 <img width="235" alt="Screen Shot 2024-03-08 at 2 36 16 PM" src="https://github.com/RedTeamRobinhood/Profile/assets/139098353/6319fa51-282d-4cdc-9d43-7e3edabdd3ab">

  Add info here: (EDIT)

  [LinkedIn](https://www.linkedin.com/in/renona-g-57935912a/) [GitHub](https://github.com/Foodisthebest)
  
- Heraldo Morales:

 <img width="234" alt="Screen Shot 2024-03-08 at 3 03 21 PM" src="https://github.com/RedTeamRobinhood/Profile/assets/139098353/e9b97dbd-c386-41e2-b5c5-3050e6758e12">

  Studying in Cybersecurity, already have basic level skills for using commands. Basic knowledge of Virtual Machine program, Have knowledge in Command Prompt/Terminal. A fast and avid learner.

- [LinkedIn](https://www.linkedin.com/in/heraldo-morales/) [GitHub](https://github.com/HeraldoM332)

- Mike Sineiro:

 <img width="263" alt="Screen Shot 2024-03-08 at 3 05 15 PM" src="https://github.com/RedTeamRobinhood/Profile/assets/139098353/96ee49ab-ab7a-4811-8c31-49514b3fca5e">

  Add info here: (EDIT)

- [LinkedIn](https://www.linkedin.com/in/michael-sineiro-4784b517b/) [GitHub](https://github.com/KrustyKode)

- Amleset Tesfamariam:

 <img width="176" alt="Screen Shot 2024-03-08 at 2 58 32 PM" src="https://github.com/RedTeamRobinhood/Profile/assets/139098353/8721bbb0-3adb-44ee-99d0-b83f5bb63bef">

 Previously I worked in healthcare before pursuing cybersecurity. While working in healthcare, I had the opportunity to work closely with sensitive patient data and witness the critical importance of data privacy and security. This experience instilled in me a deep appreciation for the need to protect confidential information and ensure the integrity of digital systems. I recognized that my background in healthcare provided me with valuable insights into the complexities of safeguarding data and mitigating risks in a highly regulated environment.

- [LinkedIn](https://www.linkedin.com/in/amleset-t/) [GitHub](https://github.com/AmlesetT)


## Executive Summary:

* We have been tasked with enumerating the target network at SimCorp from a "black box" position (minimal knowledge of the target environment) starting with a foothold on a single endpoint. One of our goals is to discover as many vulnerabilities as we can and document them in accordance with community resources such as CWE and CVSS. Additionally, we will apply TTPs and perform exploits as the opportunities present themselves and document how these TTPs were executed and whether they were successful or not.


## Current Challenges: (EDIT)

* Inadequate IAM Practices: NotOurJob Solution currently lacks stringent IAM policies for its root and user accounts, leading to potential security vulnerabilities.

* Server Vulnerability: Their Windows Server DC and Linux data servers, especially those handling PII and PCI data, are not fully compliant with CIS benchmarks, posing risks to data integrity and security.

* Insufficient Data Encryption: Sensitive data stored in their cloud infrastructure is not adequately encrypted, both at rest and in transit, leading to potential data breaches.

* Lack of Effective Monitoring: The absence of a robust SIEM system hinders the real-time detection of malicious activities and delays response to potential threats.

* Inefficient Cloud Monitoring Systems: Current cloud monitoring practices are insufficient to capture and analyze traffic effectively, limiting the ability to detect and respond to attack TTPs.


## Proposed Solutions: (EDIT)

* IAM Configuration: Implement robust IAM policies, including multi-factor authentication and regular audits, to secure root and user accounts.

* Server Hardening and Data Protection: Harden the Windows Server DC and Linux data servers following CIS benchmarks. Implement comprehensive encryption for data at rest and in transit.

* SIEM/Log Aggregation System Implementation: Deploy and configure Splunk, CloudWatch, or Elastic Stack to ingest and analyze event logs from key AWS assets in real time.

* Cloud Monitoring Enhancement: Utilize VPC Flow Logs and AWS Lambda functions for capturing traffic and automating responses to detected threats. Implement monitoring for failed SSH attempts and unusual patterns.

* Novel Tool Integration: Explore and implement a novel cybersecurity tool or technique to enhance the existing security framework.

* Compliance and Documentation: Develop thorough compliance documentation and security incident plans to align with industry standards like PCI or GDPR.


## Project Objectives:

* Enumerate the target network, gleaning as much information as possible about the various hosts and their configurations. Document in detail what tools were used and how much you were able to reveal.
* Create a professional network topology of the target environment for inclusion in your final report.
* Discover vulnerabilities on targets hosts on the network. There will be at least one web application for you to discover and test against, in addition to several other instances running various operating systems with unknown configurations.
* Build/customize and utilize at least one custom Python tool to aid in your team's offensive efforts.
* Exploit and gain access to as many host instances as possible, and as deeply as possible.
* Outcome Expectation:
* Upon project completion, SimCorp will have a complete penetration test report, highlighting their vulnerabilities, tested exploits, and areas to potentially improve to help strengthen their systems and thus improving their cybersecurity posture.


## Project Management Tool 

* Trello Board: [Trello](https://trello.com/b/ah44Trby/red-team-robinhood)


## Team Documents 

- [Team Agreement]()
- [System Selection]()
- [Presentation Materials]()
- [SOPs]()
- [Visuals]()


## Additional Resources 
