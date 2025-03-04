# Log4j overview related software

This page contains an overview of any related software regarding the Log4j vulnerability. On this page NCSC-NL will maintain a list of all known vulnerable and not vulnerable software. Futhermore any reference to the software will contain specific information regarding which version contains the security fixes, and which software still requires mitigation. Please note that this vulnerability may also occur in custom software developed within your organisation. These occurrences are not registered in this overview.

NCSC-NL will use the following status:

| Status         | Description                  |
|:---------------|:-----------------------------|
| Vulnerable     | Software is vulnerable for CVE-2021-44228. |
| Fix            | Software contains a fix for CVE-2021-44228 |
| Workaround | Software is vulnerable but mitigation steps are available |
| Not vuln     | Software is **NOT** vulnerable for CVE-2021-44228. |
| Investigation     | Software is under investigation whether it is vulnerable or not |

The `Version` relates to the `Status` column. If `Status` is Vulnerable, Version indicates vulnerable version(s). If `Status` is Fix, Version indicates the version(s) in which the fix was introduced.

**NCSC-NL has published a HIGH/HIGH advisory for the Log4j vulnerability. Normally we would update the HIGH/HIGH advisory for vulnerable software packages, however due to the extensive amounts of expected updates we have created a list of known vulnerable software in the software directory.**

