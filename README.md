Project Overview:
This system is designed to offer a user-friendly graphical interface for comprehensive management of medical services, encompassing patient prescription, medication dispensation, and medicine inventory control. Additionally, the new system ensures accessibility from Medical Center terminals and remote access via the internet. Patients, both students and staff, can conveniently access their prescriptions online from anywhere.

Users:

General Users (Patients): Students, Staff
Administrative Users: Doctors, Pharmacists, Store Officers, Medicine Distributors
Major Functions:
The primary functionalities of this project include:

Full computerization of the existing management system
Maintenance of patient diagnosis records and recommended tests
Management of patient prescriptions, medicines, medication instructions, precautions, and dietary advice
Recording and tracking of medicine stock in central and sub-stores
Monitoring the procurement and distribution of newly acquired medicines
Generating billing reports for employee patients
Generating various reports
Providing a proposed list of medicines for upcoming months
Password retrieval through hint questions
System Interfaces:

Client on Internet: Web Browser, Operating System (any)
Client on Intranet: Client Software, Web Browser, Operating System (any)
Web Server: Apache Tomcat, Operating System (any)
Database: MySQL
User Interface:
User interfaces for all users consist of graphical user interfaces (GUI), which can be both web-based and desktop-based, connecting to the medical central terminal. The interfaces are designed to be user-friendly and straightforward.

Communication Interface:

Client on the Internet uses HTTP/HTTPS Protocol
Client on the Intranet uses TCP/IP Protocol
Requirements & Installation:
Requirements:

jdk-6u1-windows-i586-p
netbeans-6.9.1-ml-windows
MySQL Database
mysql-5.1.39-win32_2
mysql-connector-odbc-5.1.6-win32
mysql-gui-tools-5.0-r17-win32
mysql-connector-java-5.1.6-bin.jar
Apache Tomcat 6.0.26 (integrated with NetBeans)
Firefox (3.6.3 or higher)
Installation:

Install JDK.
Install NetBeans IDE (Version 6.9.1).
Configure MySQL database with the provided username and password (root and admin by default). You can change these credentials in the database.java file if necessary.
Install the Firefox web browser.
Open NetBeans IDE and import the MedicalCentre project as a web project.
Add mysql-connector-java-5.1.6-bin.jar to Libraries if it's not added already.
Known Issue:
If you encounter database-related issues despite proper installation and configuration, consult the DBQuery.sql file for database queries, including triggers, procedures, and events.

Dummy Users (Available in the System):

User Name: doctor, Password: d, User Type: Doctor
User Name: doctor2, Password: d, User Type: Doctor
User Name: pharmacist, Password: p, User Type: Pharmacist
User Name: md, Password: md1, User Type: Medicine Distributor
User Name: a-cse, Password: p, User Type: Patient (Employee)
User Name: b-cse, Password: p, User Type: Patient (Employee)
User Name: 2007331039, Password: mokarrom, User Type: Patient (Student)
User Name: 2007331023, Password: p, User Type: Patient (Student)
