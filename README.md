# Fictitious Company Security Audit


<h1>Practice project security audit of a fictitious company for the Google Cybersecurity Certificate on Coursera.</h1>




<h2>Languages and Utilities Used</h2>

- <b>Coursera</b> 


<h2>Environments Used </h2>

- <b>Windows 11 PRO
- Chrome Browser
- Microsoft Word </b> 

<h2>Audit</h2>

<p align="center">
<b>Botium Toys Internal Audit </b><br>(Fictitious Company Auditing Exercise)</br>

<p align="left">
  
<b>Summary: </b>
Perform an internal audit of Botium Toys’ cybersecurity program. The audit will need to align with the current business model and industry standards. The purpose of the audit is to provide mitigation strategies for vulnerabilities classified as high-risk and present a framework for improving the security posture of the organization. The audit team will document findings, provide remediation recommendations, and communicate with stakeholders.

<b>Scope: </b>
The Botium Toys internal audit will assess the following:<ul>
  <li>Current user permissions are set in the following systems: accounting, endpoint detections, firewalls, intrusion detection systems, security information, and event management tools.</li>
  <li>Current implemented controls in the following systems: accounting, endpoint detections, firewalls, intrusion detection system, security information, and event management tools. </li>
  <li>Current procedures and protocols in the following systems: accounting, endpoint detections, firewalls, intrusion detection system, security information, and event management tools. </li>
  <li>Ensure current user permissions, controls, procedures, and protocols align with compliance requirements. </li>
  <li>Ensure current technology is accounted for including hardware and system access.</li>
</ul>

<b>Goals: </b>The goals for the Botium Toys’ internal audit are:
<p></p>
<ul>
  <li>To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF). </li>
  <li>Establish a better process for their systems to ensure they are compliant.</li>
  <li>Fortify system controls.</li>
  <li>Implement the concept of least permission to user credential management.</li>
  <li>Establish their policies and procedures including their playbooks.</li>
  <li>Ensure the meeting of compliance requirements. </li>
</ul>
<b>Current assets: </b>Assets managed by the IT department include the following:
<p></p> <ul>
  <li>On-premises equipment for office business needs. </li>
  <li>Employee equipment includes end-user devices such as desktops, laptops, and smartphones, remote workstations, headsets, cables, keyboards, mice, docking stations, and surveillance cameras.</li>
   <li>Management of systems, software, and services: accounting, telecommunications, database, security, e-commerce, and inventory management.</li>
   <li>Internet access.</li>
   <li>Internal network.</li>
   <li>Vendor access management.</li>
   <li>Data center hosting services.</li>
   <li>Data retention and storage.</li>
   <li>Badge readers.</li>
   <li>Legacy system maintenance: end-of-life systems that require human monitoring.</li>
</ul>
<b>Risk Description: </b>Currently, there is inadequate management of assets, Additionally, Botium Toys does not have proper controls in place and may not be compliant with U.S. and international regulations and standards.
Control best practices: The first of the five functions of the NIST CSF are Identified. Botium Toys will need to dedicate resources to managing assets. Additionally, they will need to determine the impact of the loss of existing assets, including systems on the business continuity.
<br></br>
<b>Risk Score: </b>On a scale of 1 to 10, the risk score is 8 which is high. This is due to a lack of controls and adherence to necessary compliance regulations and standards.
<br></br>

<b>Additional comments: </b>Several critical issues require immediate attention:<p></p><ul>
  <li>All Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII. </li>
  <li>Encryption is not in current use to ensure the confidentiality of customer credit card information that is accepted, processed, transmitted, and stored in the company's internal database.</li>
  <li>Access controls pertaining to least privilege and separation of duties have not been implemented. </li>
  <li>The IT department has ensured availability and integrated controls to ensure data integrity.</li>
  <li>The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.</li>
  <li>Antivirus software is installed and monitored by the IT department.</li>
  <li>The IT department has not installed an intrusion detection system (IDS).</li>
  <li>There are no disaster recovery plans in place including no backups for critical data.</li>
  <li>The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Privacy policies, procedures, and processes have been developed and enforced among the IT department and other employees to properly document and maintain data.</li>
  <li>Password policy exists but requirements are not in line with current minimum password complexity needs which include at least eight characters, a combination of letters at least one number, and one special character.</li>
  <li>There is no centralized password management system that enforces the password policy minimum requirements which affects productivity when employees submit a ticket to the IT department to recover or reset a password.</li>
  <li>Legacy systems are monitored and maintained but there is no regular schedule in place for these tasks and intervention methods are unclear.</li>
  <li>Physical locations which include Botium Toys’ main offices, storefront, and warehouse have sufficient locks, an up-to-date CCTV surveillance system, and a functioning fire detection and prevention system.</li></ul>
<br />


<p align="left">
<b>Administrative Controls: </b>
 <p align="left"> 
<img src="https://imgur.com/1kQ4Dd1.png" height="80%" width="80%" alt=""/>
  
<p align="left">
<b>Technical Controls: </b>
 <p align="left"> 
<img src="https://imgur.com/8Su4vKX.png" height="80%" width="80%" alt=""/>

<p align="left">
<b>Physical Controls: </b>
 <p align="left"> 
<img src="https://imgur.com/qDFsP2z.png" height="80%" width="80%" alt=""/>




<p align="left">
<b>Payment Card Industry Data Security Standard (PCI DSS): </b>
 <p align="left"> 
<img src="https://imgur.com/pJwAK4R.png" height="80%" width="80%" alt=""/>



<p align="left">
<b>General Data Protection Regulation (GDPR): </b>
 <p align="left"> 
<img src="https://imgur.com/WL8fT87.png" height="80%" width="80%" alt=""/>


<p align="left">
<b>System and Organizations Controls (SOC type 1, SOC type 2): </b>
 <p align="left"> 
<img src="https://imgur.com/YfDMNLU.png" height="80%" width="80%" alt=""/>


<p><strong>Recommendations:</strong></p>
<ul>
  <li>Implement the principle of least privilege across the company. Integration of Role-Based Access Control (RBAC) in which permissions are associated with specific roles and responsibilities.</li>
  <li>Develop a disaster recovery plan that outlines procedures for data recovery in the case of an event. Also, automate regular backups of important data.</li>
  <li>Establish an access control policy that defines who can access data and under what circumstances. Communicate the new strategy to all employees.</li>
  <li>Implement a separation of duty policy to prevent a single user from having excessive control.</li>
  <li>Deploy an intrusion detection system (IDS) that monitors network traffic and can alert the IT team to suspicious activities.</li>
  <li>Create a schedule for regular legacy system monitoring and updates to keep it secure and functioning.</li>
  <li>An encryption tool should be implemented to protect sensitive personally identifiable information (PII) during transit and at rest.</li>
  <li>Implement an improved password management system through policy updates, higher-level password complexity and expiration, and multi-factor authentication.</li>
  <li>Conduct regular security training for all employees to improve best practices and encourage prompt reporting of suspicious activities.</li>
</ul>


 
  



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
