

# Document Revision History

This chapter lists the changes made to this document from the previous release.

<br></br>
![image](images/NoteSmall.jpg)***NOTE:*** *Please refer to the <a href="http://docs.hazelcast.org/docs/rn/" target="_blank">Release Notes</a> for the new features, enhancements and fixes performed for each Hazelcast release.*

<br></br>

|Chapter|Section|Description|
|:-------|:-------|:-----------|
|[Preface](#preface)|[Phone Home](#phone-home)|Added information related to the new environment variable `HZ_PHONE_HOME_ENABLED` for disabling phone homes. 
|[Consistency and Replication Model](#consistency-and-replication-model)| |Added as a new chapter to explain the full picture of Hazelcast's consistency model.|
|[Understanding Configuration](#understanding-configuration)||Added [Configuration Pattern Patcher](#configuration-pattern-matcher) and [Dynamically Adding Configuration on a Cluster](#dynamically-adding-configuration-on-a-cluster) as a new sections.|
||| Added [Variable Replacers](#variable-replacers) as a new section.
|[Setting Up Clusters](#setting-up-clusters)|[User Code Deployment](#user-code-deployment)|Added "Example for  Filtering Members" as a new section to explain how to use the `provider-filter` element.|
||[Client User Code Deployment](#client-user-code-deployment-beta)|Added as a new section.
||[Failure Detector Configuration](#failure-detector-configuration)| Added as a new section to explain Hazelcast's Deadline and Phi Accrual failure detectors.
||[Ping Failure Detector](#ping-failure-detector)| Added as a new section.
|[Distributed Computing](#distributed-computing)|[Entry Processor](#entry-processor)|Added "Entry Processor Optimizations" as a new section explaining Offloadable and Readonly entry processors.|
|[Distributed Data Structures](#distributed-data-structures)|[Lock](#lock)|Added "Lock vs. IMap.lock" as a new section.|
||[Event Journal](#event-journal)| Added as a new section to explain the event journal distributed data structure that stores the history of mutation actions on the data structures such as map or cache.
|[Hazelcast JCache](#hazelcast-jcache)|[Scoping to Join Clusters](#scoping-to-join-clusters)|Enhanced the content to explain and give examples about the Hazelcast instance creations during cache manager starts.
| ||Added [Supported JCache Versions](#supported-jcache-versions) as a new section along with the updates regarding with JCache 1.1.0 .
|[Integrated Clustering](#integrated-clustering)|[Integrating with Spring](#integrating-with-spring)| Added "Defining Timeouts for Cache Read Operation" as a new section.
|[Hazelcast Java Client](#hazelcast-java-client)|[Enabling Client TLS/SSL](#enabling-client-tlsssl)|Added information related to mutual authentication.
||[Configuring Client Connection Strategy](#configuring-client-connection-strategy)| Added as a new section.
||[Async Start and Reconnect Modes](#async-start-and-reconnect-modes)|Added as a new section.
||[Setting Outbound Ports](#setting-outbound-ports)| Added as a new section.
||[Client Failure Detectors](#client-failure-detectors)| Added as a new section.
|[Management](#management)|[Using Management Center with TLS/SSL Only](#;)|Added as a new section.
||[Promoting Lite Members to Data Member](#promoting-lite-members-to-data-member)| Added as a new section.
||[Managing Cluster and Member States](#managing-cluster-and-member-states)| Added the explanation for the new cluster state `NO_MIGRATION`.
|||Added [LDAP](#ldap-authentication), [Active Directory](#active-directory-authentication) and [JAAS Authentication](#jaas-authentication) as new sections.
|||Added [Password Encryption](#password-encryption) as a new section to explain how to encrypt LDAP passwords.
||[Defining Member Attributes](#defining-member-attributes)|Added information related to member filtering for distributed class loading (user code deployment).
||[Management Center](#management-center)|Updated by adding "Metrics-Only" privilege definition and "Enabling TLS/SSL when starting with WAR file" section.
||[Diagnostics](#diagnostics)| Added explanations for new diagnostics plugins: OperationHeartbeats, MemberHeartbeats and WAN Diagnostics.
|[Security](#security)|[SSL](#ssl)|Added "Authenticating Mutually" as a new section.|
||[Native Client Security](#native-client-security)| Added description for the Cache Permissions.
||[Validating Secrets Using Strength Policy](#validating-secrets-using-strength-policy)| Added as a new section.
|[Performance](#performance)|[Near Cache](#near-cache)|Added "Locally Initiated Changes" as a new section.|
||[PartitioningStrategy](#partitioningstrategy)| Added as a new section.
|[WAN](#wan)|| Added the new section [Defining WAN replication using Discovery SPI](#defining-wan-replication-using-discovery-spi) to explain how to use WAN with endpoints on various cloud infrastructures (such as Amazon EC2) where the IP addresses are not known in advance. <br> [WAN Replication Failure Detection and Recovery](#wan-replication-failure-detection-and-recovery) added as a new section.
|||Added [WAN Publisher States](#wan-publisher-states) as a new section.
|||Updated [Synchronizing WAN Target Cluster](#synchronizing-wan-target-cluster) section with the timestamp description.
|[Network Partitioning](#network-partitioning)||Improved the whole content on how Hazelcast handles split-brain syndrome.
|[System Properties](#system-properties)||Added definitions for the new properties: <br> - hazelcast.partition.migration.fragments.enabled <br> - hazelcast.legacy.memberlist.format.enabled<br> - hazelcast.mastership.claim.timeout.seconds<br> - hazelcast.diagnostics.operation-heartbeat.seconds <br> - hazelcast.diagnostics.operation-heartbeat.max-deviation-percentage <br> - hazelcast.diagnostics.member-heartbeat.seconds <br> - hazelcast.diagnostics.member-heartbeat.max-deviation-percentage <br> - hazelcast.operation.fail.on.indeterminate.state|



<br> </br>
