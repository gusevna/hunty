[OWASP Testing Checklist](https://www.owasp.org/index.php/Testing_Checklist)


Ref. No.	Category	Test Name
<br>4.2		Information Gathering
<br>4.2.1	OTG-INFO-001	Conduct Search Engine Discovery and Reconnaissance for Information Leakage
<br>4.2.2	OTG-INFO-002	Fingerprint Web Server
<br>4.2.3	OTG-INFO-003	Review Webserver Metafiles for Information Leakage
<br>4.2.4	OTG-INFO-004	Enumerate Applications on Webserver
<br>4.2.5	OTG-INFO-005	Review Webpage Comments and Metadata for Information Leakage
<br>4.2.6	OTG-INFO-006	Identify application entry points
<br>4.2.7	OTG-INFO-007	Map execution paths through application
<br>4.2.8	OTG-INFO-008	Fingerprint Web Application Framework
<br>4.2.9	OTG-INFO-009	Fingerprint Web Application
<br>4.2.10	OTG-INFO-010	Map Application Architecture
<br>4.3		Configuration and Deploy Management Testing
<br>4.3.1	OTG-CONFIG-001	Test Network/Infrastructure Configuration
<br>4.3.2	OTG-CONFIG-002	Test Application Platform Configuration
<br>4.3.3	OTG-CONFIG-003	Test File Extensions Handling for Sensitive Information
<br>4.3.4	OTG-CONFIG-004	Backup and Unreferenced Files for Sensitive Information
<br>4.3.5	OTG-CONFIG-005	Enumerate Infrastructure and Application Admin Interfaces
<br>4.3.6	OTG-CONFIG-006	Test HTTP Methods
<br>4.3.7	OTG-CONFIG-007	Test HTTP Strict Transport Security
<br>4.3.8	OTG-CONFIG-008	Test RIA cross domain policy
<br>4.4		Identity Management Testing
<br>4.<br>4.1	OTG-IDENT-001	Test Role Definitions
<br>4.<br>4.2	OTG-IDENT-002	Test User Registration Process
<br>4.<br>4.3	OTG-IDENT-003	Test Account Provisioning Process
<br>4.<br>4.4	OTG-IDENT-004	Testing for Account Enumeration and Guessable User Account
<br>4.<br>4.5	OTG-IDENT-005	Testing for Weak or unenforced username policy
<br>4.<br>4.6	OTG-IDENT-006	Test Permissions of Guest/Training Accounts
<br>4.<br>4.7	OTG-IDENT-007	Test Account Suspension/Resumption Process
<br>4.5		Authentication Testing
<br>4.5.1	OTG-AUTHN-001	Testing for Credentials Transported over an Encrypted Channel
<br>4.5.2	OTG-AUTHN-002	Testing for default credentials
<br>4.5.3	OTG-AUTHN-003	Testing for Weak lock out mechanism
<br>4.5.4	OTG-AUTHN-004	Testing for bypassing authentication schema
<br>4.5.5	OTG-AUTHN-005	Test remember password functionality
<br>4.5.6	OTG-AUTHN-006	Testing for Browser cache weakness
<br>4.5.7	OTG-AUTHN-007	Testing for Weak password policy
<br>4.5.8	OTG-AUTHN-008	Testing for Weak security question/answer
<br>4.5.9	OTG-AUTHN-009	Testing for weak password change or reset functionalities
<br>4.5.10	OTG-AUTHN-010	Testing for Weaker authentication in alternative channel
<br>4.6		Authorization Testing
<br>4.6.1	OTG-AUTHZ-001	Testing Directory traversal/file include
<br>4.6.2	OTG-AUTHZ-002	Testing for bypassing authorization schema
<br>4.6.3	OTG-AUTHZ-003	Testing for Privilege Escalation
<br>4.6.4	OTG-AUTHZ-004	Testing for Insecure Direct Object References
<br>4.7		Session Management Testing
<br>4.7.1	OTG-SESS-001	Testing for Bypassing Session Management Schema
<br>4.7.2	OTG-SESS-002	Testing for Cookies attributes
<br>4.7.3	OTG-SESS-003	Testing for Session Fixation
<br>4.7.4	OTG-SESS-004	Testing for Exposed Session Variables
<br>4.7.5	OTG-SESS-005	Testing for Cross Site Request Forgery
<br>4.7.6	OTG-SESS-006	Testing for logout functionality
<br>4.7.7	OTG-SESS-007	Test Session Timeout
<br>4.7.8	OTG-SESS-008	Testing for Session puzzling
<br>4.8		Data Validation Testing
<br>4.8.1	OTG-INPVAL-001	Testing for Reflected Cross Site Scripting
<br>4.8.2	OTG-INPVAL-002	Testing for Stored Cross Site Scripting
<br>4.8.3	OTG-INPVAL-003	Testing for HTTP Verb Tampering
<br>4.8.4	OTG-INPVAL-004	Testing for HTTP Parameter pollution
<br>4.8.5	OTG-INPVAL-005	Testing for SQL Injection
<br>4.8.5.1		Oracle Testing
<br>4.8.5.2		MySQL Testing
<br>4.8.5.3		SQL Server Testing
<br>4.8.5.4		Testing PostgreSQL
<br>4.8.5.5		MS Access Testing
<br>4.8.5.6		Testing for NoSQL injection
<br>4.8.6	OTG-INPVAL-006	Testing for LDAP Injection
<br>4.8.7	OTG-INPVAL-007	Testing for ORM Injection
<br>4.8.8	OTG-INPVAL-008	Testing for XML Injection
<br>4.8.9	OTG-INPVAL-009	Testing for SSI Injection
<br>4.8.10	OTG-INPVAL-010	Testing for XPath Injection
<br>4.8.11	OTG-INPVAL-011	IMAP/SMTP Injection
<br>4.8.12	OTG-INPVAL-012	Testing for Code Injection
<br>4.8.12.1		Testing for Local File Inclusion
<br>4.8.12.2		Testing for Remote File Inclusion
<br>4.8.13	OTG-INPVAL-013	Testing for Command Injection
<br>4.8.14	OTG-INPVAL-014	Testing for Buffer overflow
<br>4.8.1<br>4.1		Testing for Heap overflow
<br>4.8.1<br>4.2		Testing for Stack overflow
<br>4.8.1<br>4.3		Testing for Format string
<br>4.8.15	OTG-INPVAL-015	Testing for incubated vulnerabilities
<br>4.8.16	OTG-INPVAL-016	Testing for HTTP Splitting/Smuggling
<br>4.9		Error Handling
<br>4.9.1	OTG-ERR-001	Analysis of Error Codes
<br>4.9.2	OTG-ERR-002	Analysis of Stack Traces
<br>4.10		Cryptography
<br>4.10.1	OTG-CRYPST-001	Testing for Weak SSL/TSL Ciphers, Insufficient Transport Layer Protection
<br>4.10.2	OTG-CRYPST-002	Testing for Padding Oracle
<br>4.10.3	OTG-CRYPST-003	Testing for Sensitive information sent via unencrypted channels
<br>4.11		Business Logic Testing
<br>4.11.1	OTG-BUSLOGIC-001	Test Business Logic Data Validation
<br>4.11.2	OTG-BUSLOGIC-002	Test Ability to Forge Requests
<br>4.11.3	OTG-BUSLOGIC-003	Test Integrity Checks
<br>4.11.4	OTG-BUSLOGIC-004	Test for Process Timing
<br>4.11.5	OTG-BUSLOGIC-005	Test Number of Times a Function Can be Used Limits
<br>4.11.6	OTG-BUSLOGIC-006	Testing for the Circumvention of Work Flows
<br>4.11.7	OTG-BUSLOGIC-007	Test Defenses Against Application Mis-use
<br>4.11.8	OTG-BUSLOGIC-008	Test Upload of Unexpected File Types
<br>4.11.9	OTG-BUSLOGIC-009	Test Upload of Malicious Files
<br>4.12		Client Side Testing
<br>4.12.1	OTG-CLIENT-001	Testing for DOM based Cross Site Scripting
<br>4.12.2	OTG-CLIENT-002	Testing for JavaScript Execution
<br>4.12.3	OTG-CLIENT-003	Testing for HTML Injection
<br>4.12.4	OTG-CLIENT-004	Testing for Client Side URL Redirect
<br>4.12.5	OTG-CLIENT-005	Testing for CSS Injection
<br>4.12.6	OTG-CLIENT-006	Testing for Client Side Resource Manipulation
<br>4.12.7	OTG-CLIENT-007	Test Cross Origin Resource Sharing
<br>4.12.8	OTG-CLIENT-008	Testing for Cross Site Flashing
<br>4.12.9	OTG-CLIENT-009	Testing for Clickjacking
<br>4.12.10	OTG-CLIENT-010	Testing WebSockets
<br>4.12.11	OTG-CLIENT-011	Test Web Messaging
<br>4.12.12	OTG-CLIENT-012	Test Local Storage
