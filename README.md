**Secure Cloud Data Governance for Academic Institutions**

**Project Overview**

Secure Cloud Data Governance for Academic Institutions is a cloud security project designed to protect sensitive student information using AWS services. The project demonstrates how academic data such as grades and personal details can be securely stored, accessed, and governed in the cloud through role-based access control and encryption.

This solution ensures that only authorized users can access specific data based on their role, helping institutions maintain data privacy, integrity, and compliance.

**Problem Statement**

Academic institutions handle highly sensitive data including student personal information, academic records, and grades. Unauthorized access or data leakage can lead to serious privacy violations and security risks. Traditional systems often lack fine-grained access control and encryption mechanisms, making them vulnerable to misuse.

**Objectives**

Implement secure Role-Based Access Control (RBAC) for students and teachers

Encrypt sensitive student data using AWS Key Management Service (KMS)

Restrict access to data using Amazon S3 bucket policies

Demonstrate controlled and secure access to academic data

**Project Goals**

Allow students to upload personal data while restricting access to sensitive information

Allow teachers to view and manage sensitive academic data

Ensure all sensitive data is encrypted at rest

Provide a simple and scalable cloud security demonstration for academic governance

**Architecture Overview**

The project architecture is built using AWS cloud services:

Amazon S3: Stores student data securely

AWS IAM Roles:

STUDENT Role – Limited access (upload and view own data)

TEACHER Role – Privileged access (view and manage sensitive data)

AWS KMS: Encrypts sensitive data stored in S3

Access to the S3 bucket is strictly controlled using IAM policies and bucket policies based on user roles.

**Tools & Technologies Used**

AWS IAM – User and role-based access management

AWS KMS – Key management and data encryption

Amazon S3 – Secure object storage

AWS CLI / SDK – Policy testing and access validation

**Expected Outcome**

Students can upload personal data but cannot access sensitive academic records

Teachers can securely access and manage sensitive student data

All sensitive information remains encrypted and protected

Demonstrates effective cloud data governance for academic institutions

**Key Benefits**

Secure storage of academic data in the cloud

Enforced role-based access control

Strong encryption ensures data confidentiality

Scalable and applicable to real-world academic environments

**Team Members**

Sunil Kumar R

Lokeshwaran S

Thamilselvan J

**Demo Video**
Link: https://drive.google.com/drive/folders/1tns3JNz5LKCRaWuMOqoMdcKK9O6Ysvg5?usp=sharing
