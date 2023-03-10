# 1. Introduction

Parenthood is an instinct-driven physiological experience and is the most powerful desire that exists in all the living beings that include all the creatures and people. Inability to have children, in general, is considered as a personal failure and tragedy around the world. In todays world, medical procedures like Assisted reproductive technology (ART) can help with difficulties or an inability to conceive children.

There are many IVF/ART/Testube baby centers/hospitals formulated various diagnosis and treatment options for the infertile couples. These treatment can take anywhere from months to years.

Maintaining treatment history (diagonistic report , doctor prescription, treatment plans , undergone procedure records, etc.) of a couple is very curical for hospital administration.

In hospital, patients records are maintained by various department and departments may use software limited to their domain/department role.

A common Hospital Management Software will not only connect every department in hospital but also help to centeralised data and digitalise workflow.

## 1.1. Purpose of this Document

This software requirement specification document describes the workflow, function and performance requirements of FertiSoft software.

## 1.2. Scope of the Development Project

The primary goal of Fertisoft system is to maintain centrelized data of patients medical history and making it accessible to hospital management through a common software tool without the need for manual interaction between department (less paper work).

Using this software

- A patients can register, request doctors appointment, request an emergency admission.
- Doctors will have an access to list of patients visiting him, patient prescriptions and test results.
- Available doctors can be assigned for consultation, ICU/CCU and doctors in case of emergency admission
- Cashier will have an access list of bills generated by patients
- Hospital management can design and manage commercials related to operations, diagonistic test , treatment

Fertisoft system can aid with

- Patient registeration with KYC
- Scheduling appointments and follow ups
- Admissions in IPD
- Maintaining diagonistic test, treatment record and case paper of patients
- Generate Discharge summaries and invoices & billing
- provide an access to list of patients visit, patient prescriptions and test results.
- Managing user
- Design and manage commercials related to operations, diagonistic test , treatment

**Fertisoft system will be govern by assisted reproductive technology (regulation) act 2022**

**Initial release of Fertisoft system will be available for tier-2 cities and IVF hospital at level-2**

## 1.3. Definitions, Acronyms and Abbreviations

### 1.3.1. Definitions

**Database** :- Collection of data that are either entered by user or administrator.

**User** :- The people who will be using the application.

**Admin** :- Admin is user who has an read and wirte access to complete software, can add user, assign user role.

**In vitro fertilisation(IVF)** :- IVF is a process of fertilisation where an egg is combined with sperm in vitro

**Resident Medical Officer (RMO)** :- RMO evaluats patients' symptoms and recording progress notes. developing treatment plans for patients. maintaining patients' medical records to document all medications and test results.

**Andrologist** :- The physicians who specialize in treating men's reproductive-related issues are known as Andrologists.

**Embryology** :- Embryologists are responsible for retrieving eggs, assisting with in vitro fertilisation, maintaining clinical records and running tests on eggs.

**Pathologist** :- A pathologist is a medical healthcare provider who examines bodies and body tissues. He or she is also responsible for performing lab tests.

**Consultant** :- Consultant is doctor a patient for an expert advice.

## 1.3.2. Abbreviations

**HMS** - Hospital Management System

**GUI** - Graphical User Interface

**IVF** ??? In vitro fertilisation

**RMO** - Resident Medical Officer (RMO)

## 1.4. References

- SRS outline format: https://users.cs.utah.edu/~tch/CS4500S09/guidelines/SRS.html

## 1.5. Overview of Document

# 2. General Description

## 2.1. User Characteristics

The system will cater to the needs of different types of users

**1. Receptionist** :Receptionist will register the patient (IPD/OPD), schedule Appointments, do Follow-up

**2. Cashier** : Cashier will collect the billing amount generated by patient (IPD/OPD) and give receipt

**3. Doctors/consultant** : Consultant will plan ART procedures/ treatments

**4. RMO** : RMO will conduct initial diagnostics of patients and report to consultant

**5. Pathologist** : Pathologist will do the required test and report the test result to Patient RMO & Consultant

**6. Counsellor** : Counsellor with explain the ART procedure plan by consultant to patient and completes documentation requirement for the procedure.

**7. Andrologist** : Andrologist will prepare specimen and conduct test based on ART procedure Plan by consultant and report the test result to Patient RMO & Consultant (Related to male partner)

**8. Nurse** : Nurse will provide medical attention and care attention to IPD patient.

**9. Embrylogist** : Embrylogist will prepare specimen and conduct test based on ART procedure Plan by consultant and report the test result to Patient RMO & Consultant (Related to female partner)

**10. accountant** : Accountant counts will verify the billing details generated casher department

**11. Admins** : Administration department will assign the staff/ user for various department, and provide login credentials

## 2.2. Product Perspective

### 2.2.1. System Specifications

**Hardware Requirements**

1. A device (Computer/laptop)
2. Memory (RAM): Minimum 8GB RAM
3. Processor:Recommended 2GHZ or more.
4. Hard disk ??? 250 GB;
5. Ethernet connection (LAN) or, a wireless adapter (Wi-Fi)

**Software Requirements**

1. A relational database for Data storage.
2. A web browser like Chrome, Mozilla Firefox etc.
3. Operating System ??? Windows, Linux, macOS - 64 bit

### 2.2.2. System Interfaces
  **User interfaces**
  The software provides a good GUI for users. 

  **Hardware Interfaces** -  None

  **Software interfaces** - None

### 2.2.3. Communication Interfaces

## 2.3. Functional Requirements

***For Detailed Functional Requirement Refer Fertisoft Project Management on***

**Tiaga project management tool** : https://tree.taiga.io/project/sanganak-fertisoft/timeline

## 2.4. Non-Functional Requirements

### 2.4.1. Correctness Requirement

The system should accurately provide real time information taking into consideration various issues.

### 2.4.2. Efficiency Requirement

The software is highly efficient and various tasks in its various modules and sub-modules can be performed simultaneously. It can work with many users logged in at the same time and is an efficient solution to the complete HMS

### 2.4.3. Usability Requirement

The software has a simple but efficient user interface, which can be used by all types of users, both technically sound as well as people not having so much knowledge about technology

### 2.4.4. Reliability Requirement

The system is extremely reliable as there are proper measures to protect the private data of the users like prescription and other health records.

### 2.4.5 Maintainability Requirement

Back Up: The system shall provide the capability to back-up the data.

Data Errors: The system shall keep a log of all the errors.

### 2.4.6. Availability requirement

The software will be available online 24/7 and would be able to do its functions at any time of the day.

### 2.4.7. Other requirements

## 2.5. Performance Requirements

The database can accommodate a high number of users without any fault. As the latest technologies have been used, the system would be very responsive and the response would be extremely fast. With high-speed internet connectivity the various operations should not take much time

## 3. General Constraints, Assumptions, Dependencies, Guidelines

### 3.1. Design and Implementation Constraints  

* This software has to perform processing in a local device and that can cause bottlenecks in very low-end devices 
* There is no provision for saving incomplete data.

### 3.2. Assumptions
* Coding is error free.
* The system should have apt storage capacity and provide fast access to the database.
* Users are using their own roles to access the software

### 3.3. Dependencies 
* The hardware and the software of the computer 
* The data entered by all the users are correct.
