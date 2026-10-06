# Awesome-Security-Investigation-Threat-Analysis

## Top Security Investigation & Threat Analysis Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SIEM, Threat Hunting & Self-Hosted Security Analytics*  

**Last updated: October 2026**



This repository tracks notable **commercial security investigation platforms** and **open-source projects** that help security teams detect, investigate, and respond to threats. These tools aggregate logs, correlate events, hunt for indicators of compromise, and automate incident response.



**Examples** include Amazon Detective, Microsoft Sentinel, Splunk Enterprise Security, Google Chronicle, Datadog Cloud SIEM, Panther Labs, Elastic Security, Exabeam, Securonix, and Rapid7 InsightIDR (the category leaders).



**Open-source emphasis**: Security investigation is a strong open-source domain. **Wazuh** leads as the most balanced open-source SIEM/XDR, **Security Onion** delivers complete network security monitoring, **Matano** brings serverless security data lakes, and **Elastic Security** provides SIEM/EDR. **TheHive** and **Cortex** handle incident response, **MISP** aggregates threat intelligence, and **Velociraptor** enables endpoint hunting. **Zeek**, **Suricata**, and **Sigma** complete the detection stack. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel)**  

  **Microsoft's cloud-native SIEM and SOAR** — integrated with Azure, Microsoft 365, and third-party sources . **Consumption-based pricing** per GB ingested . **Best for Microsoft-centric organizations** .