_Note: daily releases of this software list are listed, including CSV and JSON files, in the [releases](https://github.com/NCSC-NL/log4shell/releases) overview. Please check the [software list parser](https://github.com/NCSC-NL/log4shell/tree/main/tools/log4shell_softwarelist) tool to generate a CSV or JSON on your own._

## Software overview

[0-9](#0-9) [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) [J](#j) [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) [X](#x) [Y](#y) [Z](#z)

### 0-9

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| 1Password     | All      |  | Not vuln |  | [source](https://1password.community/discussion/comment/622612/#Comment_622612) |
| 2Brightsparks | All      |  | Not vuln |  | [source](vendor-statements/2Brightsparks.png) |
| 3CX           | All      |  | Not vuln |  | [source](https://www.3cx.com/community/threads/log4j-vulnerability-cve-2021-44228.86436/post-407835) |
| 7Signal       | Sapphire |  | Fix |Fix released 2021-12-14 | Corresp. with vendor|
| 7-Zip         | All      |  | Not vuln |  | [source](https://sourceforge.net/p/sevenzip/discussion/45797/thread/b977bbd4d1/) |

### A

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| ABB | ABB Remote Service | | Vulnerable | Details are shared with active subscribers | [source](https://search.abb.com/library/Download.aspx?DocumentID=9ADB012621&LanguageCode=en&DocumentPartId=&Action=Launch) |
| ABB | Alarminsight Cloud | | Investigation | Potentially affected as per the advisory | [source](https://search.abb.com/library/Download.aspx?DocumentID=9ADB012621&LanguageCode=en&DocumentPartId=&Action=Launch) |
| ABB | B&R Products | | Not vuln |  | [source](https://www.br-automation.com/downloads_br_productcatalogue/assets/1639507581859-en-original-1.0.pdf) |
| Abbott | All | | Investigation | | [source](https://www.abbott.com/policies/cybersecurity/apache-Log4j.html) |
| Accellence Technologies | vimacc | All | Not vuln | | [source](https://www.accellence.de/en/articles/cve-2021-44228-62) |
| Accellence Technologies | EB&#220;S | All | Workaround | EB&#220;S itself is not vulnerable to CVE-2021-44228. Although it includes several 3rd-partie software setups, which may be affected (see source for more info). | [source](https://www.accellence.de/en/articles/cve-2021-44228-62) |
| Accruent       | Accruent Single Sign On (SSO, Central Auth) | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Analytics | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Asset Enterprise | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | BigCenter | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | EMS | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Evoco | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Expesite | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Famis 360 | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Lucernex | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Maintenance Connection | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Meridian | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | SiteFM3 | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | SiteFM4 | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | Siterra | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | TMS | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | VxField | | Not vuln | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Accruent       | VxMaintain/VxObserve/VxSustain | | Fix | | [source](https://www.accruent.com/resources/articles/incident-apache-log4j2) |
| Acronis       | All |  | Investigation | See further information below| [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Backup | 11.7 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Cyber Backup | 12.5 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Cyber Infrastructure | 3.5 and 4.x | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Cyber Files | 8.6.2 onwards | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Cyber Protect  | 15 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Cyber Protection Home Office | 2017 onwards | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | DeviceLock DLP | 9.0 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Files Connect | 10.7 onwards | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | MassTransit | 8.1 and 8.2 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acronis       | Snap Deploy | 5 and 6 | Not vuln | | [source](https://security-advisory.acronis.com/advisories/SEC-3859) |
| Acunetix | 360 | All | Not Vuln | | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | Application | All | Not Vuln |   | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | Agents | All | Not Vuln |   | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | IAST: NodeJS | All | Not Vuln |   | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | IAST: ASP. NET | All | Not Vuln |   | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | IAST: PHP | All | Not Vuln |   | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Acunetix | IAST: Java | All | Workaround| AcuSensor IAST module needs attention | [source](https://www.acunetix.com/blog/web-security-zone/critical-alert-log4shell-cve-2021-44228-in-log4j-possibly-the-biggest-impact-vulnerability-ever/)  |
| Adobe         | Acrobate Reader | | Not Vuln | | [source](https://community.adobe.com/t5/acrobat-discussions/acrobat-affected-by-apache-log4j-vulnerability-cve-2021-44228/td-p/12590329?profile.language=fr) |
| Adobe         | All | | Investigation | | [source](https://helpx.adobe.com/security/products/log4j-2-advisory.html) |
| Adobe         | Cold Fusion | All | Vulnerable | Fix planned for Dec 17th | [source](https://helpx.adobe.com/coldfusion/kb/log4j-vulnerability-coldfusion.html) |
| ADP           | All | | Investigation | Patching were needed, no signs of intrusion | [source](https://www.adp.com/about-adp/data-security/alerts/adp-vulnerability-statement-apache-log4j-vulnerability-cve-2021-44228-update.aspx) |
| AFAS | All | | Not vuln | | [source](https://help.afas.nl/vraagantwoord/NL/SE/120439.htm) |
| Ahsay | AhsayPRD | version 2.0 | Not vuln | | [source](https://wiki.ahsay.com/doku.php?id=public:announcement:cve-2021-44228_log4j) |
| Ahsay | Mobile | version 1.6+ | Not vuln | | [source](https://wiki.ahsay.com/doku.php?id=public:announcement:cve-2021-44228_log4j) |
| Ahsay | Other products | version 8.5.4.86 (and above) | Not vuln | | [source](https://wiki.ahsay.com/doku.php?id=public:announcement:cve-2021-44228_log4j) |
| Aiden | all | all | Not vuln | | [source](https://www.meetaiden.com/knowledge-base/is-aiden-vulnerable-to-cve-2021-44228-log4j-log4shell/) |
| AIL           | AIL | all | Not vuln | | [source](https://twitter.com/ail_project/status/1470373644279119875) |
| Alexion Software | Alexion CRM | All | Not vuln | | [source](https://alexion.nl/blog/alexion-crm-niet-vatbaar-voor-log4shell) |
| Akamai        | Enterprise Application Access (EAA) connector |  | Not vulnerable |  | Source: Akamai support |
| Akamai        | Siem Splunk Connector | =>1.4.10 | Not vuln |  | [source](https://community.akamai.com/customers/s/feed/0D54R00008Osz7sSAB) (paywall) |
| Akamai        | Siem Splunk Connector | <1.4.10 | Workaround | Akamai SIEM Integration Connector for Splunk is not vulnerable to CVE-2021-44228. Although it includes the vulnerable Log4J component, it is not used by the connector. | [source](https://github.com/akamai/siem-splunk-connector) |
| Alertus        | Console              | 5.15.0| Fix | | [source](https://help.alertus.com/s/article/Security-Advisory-Log4Shell-Vulnerability?language=en_US) |
| Alphatron        | AMiSconnect | | Not Vuln | | [source](https://www.alphatronmedical.com/home.html) |
| Alphatron        | Custo diagnostics  | 5.4 to 5.6 | Vuln | Potentially vulnerable through the HL7 and DICOM communication interfaces | [source](https://www.alphatronmedical.com/home.html) |
| Alphatron        | JiveX | | Not Vuln | | [source](https://www.alphatronmedical.com/home.html) |
| Alphatron        | Zorgbericht | | Not Vuln | | [source](https://www.alphatronmedical.com/home.html) |
| Amazon        | AMS | | Fix | Work in progress, portion of customers may still be vulnerable. Actively monitoring this issue, and are working on addressing it for any AMS services which use Log4j2 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | API Gateway | | Fix | All hosts now patched |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS CloudHSM | 3.4.1 | Fix | CloudHSM JCE SDK 3.4.1 or higher is not vulnerable |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Directory Service | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Elastic Beanstalk | | Not vuln | Default configuration of application's usage of Log4j versions is not vulnerable |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Glue | | Fix | Has been updated. Vulnerable only if ETL jobs load affected versions of Apache Log4j |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Greengrass | | Fix | Updates for all Greengrass V2 components Stream Manager (2.0.14) and Secure Tunneling (1.0.6) are available. For Greengrass versions 1.10.x and 1.11.x, an update for the Stream Manager feature is included in Greengrass patch versions 1.10.5 and 1.11.5 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS IoT SiteWise Edge | | Fix | Updates for all AWS IoT SiteWise Edge components that use Log4j were made available; OPC-UA collector (v2.0.3), Data processing pack (v2.0.14), and Publisher (v2.0.2) |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS KMS | | Fix | AWS KMS has been updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Lambda | | Fix | Vulnerable when using aws-lambda-java-log4j2 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS SDK | | Not vuln | |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | AWS Secrets Manager | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Cloud Directory | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | CloudFront | | Fix | CloudFront services have been updated |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | CloudWatch | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Connect | | Fix | Connect services have been updated |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | DocumentDB | | Fix | Patched to mitigate the Log4j issue referenced in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | DynamoDB | | Fix | DynamoDB and DynamoDB Accelerator have been updated |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | EC2 || Fix | Packages for Amazon Linux 1 and 2 not affected, package for Amazon Linux 2022 is |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/), [fix](https://alas.aws.amazon.com/cve/html/CVE-2021-44228.html) |
| Amazon        | ElastiCache || Fix | Amazon ElastiCache completed patching the Apache Log4j2 issue |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | EMR | | Not vuln | Vulnerable only if affected EMR releases are used and untrusted sources are configured to be processed |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Inspector Classic | | Fix | Patched against the Log4j issue |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Inspector | | Fix | Patched against the Log4j issue |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Kafka (MSK) | | Fix | Applying updates as required, portion of customers may still be vulnerable. Some MSK-specific service components use Log4j > 2.0.0 library and are being patched where needed |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Keyspaces (for Apache Cassandra) | | Fix | Has been updated |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Kinesis Data Analytics | | Fix | Updates are available. See source for more information |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Kinesis Data Streams | | Fix | KCL 2.x, KCL 1.14.5 or higher, and KPL are not vulnerable |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Kinesis | | Fix | Update for Kinesis Agent is available |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Lake Formation | | Fix | Update in progress, portion of customers may still be vulnerable. AWS Lake Formation service hosts are being updated to the latest version of Log4j |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Managed Workflows for Apache Airflow (MWAA) | | Fix | Completed all required updates to the MWAA service code to address the issue |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | MemoryDB for Redis | | Fix | Amazon MemoryDB for Redis completed patching the Apache Log4j2 issue |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | MQ | | Fix | All required updates have been completed |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Neptune | | Fix | All active Amazon Neptune clusters have been automatically updated |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | NICE | | Fix | Recommended to update EnginFrame or Log4j library |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | OpenSearch | R20211203-P2 | Fix | Update released, customers need to update their clusters to the fixed release |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | RDS for Oracle | | Fix | Amazon RDS Oracle has updated the version of Log4j2 in use within the service |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | RDS | | Fix | Update in progress, portion of customers may still be vulnerable. Amazon RDS and Amazon Aurora are actively addressing all service usage of Log4j2 by applying updates |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Redshift | | Fix | Amazon Redshift clusters have been automatically updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | S3| | Fix | All S3 systems are patched |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Simple Notification Service (SNS) | | Fix | Systems that serve customer traffic are patched against the Log4j2 issue. Working to apply the patch to sub-systems that operate separately from SNS’s systems that serve customer traffic. |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Simple Queue Service (SQS) | | Fix | Completed patching. |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Simple Workflow Service (SWF) | | Fix | Amazon Simple Workflow Service (SWF) has been updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Single Sign-On | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Step Functions | | Fix | AWS Step Functions has been updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | Timestream | | Fix | Updated to mitigate the issues identified in CVE-2021-44228 |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| Amazon        | WorkSpaces/AppStream 2.0 | | Fix | Not affected by CVE-2021-44228 with default configurations. WorkDocs Sync client versions 1.2.895.1 and older within Windows WorkSpaces, which contain the Log4j component, are vulnerable; For update instruction, see source for more info |[source](https://aws.amazon.com/security/security-bulletins/AWS-2021-006/) |
| AOMEI         | All Products | | Not Vuln | | [source](https://www.aomeitech.com/forum/index.php?p=/discussion/7651/aomei-and-log4j) |
| Apache        | Archiva | <2.2.6 | Fix | Fixed in 2.2.6 | [source](https://blogs.apache.org/security/entry/cve-2021-44228), [fix](https://lists.apache.org/thread/bmvhs0jxhf4vxcjxyhozm058pchykcqx) |
| Apache        | Camel | all | Not vuln | |[source](https://camel.apache.org/blog/2021/12/log4j2/) |
| Apache        | Cassandra | all | Not vuln | |[source](https://lists.apache.org/thread/2rngylxw8bjos6xbo1krp29m9wn2hhdr) |
| Apache        | Druid | 0.22.1 | Fix | |[source](https://github.com/apache/druid/pull/12051) |
| Apache        | Dubbo | All versions | Fix | |[source](https://github.com/apache/dubbo/issues/9380) |
| Apache        | Flink | 1.15.0, 1.14.2, 1.13.5, 1.12.7, 1.11.6 | Fix | |[source](https://flink.apache.org/news/2021/12/16/log4j-patch-releases.html) |
| Apache        | Fortress | < 2.0.7 | Fix | Fixed in 2.0.7 | [source](https://blogs.apache.org/security/entry/cve-2021-44228)|
| Apache        | Guacamole | All versions | Not vuln | | [source](https://guacamole.apache.org/security/) |
| Apache        | Geode | 1.14.0 | Fix | Fixed in 1.12.6, 1.13.5, 1.14.1 |[source](https://cwiki.apache.org/confluence/plugins/servlet/mobile?contentId=66849544#ReleaseNotes-1.14.1) |
| Apache        | Hadoop | Unknown | Not vuln | Uses log4j 1.x. Are [plans to migrate to log4j2](https://issues.apache.org/jira/plugins/servlet/mobile#issue/HADOOP-12956) but never performed | [source](https://blogs.apache.org/security/entry/cve-2021-44228) |
| Apache        | HBase | Unknown | Vulnerable | Fix is committed, but not yet released |[source](https://github.com/apache/hbase/pull/3933) |
| Apache        | Hive | 4.x | Fix | Fix in 4.x | [source](https://issues.apache.org/jira/browse/HIVE-25795) |
| Apache        | James | 3.6.0 | Vulnerable |  |[source](https://twitter.com/dlitchfield/status/1469809966785564675) |
| Apache        | Jena | < 4.3.1 | Fix | Fixed in 4.3.1 |[source](https://blogs.apache.org/security/entry/cve-2021-44228)|
| Apache        | JMeter | Any | Vulnerable| Manual Bypass |[source](https://github.com/apache/jmeter/pull/680#issuecomment-993204248)|
| Apache        | JSPWiki | 2.11.1 | Fix | |[source](https://jspwiki-wiki.apache.org/Wiki.jsp?page=Log4J-CVE-2021-44228) |
| Apache        | Kafka | All versions | Not vuln | Uses log4j 1.x |[source](https://lists.apache.org/thread/lgbtvvmy68p0059yoyn9qxzosdmx4jdv) |
| Apache        | Karaf | Unknown | Vulnerable | Depends on [PAX logging](https://github.com/ops4j/org.ops4j.pax.logging/issues/414) which is affected |[source](https://mail-archives.apache.org/mod_mbox/karaf-dev/202112.mbox/browser) |
| Apache        | Log4j | 2.16.0 | Fix | |[source](https://logging.apache.org/log4j/2.x/security.html) |
| Apache        | Maven | All Versions | Not Vuln |  |[source](https://blogs.apache.org/security/entry/cve-2021-44228) |
| Apache        | NiFi | All Versions| Fix | Fixed in 1.15.1, 1.16.0 | [source](https://issues.apache.org/jira/browse/NIFI-9474) |
| Apache        | OFBiz | < 18.12.03 | Fix | Fixed in 18.12.03 | [source](https://blogs.apache.org/security/entry/cve-2021-44228) |
| Apache        | Ozone | < 1.2.1 | Fix | Fixed in 1.2.1 | [source](https://blogs.apache.org/security/entry/cve-2021-44228) |
| Apache        | SkyWalking | < 8.9.1 | Fix | Fixed in 8.9.1 | [source](https://blogs.apache.org/security/entry/cve-2021-44228) |
| Apache        | SOLR | 7.4.0 to 7.7.3, 8.0.0 to 8.11.0 | Fix | Fixed in 8.11.1, Versions before 7.4 also vulnerable when using several configurations |[source](https://solr.apache.org/security.html#apache-solr-affected-by-apache-log4j-cve-2021-44228) |
| Apache        | Spark | All versions | Not vuln | Uses log4j 1.x |[source](https://lists.apache.org/thread/wwm13b9764vjms5t8n96j6jklys49cyr) |
| Apache        | Struts | 2.5.28 | Vulnerable |  |[source](https://struts.apache.org/announce-2021#a20211212-2) |
| Apache        | Tapestry | 5.7.3 | Vulnerable | Uses Log4j |[source](https://tapestry.apache.org/logging.html) |
| Apache        | Tika | 2.0.0 and up | Vulnerable | |[source](https://tika.apache.org/2.0.0/index.html) |
| Apache        | Tomcat|| Not vuln|| [source](https://tomcat.apache.org/tomcat-9.0-doc/logging.html) |
| Apache        | TrafficControl | | Vulnerable | | [source](https://blogs.apache.org/security/entry/cve-2021-44228)|
| Apache        | Zookeeper|| Not vuln| Zookeeper uses Log4j 1.2 version | [source](https://issues.apache.org/jira/browse/ZOOKEEPER-4423) |
| APC           | PowerChute Business Edition | 9.5,10.0,10.0.1-10.0.4 | Workaround |  | [source](https://download.schneider-electric.com/files?p_enDocType=Security+and+Safety+Notice&p_File_Name=SESB-2021-347-01_Apache_Log4j_Log4Shell_Vulnerability_Security_Bulletin_V3.0.pdf&p_Doc_Ref=SESB-2021-347-01) |
| APC           | PowerChute Network Shutdown | 4.2-4.4,4.4.1 | Workaround |  | [source](https://download.schneider-electric.com/files?p_enDocType=Security+and+Safety+Notice&p_File_Name=SESB-2021-347-01_Apache_Log4j_Log4Shell_Vulnerability_Security_Bulletin_V3.0.pdf&p_Doc_Ref=SESB-2021-347-01) |
| Apereo        | CAS | 6.3.x & 6.4.x | Fix | Other versions still in active maintainance might need manual inspection |[source](https://apereo.github.io/2021/12/11/log4j-vuln/) |
| Apereo        | Opencast | < 9.10, < 10.6 | Fix | |[source](https://github.com/opencast/opencast/security/advisories/GHSA-mf4f-j588-5xm8) |
| Apigee        | Edge and OPDK products | All version | Not vuln | |[source](https://status.apigee.com/incidents/3cgzb0q2r10p) |
| Appian        | Appian | | Fix | | [source](https://community.appian.com/support/w/kb/2511/kb-2204-information-about-the-log4j2-security-vulnerability-cve-2021-44228) |
| Aptible       | Aptible | Search 5.x | Fix | | [source](https://status.aptible.com/incidents/gk1rh440h36s?u=zfbcrbt2lkv4) |
| Arduino        | Arduino IDE | 1.8.17 | Fix | | [source](https://support.arduino.cc/hc/en-us/articles/4412377144338-Arduino-s-response-to-Log4j2-vulnerability-CVE-2021-44228) |
| Arista Networks | CloudVision Portal | >2019.1.0 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | CloudVision Wi-Fi, virtual appliance or physical appliance | >8.8 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | Analytics Node for DANZ Monitoring Fabric (formerly Big Monitoring Fabric) | >7.0.0 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | Analytics Node for Converged Cloud Fabric (formerly Big Cloud Fabric) | >7.0.0 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | Embedded Analytics for Converged Cloud Fabric (formerly Big Cloud Fabric) | >5.3.0 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | CloudVision Portal | >2019.1.0 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Arista Networks | CloudVision Wi-Fi, virtual appliance or physical appliance | >8.8 | Vulnerable | | [source](https://www.arista.com/en/support/advisories-notices/security-advisories/13425-security-advisory-0070) |
| Atlassian     | Bamboo Server & Data Center | On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Atlassian     | BitBucket Server | On prem | Workaround | | [source](https://community.atlassian.com/t5/Bamboo-questions/Re-log4j-zero-day/qaq-p/1886739/comment-id/30819#M30819) |
| Atlassian     | Confluence Server & Data Center| On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Atlassian     | Crowd Server & Data Center | On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Atlassian     | Crucible | On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Atlassian     | Fisheye | On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Atlassian     | Jira Server & Data Center | On prem | Vulnerable | Only vulnerable when using non-default config, cloud version fixed |[source](https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html) |
| Autodesk     | All | | Not vuln | | [source](https://www.autodesk.com/trust/overview) |
| Avaya         | | | | | [source](https://support.avaya.com/helpcenter/getGenericDetails?detailId=1399839287609) |
| AVM           | all products | devices, firmware, software incl. MyFritz Service | Not Vuln |  | [source](https://en.avm.de/service/current-security-notifications/) |
| AXIS          | AXIS OS | All versions | Not Vuln | | [source](https://help.axis.com/axis-os) |

### B

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Backblaze      | Cloud | N/A (SaaS) | Fix | Cloud service patched |[source](https://help.backblaze.com/hc/en-us/articles/4412580603419) |
| Barco          | Demetra | | Investigation | | [source](https://www.barco.com/en/support/knowledge-base/KB12495) |
| Barco          | Other products | | Not vuln | | [source](https://www.barco.com/en/support/knowledge-base/KB12495) |
| Barco          | Projector Toolset | | Investigation | | [source](https://www.barco.com/en/support/knowledge-base/KB12495) |
| Basis Technology | Autopsy | 4.18.0 onwards | Workaround | version 4.18.0 onwards use Apache Solr 8 | [source](https://www.autopsy.com/autopsy-and-log4j-vulnerability) |
| Bender GmbH und Co. KG | All | | Not vuln | | [source](https://www.bender.de/en/cert) |
| B. Braun       | All | | Not vuln | | [source](https://www.bbraun.com/en/products-and-therapies/services/b-braun-vulnerability-disclosure-policy/security-advisory/b-braun-statement-on-Apache_Log4j.html) |
| BD             | Arctic Sun Analytics | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Diabetes Care App Cloud | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Clinical Advisor | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Data Manager | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Diversion Management | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Infection Advisor | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Inventory Optimization Analytics | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | HealthSight Medication Safety | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Knowledge Portal for Infusion Technologies | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Knowledge Portal for Medication Technologies | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Knowledge Portal for BD Pyxis Supply | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Synapsys Informatics Solution | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BD             | Veritor COVID At Home Solution Cloud | | Not vuln | | [source](https://cybersecurity.bd.com/bulletins-and-patches/third-party-vulnerability-apache-log4j) |
| BeyondTrust    | Privilege Management Cloud | Unknown | Not vuln | | [source](https://beyondtrustcorp.service-now.com/kb_view.do?sysparm_article=KB0016542) |
| BeyondTrust    | Privilege Management Reporting | Unknown | Not vuln | | [source](https://beyondtrustcorp.service-now.com/kb_view.do?sysparm_article=KB0016542) |
| BigBlueButton   | BigBlueButton | Unknown | Not vuln | |[source](https://github.com/bigbluebutton/bigbluebutton/issues/13897) |
| Bitdefender   | GravityZone On-Premises | Unknown | Not vuln | |[source](https://businessinsights.bitdefender.com/security-advisory-bitdefender-response-to-critical-0-day-apache-log4j2-vulnerability) |
| Bitnami       | Unknown | Unknown | Fix | |[source](https://docs.bitnami.com/general/security/security-2021-12-10/) |
| Bitwarden     | Bitwarden | All | Not Vuln | | [source](https://community.bitwarden.com/t/log4j-log4shell-cve-is-bitwarden-affected-due-to-docker-image/36177) |
| BioJava       | Java library for processing biological data | 6.0.3 | Fix | |[source](https://github.com/biojava/biojava/releases/tag/biojava-6.0.3) |
| BlackBerry    | Enterprise Mobility Server | 2.12 and above | Workaround | |[source](https://support.blackberry.com/community/s/article/90708) |
| BlackBerry    | Workspaces On-prem Server | All | Workaround | |[source](https://support.blackberry.com/community/s/article/90708) |
| BlackBerry    |  2FA | All | Workaround | |[source](https://support.blackberry.com/community/s/article/90708) |
| Bluemind    |  All | 3.5.x and 4.x | Not vuln | |[source](https://twitter.com/bluemind/status/1470379923034578946?s=20) |
| BMC Software  | 3270 SUPEROPTIMIZER/CICS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Application Restart Control for Db2    | | Not vuln | |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Application Restart Control for IMS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Application Restart Control for VSAM    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Bladelogic Database Automation   | | Vulnerable | Fix expected on Dec 15th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Batch Optimizer    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Capacity Management    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Command Center for Security    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Console management      | | Not vuln  | |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Cost Management    | | Not vuln | |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Datastream for Ops    | | Not vuln | |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender for Db2    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender for Ops Insight    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender for z/Linux    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender for z/OS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender for z/VM    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Defender TCP/IP Receiver    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Enterprise Connector    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Automation for Capping    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Common Rest API (CRA) | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops for Networks    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Infrastructure (MVI) - CRA component | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Insight | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor for CMF    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor for IMS Offline    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor for IMS Online    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor for USS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor for z/OS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops Monitor SYSPROG Services    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Ops UI  | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Recovery for VSAM    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Security Administrator    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Security Policy Manager    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Security Privileged Access Manager (also called BMC AMI Security Breakglass)    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Security Self Service Password Reset    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Storage    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC AMI Utilities    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Client Management | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Abend-Aid    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Application Audit    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware DevEnterprise    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Enterprise Common Components (ECC)    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Enterprise Services (CES)    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Enterprise Services    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID Data Privacy    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID Data Solutions    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID for DB2    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID for IMS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID/MVS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware File-AID/RDX    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Hiperstation ALL Product Offerings    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware ISPW    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware iStrobe    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Program Analyzer    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Storage Backup and Recovery    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Storage Migration    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Storage Performance    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware ThruPut Manager    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Topaz Enterprise Data    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Topaz for Java Performance    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Topaz for Total Test    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Topaz Program Analysis    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Topaz Workbench    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Xpediter/CICS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Xpediter/Code Coverage    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Xpediter/TSO and IMS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware Xpediter/Xchange    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Compuware zAdviser    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Db2 Admin    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Db2 SQL Performance    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender Agent Configuration Manager    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender Agent for SAP    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender Agent for Unix/Linux    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender Agent for Windows    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender App for Splunk    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender SIEM Correlation Server    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender SIEM for Motorola    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender SIEM for NNT    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender SyslogDefender    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Defender Windows Agent for Splunk    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Discovery | | Fix | Fix available in BMC’s Electronic Product Download site (EPD) |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Helix Continuous Optimization – Agents    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Helix Continuous Optimization | | Vulnerable | Fix expected on Dec 15th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Helix Knowledge Management    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC License Usage Collection Utility | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Plus Utilities    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | BMC Recovery Management – BMC AMI LogMaster, Recovery Manager, Copy, Recover    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Cloud Lifecycle Management    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | CMDB | | Vulnerable |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Common Components: Next Generation Logger (NGL), Runtime Component System (RTCS), User Interface Middleware (UIM)    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Control-M | | Vulnerable |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | ExceptionReporter    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Footprints    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Helix Data Manager | | Vulnerable |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | KMs - Sybase KM & Linux (RHEV) | | Fix | Fix available in BMC’s Electronic Product Download site (EPD)   |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | MainView Explorer    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | MainView Middleware Administrator    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | MainView Middleware Monitor | | Vulnerable | Fix expected on Dec 20th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | MainView Transaction Analyzer    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | PATROL Agent    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Release Process Management    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Remedy ITSM (IT Service Management)    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Remedy Smart Reporting | | Vulnerable |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Resident Security Server    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | Track-It!    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight App Visibility Manager | | Vulnerable | Fix expected on Dec 15th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Automation Console | | Vulnerable | Fix expected on Dec 17th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Automation for Networks | | Vulnerable | Fix expected on Dec 13th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Automation for Servers - Data Warehouse | | Vulnerable | Fix expected on Dec 17th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Automation for Servers | | Vulnerable | Fix expected on Dec 17th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Capacity Optimization – Agents    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Capacity Optimization    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Infrastructure Management | | Vulnerable |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight IT Data Analytics | | Vulnerable | Fix expected on Dec 15th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Operations Management | | Vulnerable | Fix expected on Dec 16th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Orchestration    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TrueSight Smart Reporting | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TSCO For Mainframes    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | TSOM Smart Reporting | | Vulnerable | Fix expected on Dec 14th |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | ULTRAOPT/CICS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | ULTRAOPT/IMS    | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| BMC Software  | zDetect  | | Not vuln |  |[source](https://community.bmc.com/s/news/aA33n000000TSUdCAO/bmc-security-advisory-for-cve202144228-log4shell-vulnerability) |
| Brian Pangburn | SwingSet | < 4.0.6 | Fix | |[source](https://github.com/bpangburn/swingset/releases/tag/swingset-4.0.6) |
| Broadcom      | Advanced Secure Gateway (ASG) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | BCAAA | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | CA Advanced Authentication | 9.1 & 9.1.01 & 9.1.02 | Workaround | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | CloudSOC Cloud Access Security Broker (CASB) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Cloud Workload Assurance (CWA) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Cloud Workload Protection (CWP) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Cloud Workload Protection for Storage (CWP:S) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Cloud Workload Protection for Storage (CWP:S) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Content Analysis (CA)(SEPM) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Critical System Protection (CSP) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Data Center Security (DCS) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Data Loss Prevention (DLP) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Email Security Service (ESS) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Ghost Solution Suite (GSS) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | HSM Agent | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Industrial Control System Protection (ICSP) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Information Centric Analytics (ICA) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Integrated Cyber Defense Exchange (ICDx) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Integrated Cyber Defense Manager (ICDm) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Integrated Secure Gateway (ISG) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | IT Analytics (ITA) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | IT Management Suite | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | IT Management Suite | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Layer7 API Developer Portal | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Layer7 API Gateway | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Layer7 API Gateway | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Layer7 Mobile API Gateway | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Layer7 Mobile API Gateway | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | LiveUpdate Administrator (LUA) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Management Center (MC) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | PacketShaper (PS) S-Series | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | PolicyCenter (PC) S-Series | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Privileged Access Manager Server Control | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Privileged Access Manager | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Privileged Identity Manager | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | ProxySG | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | ProxySG | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Reporter | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Secure Access Cloud (SAC) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Security Analytics (SA) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Security Analytics (SA) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | ServiceDesk | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | SiteMinder (CA Single Sign-On) | 12.8.x Policy Server, 12.8.04 or later Administrative UI, 12.8.x Access Gateway, 12.8.x SDK, 12.7 and 12.8 ASA Agents | Fix, Workaround | |[source](https://knowledge.broadcom.com/external/article?articleId=230270) |
| Broadcom      | SSL Visibility (SSLV)| Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Control Compliance Suite (CCS) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Control Compliance Suite (CCS) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Directory | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Directory | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Detection and Response (EDR) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Encryption (SEE) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Protection Manager (SEPM) | 14.3 | Workaround | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Protection (SEP) Agent | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Protection (SEP) for Mobile| Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Endpoint Protection (SEP)| Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Identity Governance and Administration (IGA)| Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Mail Security for Microsoft Exchange (SMSMSE) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Messaging Gateway (SMG) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec PGP Solutions | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Protection Engine (SPE) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Symantec Protection for SharePoint Servers (SPSS) | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | VIP Authentication Hub | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | VIP | Unknown | Not vuln | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Web Isolation (WI) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | WebPulse | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |
| Broadcom      | Web Security Service (WSS)) | Unknown | Investigation | |[source](https://support.broadcom.com/security-advisory/content/security-advisories/Symantec-Security-Advisory-for-Log4j-2-CVE-2021-44228-Vulnerability/SYMSA19793) |

### C

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Carbon Black | Cloud Workload Appliance | Unknown | Mitigation | More information on pages linked bottom of blogpost (behind login)| [source](https://community.carbonblack.com/t5/Documentation-Downloads/Log4Shell-Log4j-Remote-Code-Execution-CVE-2021-44228/ta-p/109134) |
| Carbon Black | EDR Servers| Unknown | Mitigation | More information on pages linked bottom of blogpost (behind login)| [source](https://community.carbonblack.com/t5/Documentation-Downloads/Log4Shell-Log4j-Remote-Code-Execution-CVE-2021-44228/ta-p/109134) |
| CareStream | All | | Not vuln | | [source](https://www.carestream.com/en/us/services-and-support/cybersecurity-and-privacy) |
| CaseWare | Cloud | All | Fix | |[source](https://www.caseware.com/case-knowledge/caseware-ensuring-customers-protected-log4j-vulnerabilities) |
| CaseWare | IDEA | All | Not vuln | |[source](https://www.caseware.com/case-knowledge/caseware-ensuring-customers-protected-log4j-vulnerabilities) |
| CaseWare | WorkingPapers | All | Not vuln | |[source](https://www.caseware.com/case-knowledge/caseware-ensuring-customers-protected-log4j-vulnerabilities) |
| Catalogic | CloudCasa | All | Not vuln | |[source](https://cloudcasa.io/forum/topic/no-apache-log4j-issues-in-cloudcasa) |
| Cepheid | C360 | | Not vuln | | [source](https://www.cepheid.com/en_US/legal/product-security-updates) |
| Cepheid | GeneXpert | | Investigation | | [source](https://www.cepheid.com/en_US/legal/product-security-updates) |
| Cerebro | Cerebro Elasticsearch Web Admin | All | Not vuln | Uses logback for logging |[source](https://github.com/lmenezes/cerebro/blob/main/conf/logback.xml#L5) |
| Cerberus | FTP | Unknown | Not vuln | |[source](https://support.cerberusftp.com/hc/en-us/articles/4412448183571-Cerberus-is-not-affected-by-CVE-2021-44228-log4j-0-day-vulnerability) |
| Cerebrate | Cerebrate | All | Not vuln | |[source](https://twitter.com/cerebrateproje1/status/1470347775141421058) |
| Chaser Systems | discrimiNAT Firewall | All | Not vuln | | [source](https://chasersystems.com/discrimiNAT/blog/log4shell-and-its-traces-in-a-network-egress-filter/#are-chasers-products-affected) |
| Check Point | Quantum Security Gateway | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point | Quantum Security Management | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point| CloudGuard | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point | Infinity Portal | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point | Harmony Endpoint & Harmony Mobile | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point | SMB | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Check Point | ThreatCloud | All | Not vuln | |[source](https://supportcontent.checkpoint.com/solutions?id=sk176865) |
| Chef | Infra Server | All | Not vuln | | [source](https://www.chef.io/blog/is-chef-vulnerable-to-cve-2021-44228-(log4j))|
| Chef | Automate | All | Not vuln | | [source](https://www.chef.io/blog/is-chef-vulnerable-to-cve-2021-44228-(log4j))|
| Chef | Backend | All | Not vuln | | [source](https://www.chef.io/blog/is-chef-vulnerable-to-cve-2021-44228-(log4j))|
| Cisco | General Cisco Disclaimer | Cisco is updating their advisory three times a day, please keep their website in your watchlist. We will try to update accordingly ||||
| Cisco |ACI Multi-Site Orchestrator|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |ACI Virtual Edge|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Adaptive Security Appliance (ASA) Software|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Adaptive Security Device Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Advanced Web Security Reporting Application|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1560 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1810 Series OfficeExtend Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1810w Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1815 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1830 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 1850 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 2800 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Aironet 3800 Series Access Points|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |AMP Virtual Private Cloud Appliance|Unknown|Vulnerable|Fixes expecteded 10-Jan-2022|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | AnyConnect Secure Mobility Client | All versions | Not vuln | | [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |AppDynamics |<21.12.0|Fix||[source](https://docs.appdynamics.com/display/PAA/Security+Advisory%3A+Apache+Log4j+Vulnerability) |
| Cisco |Application Policy Infrastructure Controller (APIC)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |ASR 5000 Series Routers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Broadcloud Calling|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |BroadWorks|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Business Process Automation|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Catalyst 9800 Series Wireless Controllers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |CloudCenter Action Orchestrator|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |CloudCenter Suite Admin|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |CloudCenter Workload Manager|Unknown|Vulnerable|Fixes expecteded 23-Dec-2021|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Cloud Email Security|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Cloud Services Platform 2100|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Cloud Services Platform 5000 Series|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Cognitive Intelligence|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Common Services Platform Collector|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Computer Telephony Integration Object Server (CTIOS)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |ConfD|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Connected Grid Device Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Connected Mobile Experiences|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Connectivity|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Contact Center Domain Manager (CCDM)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Contact Center Management Portal (CCMP)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Container Platform|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Content Security Management Appliance (SMA)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Crosswork Change Automation|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |CX Cloud Agent Software|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Data Center Network Manager (DCNM)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Defense Orchestrator|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |DNA Assurance|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |DNA Center|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |DNA Spaces|2.5, 2.8.2, 2.11.0, 2.13.3|Fix||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Duo| Unknown | Fix || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Elastic Services Controller (ESC)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Email Security Appliance (ESA)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Emergency Responder|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Enterprise Chat and Email|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Enterprise NFV Infrastructure Software (NFVIS)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Evolved Programmable Network Manager| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Exony Virtualized Interaction Manager (VIM)|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Expressway Series|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Extensible Network Controller (XNC)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Finesse|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Firepower 4100 Series|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Firepower 9300 Security Appliances|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Firepower Management Center|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Firepower Threat Defense (FTD)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |GGSN Gateway GPRS Support Node|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Hosted Collaboration Mediation Fulfillment|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |HyperFlex System|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Identity Services Engine (ISE)|2.4, 2.6|Vulnerable|Fix expected on Dec 17th|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Identity Services Engine (ISE)|2.7, 3.0|Vulnerable|Fix expected on Dec 16th|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Identity Services Engine (ISE)|3.1|Vulnerable|Fix expected on Dec 18th|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Integrated Management Controller (IMC) Supervisor| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Intersight|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Intersight Virtual Appliance| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |IOS and IOS XE Software|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |IOS XR Software|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |IoT Field Network Director (formerly Cisco Connected Grid Network Management System)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |IoT Operations Dashboard|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |IOx Fog Director|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |IP Services Gateway (IPSG)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Jabber Guest|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Kinetic for Cities|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Managed Services Accelerator (MSX) Network Access Control Service|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |MDS 9000 Series Multilayer Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Meeting Server|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco | Meraki GO |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki MR |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki MS |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki MT |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki MV |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki MX |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki System Manager |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco | Meraki Z-Series |Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |MME Mobility Management Entity|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Mobility Services Engine|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Mobility Unified Reporting and Analytics System|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Modeling Labs|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Network Assessment (CNA) Tool|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Network Assurance Engine|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Network Convergence System 2000 Series|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Network Planner|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Network Services Orchestrator (NSO)|< nso-5.3.5.1, nso-5.4.5.2, nso-5.5.4.1, nso-5.6.3.1|Vulnerable|Fixes expected 17-Dec|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 3000 Series Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Nexus 5500 Platform Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 5600 Platform Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 6000 Series Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 7000 Series Switches|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 9000 Series Fabric Switches in Application Centric Infrastructure (ACI) mode|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus 9000 Series Switches in standalone NX-OS mode|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Nexus Dashboard (formerly Cisco Application Services Engine)|<2.1.2|Vulnerable|Fixes expected 7-Jan-2022|[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus Data Broker|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Nexus Insights|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Optical Network Planner|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Packaged Contact Center Enterprise|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Paging Server (InformaCast)|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Paging Server|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |PDSN/HA Packet Data Serving Node and Home Agent|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |PGW Packet Data Network Gateway|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Policy Suite|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Access Registrar|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime Cable Provisioning|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime Central for Service Providers|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Collaboration Assurance|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Collaboration Deployment|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime Collaboration Manager|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Collaboration Provisioning|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Infrastructure|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime IP Express|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime License Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Network|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime Network Registrar|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Optical for Service Providers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Performance Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Prime Provisioning|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Prime Service Catalog|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Registered Envelope Service|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |SD-WAN vEdge 1000 Series Routers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |SD-WAN vEdge 2000 Series Routers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |SD-WAN vEdge 5000 Series Routers|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |SD-WAN vEdge Cloud Router Platform|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |SD-WAN vManage|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Secure Network Analytics (SNA), formerly Stealthwatch|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Security Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Smart Software Manager On-Prem|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |SocialMiner|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |System Architecture Evolution Gateway (SAEGW)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |TelePresence Management Suite|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |TelePresence Video Communication Server (VCS)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Tetration Analytics|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |UCS Central Software|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |UCS C-Series Rack Servers - Integrated Management Controller|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |UCS Director| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |UCS Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |UCS Performance Manager|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Ultra Packet Core|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Umbrella|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Attendant Console Advanced|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Attendant Console Business Edition|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Attendant Console Department Edition|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Attendant Console Enterprise Edition|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Attendant Console Premium Edition|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Communications Domain Manager|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Communications Manager / Cisco Unified Communications Manager Session Management Edition|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Communications Manager Cloud| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Communications Manager IM & Presence Service (formerly CUPS)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Contact Center Enterprise - Live Data server| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Contact Center Enterprise|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Contact Center Express|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Customer Voice Portal|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified Intelligence Center|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unified Intelligent Contact Management Enterprise|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unified SIP Proxy Software|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Unity Connection|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Unity Express|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Video Surveillance Media Server|Unknown| Not vuln || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Video Surveillance Operations Manager| <7.14.4 | Vulnerable | Fixes expected 16-Dec-2021 | [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Virtualized Voice Browser|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Virtual Topology System - Virtual Topology Controller (VTC) VM|Unknown|Investigation||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Vision Dynamic Signage Director|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |WAN Automation Engine (WAE)|Unknown|Vulnerable||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Webex App| Unknown | Not vuln || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Webex Cloud-Connected UC (CCUC)| Unknown | Vulnerable || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Webex Meetings Server | CWMS-3.0MR4SP2, CWMS-4.0MR4SP2 | Vulnerable | Fixes expecteded 14-Dec-2021 | [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Webex Room Phone| Unknown | Not vuln || [source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd) |
| Cisco |Web Security Appliance (WSA)|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Wide Area Application Services (WAAS)|All versions|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| Cisco |Cisco Wireless LAN Controller|Unknown|Not vuln||[source](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-apache-log4j-qRuKNEbd)|
| CIS-CAT|CSAT Pro| < 1.7.1 |Vulnerable|Upgrade to v1.7.1 to be released 16/12|[source](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2434301961) |
| CIS-CAT|CIS-CAT Pro Assessor v4| < 4.13.0 |Vulnerable|Upgrade to v4.13.0 to be released 16/12|[source](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2434301961) |
| CIS-CAT|CIS-CAT Pro Assessor Service v4| < 1.13.0 |Vulnerable|Upgrade to v1.13.0 to be released 16/12|[source](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2434301961) |
| CIS-CAT|CIS-CAT Pro Assessor v3| < 3.0.77 |Vulnerable| Upgrade to v3.0.77 to be released 16/12|[source](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2434301961) |
| CIS-CAT|CIS-CAT Pro Dashboard| All| Not vuln||[source](https://cisecurity.atlassian.net/servicedesk/customer/portal/15/article/2434301961) |
| Citrix | Analytics | Unknown | Investigation |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Application Delivery Management (NetScaler MAS)  | All versions | Not vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Endpoint Management (XenMobile Server)  | 10.12 RP10, 10.13 RP5 and 10.14 RP2 | Fix |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Hypervisor (XenServer)   | Unknown | Not Vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | NetScaler ADC | All versions | Not vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | NetScaler Gateway | All versions | Not vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | SD-WAN  | All versions | Not vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Sharefile  | Unknown | Not vuln  |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Virtual Apps and Desktops (XenApp & XenDesktop) | Unknown | Investigation | Not vulnerable: App Layering, Delivery Controller, Director, FAS, HDX, Profile Management, PVS, Session Recording, Storefront, Studio, Windows VDA, WEM | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Workspace App  | All versions | Not vuln |  | [source](https://support.citrix.com/article/CTX335705) |
| Citrix | Workspace  | Unknown | Not vuln  |  | [source](https://support.citrix.com/article/CTX335705) |
| Clavister    | NetWall | - | Not vuln  |  | [source](https://www.clavister.com/advisories/security/clav-sa-0297-high-severity-vulnerability-in-apache-log4j-2) |
| Clavister    | NetShield  | - | Not vuln  |  | [source](https://www.clavister.com/advisories/security/clav-sa-0297-high-severity-vulnerability-in-apache-log4j-2) |
| Clavister    | InControl  | - | Not vuln  |  | [source](https://www.clavister.com/advisories/security/clav-sa-0297-high-severity-vulnerability-in-apache-log4j-2) |
| Clavister    | OneConnect  | - | Vulnerable  | Fixed | [source](https://www.clavister.com/advisories/security/clav-sa-0297-high-severity-vulnerability-in-apache-log4j-2) |
| Clavister    | EasyAccess  | <= 4.1.2 | Vulnerable  | See link for fix | [source](https://kb.clavister.com/343410234/high-severity-vulnerability-in-apache-log4j-2) |
| Clavister    | InCenter  | <= 1.68.03, 2.0.0 and 2.1.0 | Vulnerable  | See link for fix | [source](https://kb.clavister.com/343410462/vulnerability-in-apache-log4j-2-which-is-used-in-incenter) |
| Cockroach Labs | CockroachDB | - | Not vuln | | [source](https://www.cockroachlabs.com/docs/advisories/acve-2021-44228#statement) |
| CODESYS | all | all | Not vuln  || [source](https://www.codesys.com/news-events/news/article/log4j-not-used-in-codesys.html) |
| Commvault | Cloud Apps & Oracle & MS-SQL | All supported versions | Fix || [source](https://documentation.commvault.com/11.24/essential/146231_security_vulnerability_and_reporting.html) |
| Compumatica | CryptoGuard | all | Not vuln | | [source](https://www.compumatica.com/nieuws-bericht/important-information-log4j-vulnerability-compumatica-secure-networks/) |
| Compumatica | CompuMail Gateway | all | Not vuln | | [source](https://www.compumatica.com/nieuws-bericht/important-information-log4j-vulnerability-compumatica-secure-networks/) |
| Compumatica | Compuwall | all | Not vuln | | [source](https://www.compumatica.com/nieuws-bericht/important-information-log4j-vulnerability-compumatica-secure-networks/) |
| Compumatica | MagiCtwin | all | Not vuln | | [source](https://www.compumatica.com/nieuws-bericht/important-information-log4j-vulnerability-compumatica-secure-networks/) |
| Compumatica | MASC | all | Not vuln | | [source](https://www.compumatica.com/nieuws-bericht/important-information-log4j-vulnerability-compumatica-secure-networks/) |
| Confluence | CIS CSAT Pro | v1.7.1 | Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS WorkBench | | Not Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-CAT Lite | v4.13.0 | Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-CAT Pro Assessor v3 Full and Dissolvable | v3.0.77 | Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-CAT Pro Assessor v4 | v4.13.0 | Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-CAT Pro Assessor v4 Service | v1.13.0 | Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-CAT Pro Dashboard | | Not Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluence | CIS-Hosted CSAT | | Not Vuln | | [source](https://cisecurity.atlassian.net/wiki/spaces/SCFKB/pages/2434301961/CIS+Products+and+Log4j+Vulnerability) |
| Confluent | Confluent Cloud | | Fix | server-side fix | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Confluent | Confluent Community Platform | | Not vuln | | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Confluent | Confluent Platform | 7.0.1 | Fix | | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Confluent | Confluent for Kubernetes | 2.1.0-1 and 2.2.0-1 | Fix | Only applicable to confluent-init-container | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Confluent | Confluent Connectors | see link | Fix | List of vulnerable connectors available at Confluent | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Confluent | Community/Standalone Package of ksqlDB |  | Not vuln | No exploitable conditions found, working on package without log4j2 | [source](https://support.confluent.io/hc/en-us/articles/4412615410580-CVE-2021-44228-log4j2-vulnerability) |
| Connect2id | Connect2id server | < 12.5.1 | Fix || [source](https://connect2id.com/blog/connect2id-server-12-5-1) |
| Connectwise | Global search capability of Manage Cloud | Unknown | Mitigation || [source](https://www.connectwise.com/company/trust/advisories) |
| Connectwise | Manage on-premise's Global Search  | Unknown | Mitigation || [source](https://www.connectwise.com/company/trust/advisories) |
| Connectwise | Marketplace | Unknown | Mitigation || [source](https://www.connectwise.com/company/trust/advisories) |
| Connectwise | Perch | Unknown | Fix || [source](https://www.connectwise.com/company/trust/advisories) |
| Connectwise | StratoZen | Unknown | Mitigation | Urgent action for self-hosted versions |[source](https://www.connectwise.com/company/trust/advisories) |
| Contrast | Hosted SaaS Enviroments | All | Fix | |[source](https://support.contrastsecurity.com/hc/en-us/articles/4412612486548) |
| Contrast | Java Agent | All | Not vuln | |[source](https://support.contrastsecurity.com/hc/en-us/articles/4412612486548) |
| Contrast | On-premises (EOP) Environments | All | Fix/Mitigation | |[source](https://support.contrastsecurity.com/hc/en-us/articles/4412612486548) |
| Contrast | Scan | All | Fix | |[source](https://support.contrastsecurity.com/hc/en-us/articles/4412612486548) |
| ControlUp | All products | All versions | Fix | |[source](https://status.controlup.com/incidents/qqyvh7b1dz8k) |
| Copadata | Zenon product family | All | Not vuln | |[source](https://www.copadata.com/en/support-services/knowledge-base-faq/pare-products-in-the-zenon-product-family-affect-4921/) |
| Coralogix | Coralogix | Unknown | Fix | |[source](https://status.coralogix.com/incidents/zzfn8t0fzdy2?u=1q9952ycm1gr) |
| Couchbase | Couchbase ElasticSearch connector| < 4.3.3 & < 4.2.13 | Fix | |[source](https://forums.couchbase.com/t/ann-elasticsearch-connector-4-3-3-4-2-13-fixes-log4j-vulnerability/32402) |
| cPanel | cPanel | Unknown | Mitigation | | [source](https://forums.cpanel.net/threads/log4j-cve-2021-44228-does-it-affect-cpanel.696249/) |
| Cryptshare | Cryptshare for Notes | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare for NTA 7516 | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare for Outlook | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare Java API | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare .NET API | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare Robot | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cryptshare | Cryptshare Server | All | Not vuln | |[source](https://www.cryptshare.com/nl/support/cryptshare-support/) |
| Cyberark  | Cloud Entitlements Manager || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Endpoint Privilege Manager (EPM) - Agents || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Endpoint Privilege Manager (EPM) - EPM Server (On-Premise) || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Endpoint Privilege Manager (EPM) - Service (SaaS) || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | HTML5 Gateway || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Identity - Mobile App || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Identity - On-Premise Components || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Identity - Secure Web Sessions (SWS) || Fix | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Identity - Service (SaaS) || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Legacy Sensitive Information Management (SIM) || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Marketplace components - Certified and Trusted Marketplace Components || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Marketplace components - CPM Plugins || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Marketplace components - PSM Connection Components || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | On-Demand Privileges Manager (OPM) || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | PAS Self Hosted (Vault, PVWA, CPM, PSM, PSMP) || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Privilege Cloud - On-Premise Components || Not Vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Privilege Cloud - Service (SaaS) || Fix | Mitigation applied. No further action required by customers | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Privileged Threat Analytics (PTA) || Workaround | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228), [workaround](https://cyberark-customers.force.com/s/article/PTA-CVE-2021-44228-Mitigation-for-Privilege-Threat-Analytics) |
| Cyberark  | Remote Access (Alero) - Connector || Fix | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Remote Access (Alero) - Mobile App || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Remote Access (Alero) - Service (SaaS) || Fix | Mitigation applied. No further action required by customers | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Secrets Manager Conjur Enterprise || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cyberark  | Secrets Manager Credential Providers || Not vuln | | [source](https://cyberark-customers.force.com/s/article/Critical-Vulnerability-CVE-2021-44228) |
| Cybereason | All Cybereason products | Unknown | Not vuln | |[source](https://www.cybereason.com/blog/cybereason-solutions-are-not-impacted-by-apache-log4j-vulnerability-cve-2021-44228) |

### D

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| DatadogHQ | Datadog Agent | 6 < [6.32.2](https://github.com/DataDog/datadog-agent/releases/tag/6.32.2), 7 < [7.32.2](https://github.com/DataDog/datadog-agent/releases/tag/7.32.2) | Fix/workaround | JMX monitoring component leverages an impacted version of log4j | [source](vendor-statements/DatadogHQ%20-%20Our_response_to_log4j_vulnerability.pdf) |
| DataNet Quality Systems | WinSPC | | Not vuln | Note: this is not **WinSCP**. This is a Statistical Process Control software. | Email from customer support. See vendor-statements folder. |
| Datev | All Datev products | Unknown | Vulnerable | german source |[source](https://www.datev-community.de/t5/Freie-Themen/Log4-J-Schwachstelle/td-p/258147) |
| Dataverse | The Dataverse Project | | Vulnerable || [source](dataverse.org) |
| Datto | All Datto products | Unknown | Not vuln | |[source](https://www.datto.com/blog/dattos-response-to-log4shell) |
| Datto | All Datto products | Unknown | Not vuln | |[source](https://www.datto.com/blog/dattos-response-to-log4shell) |
| DBeaver | DBeaver | Unknown | Not vuln | |[source](https://dbeaver.io/2021/12/15/log4shell-vulnerability-is-not-dangerous-for-dbeaver-users/) |
| Debian | Apache-log4j.1.2 | stretch, buster,  bullseye | Fix| |[source](https://security-tracker.debian.org/tracker/CVE-2021-44228) |
| Debian | Apache-log4j2 | stretch, buster,  bullseye | Fix| |[source](https://security-tracker.debian.org/tracker/CVE-2021-44228) |
| Dell | Alienware Command Center | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Alienware OC Controls | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Alienware On Screen Display | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Alienware Update | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | APEX Console | Unknown | Vulnerable | Cloud environment patch in progress | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | APEX Data Storage Services | Unknown | Vulnerable | Cloud environment patch in progress | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Atmos | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Cloud IQ | Unknown | Vulnerable | Cloud environment patch in progress | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | BSAFE Crypto-C Micro Edition | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | BSAFE Crypto-J | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | BSAFE Micro Edition Suite | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Centera | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Chassis Management Controller (CMC) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Cloud Mobility for Dell EMC Storage | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Cloudlink | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Data Domain OS | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Disk Library for Mainframe | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Embedded NAS | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Avamar | Unknown | Vulnerable | See [DSA-2021-277](https://www.dell.com/support/kbdoc/en-us/000194480/dsa-2021-277-dell-emc-avamar-update-for-apache-log4j-remote-code-execution-vulnerability-cve-2021-44228) | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Cloud Disaster Recovery | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC DataIQ | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Data Protection Central | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Data Protection Search | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC ECS | Unknown | Vulnerable | Patch expected 12/17 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Enterprise Storage Analytics for vRealize Operations | Unknown | Fix | See [DSA-2021-278](https://www.dell.com/support/kbdoc/en-us/000194488/dsa-2021-278) | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Integrated System for Microsoft Azure Stack Hub | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC License Manager | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC NetWorker | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC NetWorker VE | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Networking Onie | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC ObjectScale | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerFlex Appliance | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerFlex Manager | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerFlex Rack | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerMax | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerPath | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerPath Management Appliance | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerProtect Cyber Recovery | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerProtect Data Manager | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerProtect DP Series Appliance (iDPA) | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerScale OneFS | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerShell for PowerMax | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerShell for Powerstore | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerShell for Unity | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC PowerStore | Unknown | Vulnerable | Patch expected 12/31 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC RecoverPoint | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Repository Manager (DRM) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC SourceOne | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC SRM vApp | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Streaming Data Platform | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Systems Update (DSU) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Unity | Unknown | Vulnerable | Patch expected 12/31 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC Virtual Storage Integrator | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC VPLEX | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC VxRail | Unknown | Vulnerable | See [DSA-2021-265](https://www.dell.com/support/kbdoc/en-us/000194466/dsa-2021-265-dell-emc-vxrail-security-update-for-apache-log4j-remote-code-execution-vulnerability-cve-2021-44228) | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | EMC XtremIO | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Enterprise Hybrid Cloud | Unknown | Vulnerable | See [DSA-2021-270](https://www.dell.com/support/kbdoc/en-us/000194490/dsa-2021-270-enterprise-hybrid-cloud-security-update-for-apache-log4j-remote-code-execution-vulnerability-cve-2021-44228) | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | GeoDrive | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Hybrid Client (DHC) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | ImageAssist | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Insight IQ | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Integrated Dell Remote Access Controller (iDRAC) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | IsilonSD Management Server | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Mainframe Enablers | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | MyDell Mobile | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | NetWorker Management Console | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking N-Series | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking OS 10 | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking OS 9 | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking SD-WAN Edge | Unknown | Investigation |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking W-Series | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Networking X-Series | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OMIMSSC (OpenManage Integration for Microsoft System Center) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Open Manage Mobile | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Open Manage Server Administrator | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Open Management Enterprise - Modular | Unknown | Vulnerable | Patch expected 12/17 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Change Management | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Enterprise | Unknown | Vulnerable | Patch expected 12/17 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Enterprise Services  | Unknown | Vulnerable | Patch expected 12/17 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Integration for Microsoft System Center for System Center Operations Manager | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Integration with Microsoft Windows Admin Center | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | OpenManage Network Integration | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | PowerEdge BIOS | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Remotely Anywhere | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Secure Connect Gateway (SCG) 5.0 Appliance | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Smart Fabric Storage Software | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Solutions Enabler | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Sonic | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | SRS Policy Manager | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | SRS VE | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | SupportAssist Client Commercial | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | SupportAssist Client Consumer | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | SupportAssist Enterprise | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Unisphere Central | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Unisphere for PowerMax | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Vblock | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | ViPR Controller | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VNX Control Station | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VNX1 | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VNX2 | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VNXe 1600 | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VNXe 3200 | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Vsan Ready Nodes | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VxBlock | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | VxFlex Ready Nodes | Unknown | Vulnerable | Workaround expected 12/15 | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Wyse Management Suite | Unknown | Vulnerable | See [DSA-2021-267](https://www.dell.com/support/kbdoc/en-us/000194459/dsa-2021-267-dell-wyse-management-suite-security-update-for-apache-log4j-remote-code-execution-vulnerability-cve-2021-44228) | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Wyse Management Suite Import Tool | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Wyse Proprietary OS (ThinOS) | Unknown | Not vuln |  | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Dell | Wyse Windows Embedded | Unknown | Vulnerable | Fix Release Timeline TBD | [source](https://www.dell.com/support/kbdoc/nl-nl/000194414/dell-response-to-apache-log4j-remote-code-execution-vulnerability) |
| Device42 | Device42 | All | Not vuln |  | [source](https://blog.device42.com/2021/12/13/log4j-zero-day/) |
| Devolutions | All products | | Not vuln | | [source](https://blog.devolutions.net/2021/12/critical-vulnerability-in-log4j/) |
| DirectAdmin | All products | | Not vuln | Invidivual plugins not developed as part of DirectAdmin core may be vulnerable. | [source](https://forum.directadmin.com/threads/new-zero-day-exploit-for-log4j-java-library-is-an-enterprise-nightmare.65173/post-339723) |
| Docker | Docker infrastructure | Unknown | Not vuln | Docker infrastructure not vulnerable, Docker images could be vulnerable. For more info see source. |[source](https://www.docker.com/blog/apache-log4j-2-cve-2021-44228/) |
| DotCMS | Hybrid Content Management System | | Fix | | [source](https://github.com/dotCMS/core/issues/21393) |
| Draytek | All products | Unknown | Not vuln | |[source](https://www.draytek.com/about/security-advisory/log4shell-vulnerability-(cve-2021-44228)/) |
| Dräger | All Medical Devices | | Not Vuln | | [source](https://static.draeger.com/security) |
| Dropwizard | Dropwizard | Unknown | Not vuln | Only vulnerable if you manually added Log4j |[source](https://twitter.com/dropwizardio/status/1469285337524580359) |
| Dynatrace | ActiveGates | 1.229.49.20211210-165018, 1.227.31.20211210-164955, 1.225.29.20211210-164930, 1.223.30.20211210-164926 | Fix | |[source](https://community.dynatrace.com/t5/Dynatrace-Open-Q-A/Impact-of-log4j-zero-day-vulnerability/m-p/177259/highlight/true#M19282) |
| Dynatrace | Dynatrace Cloud Services | Unknown | Fix | | [source](https://community.dynatrace.com/t5/Dynatrace-Open-Q-A/Impact-of-log4j-zero-day-vulnerability/m-p/177259/highlight/true#M19282) |

### E

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| EAL | ATS Classic | All Versions | Not Vuln | | See vendor-statements |
| EclecticIQ | TIP | < 2.11 | Vulnerable | The Threat Intel Platform includes Neo4j 3.5.12 (not vulnerable) and Elasticsearch and Logstash OSS 7.9.1 (vulnerable) see Elasticsearch below for mitigation. see link in their own fix for Logstash (Support account needed, ongoing investigation) | [source/fix](https://docs.eclecticiq.com/security-advisories/security-issues-and-mitigation-actions/eiq-2021-0016-2) |
| Elastic         | APM Java Agent | 1.17.0-1.28.0 | Workaround |  Only vulnerable with specific configuration | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | APM Server | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Beats | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Cmd | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Agent | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Cloud Enterprise | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Cloud | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Cloud on Kubernetes | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Endgame | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elastic Maps Service | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Elasticsearch | < 6.8.9, 7 - 7.8  | Fix | Information leakage vulnerability, Fixed in 7.16.1 and 6.8.21 | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Endpoint Security | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Enterprise Search | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Fleet Server | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Kibana | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Logstash | < 6.8.21, < 7.16.1 | Fix | No known remote code execution exposure, Fixed in 6.8.21, 7.16.1 | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Machine Learning | | Not Vuln |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| Elastic         | Swiftype | | Investigation |   | [source](https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476) |
| ELO | Digital Office || Not Vuln || [source](http://www.elo.com)|
| Enfocus | BoardingPass | All | Not Vuln | | [source](https://enfocus-community.force.com/customers/s/article/Are-the-Enfocus-products-impacted-by-the-log4j-security-vulnerability?language=en_US)|
| Enfocus | Connect | All | Not Vuln | | [source](https://enfocus-community.force.com/customers/s/article/Are-the-Enfocus-products-impacted-by-the-log4j-security-vulnerability?language=en_US)|
| Enfocus | Switch | All | Not Vuln | | [source](https://enfocus-community.force.com/customers/s/article/Are-the-Enfocus-products-impacted-by-the-log4j-security-vulnerability?language=en_US)|
| Enfocus | PDF Review Module | All | Not Vuln | | [source](https://enfocus-community.force.com/customers/s/article/Are-the-Enfocus-products-impacted-by-the-log4j-security-vulnerability?language=en_US)|
| Enfocus | PitStop | All | Not Vuln | | [source](https://enfocus-community.force.com/customers/s/article/Are-the-Enfocus-products-impacted-by-the-log4j-security-vulnerability?language=en_US)|
| Enovation | All | | Not Vuln | | [source](https://enovationgroup.com/nl/nieuws/log4j-vulnerability-cve-2021-44228/) |
| ESET | All products | Unknown | Not vuln | |[source](https://support.eset.com/en/alert8188-information-regarding-the-log4j2-vulnerability) |
| ESET | Secure Authentication | Unknown | Workaround | |[source](https://support.eset.com/en/kb8190-vulnerability-log4j2-in-the-reporting-engine-elasticsearch-of-eset-secure-authentication?ref=esf) |
| Esri | ArcGIS Enterprise and related products | < 10.8.0 | Workaround | See source for workaround  | [source](https://www.esri.com/arcgis-blog/products/arcgis-enterprise/administration/arcgis-software-and-cve-2021-44228-aka-log4shell-aka-logjam/) |
| estos            | All products | Unknown | Not vuln | |[source](https://support.estos.de/de/sicherheitshinweise/estos-von-kritischer-schwachstelle-in-log4j-cve-2021-44228-nicht-betroffen) |
| EVL Labs | JGAAP | <8.0.2 | Fix | | [source](https://github.com/evllabs/JGAAP/releases/tag/v8.0.2) |
| Exivity | Exivity On-Premise | All version | Not Vuln | | [source](https://docs.exivity.com/getting-started/releases/announcements#announcement-regarding-cve-2021-44228) |
| Exact | All Products | | Not vuln | | [source NL](https://www.exact.com/nl/nieuws/algemeen-statement-apache-lek), [source EN](https://www.exact.com/news/general-statement-apache-leak) |
| Evolveum | midPoint || Not vuln | | [source](https://evolveum.com/midpoint-not-vulnerable-to-log4shell/) |
| Extensis | Universal Type Server | =>7.0.6 | Fix | |[source](https://help.extensis.com/hc/en-us/articles/4412767414299-Universal-Type-Server-7-and-Log4j-vulnerabilities)  |
| eXtreme Hosting | All products | Unknown | Not vuln | |[source](https://extremehosting.nl/log4shell-log4j/) |
| Extreme Networks | 200-series || Investigation |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | BOSS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | EXOS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Extreme AirDefense || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Extreme Campus Controller (ExtremeCloud Appliance) || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Extreme Fabric Automation (EFA) || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Extreme Management Center (XMC)|| Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Extreme Visibility Manager (XVM) ||  Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeAnalytics   || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeCloud A3 || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeCloud IQ || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeConnect  || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeControl  || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeGuest    || Investigation |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeLocation || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ExtremeWireless (Identifi)|| Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Fabric Manager || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | HiveManager Classic On-Premises || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | HiveManager Classic Online || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | IQEngine (HiveOS) || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | IQVA || Vulnerable |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | ISW || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | NetIron OS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Network OS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Nsight    || Investigation |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | SLX-OS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | Traffic Sensor || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | VOSS || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | WiNG || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Extreme Networks | XIQ-SE || Not vuln |  |  [source](https://extremeportal.force.com/ExtrArticleDetail?an=000100806_ga) |
| Ewon | eCatcher | 6.7.7 | Fix |  |  [source](https://hmsnetworks.blob.core.windows.net/www/docs/librariesprovider10/downloads-monitored/manuals/release-notes/ecatcher_releasenotes.txt?sfvrsn=4f054ad7_42) |

### F

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
|F5| All products | |Not Vuln | F5 products themselves are not vulnerable, but F5 published guidance on mitigating through BIG-IP ASM/Advanced WAF and NGINX App Protect|[source](https://support.f5.com/csp/article/K19026212)|
| Fiix | CMMS core | V5  | Fix | | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
|FileCap| FileCap Server | 5.1.1 | Fix | |[source](https://filecap.com/blog-posts/detecteer-log4shell-exploitatie-pogingen)|
|FileCap| FileCap Plugins || Not vuln | |[source](https://filecap.com/blog-posts/detecteer-log4shell-exploitatie-pogingen)|
| FileZilla | All | | Not vuln | | [source](https://forum.filezilla-project.org/viewtopic.php?f=6&t=54338)|
|Forcepoint |Advanced Malware Detection                                                           ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Behavioral Analytics                                                                 ||Investigation | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Bitglass SSE                                                                         ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |CASB                                                                                 ||Investigation | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Content Gateway                                                                      ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |DDP/DUP/DPS                                                                          ||Investigation | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Directory Synchronization Client                                                     ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |DLP Manager                                                                          ||Workaround | |[source](https://support.forcepoint.com)|
|Forcepoint |Email Security                                                                       ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Forcepoint Cloud Security Gateway (CSG)                                              ||Not vuln   | |[source](https://support.forcepoint.com)|
|Forcepoint |Insider Threat                                                                    ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Next Generation Firewall (NGFW)                                                      ||Not vuln   | |[source](https://support.forcepoint.com)|
|Forcepoint |Next Generation Firewall, NGFW VPN Client, Forcepoint User ID service and Sidewinder ||Not vuln   | |[source](https://support.forcepoint.com)|
|Forcepoint |Next Generation Firewall Security Management Center, and virtual SMC appliances (NGFW)||Workaround | |[source](https://support.forcepoint.com/s/article/CVE-2021-44228-Java-log4j-vulnerability-mitigation-with-NGFW-Security-Management-Center)|
|Forcepoint |One Endpoint                                                                         ||Not vuln   | |[source](https://support.forcepoint.com)|
|Forcepoint |Private Access                                                                       ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Remote Browser Isolation                                                             ||Not vuln | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forcepoint |Security Manager (Web, Email and DLP)                                                ||Workaround | |[source](https://support.forcepoint.com)|
|Forcepoint |Web Security                                                                         ||Investigation | |[source](https://support.forcepoint.com/s/article/Apache-log4j-Zero-Day-RCE-Vulnerability-CVE-2021-44228)|
|Forescout | | | Investigation | | [source](https://www.forescout.com/blog/forescout%e2%80%99s-response-to-cve-2021-44228-apache-log4j-2/) |
|ForgeRock        | Autonomous Identity |  | Workaround | all other ForgeRock products not vuln | [source](https://backstage.forgerock.com/knowledge/kb/book/b21824339#1_bzBa)  |
|Fortinet| FortiAIOps| version < 1.0.1 |Vulnerable| Fixed in version 1.0.2 |[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiAnalyzer Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiAnalyzer| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiAP| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiAuthenticator| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiCASB| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiConvertor| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiDeceptor| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiEDR Agent| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiEDR Cloud| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiGate Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiGSLB Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiMail| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiManager Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiManager| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiNAC| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiOS (includes FortiGate & FortiWiFi)| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiPhish Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiPolicy| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiPortal | Fix |Vulnerable| Fixed in version 6.0.8 and 5.3.8 |[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiRecorder| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiSIEM| Workaround |Vulnerable| [Mitigation steps](https://community.fortinet.com/t5/FortiSIEM/Techincal-Tip-FortiSIEM-Log4j-Mitigating-CVE-2021-44228/ta-p/201008) |[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiSOAR| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiSwitch Cloud in FortiLANCloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiSwitch & FortiSwitchManager| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiToken Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiVoice| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| FortiWeb Cloud| |Not Vuln||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fortinet| ShieldX| |Vulnerable||[source](https://www.fortiguard.com/psirt/FG-IR-21-245)|
|Fujitsu| ServerView Suite | Unknown | Vulnerable | Log4j v2.12 present in ServerView Operations Manager |[source](https://support.ts.fujitsu.com/ProductSecurity/content/Fujitsu-PSIRT-PSS-IS-2021-121000-Security-Notice-SF.pdf)|
|Fujitsu| SecDocs | Unknown | Vulnerable ||[source](https://support.ts.fujitsu.com/ProductSecurity/content/Fujitsu-PSIRT-PSS-IS-2021-121000-Security-Notice-SF.pdf)|
|F-Secure| Endpoint Proxy | 13-15| Fix| |[source](https://status.f-secure.com/incidents/sk8vmr0h34pd)|
|F-Secure| Policy Manager | 13-15| Fix| |[source](https://status.f-secure.com/incidents/sk8vmr0h34pd)|
|F-Secure| Policy Manager Proxy| 13-15| Fix | |[source](https://status.f-secure.com/incidents/sk8vmr0h34pd)|
|FusionAuth| FusionAuth| 1.32|Not Vuln||[source](https://fusionauth.io/blog/2021/12/10/log4j-fusionauth/)|

### G

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Genesys | All products || Investigation ||[source](https://www.genesys.com/blog/post/genesys-update-on-the-apache-log4j-vulnerability)|
| GeoSolutions | GeoServer |All versions | Not vuln ||[source](http://geoserver.org/announcements/2021/12/13/logj4-rce-statement.html)|
| GeoSolutions | Geonetwork | All versions | Workaround ||[source](https://my.geocat.net/knowledgebase/125/Log4j-RCE-CVE-2021-44228-vulnerability-patch.html)|
| GFI Software | Kerio Connect | | Vulnerable | | [source](https://forums.gfi.com/index.php?t=msg&th=39096&start=0&)|
| Ghisler | Total Commander | All | Not Vuln | Third Party plugins might contain log4j | [source](https://www.ghisler.com/whatsnew.htm) |
| GitHub | Github Enterprise Server | 3.3.1, 3.2.6, 3.1.14, 3.0.22 | Fix | | [source](https://github.blog/2021-12-13-githubs-response-to-log4j-vulnerability-cve-2021-44228/) |
| GitLab | DAST analyzer | | Not vuln | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GitLab | Dependency Scanning | | Fix | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GitLab | Gemnasium-Maven | | Fix | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GitLab | GitLab | | Not vuln | | [source](https://forum.gitlab.com/t/cve-2021-4428/62763/8)|
| GitLab | PMD OSS | | Fix | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GitLab | SAST | | Fix | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GitLab | Spotbugs | | Fix | | [source](https://about.gitlab.com/blog/2021/12/15/updates-and-actions-to-address-logj-in-gitlab/) |
| GoAnywhere| Agents| Unknown| Workaround | | [source](https://www.goanywhere.com/cve-2021-44228-goanywhere-mitigation-steps)|
| GoAnywhere| Gateway| Unknown| Workaround | | [source](https://www.goanywhere.com/cve-2021-44228-goanywhere-mitigation-steps)|
| GoAnywhere| MFT| Unknown| Workaround | | [source](https://www.goanywhere.com/cve-2021-44228-goanywhere-mitigation-steps)|
| Gradle | Gradle |  | Not vuln | Gradle Scala Compiler Plugin depends upon log4j-core but it is not used. | [source](https://blog.gradle.org/log4j-vulnerability) |
| Gradle | Gradle Enterprise | 2021.3.6 | Fix | | [source](https://security.gradle.com/advisory/2021-11) |
| Gradle | Gradle Enterprise Test Distribution Agent | 1.6.2 | Fix | | [source](https://security.gradle.com/advisory/2021-11) |
| Gradle | Gradle Enterprise Build Cache Node | 10.1 | Fix | | [source](https://security.gradle.com/advisory/2021-11) |
| Grafana | All products | | Not vuln | | [source](https://grafana.com/blog/2021/12/14/grafana-labs-core-products-not-impacted-by-log4j-cve-2021-44228-and-related-vulnerabilities/) |
| Gravwell | All products | | Not vuln | Gravwell products do not use Java | [source](https://www.gravwell.io/blog/cve-2021-44228-log4j-does-not-impact-gravwell-products) |
| Graylog | Graylog | 3.3.15, 4.0.14, 4.1.9, 4.2.3 | Fix | The vulnerable Log4j library is used to record GrayLog's own log information. Vulnerability is not triggered when GrayLog stores exploitation vector from an outer system. Graylog [version 4.2.4 fixes](https://github.com/Graylog2/graylog2-server/compare/4.2.3...4.2.4) [another vulnerability](https://www.lunasec.io/docs/blog/log4j-zero-day-update-on-cve-2021-45046/) | [source](https://www.graylog.org/post/graylog-update-for-log4j)|
| Greenshot | Greenshot |  | Not vuln | | [source](https://greenshot.atlassian.net/browse/BUG-2871) |
| GuardedBox | GuardedBox | 3.1.2 | Fix | | [source](https://twitter.com/GuardedBox/status/1469739834117799939) |

### H

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| HackerOne | Unknown | Unknown | Fix ||[source](https://twitter.com/jobertabma/status/1469490881854013444)|
| Hashicorp| All products | |Not Vuln | | [source](https://support.hashicorp.com/hc/en-us/articles/4412469195795-CVE-2021-44228-Log4J-has-no-impact-on-HashiCorp-Products)|
| HCL Software | BigFix Insights | Unknown | Not vuln |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| HCL Software | BigFix Insights for Vulnerability Remediation | Unknown | Not vuln |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| HCL Software | BigFix Compliance | > 2.0.1 ; < 2.0.4 | Workaround |  not vuln for CVE-2021-45046 | [source](https://forum.bigfix.com/t/bigfix-compliance-has-a-remediation-for-log4j-vulnerability-cve-2021-44228/40197)|
| HCL Software | BigFix Inventory | < 10.0.7 | Workaround |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| HCL Software | BigFix Lifecycle | Unknown | Not vuln |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| HCL Software | BigFix Mobile | Unknown | Not vuln |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| HCL Software | BigFix Patch | Unknown | Not vuln |  not vuln for CVE-2021-45046 | [source](https://support.hcltechsw.com/csm?id=kb_article&sysparm_article=KB0095486)|
| Heimdal Security | web-based services | Cloud | Not vuln || [source](https://heimdalsecurity.com/blog/log4j-vulnerability/) |
| Helpsystems | Clearswift Secure Email Gateway | 5.4.0 ,5.3.0 |Vulnerable | Investigation | [source](https://community.helpsystems.com/kb-nav/kb-article/?id=37becc1c-255c-ec11-8f8f-6045bd006687&redirect=false)|
| Helpsystems | Clearswift Secure Exchange Gateway | 5.4.0 ,5.3.0 |Vulnerable | Investigation | [source](https://community.helpsystems.com/kb-nav/kb-article/?id=37becc1c-255c-ec11-8f8f-6045bd006687&redirect=false)|
| Helpsystems | Clearswift Secure Web Gateway | 5.4.0 ,5.3.0 |Vulnerable | Investigation | [source](https://community.helpsystems.com/kb-nav/kb-article/?id=37becc1c-255c-ec11-8f8f-6045bd006687&redirect=false)|
| Helpsystems | Clearswift Secure ICAP Gateway | 5.4.0 ,5.3.0 |Vulnerable | Investigation | [source](https://community.helpsystems.com/kb-nav/kb-article/?id=37becc1c-255c-ec11-8f8f-6045bd006687&redirect=false)|
| Hexagon | ERDAS APOLLO Advantage & Professional | Unknown | Investigation | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | ERDAS APOLLO Essentials | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | GeoMedia SmartClient | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | GeoMedia | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | GeoMedia WebMap | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | Geospatial Portal | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | Geospatial SDI | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | ImageStation | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | IMAGINE | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | Luciad Fusion | Unknown | Not vuln | The only risk is if Log4J was implemented outside of the default product install | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | Luciad Lightspeed | Unknown | Not vuln | The only risk is if Log4J was implemented outside of the default product install | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | M.App Enterprise standalone or with Luciad Fusion | Unknown | Not vuln | | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hexagon | M.App Enterprise | Unknown | Investigation | Might be vulnerable only when used with Geoprocessing Server | [source](https://supportsi.hexagon.com/help/s/article/Security-Vulnerability-CVE-2021-44228-log4j-2)|
| Hitachi Energy | all other products | | Investigation | Meta-Advisory listing all known affected products, other are still unter investigation | [source](https://search.abb.com/library/Download.aspx?DocumentID=8DBD003132&LanguageCode=en&DocumentPartId=&Action=Launch)|
| Hitachi Energy | FOXMAN-UN | < R11BSP1 | Vulnerable | | [source](https://search.abb.com/library/Download.aspx?DocumentID=8DBD000088&LanguageCode=en&DocumentPartId=&Action=Launch) |
| Hitachi Energy | FOXMAN-UN | R15A, R14B, R14A, R11BSP1 | Workaround | | [source](https://search.abb.com/library/Download.aspx?DocumentID=8DBD000088&LanguageCode=en&DocumentPartId=&Action=Launch) |
| Hitachi Energy | UNEM | < R11BSP1 | Vulnerable | | [source](https://search.abb.com/library/Download.aspx?DocumentID=8DBD000089&LanguageCode=en&DocumentPartId=&Action=Launch) |
| Hitachi Energy | UNEM | R15A, R14B, R14A, R11BSP1 | Workaround | | [source](https://search.abb.com/library/Download.aspx?DocumentID=8DBD000089&LanguageCode=en&DocumentPartId=&Action=Launch) |
| Hitachi Vantara | Pentaho | v8.3.x, v9.2.x | Not vuln | | [source](https://support.pentaho.com/hc/en-us/articles/4416229254541-log4j-2-zero-day-vulnerability-No-impact-to-supported-versions-of-Pentaho-)|
| HostiFi | Unifi hosting | Unknown | Fix | Hosted Unifi solution | [source](https://twitter.com/hostifi_net/status/1440311322592231436) |
| HPE |3PAR Service Processor | 5.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |3PAR StoreServ Arrays| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_US&docId=a00120086en_us) |
| HPE |AirWave Management Platform| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Alletra 6000| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Alletra 9k| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba Central| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba ClearPass Policy Manager| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba ClearPass Policy Manager| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba Instant (IAP)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba Location Services| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba NetEdit| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba NetInsight Network Analytics| All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |ArubaOS-CX switches| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |ArubaOS SD-WAN Controllers and Gateways| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |ArubaOS-S switches| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |ArubaOS Wi-Fi Controllers and Gateways| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba PVOS Switches| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba SDN VAN Controller| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba User Experience Insight (UXI)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Aruba VIA Client| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Authentication Server Function (AUSF) |1.2107.0, 1.2109.0 and 1.2112.0 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |BladeSystem Onboard Administrator| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Brocade 16Gb Fibre Channel SAN Switch for HPE Synergy| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Brocade 16Gb SAN Switch for HPE BladeSystem c-Class| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Brocade 32Gb Fibre Channel SAN Switch for HPE Synergy| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Brocade Network Advisor| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |CloudAuth| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |CloudPhysics| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Compute Cloud Console| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Compute operations manager- FW UPDATE SERVICE (internal name olive)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |COS (Cray Operating System)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Cray EX System Monitoring Application (SMA) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Cray Systems Management (CSM)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Cray View for ClusterStor |1.3.1 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Custom SPP Portal (<https://spp.hpe.com/custom>)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Data Management Framework |7.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Data Services Cloud Console| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Dragon |7.2 and 7.3 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Dynamic SIM Provisioning (DSP) |DSP3.3, DSP3.1 and DSP3.4 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Device Entitlement Gateway (DEG) |5 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Edge Infrastructure Automation |2.0.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |enhanced Internet Usage Manager (eIUM) |10.6.3| Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Ezmeral Container Platform |5.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Ezmeral Container Platform Bluedata EPIC |3.x and 4.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Ezmeral Data Fabric |Core/Client v6.2.0; MCS v6.0.1, v6.1.0, v6.1.1 and v6.2.0; Installer v1.17.0.0 and older | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Ezmeral Ecosystem Pack (EEP) |Elastic Search v6.8.8 and older; Data Access Gateway (DAG) v2.x and older; Hive v2.3.x and older; HBase v1.4.13 and older; Kafka HDFS Connector v10.0.0 and older | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |General information HPE| | Investigation| Security bulletins for affected products will be posted on HPE Support Center, as the results of the investigation become available in the near future. HPE products not listed below are either vulnerable or undergoing investigation. |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Harmony Data Platform| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HOP public services (grafana, vault, rancher, Jenkins)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN2600B SAN Extension Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN4000B SAN Extension Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN6000B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN6500B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN6600B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN6650B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE B-series SN6700B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Hardware Support Manager plug-in for VMware vSphere Lifecycle Manager| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Infosight for Servers| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE OneView for VMware vRealize Operations (vROps)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE OneView Global Dashboard| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE OneView| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Performance Cluster Manager (HPCM)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Slingshot| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN3000B Fibre Channel Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8000B 4-Slot SAN Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8000B 8-Slot SAN Backbone Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8600B 4-Slot SAN Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8600B 8-Slot SAN Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8700B 4-Slot Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE SN8700B 8-Slot Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Synergy Image Streamer| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Systems Insight Manager (SIM)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Virtual Connect Enterprise Manager (VCEM)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Virtual Connect| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |HPE Virtual Server Environment (VSE)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Hyper Converged 250 System |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Hyper Converged 380 |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Infosight for Storage |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Insight Cluster Management Utility (CMU)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrated Home Subscriber Server Software Series | 4.0.x | Vulnerable | Only vulnerable when using the nHSS 4G/5G IWK function | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Integrated Lights-Out 4 (iLO 4)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrated Lights-Out 5 (iLO 5)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrated Lights-Out (iLO) Amplifier Pack| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrity BL860c, BL870c, BL890c| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrity Superdome 2| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Integrity Superdome X| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Intelligent Assurance |All versions | Vulnerable |Only Analytics on Metrics is vulnerable | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Intelligent Management Center (IMC) Standard and Enterprise |7.3 (E0706) and 7.3 (E0706P06) | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Intelligent Provisioning| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |iSUT integrated smart update tool| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Maven Artifacts (Atlas)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Media Workflow Master (MWM) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |MSA| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |NetEdit| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Network Function Virtualization Director (NFV Director) |5.1.x and 6.0.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Nimble Storage| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |NS-T0634-OSM CONSOLE TOOLS| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |NS-T0977-SCHEMA VALIDATOR| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |ntegrity Rx2800/Rx2900| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |OfficeConnect| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Primera Storage| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Real Time Management System (RTMS) |3.0.x and 3.1.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Remote SIM Provisioning Manager (RSPM) |1.3.2 and 1.4.1 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |RepoServer part of OPA (on Premises aggregator)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Resource Aggregator for Open Distributed Infrastructure Management| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |RESTful Interface Tool (iLOREST)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Revenue Intelligence Software Series |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SANnav Management Software |2.0.0 and 2.1.1 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SAT (System Admin Toolkit)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Scripting Tools for Windows PowerShell (HPEiLOCmdlets)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Service Director (SD) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SGI MC990 X Server| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |SGI UV 2000 Server| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |SGI UV 3000 Server| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |SGI UV 300, 300H, 300RL, 30EX| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Shasta Monitoring Framework (SMF) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE | Silver Peak Orchestrator |  | Workaround | |[source](https://www.arubanetworks.com/assets/alert/ARUBA-PSA-2021-019.txt), [workaround](https://www.arubanetworks.com/website/techdocs/sdwan/docs/advisories/media/security_advisory_notice_apache_log4j2_cve_2021_44228.pdf) |
| HPE |SimpliVity 325, 380 Gen9, 380 Gen10 and 2600 Gen10 |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SimpliVity OmniCube |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SN8700B 8-Slot Director Switch| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreEasy| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreEver CVTL| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreEver LTO Tape Drives| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreEver MSL Tape Libraries| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreOnce| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |StoreServ Management Console (SSMC) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |SUM (Smart Update Manager)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Superdome Flex 280| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Superdome Flex Server| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Telecom Analytics Smart Profile Server (TASPS) |All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Telecom Management Information Platform Software Series | | Vulnerable | Only TeMIP Rest Server 8.3.2 and TMB 3.4.0 are vulnerable | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Trueview Inventory Software Series | 8.6.x and 8.7.x | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |UAN (User Access Node)| | Not vuln| |  [source](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_USdocId=a00120086en_us) |
| HPE |Unified Data Management (UDM) | 1.2107.0, 1.2109.0, 1.2109.1 and 1.2112.0 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Universal IoT (UioT) Platform | All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Unstructured Data Storage Function (UDSF) | 1.2108.0, 1.2110.0 and 1.2112.0 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |User Data Repository (UDR) | 1.2106.0, 1.2110.0 and 1.2112.0 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |Virtual Headend Manager (vHM) | All versions | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| HPE |XP Performance Advisor Software | 7.5 through 8.4 | Vulnerable | | [source](https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbgn04215en_us) |
| Huawei | All products | | Investigation | | [source](https://www.huawei.com/en/psirt/security-notices/huawei-sn-20211210-01-log4j2-en)|

### I

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| IBM | All products | | Investigation | | [source](https://www.ibm.com/blogs/psirt/an-update-on-the-apache-log4j-cve-2021-44228-vulnerability/)|
| IBM | Business Automation Workflow | 18.0.0+ | Fix | JR64456 / JR64096 | [source](https://www.ibm.com/support/pages/node/6525834)|
| IBM | Cloud Object Storage | All versions  | Fix | Fix: 3.16.0.53 and 3.16.2.57 | [source](https://www.ibm.com/support/pages/mitigation-and-software-update-cve-2021-44228-vulnerability?cm_sp=s033-_-OCSTXNRM-_-F&mync=F&mynp=OCSTXNRM&myns=s033)|
| IBM | Curam SPM | 8.0.0, 7.0.11 | Vulnerable | | [source](https://www.ibm.com/blogs/psirt/security-bulletin-vulnerability-in-apache-log4j-may-affect-cram-social-program-management-cve-2019-17571/)|
| IBM | DB2 Server | 11.5 | Vulnerable | | [source](https://www.ibm.com/support/pages/node/6526462) |
| IBM | IBM Netezza Analytics for NPS | All versions <= 11.2.21 | Vulnerable | Fix should be available from 14th Dec | [source](https://www.ibm.com/support/pages/node/6525816)|
| IBM | IBM Netezza Analytics | All versions <= 3.3.9 | Vulnerable | Fix should be available from 14th Dec | [source](https://www.ibm.com/support/pages/node/6525816)|
| IBM | IBM Security Access Manager | 9.0.7-ISS-ISAM-FP0002 | Fix |  | [source](https://www.ibm.com/support/pages/node/6526174)|
| IBM | IBM Security Access Manager | 10.0.2-ISS-ISVA-FP0000 | Fix |  | [source](https://www.ibm.com/support/pages/node/6526174)|
| IBM | IBM MQ | iFix 9.2-IBM-MQ-LinuxX64-LAIT39386 | Fix |  | [source](https://www.ibm.com/support/pages/node/6526274)|
| IBM | Power Hardware Management Console | V10.1.1010.0,V9.2.950.0 | Fix | Fix: MH01913,MF69263 | [source](https://www.ibm.com/support/pages/node/6526172)|
| IBM | SPSS Statistics | 25.0, 26.0, 27.0.1, 28.0.1 | Fix | Link is behind a login | [source](https://www.ibm.com/support/pages/node/6526182)|
| IBM | Sterling Fulfillment Optimizer | Unknown | Vulnerable | | [source](https://www.ibm.com/support/pages/node/6525544)|
| IBM | Sterling Inventory Visibility | Unknown | Vulnerable | | [source](https://www.ibm.com/support/pages/node/6525544)|
| IBM | Sterling Order Management | Unknown | Not vuln | | [source](https://www.ibm.com/support/pages/node/6525544)|
| IBM | VM Manager Tool (part of License Metric Tool) | >9.2.21,<9.2.26 | Vulnerable | | [source](https://www.ibm.com/support/pages/node/6525762/)|
| IBM | Websphere | 8.5 | Vulnerable | fix: PH42728 | [source](https://www.ibm.com/support/pages/node/6525706/)|
| IBM | Websphere | 9.0 | Vulnerable | fix: PH42728 | [source](https://www.ibm.com/support/pages/node/6525706/)|
| IGEL | Universal Management Suite | | Workaround | | [source](https://kb.igel.com/securitysafety/en/isn-2021-11-ums-log4j-vulnerability-54086712.html) |
| iGrafix | All | Latest | Fix || [source](https://www.igrafx.com/igrafx-thwarts-log4j-vulnerability/) |
| Illumio | C-VEN | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | CLI | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | CloudSecure | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Core on-premise PCE | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Core SaaS PCE | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Edge SaaS PCE | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Edge-CrowdStrike | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Flowlink | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Kubelink | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | NEN | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | QRadar App | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | Splunk App | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Illumio | VEN | | Not vuln | | [source](https://support.illumio.com/knowledge-base/articles/Customer-Security-Advisory-on-log4j-RCE-CVE-2021-44228.html)|
| Imprivata | ConfirmID | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | Cortext | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | GroundControl | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | Identity Governance | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | Mobile Device Access | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | OneSign | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Imprivata | PAM | | Fix | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?urlName=IPAM-Log4j-CVE-2021-44228-vulnerability-mitigation)|
| Imprivata | PatientSecure | | Not Vuln | Link is behind a login | [source](https://support.imprivata.com/NewCommunityArticleView?url=ka52M000000AZkgQAG)|
| Inductive Automation | Ignition | All versions | Not Vuln| | [source](https://support.inductiveautomation.com/hc/en-us/articles/4416204541709-Regarding-CVE-2021-44228-Log4j-RCE-0-day) |
| Influxdata | All | All versions | Not Vuln| | [source](https://www.influxdata.com/blog/apache-log4j-vulnerability-cve-2021-44228/) |
| Informatica | Axon | 7.2.x | Workaround |  | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | Data Privacy Management | 10.5, 10.5.1 | Workaround |  | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | Information Deployment Manager |  | Fix | | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | Metadata Manager | 10.4, 10.4.1, 10.5, 10.5.1 | Workaround |  | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | PowerCenter | 10.5.1 | Workaround | | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | PowerExchange for CDC (Publisher) and Mainframe | 10.5.1 | Workaround | | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | Product 360 | All versions | Workaround  | | [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-Updates-for-Informatica-On-premises-Products) |
| Informatica | Secure Agents (Cloud hosted)| Unknown | Fix | Fixed agents may need to be restarted| [source](https://knowledge.informatica.com/s/article/Apache-Zero-Day-log4j-RCE-Vulnerability-updates-for-Informatica-Cloud-and-Cloud-Hosted-Software) |
| Infoblox | All products | All versions | Not Vuln | | [source](https://blogs.infoblox.com/security/infoblox-response-to-apache-log4j-vulnerability/) |
| Infoland | iQualify | | Not Vuln | | [source](https://community.infoland.nl/infoland-nieuws-128/geen-beveiligingslek-apache-log4j2-zenya-iprova-en-iqualify-3589) |
| Infoland | Zenya (iProva) | | Not Vuln | | [source](https://community.infoland.nl/infoland-nieuws-128/geen-beveiligingslek-apache-log4j2-zenya-iprova-en-iqualify-3589) |
| INIT GmbH | AppComm | | Not Vuln | | [source](vendor-statements/INIT-GmbH.png) [source](https://archive.newsletter2go.com/?n2g=wq37zux3-w7nrbmnl-19ru) |
| INIT GmbH | MOBILE-PERDIS | | Not Vuln | | [source](vendor-statements/INIT-GmbH.png) [source](https://archive.newsletter2go.com/?n2g=wq37zux3-w7nrbmnl-19ru) |
| INIT GmbH | Mobile Plan | 4.22.x and 5.x  | Vulnerable | | [source](vendor-statements/INIT-GmbH.png) [source](https://archive.newsletter2go.com/?n2g=wq37zux3-w7nrbmnl-19ru) |
| INIT GmbH | WebComm | | Not Vuln | | [source](vendor-statements/INIT-GmbH.png) [source](https://archive.newsletter2go.com/?n2g=wq37zux3-w7nrbmnl-19ru) |
| Intel | Audio Development Kit |  | Vulnerable | | [source](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00646.html) |
| Intel | Datacenter Manager |  | Vulnerable | | [source](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00646.html) |
| Intel | oneAPI sample browser plugin for Eclipse |  | Vulnerable | | [source](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00646.html) |
| Intel | System Debugger |  | Vulnerable | | [source](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00646.html) |
| Intel | Secure Device Onboard |  | Vulnerable | | [source](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00646.html) |
| InterSystems | API Manager |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | Atelier Integration |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | Cache |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | Ensemble |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | FHIR Accelerator |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Care Community |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Clinical Viewer | 2019.2 to 2021.1 | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Health Connect |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Health Insight |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Message Transformation Service |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Patient Index |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Personal Community |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Provider Directory |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | HealthShare Unified Care Record |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | Health Integration as a Service |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | InterSystems Cloud Manager |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | IRIS |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | IRIS for Health |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | ISC Reports |  | Vulnerable | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | TrakCare Core |  | Vulnerable | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | TrakCare Editions |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | TrakCare Lab |  | Investigation | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| InterSystems | VS Code Integration |  | Not Vuln | | [source](https://www.intersystems.com/gt/apache-log4j2/) |
| IronNet | All products | All verisons | Investigation | | [source](https://www.ironnet.com/blog/ironnet-security-notifications-related-to-log4j-vulnerability) |
| ISL Online | All products | All versions | Not Vuln | | [source](https://blog.islonline.com/2021/12/13/isl-online-is-not-affected-by-log4shell-vulnerability/) |
| ISPNext | All products | All versions | Not Vuln | | [source](vendor-statements/ISPNext.png) |
| Ivanti | Avalache | 6.3.[0-3] | Fix | Information behind login | [source](https://forums.ivanti.com/s/article/CVE-2021-44228-Avalanche-Remote-code-injection-Log4j) |
| Ivanti | Core Connector | All versions | Workaround | Information behind login | [source](https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j) |
| Ivanti | File Director | All versions | Workaround | Information behind login | [source](https://forums.ivanti.com/s/article/Apache-Log4j-Zero-Day-Vulnerability-and-Ivanti-File-Director-CVE-2021-44228) |
| Ivanti | MobileIron Core | All versions | Workaround | Information behind login | [source](https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j) |
| Ivanti | MobileIron Sentry | 9.13, 9.14 | Workaround | Information behind login | [source](https://forums.ivanti.com/s/article/Security-Bulletin-CVE-2021-44228-Remote-code-injection-in-Log4j) |
| Ivanti | Xtraction | 2019.2 | Not vuln |  | [source](https://forums.ivanti.com/s/article/CVE-2021-44228-Java-logging-library-log4j-Ivanti-Products-Impact-Mapping?language=en_US) |

### J

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| JFrog | all products | | Not Vuln | | [source](https://twitter.com/jfrog/status/1469385793823199240) |
| Jamf Nation     | Jamf Cloud | Unknown| Fix | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation     | Jamf Pro (hosted on-prem) | < 10.34.1 |  See notes | <10.14 vulnerable, 10.14-10.34 patch, >= 10.34.1 fix | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740) |
| Jamf Nation | Health Care Listener| Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Connect | Unknown | Not Vuln | |[source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Data Policy| Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Infrastructure Manager| Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Now | Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Private Access | Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Protect | Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf School| Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jamf Nation | Jamf Threat Defense| Unknown | Not Vuln | | [source](https://community.jamf.com/t5/jamf-pro/third-party-security-issue/td-p/253740)|
| Jazz/IBM | JazzSM DASH | Unknown | See notes | DASH on WebSphere Application Server requires mitigations | [source](https://www.ibm.com/support/pages/node/6525552) |
| Jenkins | Jenkins CI | Unknown | Not Vuln | Invidivual plugins not developed as part of Jenkins core *may* be vulnerable. | [source](https://www.jenkins.io/blog/2021/12/10/log4j2-rce-CVE-2021-44228/) |
| JetBrains | IntelliJ platform based IDEs (AppCode, CLion, DataGrip, DataSpell, GoLand, IntelliJ IDEA Ultimate/Community/Edu, PhpStorm, PyCharm Professional/Community/Edu, Rider, RubyMine, WebStorm) | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | All .NET tools (ReSharper, Rider, ReSharper C++, dotTrace, dotMemory, dotCover, dotPeek) | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | ToolBox | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | TeamCity | Unknown | Not vuln | | [source](https://youtrack.jetbrains.com/issue/TW-74298) |
| JetBrains | Hub | 2021.1.14080 | Fix | | [source](https://blog.jetbrains.com/hub/2021/12/14/hub-update-regarding-log4j2-vulnerability/) |
| JetBrains | YouTrack Standalone | 2021.4.35970 | Fix | | [source](https://blog.jetbrains.com/youtrack/2021/12/youtrack-update-regarding-log4j2-vulnerability/) |
| JetBrains | YouTrack InCloud | Unknown | Fix | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Datalore | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Space | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Code With Me | Unknown | Fix | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Gateway | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Kotlin | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Ktor | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | MPS | Unknown | Not vuln | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | Floating license server | 30211 | Fix | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JetBrains | UpSource | 2020.1.1952 | Fix | | [source](https://blog.jetbrains.com/blog/2021/12/13/log4j-vulnerability-and-jetbrains-products-and-services/) |
| JGraph | DrawIO | All | Not vuln || [source](https://github.com/jgraph/drawio/issues/2490) |
| Jitsi | jitsi-videobridge | v2.1-595-g3637fda42 | Fix  | | [source](https://github.com/jitsi/security-advisories/blob/4e1ab58585a8a0593efccce77d5d0e22c5338605/advisories/JSA-2021-0004.md)|
| jPOS | (ISO-8583) bridge | Unknown | Not Vuln  | | [source](https://github.com/jpos/jPOS/commit/d615199a1bdd35c35d63c07c10fd0bdbbc96f625)|
| Juniper Networks | Cross Provisioning Platform | Unspecified | Under investigation | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | JSA Series | Unspecified | Under investigation | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Advanced Threat Prevention (JATP) | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks AppFormix | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Apstra System | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks CTPOS and CTPView | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Connectivity Services Director | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Contrail products: Contrail Analytics, Contrail Cloud, Contrail Networking or Contrail Service Orchestration | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks ICEAAA Manager | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks JATP Cloud | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Juniper Identity Management Services (JIMS) | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Juniper Mist Edge | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Juniper Sky Enterprise | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Junos OS Evolved | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Junos OS | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Mist Access Points | Any version on AP12, AP21, AP32, AP33, AP34, AP41, AP43, AP45, AP61, AP63. | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Network Director | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Policy Enforcer | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks ScreenOS | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks SecIntel | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Security Director Insights | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Security Director | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Session Smart Router (Formerly 128T) | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Space SDK | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks Standalone Log Collector 20.1 (as also used by Space Security Director) | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Juniper Networks products using Wind River Linux in Junos OS and Junos OS Evolved | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Junos Space Network Management Platform  | Unspecified | Vulnerable | Only when OpenNMS has been enabled. | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks Marvis Virtual Network Assistant (VNA) | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks Mist AI | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks Paragon Active Assurance | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks WAN Assurance | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks Wi-Fi Assurance | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | MIST: Juniper Networks Wired Assurance | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Northstar Controller | Unspecified | Vulnerable | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Northstar Planner | Unspecified | Under investigation | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Paragon Insights | >= 21 version 21.1 ; >= 22 version 22.2  | Vulnerable | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Paragon Pathfinder | >= 21 version 21.1 ; >= 22 version 22.2 | Vulnerable | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Paragon Planner | >= 21 version 21.1 ; >= 22 version 22.2 | Vulnerable | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | Secure Analytics | Unspecified | Under investigation | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |
| Juniper Networks | User Engagement Virtual BLE | Unspecified | Not Vuln | | [source](https://kb.juniper.net/InfoCenter/index?page=content&id=JSA11259&actp=SUBSCRIPTION) |

### K

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Kaseya | AuthAnvil | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | BMS | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | ID Agent DarkWeb ID and BullPhish ID | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | IT Glue | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | MyGlue | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Network Glue | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Passly | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | RocketCyber | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Spannign Salesforce Backup | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Spanning O365 Backup | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Unitrends | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | VSA SaaS and VSA On-Premises | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | Vorex | Unknown | Not Vuln | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Kaseya | products not listed above | Unknown | Investigation | | [source](https://helpdesk.kaseya.com/hc/en-gb/articles/4413449967377-Log4j2-Vulnerability-Assessment) |
| Keeper | SSO Connect On-Prem | 16.0.2 | Fix | | [source](vendor-statements/Keeper.png), [source](https://docs.keeper.io/release-notes/on-prem-components/sso-connect/sso-connect-version-16.0.2)|
| Keycloak | Keycloak | all version | Not Vuln | | [source](https://github.com/keycloak/keycloak/discussions/9078) |
| Kofax | Capture | All | Not Vuln | | [source](https://knowledge.kofax.com/Capture/Kofax_Capture/Reference/Log4J_Vulnerability_CVE-2021-44228_Does_Not_Affect_Kofax_Capture) |
| Kofax | Communication Manager (KCM) |5.3-5.5 | Fix | | [source](https://knowledge.kofax.com/Communications_Manager/Troubleshooting/log4j_vulnerability_in_Kofax_Communications_Manager) |
| Kofax | Robotic Process Automation (RPA) | 11.1 | Workaround | | [source](https://knowledge.kofax.com/Robotic_Process_Automation/Troubleshooting/Kofax_RPA_CVE-2021-44228_log4j_Security_Exploit_Information) |
| Kofax | Robotic Process Automation (RPA) | 11.2 | Workaround | | [source](https://knowledge.kofax.com/Robotic_Process_Automation/Troubleshooting/Kofax_RPA_CVE-2021-44228_log4j_Security_Exploit_Information) |
| Kofax | Robot File System (RFS) | >=10.7 | Workaround | | [source](https://knowledge.kofax.com/Robotic_Process_Automation/Troubleshooting/Kofax_RPA_CVE-2021-44228_log4j_Security_Exploit_Information) |

### L

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Lancom Systems | All products  | All versions | Not Vuln| | [source](https://www.lancom-systems.com/service-support/instant-help/general-security-information) |
| Lansweeper | All products | All versions | Not Vuln| | [source](https://www.lansweeper.com/vulnerability/critical-log4j-vulnerability-affects-millions-of-applications/) |
| LastPass | Other products | | Not Vuln | | [source](https://support.logmeininc.com/lastpass/help/log4j-vulnerability-faq-for-lastpass-universal-proxy) |
| LastPass | LastPass MFA |  | Fix | Universal Proxy on Windows with Debug logging enabled are highly recommended to update to the newest version of the Universal Proxy 3.0.2 or 4.1.2 | [source](https://support.logmeininc.com/lastpass/help/log4j-vulnerability-faq-for-lastpass-universal-proxy) |
| LeanIX | All products | All versions | Fix | | [source](https://www.leanix.net/en/blog/log4j-vulnerability-log4shell) |
| Lenovo | Any 5594 UPS unit | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Any 5595 UPS unit | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | BIOS/UEFI | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Chassis Management Module 2 (CMM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Commercial Vantage | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Confluent | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | CP6000 (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-CB-10E (Lenovo) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-CB-10 (Lenovo) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-CN-10E (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-CN-10 (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-I-10 (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-SB-D20E (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-SB-D20E (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | CP-SB-D20 (ThinkAgile) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkAgile,-Product) |
| Lenovo | DM120S (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM240N (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM240S (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM3000H (ThinkSystem)| | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM5000F (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM5000H (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM5100F (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM600S (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM7000F (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM7000H (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM7100F (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | DM7100H (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Storage-,Product,-Component) |
| Lenovo | Eaton UPS Network Management Card (NMC) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Eaton UPS Network Management Card (NMC) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Fan Power Controller2 (FPC2) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Fan Power Controller (FPC) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | IBM Advanced Management Module (AMM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | IBM Advanced Management Module (AMM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Cloud Deploy | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Device Intelligence (LDI) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo DSS-G | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=the%20vulnerable%20Component.-,Software,-Product) |
| Lenovo | Lenovo Dynamic System Analysis (DSA) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Dynamic System Analysis (DSA) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Dynamic System Analysis (DSA) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Thin Installer | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo ThinkSystem Digital 2x1x16 KVM Switch, 1754-D1T | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Update Retriever | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Update Retriever | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo Vantage | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Administrator | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=the%20vulnerable%20Component.-,Software,-Product) |
| Lenovo | Lenovo XClarity Controller (XCC) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Energy Manager | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=the%20vulnerable%20Component.-,Software,-Product) |
| Lenovo | Lenovo XClarity Essentials (LXCE) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Integrator (LXCI) for Microsoft System Center | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo xClarity Integrator | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=the%20vulnerable%20Component.-,Software,-Product) |
| Lenovo | Lenovo XClarity Mobile (LXCM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Mobile (LXCM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Orchestrator (LXCO) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Lenovo XClarity Provisioning Manager (LXPM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | Network Switches | | Not vuln | Lenovo CNOS, Lenovo ENOS, IBM ENOS, Brocade FOS | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | P920 Rack Workstation | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=TBD-,ThinkStation,-Product) |
| Lenovo | SR530 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR550 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR570 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR590 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR630 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR630 V2 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR645 (ThinkSystem)| | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR650 (ThinkSystem)| | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR650 V2 (ThinkSystem)| | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR665 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR850 V2 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | SR860 V2 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | ST550 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | ST558 (ThinkSystem) | | Vulnerable | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=%C2%A0-,ThinkSystem,-Product) |
| Lenovo | System Management Module (SMM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | System Management Module (SMM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | ThinkSystem 2x1x16 Digital KVM Switch - Type 1754D1T | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | ThinkSystem DE Series Storage | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | ThinkSystem DM Series Storage | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | ThinkSystem DS Series Storage | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lenovo | ThinkSystem Manager (TSM) | | Not vuln | | [source](https://support.lenovo.com/ca/en/product_security/len-76573#:~:text=Not%20Affected-,Any%205594%20UPS%20unit,-Any%205595%20UPS) |
| Lightbend | Akka  | Unknown | Not Vuln| | [source](https://discuss.lightbend.com/t/regarding-the-log4j2-vulnerability-cve-2021-44228/9275) |
| Lightbend | Akka Serverless | Unknown | Not Vuln| | [source](https://discuss.lightbend.com/t/regarding-the-log4j2-vulnerability-cve-2021-44228/9275) |
| Lightbend | Lagom Framework | Unknown | Not Vuln by default | Users that switched from logback to log4j are affected | [source](https://discuss.lightbend.com/t/regarding-the-log4j2-vulnerability-cve-2021-44228/9275) |
| Lightbend | Play Framework| Unknown | Not Vuln by default | Users that switched from logback to log4j are affected | [source](https://discuss.lightbend.com/t/regarding-the-log4j2-vulnerability-cve-2021-44228/9275) |
| Liongard | All products  | Unknown | Investigation| | [source](https://insights.liongard.com/faq-apache-log4j-vulnerability) |
| LiquidFiles | LiquidFiles | All versions | Not vuln | |[source](https://mailchi.mp/liquidfiles/liquidfiles-log4j) |
| LiveAction | LiveNX | <21.5.1 | Fix | | [source](https://documentation.liveaction.com/LiveNX/LiveNX%2021.5.1%20Release%20Notes/Release%20Notes%20LiveNX%2021.5.1.1.3) |
| LiveAction | LiveNA | <21.5.1 | Fix | | [source](https://documentation.liveaction.com/LiveNA/LiveNA%2021.5.1%20Release%20Notes/Release%20Notes%20LiveNA%2021.5.1.1.2) |
| LogRhythm | SIEM | 7.4-7.8 | Workaround | Link is behind a login | [source](https://community.logrhythm.com/t5/Product-Security/Log4J-Remediation-Update-CloudAI-and-NetMon-Complete-LogRhythm/td-p/494350) |
| LogZilla | NEO | All versions | Not vuln | LogZilla's engine is C++ |
| LogicMonitor | LogicMonitor SaaS Platform| Unknown | Fix | Automatic update before 13th December | [source](https://communities.logicmonitor.com/topic/7472-logicmonitor-collectors-running-vulnerable-version-of-log4j-are-affected-by-log4shell-cve-2021-44228-vulnerability/) |
| Lyrasis | DSpace | 7.x | Fix/Workaround | |[source](https://groups.google.com/g/dspace-community/c/Fa4VdjiiNyE) |
| The Linux Foundation | StackStorm (ST2) | All versions | Not vuln | |[source](https://github.com/StackStorm/st2/discussions/5503) |
| The Linux Foundation | XCP-ng | All versions | Not vuln | |[source](https://xcp-ng.org/forum/topic/5315/log4j-vulnerability-impact) |
| LucaNet  | LucaNet | 12 LTS - 1911.0.192+3, 13 LTS - 2011.0.112+7, 22 LTS - 2111.0.11+9 | Fix | |[source](https://www.lucanet.com/en/blog/update-vulnerability-log4j) |

### M

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| MISP | MISP | All | Not vuln | |[source](https://twitter.com/MISPProject/status/1470051242038673412) |
| MONARC | MONARC | All | Not vuln | |[source](https://twitter.com/MONARCproject/status/1470349937443491851) |
| MailStore | MailStore | all | Not Vuln  | | [source](https://www.mailstore.com/en/blog/mailstore-affected-by-log4shell/) |
| Mailcow | Mailcow Solr Docker| < 1.8 | Fix | | [source](https://community.mailcow.email/d/1229-cve-2021-44228-vulnerability-solr) |
| ManageEngine | ADAudit Plus | Unknown | Investigation | Workaround | [source](https://pitstop.manageengine.com/portal/en/community/topic/apache-log4j-vulnerability-cve-2021-44228-1) |
| ManageEngine | ADManager Plus | Unknown | Investigation| Mitigation: set `-Dlog4j2.formatMsgNoLookups=true` in `jvm.options`. | [source](https://pitstop.manageengine.com/portal/en/community/topic/log4j-ad-manager-plus) |
| ManageEngine | Desktop Central | Unknown | Not Vuln | |[source](https://pitstop.manageengine.com/portal/en/community/topic/log4j-security-issue) |
| ManageEngine | EventLog Analyzer | Unknown | Workaround | |[source](https://pitstop.manageengine.com/portal/en/community/topic/fixing-log4j-cve-2021-44228-vulnerability-in-log360) |
| Mathworks | MATLAB | All | Not Vuln | |[source](https://www.mathworks.com/content/dam/mathworks/policies/mathworks-response-to-cve-2021-44228-log4j-vulnerability.pdf) |
| Mattermost   | Mattermost | | Not Vuln | | [source](https://forum.mattermost.org/t/security-update-log4j-security-vulnerability/12695) |
| McAfee | Data Exchange Layer (DXL) | Unknown | Not Vuln || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | Enterprise Security Manager (ESM) | 11.x | Workaround || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | McAfee Active Response (MAR) | Unknown | Not Vuln | Standalone MAR not vulnerable, for MAR included in bundle see TIE | [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | Network Security Manager (NSM) | Unknown | Not Vuln || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | Network Security Platform (NSP) | Unknown | Not Vuln || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | Threat Intelligence Exchange (TIE) | 2.2, 2.3, 3.0 | Workaround || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | ePolicy Orchestrator Agent Handlers (ePO-AH) | Unknown | Not Vuln || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | ePolicy Orchestrator Application Server (ePO) | 5.10 CU11 | Workaround || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| McAfee | ePolicy Orchestrator Application Server (ePO) | <= 5.10 CU10 | Not Vuln || [source](https://kc.mcafee.com/corporate/index?page=content&id=KB95091) |
| Meinberg | LANTIME | all | Not Vuln | | [source](https://www.meinbergglobal.com/english/sw/mbgsecurityadvisory.htm#mbgsa_535) |
| Meinberg | microSync | all | Not Vuln | | [source](https://www.meinbergglobal.com/english/sw/mbgsecurityadvisory.htm#mbgsa_535) |
| Memurai | All products | | Not Vuln | | [source](https://www.memurai.com/blog/apache-log4j2-cve-2021-44228) |
| messageconcept | PeopleSync |  All | Not vuln |  |[source](https://messageconcept.atlassian.net/wiki/spaces/PSKB/pages/2139095041/Is+PeopleSync+affected+by+Log4Shell) |
| Metabase  | Metabase                         | <0.41.4 | Fix      | Mitigations available for earlier versions                                                                | [source](https://github.com/metabase/metabase/releases/tag/v0.41.4)                                                                                                                                                                                                        |
| Micro Focus | ArcSight ESM                   | 7.2, 7.5 | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Micro Focus | ArcSight Logger                | 7.2 and above | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Micro Focus | ArcSight Recon                 | All Versions | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Micro Focus | ArcSight Intelligence          | All Versions | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Micro Focus | ArcSight Connectors            | 8.2 and above | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Micro Focus | ArcSight Transformation Hub    | All Versions | Vulnerable | | [source](https://community.microfocus.com/cyberres/b/sws-22/posts/summary-of-cyberres-impact-from-log4j-or-logshell-logjam-cve-2021-44228) |
| Microsoft | Azure AD                         | Unknown | Not Vuln | ADFS itself is not vulnerable, federation providers may be                                                | [source](https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/)                                                                                                                                                                  |
| Microsoft | Azure App Service                | Unknown | Not Vuln | This product itself is not vulnerable, Microsoft provides guidance on remediation for hosted applications | [source](https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/)                                                                                                                                                                  |
| Microsoft | Azure Application Gateway        | Unknown | Not Vuln |                                                                                                           | [source](https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/)                                                                                                                                                                  |
| Microsoft          | Azure Data Lake Store Java | < 2.3.10 | Not vuln | Fix has been made to upgrade log4j-core. But this dependency has scope 'test' meaning it is not part of the final product/artifact. So there's no risk for end users here. |[source](https://github.com/Azure/azure-data-lake-store-java/blob/ed5d6304783286c3cfff0a1dee457a922e23ad48/CHANGES.md#version-2310) |
| Microsoft | Azure DevOps       |  | Not Vuln |                                                                                                           | [source](https://devblogs.microsoft.com/devops/azure-devops-and-azure-devops-server-and-the-log4j-vulnerability/?WT.mc_id=DOP-MVP-5001511)                                                                                                                                                                  |
| Microsoft | Azure DevOps Server       | 2019-2020.1 | Vulnerable  | When Azure DevOps Server Search is configured. Uses Elasticsearch OSS 6.2.4 (vulnerable) see Elasticsearch above for mitigation                                                                                                          | [source](https://devblogs.microsoft.com/devops/azure-devops-and-azure-devops-server-and-the-log4j-vulnerability/?WT.mc_id=DOP-MVP-5001511)                                                                                                                                                                  |
| Microsoft | Azure Front Door                 | Unknown | Not Vuln |                                                                                                           | [source](https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/)                                                                                                                                                                  |
| Microsoft | Azure WAF                        | Unknown | Not Vuln |                                                                                                           | [source](https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/)                                                                                                                                                                  |
| Microsoft | Cosmos DB Kafka Connector | Fix | 1.2.1 | | [source](https://github.com/microsoft/kafka-connect-cosmosdb/releases/tag/v1.2.1) |
| Microsoft | Events Hub Extension | Fix | 3.3.1 | | [source](https://mvnrepository.com/artifact/com.microsoft.azure/azure-eventhubs-extensions/3.3.1) |
| Microsoft | Kafka Connect for Azure Cosmo DB | < 1.2.1 | Fix      |                                                                                                           | [source](https://github.com/microsoft/kafka-connect-cosmosdb/blob/0f5d0c9dbf2812400bb480d1ff0672dfa6bb56f0/CHANGELOG.md)                                                                                                                                                   |
| Microsoft | Microsoft Defender for IoT | 10.5.2 | Fix | | [source](https://docs.microsoft.com/en-us/azure/defender-for-iot/organizations/release-notes#october-2021) |
| Microsoft | Minecraft Java Edition | 1.18.1 | Fix | | [source](https://www.minecraft.net/en-us/article/minecraft-java-edition-1-18-1) |
| Microsoft | Team Foundation Server       | 2018.2+ | Vulnerable  | When Team Foundation Server Search is configured. Uses Elasticsearch OSS 5.4.1 (vulnerable) see Elasticsearch above for mitigation                                                                                                          | [source](https://devblogs.microsoft.com/devops/azure-devops-and-azure-devops-server-and-the-log4j-vulnerability/?WT.mc_id=DOP-MVP-5001511)                                                                                                                                                                  |
| MicroStrategy | Secure Enterprise | 11.1.7+ 11.2.x 11.3.x | Workaround | Workaround available, Update scheduled for Week 51/2021 | [source](https://community.microstrategy.com/s/article/MicroStrategy-s-response-to-CVE-2021-44228-The-Log4j-0-Day-Vulnerability?language=en_US) |
| MIDITEC | All | | Not vuln | MTZ Time uses Log4j v1.x | [source](https://www.miditec.de/_download/files/information/Entwarnung%20-%20Schwachstelle.pdf) |
| Milestone | VMS | Unknown | Not vuln | | [source](https://supportcommunity.milestonesys.com/s/article/Log4J-vulnerability-faq?language=en_US) |
| Minecraft | Java edition | <1.18.1 | Fix | Mitigations available for earlier versions| [source](https://www.minecraft.net/en-us/article/important-message--security-vulnerability-java-edition) |
| Mirantis      | Mirantis Container Runtime |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | Mirantis Kubernetes Engine |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | Mirantis Secure Registry   |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | Mirantis Container Cloud   |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | Mirantis OpenStack         |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | Lens                       |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mirantis      | K0s                        |  All | Not vuln |  |[source](https://github.com/Mirantis/security/blob/main/news/cve-2021-44288.md) |
| Mitel      | MiCollab |  >=7.1 to <=9.4 | Fix | Below v7.0 not vuln |[source](https://www.mitel.com/-/media/mitel/file/pdf/support/security-advisories/log4j_micollab_remediation_details.pdf) |
| Mitel      | MiContact Center  Enterprise |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiContact Center Business |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel CMG Suite |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel InAttend |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Interaction Recording (MIR) |  6.3 to 6.7 | Fix | see SA211213-17 |[source](https://www.mitel.com/-/media/mitel/file/pdf/support/security-advisories/security-bulletin_21-0010-001.pdf) |
| Mitel      | Mitel Management Gateway |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Management Portal |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Mobility Router |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Performance Analytics Server and Probe |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Standard Linux (MSL) |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Mitel Virtual Reception |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice 5000 |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice Border Gateway |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice Business |  All (excluding EX) | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice Business EX and MiConfig Wizard |  9.2 only | Fix |  |[source](https://www.mitel.com/-/media/mitel/file/pdf/support/security-advisories/security-bulletin_21-0010-004.pdf) |
| Mitel      | MiVoice Call Recording |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice Connect |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | MiVoice MX-ONE |  7.4 only | Fix |  |[source](https://www.mitel.com/-/media/mitel/file/pdf/support/security-advisories/security-bulletin_21-0010-003.pdf) |
| Mitel      | MiVoice Office 400 |  All | Not vuln |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| Mitel      | Open Integration Gateway (OIG) |  All | Investigation |  |[source](https://www.mitel.com/support/security-advisories/mitel-product-security-advisory-21-0010) |
| MongoDB | Atlas Search | Unknown | Fix | Affected and patched. No evidence of exploitation or indicators of compromise prior to the patch were discovered. | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Atlas | Unknown | Not vuln | Including Atlas Database, Data Lake, Charts | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Community Edition | Unknown | Not vuln | Including Community Server, Cloud Manager, Community Kubernetes Operators. | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Drivers | Unknown | Not vuln | | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Enterprise Advanced | Unknown | Not vuln | Including Enterprise Server, Ops Manager, Enterprise Kubernetes Operators. | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Realm | Unknown | Not vuln | including Realm Database, Sync, Functions, APIs | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| MongoDB | Tools | Unknown | Not vuln | Including Compass, Database Shell, VS Code Plugin, Atlas CLI, Database Connectors | [source](https://www.mongodb.com/blog/post/log4shell-vulnerability-cve-2021-44228-and-mongodb) |
| Moodle | Moodle | All | Not vuln | | [source](https://moodle.org/mod/forum/discuss.php?d=429966) |
| Moxa | All | All | Not vuln | | [source](https://www.moxa.com/en/support/product-support/security-advisory/moxa-s-response-regarding-the-apache-log4j-vulnerability) |

### N

| Supplier           | Product                                                            | Version  (See Status) |    Status     | Notes                                          |                                                                                                            Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| N-able             | Backup                                                             | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | Mail Assure                                                        | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | MSP Manager                                                        | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | N-central                                                          | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | Passportal                                                         | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | Risk Intelligence                                                  | Unknown  |  Vulnerable   |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | RMM                                                                | Unknown  |      Fix      |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| N-able             | Take Control                                                       | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.n-able.com/security-and-privacy/apache-log4j-vulnerability) |
| Nagios             | Nagios Core                                                       | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.nagios.com/news/2021/12/update-on-apache-log4j-vulnerability/) |
| Nagios             | Nagios XI                                                       | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.nagios.com/news/2021/12/update-on-apache-log4j-vulnerability/) |
| Nagios             | Nagios Log Server                                                      | Unknown  |   Not Vuln    |                                                |                                 [source](https://www.nagios.com/news/2021/12/update-on-apache-log4j-vulnerability/) |
| Nakivo             | Nakivo Backup & Replication                                        | Unknown  | Workaround | manual fix by removing JndiLookup.class located in libs\log4j-core-2.2.jar. [source](https://forum.nakivo.com/index.php?/topic/7574-log4j-cve-2021-44228/#comment-9145) |  [source](vendor-statements/nakivo_email.png) |
| Nelson             | Nelson                                                             | 0.16.185 |  Vulnerable   | Workaround is available, but not released yet. | [source](https://github.com/getnelson/nelson/blob/f4d3dd1f1d4f8dfef02487f67aefb9c60ab48bf5/project/custom.scala) |
| Neo4j              | Neo4j                                                              | >=4.2.12, >=4.3.8, >=4.4.1 |   Fix    |                                    | [source](https://community.neo4j.com/t/log4j-cve-mitigation-for-neo4j/48856), [source_fix](https://neo4j.com/security/log4j/?_gl=1*21owwo*_ga*MjE0NzMyNTYxMy4xNjM4MTE2NTM0*_ga_DL38Q8KGQC*MTYzOTY1NTgyMS4yNS4wLjE2Mzk2NTU4MjEuMA..&_ga=2.221851932.50302124.1639655825-2147325613.1638116534) |
| NetApp             | Brocade SAN Naviator                                               | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | Cloud Insights Acquisition Unit                                    | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | Cloud Manager                                                      | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | Cloud Secure                                                       | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | Element Plug-in for vCenter Server                                 | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | Management Services for Element Software and NetApp HCI            | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | NetApp HCI Compute Node                                            | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | NetApp SolidFire, Enterprise SDS & HCI Storage                     | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | NetApp SolidFire & HCI Management Node                             | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | NetApp SolidFire Plug-in for vRealize Orchestrator (SolidFire vRO) | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | NetApp SolidFireStorage Replication Adapter                        | Unknown  | Not Vuln |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | ONTAP Tools for VMware vSphere                                     | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | OnCommand Insight                                                  | Unknown  | Vulnerable |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/) |
| NetApp             | SnapCenter Plug-in for VMware vSphere                              | Unknown  | Workaround |                                                |                                               [source](https://security.netapp.com/advisory/ntap-20211210-0007/#:~:text=Workarounds-,snapcenter%20plug-in%20for%20vmware%20vsphere) |
| NetCore | Unimus | 2.1.4 | Fix || [source](https://download.unimus.net/unimus/Changelog.txt)|
| Netflix            | atlas                                                              |  1.6.6   |  Workaround   |                                                |                                                                                                                                                                                                    [source](https://github.com/Netflix/atlas/commit/5baff2b656a45886b85968a4b66f33bd36c648be) |
| Netflix            | dgs-framework                                                      | < 4.9.11 |      Fix      |                                                |                                                                                                                                                                                                                          [fix](https://github.com/Netflix/dgs-framework/releases/tag/v4.9.11) |
| Netflix            | spectator                                                          | < 1.0.9  |      Fix      |                                                |                                                                                                                                                                                                                               [fix](https://github.com/Netflix/spectator/releases/tag/v1.0.9) |
| Netflix            | zuul                                                               | Unknown  |  Workaround   |                                                |                                                                                                                                                                                                     [source](https://github.com/Netflix/zuul/commit/280f20cd51deb7e72275625d5ec556aae06f6a29) |
| Netgate | pfSense | All | Not vuln || [source](https://forum.netgate.com/topic/168417/java-log4j-vulnerability-is-pfsense-affected) |
| Netgear | All | | Not vuln | | [source](https://community.netgear.com/t5/Smart-Plus-and-Smart-Pro-Managed/Has-Netgear-GS748TS-been-affected-by-Log4J/m-p/2173582#M19998) |
| NetIQ | Access Manager            | >= 4.5.x & >= 5.0.x | Workaround    || [source](https://portal.microfocus.com/s/article/KM000002997)|
| NetIQ | Advanced Authentication   | >= 6.x              | Workaround    || [source](https://portal.microfocus.com/s/article/KM000003047)|
| NetIQ | eDirectory                | >= 9.2.x            | Not vuln      || [source](https://portal.microfocus.com/s/article/KM000003035)|
| NetIQ | Identity Manager          | >= 4.7.x & >= 4.8.x | Not vuln      || [source](https://portal.microfocus.com/s/article/KM000003035)|
| NetIQ | iManager                  | >= 3.2.x            | Not vuln      || [source](https://portal.microfocus.com/s/article/KM000003035)|
| Netwrix            | Netwrix Auditor                                                    |          |   Not vuln    |                                                |                                                                                                                                                                                                              [source](http://www.publicnow.com/view/EA90CB461F5F0A1BA339E2AC55C719CA5AD58CE4) |
| New Relic          | Containerized Private Minion (CPM)                                 |  3.0.55  |      Fix      |                                                |                                                                                                                                                                            [source](https://docs.newrelic.com/docs/security/new-relic-security/security-bulletins/security-bulletin-nr21-04/) |
| New Relic          | Java Agent                                                         |  6.5.1 & 7.4.1  |      Fix      |                                                |                                                                                                                                                                            [source](https://docs.newrelic.com/docs/security/new-relic-security/security-bulletins/security-bulletin-nr21-03/) |
| NextCloud | All products | | Not vuln | Invidivual plugins not developed as part of Nextcloud core may be vulnerable. |                                                                                                                                                                                                          [source](https://help.nextcloud.com/t/apache-log4j-does-not-affect-nextcloud/129244) |
| NextGen Healthcare | Mirth                                                              | Unknown  |   Not Vuln    |                                                |                                                                                                                                                                                             [source](https://github.com/nextgenhealthcare/connect/discussions/4892#discussioncomment-1789526) |
|Nomachine | All products | All versions | Not vuln | |                                                                                                                                                                                                                        [source](https://forums.nomachine.com/topic/apache-log4j-notification) |
| NSA | Ghidra| < 10.1| Fix | |                                                                            [source](https://github.com/NationalSecurityAgency/ghidra/blob/2c73c72f0ba2720c6627be4005a721a5ebd64b46/README.md#warning), [fix](https://github.com/NationalSecurityAgency/ghidra/releases/tag/Ghidra_10.1_build) |
| Nulab | Backlog | N/A (SaaS) | Fix || [source](https://nulab.com/blog/company-news/log4shell/) |
| Nulab | Backlog Enterprise (On-premises) | 1.11.6 | Fix || [source](https://nulab.com/blog/company-news/log4shell/) |
| Nulab | Cacoo | N/A (SaaS) | Fix || [source](https://nulab.com/blog/company-news/log4shell/) |
| Nulab | Cacoo Enterprise (On-premises) | 4.0.2 | Fix || [source](https://nulab.com/blog/company-news/log4shell/) |
| Nulab | Typetalk | N/A (SaaS) | Fix || [source](https://nulab.com/blog/company-news/log4shell/) |
| Nutanix | General Guidance | Nutanix updating Security Advisory #23 multiple times per day, please check source link for absolute latest status | | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | AHV | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | AOS (CE) | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | AOS (LTS) | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | AOS (STS) | All supported versions | Workaround | Non exploitable dormant code present, Patch 6.0.2.4 will remove dormant code |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Beam | SaaS | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Calm | On-Prem | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Calm | SaaS | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Data Lens | SaaS | Not vuln | WAF updated to block exploit, backend not vuln |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Era | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | File Analytics | All supported versions | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Files | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Flow | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Flow Security Central | SaaS | Fix | WAF updated to block exploit, backend production patched |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Foundation | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Frame | SaaS GovCloud | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Frame | SaaS Public | Fix | WAF updated to block exploit, backend production patched |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Insights | SaaS | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Karbon | On-Prem | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Karbon | SaaS | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | LCM | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Leap | SaaS | Not vuln | WAF updated to block exploit, backend patch pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Mine | All supported versions | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Move | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | MSP | All supported versions | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | NCC | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Objects | All supported versions | Investigation | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Prism Central | All supported versions | Vulnerable | Patch 2021.9.0.3 pending |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Sizer | SaaS | Fix | WAF updated to block exploit, backend production patched |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | Volumes | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| Nutanix | X-Ray | All supported versions | Not vuln | |                                                                                                                                                                                                                      [source](https://download.nutanix.com/alerts/Security_Advisory_0023.pdf) |
| NVIDIA | DGX systems | DGX OS 4 and DGX OS 5 | Fix | | [source](https://nvidia.custhelp.com/app/answers/detail/a_id/5294) |
| NVIDIA | vGPU software license server | 2021.7 and 2020.5 Update 1 | Workaround | | [source](https://nvidia.custhelp.com/app/answers/detail/a_id/5294) |
| NXLog | NXLog Manager |  5.x | Not Vuln | |                                                                                                                                                                                                                     [source](https://nxlog.co/news/apache-log4j-vulnerability-cve-2021-44228) |

### O

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Obsidian Dynamics | kafdrop | all | Investigation | | [source](https://github.com/obsidiandynamics/kafdrop/issues/315) |
| OCLC   | all | all | Fix | | [source](https://oc.lc/status) |
| Ogest   | all | all | Not vuln | | [source](https://www.ogest.fr/20211216-vulnerability-java-log4j) |
| Okta       | Access Gateway                                     | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | AD Agent                                           | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | Advanced Server Access                             | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | Browser Plugin                                     | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | IWA Web Agent                                      | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | LDAP Agent                                         | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | Mobile                                             | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | On-Prem MFA Agent                                  | <1.4.6                           | Fix        |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell), [fix](https://trust.okta.com/security-advisories/okta-on-prem-mfa-agent-cve-2021-44228)                |
| Okta       | Radius Server Agent                                | 2.17.0                           | Fix        |                                                    | [source/fix](https://trust.okta.com/security-advisories/okta-radius-server-agent-cve-2021-44228)                |
| Okta       | Verify                                             | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| Okta       | Workflow                                           | Unknown                          | Not Vuln   |                                                    | [source](https://sec.okta.com/articles/2021/12/log4shell)                                                                                                         |
| OneSpan    | Authentication Appliance                          | Unknown | Vulnerable | Fix availability will be announced soon | [source](https://www.onespan.com/remote-code-execution-vulnerability-in-log4j2-cve-2018-11776) |
| OneSpan    | Authentication Server                              | Unknown | Vulnerable | Fix availability will be announced soon | [source](https://www.onespan.com/remote-code-execution-vulnerability-in-log4j2-cve-2018-11776) |
| OneSpan    | Digipass Gateway                                   | Unknown | Vulnerable | Fix availability will be announced soon | [source](https://www.onespan.com/remote-code-execution-vulnerability-in-log4j2-cve-2018-11776) |
| OneSpan    | OneSpan Sign                                      | Unknown | Vulnerable | Fix availability will be announced soon | [source](https://www.onespan.com/remote-code-execution-vulnerability-in-log4j2-cve-2018-11776) |
| OneSpan    | Mobile Security Suite                              | 4.31.1  | Fix        |                                         | [source](https://www.onespan.com/remote-code-execution-vulnerability-in-log4j2-cve-2018-11776) |
| openHAB    | openHAB                                            | 3.0.4, 3.1.1                          | Fix |            | [source](https://github.com/openhab/openhab-distro/security/advisories/GHSA-j99j-qp89-pcfq) |
| OpenMRS    | Talk                                               | 2.4.0-2.4.1                      | Vulnerable | Mitigations are available, pending a new release   | [source](https://talk.openmrs.org/t/urgent-security-advisory-2021-12-11-re-apache-log4j-2/35341)                                                                  |
| OpenNMS    | Horizon (including derived Sentinels)              | < 29.0.3                         | Fix        | Workarounds are available too for earlier versions | [source](https://www.opennms.com/en/blog/2021-12-10-opennms-products-affected-by-apache-log4j-vulnerability-cve-2021-44228/)                                      |
| OpenNMS    | Meridian (including derived Minions and Sentinels) | < 2021.1.8, 2020.1.15, 2019.1.27 | Fix        | Workarounds are available too for earlier versions | [source](https://www.opennms.com/en/blog/2021-12-10-opennms-products-affected-by-apache-log4j-vulnerability-cve-2021-44228/)                                      |
| OpenNMS    | Minion appliance                                   | Unknown                          | Fix        |                                                    | [source](https://www.opennms.com/en/blog/2021-12-10-opennms-products-affected-by-apache-log4j-vulnerability-cve-2021-44228/)                                      |
| OpenNMS    | PoweredBy OpenNMS                                  | Unknown                          | Workaround |                                                    | [source](https://www.opennms.com/en/blog/2021-12-10-opennms-products-affected-by-apache-log4j-vulnerability-cve-2021-44228/)                                      |
| OpenSearch | OpenSearch                                         | < 1.2.1                          | Fix        |                                                    | [source](https://opensearch.org/blog/releases/2021/12/update-to-1-2-1/)                                                                                           |
| OpenVPN | All products |  | Not vuln | | [source](https://forums.openvpn.net/viewtopic.php?f=4&p=103724#p103750) |
| Oracle     | Database                                           | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Fusion Middleware                                  | 12.2.1.3.0 to 12.2.1.4.0                          | Fix        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 209768.1](https://support.oracle.com/rs?type=doc&id=209768.1), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [MOS note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| Oracle     | NoSQL Database                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Forms                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Golden Gate                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle Access Manager                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle Data Integrator (ODI)                          | >= 12.2.1.3.210119, Marketplace - >= 2.1.0                          | Workaround        |[Patch Available, Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| Oracle     | Oracle eBusiness Suite                          | Unknown                          | Workaround        |[MOS note 2827804.1](https://support.oracle.com/rs?type=doc&id=2827804.1)                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle Enterprise Manager                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 209768.1](https://support.oracle.com/rs?type=doc&id=209768.1), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle Enterprise Repository                          | Unknown                          | Workaround        |[Mitigation, Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| Oracle     | Oracle HTTP Server                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 209768.1](https://support.oracle.com/rs?type=doc&id=209768.1), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle Internet Directory                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 209768.1](https://support.oracle.com/rs?type=doc&id=209768.1), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle JDeveloper                          | Unknown                          | Workaround        |[Mitigation Available, Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| Oracle     | Oracle Policy Automation (OPA)                          | Unknown                          | Fix        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), MOS note 33660673           |
| Oracle     | Oracle SOA Suite                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle SQL Developer                          | 21.4                          | Fix        |                                                    | [source](https://www.oracle.com/tools/sqldev/sqldev-relnotes-21.4.html)           |
| Oracle     | Oracle VM VirtualBox                          | Unknown                          | Not Vuln        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle WebCenter Portal                          | 12.2.1.3 & 12.2.1.4 | Workaround        |  [MOS note 2827977.1](https://support.oracle.com/rs?type=doc&id=2827977.1) using Elasticsearch which uses Log4j 2.X jars  | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1)           |
| Oracle     | Oracle WebCenter Sites                          | Unknown                          | Workaround        |[Mitigation Available, Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [Support Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| Oracle     | Oracle WebLogic Server                          | 12.2.1.3.0 to 14.1.1.0.0                          | Fix        |                                                    | [source](https://www.oracle.com/security-alerts/alert-cve-2021-44228.html), [Support note 209768.1](https://support.oracle.com/rs?type=doc&id=209768.1), [Support note 2827611.1](https://support.oracle.com/rs?type=doc&id=2827611.1), [MOS Note 2827793.1](https://support.oracle.com/rs?type=doc&id=2827793.1)           |
| OTRS      | All products                                                |                        | Not Vuln      |                                                    | [source](https://portal.otrs.com/external) |
| OWASP      | ZAP                                                | < 2.11.1                         | Fix        |                                                    | [source](https://www.zaproxy.org/blog/2021-12-10-zap-and-log4shell/) |
| Owncloud       | All Products                                             | Unknown                          | Not Vuln   |                                                    | [source](https://central.owncloud.org/t/owncloud-not-directly-affected-by-log4j-vulnerability/35493)                                                                                                         |
| OVHCloud       | Logs Data Platform                                             |                           | Fix   |                                                    | [source](https://blog.ovhcloud.com/log4shell-how-to-protect-my-cloud-workloads/)                                                                                                         |
| OVHCloud       | Hosted Private Cloud powered by VMware                                             |  |           Vuln                | Deploying the workarounds provided by VMWare   | [source](https://blog.ovhcloud.com/log4shell-how-to-protect-my-cloud-workloads/) |
| OVHCloud       | ML serving                                             |                           | Fix   |                                                    | [source](https://blog.ovhcloud.com/log4shell-how-to-protect-my-cloud-workloads/)                                                                                                         |
| OVHCloud       | OVHcloud Internal Systems                                             |                           | Fix & Under Investigation   |                                                    | [source](https://blog.ovhcloud.com/log4shell-how-to-protect-my-cloud-workloads/)                                                                                                         |

### P

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Paessler | PRTG | | Not vuln | | [source](https://kb.paessler.com/en/topic/90213-is-prtg-affected-by-cve-2021-44228) |
| PagerDuty | Rundeck | 3.3+ | Fix | | [source](https://docs.rundeck.com/docs/history/CVEs/#log4shell-cves), [fix](https://github.com/rundeck/rundeck/pull/7427) |
| Palo Alto | Bridgecrew  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | CloudGenix  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | Cortex XDR Agent  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | Cortex XSOAR  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | Exact Data Matching CLI  | < 1.2 | Vulnerable | >= 1.2 Not vuln | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | GlobalProtect App  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | PAN-OS for Panorama | 9.0.x, 9.1.x, 10.0.x | Vulnerable | 8.1.x, 10.1.x Not vuln | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | PAN-OS for Firewall and Wildfire | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | Prisma Cloud Compute | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | Prisma Cloud  | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| Palo Alto | WildFire Appliance | | Not Vuln | | [source](https://security.paloaltonetworks.com/CVE-2021-44228) |
| PaperCut  | PaperCut Hive | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut MF | >= 21.0 | Workaround | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut MobilityPrint | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut MultiVerse | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut NG | >= 21.0 | Workaround | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut Online Services | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut Pocket | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut Print Logger | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| PaperCut  | PaperCut Views | | Not vuln | |[source](https://www.papercut.com/kb/Main/Log4Shell-CVE-2021-44228) |
| Parallels | Remote Application Server  | All versions | Not Vuln | | [source](https://kb.parallels.com/en/128696) |
| PDQ | PDQ Deploy | All versions | Investigation | | [source](https://www.pdq.com/blog/log4j-vulnerability-cve-2021-44228/?utm_content=190941012&utm_medium=social&utm_source=twitter&hss_channel=tw-90432152) |
| PDQ | PDQ Inventory | All versions | Investigation | | [source](https://www.pdq.com/blog/log4j-vulnerability-cve-2021-44228/?utm_content=190941012&utm_medium=social&utm_source=twitter&hss_channel=tw-90432152) |
| Pega | Pega Platform | On Prem | Fix | | [source](https://docs.pega.com/security-advisory/security-advisory-apache-log4j-zero-day-vulnerability) |
| Pexip | Endpoint Activation | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Eptools | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Infinity | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Infinity Connect client | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Microsoft Teams Connector | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | My Meeting Video | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Pexip Service | all | Fix | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | Reverse Proxy and TURN Server | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Pexip | VMR self-service portal | all | Not vuln | | [source](https://www.pexip.com/blog1.0/pexip-statement-on-log4j-vulnerability) |
| Philips | IntelliBridge Enterprise | B.13 and B.15 | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided it is customer responsibility to validate and deploy patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | IntelliSite Pathology Solution 5.1 | L1 | Vuln | | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | IntelliSpace PACS | | Workaround | Philips hosting environment is evaluating the VMware provided workaround and in the process of deploying for managed service customers. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | IntelliSpace Precision Medicine | | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided it is customer responsibility to validate and deploy patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Pathology De-identifier 1.0 | L1 | Vuln | | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Performance Bridge | 3.0 | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided by Philips, it will be Philips responsibility to validate and provide patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Pinnacle | 18.x | Vuln | | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Protocol Applications | 1.1 | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided by Philips, it will be Philips responsibility to validate and provide patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | RIS Clinic | | Vuln | | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Scanner Protocol Manager | 1.1 | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided by Philips, it will be Philips responsibility to validate and provide patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Tasy EMR | | Vuln | Software only products with customer owned Operating Systems. For products solutions where the server was provided it is customer responsibility to validate and deploy patches. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | Universal Data Manager (UDM) | 1.x,2.1.x,2.2.x,3.1.x | Workaround | Philips hosting environment is evaluating the VMware provided workaround and in the process of deploying for managed service customers. | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Philips | VuePACS | | Vuln | | [source](https://www.philips.com/a-w/security/security-advisories.html) |
| Phoenix Contact | Cloud Services | | Vulnerable | Remediations are being implemented | [source](https://dam-mdc.phoenixcontact.com/asset/156443151564/1a0f6db6bbc86540bfe4f05fd65877f4/Vulnerability_Statement_Log4J_20211215.pdf) |
| Phoenix Contact | Physical products containing firmware | |  Not vuln | | [source](https://dam-mdc.phoenixcontact.com/asset/156443151564/1a0f6db6bbc86540bfe4f05fd65877f4/Vulnerability_Statement_Log4J_20211215.pdf) |
| Phoenix Contact | Software products | |  Not vuln | | [source](https://dam-mdc.phoenixcontact.com/asset/156443151564/1a0f6db6bbc86540bfe4f05fd65877f4/Vulnerability_Statement_Log4J_20211215.pdf) |
| Planon Software | Planon Universe | all | Not vuln | | [source](https://my.planonsoftware.com/uk/news/log4j-impact-on-planon/) |
| Plex | Industrial IoT | | Not vuln | Mitigation already applied, patch will be issued today | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Plex | Media Server | | Not vuln | | [source](https://forums.plex.tv/t/seeking-information-is-plex-media-server-vulnerable-to-the-cve-2021-44228-log4j-vulnerability/763642) |
| Polycom | Poly Clariti Core/Edge (a.k.a. DMA/CCE) | 9.0 and above | Fix | | [source](https://support.polycom.com/content/dam/polycom-support/global/documentation/plygn-21-08-poly-systems-apache.pdf)|
| Polycom | Poly Clariti Relay version 1.x | 1.0.2 | Fix | | [source](https://support.polycom.com/content/dam/polycom-support/global/documentation/plygn-21-08-poly-systems-apache.pdf)|
| Polycom | Poly RealConnect for Microsoft Teams and Skype for Business | | Workaround | | [source](https://support.polycom.com/content/dam/polycom-support/global/documentation/plygn-21-08-poly-systems-apache.pdf)|
| Polycom | Cloud Relay (OTD and RealConnect hybrid use case) | | Investigation | | [source](https://support.polycom.com/content/dam/polycom-support/global/documentation/plygn-21-08-poly-systems-apache.pdf)|
| Polycom | RealAccess  | | Workaround | | [source](https://support.polycom.com/content/dam/polycom-support/global/documentation/plygn-21-08-poly-systems-apache.pdf)|
| Portex | Portex | <3.0.2 | Fix | | [source](https://github.com/katjahahn/PortEx/releases)|
| Postgres | PostgreSQL JDBC | | Not vuln | | [source](https://www.postgresql.org/about/news/postgresql-jdbc-and-the-log4j-cve-2371/) |
| PowerDNS | dnsdist | | Not vuln | | [source](https://blog.powerdns.com/2021/12/16/powerdns-and-log4j-log4shell/) |
| PowerDNS | PowerDNS Authoritative | | Not vuln | | [source](https://blog.powerdns.com/2021/12/16/powerdns-and-log4j-log4shell/) |
| PowerDNS | PowerDNS Recursor | | Not vuln | | [source](https://blog.powerdns.com/2021/12/16/powerdns-and-log4j-log4shell/) |
| Progress | DataDirect Hybrid Data Pipeline | | Workaround | | [source](https://www.progress.com/security), [mitigations](https://knowledgebase.progress.com/articles/Knowledge/Is-Hybrid-Data-Pipeline-vulnerable-CVE-2021-44228-Log4j) |
| Progress | OpenEdge | | Workaround | | [source](https://www.progress.com/security), [mitigations](https://knowledgebase.progress.com/articles/Knowledge/Is-OpenEdge-vulnerable-to-CVE-2021-44228-Log4j) |
| Proofpoint | Archiving Appliance | | Vulnerable | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Archiving Backend | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Cloud App Security Broker | | Vulnerable | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Cloudmark Cloud/Cloudmark Hybrid | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Cloudmark on Premise | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Content Patrol | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Data Discover | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | DLP Core Engine | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Email Continuity | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Email Fraud Defense (EFD) | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Email Protection on Demand (PoD), including Email DLP and Email Encryption | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | mail Protection On-Premises (PPS), including Email DLP and Email Encryption | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Email Security Relay | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Endpoint DLP | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Essentials Archive | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Essentials Email | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Insider Threat Management On-prem | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Insider Threat Management SaaS | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Isolation | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | ITM SaaS Endpoint Agents | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Meta/ZTNA | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Nexus People Risk Explorer | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Proofpoint Compliance Gateway | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Secure Email Relay | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Secure Share | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Security Awareness Training | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Sentrion | | Fix | Version 4.4 and earlier are not vulnerable. For version 4.5 patches have been made available to remediate the vulnerability. | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Social Discover | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | SocialPatrol | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Targeted Attack Protection (TAP) | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Threat Response (TRAP) | | Not vuln | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Web Gateway | | Fix | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proofpoint | Web Security | | Vulnerable | | [source](https://www.proofpoint.com/us/blog/corporate-news/proofpoints-response-log4j-vulnerability) |
| Proxmox | Backup Server | | Not vuln | | [source](https://forum.proxmox.com/threads/log4j-exploit-what-to-do.101254/#post-436880) |
| Proxmox | Mail Gateway | | Not vuln | | [source](https://forum.proxmox.com/threads/log4j-exploit-what-to-do.101254/#post-436880) |
| Proxmox | VE | | Not vuln | | [source](https://forum.proxmox.com/threads/log4j-exploit-what-to-do.101254/#post-436880) |
| PTC | Windchill PDMLink | 12.0.2.0, 12.0.2.1, 12.0.2.2 | Workaround | | [source](https://www.ptc.com/en/support/article/CS358789) |
| PTV Group                                       | PTV Arrival Board / Trip Creator / EM Portal    | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Balance and PTV Epics                       | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Developer                                   | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Drive&Arrive App                            | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Drive&Arrive                                | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Hyperpath                                   | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV MaaS Modeller                               | Unknown | Vulnerable    |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Map&Guide internet                          | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Map&Guide intranet                          | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Map&Market                                  | Unknown | Vulnuerable |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Navigator App                               | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Navigator Licence Manager                   | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Optima                                      | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Road Editor                                 | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Route Optimiser CL                          | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Route Optimiser ST (on prem - xServer2)     | Unknown | Fix | Fixed by integrating Log4j 2.16.0. and Patch 34 for Version 2019.1, Patch 28 for Version 2020.1 or Patch 16 for Version 2021.1 (15.12.21)      | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Route Optimiser ST (TourOpt)                | Unknown | Not vuln |  | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Route Optimizer SaaS / Demonstrator         | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV TLN planner internet                        | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV TRE and PTV Tre-Addin                       | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Vissim                                      | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Vistro                                      | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Visum                                       | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Visum Publisher                             | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV Viswalk                                     | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV xServer < 1.34 (on prem)                    | Unknown | Not vuln      |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV xServer 1.34 (on prem)                      | Unknown | Vulnerable    |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV xServer 2.x (on prem)                       | Unknown | Vulnerable    |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| PTV Group                                       | PTV xServer internet 1 / PTV xServer internet 2 | Unknown | Fix           |       | [source](https://company.ptvgroup.com/en/resources/service-support/log4j-latest-information) |
| Pulse Secure | Ivanti Connect Secure (ICS) | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Ivanti Neurons for secure Access | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Ivanti Neurons for ZTA | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Connect Secure | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Desktop Client | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Mobile Client | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse One | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Policy Secure | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Secure Services Director | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Secure Virtual Traffic Manager | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse Secure Web Application Firewall | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Pulse Secure | Pulse ZTA | | Not Vuln | | [source](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB44933/) |
| Puppet | Continuous Delivery for Puppet Enterprise | 3.x, < 4.10.2| Fix | Update available for version 4.x, mitigations for 3.x which is EOL| [source](https://puppet.com/blog/puppet-response-to-remote-code-execution-vulnerability-cve-2021-44228/), [workaround](https://puppet.com/docs/continuous-delivery/4.x/cd_release_notes.html#cd_release_notes-version-4-10-3),[mitigations](https://support.puppet.com/hc/en-us/articles/360046708133-Puppet-Response-to-CVE-2021-44228-FAQ/) |
| Puppet | Puppet agents | | Not Vuln | | [source](https://puppet.com/blog/puppet-response-to-remote-code-execution-vulnerability-cve-2021-44228/) |
| Puppet | Puppet Enterprise| | Not Vuln | | [source](https://puppet.com/blog/puppet-response-to-remote-code-execution-vulnerability-cve-2021-44228/) |
| PuTTY | PuTTY | | Not Vuln | | [source](https://www.chiark.greenend.org.uk/~sgtatham/putty/) |
| Pyramid Analytics                               | Pyramid Analytics                               | All     | Not vuln      |       | [source](https://community.pyramidanalytics.com/t/83hjjt4/log4j-security-vulnerability-pyramid) |

### Q

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Qconferencing | FaceTalk | | Fix | | [source](https://qconferencing.com/status-vulnerability-log4j-en-qconferencing/) |
| QlikTech International | Compose | | Investigation | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QlikTech International | Nprinting | | Not Vuln | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QlikTech International | QEM products | | Investigation | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QlikTech International | Qlik Replicate | | Investigation | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QlikTech International | Qlik Sense Enterprise | | Not Vuln | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QlikTech International | QlikView | | Not Vuln | | [source](https://community.qlik.com/t5/Support-Updates-Blog/Vulnerability-Testing-Apache-Log4j-reference-CVE-2021-44228-also/ba-p/1869368) |
| QNAP | General information QNAP | | Investigation | Applications maintained by a third-party are under investigation. | [source](https://www.qnap.com/en-uk/security-advisory/qsa-21-58) |
| QNAP | Qsirch | | Not Vuln | | [source](https://www.qnap.com/en-uk/security-advisory/qsa-21-58) |
| QNAP | QES Operating System | | Not Vuln | | [source](https://www.qnap.com/en-uk/security-advisory/qsa-21-58) |
| QNAP | QTS operating system | | Not Vuln | | [source](https://www.qnap.com/en-uk/security-advisory/qsa-21-58) |
| QNAP | QuTS hero operating system | | Not Vuln | | [source](https://www.qnap.com/en-uk/security-advisory/qsa-21-58) |
| QOS.ch          | SLF4J Simple Logging Facade for Java | |  | SLF4J API doesn't protect against the vulnerability when using a vulnerable version of log4j | [source](http://slf4j.org/log4shell.html) |
| Quadira | All |  | Not vuln |  | [source](vendor-statements/Quadira.png) |
| QUEST | Quest KACE SMA | | Not Vuln | | [source](https://support.quest.com/kace-systems-management-appliance/kb/335869/are-the-kace-sma-and-kace-sda-appliances-affected-by-cve-2021-44228) |
| QUEST | Foglight | 5.9 | Not Vuln | | [source](https://support.quest.com/fr-fr/foglight/kb/335908/are-currently-supported-versions-of-foglight-affected-by-the-latest-log4j-2-vulnerability-apache-log4j-2-cve-2021-44228?kblang=en-US) |
| QUEST | Foglight | 6.0 | Workaround | | [source](https://support.quest.com/fr-fr/foglight/kb/335908/are-currently-supported-versions-of-foglight-affected-by-the-latest-log4j-2-vulnerability-apache-log4j-2-cve-2021-44228?kblang=en-US) |

### R

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Red Hat         | A-MQ Clients 2 |  | Not Vuln | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat build of Quarkus |  | Not Vuln | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat CodeReady Studio 12 |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Data Grid 8 |  | Fixed | [RHSA-2021:5132](https://access.redhat.com/errata/RHSA-2021:5132)| [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Descision Manager 7 |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Integration Camel K |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Integration Camel Quarkus |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat JBoss A-MQ Streaming |  | Fixed | [RHSA-2021:5133](https://access.redhat.com/errata/RHSA-2021:5133)| [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat JBoss Enterprise Application Platform 6 |  | Not Vuln | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat JBoss Enterprise Application Platform Expansion Pack |  | Not Vuln | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat JBoss Fuse 7 |  | Fixed | [RHSA-2021:5134](https://access.redhat.com/errata/RHSA-2021:5134) | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Application Runtimes |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Container Platform 3.11 openshift3/ose-logging-elasticsearch5 |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Container Platform 4 openshift4/ose-logging-elasticsearch6 |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Container Platform 4 openshift4/ose-metering-hive |  | Fixed | [RHSA-2021:5108](https://access.redhat.com/errata/RHSA-2021:5108) | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Container Platform 4 openshift4/ose-metering-presto |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenShift Logging logging-elasticsearch6-container |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat OpenStack Platform 13 (Queens) opendaylight |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Process Automation 7 |  | Vulnerable | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Single Sign-On 7 |  | Not Vuln | | [source](https://access.redhat.com/security/cve/cve-2021-44228) |
| Red Hat         | Red Hat Virtualization 4 |  | Not Vuln | | [source](https://access.redhat.com/security/cve/CVE-2021-4104#:~:text=affected%20packages%20and%20issued%20red%20hat%20security%20errata) |
| Redgate | Flyway | all | Not Vuln | Only vulnerable when using non-default config. | [source](https://flywaydb.org/blog/flyway-log4j-vulnerability) |
| Redis | Jedis | 3.7.1, 4.0.0-rc2 | Fix | Jedis uses the affected library in test suites only. | [source](https://redis.com/security/notice-apache-log4j2-cve-2021-44228/) |
| Redis | Redis Enterprise & Open Source | all | Not Vuln | Redis Enterprise and Open Source Redis (self-managed software product) does not use Java and is therefore not impacted by this vulnerability | [source](https://redis.com/security/notice-apache-log4j2-cve-2021-44228/) |
| ResMed | AirView | | Not Vuln | | [source](https://www.resmed.com/en-us/security/) |
| ResMed | myAir | | Not Vuln | | [source](https://www.resmed.com/en-us/security/) |
| Ricoh | Commercial & Industrial Printing - Garment Printers | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Commercial & Industrial Printing - Production Printers | | Investigation | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Digital Duplicators | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - FAX | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Interactive Whiteboards | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Multifunction Printers/Copiers - Black & White MFP | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Multifunction Printers/Copiers - Color MFP | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Multifunction Printers/Copiers - Wide Format MFP | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Printers - Black & White Laser Printers | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Printers - Color Laser Printers | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Printers - Gel Jet Printers | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Printers - Handy Printers | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Printers - Printer based MFP | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Projectors | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Office Products - Video Conferencing | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Card Authentication Package Series | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Certificate Enrolment Service | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Device Manager NX Accounting | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Device Manager NX Enterprise | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Device Manager NX Lite | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Device Manager NX Pro | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Docuware | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Enhanced Locked Print Series | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - GlobalScan NX | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Intelligent Barcode Solution | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - myPrint | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Printer Driver Packager NX | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - @Remote Connector NX | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Ricoh Print Management Cloud | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Ricoh Smart Integration (RSI) applications | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Ricoh Smart Integration (RSI) Platform and its applications | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Ricoh Streamline NX V2 | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Ricoh Streamline NX V3 | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Scan Workflow Navigator | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Ricoh | Software & Solutions - Streamline NX Share | | Not Vuln | | [source](https://www.ricoh-europe.com/news-events/news/notice-potential-impact-of-apache-log4j-vulnerability-towards-ricoh-products-and-services/) |
| Riverbed        | AppResponse11 | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Aternity | | Investigation | See source for latest updates | [source](https://aternity.force.com/customersuccess/s/article/Apache-Log4j-Zero-Day-Exploit) |
| Riverbed        | Client Accelerator Controllers and Client Accelerator (aka SteelCentral Controller for SteelHead Mobile and SteelHead Mobile) | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Flow Gateway | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | FlowTraq | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Modeler | | Investigation | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetAuditor Desktop | | Investigation | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetAuditor Web | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetCollector | | Investigation | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetExpress | | Investigation | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetIM 1.x | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetIM 2.x | | Vulnerable | Patches planned | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetIM Test Engine | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetPlanner | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | NetProfiler | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Packet Analyzer | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Packet Trace Warehouse | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Portal 1.x | | Vulnerable | Includes Log4j 2.2 | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Portal 3.x | | Vulnerable | Includes Log4j 2.13 | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SaaS Accelerator | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Scon CX | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Scon EX Analytics | | Vulnerable | Patches planned | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Scon EX Director | | Vulnerable | Patches planned | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Scon EX FlexVNF | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SteelCentral Controller for SteelHead | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SteelFusionCore (appliance, virtual) | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SteelFusion Edge | | Not vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SteelHead CX (appliance, virtual, cloud) | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | SteelHead Interceptor | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Transaction Analyzer Agents | | Not vuln | Log4j not in use | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | Transaction Analyzer | | Investigation | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | UCExpert | | Vulnerable | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| Riverbed        | WinSec Controller for SteelHead (WSC) | | Not Vuln | | [source](https://supportkb.riverbed.com/support/index?page=content&id=S35645&actp=LIST_RECENT) |
| RocketChat |All|All|Not Vuln||[source](https://rocket.chat/blog/log4j-software-vulnerability)|
| Rockwell Automation | Warehouse Management | 4.01.00, 4.02.00, 4.02.01, 4.02.02 | Vulnerable | Patch under development | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Rockwell Automation | MES EIG | 3.03.00 | Vulnerable | Product discontinued. Customers should upgrade to EIG Hub if possible or work with their local representatives about alternative solutions. | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Rockwell Automation | Industrial Data Center | Gen 1, Gen 2, Gen 3, Gen 3.5 | Workaround | Follow the mitigation instructions outlined by VMware in VMSA-2021-0028 | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Rockwell Automation | VersaVirtual | Series A | Workaround | Follow the mitigation instructions outlined by VMware in VMSA-2021-0028 | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Rockwell Automation | FactoryTalk Analytics DataFlowML | 4.00.00 | Vulnerable | Patch under development | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| Rockwell Automation | FactoryTalk Analytics DataView | 3.03.00 | Vulnerable | Patch under development | [source](https://rockwellautomation.custhelp.com/app/answers/answer_view/a_id/1133605) |
| RSA             | NetWitness Orchestrator | >= 6.0 | Workaround | Mitigation for the ThreatConnect Application server is available, no impact described | [source](https://community.rsa.com/t5/netwitness-platform-product/netwitness-apache-vulnerability-log4j2-cve-2021-44228-nbsp/ta-p/660540) |
| RSA             | NetWitness Platform | 11.4 | Workaround | It is theoretically possible to exploit the vulnerability to gain shell access to the NetWitness Platform | [source](https://community.rsa.com/t5/netwitness-platform-product/netwitness-apache-vulnerability-log4j2-cve-2021-44228-nbsp/ta-p/660540) |
| RSA             | NetWitness Platform | >= 11.5 | Workaround | It is possible to leak system configuration data | [source](https://community.rsa.com/t5/netwitness-platform-product/netwitness-apache-vulnerability-log4j2-cve-2021-44228-nbsp/ta-p/660540) |
| RSA             | SecurID Authentication Manager |  | Not Vuln | Version 8.6 Patch 1 contains a version of log4j that is vulnerable, but this vulnerability is not exploitable. | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| RSA             | SecurID Authentication Manager Prime |  | Not Vuln | | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| RSA             | SecurID Authentication Manager WebTier |  | Not Vuln | | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| RSA             | SecurID Governance and Lifecycle Cloud (SecurID G&L Cloud) |  | Not Vuln | | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| RSA             | SecurID Governance and Lifecycle (SecurID G&L) |  | Not Vuln | | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| RSA             | SecurID Identity Router (On-Prem component of Cloud Authentication Service) |  | Not Vuln | | [source](https://community.rsa.com/t5/general-security-advisories-and/rsa-customer-advisory-apache-vulnerability-log4j2-cve-2021-44228/ta-p/660501) |
| Ruckus          | FlexMaster |  | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |
| Ruckus          | SmartZone 100 (SZ-100) | 5.1 to 6.0 | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |
| Ruckus          | SmartZone 144 (SZ-144) | 5.1 to 6.0 | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |
| Ruckus          | SmartZone 300 (SZ-300) | 5.1 to 6.0 | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |
| Ruckus          | Unleashed |  | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |
| Ruckus          | Virtual SmartZone (vSZ) | 5.1 to 6.0 | Vuln | Additional details in [PDF](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=pdf)/[Text](https://support.ruckuswireless.com/security_bulletins_downloads/313?type=txt) (Sign-in Required) | [source](https://support.ruckuswireless.com/security_bulletins/313) |

### S

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| SAE IT-systems  | codeIT Runtime  | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | codeIT Workbench | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | connectIT       | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | net-line series5 | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | setIT           | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | SG-50 / Kombisafe | all | Investigation | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | Straton Runtime   | all | Investigation | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | Straton Workbench | all | Investigation | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | System-4        | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | T10/T7 Touch panel | all | Investigation | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | visIT Runtime   | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| SAE IT-systems  | visIT Workbench | all | Not vuln | | [source](https://www.sae-it.com/nc/de/news/sicherheitsmeldungen.html?tx_saenews_saenews%5Bnews%5D=484&tx_saenews_saenews%5Baction%5D=show&tx_saenews_saenews%5Bcontroller%5D=News&cHash=ad11bc1ce9c7212cc27d45211b855e97) |
| Safe            | FME Server      | | Investigation | | [source](https://community.safe.com/s/article/Is-FME-Server-Affected-by-the-Security-Vulnerability-Reported-Against-log4j) |
| SailPoint       | IdentityIQ      | 8.0 or later | Workaround      |                 | [source](https://community.sailpoint.com/t5/IdentityIQ-Blog/IdentityIQ-log4j-Remote-Code-Execution-Vulnerability/m-p/206681#M342) |
| Salesforce      | All products    | | Investigation | | [source](https://status.salesforce.com/generalmessages/826) |
| SAP             | S/4 HANA On-Premise on ABAP | | Not Vuln | | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | S/4 HANA Cloud Customer systems | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | S/4 HANA Digital Payments Add-On | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | BusinessObjects Business Intelligence | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | BusinessObjects Explorer | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | BusinessObjects Data Services | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | BusinessObjects Financial Information Management | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | BusinessObjects Knowledge Accelerator | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | HANA Database | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | HANA Smart Data Integration | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | HANA Streaming Analytics | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | HANA Spatial Service | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | HANA Streaming Analytics | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | Integrated Business Planning for Supply Chain – Customer systems | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | NetWeaver Application Server for ABAP | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | SuccessFactors Litmos | | Not Vuln | (behind login) | [source](https://support.sap.com/content/dam/support/en_us/library/ssp/my-support/trust-center/sap-tc-01-5025.pdf) |
| SAP             | Customer Checkout PoS / manager | 2.0 FP09, 2.0 FP10, 2.0 FP11 PL06 (or lower) and 2.0 FP12 PL04 (or lower) | Fix | SAP note 3130499 | [source](https://launchpad.support.sap.com/#/notes/0003130499) |
| SAP             | XS Advanced Runtime | 1.0.140 or lower | Fix | SAP note 3130698 | [source](https://launchpad.support.sap.com/#/notes/3130698) |
| SAS Institute   | JMP | | Not vuln | | [source](https://support.sas.com/content/support/en/security-bulletins/remote-code-execution-vulnerability-cve-2021-44228.html) |
| SAS Institute   | SAS Cloud Solutions | | Workaround | | [source](https://support.sas.com/content/support/en/security-bulletins/remote-code-execution-vulnerability-cve-2021-44228.html) |
| SAS Institute   | SAS Profile | | Fix | | [source](https://support.sas.com/content/support/en/security-bulletins/remote-code-execution-vulnerability-cve-2021-44228.html) |
| Schneider Electric | All other products  |  | Investigation | | [source](https://download.schneider-electric.com/files?p_Doc_Ref=SESB-2021-347-01) |
| Schneider Electric | EcoStruxure IT Expert  |  | Fix | cloud-based offer; no customer action required.  | [source](https://download.schneider-electric.com/files?p_Doc_Ref=SESB-2021-347-01) |
| Schneider Electric | EcoStruxure IT Gateway  | 1.5.0 - 1.13.0 | Vulnerable | | [source](https://download.schneider-electric.com/files?p_Doc_Ref=SESB-2021-347-01) |
| Schneider Electric | EcoStruxure IT Gateway  | 1.13.1.5 | Fix | | [source](https://download.schneider-electric.com/files?p_Doc_Ref=SESB-2021-347-01) |
| SecurityHive | All products | All | Not vuln | | [source](https://blog.securityhive.nl/security-info/securityhive-informs-log4j-vulnerable-customers-using-threat-intelligence/) |
| SecurityRoots | Dradis Professional | All | Not vuln  |  | [source](screenshotemail) |
| Seafile  | Seafile Server | | Fix | | [source](https://forum.seafile.com/t/security-advisory-seafile-servers-vulnerability-to-log4shell-log4j-vulnerability-cve-2021-44228/15590) |
| Seagull Scientific | BarTender | All | Not vuln | | [source](https://support.seagullscientific.com/hc/en-us/articles/4415794235543-Apache-Log4Shell-Vulnerability) |
| Security Onion Solutions | Security Onion | 2.3.90 20211210 | Fix | | [source](https://blog.securityonion.net/2021/12/security-onion-2390-20211210-hotfix-now.html) |
| Sentry.io | Self Hosted and SaaS | All Versions | Not Vuln | Not affected as it is written in Python and Rust. Makes use of unaffected versions of log4j 1.x in Kafka and Zookeeper subsystems | [source](https://blog.sentry.io/2021/12/15/sentrys-response-to-log4j-vulnerability-cve-2021-44228) |
| Scootersoftware | Beyond Compare | All | Not Vuln | | [source](https://www.scootersoftware.com/index.php) |
| Shibboleth      | Shibboleth IdP/SP | | Not Vuln |  | [source](https://shibboleth.net/pipermail/announce/2021-December/000253.html) |
| Siemens     | Advantage Navigator Cloud Service | | Investigation | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Advantage Navigator Software Proxy | all | Investigation | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Capital (and its derivatives) | >= 2019.1 SP1912 | Workaround | Only vulnerable if Teamcenter integration feature is used | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Comfy | | Investigation | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Comos Desktop App | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Desigo CC Advanced Reporting | V4.0, V4.1, V4.2, V5.0, V5.1 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Desigo CC Info Center | V5.0, V5.1 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | E-Car OC Cloud Application | | Fix | Vulnerability fixed on central cloud service starting2021-12-13; no user actions necessary | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | EnergyIP | | Investigation | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | EnergyIP Prepay | 3.7, 3.8 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Enlighted | | Investigation | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Geolus | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | GMA-Manager | > V8.6.2j-398 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | HCRA | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | HES UDIS | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Industrial Edge Management App (IEM-App) | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Industrial Edge Management OS (IEM-OS) | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Industrial Edge Manangement Hub | all | Fix | Vulnerability fixed on central cloud service starting 2021-12-13; no user actions necessary | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | LOGO! Soft Comfort | all | Workaround | Only LOGO! Web Projects deployed to AWS are potentially affected | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Mendix Applications | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Mindsphere Cloud Application | < 2021-12-11 | Fix | Vulnerability fixed on central cloud service starting2021-12-11; no user actions necessary | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Opscenter Intelligence | >= 3.2 | Workaround | Only OEM version that ships Tableau is affected | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Operation Scheduler |  >= V1.1.3 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | RUGGEDCOM ELAN | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | RUGGEDCOM MAESTRO | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SIGUARD DSA | V4.2, V4.3, V4.4 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SIMATIC WinCC V7.4 | < V7.4 SP1 | Fix | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SINAMICS TEC - SDK | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SINUMERIK Analyze MyWorkpiece / Capture | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SINUMERIK Optimize MyMachine | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SiPass Integrated | V2.80, V2.85 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Siveillance Command |  >= 4.16.2.1 | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Siveillance Control Pro | all | Fix | Hotfix available for versions >= V2.1 | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Siveillance Control Pro | >= V2.1 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Siveillance Identity | V1.5, V1.6 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Siveillance Vantage | all | Vulnerable | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | SIZER Design Tool for SINAMICS | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Solid Edge | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Solid Edge Technical Publication | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Solid Edge Wiring and Harness Design | >= 2020 SP2002 | Workaround | Only affected if Teamcenter integration feature is used | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Spectrum Power 4 | all versions only with component jROS in version 3.0.0 | Fix | Patch available for V4.70 SP9 | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Spectrum Power 7 | all except < V2.30 SP2 without component jROS | Fix | Patch available for V21Q4 | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Teamcenter | all | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Teamcenter Integration for NX (TcIN) | <= NX 2007 | Workaround | Also known as "NX Managed Mode" | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | VeSys | >= 2019.1 SP1912 | Workaround | Only vulnerable if Teamcenter integration feature is used | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | XHQ | | Not Vuln | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Xpedition EDM Client | VX.2.6-VX.2.10 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Xpedition EDM Server | VX.2.6-VX.2.10 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Siemens     | Xpedition Package Integrator | VX.2.6-VX.2.10 | Workaround | | [source](https://cert-portal.siemens.com/productcert/pdf/ssa-661247.pdf) |
| Sitecore    | Sitecore Content Hub | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore CDP | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Personalize | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Boxever | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore OrderCloud | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Moosend | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Send | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Discover | | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore XP | <= 9.1 (with SOLR as Content Search provider) | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore XP | >= 9.2 (with SOLR as Content Search provider) | Workaround | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore XP | all (with Azure Search as Content Search provider) | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Managed Cloud | customers who host Solr using SearchStax | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Managed Cloud | customers who bring their own Solr | Workaround | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Sitecore    | Sitecore Managed Cloud | customers who do not use Solr | Not Vuln | | [source](https://support.sitecore.com/kb?id=kb_article_view&sysparm_article=KB1001391) |
| Snow Software | Snow Commander | 8.0.x - 8.9.x | Workaround | | [source](https://community.snowsoftware.com/s/article/LOG4J-Vulnerability), [workaround](https://community.snowsoftware.com/s/article/SnowCommander-LOG4J2-XML-library-version-used-is-exposed-to-VULNERABILITY-CVE-2021-44228)|
| Snow Software | VM Access Proxy | >= 3.0 | Workaround | | [source](https://community.snowsoftware.com/s/article/LOG4J-Vulnerability), [workaround](https://community.snowsoftware.com/s/article/VM-ACCESS-PROXY-LOG4J2-XML-library-version-used-is-exposed-to-VULNERABILITY-CVE-2021-44228)|
| SolarWinds      | Database Performance Analyzer | 2021.1.x, 2021.3.x, 2022.1.x | Workaround | | [source](https://www.solarwinds.com/trust-center/security-advisories/cve-2021-44228), [workaround](https://support.solarwinds.com/SuccessCenter/s/article/Database-Performance-Analyzer-DPA-and-the-Apache-Log4j-Vulnerability-CVE-2021-44228?language=en_US) |
| SolarWinds      | Orion Platform core | | Not vuln | | [source](https://www.solarwinds.com/trust-center/security-advisories/cve-2021-44228) |
| SolarWinds      | Server & Application Monitor | >= 2020.2.6 | Workaround | | [source](https://www.solarwinds.com/trust-center/security-advisories/cve-2021-44228), [workaround](https://support.solarwinds.com/SuccessCenter/s/article/Server-Application-Monitor-SAM-and-the-Apache-Log4j-Vulnerability-CVE-2021-44228?language=en_US) |
| Soliton Systems | MailZen Management Portal - On-Premise | 2.36.2, 2.37.3, 2.38.2 | Fix | | [source](https://blog.solitonsystems.com/news/update-on-log4j-vulnerability#:~:text=mailzen%20management%20portal%20%E2%80%93%20on-premise) |
| Soliton Systems | MailZen Management - Cloud Service | all | Fix | | [source](https://status.solitonsystems.com/) |
| Soliton Systems | MailZen Push Server | all | Fix | | [source](https://status.solitonsystems.com/) |
| Soliton Systems | Other products | all | Not vuln | | [source](https://blog.solitonsystems.com/news/update-on-log4j-vulnerability) |
| SonarSource     | SonarCloud |  | Fix | | [source](https://community.sonarsource.com/t/sonarqube-sonarcloud-and-the-log4j-vulnerability/54721) |
| SonarSource     | SonarQube | | Workaround | | [source](https://community.sonarsource.com/t/sonarqube-sonarcloud-and-the-log4j-vulnerability/54721) |
| SonicWall       | Access Points |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Analytics |  | Investigation | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Analyzer |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Capture Client & Capture Client Portal |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Capture Security Appliance  |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | CAS |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Email Security | 10.0.12 | Fix | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Gen5 Firewalls (EOS) |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Gen6 Firewalls |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | Gen7 Firewalls |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | GMS |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | MSW |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | NSM |  | Investigation | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | SMA 1000 | | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | SMA 100 |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | SonicCore |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | SonicWall Switch |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | WAF |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | WNM |  | Not vuln | |  [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| SonicWall       | WXA |  | Not vuln | | [source](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2021-0032) |
| Sophos          | Cloud Optix |  | Fix | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Reflexion |  | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | SG UTM | All | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | SG UTM Manager (SUM)  | All | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos Central |  | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos Firewall | All | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos Home |  | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos Mobile EAS Proxy | 9.7.2 | Fix | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos Mobile |  | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| Sophos          | Sophos ZTNA |  | Not Vuln | | [source](https://www.sophos.com/en-us/security-advisories/sophos-sa-20211210-log4j-rce) |
| SOS (Berlin)    | Jobscheduler | 1.12.15, 1.13.10, 2.2.0, 2.1.3 | Fix | | [source](https://www.sos-berlin.com/en/news-maintenance-releases-and-patches-mitigation-log4j-vulnerabilities) |
| Specops Software | All |  | Not Vuln | | [source](https://specopssoft.com/blog/apache-log4j-vulnerability/) |
| Splunk          | Add-On: Java Management Extensions | 3.0.0, 2.1.0 | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Add-On: JBoss | 3.0.0, 2.1.0 | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Add-On: Tomcat | 3.0.0, 2.1.0 | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Admin Config Service | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Analytics Workspace | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Behavior Analytics | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Dashboard Studio | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Data Stream Processor | DSP 1.0.x, DSP 1.1.x, DSP 1.2.x | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Developer Tools: AppInspect | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Enterprise Security | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Intelligence Management (TruSTAR) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | IT Service Intelligence (ITSI) | 4.11.x, 4.10.x, 4.9.x, 4.8.x, 4.7.x, 4.4.x | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | KV Service | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Mission Control | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | MLTK | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Operator for Kubernetes | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Security Analytics for AWS | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | SignalFx Smart Agent | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | SOAR Cloud (Phantom) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | SOAR (On-Premises) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Application Performance Monitoring | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Augmented Reality | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Cloud Data Manager (SCDM) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Connect for Kafka | <2.0.4 | Fix | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Connect for Kubernetes | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Connect for SNMP | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Connect for Syslog | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk DB Connect | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Enterprise | All supported non-Windows versions of 8.1.x and 8.2.x only if Hadoop (Hunk) and/or DFS are used. | Workaround | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Enterprise Amazon Machine Image (AMI) | see Splunk Enterprise | Workaround | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Enterprise Cloud | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Enterprise Docker Container | see Splunk Enterprise | Workaround | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Heavyweight Forwarder (HWF) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Infrastructure Monitoring | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Logging Library for Java | <1.11.1 | Fix | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Log Observer | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Mint | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Mobile | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Network Performance Monitoring | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk On-Call/Victor Ops | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Open Telemetry Distributions | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Profiling | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Real User Monitoring | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Secure Gateway (Spacebridge) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Synthetics | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk TV | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk Universal Forwarder (UF) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Splunk User Behavior Analytics (UBA) | all | Not vuln | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Splunk          | Stream Processor Service | Current | Vulnerable | | [source](https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html) |
| Sprecher Automation | SPRECON-E | all | Not vuln | | [source](https://www.sprecher-automation.com/en/it-security/security-alerts) |
| Sprecher Automation | SPRECON-EDIR | all | Not vuln | | [source](https://www.sprecher-automation.com/en/it-security/security-alerts) |
| Sprecher Automation | SPRECON-SG | all | Not vuln | | [source](https://www.sprecher-automation.com/en/it-security/security-alerts) |
| Sprecher Automation | SPRECON-V | all | Not vuln | | [source](https://www.sprecher-automation.com/en/it-security/security-alerts) |
| Stackstate | | 4.3.x, 4.4.x, 4.5.x and SaaS | Workaround | StackState ships with a version of Elasticsearch that contains a vulnerable Log4j library. | [source](https://support.stackstate.com/hc/en-us/articles/4412242847506-Apache-Log4j2-Remote-Code-Execution-RCE-Vulnerability-CVE-2021-44228) |
| Stackstate | Agent | | Workaround | StackState Agent distributed as an RPM, DEB or MSI package contains a vulnerable Log4j library. | [source](https://support.stackstate.com/hc/en-us/articles/4412242847506-Apache-Log4j2-Remote-Code-Execution-RCE-Vulnerability-CVE-2021-44228) |
| Stardog | Stardog | <7.8.1 | Fix | | [source](https://community.stardog.com/t/stardog-7-8-1-available/3411) |
| Stratodesk | NoTouch | 4.5.231 | Fix | | [source](http://cdn.stratodesk.com/repository/notouch-center/10/4.5.231/0/ReleaseNotes-Stratodesk-NoTouch_Center-4.5.231.html) |
| Sumo logic | Sumu logic | 19.361-12 | Fix | | [source](https://help.sumologic.com/Release-Notes/Collector-Release-Notes#december-11-2021-19-361-12) |
| SuperMicro | BIOS | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | BMC | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | SuperCloud Composer (SCC) | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | Supermicro Server Manager (SSM) | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | Supermicro SuperDoctor (SD5) | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | Supermicro Power Manager (SPM) | all | Vulnerable | Upgrade to Log4j 2.15.0. Release pending ASAP | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | SMCIPMITool | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | SCC Analytics | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | SCC PODM | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | vCenter Plug-in | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | Super Diagnostics Offline | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | Supermicro Update Manager (SUM) | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SuperMicro | SUM Service (SUM_SERVER) | all | Not vuln | | [source](https://www.supermicro.com/en/support/security/Apache_log4j2)|
| SUSE | SUSE Linux Enterprise server | all | Not vuln | | [source](https://www.suse.com/c/suse-statement-on-log4j-log4shell-cve-2021-44228-vulnerability/)|
| SUSE | SUSE Manager | all | Not vuln | | [source](https://www.suse.com/c/suse-statement-on-log4j-log4shell-cve-2021-44228-vulnerability/)|
| SUSE | SUSE Openstack Cloud | all | Vuln | will get update | [source](https://www.suse.com/c/suse-statement-on-log4j-log4shell-cve-2021-44228-vulnerability/)|
| SUSE | SUSE Rancher | all | Not vuln | | [source](https://www.suse.com/c/suse-statement-on-log4j-log4shell-cve-2021-44228-vulnerability/)|
| Synacor | Zimbra | 8.8.15 and 9.x | Not vuln | Zimbra stated (in their private support portal) they're not vulnerable. Currently supported Zimbra versions ship 1.2.6 |[source](https://forums.zimbra.org/viewtopic.php?f=15&t=70240&start=10#p303354) |
| Syncro Soft | Oxygen Content Fusion | <= v4.1 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen Content Fusion | 3.0.1 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Web Author | v22.1 - v24.0.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Web Author | 23.1.1.2 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen Feedback | 1.4.4 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Publishing Engine | v22.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML WebHelp | v22.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen PDF Chemistry | v22.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen License Server | v22.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Author | v16.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Developer | v16.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Syncro Soft | Oxygen XML Editor | v16.1 - v24.0 | Fix | Fix available | [source](https://www.oxygenxml.com/security/advisory/CVE-2021-44228.html) |
| Synology | DSM | | Not vuln | The base DSM is not affected. Software installed via the package manager may be vulnerable. | [source](https://www.synology.com/en-global/security/advisory/Synology_SA_21_30) |
| syntevo | DeepGit | >= 4.0 | Fix | 3.0.x and older are vulnerable | [source](https://www.syntevo.com/blog/?p=5240) |
| syntevo | SmartGit | >= 18.1 | Fix | 17.1.x and older are vulnerable | [source](https://www.syntevo.com/blog/?p=5240) |
| syntevo | SmartSVN | >= 9.3 | Fix | 9.2.x and older are vulnerable | [source](https://www.syntevo.com/blog/?p=5240) |
| syntevo | SmartSynchronize | >= 3.5 | Fix | 3.4.x and older are vulnerable | [source](https://www.syntevo.com/blog/?p=5240) |
| SysAid | All products | | Fix | | [source](https://www.sysaid.com/lp/important-update-regarding-apache-log4j) |

### T

| Supplier        | Product         | Version         | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Tableau | Tableau Desktop | 2021.4| Vulnerable | | [source](https://www.tableau.com/support/releases/desktop/2021.4) |
| Tableau | Tableau Server | 2021.2.5| Vulnerable | | [source](https://www.tableau.com/support/releases/server/2021.2.5) |
| Tableau | Tableau Desktop | 2021.4.1 | Fix | | [source](https://kb.tableau.com/articles/issue/Apache-Log4j2-vulnerability-Log4shell), [fix](https://www.tableau.com/products/reader) |
| Tableau | Tableau Server | 2021.4.1 | Fix | | [source](https://kb.tableau.com/articles/issue/Apache-Log4j2-vulnerability-Log4shell), [fix](https://www.tableau.com/products/reader) |
| Tableau | Tableau Prep | 2021.4.2 | Fix | | [source](https://kb.tableau.com/articles/issue/Apache-Log4j2-vulnerability-Log4shell), [fix](https://www.tableau.com/products/reader) |
| Tableau | Tableau Bridge | 20214.21.1214.2057 | Fix | | [source](https://kb.tableau.com/articles/issue/Apache-Log4j2-vulnerability-Log4shell), [fix](https://www.tableau.com/products/reader) |Apache-Log4j2-vulnerability-Log4shell) |
| Tableau | Tableau Reader | unkown | Fix | | [source](https://kb.tableau.com/articles/issue/Apache-Log4j2-vulnerability-Log4shell), [fix](https://www.tableau.com/products/reader) |
| Tailscale | Tailscale | all | Not vuln | | [source](https://github.com/tailscale/tailscale/issues/3550) |
| Talend | Talend Component Kit | | Fix | |[source](https://jira.talendforge.org/browse/TCOMP-2054) |
| Tanium | All products | all | Not vuln | | [source](https://community.tanium.com/s/article/How-Tanium-Can-Help-with-CVE-2021-44228-Log4Shell#_Toc90296319) |
| TARGIT | All products | all | Not vuln | | [source](vendor-statements/Targit.png) |
| Tealium | All products | | Fix | |[source](https://community.tealiumiq.com/t5/Announcements-Blog/Update-on-Log4j-Security-Vulnerability/ba-p/36824) |
| Teamviewer  | All products | | Fix | Server-side hotfix deployed. No user interaction required | [source](https://www.teamviewer.com/en-us/trust-center/security-bulletins/hotfix-log4j2-issue/)|
| Tenable | All products  | | Not vuln  | | [source](https://community.tenable.com/s/article/Log4Shell-FAQs)  |
| Tesorion | Immunity-appliances and software | all | Not vuln | | [source](https://www.tesorion.nl/en/posts/tesorion-products-not-vulnerable-to-log4j/) |
| Tesorion | SOC-appliances and software | all | Fix | Potential Log4j impact mitigated | [source](https://www.tesorion.nl/en/posts/tesorion-products-not-vulnerable-to-log4j/) |
| TheHive | Cortex | all | Not vuln | |[source](https://blog.strangebee.com/apache-log4j-cve-2021-44228/) |
| TheHive | TheHive | all | Not vuln | |[source](https://blog.strangebee.com/apache-log4j-cve-2021-44228/) |
| Tools4ever | HelloID | All | Not Vuln |  | [source](https://forum.helloid.com/forum/main-forum/642-log4j-vulnerability) |
| TOPdesk | TOPdesk SaaS | all | Not Vuln |  | [source](vendor-statements/TOPdesk.png) |
| TOPdesk | TOPdesk On-Premises Virtual Appliance | all | Not Vuln | Although the standard product is not vulnerable, we advise our customers to scan for vulnerabilies if they modified the product, installed add-ons or bespoke work | [source](vendor-statements/TOPdesk.png) |
| TOPdesk | TOPdesk On-Premises Classic | all | Not Vuln | Although the standard product is not vulnerable, we advise our customers to scan for vulnerabilies if they modified the product, installed add-ons or bespoke work | [source](vendor-statements/TOPdesk.png) |
| Topicus Security | Topicus KeyHub | all | Not vuln | | [source](https://blog.topicus-keyhub.com/topicus-keyhub-is-not-vulnerable-to-cve-2021-44228/) |
| Tosibox | All products | | Fix | | [source](https://helpdesk.tosibox.com/support/solutions/articles/2100050946-security-advisory-on-vulnerability-in-apache-log4j-library-cve-2021-44228)|
| TP-Link | Omada SDN Controller (Windows)  | 5.0.29 | Fix | |[source](https://community.tp-link.com/en/business/forum/topic/514452) |
| TP-Link | Omada SDN Controller (Linux) | 4.4.8 | Fix | |[source](https://community.tp-link.com/en/business/forum/topic/514452) |
| Trend Micro | 5G Mobile Network Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | ActiveUpdate  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Apex Central (including as a Service)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Apex One (all versions including SaaS, Mac, and Edge Relay)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud App Security  |  | fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud Edge  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Application Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Common Services  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Conformity  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Container Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - File Storage Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Network Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud One - Workload Secuity  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Cloud Sandbox  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Discovery Analyzer  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Discovery Director  |  | Investigation | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Discovery Email Inspector  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Discovery Inspector  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Discovery Web Inspector  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Deep Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Endpoint Encryption  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Fraudbuster  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Home Network Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Housecall  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Instant Messaging Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Internet Security for Mac (Consumer)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Interscan Messaging Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Interscan Messaging Security Virtual Appliance (IMSVA)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Interscan Web Security Suite  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Interscan Web Security Virtual Appliance (IWSVA)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Mobile Security for Enterprise  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Mobile Security for Android  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Mobile Security for iOS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | MyAccount (Consumer Sign-on)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Network Viruswall  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | OfficeScan  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Password Manager  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Phish Insight  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Policy Manager  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Portable Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | PortalProtect  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Public Wifi Protection / VPN Proxy One Pro  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Rescue Disk  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Rootkit Buster  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Safe Lock (TXOne Edition) |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Safe Lock 2.0  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Sandbox as a Service  |  | Fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | ScanMail for Domino  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | ScanMail for Exchange  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Security for NAS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | ServerProtect (all versions)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Smart Home Network  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Smart Protection Complete  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Smart Protection for Endpoints  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Smart Protection Server (SPS)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint Accessories  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint IPS (N-, NX- and S-series)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint Network Protection (AWS & Azure)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint SMS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint Threat Management Center (TMC)  |  | Fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint ThreatDV  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint TPS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint TX-Series  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint Virtual SMS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TippingPoint Virtual TPS  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TMUSB  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Email Security & HES  |  | Fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Endpoint Sensor  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro ID Security  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Remote Manager  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Security (Consumer)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Virtual Patch for Endpoint  |  | Investigation | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Trend Micro Web Security  |  | Fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TXOne (Edge Series)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | TXOne (Stekkar Series)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Vision One  |  | Fix | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Worry-Free Business Security (on-prem)  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| Trend Micro | Worry-Free Business Security Services  |  | Not vuln | |[source](https://success.trendmicro.com/solution/000289940) |
| tribe29 | Check_MK |  | Not vuln | |[source](https://forum.checkmk.com/t/checkmk-not-affected-by-log4shell/28643) |
| Tripwire | Tripwire® Enterprise  |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire IP360™  |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire LogCenter®  |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Industrial Visibility |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Apps |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Configuration Compliance Manager (CCM) |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire for Servers (TFS)  |  | Not vuln | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Connect (on-prem)   |  | Vulnerable  | |[source](https://www.tripwire.com/log) |
| Tripwire | Tripwire Connect SaaS (cloud)  |  | Vulnerable  | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Configuration Manager SaaS  |  | Vulnerable  | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Anyware SCM  |  | Vulnerable  | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire State Analyzer  |  | Vulnerable  | |[source](https://www.tripwire.com/log4j) |
| Tripwire | Tripwire Industrial Sentinel  |  | Workaround  | |[source](https://www.tripwire.com/log4j) |
| TRUMPF | PFO Smart Teach App |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | QDS 2.0 |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | redpowerDirect |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | Smart Power Tube |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | Smart View Services |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruBend Cell 5000 / 7000 |  | Investigation | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruBend Center |  | Investigation | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruConvert |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruDiode |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruDisk |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruFiber |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruHeat |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruLaser 5000 series |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruLaser all other series |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruLaser Center 7030 |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruMark |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruMatic 1000 fiber |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruMatic 3000 |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruMatic all other series |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruMicro series |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TRUMPF TRUMPF Seamline Remote |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TRUMPF Visionline |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruPlasma |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruPulse |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Boost |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Calculate |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Classic |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Cell |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops FAB |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops I-PFO |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Mark 3D |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Monitor |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops PFO |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Print |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruTops Print Multilaser Assistant |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruPrint Monitoring Analyzer |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruPunch 1000 / 3000 |  | Investigation  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | TruPunch all other series |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |
| TRUMPF | all other TRUMPF machines and systems |  | Not vuln  | |[source](https://www.trumpf.com/filestorage/TRUMPF_Master/Corporate/Security/TRUMPF-Security-Information-TSI-2021-1.pdf) |

### U

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Ubiquiti | UniFi Network Application | 6.5.55 | Fix | Update log4j version to 2.16.0 (CVE-2021-45046) |[source](https://community.ui.com/releases/UniFi-Network-Application-6-5-55/48c64137-4a4a-41f7-b7e4-3bee505ae16e) |
| Unify | First Response OpenScape Policy Store |  | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | Hipath DS-Win |  | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | OpenScape Contact Center |  | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | OpenScape Contact Media Service |  | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | OpenScape Enterprise Express |  | Investigation | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | OpenScape UC | >= 10.2.9.0 | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| Unify | OpenScape Voice | simplex deployments | Vulnerable | |[source](https://networks.unify.com/security/advisories/OBSO-2112-01.pdf) |
| US Signal       | Remote Management and Monitoring platform | | Workaround | |[source](https://ussignal.com/blog/apache-log4j-vulnerability) |
| USoft | USoft | 9.1.1F | Vulnerable | Found by manual scanning | [proof](<https://ibb.co/tqV40qB>) |

### V

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Variphy      | All products  | | Not vuln |  | [source](https://kb.variphy.com/knowledge-base/cve-2021-44228-critical-vulnerability-in-log4j2/)|
| Vectra       | All products  | | Not vuln |  | [source](https://support.vectra.ai/s/article/KB-VS-1568)|
| Veeam        | All products  | | Not vuln |  | [source](https://www.veeam.com/kb4254)|
| Veritas | Aptare IT Analytics | 10.5 and 10.6 | Workaround | Version 10.4 and earlier are not affected. | [source](https://www.veritas.com/support/en_US/article.100052081) |
| Veritas | NetBackup Appliance | 3.1.2 through 4.1.0.1 MR1 | Workaround | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Client | 7.7.3 through 9.1.0.1 | Not vuln | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup CloudPoint | 2.2.2, 8.3 through 9.1.0.1 | Workaround | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Flex Scale | 2.1 | Workaround | Veritas strongly recommends customers using version 1.3 or 1.3.1 to upgrade to NetBackup FlexScale 2.1 in order to be able to perform the mitigation steps. | [source](https://www.veritas.com/content/support/en_US/article.100052101.html) |
| Veritas | NetBackup Media Server | 8.1 through 9.1.0.1 | Not vuln | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Media Server container on Flex Appliance | 8.1 through 9.1.0.1 | Not vuln | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup OpsCenter | 7.7 through 7.7.3 and 8.0 | Not vuln | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup OpsCenter | 8.1.2 through 9.1.0.1 | Workaround | Veritas has published updated versions of Log4j that replace the vulnerable libraries used by NetBackup OpsCenter 8.1.2 through 9.1.0.1. | [source](https://www.veritas.com/support/en_US/article.100052100) |
| Veritas | NetBackup Primary Server | 7.7 through 7.7.3 and 8.0 | Not vuln | | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Primary Server | 8.1.2 through 9.1.0.1 | Workaround | Veritas has published updated versions of Log4j that replace the vulnerable libraries used by NetBackup Primary Server 8.1.2 through 9.1.0.1. | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Primary Server BYO (also known as Master Server) | 8.1 through 8.1.1 | Workaround | Veritas strongly recommends customers upgrade to NetBackup 8.1.2 or the latest release in order to be able to perform the mitigation steps. | [source](https://www.veritas.com/content/support/en_US/article.100052058) |
| Veritas | NetBackup Primary Server container on Flex Appliance | 8.1.2 through 9.1.0.1 | Workaround | | [source](https://www.veritas.com/content/support/en_US/article.100052084) |
| Veritas | NetBackup Resiliency Platform | 3.4 through 4.0 | Workaround | | [source](https://www.veritas.com/content/support/en_US/article.100052109) |
| Veritas | Media Server Deduplication Pool (MSDP) (on NB Appliance) | 3.1.2 and 3.2 | Workaround | | [source](https://www.veritas.com/content/support/en_US/article.100052062) |
| VMware       | API Portal for VMware Tanzu  | 1.x | Fix | Fixed in 1.0.7 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.pivotal.io/products/api-portal#/releases/1012478) |
| VMware       | AppDefense Appliance | 2.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.carbonblack.com/t5/Threat-Research-Docs/Log4Shell-Mitigation-Steps-for-AppDefense/ta-p/109180)|
| VMware       | App Metrics  | 2.1.1 | Fix |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.pivotal.io/products/apm) |
| VMware       | Carbon Black Cloud Workload Appliance | 1.x | Fix | Fixed in 1.1.1 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.carbonblack.com/t5/Threat-Research-Docs/Log4Shell-Mitigation-Steps-for-VMware-Carbon-Black-Cloud/ta-p/109167) |
| VMware       | Carbon Black EDR Server  | 7.x, 6.x | Fix | Fixed in 7.6.0 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.carbonblack.com/t5/Threat-Research-Docs/Log4Shell-Mitigation-Steps-for-VMware-Carbon-Black-EDR/ta-p/109168), [fix](https://community.carbonblack.com/t5/Endpoint-Detection-and-Response/VMware-Carbon-Black-EDR-Announcing-General-Availability-of-EDR/td-p/109189) |
| VMware       | Cloud Director Object Storage Extension | 2.1.x, 2.0.x | Fix | Fixed in 2.1.0.1, 2.0.0.3 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://docs.vmware.com/en/VMware-Cloud-Director-Object-Storage-Extension/2.0.0.3/rn/vmware-cloud-director-object-storage-extension-2003-release-notes/index.html) |
| VMware       | Cloud Foundation  | 4.x, 3.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87095)|
| VMware       | HCX | 4.2.3, 4.1.0.2 | Fix |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html) |
| VMware       | Healthwatch for Tanzu Application Service  | 2.1.7, 1.8.6 | Fix |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.pivotal.io/products/p-healthwatch) |
| VMware       | Horizon | 8.x, 7.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87073) |
| VMware       | Horizon Cloud Connector | 1.x, 2.x | Fix | Fixed in 2.1.1 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://customerconnect.vmware.com/downloads/details?downloadGroup=HCS-CC-210&productId=716&rPId=79131#product_downloads)|
| VMware       | Horizon DaaS | 9.1.x, 9.0.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87101)|
| VMware       | Identity Manager    | 3.3.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87093) |
| VMware       | NSX Data Center for vSphere | 6.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87099)|
| VMware       | NSX-T Data Center  | 3.x, 2.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87086) |
| VMware       | Single Sign-On for VMware Tanzu Application Service  | 1.x | Fix | Fixed in 1.14.5 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.tanzu.vmware.com/products/pivotal_single_sign-on_service#/releases/1012467) |
| VMware       | Site Recovery Manager   | 8.x | Vuln |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87098)|
| VMware       | Skyline Collector virtual appliance  | | Not vuln | | [source](https://kb.vmware.com/s/article/87068) |
| VMware       | Spring Boot  | < 2.5.8, < 2.6.2 | Workaround |   | [source](https://spring.io/blog/2021/12/10/log4j2-vulnerability-and-spring-boot) |
| VMware       | Spring Cloud Gateway for Kubernetes  | 1.x | Vulnerable |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html) |
| VMware       | Spring Cloud Gateway for VMware Tanzu | 1.x | Fix | Fixed in 1.1.3 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.pivotal.io/products/spring-cloud-gateway#/releases/1014134)|
| VMware       | Spring Cloud Services for VMware Tanzu  | 3.x | Fix | Fixed in 3.1.26 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.tanzu.vmware.com/products/p-spring-cloud-services#/releases/1014061)|
| VMware       | Tanzu Application Service for VMs  | 2.x | Fix | Fixed in 2.7.42, 2.10.22, 2.11.10, 2.12.3 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.pivotal.io/s/article/Workaround-instructions-to-address-CVE-2021-44228-in-Tanzu-Application-Service-2-7-through-2-12?language=en_US), [fix](https://network.pivotal.io/products/elastic-runtime) |
| VMware       | Tanzu GemFire   | 1.14.x, 1.13.x, 1.10.x | Fix | Fixed in 1.14.1, 1.13.4 | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [fix](https://network.pivotal.io/products/tanzu-gemfire-for-vms#/releases/)|
| VMware       | Tanzu Greenplum  | 6.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.pivotal.io/s/article/Workaround-to-address-CVE-2021-44228-Apache-Log4j-Remote-Code-Execution-for-All-Greenplum-Versions?language=en_US)|
| VMware       | Tanzu Kubernetes Grid Integrated Edition   | 2.x | Workaround |   | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://community.pivotal.io/s/article/Workaround-instructions-to-address-CVE-2021-44228-in-Tanzu-Application-Service-2-7-through-2-12?language=en_US) |
| VMware       | Tanzu Observability by Wavefront Nozzle | 3.x, 2.x | Fix | Fixed in 3.0.3 | [source](https://kb.vmware.com/s/article/87068), [fix](https://network.pivotal.io/products/wavefront-nozzle) |
| VMware       | Tanzu Operations Manager  | 2.x | Fix | Fixed in 2.10.23 | [source](https://kb.vmware.com/s/article/87068), [workaround](https://community.pivotal.io/s/article/5004y00001mPn2N1639255611105?language=en_US), [fix](https://network.pivotal.io/products/ops-manager/) |
| VMware       | Tanzu SQL with MySQL for VMs  | 2.x, 1.x | Vulnerable |   | [source](https://kb.vmware.com/s/article/87068)|
| VMware       | Telco Cloud Automation | 2.x, 1.x | Vulnerable |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html)|
| VMware       | Unified Access Gateway  | 21.x, 20.x, 3.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87092) |
| VMware       | vCenter Cloud Gateway  | 1.x | Workaround |   | [source](https://kb.vmware.com/s/article/87068), [workaround](https://kb.vmware.com/s/article/87081)|
| VMware       | vCenter Server  | 6.x | Workaround |  Running on: Windows | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87096?lang=en_US)|
| VMware       | vCenter Server  | 7.x, 6.x | Workaround |  Running on: Virtual Appliance | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87081?lang=en_US) |
| VMware       | vCloud Director | all | Not vuln | | [source](https://kb.vmware.com/s/article/87068?lang=en_US) |
| VMware       | vCloud Workstation | all | Not vuln | | [source](https://kb.vmware.com/s/article/87068?lang=en_US) |
| VMware       | vRealize Automation     | 8.x, 7.x | Vulnerable |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html)|
| VMware       | vRealize Lifecycle Manager  | 8.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87097)|
| VMware       | vRealize Log Insight     | 8.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87089) |
| VMware       | vRealize Operations    | 8.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87076) |
| VMware       | vRealize Operations Cloud Proxy     | Any | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87080) |
| VMware       | vRealize Orchestrator   | 8.x, 7.x | Vulnerable |   | [source](https://kb.vmware.com/s/article/87068)|
| VMware       | vSphere ESXi | Unknown | Not Vuln |   | [source](https://kb.vmware.com/s/article/87068) |
| VMware       | Workspace ONE Access   | 21.x, 20.x | Workaround |  | [source](https://www.vmware.com/security/advisories/VMSA-2021-0028.html), [workaround](https://kb.vmware.com/s/article/87090) |
| VMware       | Workspace ONE Access Connector (VMware Identity Manager Connector)  | 19.03.0.1, 20.x, 21.x | Workaround |   | [source](https://kb.vmware.com/s/article/87068), [workaround](https://kb.vmware.com/s/article/87091)|
| Vuze         | Vuze Torrent (desktop/server/mobile) | Revision 44261 | Investigation | Also know as Azureus | [source](http://svn.vuze.com/public/client/trunk/uis/lib/), [vendor](https://www.vuze.com/) |

### W

| Supplier | Product | Version | Status | Notes | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Watcher | [Watcher](https://github.com/thalesgroup-cert/Watcher) | all | Not vuln | | [source](https://twitter.com/felix_hrn/status/1470387338001977344) |
| WatchGuard | AuthPoint | Cloud | Fixed | See link | [source](https://techsearch.watchguard.com/KB?type=Security%20Issues&SFDCID=kA16S000000SNnuSAG&lang=en_US)  |
| WatchGuard | Dimension | - | Not vuln | |[source](https://www.secplicity.org/2021/12/10/critical-rce-vulnerability-in-log4js/) |
| WatchGuard | Firebox | - | Not vuln | |[source](https://www.secplicity.org/2021/12/10/critical-rce-vulnerability-in-log4js/) |
| WatchGuard | Threat Detection and Response | Cloud | Fixed | See link | [source](https://techsearch.watchguard.com/KB?type=Security%20Issues&SFDCID=kA16S000000SNnuSAG&lang=en_US)  |
| WatchGuard | WatchGuard EPDR and Panda AD360 | - | Not vuln | |[source](https://www.secplicity.org/2021/12/10/critical-rce-vulnerability-in-log4js/) |
| WatchGuard | WatchGuard System Manager, Dimension, WatchGuard EPDR and Panda AD360 | - | Not vuln | |[source](https://www.secplicity.org/2021/12/10/critical-rce-vulnerability-in-log4js/) |
| WatchGuard | Wi-Fi Cloud | Cloud | Fixed | See link | [source](https://techsearch.watchguard.com/KB?type=Security%20Issues&SFDCID=kA16S000000SNnuSAG&lang=en_US)  |
| Weblib | Ucopia | | Not vuln | | [source](vendor-statements/Ucopia.png)  |
| Wibu Systems | CodeMeter Keyring for TIA Portal  | > 1.30 | Fix | Only the Password Manager is affected | [source](https://cdn.wibu.com/fileadmin/wibu_downloads/security_advisories/Advisory_WIBU-211213-01.pdf)|
| Wibu Systems | CodeMeter Cloud Lite  | > 2.2 | Fix |  | [source](https://cdn.wibu.com/fileadmin/wibu_downloads/security_advisories/Advisory_WIBU-211213-01.pdf)|
| WildFly | WildFly | < 22 | Not vuln | "No log4j artifact shipped" | [source](https://www.wildfly.org/news/2021/12/13/Log4j-CVEs/)|
| WildFly | WildFly | >= 22; <= 26.0.0.Beta1 | Not vuln | "ships log4j-api but not vulnerable code from log4j-core; version of log4j-api might seem to be vulnerable but is not" | [source](https://www.wildfly.org/news/2021/12/13/Log4j-CVEs/)|
| WildFly | WildFly | > 26.0.0.Final | Not vuln | "ships log4j-api where version matches patched version" | [source](https://www.wildfly.org/news/2021/12/13/Log4j-CVEs/)|
| Wind River | Wind River Linux | <= 8 | Not vuln | "contain package log4j, but their version is 1.2.x, too old to be affected" | [source](https://support2.windriver.com/index.php?page=security-notices&on=view&id=7191)|
| Wind River | Wind River Linux | > 8 | Not vuln | no support for log4j | [source](https://support2.windriver.com/index.php?page=security-notices&on=view&id=7191)|
| Wireshark | Wireshark | | Not vuln | | [source](https://www.wireshark.org/news/20211215.html)|
| WitFoo | WitFoo Precinct | 6.x | Fix | WitFoo Streamer & Apache Kafka Docker containers are/were vulnerable | [source](https://www.witfoo.com/blog/emergency-update-for-cve-2021-44228-log4j/)|
| WordPress | All | | Not vuln | | [source](https://wordpress.org/support/topic/is-the-log4j-vulnerability-an-issue/)|
| Wowza | Wowza Streaming Engine | 4.7.8, 4.8.x | Workaround | |[source](https://www.wowza.com/docs/known-issues-with-wowza-streaming-engine#log4j2-cve) |
| WSO2 | WSO2 API Manager | >= 3.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 API Manager Analytics | >= 2.6.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Enterprise Integrator | >= 6.1.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Enterprise Integrator Analytics | >= 6.6.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Identity Server | >= 5.9.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Identity Server Analytics | >= 5.7.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Identity Server as Key Manager | >= 5.9.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Micro Gateway | >= 3.2.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Micro Integrator | >= 1.1.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Micro Integrator Dashboard | >= 4.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Micro Integrator Monitoring Dashboard | >= 1.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Stream Processor | >= 4.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Stream Integrator | >= 1.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Stream Integrator Tooling | >= 1.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Open Banking AM | >= 2.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Open Banking BI | >= 1.3.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |
| WSO2 | WSO2 Open Banking KM | >= 2.0.0 | Workaround | | [source](https://docs.wso2.com/pages/viewpage.action?pageId=180948677) |

### X

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Xerox | All other products | | Investigation | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | AltaLink B8000 Series | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | AltaLink B8100 Series | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | AltaLink C8000 Series | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | AltaLink C8100 Series | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | B1022/1025 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Baltoro HF Inkjet Press | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | DocuShare | | Not vuln | DocuShare using Solr search is vulnerable, see below. | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/DocuShare-Security-Bulletin-XRX21-022-for-CVE-2021-44228.pdf) |
| Xerox | DocuShare Flex | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/DocuShare-Security-Bulletin-XRX21-022-for-CVE-2021-44228.pdf) |
| Xerox | DocuShare Go | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/DocuShare-Security-Bulletin-XRX21-022-for-CVE-2021-44228.pdf) |
| Xerox | DocuShare using Solr search | 7.5 hotfix 11 | Fixed | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/DocuShare-Security-Bulletin-XRX21-022-for-CVE-2021-44228.pdf) |
| Xerox | EC8036/EC8056 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | iGen 5 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Instant Print Kiosk | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Nuvera EA Perfecting Production Systems | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Nuvera EA Production Systems | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Phaser 3330 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Phaser 3435 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Versant 180/280 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Versant 3100/4100 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | WorkCentre 3335/45 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | WorkCentre 5865i/5875i/58901 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | WorkCentre 7970i | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | WorkCentre EC7836/EC7856 | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |
| Xerox | Workplace Kiosk | | Not vuln | | [source](https://security.business.xerox.com/wp-content/uploads/2021/12/Xerox-Special-Bulletin-Regarding-CVE-2021-44228.pdf) |

### Y

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links      |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Yahoo           | Vespa           |                 | Not vuln        | Your Vespa application may still be affected if log4j is included in your application package |[source](https://blog.vespa.ai/log4j-vulnerability/) |
| Y Soft          | SAFEQ 6 | <= 6.0.63 | Workaround |  |[source](https://www.ysoft.com/getattachment/Products/Security/Standards-Compliance/text/Information-Security-Policy-Statement/YSOFT-SAFEQ-LOG4J-VULNERABILITY-PRODUCT-UPDATE-WORKAROUND-1.pdf) |
| Yellowfin       | Yellowfin       | 8.0.10.3, 9.7.0.2 | Fix | v7 and v6 releases are not affected unless you have manually upgraded to Log4j2 | [source](https://community.yellowfinbi.com/announcement/notice-critical-vulnerability-in-log4j2) |
| Yenlo | Connext | 2.x| Not vuln |Connext Platform (Managed WSO2 Cloud) and all underlying middleware components are not vulnerable |[source](https://www.yenlo.com/news/vulnerability-code-log4shell-log4j2)|

### Z

| Supplier        | Product         | Version (see Status) | Status          | Notes           | Links      |
|:----------------|:----------------|:--------------------:|:---------------:|:----------------|-----------:|
| Zabbix          | Zabbix          |                 | Not vuln        | Zabbix is aware of this vulnerability, has completed verification, and can conclude that the only product where we use Java is Zabbix Java Gateway, which does not utilize the log4j library, thereby is not impacted by this vulnerability. |[source](https://blog.zabbix.com/zabbix-not-affected-by-the-log4j-exploit/17873/) |
| Zammad          | Zammad          |                 | Workaround      | Most of Zammad instances make use of Elasticsearch which might be vulnerable. |[source](https://community.zammad.org/t/cve-2021-44228-elasticsearch-users-be-aware/8256) |
| Zendesk         | Zendesk         |                 | Workaround      | SaaS - No user action |[source](https://support.zendesk.com/hc/en-us/articles/4413583476122-2021-12-13-Security-Advisory-Apache-Log4j-CVE-2021-44228-) |
| Zerto           | Virtual Replication Appliance   | | Not vuln        | |[source](https://help.zerto.com/kb/000004822) |
| Zerto           | Zerto Cloud Appliance |           | Not vuln        | |[source](https://help.zerto.com/kb/000004822) |
| Zerto           | Zerto Cloud Manager |             | Not vuln        | |[source](https://help.zerto.com/kb/000004822) |
| Zerto           | Zerto Virtual Manager |           | Not vuln        | |[source](https://help.zerto.com/kb/000004822) |
| Zesty           | Zesty.io        |                 | Not vuln        | |[source](https://www.zesty.io/mindshare/company-announcements/log4j-exploit/) |
| Zoho | Online | | Investigation | | [source](https://help.zoho.com/portal/en/community/topic/update-on-the-recent-apache-log4j-vulnerability )|
| Zoom | All products | | Not vuln | | [source](https://explore.zoom.us/en/trust/security/security-bulletin/security-bulletin-log4j) |
| Zscaler         | All products    |                 | Fix        | |[source](https://trust.zscaler.com/posts/9581) |
| Zyxel           | All other products |  | Not vuln  | |[source](https://community.zyxel.com/en/discussion/12229/zyxel-security-advisory-for-apache-log4j-rce-vulnerability) |
| Zyxel           | NetAtlas Element Management System (EMS)  |  | Vulnerable       | Hotfix availability Dec. 20, 2021, Patch availability in end of Feb. 2022 |[source](https://community.zyxel.com/en/discussion/12229/zyxel-security-advisory-for-apache-log4j-rce-vulnerability) |
