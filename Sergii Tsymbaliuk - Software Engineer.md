# Sergii Tsymbaliuk

San Jose, CA | +1 (650) 450-0933 | [sergii.tsymbaliuk@gmail.com](mailto:sergii.tsymbaliuk@gmail.com) | [linkedin.com/in/stsymbaliuk](https://www.linkedin.com/in/stsymbaliuk)

## Summary

Senior software engineer specializing in large-scale distributed systems, cloud infrastructure, and data platforms — with high-impact delivery at LinkedIn, AWS, Roku, Apple, and Google. Built petabyte-scale HDFS storage systems at LinkedIn, improved IAM reliability for billions of AWS customers, and drove ~15% engagement growth at Roku through ML personalization — now advancing infrastructure automation and operational intelligence with AI-native tooling.

## Skills

**Languages:** Java, Scala, Python, TypeScript  
**Infrastructure & Cloud:** Kubernetes, Docker, Linux, Shell Scripting, AWS, Google Cloud Platform  
**Data Platforms:** Hadoop/HDFS, Apache Spark, Apache Airflow, Apache Kafka, Apache Gobblin  
**Storage:** MySQL, DynamoDB, Apache Cassandra, MongoDB, Redis  
**APIs & Protocols:** REST, gRPC, HTTP/HTTPS, JSON, Protobuf  
**Domains:** Distributed Systems, Large-Scale Systems, Microservices, Big Data, AI/ML, Cloud Infrastructure  
**Practices:** CI/CD, Platform Engineering, Static Code Analysis, Network Architecture, Agile/Scrum  
**AI Tooling:** Claude Code, LLM, MCP  

## Experience

### Senior Software Engineer — LinkedIn
*Jun 2024 – Present | Sunnyvale, CA*

**Project:** Data Lake Management (DLM) within Core Infrastructure's Analytics & AI Storage team — an intelligent storage management ecosystem spanning Quota Management & Enforcement, HDFS Capacity Planning & Forecasting, Hadoop Corpus Reduction (projected $30M+ savings in H2-FY26), and Space Mover for automated data migration across HDFS clusters.

**Achievements:**

- Owned Space Management Service launch: automated HDFS mount-point lifecycle (provisioning, encryption zones, federation publishing) and cutover orchestration; established SLOs, runbooks, and monitoring for production-grade reliability.

- Led build-out of the Quota Management Service: designed enforcement-group model, implemented mid-tier hard enforcement and throttling, and delivered ETL pipelines for storage visibility and dataset attribution.

- Drove platform observability: migrated quota dashboards to real-time service data, automated dataset-to-enforcement-group mappings via daily ETLs, and extended the usage dashboard with top-path breakdown by storage and object count — improving accuracy and reducing manual operational overhead.

- Built an agent toolkit and skills library to automate quota and utilization analysis across core infrastructure, accelerating team workflows.

**Toolset:** Java, Scala, Python, Kubernetes, Docker, Linux, MySQL, Spring Framework, Hibernate, Hadoop, HDFS, Apache Airflow, Apache Spark, Apache Gobblin, [Openhouse](https://github.com/linkedin/openhouse), [Datahub](https://github.com/datahub-project/datahub), Claude Code, MCP

### Senior Software Engineer — Amazon AWS
*Mar 2022 – Jun 2024 | San Jose, CA*

**Project:** AWS IAM — a foundational AWS service with billions of internal and external customers, requiring extreme availability, strict transactional consistency, and low latency across all global regions.

**Achievements:**

- Delivered a data retention solution for closed AWS accounts: led design, implementation, and multi-year historical data backfill. Explicitly removed PII to satisfy GDPR and CCPA requirements, mitigated legal and reputational risk, and eliminated manual Customer Support retention procedures.

- Implemented a block-listing solution to prevent publicly disclosed account IDs from appearing in documentation and code examples, closing a security and compliance exposure at scale.

- Automated infrastructure and service configuration generation for new AWS regions, reducing time-to-launch from weeks to hours and eliminating manual effort and human error.

**Toolset:** Java, SpringBoot, Guice, Hibernate, MySQL, Ruby on Rails, TypeScript, Docker, Linux, AWS: EC2, ECS, CloudFormation, DynamoDB, Kinesis, S3, SQS, SNS, ELB

### Senior Software Engineer — Roku
*Aug 2020 – Mar 2022 | San Jose, CA*

**Project:** Roku Search and Recommendations — a suite of microservices and data pipelines powering content search and personalized recommendations across the Roku platform and streaming channels.

**Achievements:**

- Designed and launched ML-backed personalized content collections aggregating titles across user subscriptions based on viewing history and preferences, driving ~15% improvement in user engagement.

- Built a probabilistic cardinality metrics framework using HyperLogLog, enabling multi-dimensional customer engagement measurement at scale.

- Root-caused and resolved a critical news feed latency bottleneck, reducing response time from 10 seconds to 200 milliseconds under peak load.

**Toolset:** Java, Spring Framework, SparkJava, Guice, Apache Kafka, Redis, Apache Flume, Docker, EnvoyProxy, gRPC, AWS: DynamoDB, S3, ECS, EKS, ELB, CloudFormation

### Senior Software Engineer — Apple
*Jul 2019 – Aug 2020 | Cupertino, CA*

**Project:** Apple Media Products — a distributed transcoding system at scale used by Apple TV+, iTunes, and the App Store to convert production media assets into consumer formats. Contributed to the architectural shift from a legacy bare-metal media-conversion system to an elastic cloud-native solution.

**Achievements:**

- Integrated the media processing task scheduler with the media-encoding system for Apple TV+, enabling elastic workload distribution across the cloud-native fleet.

- Built a pub/sub notification microservice for tracking media transcoding status and artifact readiness, enabling downstream consumers to react to pipeline events without polling.

- Implemented a cluster telemetry service to collect hardware capabilities, capacity, and utilization data from Kubernetes nodes, supporting resource optimization across the fleet.

- Standardized code quality gates by introducing JaCoCo coverage enforcement and SonarQube Quality Gates into CI, with automated PR decoration for inline review feedback.

- Mentored junior engineers and contributed to engineering hiring.

**Toolset:** Java, Jetty, Guice, gRPC, Docker, Kubernetes, fabric8, AWS SDK, Apache Kafka, Apache Cassandra, Redis, Apache ZooKeeper, Apache Curator, AWS DynamoDB

### Software Engineer — EPAM for Google (YouTube Creator Academy)
*Apr 2018 – Jul 2019 | Mountain View, CA*

**Project:** Online learning platform for YouTube content creators; backend engineering.

**Achievements:**

- Implemented content popularity and user activity metrics, giving creators visibility into engagement and reach.

- Integrated Google's ML-based recommendation service to surface more relevant courses and improve user engagement.

- Automated the Creator Awards ETL pipeline, eliminating manual data processing and freeing 16 developer-hours per month.

- Migrated the App Engine service to Java 8 and Google Cloud Endpoints v2.0, enabling gRPC support for downstream services.

**Toolset:** Java, Python, TypeScript, AngularJS, REST, Protobuf, gRPC, FlumeJava, MapReduce, Apache Beam, Cloud Dataflow, BigTable, BigQuery, Cloud Datastore, MySQL, Bazel, Google Cloud Platform

### Software Engineer — EPAM for Google (Google Search Appliance)
*Apr 2016 – Apr 2018 | Mountain View, CA*

**Project:** Google-manufactured enterprise search appliance for corporate intranet and file systems; platform infrastructure team.

**Achievements:**

- Refactored the build automation service from synchronous to async job execution, cutting average build time from 2 hours to 30 minutes.

- Designed and implemented a custom VPN solution (OpenVPN) for connecting developer machines to remote devices in isolated networks, reducing debug setup time from 2 hours to minutes.

- Built a multi-layer RAID and filesystem health-check module for the self-monitoring and recovery service, specifically targeting device failures caused by unsuccessful patch and upgrade attempts — reducing bricked devices and eliminating the need to ship hardware back to Google for recovery.

- Created a distributed log collection system for a bare-metal test machine pool, enabling teams to aggregate installation and debug logs across remote infrastructure.

**Toolset:** Java, Python, Django, SQLAlchemy, REST, Protobuf, gRPC, Google Borg, Dremel, BigTable, Colossus, MySQL, Bazel, Linux, Docker, Shell Scripting, iptables, OpenVPN, Google Cloud Platform

### Application Support Team Lead — EPAM for Barclays
*Aug 2012 – Apr 2016 | Kyiv, Ukraine*

**Project:** Application support and incident management for Barclays Capital banking systems, leading a distributed team across multiple time zones.

**Achievements:**

- Played a pivotal role in migrating a core banking system to a microservices architecture: contributed to architectural design, planning, and implementation to enhance system scalability and operational efficiency.

- Drove Agile Scrum and Kanban adoption across the support team, achieving ~30% increase in team throughput and 60% reduction in average incident response time.

**Toolset:** Java, MongoDB, Linux, Microsoft SQL Server, T-SQL, C#/.NET, Autosys, Jira, Perforce, ServiceNow, Agile/Scrum/Kanban

### Product Manager — ING Bank Ukraine
*May 2011 – Aug 2012 | Kyiv, Ukraine*

- Led the release of a Cyrillic transliteration module for the SWIFT processing system, shifting international transfers from paper-based to electronic SWIFT transactions and significantly reducing processing time.

**Toolset:** SWIFT, Oracle Application Server, Oracle Database, Java, JavaScript

### Senior Infrastructure Engineer & Network Architect — ING Bank Ukraine
*Nov 2005 – May 2011 | Kyiv, Ukraine*

- Designed and deployed highly available internet and WAN connectivity across multiple bank data centers.

- Migrated the network core to a split architecture with VRRP, BGP, OSPF, and IPSec-based load balancing, eliminating single points of failure.

- Introduced centralized AAA on network devices using LDAP, SNMP, and Cisco IOS; automated configuration management and backup.

- Deployed a NetFlow-based traffic monitoring and analysis platform across data centers.

- Established multipath LAN/WAN routing using BGP/OSPF with route redistribution, eliminating cold-standby infrastructure dependency.

**Toolset:** Cisco IOS, Checkpoint Firewall, Linux, MS SQL Server, Microsoft Active Directory, TCP/IP, DNS, OSPF, BGP, IPSec, VPN, VMware ESXi, Citrix XenApp

### Lead System Administrator — Naftogaz of Ukraine DC Gas-Heat
*Sep 2003 – Oct 2005 | Kyiv, Ukraine*

**Achievements:**

- Built the company's IT infrastructure from the ground up, including servers, networking, and core services.

**Toolset:** Linux, Windows Server, TCP/IP, Network Architecture, Shell Scripting, Automation

## Education

- **M.S. in Computer Science (With Honors)**, 2004 — National Technical University of Ukraine "Kyiv Polytechnic Institute"
  *Specialization: Software of Automated Systems*

- **B.S. in Computer Science**, 2002 — National Technical University of Ukraine "Kyiv Polytechnic Institute"

- **M.S. in Finances (Economics & Enterprise)**, 2009 — Kyiv National Economic University named after Vadym Hetman
  *Specialization: Financial Management in the Business Sphere*

## Publications

- **Authentication Authorization Accounting: Integrating Cisco with Microsoft Active Directory** — *System Administrator Magazine*, №1-2 (98-99), 2011 | [samag.ru/archive/more/103](https://samag.ru/archive/more/103)

## Certifications

- Google Cloud Certified Professional — 2018
- ITIL v3 Foundation — 2013
- Cisco Certified Network Professional (CCNP) — 2008
- Cisco Certified Network Associate (CCNA) — 2005