- **[Splunk Enterprise Security](https://www.splunk.com/en_us/products/enterprise-security.html)**  

  **The enterprise SIEM standard** — mature UEBA, correlation, and the largest app ecosystem . **Pricing scales with data volume** . **Best for large SOCs with dedicated teams** .



- **[Google Chronicle](https://cloud.google.com/chronicle)**  

  **Google's cloud-native SIEM** — petabyte-scale ingestion, UDM normalization, and YARA-L detection . **Best for massive scale** .



- **[Amazon Detective](https://aws.amazon.com/detective/)**  

  **AWS's security investigation service** — visualizes and analyzes security findings . **Best for AWS-native investigations** .



- **[Datadog Cloud SIEM](https://www.datadoghq.com/)**  

  **Datadog's SIEM** — integrated with observability platform . **Best for Datadog users** .



- **[Panther Labs](https://panther.com/)**  

  **Cloud-native SIEM** — detection-as-code with Python rules . **Best for modern security teams** .



- **[Elastic Security](https://www.elastic.co/security)**  

  **SIEM and EDR on Elastic Stack** — detection rules, timelines, and cases . **Best for Elastic ecosystem users** .



- **[Exabeam](https://www.exabeam.com/)**  

  **SIEM with behavioral analytics (UEBA)** — automated incident timelines . **Best for behavioral detection** .



- **[Securonix](https://www.securonix.com/)**  

  **Cloud-native SIEM with UEBA, SOAR, and NDR** . **Best for integrated security analytics** .



- **[Rapid7 InsightIDR](https://www.rapid7.com/products/insightidr/)**  

  **SIEM with UEBA, endpoint detection, and honeypots** . **Best for SIEM + EDR convergence** .



## Open-Source GitHub Projects



### SIEM & Security Analytics



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  **The leading open-source security platform with SIEM and XDR capabilities**, GPLv2 licensed with **16,646+ GitHub stars** . **Native HIDS, FIM, rootkit detection, vulnerability detection, and 1,000+ MITRE ATT&CK rules** . **OpenSearch is the default backend** since v4.4 — Apache 2.0 licensed . **Single-node handles 5,000-10,000 EPS** on 8 vCPU / 16 GB RAM . **The best-balanced open-source SIEM** for most organizations . **Best for log aggregation, detection, and compliance** .



- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)**  

  **Free and open platform for network security monitoring, log management, and case management** . **Integrates Suricata, Zeek, Elastic Stack, Strelka, and OpenCanary** . **Full packet capture** provides "a video camera for your network" . **Scales from single appliance to thousand-node grid** . **Best for network-focused monitoring and threat hunting** .



- **[Matano](https://github.com/matanolabs/matano)**  

  **Open-source, serverless SIEM for AWS**, Apache-2.0 licensed . **Security data lake in your AWS account** — ingest petabytes, store in Iceberg Parquet on S3 . **Detection-as-code in Python** — manage rules in Git . **No vendor lock-in** — query from Athena, Snowflake . **Best for AWS-native security data lakes** .



- **[Elastic Security](https://github.com/elastic/elasticsearch)**  

  **SIEM and EDR on Elastic Stack**, Apache-2.0 (OpenSearch) or Elastic License . **Detection rules, timelines, and cases** . **Trade-off**: Free version lacks correlation engine and built-in rules . **Best for Elastic Stack users** .



- **[OpenSearch Security Analytics](https://github.com/opensearch-project/OpenSearch)**  

  **Apache 2.0 licensed fork of Elasticsearch/Kibana** . **Security Analytics includes Sigma rules, alerting, and anomaly detection at no cost** . **Best for open-source SIEM with Sigma rules** .



### Incident Response & Case Management



- **[TheHive](https://github.com/TheHive-Project/TheHive)**  

  **Open-source incident response platform**, AGPL-3.0 licensed with **3,500+ GitHub stars** . **Case management, collaboration, and task tracking** for security incidents . **Integrates with MISP and Cortex** . **The de facto open-source incident response platform** . **Best for SOC case management** .



- **[Cortex](https://github.com/TheHive-Project/Cortex)**  

  **Open-source observable analysis engine**, AGPL-3.0 licensed . **Analyze observables (IPs, domains, files) with 100+ analyzers** . **Integrates with TheHive** . **Best for automated observable analysis** .



- **[MISP](https://github.com/MISP/MISP)**  

  **Open-source threat intelligence platform**, AGPL-3.0 licensed with **5,000+ GitHub stars** . **Share, store, and correlate threat indicators** . **The de facto open-source threat intel platform** . **Best for threat intelligence sharing** .



- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  **Open-source cyber threat intelligence platform**, Apache-2.0 licensed . **Structured threat intelligence with STIX/TAXII** . **Best for CTI management** .



### Endpoint Hunting & Forensics



- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  

  **Open-source endpoint monitoring and digital forensics**, Apache-2.0 licensed with **3,000+ GitHub stars** . **Query endpoints at scale with VQL** . **The best open-source endpoint hunting tool** . **Best for threat hunting and DFIR** .



- **[GRR](https://github.com/google/grr)**  

  **Google's remote live forensics**, Apache-2.0 licensed . **Scalable incident response and forensics** . **Best for enterprise DFIR** .



- **[osquery](https://github.com/osquery/osquery)**  

  **SQL-powered operating system instrumentation**, Apache-2.0 licensed with **22,000+ GitHub stars** . **Query endpoints like a database** . **Best for endpoint visibility** .



- **[Fleet](https://github.com/fleetdm/fleet)**  

  **Open-source osquery manager**, MIT licensed . **Manage osquery at scale** . **Best for endpoint fleet management** .



### Network Detection & Analysis



- **[Zeek](https://github.com/zeek/zeek)**  

  **Network security monitor**, BSD-3-Clause licensed . **Rich network metadata and file extraction** . **Best for network visibility** .



- **[Suricata](https://github.com/OISF/suricata)**  

  **Network IDS/IPS/NSM**, GPL-2.0 licensed . **Deep packet inspection with TLS and application-layer detection** . **Best for network detection** .



- **[Snort](https://github.com/snort3/snort3)**  

  **Network IDS/IPS**, GPL-2.0 licensed . **DDoS, port scan, and OS fingerprinting detection** . **Best for network intrusion detection** .



- **[RITA](https://github.com/activecm/rita)**  

  **Real Intelligence Threat Analytics**, BSD-3-Clause licensed . **Detect beaconing and C2 traffic** . **Best for network threat hunting** .



### Detection Rules & Frameworks



- **[Sigma](https://github.com/SigmaHQ/sigma)**  

  **Open standard for detection rules**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Vendor-neutral detection rules** — convert to any SIEM . **The de facto standard for detection-as-code** . **Best for portable detection rules** .



- **[MITRE ATT&CK](https://github.com/mitre-attack/attack-navigator)**  

  **Adversary tactics and techniques knowledge base** . **The standard for threat modeling** . **Best for detection coverage mapping** .



- **[Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)**  

  **Library of ATT&CK-mapped tests** . **Best for detection validation** .



- **[Chainsaw](https://github.com/WithSecureLabs/chainsaw)**  

  **Rapidly search and hunt through Windows event logs**, Apache-2.0 licensed . **Best for Windows forensic analysis** .



### Additional Strong Open-Source Options



- **Logstash** — Data collection and transformation .

- **Fluentd** — Unified logging layer .

- **Vector** — Observability data pipeline .

- **Graylog** — Log management with SIEM capabilities .

- **Apache Metron** — Big data security analytics (retired) .

- **Prelude SIEM** — Hybrid SIEM with correlation .

- **SIEMonster** — Open-source SIEM for MSSPs .

- **Deepfence** — Cloud-native security and threat analysis .



**Frameworks for building custom security investigation solutions**: Combine **Wazuh** for SIEM/XDR with compliance and MITRE rules . Use **Security Onion** for network-focused monitoring with full packet capture . Deploy **Matano** for AWS-native security data lakes . Choose **TheHive** + **Cortex** for incident response and case management . Integrate **MISP** or **OpenCTI** for threat intelligence . Use **Velociraptor** for endpoint hunting and DFIR . Deploy **Sigma** for portable detection rules . Note that true enterprise security investigation with curated threat intelligence, managed detection content, and vendor-supported SLAs (Splunk, Sentinel, Chronicle) remains primarily commercial territory; open-source stacks provide strong SIEM, incident response, and threat hunting foundations that require integration for complete security operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Security investigation platforms process sensitive security telemetry and may contain PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Open-source SIEM has hidden costs** — engineering overhead, detection coverage gaps, limited UEBA, manual compliance reporting, and higher false-positive rates increase analyst triage time . A senior security engineer dedicated to SIEM maintenance costs more than many commercial licenses .

- **Resource requirements are real** — Security Onion Standalone needs 24 GB RAM minimum, 32 GB+ recommended . Wazuh single-node handles 5,000-10,000 EPS on 8 vCPU / 16 GB RAM . Size infrastructure before committing.

- **Detection rules require tuning** — Sigma and Wazuh rules produce false positives. Plan for log-only mode before production blocking .

- The open-source ecosystem provides strong SIEM, incident response, and threat hunting foundations, but **curated threat intelligence, managed detection content, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for security analysts, SOC teams, and organizations seeking security investigation sovereignty.**  

Let's make security investigation and threat analysis more open, transparent, and effective.
