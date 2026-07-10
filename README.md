# PEITT523 Cloud Computing

This repository contains the student reading path for **PEITT523 Cloud Computing**. The sequence is based on the four-module structure in [`syllabus.md`](syllabus.md) and the chapter list in [`chapters.md`](chapters.md).

Use this file as the practical companion to the syllabus. Read the listed chapter first, then open the linked resources to see how the same ideas appear in real cloud tools, platforms, and services.

> **Cost note:** Some cloud-provider labs require an account and may create billable resources. Use free-tier resources where available, stop or delete resources after practice, and avoid uploading sensitive data.

## Course Files

- [`syllabus.md`](syllabus.md): module-wise reading sequence mapped to the official syllabus
- [`chapters.md`](chapters.md): chapter list and complete reading order
- `Syllabus_PEITT523_Cloud Computing.pdf`: official course syllabus

## Module 1: Cloud Computing Foundations

### Chapter 1: Cloud Computing

**Read for:** cloud computing introduction, computing paradigms, service models, deployment models, cloud characteristics, advantages and disadvantages, reference architecture, and use cases.

**Practical links:**

- [NIST: The Definition of Cloud Computing](https://www.nist.gov/publications/nist-definition-cloud-computing) - standard definition, essential characteristics, service models, and deployment models
- [AWS: What is cloud computing?](https://aws.amazon.com/what-is-cloud-computing/) - service-model examples and common cloud use cases
- [Google Cloud: What is cloud computing?](https://cloud.google.com/learn/what-is-cloud-computing) - cloud concepts from a provider perspective
- [Microsoft Learn: Describe cloud computing](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/) - beginner-friendly module on cloud models, pricing, and shared responsibility

**Try after reading:** identify one real example each for SaaS, PaaS, and IaaS, then explain which responsibilities belong to the provider and which belong to the user.

## Module 2: Virtualization

### Chapter 2: Virtualization

**Read for:** virtualization basics, types of virtualization, hypervisors, virtual machines, containers, virtual clusters, resource management, and the role of virtualization in cloud data centers.

**Practical links:**

- [QEMU System Emulation Introduction](https://www.qemu.org/docs/master/system/introduction.html) - practical view of machine emulation and virtualization
- [Oracle VirtualBox User Manual](https://www.virtualbox.org/manual/UserManual.html) - hands-on virtual machine creation and configuration
- [Docker: What is Docker?](https://docs.docker.com/get-started/docker-overview/) - container-based virtualization and container lifecycle basics
- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/) - how containers are deployed and managed as distributed applications
- [Microsoft Learn: Install Hyper-V](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v) - practical hypervisor setup on Windows

**Try after reading:** create a small Linux VM or container, check its CPU, memory, network, and storage settings, and compare those with the host machine.

## Module 3: Compute, Storage, and Cloud Security

### Chapter 3: Architectural Design of Compute and Storage Clouds

**Read for:** data center interconnection networks, compute-cloud architecture, storage-cloud architecture, cloud platforms, resource management, and design challenges.

**Practical links:**

- [OpenStack Installation Guide: Overview](https://docs.openstack.org/install-guide/overview.html) - open-source cloud architecture and core services
- [AWS EC2: Get started](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html) - launch and connect to a virtual server
- [AWS EBS: What is Amazon Elastic Block Store?](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html) - block storage used with cloud virtual machines
- [AWS S3: Getting started](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html) - object storage concepts using buckets and objects
- [Google Compute Engine: Create a Linux VM](https://cloud.google.com/compute/docs/create-linux-vm-instance) - VM creation on Google Cloud

**Try after reading:** draw a simple cloud architecture with one VM, one block-storage volume, one object-storage bucket, a virtual network, and a firewall rule.

### Chapter 4: Secure Distributed Data Storage in Cloud - Methods and Practices

**Read for:** cloud security threats, cryptography, attacks, secure distributed data storage, security requirements, security controls, and security architecture.

**Practical links:**

- [NIST SP 800-144: Guidelines on Security and Privacy in Public Cloud Computing](https://csrc.nist.gov/pubs/sp/800/144/final) - security and privacy risks in public cloud
- [AWS Well-Architected: Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) - security design principles for cloud workloads
- [AWS S3 Security Best Practices](https://docs.aws.amazon.com/AmazonS3/latest/userguide/security-best-practices.html) - practical storage security controls
- [Google Cloud Security Foundations Blueprint](https://cloud.google.com/architecture/security-foundations) - cloud security architecture and governance patterns
- [Microsoft Azure: Shared responsibility in the cloud](https://learn.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility) - responsibility split across IaaS, PaaS, and SaaS

**Try after reading:** list the security controls you would apply to an object-storage bucket containing student assignment submissions.

### Chapter 12: Cloud Computing Governance and Compliance

**Read for:** governance, risk, compliance, audit readiness, policy controls, and cloud accountability.

**Practical links:**

- [AWS: Security and compliance overview](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/security-and-compliance.html) - provider-side security and compliance services
- [Microsoft Azure Security Fundamentals](https://learn.microsoft.com/en-us/azure/security/fundamentals/overview) - Azure security concepts and controls
- [Google Cloud Architecture Center: Security, privacy, and compliance](https://cloud.google.com/architecture/security-foundations) - governance-oriented security foundations
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) - common vocabulary for identifying, protecting, detecting, responding, and recovering

**Try after reading:** prepare a one-page policy checklist for a college department moving a course-management application to the cloud.

## Module 4: Distributed Programming, Cloud Software, Databases, and Platforms

### Chapter 8: Parallel and Distributed Programming Models

**Read for:** parallel programming, distributed programming, task decomposition, communication, synchronization, and cloud-scale execution patterns.

**Practical links:**

- [Apache Beam Programming Guide](https://beam.apache.org/documentation/programming-guide/) - modern distributed data-processing model
- [OpenMP Tutorials and Articles](https://www.openmp.org/resources/tutorials-articles/) - shared-memory parallel programming references
- [MPI Tutorial](https://mpitutorial.com/tutorials/) - message-passing concepts used in distributed systems
- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/) - deployment, scaling, and service discovery for distributed applications

**Try after reading:** take a simple task such as word counting or image processing and describe how it can be split into independent subtasks.

### Chapter 9: Implementation and Testing of MapReduce Programming Model in Cloud

**Read for:** MapReduce programming model, logical data flow, control flow, inverted index case study, Hadoop library, implementation, and testing.

**Practical links:**

- [Apache Hadoop MapReduce Tutorial](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - official MapReduce example flow
- [Apache Hadoop Single Node Setup](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html) - local Hadoop setup for practice
- [Apache Hadoop HDFS Architecture](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) - how Hadoop stores data before processing

**Try after reading:** manually trace the map, shuffle, and reduce phases for an inverted-index example using three short text documents.

### Chapter 10: Apache Spark - A Framework for Big Data

**Read for:** Apache Spark fundamentals, resilient distributed datasets, DataFrames, Spark SQL, and Spark as a big-data processing framework.

**Practical links:**

- [Apache Spark Quick Start](https://spark.apache.org/docs/latest/quick-start.html) - hands-on Spark shell and first operations
- [Apache Spark SQL Getting Started](https://spark.apache.org/docs/latest/sql-getting-started.html) - DataFrame and SQL practice
- [Apache Spark Examples](https://spark.apache.org/examples.html) - sample Spark programs and workloads

**Try after reading:** run a small word-count or CSV aggregation example in Spark and compare its programming style with MapReduce.

### Chapter 5: Emerging Cloud Software Environments

**Read for:** Eucalyptus, OpenNebula, OpenStack, Aneka, CloudSim, and cloud environment simulation or management tools.

**Practical links:**

- [OpenStack Installation Guide](https://docs.openstack.org/install-guide/) - practical private-cloud platform setup overview
- [OpenNebula Documentation](https://opennebula.io/docs/) - private, hybrid, and edge cloud management platform
- [Eucalyptus Wiki](https://github.com/eucalyptus/eucalyptus/wiki) - historical AWS-compatible private-cloud software
- [CloudSim GitHub Repository](https://github.com/Cloudslab/cloudsim) - simulation toolkit for cloud infrastructure research
- [Aneka: A Software Platform for .NET-based Cloud Computing](https://arxiv.org/abs/0907.4622) - research paper explaining Aneka architecture and programming models

**Try after reading:** compare OpenStack, OpenNebula, and CloudSim by purpose: production cloud platform, cloud management platform, and simulation toolkit.

### Chapter 6: Popular Cloud Databases

**Read for:** cloud databases, NoSQL systems, MongoDB, HBase, document stores, wide-column stores, scalability, and database use cases.

**Practical links:**

- [MongoDB Manual](https://www.mongodb.com/docs/manual/) - document database concepts and operations
- [MongoDB Getting Started](https://www.mongodb.com/docs/manual/tutorial/getting-started/) - first database, collection, and query workflow
- [MongoDB University](https://learn.mongodb.com/) - free guided labs and courses
- [Apache HBase Reference Guide](https://hbase.apache.org/book.html) - HBase architecture, data model, and shell usage
- [Apache HBase Quick Start](https://hbase.apache.org/book.html#quickstart) - standalone HBase practice path

**Try after reading:** model the same student-record data once as MongoDB documents and once as an HBase table, then compare the query patterns.

### Chapter 7: Big Data Analytics in Cloud

**Read for:** big-data pipelines, cloud analytics workflows, data ingestion, storage, processing, and analytics services.

**Practical links:**

- [Google BigQuery Sandbox](https://cloud.google.com/bigquery/docs/sandbox) - practice SQL analytics without setting up servers
- [Apache Spark SQL Getting Started](https://spark.apache.org/docs/latest/sql-getting-started.html) - distributed analytics with Spark DataFrames and SQL
- [AWS S3: What is Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html) - object storage as a common data lake foundation
- [Google Cloud Storage Quickstart](https://cloud.google.com/storage/docs/discover-object-storage-console) - upload and manage analytics data in object storage

**Try after reading:** create a simple analytics flow: raw CSV file, object storage, processing step, and final query/report.

### Chapter 11: Use Cases: Hadoop, R, and Social Network Analysis

**Read for:** Hadoop use cases, R-based analytics, and social network analysis workflows.

**Practical links:**

- [Apache Hadoop Documentation](https://hadoop.apache.org/docs/stable/) - Hadoop ecosystem reference
- [R Project](https://www.r-project.org/) - statistical computing environment used for analytics
- [igraph for R](https://r.igraph.org/) - network analysis and graph visualization in R
- [Gephi Tutorials](https://gephi.org/users/) - visual exploration of social networks and graph data

**Try after reading:** create a small graph of students and shared project groups, then compute degree or centrality using R igraph or Gephi.

## Cloud Platform Supplement

The syllabus also names AWS, Google Cloud Platform, and Microsoft Azure services. Use these links when studying the provider-specific parts of Module 4.

### Amazon Web Services

- [Amazon EC2: Get started](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- [Amazon S3: Getting started](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html)
- [Amazon EBS: What is Amazon EBS?](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
- [Amazon CloudFront: Get started](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GettingStarted.html)

### Google Cloud Platform

- [Google Cloud: Get started](https://cloud.google.com/docs/get-started)
- [Compute Engine: Create a Linux VM](https://cloud.google.com/compute/docs/create-linux-vm-instance)
- [App Engine Standard Environment](https://cloud.google.com/appengine/docs/standard)
- [Cloud Storage Quickstart](https://cloud.google.com/storage/docs/discover-object-storage-console)

### Microsoft Azure

- [Azure Training](https://learn.microsoft.com/en-us/training/azure/)
- [Azure Virtual Machines Overview](https://learn.microsoft.com/en-us/azure/virtual-machines/overview)
- [Create a Linux VM in the Azure portal](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal)
- [Azure Storage Introduction](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- [Create an Azure Storage Account](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create)
- [Install Hyper-V](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)

## Complete Reading Order

1. Chapter 1: Cloud Computing
2. Chapter 2: Virtualization
3. Chapter 3: Architectural Design of Compute and Storage Clouds
4. Chapter 4: Secure Distributed Data Storage in Cloud - Methods and Practices
5. Chapter 12: Cloud Computing Governance and Compliance
6. Chapter 8: Parallel and Distributed Programming Models
7. Chapter 9: Implementation and Testing of MapReduce Programming Model in Cloud
8. Chapter 10: Apache Spark - A Framework for Big Data
9. Chapter 5: Emerging Cloud Software Environments
10. Chapter 6: Popular Cloud Databases
11. Chapter 7: Big Data Analytics in Cloud
12. Chapter 11: Use Cases: Hadoop, R, and Social Network Analysis

## Primary Textbook

**[Cloud Computing & Big Data: From the Basics to Practical Use Cases](https://www.cengage.co.in/book-list/ebook/cloud-computing-big-data-from-the-basics-to-practical-use-cases-qr)**

**Authors:**

- M Sudheep Elayidom
- Sarith Divakar M.
- Lija Mohan
- Tanmay Kumar Pandey
- Shubham Agrawal

**Publisher:** Cengage Learning India Pvt. Ltd.  
**ISBN:** 9789360533953  
**Edition:** 1st Edition  
**Copyright:** 2025  
**Binding:** Paperback  
**Pages:** 320  
**Trim size:** 241 x 181 mm  
**Listed price:** Rs. 495  
**Official book page:** <https://www.cengage.co.in/book-list/ebook/cloud-computing-big-data-from-the-basics-to-practical-use-cases-qr>

### Buy the Book

**Amazon India:** [Buy Cloud Computing & Big Data on Amazon](https://www.amazon.in/Cloud-Computing-Big-Data-Practical/dp/9360533955)

Amazon listing details checked on **25 June 2026**:

- **ASIN / ISBN-10:** 9360533955
- **ISBN-13:** 978-9360533953
- **Format:** Paperback
- **Publication date:** 15 July 2024
- **Language:** English
- **Publisher:** Cengage Learning India Pvt. Ltd.
- **Print length:** 320 pages
- **Dimensions:** 24.1 x 18.1 x 12.5 cm
- **Customer rating shown:** 4.6 out of 5 stars from 6 reviews
- **Amazon price shown:** Rs. 442.00, with new offers from Rs. 426.94

Prices, seller details, ratings, delivery dates, and availability can change on Amazon. Check the Amazon listing before purchasing.

### Supplemental Material and Code

[Cengage Digital App](https://www.cengage.co.in/cengagedigital) includes: Solutions manual, additional readings, and videos.
