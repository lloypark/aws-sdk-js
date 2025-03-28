# Changelog for AWS SDK for JavaScript
<!--LATEST=2.1040.0-->
<!--ENTRYINSERT-->

## 2.1040.0
* feature: AccessAnalyzer: AWS IAM Access Analyzer now supports policy validation for resource policies attached to S3 buckets and access points. You can run additional policy checks by specifying the S3 resource type you want to attach to your resource policy.
* feature: BackupGateway: Initial release of AWS Backup gateway which enables you to centralize and automate protection of on-premises VMware and VMware Cloud on AWS workloads using AWS Backup.
* feature: EC2: This release adds support for Is4gen and Im4gn instances. This release also adds a new subnet attribute, enableLniAtDeviceIndex, to support local network interfaces, which are logical networking components that connect an EC2 instance to your on-premises network.
* feature: FSx: This release adds support for the FSx for OpenZFS file system type, FSx for Lustre file systems with the Persistent_2 deployment type, and FSx for Lustre file systems with Amazon S3 data repository associations and automatic export policies.
* feature: Glue: Support for DataLake transactions
* feature: IoTTwinMaker: AWS IoT TwinMaker makes it faster and easier to create, visualize and monitor digital twins of real-world systems like buildings, factories and industrial equipment to optimize operations. Learn more: https://docs.aws.amazon.com/iot-twinmaker/latest/apireference/Welcome.html (New Service) (Preview)
* feature: Iot: Added the ability to enable/disable IoT Fleet Indexing for Device Defender and Named Shadow information, and search them through IoT Fleet Indexing APIs.
* feature: Kafka: This release adds three new V2 APIs. CreateClusterV2 for creating both provisioned and serverless clusters. DescribeClusterV2 for getting information about provisioned and serverless clusters and ListClustersV2 for listing all clusters (both provisioned and serverless) in your account.
* feature: Kinesis: Updates API to latest version.
* feature: LakeFormation: This release adds support for row and cell-based access control in Lake Formation. It also adds support for Lake Formation Governed Tables, which support ACID transactions and automatic storage optimizations.
* feature: Outposts: This release adds the SupportedHardwareType parameter to CreateOutpost.
* feature: RedshiftData: Data API now supports serverless queries.
* feature: S3: Introduce Amazon S3 Glacier Instant Retrieval storage class and a new setting in S3 Object Ownership to disable ACLs for bucket and the objects in it.
* feature: Snowball: Tapeball is to integrate tape gateway onto snowball, it enables customer to transfer local data on the tape to snowball,and then ingest the data into tape gateway on the cloud.
* feature: StorageGateway: Added gateway type VTL_SNOW. Added new SNOWBALL HostEnvironment for gateways running on a Snowball device. Added new field HostEnvironmentId to serve as an identifier for the HostEnvironment on which the gateway is running.
* feature: WorkSpacesWeb: This is the initial SDK release for Amazon WorkSpaces Web. Amazon WorkSpaces Web is a low-cost, fully managed WorkSpace built to deliver secure web-based workloads and software-as-a-service (SaaS) application access to users within existing web browsers.

## 2.1039.0
* feature: ComputeOptimizer: Adds support for the enhanced infrastructure metrics paid feature. Also adds support for two new sets of resource efficiency metrics, including savings opportunity metrics and performance improvement opportunity metrics.
* feature: DataExchange: This release enables providers and subscribers to use Data Set, Job, and Asset operations to work with API assets from Amazon API Gateway. In addition, this release enables subscribers to use the SendApiAsset operation to invoke a provider's Amazon API Gateway API that they are entitled to.
* feature: EC2: This release adds support for G5g and M6a instances. This release also adds support for Amazon EBS Snapshots Archive, a feature that enables you to archive your EBS snapshots; and Recycle Bin, a feature that enables you to protect your EBS snapshots against accidental deletion.
* feature: ECR: This release adds supports for pull through cache rules and enhanced scanning.
* feature: Evidently: Introducing Amazon CloudWatch Evidently. This is the first public release of Amazon CloudWatch Evidently.
* feature: Inspector2: This release adds support for the new Amazon Inspector API. The new Amazon Inspector can automatically discover and scan Amazon EC2 instances and Amazon ECR container images for software vulnerabilities and unintended network exposure, and report centralized findings across multiple AWS accounts.
* feature: IoTSiteWise: AWS IoT SiteWise now supports retention configuration for the hot tier storage.
* feature: RUM: This is the first public release of CloudWatch RUM
* feature: Rbin: This release adds support for Recycle Bin.
* feature: S3: Amazon S3 Event Notifications adds Amazon EventBridge as a destination and supports additional event types. The PutBucketNotificationConfiguration API can now skip validation of Amazon SQS, Amazon SNS and AWS Lambda destinations.
* feature: SSM: Added two new attributes to DescribeInstanceInformation called SourceId and SourceType along with new string filters SourceIds and SourceTypes to filter instance records.
* feature: WellArchitected: This update provides support for Well-Architected API users to use custom lens features.

## 2.1038.0
* feature: MigrationHubRefactorSpaces: This is the initial SDK release for AWS Migration Hub Refactor Spaces
* feature: Personalize: This release adds API support for Recommenders and BatchSegmentJobs.
* feature: PersonalizeRuntime: This release adds inference support for Recommenders.
* feature: Textract: This release adds support for synchronously analyzing identity documents through a new API: AnalyzeID

## 2.1037.0
* feature: EC2: Documentation updates for EC2.
* feature: Mgn: Application Migration Service now supports an additional replication method that does not require agent installation on each source server. This option is available for source servers running on VMware vCenter versions 6.7 and 7.0.
* feature: Outposts: This release adds new APIs for working with Outpost sites and orders.
* feature: Pinpoint: Added a One-Time Password (OTP) management feature. You can use the Amazon Pinpoint API to generate OTP codes and send them to your users as SMS messages. Your apps can then call the API to verify the OTP codes that your users input

## 2.1036.0
* feature: AutoScaling: Customers can now configure predictive scaling policies to proactively scale EC2 Auto Scaling groups based on any CloudWatch metrics that more accurately represent the load on the group than the four predefined metrics. They can also use math expressions to further customize the metrics.
* feature: CustomerProfiles: This release introduces a new auto-merging feature for profile matching. The auto-merging configurations can be set via CreateDomain API or UpdateDomain API. You can use GetIdentityResolutionJob API and ListIdentityResolutionJobs API to fetch job status.
* feature: Imagebuilder: This release adds support for sharing AMIs with Organizations within an EC2 Image Builder Distribution Configuration.
* feature: IoTSiteWise: AWS IoT SiteWise now accepts data streams that aren't associated with any asset properties. You can organize data by updating data stream associations.
* feature: Lambda: Remove Lambda function url apis
* feature: Proton: This release adds APIs for getting the outputs and provisioned stacks for Environments, Pipelines, and ServiceInstances.  You can now add tags to EnvironmentAccountConnections.  It also adds APIs for working with PR-based provisioning.  Also, it adds APIs for syncing templates with a git repository.
* feature: TimestreamQuery: Releasing Amazon Timestream Scheduled Queries. It makes real-time analytics more performant and cost-effective for customers by calculating and storing frequently accessed aggregates, and other computations, typically used in operational dashboards, business reports, and other analytics applications
* feature: TimestreamWrite: This release adds support for multi-measure records and magnetic store writes. Multi-measure records allow customers to store multiple measures in a single table row. Magnetic store writes enable customers to write late arrival data (data with timestamp in the past) directly into the magnetic store.
* feature: Translate: This release enables customers to use translation settings to mask profane words and phrases in their translation output.

## 2.1035.0
* feature: Backup: This release adds new opt-in settings for advanced features for DynamoDB backups
* feature: DynamoDB: DynamoDB PartiQL now supports ReturnConsumedCapacity, which returns capacity units consumed by PartiQL APIs if the request specified returnConsumedCapacity parameter. PartiQL APIs include ExecuteStatement, BatchExecuteStatement, and ExecuteTransaction.
* feature: EC2: This release adds a new parameter ipv6Native to the allow creation of IPv6-only subnets using the CreateSubnet operation, and the operation ModifySubnetAttribute includes new parameters to modify subnet attributes to use resource-based naming and enable DNS resolutions for Private DNS name.
* feature: ElastiCache: Adding support for r6gd instances for Redis with data tiering. In a cluster with data tiering enabled, when available memory capacity is exhausted, the least recently used data is automatically tiered to solid state drives for cost-effective capacity scaling with minimal performance impact.
* feature: IoTWireless: Two new APIs, GetNetworkAnalyzerConfiguration and UpdateNetworkAnalyzerConfiguration, are added for the newly released Network Analyzer feature which enables customers to view real-time frame information and logs from LoRaWAN devices and gateways.
* feature: Iot: This release introduces a new feature, Managed Job Template, for AWS IoT Jobs Service. Customers can now use service provided managed job templates to easily create jobs for supported standard job actions.
* feature: IotDeviceAdvisor: This release introduces a new feature for Device Advisor: ability to execute multiple test suites in parallel for given customer account. You can use GetEndpoint API to get the device-level test endpoint and call StartSuiteRun with "parallelRun=true" to run suites in parallel.
* feature: Lambda: Release Lambda event source filtering for SQS, Kinesis Streams, and DynamoDB Streams.
* feature: OpenSearch: This release adds an optional parameter dry-run for the UpdateDomainConfig API to perform basic validation checks, and detect the deployment type that will be required for the configuration change, without actually applying the change.
* feature: RDS: Adds support for Multi-AZ DB clusters for RDS for MySQL and RDS for PostgreSQL.
* feature: Redshift: This release adds support for reserved node exchange with restore/resize
* feature: S3: Introduce two new Filters to S3 Lifecycle configurations - ObjectSizeGreaterThan and ObjectSizeLessThan. Introduce a new way to trigger actions on noncurrent versions by providing the number of newer noncurrent versions along with noncurrent days.
* feature: SQS: Amazon SQS adds a new queue attribute, SqsManagedSseEnabled, which enables server-side queue encryption using SQS owned encryption keys.

## 2.1034.0
* feature: Braket: This release adds support for Amazon Braket Hybrid Jobs.
* feature: ChimeSDKMeetings: Added new APIs for enabling Echo Reduction with Voice Focus.
* feature: CloudFormation: This release include SDK changes for the feature launch of Stack Import to Service Managed StackSet.
* feature: Connect: This release adds support for UpdateContactFlowMetadata, DeleteContactFlow and module APIs. For details, see the Release Notes in the Amazon Connect Administrator Guide.
* feature: DMS: Added new S3 endpoint settings to allow to convert the current UTC time into a specified time zone when a date partition folder is created. Using with 'DatePartitionedEnabled'.
* feature: EKS: Adding missing exceptions to RegisterCluster operation
* feature: ES: This release adds an optional parameter dry-run for the UpdateElasticsearchDomainConfig API to perform basic validation checks, and detect the deployment type that will be required for the configuration change, without actually applying the change.
* feature: Finspacedata: Add new APIs for managing Datasets, Changesets, and Dataviews.
* feature: QuickSight: Add support for Exasol data source, 1 click enterprise embedding and email customization.
* feature: RDS: Adds local backup support to Amazon RDS on AWS Outposts.
* feature: S3Control: Added Amazon CloudWatch publishing option for S3 Storage Lens metrics.
* feature: SSM: Adds new parameter to CreateActivation API . This parameter is for "internal use only".

## 2.1033.0
* feature: AppStream: Includes APIs for managing resources for Elastic fleets: applications, app blocks, and application-fleet associations.
* feature: ApplicationInsights: Application Insights now supports monitoring for HANA
* feature: CloudFormation: The StackSets ManagedExecution feature will allow concurrency for non-conflicting StackSet operations and queuing the StackSet operations that conflict at a given time for later execution.
* feature: Lambda: Add support for Lambda Function URLs. Customers can use Function URLs to create built-in HTTPS endpoints on their functions.
* feature: LexRuntimeV2: Updates API to latest version.
* feature: MediaLive: This release adds support for specifying a SCTE-35 PID on input. MediaLive now supports SCTE-35 PID selection on inputs containing one or more active SCTE-35 PIDs.
* feature: Redshift: Added support of default IAM role for CreateCluster, RestoreFromClusterSnapshot and ModifyClusterIamRoles APIs

## 2.1032.0
* bugfix: EC2: Add customization for EC2 legacy dualstack endpoints
* bugfix: S3/S3Control: Check for config.useDualstackEndpoint in customizations
* feature: AppConfig: Add Type to support feature flag configuration profiles
* feature: AuditManager: This release introduces a new feature for Audit Manager: Dashboard views. You can now view insights data for your active assessments, and quickly identify non-compliant evidence that needs to be remediated.
* feature: Chime: Adds new Transcribe API parameters to StartMeetingTranscription, including support for content identification and redaction (PII & PHI), partial results stabilization, and custom language models.
* feature: ChimeSDKMeetings: Adds new Transcribe API parameters to StartMeetingTranscription, including support for content identification and redaction (PII & PHI), partial results stabilization, and custom language models.
* feature: CloudWatch: CloudWatch Anomaly Detection now supports anomaly detectors that use metric math as input.
* feature: DataBrew: This SDK release adds the following new features: 1) PII detection in profile jobs, 2) Data quality rules, enabling validation of data quality in profile jobs, 3) SQL query-based datasets for Amazon Redshift and Snowflake data sources, and 4) Connecting DataBrew datasets with Amazon AppFlow flows.
* feature: ForecastService: NEW CreateExplanability API that helps you understand how attributes such as price, promotion, etc. contributes to your forecasted values; NEW CreateAutoPredictor API that trains up to 40% more accurate forecasting model, saves up to 50% of retraining time, and provides model level explainability.
* feature: IVS: Add APIs for retrieving stream session information and support for filtering live streams by health.  For more information, see https://docs.aws.amazon.com/ivs/latest/userguide/stream-health.html
* feature: Kafka: Amazon MSK has added a new API that allows you to update the connectivity settings for an existing cluster to enable public accessibility.
* feature: Lambda: Added support for CLIENT_CERTIFICATE_TLS_AUTH and SERVER_ROOT_CA_CERTIFICATE as SourceAccessType for MSK and Kafka event source mappings.
* feature: LexModelsV2: Added support for Polly Neural TTS (NTTS) voices. Customers can choose between 'standard' and 'neural' for Polly Engine configuration per locale when creating or updating an Amazon Lex bot.
* feature: RedshiftData: Rolling back Data API serverless features until dependencies are live.

## 2.1031.0
* bugfix: S3: Support FIPS for S3 Accesspoint & Object Lambda
* feature: AmplifyBackend: New APIs to support the Amplify Storage category. Add and manage file storage in your Amplify app backend.
* feature: AppConfigData: AWS AppConfig Data is a new service that allows you to retrieve configuration deployed by AWS AppConfig. See the AppConfig user guide for more details on getting started. https://docs.aws.amazon.com/appconfig/latest/userguide/what-is-appconfig.html
* feature: DevOpsGuru: Add paginator for DescribeResourceCollectionHealth
* feature: Drs: Introducing AWS Elastic Disaster Recovery (AWS DRS), a new service that minimizes downtime and data loss with fast, reliable recovery of on-premises and cloud-based applications using affordable storage, minimal compute, and point-in-time recovery.
* feature: RedshiftData: Data API now supports serverless requests.
* feature: SNS: Amazon SNS introduces the PublishBatch API, which enables customers to publish up to 10 messages per API request. The new API is valid for Standard and FIFO topics.

## 2.1030.0
* feature: CloudTrail: CloudTrail Insights now supports ApiErrorRateInsight, which enables customers to identify unusual activity in their AWS account based on API error codes and their rate.
* feature: Location: This release adds the support for Relevance, Distance, Time Zone, Language and Interpolated Address for Geocoding and Reverse Geocoding.
* feature: S3Control: Support FIPS for S3 Outposts
* feature: s3util: Add allowFipsEndpoint option in validateArnRegion

## 2.1029.0
* feature: AppStream: This release includes support for images of AmazonLinux2 platform type.
* feature: DMS: Add Settings in JSON format for the source GCP MySQL endpoint
* feature: EC2: Adds a new VPC Subnet attribute "EnableDns64." When enabled on IPv6 Subnets, the Amazon-Provided DNS Resolver returns synthetic IPv6 addresses for IPv4-only destinations.
* feature: EKS: Adding Tags support to Cluster Registrations.
* feature: MigrationHubStrategy: AWS SDK for Migration Hub Strategy Recommendations. It includes APIs to start the portfolio assessment, import portfolio data for assessment, and to retrieve recommendations. For more information, see the AWS Migration Hub documentation at https://docs.aws.amazon.com/migrationhub/index.html
* feature: SSM: Adds support for Session Reason and Max Session Duration for Systems Manager Session Manager.
* feature: Transfer: AWS Transfer Family now supports integrating a custom identity provider using AWS Lambda
* feature: WAFV2: Your options for logging web ACL traffic now include Amazon CloudWatch Logs log groups and Amazon S3 buckets.

## 2.1028.0
* feature: Connect: This release adds APIs for creating and managing scheduled tasks. Additionally, adds APIs to describe and update a contact and list associated references.
* feature: DevOpsGuru: Add support for cross account APIs.
* feature: EC2: C6i instances are powered by a third-generation Intel Xeon Scalable processor (Ice Lake) delivering all-core turbo frequency of 3.5 GHz. G5 instances feature up to 8 NVIDIA A10G Tensor Core GPUs and second generation AMD EPYC processors.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added automatic modes for GOP configuration and added the ability to ingest screen recordings generated by Safari on MacOS 12 Monterey.
* feature: SSM: This Patch Manager release supports creating Patch Baselines for RaspberryPi OS (formerly Raspbian)
* feature: endpoint: Add useDualstackEndpoint configuration

## 2.1027.0
* feature: EC2: This release provides an additional route target for the VPC route table.
* feature: Translate: This release enables customers to import Multi-Directional Custom Terminology and use Multi-Directional Custom Terminology in both real-time translation and asynchronous batch translation.
* feature: endpoint: Add useFipsEndpoint configuration

## 2.1026.0
* feature: Backup: AWS Backup SDK provides new options when scheduling backups: select supported services and resources that are assigned to a particular tag, linked to a combination of tags, or can be identified by a partial tag value, and exclude resources from their assignments.
* feature: ECS: This release adds support for container instance health.
* feature: Resiliencehub: Initial release of AWS Resilience Hub, a managed service that enables you to define, validate, and track the resilience of your applications on AWS
* feature: endpoint: Move FIPS rules to a separate section in region_config

## 2.1025.0
* feature: Batch: Adds support for scheduling policy APIs.
* feature: GreengrassV2: This release adds support for Greengrass core devices running Windows. You can now specify name of a Windows user to run a component.

## 2.1024.0
* feature: ChimeSDKMeetings: Updated format validation for ids and regions.
* feature: EC2: This release adds internal validation on the GatewayAssociationState field
* feature: SageMaker: SageMaker CreateEndpoint and UpdateEndpoint APIs now support additional deployment configuration to manage traffic shifting options and automatic rollback monitoring. DescribeEndpoint now shows new in-progress deployment details with stage status.
* feature: WAFV2: You can now configure rules to run a CAPTCHA check against web requests and, as needed, send a CAPTCHA challenge to the client.

## 2.1023.0
* feature: EC2: DescribeInstances now returns customer-owned IP addresses for instances running on an AWS Outpost.
* feature: Translate: This release enable customers to use their own KMS keys to encrypt output files when they submit a batch transform job.

## 2.1022.0
* feature: ChimeSDKMeetings: The Amazon Chime SDK Meetings APIs allow software developers to create meetings and attendees for interactive audio, video, screen and content sharing in custom meeting applications which use the Amazon Chime SDK.
* feature: Connect: This release adds CRUD operation support for Security profile resource in Amazon Connect
* feature: EC2: This release adds a new instance replacement strategy for EC2 Fleet, Spot Fleet. Now you can select an action to perform when your instance gets a rebalance notification. EC2 Fleet, Spot Fleet can launch a replacement then terminate the instance that received notification after a termination delay
* feature: IoTWireless: Adding APIs for the FUOTA (firmware update over the air) and multicast for LoRaWAN devices and APIs to support event notification opt-in feature for Sidewalk related events. A few existing APIs need to be modified for this new feature.
* feature: SageMaker: ListDevices and DescribeDevice now show Edge Manager agent version.

## 2.1021.0
* feature: ConnectParticipant: This release adds a new boolean attribute - Connect Participant - to the CreateParticipantConnection API, which can be used to mark the participant as connected.
* feature: DataSync: AWS DataSync now supports Hadoop Distributed File System (HDFS) Locations
* feature: Finspace: Adds superuser and data-bundle parameters to CreateEnvironment API
* feature: Macie2: This release adds support for specifying the severity of findings that a custom data identifier produces, based on the number of occurrences of text that matches the detection criteria.

## 2.1020.0
* feature: CloudFront: CloudFront now supports response headers policies to add HTTP headers to the responses that CloudFront sends to viewers. You can use these policies to add CORS headers, control browser caching, and more, without modifying your origin or writing any code.
* feature: Connect: Amazon Connect Chat now supports real-time message streaming.
* feature: Nimble: Amazon Nimble Studio adds support for users to stop and start streaming sessions.

## 2.1019.0
* feature: Lightsail: This release adds support to enable access logging for buckets in the Lightsail object storage service.
* feature: Neptune: Adds support for major version upgrades to ModifyDbCluster API
* feature: NetworkManager: This release adds API support to aggregate resources, routes, and telemetry data across a Global Network.
* feature: Node.js: Remove postinstall script warning end-of-support for Node.js <10.x
* feature: Node.js: Update engines field to support node >= 10.0.0
* feature: Rekognition: This Amazon Rekognition Custom Labels release introduces the management of datasets with  projects

## 2.1018.0
* feature: ApplicationInsights: Added Monitoring support for SQL Server Failover Cluster Instance. Additionally, added a new API to allow one-click monitoring of containers resources.
* feature: Connect: Amazon Connect Chat now supports real-time message streaming.
* feature: EC2: Support added for AMI sharing with organizations and organizational units in ModifyImageAttribute API
* feature: Rekognition: This release added new attributes to Rekognition Video GetCelebrityRecognition API operations.
* feature: TranscribeService: Transcribe and Transcribe Call Analytics now support automatic language identification along with custom vocabulary, vocabulary filter, custom language model and PII redaction.

## 2.1017.0
* feature: ConnectParticipant: This release adds a new boolean attribute - Connect Participant - to the CreateParticipantConnection API, which can be used to mark the participant as connected.
* feature: EC2: Added new read-only DenyAllIGWTraffic network interface attribute. Added support for DL1 24xlarge instances powered by Habana Gaudi Accelerators for deep learning model training workloads
* feature: ECS: Amazon ECS now supports running Fargate tasks on Windows Operating Systems Families which includes Windows Server 2019 Core and Windows Server 2019 Full.
* feature: GameLift: Added support for Arm-based AWS Graviton2 instances, such as M6g, C6g, and R6g.
* feature: SSMIncidents: Updating documentation, adding new field to ConflictException to indicate earliest retry timestamp for some operations, increase maximum length of nextToken fields
* feature: SageMaker: This release adds support for RStudio on SageMaker.

## 2.1016.0
* feature: AutoScaling: This release adds support for attribute-based instance type selection, a new EC2 Auto Scaling feature that lets customers express their instance requirements as a set of attributes, such as vCPU, memory, and storage.
* feature: EC2: This release adds: attribute-based instance type selection for EC2 Fleet, Spot Fleet, a feature that lets customers express instance requirements as attributes like vCPU, memory, and storage; and Spot placement score, a feature that helps customers identify an optimal location to run Spot workloads.
* feature: EKS: EKS managed node groups now support BOTTLEROCKET_x86_64 and BOTTLEROCKET_ARM_64 AMI types.
* feature: SageMaker: This release allows customers to describe one or more versioned model packages through BatchDescribeModelPackage, update project via UpdateProject, modify and read customer metadata properties using Create, Update and Describe ModelPackage and enables cross account registration of model packages.
* feature: Textract: This release adds support for asynchronously analyzing invoice and receipt documents through two new APIs: StartExpenseAnalysis and GetExpenseAnalysis

## 2.1015.0
* feature: ChimeSDKIdentity: The Amazon Chime SDK now supports push notifications through Amazon Pinpoint
* feature: ChimeSDKMessaging: The Amazon Chime SDK now supports push notifications through Amazon Pinpoint
* feature: EMRcontainers: This feature enables auto-generation of certificate  to secure the managed-endpoint and removes the need for customer provided certificate-arn during managed-endpoint setup.

## 2.1014.0
* bugfix: endpoint: Update fips endpoint heuristics test to use callback
* feature: AuditManager: This release introduces a new feature for Audit Manager: Custom framework sharing. You can now share your custom frameworks with another AWS account, or replicate them into another AWS Region under your own account.
* feature: EC2: This release adds support to create a VPN Connection that is not attached to a Gateway at the time of creation. Use this to create VPNs associated with Core Networks, or modify your VPN and attach a gateway using the modify API after creation.
* feature: RDS: This release adds support for Amazon RDS Custom, which is a new RDS management type that gives you full access to your database and operating system. For more information, see https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/rds-custom.html
* feature: Route53Resolver: New API for ResolverConfig, which allows autodefined rules for reverse DNS resolution to be disabled for a VPC

## 2.1013.0
* bugfix: endpoint: Support FIPS in endpoint heuristics
* feature: AuditManager: This release introduces character restrictions for ControlSet names. We updated regex patterns for the following attributes: ControlSet, CreateAssessmentFrameworkControlSet, and UpdateAssessmentFrameworkControlSet.
* feature: Chime: Chime VoiceConnector and VoiceConnectorGroup APIs will now return an ARN.
* feature: QuickSight: Added QSearchBar option for GenerateEmbedUrlForRegisteredUser ExperienceConfiguration to support Q search bar embedding
* feature: rest-json: Update serialization of Rest-JSON API input and Content-Type

## 2.1012.0
* feature: Appflow: Feature to add support for  JSON-L format for S3 as a source.
* feature: DirectConnect: This release adds 4 new APIS, which needs to be public able
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for specifying caption time delta in milliseconds and the ability to apply color range legalization to source content other than AVC video.
* feature: MediaPackage: When enabled, MediaPackage passes through digital video broadcasting (DVB) subtitles into the output.
* feature: MediaPackageVod: MediaPackage passes through digital video broadcasting (DVB) subtitles into the output.
* feature: Panorama: General availability for AWS Panorama. AWS SDK for Panorama includes APIs to manage your devices and nodes, and deploy computer vision applications to the edge. For more information, see the AWS Panorama documentation at http://docs.aws.amazon.com/panorama
* feature: SecurityHub: Added support for cross-Region finding aggregation, which replicates findings from linked Regions to a single aggregation Region. Added operations to view, enable, update, and delete the finding aggregation.

## 2.1011.0
* feature: ChimeSDKMessaging: The Amazon Chime SDK now allows developers to execute business logic on in-flight messages before they are delivered to members of a messaging channel with channel flows.
* feature: DataExchange: This release adds support for our public preview of AWS Data Exchange for Amazon Redshift. This enables data providers to list products including AWS Data Exchange datashares for Amazon Redshift, giving subscribers read-only access to provider data in Amazon Redshift.

## 2.1010.0
* feature: IVS: Bug fix: remove unsupported maxResults and nextToken pagination parameters from ListTagsForResource
* feature: QuickSight: AWS QuickSight Service  Features    - Add IP Restriction UI and public APIs support.

## 2.1009.0
* feature: Glue: Enable S3 event base crawler API.

## 2.1008.0
* feature: AutoScaling: Amazon EC2 Auto Scaling now supports filtering describe Auto Scaling groups API using tags
* feature: ELBv2: Adds new option to filter by availability on each type of load balancer when describing ssl policies.
* feature: RoboMaker: Adding support to GPU simulation jobs as well as non-ROS simulation jobs.
* feature: SageMaker: This release updates the provisioning artifact ID to an optional parameter in CreateProject API. The provisioning artifact ID defaults to the latest provisioning artifact ID of the product if you don't provide one.

## 2.1007.0
* feature: ConfigService: Adding Config support for AWS::OpenSearch::Domain
* feature: EC2: This release adds support for additional VPC Flow Logs delivery options to S3, such as Apache Parquet formatted files, Hourly partitions and Hive-compatible S3 prefixes
* feature: KinesisAnalyticsV2: Support for Apache Flink 1.13 in Kinesis Data Analytics. Changed the required status of some Update properties to better fit the corresponding Create properties.
* feature: StorageGateway: Adding support for Audit Logs on NFS shares and Force Closing Files on SMB shares.
* feature: WorkMail: This release adds APIs for adding, removing and retrieving details of mail domains

## 2.1006.0
* feature: CloudSearch: Adds an additional validation exception for Amazon CloudSearch configuration APIs for better error handling.
* feature: EC2: EncryptionSupport for InstanceStorageInfo added to DescribeInstanceTypes API
* feature: MediaTailor: MediaTailor now supports ad prefetching.

## 2.1005.0
* feature: ELBv2: Enable support for ALB IPv6 Target Groups (IP Address Type)
* feature: FraudDetector: New model type: Transaction Fraud Insights, which is optimized for online transaction fraud. Stored Events, which allows customers to send and store data directly within Amazon Fraud Detector. Batch Import, which allows customers to upload a CSV file of historic event data for processing and storage
* feature: MediaLive: This release adds support for Transport Stream files as an input type to MediaLive encoders.

## 2.1004.0
* feature: EC2: This release removes a requirement for filters on SearchLocalGatewayRoutes operations.
* feature: LexModelsV2: Added configuration support for an Amazon Lex bot to provide fulfillment progress updates to users while their requests are being processed. See documentation for more details: https://docs.aws.amazon.com/lexv2/latest/dg/streaming-progress.html
* feature: LexRuntimeV2: Updates API to latest version.
* feature: MediaConvert: AWS Elemental MediaConvert has added the ability to set account policies which control access restrictions for HTTP, HTTPS, and S3 content sources.
* feature: SecurityHub: Added new resource details objects to ASFF, including resources for WAF rate-based rules, EC2 VPC endpoints, ECR repositories, EKS clusters, X-Ray encryption, and OpenSearch domains. Added additional details for CloudFront distributions, CodeBuild projects, ELB V2 load balancers, and S3 buckets.
* feature: protocol: Update protocol tests

## 2.1003.0
* feature: Backup: Launch of AWS Backup Vault Lock, which protects your backups from malicious and accidental actions, works with existing backup policies, and helps you meet compliance requirements.
* feature: Chime: This release enables customers to configure Chime MediaCapturePipeline via API.
* feature: Firehose: Allow support for Amazon Opensearch Service(successor to Amazon Elasticsearch Service) as a Kinesis Data Firehose delivery destination.
* feature: Grafana: Initial release of the SDK for Amazon Managed Grafana API.
* feature: Kendra: Amazon Kendra now supports indexing and querying documents in different languages.
* feature: Schemas: Removing unused request/response objects.

## 2.1002.0
* feature: AmplifyBackend: Adding a new field 'AmplifyFeatureFlags' to the response of the GetBackend operation. It will return a stringified version of the cli.json file for the given Amplify project.
* feature: FSx: This release adds support for Lustre 2.12 to FSx for Lustre.
* feature: Kendra: Amazon Kendra now supports integration with AWS SSO
* feature: SageMaker: This release adds a new TrainingInputMode FastFile for SageMaker Training APIs.

## 2.1001.0
* bugfix: Signer: Fix the bug that httpChecksumRequired trait is not honored in SigV2
* feature: ApplicationAutoScaling: With this release, Application Auto Scaling adds support for Amazon Neptune. Customers can now automatically add or remove Read Replicas of their Neptune clusters to keep the average CPU Utilization at the target value specified by the customers.
* feature: Backup: AWS Backup Audit Manager framework report.
* feature: EC2: Released Capacity Reservation Fleet, a feature of Amazon EC2 Capacity Reservations, which provides a way to manage reserved capacity across instance types. For more information: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/cr-fleets.html
* feature: Glue: This release adds tag as an input of CreateConnection
* feature: Location: Add support for PositionFiltering.
* feature: WorkMail: This release allows customers to change their inbound DMARC settings in Amazon WorkMail.

## 2.1000.0
* feature: CodeBuild: CodeBuild now allows you to select how batch build statuses are sent to the source provider for a project.
* feature: EFS: EFS adds a new exception for short identifiers to be thrown after its migration to long resource identifiers.

## 2.999.0
* feature: AppRunner: This release contains several minor bug fixes.
* feature: SSM: When "AutoApprovable" is true for a Change Template, then specifying --auto-approve (boolean) in Start-Change-Request-Execution will create a change request that bypasses approver review. (except for change calendar restrictions)
* feature: Synthetics: CloudWatch Synthetics now enables customers to choose a customer managed AWS KMS key or an Amazon S3-managed key instead of an AWS managed key (default) for the encryption of artifacts that the canary stores in Amazon S3. CloudWatch Synthetics also supports artifact S3 location updation now.

## 2.998.0
* feature: Account: This release of the Account Management API enables customers to manage the alternate contacts for their AWS accounts. For more information, see https://docs.aws.amazon.com/accounts/latest/reference/accounts-welcome.html
* feature: CloudControl: Initial release of the SDK for AWS Cloud Control API
* feature: DataExchange: This release enables subscribers to set up automatic exports of newly published revisions using the new EventAction API.
* feature: Macie2: Amazon S3 bucket metadata now indicates whether an error or a bucket's permissions settings prevented Amazon Macie from retrieving data about the bucket or the bucket's objects.
* feature: NetworkFirewall: This release adds support for strict ordering for stateful rule groups. Using strict ordering, stateful rules are evaluated in the exact order in which you provide them.
* feature: WorkMail: This release adds support for mobile device access overrides management in Amazon WorkMail.
* feature: WorkSpaces: Added CreateUpdatedWorkspaceImage API to update WorkSpace images with latest software and drivers. Updated DescribeWorkspaceImages API to display if there are updates available for WorkSpace images.

## 2.997.0
* feature: Amp: This release adds alert manager and rule group namespace APIs
* feature: Lambda: Adds support for Lambda functions powered by AWS Graviton2 processors. Customers can now select the CPU architecture for their functions.
* feature: SESV2: This release includes the ability to use 2048 bits RSA key pairs for DKIM in SES, either with Easy DKIM or Bring Your Own DKIM.

## 2.996.0
* feature: AppIntegrations: The Amazon AppIntegrations service enables you to configure and reuse connections to external applications.
* feature: Connect: This release updates a set of APIs: CreateIntegrationAssociation, ListIntegrationAssociations, CreateUseCase, and StartOutboundVoiceContact. You can use it to create integrations with Amazon Pinpoint for the Amazon Connect Campaigns use case, Amazon Connect Voice ID, and Amazon Connect Wisdom.
* feature: ELBv2: Adds new ALB-type target group to facilitate forwarding traffic from NLB to ALB
* feature: Pinpoint: Added support for journey with contact center activity
* feature: VoiceID: Released the Amazon Voice ID SDK, for usage with the Amazon Connect Voice ID feature released for Amazon Connect.
* feature: Wisdom: Released Amazon Connect Wisdom, a feature of Amazon Connect, which provides real-time recommendations and search functionality in general availability (GA).  For more information, see https://docs.aws.amazon.com/wisdom/latest/APIReference/Welcome.html.

## 2.995.0
* feature: EC2: DescribeInstances now returns Platform Details, Usage Operation, and Usage Operation Update Time.
* feature: LicenseManager: AWS License Manager now allows customers to get the LicenseArn in the Checkout API Response.

## 2.994.0
* bugfix: HttpRequest: Allows request body to be either a string or a buffer
* feature: AppSync: Documented the new OpenSearchServiceDataSourceConfig data type. Added deprecation notes to the ElasticsearchDataSourceConfig data type.
* feature: MediaConvert: This release adds style and positioning support for caption or subtitle burn-in from rich text sources such as TTML. This release also introduces configurable image-based trick play track generation.
* feature: SSM: Added cutoff behavior support for preventing new task invocations from starting when the maintenance window cutoff time is reached.

## 2.993.0
* feature: Imagebuilder: This feature adds support for specifying GP3 volume throughput and configuring instance metadata options for instances launched by EC2 Image Builder.
* feature: LexModelsV2: This release adds support for utterances statistics for bots built using Lex V2 console and APIs. For details, see: https://docs.aws.amazon.com/lexv2/latest/dg/monitoring-utterances.html
* feature: LicenseManager: AWS License Manager now allows customers to change their Windows Server or SQL license types from Bring-Your-Own-License (BYOL) to License Included or vice-versa (using the customer's media).
* feature: MediaPackageVod: MediaPackage VOD will now return the current processing statuses of an asset's endpoints. The status can be QUEUED, PROCESSING, PLAYABLE, or FAILED.
* feature: MediaTailor: This release adds support to configure logs for playback configuration.
* feature: WAFV2: Added the regex match rule statement, for matching web requests against a single regular expression.

## 2.992.0
* feature: Comprehend: Amazon Comprehend now supports versioning of custom models, improved training with ONE_DOC_PER_FILE text documents for custom entity recognition, ability to provide specific test sets during training, and live migration to new model endpoints.
* feature: EC2: This update adds support for downloading configuration templates using new APIs (GetVpnConnectionDeviceTypes and GetVpnConnectionDeviceSampleConfiguration) and Internet Key Exchange version 2 (IKEv2) parameters for many popular CGW devices.
* feature: ECR: This release adds additional support for repository replication
* feature: Iot: This release adds support for verifying, viewing and filtering AWS IoT Device Defender detect violations with four verification states.
* feature: Kafka: Added StateInfo to ClusterInfo

## 2.991.0
* feature: DMS: Optional flag force-planned-failover added to reboot-replication-instance API call. This flag can be used to test a planned failover scenario used during some maintenance operations.
* feature: ES: This release adds an optional parameter in the ListDomainNames API to filter domains based on the engine type (OpenSearch/Elasticsearch).
* feature: OpenSearch: This release adds an optional parameter in the ListDomainNames API to filter domains based on the engine type (OpenSearch/Elasticsearch).

## 2.990.0
* feature: KafkaConnect: This is the initial SDK release for Amazon Managed Streaming for Apache Kafka Connect (MSK Connect).
* feature: Macie2: This release adds support for specifying which managed data identifiers are used by a classification job, and retrieving a list of managed data identifiers that are available.
* feature: Pinpoint: This SDK release adds a new feature for Pinpoint campaigns, in-app messaging.
* feature: RoboMaker: Adding support to create container based Robot and Simulation applications by introducing an environment field
* feature: S3: Add support for access point arn filtering in S3 CW Request Metrics
* feature: SageMaker: Add API for users to retry a failed pipeline execution or resume a stopped one.
* feature: TranscribeService: This release adds support for subtitling with Amazon Transcribe batch jobs.

## 2.989.0
* feature: Chime: Adds support for SipHeaders parameter for CreateSipMediaApplicationCall.
* feature: Comprehend: Amazon Comprehend now allows you to train and run PDF and Word documents for custom entity recognition. With PDF and Word formats, you can extract information from documents containing headers, lists and tables.
* feature: EC2: This release adds support for vt1 3xlarge, 6xlarge and 24xlarge instances powered by Xilinx Alveo U30 Media Accelerators for video transcoding workloads
* feature: SageMaker: This release adds support for "Project Search"
* feature: WAFV2: This release adds support for including rate based rules in a rule group.

## 2.988.0
* feature: Iot: AWS IoT Rules Engine adds OpenSearch action. The OpenSearch rule action lets you stream data from IoT sensors and applications to Amazon OpenSearch Service which is a successor to Amazon Elasticsearch Service.

## 2.987.0
* feature: QuickSight: Add new data source type for Amazon OpenSearch (successor to Amazon ElasticSearch).
* feature: RDS: This release adds support for providing a custom timeout value for finding a scaling point during autoscaling in Aurora Serverless v1.
* feature: SageMaker: This release adds support for "Lifecycle Configurations" to SageMaker Studio
* feature: TranscribeService: This release adds an API option for startTranscriptionJob and startMedicalTranscriptionJob that allows the user to specify encryption context key value pairs for batch jobs.

## 2.986.0
* feature: CodeGuruReviewer: The Amazon CodeGuru Reviewer API now includes the RuleMetadata data object and a Severity attribute on a RecommendationSummary object. A RuleMetadata object contains information about a rule that generates a recommendation. Severity indicates how severe the issue associated with a recommendation is.
* feature: EMR: This release enables customers to login to EMR Studio using AWS Identity and Access Management (IAM) identities or identities in their Identity Provider (IdP) via IAM.
* feature: LookoutEquipment: Added OffCondition parameter to CreateModel API

## 2.985.0
* feature: Kafka: Amazon MSK has added a new API that allows you to update the encrypting and authentication settings for an existing cluster.
* feature: OpenSearch: Updated Configuration APIs for Amazon OpenSearch Service (successor to Amazon Elasticsearch Service)

## 2.984.0
* feature: Amp: This release adds tagging support for Amazon Managed Service for Prometheus workspace.
* feature: EKS: Adding RegisterCluster and DeregisterCluster operations, to support connecting external clusters to EKS.
* feature: ForecastService: Predictor creation now supports selecting an accuracy metric to optimize in AutoML and hyperparameter optimization. This release adds additional accuracy metrics for predictors - AverageWeightedQuantileLoss, MAPE and MASE.
* feature: MediaPackage: SPEKE v2 support for live CMAF packaging type. SPEKE v2 is an upgrade to the existing SPEKE API to support multiple encryption keys, it supports live DASH currently.

## 2.983.0
* feature: CodeGuruReviewer: Added support for CodeInconsistencies detectors
* feature: FraudDetector: Enhanced GetEventPrediction API response to include risk scores from imported SageMaker models
* feature: Outposts: This release adds a new API CreateOrder.

## 2.982.0
* feature: ACMPCA: Private Certificate Authority Service now allows customers to enable an online certificate status protocol (OCSP) responder service on their private certificate authorities. Customers can also optionally configure a custom CNAME for their OCSP responder.
* feature: EFS: Adds support for EFS Intelligent-Tiering, which uses EFS Lifecycle Management to monitor file access patterns and is designed to automatically transition files to and from your corresponding Infrequent Access (IA) storage classes.
* feature: FSx: Announcing Amazon FSx for NetApp ONTAP, a new service that provides fully managed shared storage in the AWS Cloud with the data access and management capabilities of ONTAP.
* feature: LexModelBuildingService: Lex now supports Korean (ko-KR) locale.
* feature: QuickSight: This release adds support for referencing parent datasets as sources in a child dataset.
* feature: S3Control: S3 Multi-Region Access Points provide a single global endpoint to access a data set that spans multiple S3 buckets in different AWS Regions.
* feature: Schemas: This update include the support for Schema Discoverer to discover the events sent to the bus from another account. The feature will be enabled by default when discoverer is created or updated but can also be opt-in or opt-out  by specifying the value for crossAccount.
* feature: SecurityHub: New ASFF Resources: AwsAutoScalingLaunchConfiguration, AwsEc2VpnConnection, AwsEcrContainerImage. Added KeyRotationStatus to AwsKmsKey. Added AccessControlList, BucketLoggingConfiguration,BucketNotificationConfiguration and BucketNotificationConfiguration to AwsS3Bucket.
* feature: Transfer: AWS Transfer Family introduces Managed Workflows for creating, executing, monitoring, and standardizing post file transfer processing

## 2.981.0
* feature: EC2: Added LaunchTemplate support for the IMDS IPv6 endpoint
* feature: MediaTailor: This release adds support for wall clock programs in LINEAR channels.
* feature: ServiceCatalogAppRegistry: Introduction of GetAssociatedResource API and GetApplication response extension for Resource Groups support.

## 2.980.0
* feature: Iot: Added Create/Update/Delete/Describe/List APIs for a new IoT resource named FleetMetric. Added a new Fleet Indexing query API named GetBucketsAggregation. Added a new field named DisconnectedReason in Fleet Indexing query response. Updated their related documentations.
* feature: Polly: Amazon Polly adds new South African English voice - Ayanda. Ayanda is available as Neural voice only.
* feature: SQS: Amazon SQS adds a new queue attribute, RedriveAllowPolicy, which includes the dead-letter queue redrive permission parameters. It defines which source queues can specify dead-letter queues as a JSON object.

## 2.979.0
* feature: CloudFormation: AWS CloudFormation allows you to iteratively develop your applications when failures are encountered without rolling back successfully provisioned resources. By specifying stack failure options, you can troubleshoot resources in a CREATE_FAILED or UPDATE_FAILED status.
* feature: Firehose: This release adds the Dynamic Partitioning feature to Kinesis Data Firehose service for S3 destinations.
* feature: KMS: This release has changes to KMS nomenclature to remove the word master from both the "Customer master key" and "CMK" abbreviation and replace those naming conventions with "KMS key".

## 2.978.0
* feature: EC2: This release adds the BootMode flag to the ImportImage API and showing the detected BootMode of an ImportImage task.
* feature: EMR: Amazon EMR now supports auto-terminating idle EMR clusters. You can specify the idle timeout value when enabling auto-termination for both running and new clusters and Amazon EMR automatically terminates the cluster when idle timeout kicks in.

## 2.977.0
* feature: ComputeOptimizer: Adds support for 1) the AWS Graviton (AWS_ARM64) recommendation preference for Amazon EC2 instance and Auto Scaling group recommendations, and 2) the ability to get the enrollment statuses for all member accounts of an organization.
* feature: EC2: Support added for resizing VPC prefix lists
* feature: Rekognition: This release added new attributes to Rekognition RecognizeCelebities and GetCelebrityInfo API operations.
* feature: TranscribeService: This release adds support for batch transcription in six new languages - Afrikaans, Danish, Mandarin Chinese (Taiwan), New Zealand English, South African English, and Thai.

## 2.976.0
* feature: CloudWatchEvents: AWS CWEvents adds an enum of EXTERNAL for EcsParameters LaunchType for PutTargets API
* feature: DataSync: Added include filters to CreateTask and UpdateTask, and added exclude filters to StartTaskExecution, giving customers more granular control over how DataSync transfers files, folders, and objects.
* feature: EC2: Support added for IMDS IPv6 endpoint
* feature: EventBridge: AWS EventBridge adds an enum of EXTERNAL for EcsParameters LaunchType for PutTargets API
* feature: FMS: AWS Firewall Manager now supports triggering resource cleanup workflow when account or resource goes out of policy scope for AWS WAF, Security group, AWS Network Firewall, and Amazon Route 53 Resolver DNS Firewall policies.

## 2.975.0
* feature: IotData: Updated Publish with support for new Retain flag and added two new API operations: GetRetainedMessage, ListRetainedMessages.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added MBAFF encoding support for AVC video and the ability to pass encryption context from the job settings to S3.
* feature: Polly: Amazon Polly adds new New Zealand English voice - Aria. Aria is available as Neural voice only.
* feature: SSM: Updated Parameter Store property for logging improvements.
* feature: TranscribeService: This release adds support for feature tagging with Amazon Transcribe batch jobs.

## 2.974.0
* feature: APIGateway: Adding some of the pending releases (1) Adding WAF Filter to GatewayResponseType enum (2) Ensuring consistent error model for all operations (3) Add missing BRE to GetVpcLink operation
* feature: Backup: AWS Backup - Features: Evaluate your backup activity and generate audit reports.
* feature: DLM: Added AMI deprecation support for Amazon Data Lifecycle Manager EBS-backed AMI policies.
* feature: DMS: Amazon AWS DMS service now support Redis target endpoint migration. Now S3 endpoint setting is capable to setup features which are used to be configurable only in extract connection attributes.
* feature: FraudDetector: Updated an element of the DescribeModelVersion API response (LogitMetrics -> logOddsMetrics) for clarity. Added new exceptions to several APIs to protect against unlikely scenarios.
* feature: Glue: Add support for Custom Blueprints

## 2.973.0
* feature: Comprehend: Add tagging support for Comprehend async inference job.
* feature: EC2: encryptionInTransitSupported added to DescribeInstanceTypes API
* feature: EKS: Adds support for EKS add-ons "preserve" flag, which allows customers to maintain software on their EKS clusters after removing it from EKS add-ons management.
* feature: IMDS: Support IPv6 endpoints in IMDS

## 2.972.0
* feature: Appflow: This release adds support for SAPOData connector and extends Veeva connector for document extraction.
* feature: ApplicationAutoScaling: This release extends Application Auto Scaling support for replication group of Amazon ElastiCache Redis clusters. Auto Scaling monitors and automatically expands node group count and number of replicas per node group when a critical usage threshold is met or according to customer-defined schedule.
* feature: EC2: The ImportImage API now supports the ability to create AMIs with AWS-managed licenses for Microsoft SQL Server for both Windows and Linux.
* feature: MemoryDB: AWS MemoryDB  SDK now supports all APIs for newly launched MemoryDB service.

## 2.971.0
* feature: CodeBuild: CodeBuild now allows you to make the build results for your build projects available to the public without requiring access to an AWS account.
* feature: SageMaker: Amazon SageMaker now supports Asynchronous Inference endpoints. Adds PlatformIdentifier field that allows Notebook Instance creation with different platform selections. Increases the maximum number of containers in multi-container endpoints to 15. Adds more instance types to InstanceType field.
* feature: SageMakerRuntime: Amazon SageMaker Runtime now supports InvokeEndpointAsync to asynchronously invoke endpoints that were created with the AsyncInferenceConfig object in the EndpointConfig. Asynchronous invocations support larger payload sizes in Amazon S3 and longer processing times.

## 2.970.0
* feature: Cloud9: Added DryRun parameter to CreateEnvironmentEC2 API. Added ManagedCredentialsActions parameter to UpdateEnvironment API
* feature: CostExplorer: This release is a new feature for Cost Categories: Split charge rules. Split charge rules enable you to allocate shared costs between your cost category values.
* feature: EC2: This release adds support for EC2 ED25519 key pairs for authentication

## 2.969.0
* feature: CodeBuild: CodeBuild now allows you to select how batch build statuses are sent to the source provider for a project.
* feature: ConfigService: Update ResourceType enum with values for Backup Plan, Selection, Vault, RecoveryPoint; ECS Cluster, Service, TaskDefinition; EFS AccessPoint, FileSystem; EKS Cluster; ECR Repository resources
* feature: DirectoryService: This release adds support for describing client authentication settings.
* feature: IoTSiteWise: AWS IoT SiteWise added query window for the interpolation interval. AWS IoT SiteWise computes each interpolated value by using data points from the timestamp of each interval minus the window to the timestamp of each interval plus the window.
* feature: LicenseManager: AWS License Manager now allows end users to call CheckoutLicense API using new CheckoutType PERPETUAL. Perpetual checkouts allow sellers to check out a quantity of entitlements to be drawn down for consumption.

## 2.968.0
* feature: CustomerProfiles: This release introduces Standard Profile Objects, namely Asset and Case which contain values populated by data from third party systems and belong to a specific profile. This release adds an optional parameter, ObjectFilter to the ListProfileObjects API in order to search for these Standard Objects.
* feature: EMR: Amazon EMR customers can now specify custom AMIs at the instance level in their clusters. This allows using custom AMIs in clusters that have instances with different instruction set architectures, e.g. m5.xlarge (x86) and m6g.xlarge (ARM).
* feature: ElastiCache: This release adds ReplicationGroupCreateTime field to ReplicationGroup which indicates the UTC time when ElastiCache ReplicationGroup is created

## 2.967.0
* feature: APIGateway: Adding support for ACM imported or private CA certificates for mTLS enabled domain names
* feature: ApiGatewayV2: Adding support for ACM imported or private CA certificates for mTLS enabled domain names
* feature: DataBrew: This SDK release adds support for the output of a recipe job results to Tableau Hyper format.
* feature: Lambda: Lambda Python 3.9 runtime launch
* feature: SageMaker: Amazon SageMaker Autopilot adds new metrics for all candidate models generated by Autopilot experiments.

## 2.966.0
* feature: CodeBuild: CodeBuild now allows you to make the build results for your build projects available to the public without requiring access to an AWS account.
* feature: Nimble: Add new attribute 'ownedBy' in Streaming Session APIs. 'ownedBy' represents the AWS SSO Identity Store User ID of the owner of the Streaming Session resource.
* feature: SnowDeviceManagement: AWS Snow Family customers can remotely monitor and operate their connected AWS Snowcone devices.

## 2.965.0
* feature: Chime: Add support for "auto" in Region field of StartMeetingTranscription API request.

## 2.964.0
* feature: Rekognition: This release adds support for four new types of segments (opening credits, content segments, slates, and studio logos), improved accuracy for credits and shot detection and new filters to control black frame detection.
* feature: WAFV2: This release adds APIs to support versioning feature of AWS WAF Managed rule groups

## 2.963.0
* feature: ChimeSDKIdentity: The Amazon Chime SDK Identity APIs allow software developers to create and manage unique instances of their messaging applications.
* feature: ChimeSDKMessaging: The Amazon Chime SDK Messaging APIs allow software developers to send and receive messages in custom messaging applications.
* feature: Connect: This release adds support for agent status and hours of operation. For details, see the Release Notes in the Amazon Connect Administrator Guide.
* feature: Lightsail: This release adds support to track when a bucket access key was last used.

## 2.962.0
* feature: AutoScaling: EC2 Auto Scaling adds configuration checks and Launch Template validation to Instance Refresh.
* feature: LexModelsV2: Customers can now toggle the active field on prompts and responses.

## 2.961.0
* feature: RDS: This release adds AutomaticRestartTime to the DescribeDBInstances and DescribeDBClusters operations. AutomaticRestartTime indicates the time when a stopped DB instance or DB cluster is restarted automatically.
* feature: SSMIncidents: Documentation updates for Incident Manager.
* feature: TranscribeService: This release adds support for call analytics (batch) within Amazon Transcribe.

## 2.960.0
* feature: Glue: Add ConcurrentModificationException to create-table, delete-table, create-database, update-database, delete-database
* feature: IoTSiteWise: My AWS Service (placeholder) - This release introduces custom Intervals and offset for tumbling window in metric for AWS IoT SiteWise.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added control over the passthrough of XDS captions metadata to outputs.
* feature: Redshift: API support for Redshift Data Sharing feature.

## 2.959.0
* feature: GreengrassV2: This release adds support for component system resource limits and idempotent Create operations. You can now specify the maximum amount of CPU and memory resources that each component can use.
* feature: SSMContacts: Added new attribute in AcceptCode API. AcceptCodeValidation takes in two values - ENFORCE, IGNORE. ENFORCE forces validation of accept code and IGNORE ignores it which is also the default behavior; Corrected TagKeyList length from 200 to 50

## 2.958.0
* feature: AppSync: AWS AppSync now supports a new authorization mode allowing you to define your own authorization logic using an AWS Lambda function.
* feature: SageMaker: API changes with respect to Lambda steps in model building pipelines. Adds several waiters to async Sagemaker Image APIs. Add more instance types to AppInstanceType field
* feature: SecretsManager: Add support for KmsKeyIds in the ListSecretVersionIds API response

## 2.957.0
* feature: Chime: Adds support for live transcription of meetings with Amazon Transcribe and Amazon Transcribe Medical.  The new APIs, StartMeetingTranscription and StopMeetingTranscription, control the generation of user-attributed transcriptions sent to meeting clients via Amazon Chime SDK data messages.
* feature: EC2: This release adds support for G4ad xlarge and 2xlarge instances powered by AMD Radeon Pro V520 GPUs and AMD 2nd Generation EPYC processors
* feature: IoTSiteWise: Added support for AWS IoT SiteWise Edge. You can now create an AWS IoT SiteWise gateway that runs on AWS IoT Greengrass V2. With the gateway,  you can collect local server and equipment data, process the data, and export the selected data from the edge to the AWS Cloud.
* feature: Iot: Increase maximum credential duration of role alias to 12 hours.
* feature: SavingsPlans: Documentation update for valid Savings Plans offering ID pattern

## 2.956.0
* feature: CloudFormation: SDK update to support Importing existing Stacks to new/existing Self Managed StackSet - Stack Import feature.

## 2.955.0
* feature: Batch: Add support for ListJob filters
* feature: IoTAnalytics: IoT Analytics now supports creating a dataset resource with IoT SiteWise MultiLayerStorage data stores, enabling customers to query industrial data within the service. This release includes adding JOIN functionality for customers to query multiple data sources in a dataset.
* feature: IoTWireless: Add SidewalkManufacturingSn as an identifier to allow Customer to query WirelessDevice, in the response, AmazonId is added in the case that Sidewalk device is return.
* feature: LexModelsV2: Add waiters that automatically poll for resource status for asynchronous operations, such as building a bot
* feature: QuickSight: Add support to use row-level security with tags when embedding dashboards for users not provisioned in QuickSight
* feature: RedshiftData: Added structures to support new Data API operation BatchExecuteStatement, used to execute multiple SQL statements within a single transaction.
* feature: Route53: This release adds support for the RECOVERY_CONTROL health check type to be used in conjunction with Route53 Application Recovery Controller.
* feature: Route53RecoveryCluster: Amazon Route 53 Application Recovery Controller's routing control - Routing Control Data Plane APIs help you update the state (On/Off) of the routing controls to reroute traffic across application replicas in a 100% available manner.
* feature: Route53RecoveryControlConfig: Amazon Route 53 Application Recovery Controller's routing control - Routing Control Configuration APIs help you create and delete clusters, control panels, routing controls and safety rules. State changes (On/Off) of routing controls are not part of configuration APIs.
* feature: Route53RecoveryReadiness: Amazon Route 53 Application Recovery Controller's readiness check capability continually monitors resource quotas, capacity, and network routing policies to ensure that the recovery environment is scaled and configured to take over when needed.

## 2.954.0
* feature: CloudWatch: SDK update to support creation of Cross-Account Metric Alarms and update API documentation.
* feature: S3Control: S3 Access Point aliases can be used anywhere you use S3 bucket names to access data in S3
* feature: Synthetics: CloudWatch Synthetics now supports visual testing in its canaries.
* feature: Textract: Adds support for AnalyzeExpense, a new API to extract relevant data such as contact information, items purchased, and vendor name, from almost any invoice or receipt without the need for any templates or configuration.

## 2.953.0
* feature: S3Outposts: Add on-premise access type support for endpoints
* feature: SecurityHub: Added product name, company name, and Region fields for security findings. Added details objects for RDS event subscriptions and AWS ECS services. Added fields to the details for AWS Elasticsearch domains.

## 2.952.0
* feature: DataBrew: This SDK release adds two new features: 1) Output to Native JDBC destinations and 2) Adding configurations to profile jobs
* feature: EC2: This release allows customers to assign prefixes to their elastic network interface and to reserve IP blocks in their subnet CIDRs. These reserved blocks can be used to assign prefixes to elastic network interfaces or be excluded from auto-assignment.
* feature: MediaLive: MediaLive now supports passing through style data on WebVTT caption outputs.
* feature: QLDB: Amazon QLDB now supports ledgers encrypted with customer managed KMS keys. Changes in CreateLedger, UpdateLedger and DescribeLedger APIs to support the changes.

## 2.951.0
* feature: CodeBuild: AWS CodeBuild now allows you to set the access permissions for build artifacts, project artifacts, and log files that are uploaded to an Amazon S3 bucket that is owned by another account.
* feature: EMR: EMR now supports new DescribeReleaseLabel and ListReleaseLabel APIs. They can provide Amazon EMR release label details. You can programmatically list available releases and applications for a specific Amazon EMR release label.
* feature: Kendra: Amazon Kendra now provides a data source connector for Amazon WorkDocs. For more information, see https://docs.aws.amazon.com/kendra/latest/dg/data-source-workdocs.html
* feature: Lambda: New ResourceConflictException error code for PutFunctionEventInvokeConfig, UpdateFunctionEventInvokeConfig, and DeleteFunctionEventInvokeConfig operations.
* feature: Personalize: My AWS Service (placeholder) - Making minProvisionedTPS an optional parameter when creating a campaign. If not provided, it defaults to 1.
* feature: RDS: Adds the OriginalSnapshotCreateTime field to the DBSnapshot response object. This field timestamps the underlying data of a snapshot and doesn't change when the snapshot is copied.

## 2.950.0
* feature: EC2: Added idempotency to the CreateVolume API using the ClientToken request parameter

## 2.949.0
* feature: EMRcontainers: Updated DescribeManagedEndpoint and ListManagedEndpoints to return failureReason and stateDetails in API response.
* feature: Health: In the Health API, the maximum number of entities for the EventFilter and EntityFilter data types has changed from 100 to 99. This change is related to an internal optimization of the AWS Health service.
* feature: Location: Add five new API operations: UpdateGeofenceCollection, UpdateMap, UpdatePlaceIndex, UpdateRouteCalculator, UpdateTracker.
* feature: Model: support document types trait that allows serializing and parsing unmodeled json value
* feature: RoboMaker: This release allows customers to create a new version of WorldTemplates with support for Doors.

## 2.948.0
* feature: AuditManager: This release relaxes the S3 URL character restrictions in AWS Audit Manager. Regex patterns have been updated for the following attributes: s3RelativePath, destination, and s3ResourcePath. 'AWS' terms have also been replaced with entities to align with China Rebrand documentation efforts.
* feature: Chime: This SDK release adds Account Status as one of the attributes in Account API response

## 2.947.0
* feature: EC2: This feature enables customers  to specify weekly recurring time window(s) for scheduled events that reboot, stop or terminate EC2 instances.
* feature: IoTSiteWise: Update the default endpoint for the APIs used to manage asset models, assets, gateways, tags, and account configurations. If you have firewalls with strict egress rules, configure the rules to grant you access to api.iotsitewise.[region].amazonaws.com or api.iotsitewise.[cn-region].amazonaws.com.cn.
* feature: LexModelBuildingService: Lex now supports the en-IN locale

## 2.946.0
* feature: ACM: Added support for RSA 3072 SSL certificate import
* feature: DMS: Release of feature needed for ECA-Endpoint settings. This allows customer to delete a field in endpoint settings by using --exact-settings flag in modify-endpoint api. This also displays default values for certain required fields of endpoint settings in describe-endpoint-settings api.
* feature: Glue: Add support for Event Driven Workflows
* feature: HealthLake: General availability for Amazon HealthLake. StartFHIRImportJob and StartFHIRExportJob APIs now require AWS KMS parameter. For more information, see the Amazon HealthLake Documentation https://docs.aws.amazon.com/healthlake/index.html.
* feature: Lightsail: This release adds support for the Amazon Lightsail object storage service, which allows you to create buckets and store objects.
* feature: WellArchitected: This update provides support for Well-Architected API users to mark answer choices as not applicable.

## 2.945.0
* feature: AmplifyBackend: Added Sign in with Apple OAuth provider.
* feature: DevOpsGuru: Add paginator for GetCostEstimation
* feature: DirectConnect: This release adds a new filed named awsLogicalDeviceId that it displays the AWS Direct Connect endpoint which terminates a physical connection's BGP Sessions.
* feature: LexModelBuildingService: Customers can now migrate bots built with Lex V1 APIs to V2 APIs. This release adds APIs to initiate and manage the migration of a bot.
* feature: Redshift: Release new APIs to support new Redshift feature - Authentication Profile
* feature: SSM: Changes to OpsCenter APIs to support a new feature, operational insights.

## 2.944.0
* feature: Kendra: Amazon Kendra now supports Principal Store

## 2.943.0
* feature: FraudDetector: This release adds support for ML Explainability to display model variable importance value in Amazon Fraud Detector.
* feature: MediaConvert: MediaConvert now supports color, style and position information passthrough from 608 and Teletext to SRT and WebVTT subtitles. MediaConvert now also supports Automatic QVBR quality levels for QVBR RateControlMode.
* feature: SageMaker: Releasing new APIs related to Tuning steps in model building pipelines.

## 2.942.0
* feature: DevOpsGuru: Add AnomalyReportedTimeRange field to include open and close time of anomalies.
* feature: EKS: Added waiters for EKS FargateProfiles.
* feature: FMS: AWS Firewall Manager now supports route table monitoring, and provides remediation action recommendations to security administrators for AWS Network Firewall policies with misconfigured routes.
* feature: MediaTailor: Add ListAlerts for Channel, Program, Source Location, and VOD Source to return alerts for resources.
* feature: Outposts: Added property filters for listOutposts

## 2.941.0
* feature: Chime: Releasing new APIs for AWS Chime MediaCapturePipeline
* feature: CloudFront: Amazon CloudFront now provides two new APIs, ListConflictingAliases and AssociateAlias, that help locate and move Alternate Domain Names (CNAMEs) if you encounter the CNAMEAlreadyExists error code.
* feature: EC2: This release adds resource ids and tagging support for VPC security group rules.
* feature: IoTSiteWise: This release add storage configuration APIs for AWS IoT SiteWise.
* feature: MQ: adds support for modifying the maintenance window for brokers.
* feature: StorageGateway: Adding support for oplocks for SMB file shares,  S3 Access Point and S3 Private Link for all file shares and IP address support for file system associations

## 2.940.0
* feature: EKS: Adding new error code UnsupportedAddonModification for Addons in EKS
* feature: Imagebuilder: Adds support for specifying parameters to customize components for recipes. Expands configuration of the Amazon EC2 instances that are used for building and testing images, including the ability to specify commands to run on launch, and more control over installation and removal of the SSM agent.
* feature: Lambda: Added support for AmazonMQRabbitMQ as an event source. Added support for VIRTUAL_HOST as SourceAccessType for streams event source mappings.
* feature: Mgn: Bug fix: Remove not supported EBS encryption type "NONE"

## 2.939.0
* feature: EC2: This release removes network-insights-boundary
* feature: cloudhsmv2: Enable CORS

## 2.938.0
* feature: EC2: Adding a new reserved field to support future infrastructure improvements for Amazon EC2 Fleet.
* feature: SageMaker: SageMaker model registry now supports up to 5 containers and associated environment variables.

## 2.937.0
* feature: AutoScaling: Amazon EC2 Auto Scaling infrastructure improvements and optimizations.
* feature: DataBrew: Adds support for the output of job results to the AWS Glue Data Catalog.
* feature: MediaPackageVod: Add support for Widevine DRM on CMAF packaging configurations. Both Widevine and FairPlay DRMs can now be used simultaneously, with CBCS encryption.
* feature: SSMContacts: Fixes the tag key length range to 128 chars,  tag value length to 256 chars; Adds support for UTF-8 chars for contact and channel names, Allows users to unset name in UpdateContact API; Adds throttling exception to StopEngagement API, validation exception to APIs UntagResource, ListTagsForResource
* feature: ServiceDiscovery: AWS Cloud Map now allows configuring the TTL of the SOA record for a hosted zone to control the negative caching for new services.

## 2.936.0
* feature: Glue: Add JSON Support for Glue Schema Registry
* feature: MediaConvert: MediaConvert adds support for HDR10+, ProRes 4444,  and XAVC outputs, ADM/DAMF support for Dolby Atmos ingest, and alternative audio and WebVTT caption ingest via HLS inputs. MediaConvert also now supports creating trickplay outputs for Roku devices for HLS, CMAF, and DASH output groups.
* feature: Redshift: Added InvalidClusterStateFault to the DisableLogging API, thrown when calling the API on a non available cluster.
* feature: SageMaker: Sagemaker Neo now supports running compilation jobs using customer's Amazon VPC

## 2.935.0
* feature: AmplifyBackend: Imports an existing backend authentication resource.
* feature: Proton: Added waiters for template registration, service operations, and environment deployments.
* feature: Snowball: AWS Snow Family customers can remotely monitor and operate their connected AWS Snowcone devices. AWS Snowball Edge Storage Optimized customers can now import and export their data using NFS.

## 2.934.0
* feature: Chime: Adds EventIngestionUrl field to MediaPlacement
* feature: CodeBuild: BucketOwnerAccess is currently not supported
* feature: DAX: Add support for encryption in transit to DAX clusters.
* feature: Kendra: Amazon Kendra now supports SharePoint 2013 and SharePoint 2016 when using a SharePoint data source.
* feature: SecurityHub: Added new resource details for ECS clusters and ECS task definitions. Added additional information for S3 buckets, Elasticsearch domains, and API Gateway V2 stages.
* feature: Transfer: Customers can successfully use legacy clients with Transfer Family endpoints enabled for FTPS and FTP behind routers, firewalls, and load balancers by providing a Custom IP address used for data channel communication.
* feature: WAFV2: Added support for 15 new text transformation.

## 2.933.0
* feature: CloudFront: Amazon CloudFront adds support for a new security policy, TLSv1.2_2021.
* feature: CloudSearch: This release replaces previous generation CloudSearch instances with equivalent new instances that provide better stability at the same price.
* feature: CloudWatchEvents: Added the following parameters to ECS targets: CapacityProviderStrategy, EnableECSManagedTags, EnableExecuteCommand, PlacementConstraints, PlacementStrategy, PropagateTags, ReferenceId, and Tags
* feature: CodeGuruReviewer: Adds support for S3 based full repository analysis and changed lines scan.
* feature: EC2: This release adds support for provisioning your own IP (BYOIP) range in multiple regions. This feature is in limited Preview for this release. Contact your account manager if you are interested in this feature.
* feature: EventBridge: Added the following parameters to ECS targets: CapacityProviderStrategy, EnableECSManagedTags, EnableExecuteCommand, PlacementConstraints, PlacementStrategy, PropagateTags, ReferenceId, and Tags
* feature: LicenseManager: AWS License Manager now allows license administrators and end users to communicate to each other by setting custom status reasons when updating the status on a granted license.
* feature: MediaTailor: Update GetChannelSchedule to return information on ad breaks.
* feature: QuickSight: Releasing new APIs for AWS QuickSight Folders

## 2.932.0
* feature: ApiGateway: adds mention of default value for "enabled" field of CreateApiKeyRequest for better documentation
* feature: CloudFormation: CloudFormation registry service now supports 3rd party public type sharing

## 2.931.0
* feature: Chime: This release adds a new API UpdateSipMediaApplicationCall, to update an in-progress call for SipMediaApplication.
* feature: Kendra: Amazon Kendra now supports the indexing of web documents for search through the web crawler.
* feature: Location: Enable CORS
* feature: RDS: This release enables Database Activity Streams for RDS Oracle
* feature: SageMaker: Enable ml.g4dn instance types for SageMaker Batch Transform and SageMaker Processing

## 2.930.0
* feature: EC2: This release adds support for VLAN-tagged network traffic over an Elastic Network Interface (ENI). This feature is in limited Preview for this release. Contact your account manager if you are interested in this feature.
* feature: KMS: Adds support for multi-Region keys
* feature: MediaTailor: Adds AWS Secrets Manager Access Token Authentication for Source Locations
* feature: Model: Add support for httpChecksumRequired trait. SDK will insert Content-MD5 header value for operations with this trait. To disable the behavior, users can unset computeChecksums config
* feature: RDS: This release enables fast cloning in Aurora Serverless. You can now clone between Aurora Serverless clusters and Aurora Provisioned clusters.

## 2.929.0
* feature: Connect: This release adds new sets of APIs: AssociateBot, DisassociateBot, and ListBots. You can use it to programmatically add an Amazon Lex bot or Amazon Lex V2 bot on the specified Amazon Connect instance
* feature: EC2: EC2 M5n, M5dn, R5n, R5dn metal instances with 100 Gbps network performance and Elastic Fabric Adapter (EFA) for ultra low latency
* feature: LexModelsV2: This release adds support for Multi Valued slots in Amazon Lex V2 APIs for model building
* feature: LexRuntimeV2: Updates API to latest version.
* feature: RedshiftData: Redshift Data API service now supports SQL parameterization.

## 2.928.0
* feature: GreengrassV2: We have verified the APIs being released here and are ready to release
* feature: IoTAnalytics: Adds support for data store partitions.
* feature: LookoutMetrics: Added "LEARNING" status for anomaly detector and updated description for "Offset" parameter in MetricSet APIs.

## 2.927.0
* feature: EC2: Amazon EC2 adds new AMI property to flag outdated AMIs
* feature: MediaConnect: When you enable source failover, you can now designate one of two sources as the primary source. You can choose between two failover modes to prevent any disruption to the video stream. Merge combines the sources into a single stream. Failover allows switching between a primary and a backup stream.
* feature: MediaLive: AWS MediaLive now supports OCR-based conversion of DVB-Sub and SCTE-27 image-based source captions to WebVTT, and supports ingest of ad avail decorations in HLS input manifests.

## 2.926.0
* feature: AppMesh: AppMesh now supports additional routing capabilities in match and rewrites for Gateway Routes and Routes. Additionally, App Mesh also supports specifying DNS Response Types in Virtual Nodes.
* feature: Appflow: Adding MAP_ALL task type support.
* feature: Chime: This SDK release adds support for UpdateAccount API to allow users to update their default license on Chime account.
* feature: CognitoIdentityServiceProvider: Amazon Cognito now supports targeted sign out through refresh token revocation
* feature: EC2: This release adds a new optional parameter connectivityType (public, private) for the CreateNatGateway API. Private NatGateway does not require customers to attach an InternetGateway to the VPC and can be used for communication with other VPCs and on-premise networks.
* feature: ManagedBlockchain: This release supports KMS customer-managed Customer Master Keys (CMKs) on member-specific Hyperledger Fabric resources.
* feature: RAM: AWS Resource Access Manager (RAM) is releasing new field isResourceTypeDefault in ListPermissions and GetPermission response, and adding permissionArn parameter to GetResourceShare request to filter by permission attached
* feature: Redshift: Added InvalidClusterStateFault to the ModifyAquaConfiguration API, thrown when calling the API on a non available cluster.
* feature: SageMaker: Using SageMaker Edge Manager with AWS IoT Greengrass v2 simplifies accessing, maintaining, and deploying models to your devices. You can now create deployable IoT Greengrass components during edge packaging jobs. You can choose to create a device fleet with or without creating an AWS IoT role alias.
* feature: SageMakerFeatureStoreRuntime: Release BatchGetRecord API for AWS SageMaker Feature Store Runtime.

## 2.925.0
* feature: Kendra: AWS Kendra now supports checking document status.
* feature: PersonalizeEvents: Support for unstructured text inputs in the items dataset to to automatically extract key information from product/content description as an input when creating solution versions.
* feature: Proton: This is the initial SDK release for AWS Proton

## 2.924.0
* feature: FSx: This release adds support for auditing end-user access to files, folders, and file shares using Windows event logs, enabling customers to meet their security and compliance needs.
* feature: Macie2: This release of the Amazon Macie API introduces stricter validation of S3 object criteria for classification jobs.
* feature: ServiceCatalog: increase max pagesize for List/Search apis

## 2.923.0
* feature: EKS: Added updateConfig option that allows customers to control upgrade velocity in Managed Node Group.
* feature: Glue: Add SampleSize variable to S3Target to enable s3-sampling feature through API.
* feature: Personalize: Update regex validation in kmsKeyArn and s3 path API parameters for AWS Personalize APIs
* feature: SageMaker: AWS SageMaker - Releasing new APIs related to Callback steps in model building pipelines. Adds experiment integration to model building pipelines.

## 2.922.0
* feature: MediaLive: Add support for automatically setting the H.264 adaptive quantization and GOP B-frame fields.
* feature: PI: The new GetDimensionKeyDetails action retrieves the attributes of the specified dimension group for a DB instance or data source.

## 2.921.0
* feature: ForecastService: Added optional field AutoMLOverrideStrategy to CreatePredictor API that allows users to customize AutoML strategy. If provided in CreatePredictor request, this field is visible in DescribePredictor and GetAccuracyMetrics responses.
* feature: S3: S3 Inventory now supports Bucket Key Status
* feature: S3Control: Amazon S3 Batch Operations now supports S3 Bucket Keys.

## 2.920.0
* feature: AutoScaling: You can now launch EC2 instances with GP3 volumes when using Auto Scaling groups with Launch Configurations
* feature: Braket: Introduction of a RETIRED status for devices.
* feature: DocDB: This SDK release adds support for DocDB global clusters.

## 2.919.0
* feature: EC2: Added idempotency to CreateNetworkInterface using the ClientToken parameter.
* feature: IoTWireless: Added six new public customer logging APIs to allow customers to set/get/reset log levels at resource type and resource id level. The log level set from the APIs will be used to filter log messages that can be emitted to CloudWatch in customer accounts.
* feature: Polly: Amazon Polly adds new Canadian French voice - Gabrielle. Gabrielle is available as Neural voice only.
* feature: SNS: This release adds SMS sandbox in Amazon SNS and the ability to view all configured origination numbers. The SMS sandbox provides a safe environment for sending SMS messages, without risking your reputation as an SMS sender.
* feature: ServiceDiscovery: Bugfixes - The DiscoverInstances API operation now provides an option to return all instances for health-checked services when there are no healthy instances available.

## 2.918.0
* feature: DataSync: Added SecurityDescriptorCopyFlags option that allows for control of which components of SMB security descriptors are copied from source to destination objects.
* feature: Location: Adds support for calculation of routes, resource tagging and customer provided KMS keys.
* feature: LookoutMetrics: Allowing dot(.) character in table name for RDS and Redshift as source connector.

## 2.917.0
* feature: DeviceFarm: Introduces support for using our desktop testing service with applications hosted within your Virtual Private Cloud (VPC).
* feature: FSx: This release adds LZ4 data compression support to FSx for Lustre to reduce storage consumption of both file system storage and file system backups.
* feature: IoTEvents: Releasing new APIs for AWS IoT Events Alarms
* feature: IoTEventsData: Releasing new APIs for AWS IoT Events Alarms
* feature: IoTSiteWise: IoT SiteWise Monitor Portal API updates to add alarms feature configuration.
* feature: Kendra: Amazon Kendra now suggests popular queries in order to help guide query typing and help overall accuracy.

## 2.916.0
* feature: EC2: This release removes resource ids and tagging support for VPC security group rules.

## 2.915.0
* feature: ACMPCA: This release enables customers to store CRLs in S3 buckets with Block Public Access enabled. The release adds the S3ObjectAcl parameter to the CreateCertificateAuthority and UpdateCertificateAuthority APIs to allow customers to choose whether their CRL will be publicly available.
* feature: EC2: This release adds resource ids and tagging support for VPC security group rules.
* feature: ECS: The release adds support for registering External instances to your Amazon ECS clusters.
* feature: MWAA: Adds scheduler count selection for Environments using Airflow version 2.0.2 or later.
* feature: Outposts: Add ConflictException to DeleteOutpost, CreateOutpost
* feature: QLDB: Support STANDARD permissions mode in CreateLedger and DescribeLedger. Add UpdateLedgerPermissionsMode to update permissions mode on existing ledgers.

## 2.914.0
* feature: Iot: This release includes support for a new feature: Job templates for AWS IoT Device Management Jobs. The release includes job templates as a new resource and APIs for managing job templates.
* feature: Transfer: AWS Transfer Family customers can now use AWS Managed Active Directory or AD Connector to authenticate their end users, enabling seamless migration of file transfer workflows that rely on AD authentication, without changing end users' credentials or needing a custom authorizer.
* feature: WorkSpaces: Adds support for Linux device types in WorkspaceAccessProperties

## 2.913.0
* feature: CloudWatchLogs: This release provides dimensions and unit support for metric filters.
* feature: ComputeOptimizer: Adds support for 1) additional instance types, 2) additional instance metrics, 3) finding reasons for instance recommendations, and 4) platform differences between a current instance and a recommended instance type.
* feature: CostExplorer: Introduced FindingReasonCodes, PlatformDifferences, DiskResourceUtilization and NetworkResourceUtilization to GetRightsizingRecommendation action
* feature: EC2: This release adds support for creating and managing EC2 On-Demand Capacity Reservations on Outposts.
* feature: QuickSight: Add new parameters on RegisterUser and UpdateUser APIs to assign or update external ID associated to QuickSight users federated through web identity.

## 2.912.0
* feature: EFS: EFS now supports account preferences. Utilizing the new capability, users can customize some aspects of their experience using EFS APIs and the EFS Console. The first preference clients are able to set is whether to start using longer File System and Mount Target IDs before EFS migrates to such IDs.
* feature: ForecastService: Updated attribute statistics in DescribeDatasetImportJob response to support Long values

## 2.911.0
* feature: LexModelsV2: Customers can now use resource-based policies to control access to their Lex V2 bots. This release adds APIs to attach and manage permissions for a bot or a bot alias. For details, see: https://docs.aws.amazon.com/lexv2/latest/dg/security_iam_service-with-iam.html
* feature: Personalize: Added new API to stop a solution version creation that is pending or in progress for Amazon Personalize
* feature: QuickSight: Add ARN based Row Level Security support to CreateDataSet/UpdateDataSet APIs.

## 2.910.0
* feature: AutoScaling: With this release, customers can easily use Predictive Scaling as a policy directly through Amazon EC2 Auto Scaling configurations to proactively scale their applications ahead of predicted demand.
* feature: EKS: Update the EKS AddonActive waiter.
* feature: IAM: Add pagination to ListUserTags operation
* feature: KinesisAnalyticsV2: Kinesis Data Analytics now allows rapid iteration on Apache Flink stream processing through the Kinesis Data Analytics Studio feature.
* feature: Rekognition: Amazon Rekognition Custom Labels adds support for customer managed encryption, using AWS Key Management Service, of image files copied into the service and files written back to the customer.

## 2.909.0
* feature: AppRunner: AWS App Runner is a service that provides a fast, simple, and cost-effective way to deploy from source code or a container image directly to a scalable and secure web application in the AWS Cloud.
* feature: ComputeOptimizer: This release enables compute optimizer to support exporting  recommendations to Amazon S3 for EBS volumes and Lambda Functions.
* feature: LexModelsV2: This release adds support for exporting and importing Lex V2 bots and bot locales. It also adds validations to enforce minimum number of tags on Lex V2 resources. For details, see https://docs.aws.amazon.com/lexv2/latest/dg/importing-exporting.html
* feature: LicenseManager: AWS License Manager now supports periodic report generation.
* feature: Personalize: Amazon Personalize now supports the ability to optimize a solution for a custom objective in addition to maximizing relevance.

## 2.908.0
* feature: ApplicationCostProfiler: APIs for AWS Application Cost Profiler.
* feature: CORS: Set the CORS support flag for Athena  to Athena client
* feature: IotDeviceAdvisor: AWS IoT Core Device Advisor is fully managed test capability for IoT devices. Device manufacturers can use Device Advisor to test their IoT devices for reliable and secure connectivity with AWS IoT.
* feature: MediaConnect: MediaConnect now supports JPEG XS for AWS Cloud Digital Interface (AWS CDI) uncompressed workflows, allowing you to establish a bridge between your on-premises live video network and the AWS Cloud.
* feature: Neptune: Neptune support for CopyTagsToSnapshots

## 2.907.0
* feature: CloudWatchEvents: Update InputTransformer variable limit from 10 to 100 variables.
* feature: ES: Adds support for cold storage.
* feature: EventBridge: Update InputTransformer variable limit from 10 to 100 variables.
* feature: Macie2: This release of the Amazon Macie API adds support for defining run-time, S3 bucket criteria for classification jobs. It also adds resources for querying data about AWS resources that Macie monitors.
* feature: TranscribeService: Transcribe Medical now supports identification of PHI entities within transcripts

## 2.906.0
* feature: EC2: High Memory virtual instances are powered by Intel Sky Lake CPUs and offer up to 12TB of memory.

## 2.905.0
* bugfix: retry: Retry http request on ECONNRESET error
* feature: SSMContacts: AWS Systems Manager Incident Manager enables faster resolution of critical application availability and performance issues, management of contacts and post incident analysis
* feature: SSMIncidents: AWS Systems Manager Incident Manager enables faster resolution of critical application availability and performance issues, management of contacts and post-incident analysis

## 2.904.0
* feature: ConfigService: Adds paginator to multiple APIs: By default, the paginator allows user to iterate over the results and allows the CLI to return up to 1000 results.
* feature: EKS: This release updates create-nodegroup and update-nodegroup-config APIs for adding/updating taints on managed nodegroups.
* feature: IoTWireless: Add three new optional fields to support filtering and configurable sub-band in WirelessGateway APIs. The filtering is for all the RF region supported. The sub-band configuration is only applicable to LoRa gateways of US915 or AU915 RF region.
* feature: KinesisAnalyticsV2: Amazon Kinesis Analytics now supports ListApplicationVersions and DescribeApplicationVersion API for Apache Flink applications
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for Kantar SNAP File Audio Watermarking with a Kantar Watermarking account, and Display Definition Segment(DDS) segment data controls for DVB-Sub caption outputs.
* feature: SSM: This release adds new APIs to associate, disassociate and list related items in SSM OpsCenter; and this release adds DisplayName as a version-level attribute for SSM Documents and introduces two new document types: ProblemAnalysis, ProblemAnalysisTemplate.

## 2.903.0
* bugfix: changelog: switch replaceAll with replace in change-creator
* feature: Connect: Adds tagging support for Connect APIs CreateIntegrationAssociation and CreateUseCase.
* feature: LakeFormation: This release adds Tag Based Access Control to AWS Lake Formation service
* feature: LookoutMetrics: Enforcing UUID style for parameters that are already in UUID format today. Documentation specifying eventual consistency of lookoutmetrics resources.

## 2.902.0
* bugfix: EndpointCache: Only delete endpoint which has expired in EndpointCache
* feature: Kafka: IAM Access Control for Amazon MSK enables you to create clusters that use IAM to authenticate clients and to allow or deny Apache Kafka actions for those clients.
* feature: SSM: SSM feature release - ChangeCalendar integration with StateManager.
* feature: ServiceDiscovery: Bugfix: Improved input validation for RegisterInstance action, InstanceId field
* feature: Snowball: AWS Snow Family adds APIs for ordering and managing Snow jobs with long term pricing

## 2.901.0
* feature: AuditManager: This release updates the CreateAssessmentFrameworkControlSet and UpdateAssessmentFrameworkControlSet API data types. For both of these data types, the control set name is now a required attribute.
* feature: KinesisAnalyticsV2: Amazon Kinesis Analytics now supports RollbackApplication for Apache Flink applications to revert the application to the previous running version
* feature: SageMaker: Amazon SageMaker Autopilot now provides the ability to automatically deploy the best model to an endpoint

## 2.900.0
* feature: ACMPCA: This release adds the KeyStorageSecurityStandard parameter to the CreateCertificateAuthority API to allow customers to mandate a security standard to which the CA key will be stored within.
* feature: Chime: This release adds the ability to search for and order international phone numbers for Amazon Chime SIP media applications.
* feature: DevOpsGuru: Added GetCostEstimation and StartCostEstimation to get the monthly resource usage cost and added ability to view resource health by AWS service name and to search insights be AWS service name.
* feature: SageMaker: Enable retrying Training and Tuning Jobs that fail with InternalServerError by setting RetryStrategy.

## 2.899.0
* feature: Chime: Added new BatchCreateChannelMembership API to support multiple membership creation for channels
* feature: Finspace: This is the initial SDK release for the management APIs for Amazon FinSpace. Amazon FinSpace is a data management and analytics service for the financial services industry (FSI).
* feature: Finspacedata: This is the initial SDK release for the data APIs for Amazon FinSpace. Amazon FinSpace is a data management and analytics application for the financial services industry (FSI).
* feature: SecurityHub: Updated ASFF to add the following new resource details objects: AwsEc2NetworkAcl, AwsEc2Subnet, and AwsElasticBeanstalkEnvironment.

## 2.898.0
* feature: Chime: Added new BatchCreateChannelMembership API to support multiple membership creation for channels
* feature: Finspace: This is the initial SDK release for the management APIs for Amazon FinSpace. Amazon FinSpace is a data management and analytics service for the financial services industry (FSI).
* feature: Finspacedata: This is the initial SDK release for the data APIs for Amazon FinSpace. Amazon FinSpace is a data management and analytics application for the financial services industry (FSI).
* feature: SecurityHub: Updated ASFF to add the following new resource details objects: AwsEc2NetworkAcl, AwsEc2Subnet, and AwsElasticBeanstalkEnvironment.

## 2.897.0
* feature: CloudFront: CloudFront now supports CloudFront Functions, a native feature of CloudFront that enables you to write lightweight functions in JavaScript for high-scale, latency-sensitive CDN customizations.
* feature: CustomerProfiles: This release introduces GetMatches and MergeProfiles APIs to fetch and merge duplicate profiles
* feature: ForecastService: Added new DeleteResourceTree operation that helps in deleting all the child resources of a given resource including the given resource.
* feature: MarketplaceCatalog: Allows user defined names for Changes in a ChangeSet. Users can use ChangeNames to reference properties in another Change within a ChangeSet. This feature allows users to make changes to an entity when the entity identifier is not yet available while constructing the StartChangeSet request.
* feature: RoboMaker: Adds ROS2 Foxy as a supported Robot Software Suite Version and Gazebo 11 as a supported Simulation Software Suite Version

## 2.896.0
* bugfix: Serializer: XML entity encoding for carriage return, line feed, next line, and line separator characters
* feature: Chime: Increase AppInstanceUserId length to 64 characters
* feature: ECS: Add support for EphemeralStorage on TaskDefinition and TaskOverride
* feature: Macie2: The Amazon Macie API now provides S3 bucket metadata that indicates whether a bucket policy requires server-side encryption of objects when objects are uploaded to the bucket.

## 2.895.0
* feature: CloudFormation: Add CallAs parameter to GetTemplateSummary to enable use with StackSets delegated administrator integration
* feature: Connect: Updated max number of tags that can be attached from 200 to 50. MaxContacts is now an optional parameter for the UpdateQueueMaxContact API.
* feature: IoTSiteWise: AWS IoT SiteWise interpolation API will get interpolated values for an asset property per specified time interval during a period of time.
* feature: MediaPackageVod: MediaPackage now offers the option to place your Sequence Parameter Set (SPS), Picture Parameter Set (PPS), and Video Parameter Set (VPS) encoder metadata in every video segment instead of in the init fragment for DASH and CMAF endpoints.
* feature: Nimble: Amazon Nimble Studio is a virtual studio service that empowers visual effects, animation, and interactive content teams to create content securely within a scalable, private cloud service.

## 2.894.0
* feature: AuditManager: This release restricts using backslashes in control, assessment, and framework names. The controlSetName field of the UpdateAssessmentFrameworkControlSet API now allows strings without backslashes.
* feature: Node.js: Add postinstall script warning end-of-support for Node.js <10.x

## 2.893.0
* feature: CodeGuruReviewer: Include KMS Key Details in Repository Association APIs to enable usage of customer managed KMS Keys.
* feature: EC2: Adding support for Red Hat Enterprise Linux with HA for Reserved Instances.
* feature: EKS: This release updates existing Amazon EKS input validation so customers will see an InvalidParameterException instead of a ParamValidationError when they enter 0 for minSize and/or desiredSize. It also adds LaunchTemplate information to update responses and a new "CUSTOM" value for AMIType.
* feature: Glue: Adding Kafka Client Auth Related Parameters
* feature: IoTWireless: Add a new optional field MessageType to support Sidewalk devices in SendDataToWirelessDevice API
* feature: KinesisAnalyticsV2: Amazon Kinesis Data Analytics now supports custom application maintenance configuration using UpdateApplicationMaintenanceConfiguration API for Apache Flink applications. Customers will have visibility when their application is under maintenance status using 'MAINTENANCE' application status.
* feature: Personalize: Added support for exporting data imported into an Amazon Personalize dataset to a specified data source (Amazon S3 bucket).

## 2.892.0
* feature: MediaPackage: Add support for Widevine DRM on CMAF origin endpoints. Both Widevine and FairPlay DRMs can now be used simultaneously, with CBCS encryption.
* feature: SNS: Amazon SNS adds two new attributes, TemplateId and EntityId, for using sender IDs to send SMS messages to destinations in India.

## 2.891.0
* feature: ElastiCache: This release introduces log delivery of Redis slow log from Amazon ElastiCache.
* feature: ForecastService: This release adds EstimatedTimeRemaining minutes field to the DescribeDatasetImportJob, DescribePredictor, DescribeForecast API response which denotes the time remaining to complete the job IN_PROGRESS.
* feature: SecurityHub: Replaced the term "master" with "administrator". Added new actions to replace AcceptInvitation, GetMasterAccount, and DisassociateFromMasterAccount. In Member, replaced MasterId with AdministratorId.

## 2.890.0
* feature: Detective: Added parameters to track the data volume in bytes for a member account. Deprecated the existing parameters that tracked the volume as a percentage of the allowed volume for a behavior graph. Changes reflected in MemberDetails object.
* feature: GroundStation: Support new S3 Recording Config allowing customers to write downlink data directly to S3.
* feature: Kendra: Amazon Kendra now enables users to override index-level boosting configurations for each query.
* feature: Redshift: Add operations: AddPartner, DescribePartners, DeletePartner, and UpdatePartnerStatus to support tracking integration status with data partners.

## 2.889.0
* feature: CostExplorer: Adding support for Sagemaker savings plans in GetSavingsPlansPurchaseRecommendation API
* feature: SavingsPlans: Added support for Amazon SageMaker in Machine Learning Savings Plans

## 2.888.0
* feature: DMS: AWS DMS added support of TLS for Kafka endpoint. Added Describe endpoint setting API for DMS endpoints.

## 2.887.0
* feature: CodeStarconnections: This release adds tagging support for CodeStar Connections Host resources
* feature: ConfigService: Add exception for DeleteRemediationConfiguration and DescribeRemediationExecutionStatus
* feature: MediaConnect: For flows that use Listener protocols, you can now easily locate an output's outbound IP address for a private internet. Additionally, MediaConnect now supports the Waiters feature that makes it easier to poll for the status of a flow until it reaches its desired state.

## 2.886.0
* feature: ComprehendMedical: The InferICD10CM API now returns TIME_EXPRESSION entities that refer to medical conditions.
* feature: Redshift: Added support to enable AQUA in Amazon Redshift clusters.
* feature: STS: This release adds the SourceIdentity parameter that can be set when assuming a role.

## 2.885.0
* feature: CodeBuild: AWS CodeBuild now allows you to set the access permissions for build artifacts, project artifacts, and log files that are uploaded to an Amazon S3 bucket that is owned by another account.
* feature: FSx: Support for cross-region and cross-account backup copies

## 2.884.0
* feature: EC2: Add paginator support to DescribeStoreImageTasks and update documentation.
* feature: Redshift: Add support for case sensitive table level restore
* feature: Shield: CreateProtection now throws InvalidParameterException instead of InternalErrorException when system tags (tag with keys prefixed with "aws:") are passed in.

## 2.883.0
* bugfix: ManagedUpload: Use resolved credentials if customer supplies configured S3 Client
* feature: AppStream: This release provides support for image updates
* feature: AutoScaling: Amazon EC2 Auto Scaling announces Warm Pools that help applications to scale out faster by pre-initializing EC2 instances and save money by requiring fewer continuously running instances
* feature: LookoutEquipment: This release introduces support for Amazon Lookout for Equipment.
* feature: RoboMaker: This release allows RoboMaker customers to specify custom tools to run with their simulation job

## 2.882.0
* bugfix: Credentials: Do not require credentials file when loading region from config.
* feature: AccessAnalyzer: IAM Access Analyzer now analyzes your CloudTrail events to identify actions and services that have been used by an IAM entity (user or role) and generates an IAM policy that is based on that activity.
* feature: ElastiCache: This release adds tagging support for all AWS ElastiCache resources except Global Replication Groups.
* feature: IVS: This release adds support for the Auto-Record to S3 feature. Amazon IVS now enables you to save your live video to Amazon S3.
* feature: Mgn: Add new service - Application Migration Service.
* feature: StorageGateway: File Gateway APIs now support FSx for Windows as a cloud storage.

## 2.881.0
* bugfix: changelog/release: Sanitize type and category in next-release filename
* feature: EC2: This release adds support for storing EBS-backed AMIs in S3 and restoring them from S3 to enable cross-partition copying of AMIs
* feature: MediaLive: MediaLive VPC outputs update to include Availability Zones, Security groups, Elastic Network Interfaces, and Subnet Ids in channel response
* feature: SSM: Supports removing a label or labels from a parameter, enables ScheduledEndTime and ChangeDetails for StartChangeRequestExecution API, supports critical/security/other noncompliant count for patch API.

## 2.880.0
* feature: Appflow: Added destination properties for Zendesk.
* feature: AuditManager: AWS Audit Manager has updated the GetAssessment API operation to include a new response field called userRole. The userRole field indicates the role information and IAM ARN of the API caller.
* feature: MediaLive: MediaLive now support HTML5 Motion Graphics overlay

## 2.879.0
* bugfix: s3: handle 'continue' event only once
* feature: Imagebuilder: This release adds support for Block Device Mappings for container image builds, and adds distribution configuration support for EC2 launch templates in AMI builds.
* feature: MediaPackage: SPEKE v2 is an upgrade to the existing SPEKE API to support multiple encryption keys, based on an encryption contract selected by the customer.

## 2.878.0
* feature: EC2: VPC Flow Logs Service adds a new API, GetFlowLogsIntegrationTemplate, which generates CloudFormation templates for Athena. For more info, see https://docs.aws.amazon.com/console/vpc/flow-logs/athena
* feature: FMS: Added Firewall Manager policy support for AWS Route 53 Resolver DNS Firewall.
* feature: Kendra: AWS Kendra's ServiceNow data source now supports OAuth 2.0 authentication and knowledge article filtering via a ServiceNow query.
* feature: LexModelBuildingService: Lex now supports the ja-JP locale
* feature: LexRuntime: Amazon Lex now supports base64-encoded message and input transcript fields.
* feature: Lightsail: - This release adds support for state detail for Amazon Lightsail container services.
* feature: MediaConvert: MediaConvert now supports HLS ingest, sidecar WebVTT ingest, Teletext color & style passthrough to TTML subtitles, TTML to WebVTT subtitle conversion with style, & DRC profiles in AC3 audio.
* feature: Route53Resolver: Route 53 Resolver DNS Firewall is a firewall service that allows you to filter and regulate outbound DNS traffic for your VPCs.
* feature: WAFV2: Added support for ScopeDownStatement for ManagedRuleGroups, Labels, LabelMatchStatement, and LoggingFilter. For more information on these features, see the AWS WAF Developer Guide.

## 2.877.0
* bugfix: S3/S3Control: fix the issue that previously resolved S3 ARN incorrectly cached in S3/S3Control client
* feature: Batch: AWS Batch adds support for Amazon EFS File System
* feature: Cloud9: Add ImageId input parameter to CreateEnvironmentEC2 endpoint. New parameter enables creation of environments with different AMIs.
* feature: CloudFormation: 1. Added a new parameter "RegionConcurrencyType" in OperationPreferences. 2. Changed the name of "AccountUrl" to "AccountsUrl" in "DeploymentTargets" parameter.
* feature: CloudHSM: Minor documentation and link updates.
* feature: CognitoSync: Minor documentation updates and link updates.
* feature: Comprehend: Support for customer managed KMS encryption of Comprehend custom models
* feature: DataPipeline: Minor documentation updates and link updates.
* feature: Detective: Added the ability to assign tag values to Detective behavior graphs. Tag values can be used for attribute-based access control, and for cost allocation for billing.
* feature: DirectConnect: This release adds MACsec support to AWS Direct Connect
* feature: IoTWireless: Add Sidewalk support to APIs: GetWirelessDevice, ListWirelessDevices, GetWirelessDeviceStatistics. Add Gateway connection status in GetWirelessGatewayStatistics API.
* feature: Iot: Added ability to prefix search on attribute value for ListThings API.
* feature: MachineLearning: Minor documentation updates and link updates.
* feature: Pricing: Minor documentation and link updates.
* feature: Redshift: Enable customers to share access to their Redshift clusters from other VPCs (including VPCs from other accounts).
* feature: TranscribeService: Amazon Transcribe now supports creating custom language models in the following languages: British English (en-GB), Australian English (en-AU), Indian Hindi (hi-IN), and US Spanish (es-US).
* feature: WorkMail: This release adds support for mobile device access rules management in Amazon WorkMail.

## 2.876.0
* feature: CloudWatch: SDK update for new Metric Streams feature
* feature: ConfigService: Adding new APIs to support ConformancePack Compliance CI in Aggregators
* feature: DataBrew: This SDK release adds two new dataset features: 1) support for specifying a database connection as a dataset input 2) support for dynamic datasets that accept configurable parameters in S3 path.
* feature: EC2: ReplaceRootVolume feature enables customers to replace the EBS root volume of a running instance to a previously known state. Add support to grant account-level access to the EC2 serial console
* feature: EC2InstanceConnect: Adding support to push SSH keys to the EC2 serial console in order to allow an SSH connection to your Amazon EC2 instance's serial port.
* feature: FraudDetector: This release adds support for Batch Predictions in Amazon Fraud Detector.
* feature: Pinpoint: Added support for journey pause/resume, journey updatable import segment and journey quiet time wait.
* feature: SageMaker: Amazon SageMaker Autopilot now supports 1) feature importance reports for AutoML jobs and 2) PartialFailures for AutoML jobs
* feature: s3: update writeGetObjectResponse to validate with and hit s3-object-lambda endpoint

## 2.875.0
* feature: DocDB: This release adds support for Event Subscriptions to DocumentDB.
* feature: Glue: Allow Dots in Registry and Schema Names for CreateRegistry, CreateSchema; Fixed issue when duplicate keys are present and not returned as part of QuerySchemaVersionMetadata.
* feature: IAM: AWS Identity and Access Management GetAccessKeyLastUsed API will throw a custom error if customer public key is not found for access keys.
* feature: Location: Amazon Location added support for specifying pricing plan information on resources in alignment with our cost model.
* feature: WAFV2: Added custom request handling and custom response support in rule actions and default action; Added the option to inspect the web request body as parsed and filtered JSON.

## 2.874.0
* feature: CloudWatchEvents: Add support for SageMaker Model Builder Pipelines Targets to EventBridge
* feature: CustomerProfiles: This release adds an optional parameter named FlowDefinition in PutIntegrationRequest.
* feature: EventBridge: Add support for SageMaker Model Builder Pipelines Targets to EventBridge
* feature: IoTWireless: Support tag-on-create for WirelessDevice.
* feature: TranscribeService: Amazon Transcribe now supports tagging words that match your vocabulary filter for batch transcription.

## 2.873.0
* bugfix: Lookout Metrics: Update Lookout Metrics to set Content-Type header to be application/x-amz-json-1.1
* feature: LookoutMetrics: Allowing uppercase alphabets for RDS and Redshift database names.

## 2.872.0
* feature: AlexaForBusiness: Added support for enabling and disabling data retention in the CreateProfile and UpdateProfile APIs and retrieving the state of data retention for a profile in the GetProfile API.
* feature: LookoutMetrics: Amazon Lookout for Metrics is now generally available. You can use Lookout for Metrics to monitor your data for anomalies. For more information, see the Amazon Lookout for Metrics Developer Guide.
* feature: MediaLive: EML now supports handling HDR10 and HLG 2020 color space from a Link input.
* feature: Rekognition: "This release introduces AWS tagging support for Amazon Rekognition collections, stream processors, and Custom Label models."
* feature: SageMaker: This feature allows customer to specify the environment variables in their CreateTrainingJob requests.

## 2.871.0
* feature: EC2: maximumEfaInterfaces added to DescribeInstanceTypes API
* feature: Greengrass: Updated the parameters to make name required for CreateGroup API.
* feature: SSM: This release allows SSM Explorer customers to enable OpsData sources across their organization when creating a resource data sync.

## 2.870.0
* feature: CostExplorer: You can now create cost categories with inherited value rules and specify default values for any uncategorized costs.
* feature: Fis: Updated maximum allowed size of action parameter from 64 to 1024
* feature: GameLift: GameLift adds support for using event notifications to monitor game session placements. Specify an SNS topic or use CloudWatch Events to track activity for a game session queue.
* feature: Redshift: Removed APIs to control AQUA on clusters.

## 2.869.0
* feature: EC2: This release adds support for UEFI boot on selected AMD- and Intel-based EC2 instances.
* feature: Macie2: This release of the Amazon Macie API adds support for publishing sensitive data findings to AWS Security Hub and specifying which categories of findings to publish to Security Hub.
* feature: Redshift: Added support to enable AQUA in Amazon Redshift clusters.

## 2.868.0
* feature: EC2: X2gd instances are the next generation of memory-optimized instances powered by AWS-designed, Arm-based AWS Graviton2 processors.
* feature: SageMaker: Adding authentication support for pulling images stored in private Docker registries to build containers for real-time inference.

## 2.867.0
* feature: AutoScaling: Amazon EC2 Auto Scaling Instance Refresh now supports phased deployments.
* feature: Redshift: Add new fields for additional information about VPC endpoint for clusters with reallocation enabled, and a new field for total storage capacity for all clusters.
* feature: S3: S3 Object Lambda is a new S3 feature that enables users to apply their own custom code to process the output of a standard S3 GET request by automatically invoking a Lambda function with a GET request
* feature: S3Control: S3 Object Lambda is a new S3 feature that enables users to apply their own custom code to process the output of a standard S3 GET request by automatically invoking a Lambda function with a GET request
* feature: SecurityHub: New object for separate provider and customer values. New objects track S3 Public Access Block configuration and identify sensitive data. BatchImportFinding requests are limited to 100 findings.

## 2.866.0
* feature: Batch: Making serviceRole an optional parameter when creating a compute environment. If serviceRole is not provided then Service Linked Role will be created (or reused if it already exists).
* feature: SageMaker: Support new target device ml_eia2 in SageMaker CreateCompilationJob API

## 2.865.0
* feature: AccessAnalyzer: This release adds support for the ValidatePolicy API. IAM Access Analyzer is adding over 100 policy checks and actionable recommendations that help you validate your policies during authoring.
* feature: GameLift: GameLift expands to six new AWS Regions, adds support for multi-location fleets to streamline management of hosting resources, and lets you customize more of the game session placement process.
* feature: Lambda: Allow empty list for function response types
* feature: MWAA: This release adds UPDATE_FAILED and UNAVAILABLE MWAA environment states.
* feature: MediaConnect: This release adds support for the SRT-listener protocol on sources and outputs.
* feature: MediaTailor: MediaTailor channel assembly is a new manifest-only service that allows you to assemble linear streams using your existing VOD content.

## 2.864.0
* feature: CodeDeploy: AWS CodeDeploy can now detect instances running an outdated revision of your application and automatically update them with the latest revision.
* feature: ECS: This is for ecs exec feature release which includes two new APIs - execute-command and update-cluster and an AWS CLI customization for execute-command API
* feature: EMR: Amazon EMR customers can now specify Resource Group to target Capacity Reservations in their EMR clusters with instance fleets using allocation strategy.
* feature: Fis: Initial release of AWS Fault Injection Simulator, a managed service that enables you to perform fault injection experiments on your AWS workloads

## 2.863.0
* feature: CUR: - Added optional billingViewArn field for OSG.
* feature: MediaTailor: MediaTailor channel assembly is a new manifest-only service that allows you to assemble linear streams using your existing VOD content.
* feature: WorkSpaces: Adds API support for WorkSpaces bundle management operations.

## 2.862.0
* feature: Comprehend: ContainsPiiEntities API analyzes the input text for the presence of personally identifiable information(PII) and returns the labels of identified PII entity types such as name, address etc.
* feature: MediaLive: MediaLive supports the ability to apply a canned ACL to output sent to an AWS S3 bucket; supports ability to specify position for EBU-TT and TTML output captions converted from Teletext source.

## 2.861.0
* feature: AccessAnalyzer: This release adds support to preview IAM Access Analyzer findings for a resource before deploying resource permission changes.
* feature: Backup: Added support for enabling continuous backups.
* feature: S3: Adding ID element to the CORSRule schema
* feature: SSM: Systems Manager support for tagging OpsMetadata.

## 2.860.0
* feature: AutoScaling: EC2 Auto Scaling now supports setting a local time zone for cron expressions in scheduled actions, removing the need to adjust for Daylight Saving Time (DST)
* feature: CodeGuruProfiler: Update documentation to include Python. Add ConflictException for DeleteProfilingGroup. Add FrameMetricValue.
* feature: EFS: AWS EFS is introducing one-zone file systems.
* feature: IoTWireless: Add max value to Seq in SendDataToWirelessDevice API"
* feature: RDS: This release adds support for Amazon RDS Proxy endpoints.

## 2.859.0
* feature: EMR: Amazon EMR customers can now specify how EC2 On-Demand Capacity Reservations are used in their EMR clusters with instance fleets using allocation strategy.
* feature: KinesisVideoArchivedMedia: Increase the maximum HLS and MPEG-DASH manifest size from 1,000 to 5,000 fragments.
* feature: Lambda: Documentation updates for Lambda. Constraint updates to AddLayerVersionPermission's Action and OrganizationId parameters, and AddPermission's Principal and SourceAccount parameters.

## 2.858.0
* feature: Athena: Adds APIs to create, list, update, and delete prepared SQL statements that have optional placeholder parameters. A prepared statement can use different values for these parameters each time it is run.
* feature: CodePipeline: Updated the parameters to make actionType required for UpdateActionType
* feature: EC2: Expands EC2/Spot Fleet capacity-optimized allocation strategy to allow users to prioritize instance pools. Fleet attempts to fulfill priorities on a best-effort basis but optimizes for capacity first.
* feature: LicenseManager: License Manager Automated Discovery now supports Exclusion Filters.
* feature: MediaLive: Medialive now supports the ability to transfer AWS Elemental Link devices to another region.
* feature: NetworkFirewall: Added a new UpdateToken output field to the PerObjectStatus as part of firewall sync state. This is added to track which version of the object the firewall is in sync or pending synchronization.
* feature: Shield: Add support for tagging of Shield protection and protection group resources.

## 2.857.0
* feature: CloudWatchEvents: Introducing support for EventBridge Api Destinations - any HTTP APIs as Targets, with managed authorization via EventBridge Connections.
* feature: EventBridge: Introducing support for EventBridge Api Destinations - any HTTP APIs as Targets, with managed authorization via EventBridge Connections.
* feature: MWAA: This release introduces a new MinWorker parameter to the CreateEnvironment and UpdateEnvironment APIs. MinWorker allows the users to set a minimum worker count for worker auto-scaling operations.
* feature: SageMaker: This release adds the ResolvedOutputS3Uri to the DescribeFeatureGroup API to indicate the S3 prefix where offline data is stored in a feature group
* feature: ServiceDiscovery: Supports creating API-only services under DNS namespace.  Add namespace syntax validation.

## 2.856.0
* feature: ACM: Adds 2 new APIs to add and retrieve account configuration in AWS Certificate Manager.
* feature: CloudWatchEvents: Adds TraceHeader to PutEventsRequestEntry to support AWS X-Ray trace-ids on events generated using the PutEvents operation.
* feature: CodeBuild: AWS CodeBuild now supports Session Manager debugging for batch builds.
* feature: ES: AWS ElasticSearch Feature : Support for adding tags in elastic search domain during domain creation
* feature: ForecastService: Added new StopResource operation that stops Amazon Forecast resource jobs that are in progress.
* feature: SecretsManager: Added support for multi-Region secrets APIs ReplicateSecretToRegions, RemoveRegionsFromReplication, and StopReplicationToReplica
* feature: WellArchitected: This release supports tagging on AWS Well-Architected workloads.

## 2.855.0
* feature: DataSync: Additional API Support to update NFS/SMB/ObjectStorage locations
* feature: EventBridge: Adds TraceHeader to PutEventsRequestEntry to support AWS X-Ray trace-ids on events generated using the PutEvents operation.
* feature: IoTWireless: Add ARN & Tags for PartnerAccount related APIs and WirelessGatewayTaskDefinition related APIs

## 2.854.0
* feature: AlexaForBusiness: Added support for optional tags in CreateAddressBook, CreateConferenceProvider, CreateContact, CreateGatewayGroup, CreateNetworkProfile and RegisterAVSDevice APIs.
* feature: CodePipeline: Added a new field to the ListPipelines API to allow maximum search results of 1000
* feature: EKS: Adding new error code AdmissionRequestDenied for Addons in EKS
* feature: SSM: Add Support for Patch Manger Baseline Override parameter.

## 2.853.0
* bugfix: s3: Bugfixing the s3 arn endpoint parser
* feature: EKS: Amazon EKS now supports adding KMS envelope encryption to existing clusters to enhance security for secrets
* feature: EMR: Added UpdateStudio API that allows updating a few attributes of an EMR Studio.
* feature: S3: Add RequestPayer to GetObjectTagging and PutObjectTagging.
* feature: SSOAdmin: Relax constraint on List* API pagination tokens to include underscore character

## 2.852.0
* feature: DataBrew: This SDK release adds two new dataset features: 1) support for specifying the file format for a dataset, and 2) support for specifying whether the first row of a CSV or Excel file contains a header.
* feature: Detective: Changed "master account" to "administrator account." A new AdministratorId field replaces the deprecated MasterId field. Added an option to disable email notifications for member account invitations.
* feature: Imagebuilder: This release introduces a new API (ListImagePackages) for listing packages installed on an image, and adds support for GP3 volume types, and for specifying a time zone in an image pipeline schedule.
* feature: Transfer: Corrected the upper limit for TestIdentityProvider input lengths to 1024 characters

## 2.851.0
* feature: Appflow: # Adding 'Amazon Honeycode' , 'Amazon Lookout for Metrics' and  'Amazon Connect Customer Profiles' as Destinations.
* feature: ECRPUBLIC: This release adds support for AWS tags on Amazon ECR Public repositories.
* feature: ES: Amazon Elasticsearch Service now supports Auto-Tune, which monitors performance metrics and automatically optimizes domains
* feature: MediaPackageVod: AWS Elemental MediaPackage provides access logs that capture detailed information about requests sent to a customer's MediaPackage VOD packaging group.

## 2.850.0
* feature: AutoScaling: Adds a new optional IncludeDeletedGroups parameter to the DescribeScalingActivities API.
* feature: Glue: Updating the page size for Glue catalog getter APIs.
* feature: IoTEvents: This release adds an Analyze feature to AWS IoT Events that lets customers analyze their detector models for runtime issues.
* feature: Pinpoint: Enables AWS Pinpoint customers to use Entity Id and Template Id when sending SMS message. These parameters can be obtained from the regulatory body of the country where you are trying to send the SMS.
* feature: RedshiftData: This release adds an additional parameter 'ConnectedDatabase' into ListSchemasRequest, ListTablesRequest and DescribeTableRequest to support the metadata sharing across databases.

## 2.849.0
* feature: SageMaker: Amazon SageMaker now supports core dump for SageMaker Endpoints and direct invocation of a single container in a SageMaker Endpoint that hosts multiple containers.
* feature: SageMakerRuntime: SageMaker Runtime now supports a new TargetContainerHostname header to invoke a model in a specific container if the endpoint hosts multiple containers and is configured to use direct invocation.

## 2.848.0
* feature: RDS: Added awsBackupRecoveryPointArn in ModifyDBInstanceRequest and in the response of ModifyDBInstance.

## 2.847.0
* feature: CloudFormation: Adding the 'callAs' parameter to all CloudFormation StackSets APIs except getTemplateSummary to support creating and managing service-managed StackSets with AWS Organizations Delegated Administrators
* feature: CodeBuild: AWS CodeBuild now allows you to specify a separate bucket owner as part of the S3 destination in a report group.
* feature: SageMaker: This release adds expires-in-seconds parameter to the CreatePresignedDomainUrl API for support of a configurable TTL.

## 2.846.0
* feature: ConfigService: Added INSUFFICIENT_DATA in ConformancePackComplianceType.
* feature: LookoutVision: This release for Amazon Lookout for Vision includes documentation updates and a correction to the Status field returned in the response from StartModel and StopModel.

## 2.845.0
* feature: CodeBuild: This release provides per-project limits for the number of concurrent builds
* feature: DevOpsGuru: Amazon DevOps Guru is GA ready. This API update added a describeFeedback Api allows users to view submitted insight feedback. The release date is 02/16/2021
* feature: LexRuntimeV2: Enable CORS

## 2.844.0
* feature: ConfigService: Added option to provide KMS key to AWS Config DeliveryChannel
* feature: KinesisVideoArchivedMedia: The ListFragments and GetMediaForFragmentList APIs now support StreamName or StreamARN as input parameters.
* feature: MediaLive: AWS MediaLive now supports Automatic-Input-Failover for CDI Inputs.
* feature: MediaTailor: MediaTailor now supports specifying aliases for dynamic variables. This allows use cases such as binding multiple origin domains to a single MediaTailor playback configuration.
* feature: Pinpoint: Lets customers use origination number when specifying SMS message configuration for Campaigns and Journeys.
* feature: RedshiftData: This release enables fine grant access control in ListStatements, GetStatementResult, CancelStatement and DescribeStatement.
* feature: WorkMailMessageFlow: This release allows customers to update email messages as they flow in and out of Amazon WorkMail

## 2.843.0
* feature: AppSync: Approve release for appsync local on pipeline resolver
* feature: CodePipeline: The release provides new GetActionType and UpdateActionType APIs for viewing and editing action types in CodePipeline.
* feature: Detective: The API definition now indicates that the format for timestamps is an ISO 8601 date-time string
* feature: EKS: Amazon EKS now supports OpenId Connect (OIDC) compatible identity providers as a user authentication option
* feature: IAM: AWS Identity and Access Management now supports tagging for the following resources: customer managed policies, identity providers, instance profiles, server certificates, and virtual MFA devices.
* feature: Macie2: This release of the Amazon Macie API replaces the term master account with the term administrator account, including deprecating APIs that use the previous term and adding APIs that use the new term.
* feature: PersonalizeEvents: Increased maximum char size of PutUsers and PutItems properties.
* feature: RDS: EngineMode in the response of DescribeDBClusterSnapshots. SupportedEngineModes, SupportsParallelQuery and SupportsGlobalDatabases in ValidUpgradeTarget of DBEngineVersions in DescribeDBEngineVersions.
* feature: WAFV2: Added the option to inspect the web request body as parsed and filtered JSON (new FieldToMatch type JsonBody), in addition to the existing option to inspect the web request body as plain text.

## 2.842.0
* feature: DataBrew: This release adds support for profile job sampling, which determines the number of rows on which the profile job will be executed.
* feature: RDS: Adding support for RDS Aurora Global Database Failover
* feature: RDS: Support cross-region copying in DocDB and Neptune

## 2.841.0
* feature: GameLift: GameLift FleetIQ users can now use AMD instance families in supported Regions. In addition, FlexMatch matchmaking notification now supports SNS FIFO topics.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for WMA audio only ingest, SMPTE-TT text and image caption ingest, and MPEG-2 video in MXF OP1a outputs.
* feature: QLDBSession: This release adds CapacityExceededException to the AWS QLDBSession API.
* feature: QuickSight: QuickSight now supports Python's paginators for Exploration APIs.
* feature: SageMaker: Add a new optional FrameworkVersion field to Sagemaker Neo CreateCompilationJob API

## 2.840.0
* feature: CloudTrail: ConflictException is now thrown when certain operations are called on resources before CloudTrail has time to load the resources. Two new exceptions have been added to the PutInsightSelectors API.
* feature: DataExchange: This release introduces the new ExportRevision job type, which allows for the export of an entire revision.
* feature: GlobalAccelerator: Global Accelerator now supports bringing your own IP addresses for custom routing accelerators
* feature: IVS: Fixed an issue where StreamStartTime could not be unmarshalled from response. Changed DeleteChannel and DeleteStreamKey response codes to 204.
* feature: IoTSiteWise: Recall CreatePresignedPortalUrl API
* feature: Macie2: This release of the Amazon Macie API adds support for specifying a time range in queries for usage data.

## 2.839.0
* feature: Organizations: Added support for a few additional exception codes for some AWS Organizations APIs.

## 2.838.0
* feature: Appflow: Adding schedule offset as an input for scheduled flows in CreateFlow API. Also, adding data pull start time and data pull end time for DescribeFlowExecutionRecords API response.
* feature: Athena: Adds the Athena ListEngineVersions action and the EngineVersion data type. ListEngineVersions returns the available Athena engine versions, including Auto, as a list of EngineVersion objects.
* feature: DLM: Provide support for EBS Local Snapshots on AWS Outpost in Data Lifecycle Manager (DLM).
* feature: EC2: AWS Outposts now supports EBS local snapshots on Outposts that allows customers to store snapshots of EBS volumes and AMIs locally on S3 on Outposts.
* feature: EMRcontainers: This release is to correct the timestamp format to ISO8601 for the date parameters in the describe and list API response objects of Job Run and Virtual Clusters.
* feature: QuickSight: API release for field folders feature.

## 2.837.0
* feature: Appflow: Adding schedule offset as an input for scheduled flows in CreateFlow API. Also, adding data pull start time and data pull end time for DescribeFlowExecutionRecords API response.
* feature: Athena: Adds the Athena ListEngineVersions action and the EngineVersion data type. ListEngineVersions returns the available Athena engine versions, including Auto, as a list of EngineVersion objects.
* feature: DLM: Provide support for EBS Local Snapshots on AWS Outpost in Data Lifecycle Manager (DLM).
* feature: EC2: AWS Outposts now supports EBS local snapshots on Outposts that allows customers to store snapshots of EBS volumes and AMIs locally on S3 on Outposts.
* feature: EMRcontainers: This release is to correct the timestamp format to ISO8601 for the date parameters in the describe and list API response objects of Job Run and Virtual Clusters.
* feature: QuickSight: API release for field folders feature.

## 2.836.0
* feature: AuditManager: This release adds AccessDeniedException to GetServicesInScope API.
* feature: DataBrew: This release adds the DescribeJobRun API to allow customers retrieve details of a given job run
* feature: EC2: EC2 Public IP now supports API for setting PTR records on Elastic IP address.
* feature: IoTSiteWise: Update AccessPolicy API input to support IAM role for IAM mode. Iam role is added as part of accessPolicyIdentity.
* feature: Lambda: Support for creating Lambda Functions using 'nodejs14.x'
* feature: SecurityHub: Added a ProductArn parameter to DescribeProducts. ProductArn is used to identify the integration to return details for.
* feature: WorkMail: Increased maximum length of ipRanges values for Access Control Rules from 10 to 1024.

## 2.835.0
* feature: AppMesh: App Mesh now supports mutual TLS with two-way peer authentication. You can specify client certificates, server-side TLS validation, and matching of Subject Alternative Names.
* feature: ApplicationAutoScaling: With this release, scheduled actions of Application Auto Scaling can be created in the local time zone and automatically adjusted according to daylight saving changes.
* feature: IoTWireless: Add enum value MqttTopic for Destination ExpressionType, add LoRaWANNetworkServerCertificateId for GetWirelessGatewayCertificate API
* feature: LookoutVision: This release includes the General Availability (GA) SDK for Amazon Lookout for Vision. New for GA is tagging support for Amazon Lookout for Vision models.
* feature: MediaLive: AWS Elemental MediaLive now supports Image Media Playlists on HLS outputs, version 0.4 (trick-mode).
* feature: RDSDataService: With the Data API, you can now use UUID and JSON data types as input to your database. Also with the Data API, you can now have a LONG type value returned from your database as a STRING value.
* feature: S3Control: Amazon S3 Batch Operations now supports Delete Object Tagging

## 2.834.0
* bugfix: Lex Models V2: Lex Models V2 service requires Content-Type header to be application/x-amz-json-1.1
* feature: Connect: Added API to manage queues or get hours of operation for a queue programmatically, which can be used to create new/update queues, or take actions when skills are outside of their hours of operation.
* feature: Macie2: This release of the Amazon Macie API adds support for using object prefixes to refine the scope of a classification job.
* feature: MediaLive: "AWS Elemental MediaLive now supports output to a private VPC. When this property is specified, the output will egress from a user specified VPC."

## 2.833.0
* feature: CloudWatch: Update to SDK to support label time zones in CloudWatch GetMetricData
* feature: DataBrew: This SDK release adds support for specifying a custom delimiter for input CSV datasets and for CSV job outputs.
* feature: ManagedBlockchain: This release supports tagging on Amazon Managed Blockchain resources.
* feature: RoboMaker: This release allows Robomaker customers to specify configuration for uploading logs and artifacts generated by their simulation jobs.

## 2.832.0
* feature: AccessAnalyzer: This release adds Secrets Manager secrets as a supported resource in IAM Access Analyzer to help you identify secrets that can be accessed from outside your account or AWS organization.
* feature: CustomerProfiles: This release makes Uri a required parameter in GetIntegrationRequest and DeleteIntegrationRequest.
* feature: ES: Amazon Elasticsearch Service adds support for node-to-node encryption and encryption at rest for existing domains running Elasticsearch version 6.7 and above
* feature: ElastiCache: Add support to pass ParameterGroup name as part updating Engine Version of Global Datastore.
* feature: SESV2: This release includes the ability to assign a configuration set to an email identity (a domain or email address), which allows the settings from the configuration set to be applied to the identity.

## 2.831.0
* feature: EC2: Introducing startDate field for CapacityReservation object for the date and time which the reservation started and adding reserved parameter for ModifyCapacityReservation.
* feature: LexModelsV2: This release adds support for Amazon Lex V2 APIs for model building.
* feature: LexRuntimeV2: Updates API to latest version.
* feature: Redshift: Update VPC endpoint field names.

## 2.830.0
* feature: Kafka: Amazon MSK has added a new API that allows you to update all the brokers in the cluster to the specified type.
* feature: ResourceGroupsTaggingAPI: This release adds a new parameter ResourceARNList to Resource Groups Tagging api GetResources api to allow customers retrieve tag data for specific resources.
* feature: SecurityHub: This release of ASFF adds a new Action object and a new resource details object - AwsSsmPatchCompliance. It also adds several new attributes for the AwsEc2NetworkInterface resource type.

## 2.829.0
* feature: ACMPCA: ACM Private CA is launching additional certificate templates and API parameters. This allows customers to create custom certificates for their identity and secure communication use cases.
* feature: Chime: Add support for specifying ChimeBearer header as part of the request for Amazon Chime SDK messaging APIs. Documentation updates.
* feature: ECS: This release adds support to include task definition metadata information such as registeredAt, deregisteredAt, registeredBy as part of DescribeTaskDefinition API.

## 2.828.0
* feature: CognitoIdentity: Add Attributes For Access Control support for Amazon Cognito Identity Pools to facilitate access to AWS resources based on attributes from social and corporate identity providers
* feature: Pinpoint: Customers can create segments using 5 new filters. Filters can check for the presence of a substring in attributes and can perform time-based comparisons formatted as ISO_INSTANT datetimes.
* feature: S3Control: Amazon S3 Batch Operations now supports restoring objects from the S3 Intelligent-Tiering Archive Access and Deep Archive Access tiers.
* feature: SageMaker: This feature allows customers to enable/disable model caching on Multi-Model endpoints.

## 2.827.0
* feature: FraudDetector: Added support for cancelling a model version that is TRAINING_IN_PROGRESS.

## 2.826.0
* feature: AppStream: Adds support for the Smart Card Redirection feature
* feature: AuditManager: This release introduces tag support for assessment frameworks. You can now add, remove, and get tags from existing frameworks, and specify the tags to apply when creating a custom framework.
* feature: Lightsail: This release adds IPv6 support for Amazon Lightsail instances, container services, CDN distributions, and load balancers.
* feature: SSM: AWS Systems Manager adds pagination support for DescribeDocumentPermission API

## 2.825.0
* feature: KMS: Adds support for filtering grants by grant ID and grantee principal in ListGrants requests to AWS KMS.
* feature: RDS: This releases adds support for Major Version Upgrades on Aurora MySQL Global Clusters. Customers will be able to upgrade their whole Aurora MySQL Global Cluster to a new major engine version.

## 2.824.0
* feature: CodePipeline: Adding cancelled status and summary for executions aborted by pipeline updates.
* feature: DevOpsGuru: Add resourceHours field in GetAccountHealth API to show total number of resource hours AWS Dev Ops Guru has done work for in the last hour.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for I-Frame-only HLS manifest generation in CMAF outputs.

## 2.823.0
* feature: Transfer: This release adds support for Amazon EFS, so customers can transfer files over SFTP, FTPS and FTP in and out of Amazon S3 as well as Amazon EFS.

## 2.822.0
* feature: CostExplorer: - ### Features    - Add new GetCostcategories API - Support filter for GetDimensions, GetTags and GetCostcategories api - Support sortBy metrics for GetDimensions, GetTags and GetCostcategories api
* feature: ParamValidator: Updated validateStructure to accept null and undefined values for params not described in the input shape

## 2.821.0
* feature: CloudSearch: This release adds support for new Amazon CloudSearch instances.
* feature: HealthLake: Amazon HealthLake now supports exporting data from FHIR Data Stores in Preview.

## 2.820.0
* feature: ServiceCatalog: Enhanced Service Catalog DescribeProvisioningParameters API to return new parameter constraints, i.e., MinLength, MaxLength, MinValue, MaxValue, ConstraintDescription and AllowedPattern

## 2.819.0
* feature: ACMPCA: This release adds a new parameter "CsrExtensions" in the "CertificateAuthorityConfiguration" data structure, which allows customers to add the addition of KU and SIA into the CA CSR.
* feature: ApiGatewayV2: Amazon API Gateway now supports data mapping for HTTP APIs which allows customers to modify HTTP Request before sending it to their integration and HTTP Response before sending it to the invoker.

## 2.818.0
* feature: CloudFront: Amazon CloudFront has deprecated the CreateStreamingDistribution and CreateStreamingDistributionWithTags APIs as part of discontinuing support for Real-Time Messaging Protocol (RTMP) distributions.

## 2.817.0
* feature: ComputeOptimizer: This release enables AWS Compute Optimizer to analyze and generate optimization recommendations for lambda functions.
* feature: DMS: AWS DMS launches support for AWS Secrets Manager to manage Oracle ASM Database credentials
* feature: ResourceGroups: Add operation `PutGroupConfiguration`. Support dedicated hosts and add `Pending` in operations `Un/GroupResources`. Add `Resources` in `ListGroupResources` and deprecate `ResourceIdentifiers`.

## 2.816.0
* feature: Connect: This release adds support for quick connects. For details, see the Release Notes in the Amazon Connect Administrator Guide.
* feature: CostExplorer: This release adds additional metadata that may be applicable to the Rightsizing Recommendations.
* feature: Glue: AWS Glue Find Matches machine learning transforms now support column importance scores.
* feature: IoTWireless: Adding the ability to use Fingerprint in GetPartnerAccount and ListPartnerAccounts API responses to protect sensitive customer account information.
* feature: RDS: Adds customer-owned IP address (CoIP) support to Amazon RDS on AWS Outposts.
* feature: SSM: SSM Maintenance Window support for registering/updating maintenance window tasks without targets.

## 2.815.0
* feature: ConfigService: AWS Config adds support to save advanced queries. New API operations - GetStoredQuery, PutStoredQuery, ListStoredQueries, DeleteStoredQuery
* feature: ConnectParticipant: This release adds three new APIs: StartAttachmentUpload, CompleteAttachmentUpload, and GetAttachment. For Amazon Connect Chat, you can use these APIs to share files in chat conversations.
* feature: DMS: AWS DMS launches support for AWS Secrets Manager to manage source and target database credentials.
* feature: EC2: This release adds Tag On Create feature support for the AllocateAddress API.
* feature: Glue: Add 4 connection properties: SECRET_ID, CONNECTOR_URL, CONNECTOR_TYPE, CONNECTOR_CLASS_NAME. Add two connection types: MARKETPLACE, CUSTOM
* feature: ManagedBlockchain: Added support for provisioning and managing public Ethereum nodes on main and test networks supporting secure access using Sigv4 and standard open-source Ethereum APIs.
* feature: Outposts: In this release, AWS Outposts adds support for three new APIs: TagResource, UntagResource, and ListTagsForResource. Customers can now manage tags for their resources through the SDK.
* feature: QLDBSession: Adds "TimingInformation" to all SendCommand API results and "IOUsage" to ExecuteStatementResult, FetchPageResult and CommitTransactionResult.
* feature: S3: Format GetObject's Expires header to be an http-date instead of iso8601
* feature: ServiceCatalogAppRegistry: New API `SyncResouce` to update AppRegistry system tags.
* feature: ServiceQuotas: Added the ability to tag applied quotas.

## 2.814.0
* bugfix: Credentials: SDK will throw if shared ini file's profile name can be resolved to __proto__
* feature: EC2: EBS io2 volumes now supports Multi-Attach
* feature: PersonalizeRuntime: Updated FilterValues regex pattern to align with Filter Expression.
* feature: RDS: Adds IAM DB authentication information to the PendingModifiedValues output of the DescribeDBInstances API. Adds ClusterPendingModifiedValues information to the output of the DescribeDBClusters API.

## 2.813.0
* feature: ConfigService: Adding PutExternalEvaluation API which grants permission to deliver evaluation result to AWS Config
* feature: DLM: Provide Cross-account copy event based policy support in DataLifecycleManager (DLM)
* feature: EC2: C6gn instances are powered by AWS Graviton2 processors and offer 100 Gbps networking bandwidth. These instances deliver up to 40% better price-performance benefit versus comparable x86-based instances
* feature: Imagebuilder: This release adds support for building and distributing container images within EC2 Image Builder.
* feature: KMS: Added CreationDate and LastUpdatedDate timestamps to ListAliases API response
* feature: Route53: This release adds support for DNSSEC signing in Amazon Route 53.
* feature: Route53Resolver: Route 53 Resolver adds support for enabling resolver DNSSEC validation in virtual private cloud (VPC).
* feature: SQS: Amazon SQS adds queue attributes to enable high throughput FIFO.
* feature: ServiceCatalog: Support TagOptions sharing with Service Catalog portfolio sharing.

## 2.812.0
* feature: CostExplorer: This release updates the "MonitorArnList" from a list of String to be a list of Arn for both CreateAnomalySubscription and UpdateAnomalySubscription APIs
* feature: Location: Initial release of Amazon Location Service. A new geospatial service providing capabilities to render maps, geocode/reverse geocode, track device locations, and detect geofence entry/exit events.
* feature: QuickSight: QuickSight now supports connecting to federated data sources of Athena
* feature: WellArchitected: This is the first release of AWS Well-Architected Tool API support, use to review your workload and compare against the latest AWS architectural best practices.

## 2.811.0
* feature: Amp: (New Service) Amazon Managed Service for Prometheus is a fully managed Prometheus-compatible monitoring service that makes it easy to monitor containerized applications securely and at scale.
* feature: GreengrassV2: AWS IoT Greengrass V2 is a new major version of AWS IoT Greengrass. This release adds several updates such as modular components, continuous deployments, and improved ease of use.
* feature: IoTAnalytics: FileFormatConfiguration enables data store to save data in JSON or Parquet format. S3Paths enables you to specify the S3 objects that save your channel messages when you reprocess the pipeline.
* feature: IoTFleetHub: AWS IoT Fleet Hub, a new feature of AWS IoT Device Management that provides a web application for monitoring and managing device fleets connected to AWS IoT at scale.
* feature: IoTWireless: AWS IoT for LoRaWAN enables customers to setup a private LoRaWAN network by connecting their LoRaWAN devices and gateways to the AWS cloud without managing a LoRaWAN Network Server.
* feature: Iot: AWS IoT Rules Engine adds Kafka Action that allows sending data to Apache Kafka clusters inside a VPC. AWS IoT Device Defender adds custom metrics and machine-learning based anomaly detection.
* feature: IotDeviceAdvisor: AWS IoT Core Device Advisor is fully managed test capability for IoT devices. Device manufacturers can use Device Advisor to test their IoT devices for reliable and secure connectivity with AWS IoT.
* feature: Lambda: Added support for Apache Kafka as a event source. Added support for TumblingWindowInSeconds for streams event source mappings. Added support for FunctionResponseTypes for streams event source mappings
* feature: SSM: Adding support for Change Manager API content

## 2.810.0
* feature: DevOpsGuru: Documentation updates for DevOps Guru.
* feature: EC2: Add c5n.metal to ec2 instance types list
* feature: GlobalAccelerator: This release adds support for custom routing accelerators

## 2.809.0
* feature: AutoScaling: Documentation updates and corrections for Amazon EC2 Auto Scaling API Reference and SDKs.
* feature: CloudTrail: CloudTrailInvalidClientTokenIdException is now thrown when a call results in the InvalidClientTokenId error code. The Name parameter of the AdvancedEventSelector data type is now optional.
* feature: IoTSiteWise: Added the ListAssetRelationships operation and support for composite asset models, which represent structured sets of properties within asset models.

## 2.808.0
* feature: EC2: TGW connect simplifies connectivity of SD-WAN appliances; IGMP support for TGW multicast; VPC Reachability Analyzer for VPC resources connectivity analysis.
* feature: Kendra: Amazon Kendra now supports adding synonyms to an index through the new Thesaurus resource.
* feature: NetworkManager: This release adds API support for Transit Gateway Connect integration into AWS Network Manager.

## 2.807.0
* feature: EC2: This release adds support for G4ad instances powered by AMD Radeon Pro V520 GPUs and AMD 2nd Generation EPYC processors
* feature: GlobalAccelerator: This release adds support for custom routing accelerators
* feature: Redshift: Add support for availability zone relocation feature.

## 2.806.0
* feature: AuditManager: AWS Audit Manager helps you continuously audit your AWS usage to simplify how you manage risk and compliance. This update releases the first version of the AWS Audit Manager APIs and SDK.
* feature: ECR: This release adds support for configuring cross-region and cross-account replication of your Amazon ECR images.
* feature: EMRcontainers: This release adds support for Amazon EMR on EKS, a simple way to run Spark on Kubernetes.
* feature: ForecastService: This release adds support for the Amazon Forecast Weather Index which can increase forecasting accuracy by automatically including weather forecasts in demand forecasts.
* feature: HealthLake: This release introduces Amazon HealthLake (preview), a HIPAA-eligible service that enables healthcare and life sciences customers to store, transform, query, and analyze health data in the AWS Cloud.
* feature: Kendra: 1. Amazon Kendra connector for Google Drive repositories 2. Amazon Kendra's relevance ranking models are regularly tuned for each customer by capturing end-user search patterns and feedback.
* feature: QuickSight: Added new parameters for join optimization.
* feature: SageMaker: This feature helps you monitor model performance characteristics such as accuracy, identify undesired bias in your ML models, and explain model decisions better with explainability drift detection.
* feature: SageMakerRuntime: This feature allows customers to invoke their endpoint with an inference ID. If used and data capture for the endpoint is enabled, this ID will be captured along with request data.
* feature: SagemakerEdge: Amazon SageMaker Edge Manager makes it easy to optimize, secure, monitor, and maintain  machine learning (ML) models across fleets of edge devices such as smart cameras, smart speakers, and robots.

## 2.805.0
* bugfix: S3: fixed a bug where createPresignedPost could result in a process crash.
* feature: DMS: Added PreserveTransaction setting to preserve order of CDC for S3 as target. Added CsvNoSupValue setting to replace empty value for columns not included in the supplemental log for S3 as target.
* feature: ServiceCatalogAppRegistry: AWS Service Catalog AppRegistry now supports adding, removing, and listing tags on resources after they are created.

## 2.804.0
* feature: EC2: This release introduces tag-on-create capability for the CreateImage API. A user can now specify tags that will be applied to the new resources (image, snapshots or both), during creation time.
* feature: Kafka: Adding HEALING to ClusterState.
* feature: Lambda: Added the additional enum InvalidImage to StateReasonCode and LastUpdateStatusReasonCode fields.
* feature: LicenseManager: Automated Discovery now has support for custom tags, and detects software uninstalls.
* feature: MediaLive: AWS Elemental MediaLive now supports black video and audio silence as new conditions to trigger automatic input failover.
* feature: RDS: Adds support for Amazon RDS Cross-Region Automated Backups, the ability to setup automatic replication of snapshots and transaction logs from a primary AWS Region to a secondary AWS Region.
* feature: SSM: AWS Systems Manager Patch Manager MAC OS Support and OpsMetadata Store APIs to store operational metadata for an Application.
* feature: WorkSpaces: Update the import-workspace-image API to have "BYOL_REGULAR_WSP" as a valid input string for ingestion-process.

## 2.803.0
* feature: Batch: This release adds support for customer to run Batch Jobs on ECS Fargate, the serverless compute engine built for containers on AWS. Customer can also propagate Job and Job Definition Tags to ECS Task.
* feature: ComputeOptimizer: This release enables AWS Compute Optimizer to analyze and generate optimization recommendations for EBS volumes that are attached to instances.
* feature: LicenseManager: AWS License Manager enables managed entitlements for AWS customers and Software Vendors (ISV). You can track and distribute license entitlements from AWS Marketplace and supported ISVs.

## 2.802.0
* bugfix: Profile: Removes an incorrectly named service `Profile` that was included in release, v2.801.0
* feature: CustomerProfiles: This is the first release of Amazon Connect Customer Profiles, a unified customer profile for your Amazon Connect contact center.

## 2.801.0
* feature: AmplifyBackend: (New Service) The Amplify Admin UI offers an accessible way to develop app backends and manage app content. We recommend that you use the Amplify Admin UI to manage the backend of your Amplify app.
* feature: AppIntegrations: The Amazon AppIntegrations service (in preview release) enables you to configure and reuse connections to external applications.
* feature: Connect: This release adds an Amazon Connect API that provides the ability to create tasks, and a set of APIs (in preview) to configure AppIntegrations associations with Amazon Connect instances.
* feature: ConnectContactLens: Contact Lens for Amazon Connect analyzes conversations, both real-time and post-call. The ListRealtimeContactAnalysisSegments API returns a list of analysis segments for a real-time analysis session.
* feature: DevOpsGuru: (New Service) Amazon DevOps Guru is available in public preview. It's a fully managed service that uses machine learning to analyze your operational solutions to help you find and troubleshoot issues.
* feature: DirectoryService: Adding client authentication feature for AWS AD Connector
* feature: EC2: This release adds support for: EBS gp3 volumes; and D3/D3en/R5b/M5zn instances powered by Intel Cascade Lake CPUs
* feature: ECRPUBLIC: Supports Amazon Elastic Container Registry (Amazon ECR) Public, a fully managed registry that makes it easy for a developer to publicly share container software worldwide for anyone to download.
* feature: EKS: Amazon EKS now allows you to define and manage the lifecycle for Kubernetes add-ons for your clusters. This release adds support for the AWS VPC CNI (vpc-cni).
* feature: Honeycode: Introducing APIs to read and write directly from Honeycode tables. Use APIs to pull table and column metadata, then use the read and write APIs to programmatically read and write from the tables.
* feature: Lambda: This release includes support for a new feature: Container images support in AWS Lambda. This adds APIs for deploying functions as container images. AWS Lambda now supports memory up to 10240MB.
* feature: LookoutVision: This release introduces support for Amazon Lookout for Vision.
* feature: Profile: This is the first release of Amazon Connect Customer Profiles, a unified customer profile for your Amazon Connect contact center.
* feature: S3: S3 adds support for multiple-destination replication, option to sync replica modifications;  S3 Bucket Keys to reduce cost of S3 SSE with AWS KMS
* feature: SageMaker: Amazon SageMaker Pipelines for ML workflows. Amazon SageMaker Feature Store, a fully managed repository for ML features.
* feature: SageMakerFeatureStoreRuntime: This release adds support for Amazon SageMaker Feature Store, which makes it easy for customers to create, version, share, and manage curated data for machine learning (ML) development.

## 2.800.0
* feature: EC2: This release introduces Amazon EC2 Mac1 instances, a new Amazon EC2 instance family built on Apple Mac mini computers, powered by AWS Nitro System, and support running macOS workloads on Amazon EC2

## 2.799.0
* feature: Appflow: Upsolver as a destination connector and documentation update.
* feature: Batch: Add Ec2Configuration in ComputeEnvironment.ComputeResources. Use in CreateComputeEnvironment API to enable AmazonLinux2 support.
* feature: CloudFormation: Adds support for the new Modules feature for CloudFormation. A module encapsulates one or more resources and their respective configurations for reuse across your organization.
* feature: CloudTrail: CloudTrail now includes advanced event selectors, which give you finer-grained control over the events that are logged to your trail.
* feature: CodeBuild: Adding GetReportGroupTrend API for Test Reports.
* feature: CognitoIdentityServiceProvider: This release adds ability to configure Cognito User Pools with third party sms and email providers for sending notifications to users.
* feature: Comprehend: Support Comprehend events detection APIs
* feature: ElasticBeanstalk: Updates the Integer constraint of DescribeEnvironmentManagedActionHistory's MaxItems parameter to [1, 100].
* feature: FSx: This release adds the capability to increase storage capacity of Amazon FSx for Lustre file systems, providing the flexibility to meet evolving storage needs over time.
* feature: GameLift: GameLift FlexMatch is now available as a standalone matchmaking solution. FlexMatch now provides customizable matchmaking for games hosted peer-to-peer, on-premises, or on cloud compute primitives.
* feature: IoTSiteWise: This release adds support for customer managed customer master key (CMK) based encryption in IoT SiteWise.
* feature: LexModelBuildingService: Lex now supports es-419, de-DE locales
* feature: MWAA: (New Service) Amazon MWAA is a managed service for Apache Airflow that makes it easy for data engineers and data scientists to execute data processing workflows in the cloud.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for Vorbis and Opus audio in OGG/OGA containers.
* feature: QuickSight: Support for embedding without user registration. New enum EmbeddingIdentityType. A potential breaking change. Affects code that refers IdentityType enum type directly instead of literal string value.
* feature: StepFunctions: This release of the AWS Step Functions SDK introduces support for Synchronous Express Workflows
* feature: TimestreamWrite: Adds support of upserts for idempotent updates to Timestream.

## 2.798.0
* feature: ApplicationInsights: Add Detected Workload to ApplicationComponent which shows the workloads that installed in the component
* feature: CodeArtifact: Add support for the NuGet package format.
* feature: CodeStarconnections: Added support for the UpdateHost API.
* feature: DynamoDB: With this release, you can capture data changes in any Amazon DynamoDB table as an Amazon Kinesis data stream. You also can use PartiQL (SQL-compatible language) to manipulate data in DynamoDB tables.
* feature: EC2: This release adds support for Multiple Private DNS names to DescribeVpcEndpointServices response.
* feature: ECS: This release adds support for updating capacity providers, specifying custom instance warmup periods for capacity providers, and using deployment circuit breaker for your ECS Services.
* feature: EMR: Add API support for EMR Studio, a new notebook-first IDE for data scientists and data engineers with single sign-on, Jupyter notebooks, automated infrastructure provisioning, and job diagnosis.
* feature: ForecastService: Releasing the set of PredictorBacktestExportJob APIs which allow customers to export backtest values and item-level metrics data from Predictor training.
* feature: Glue: Feature1 - Glue crawler adds data lineage configuration option. Feature2 - AWS Glue Data Catalog adds APIs for PartitionIndex creation and deletion as part of Enhancement Partition Management feature.
* feature: Iot: This release enables users to identify different file types in the over-the-air update (OTA) functionality using fileType parameter for CreateOTAUpdate API
* feature: Kafka: Adding MAINTENANCE and REBOOTING_BROKER to Cluster states.
* feature: Lambda: This release includes support for new feature: Code Signing for AWS Lambda. This adds new resources and APIs to configure Lambda functions to accept and verify signed code artifacts at deployment.
* feature: LicenseManager: AWS License Manager now provides the ability for license administrators to be able to associate license configurations to AMIs shared with their AWS account
* feature: Outposts: Support specifying tags during the creation of the Outpost resource. Tags are now returned in the response body of Outpost APIs.
* feature: SSOAdmin: AWS Single Sign-On now enables attribute-based access control for workforce identities to simplify permissions in AWS
* feature: SecurityHub: Updated the account management API to support the integration with AWS Organizations. Added new methods to allow users to view and manage the delegated administrator account for Security Hub.
* feature: Signer: AWS Signer is launching code-signing for AWS Lambda. Now customers can cryptographically sign Lambda code to ensure trust, integrity, and functionality.
* feature: TimestreamQuery: Amazon Timestream now supports "QueryStatus" in Query API which has information about cumulative bytes scanned, metered, as well as progress percentage for the query.
* feature: Translate: This update adds new operations to create and manage parallel data in Amazon Translate. Parallel data is a resource that you can use to run Active Custom Translation jobs.

## 2.797.0
* feature: AppMesh: This release makes tag value a required attribute of the tag's key-value pair.
* feature: Chime: The Amazon Chime SDK for messaging provides the building blocks needed to build chat and other real-time collaboration features.
* feature: CloudHSMV2: Added managed backup retention, a feature that enables customers to retain backups for a configurable period after which CloudHSM service will automatically delete them.
* feature: CodeGuruReviewer: This release supports tagging repository association resources in Amazon CodeGuru Reviewer.
* feature: CognitoIdentity: Added SDK pagination support for ListIdentityPools
* feature: Connect: This release adds a set of Amazon Connect APIs to programmatically control instance creation, modification, description and deletion.
* feature: Kafka: This release adds support for PER TOPIC PER PARTITION monitoring on AWS MSK clusters.
* feature: Macie2: The Amazon Macie API now provides S3 bucket metadata that indicates whether any one-time or recurring classification jobs are configured to analyze data in a bucket.
* feature: S3: Add new documentation regarding automatically generated Content-MD5 headers when using the SDK or CLI.
* feature: ServiceCatalogAppRegistry: AWS Service Catalog AppRegistry Documentation update

## 2.796.0
* feature: AutoScaling: You can now create Auto Scaling groups with multiple launch templates using a mixed instances policy, making it easy to deploy an AMI with an architecture that is different from the rest of the group.
* feature: CloudWatchEvents: EventBridge now supports Resource-based policy authorization on event buses. This enables cross-account PutEvents API calls, creating cross-account rules, and simplifies permission management.
* feature: CostExplorer: Additional metadata that may be applicable to the recommendation.
* feature: DirectoryService: Adding multi-region replication feature for AWS Managed Microsoft AD
* feature: EventBridge: EventBridge now supports Resource-based policy authorization on event buses. This enables cross-account PutEvents API calls, creating cross-account rules, and simplifies permission management.
* feature: Glue: Adding support for Glue Schema Registry. The AWS Glue Schema Registry is a new feature that allows you to centrally discover, control, and evolve data stream schemas.
* feature: KinesisAnalyticsV2: Amazon Kinesis Data Analytics now supports building and running streaming applications using Apache Flink 1.11 and provides a way to access the Apache Flink dashboard for supported Flink versions.
* feature: Lambda: Added the starting position and starting position timestamp to ESM Configuration. Now customers will be able to view these fields for their ESM.
* feature: LexModelBuildingService: Amazon Lex supports managing input and output contexts as well as default values for slots.
* feature: LexRuntime: Amazon Lex now supports the ability to view and manage active contexts associated with a user session.
* feature: MediaLive: The AWS Elemental MediaLive APIs and SDKs now support the ability to see the software update status on Link devices
* feature: Redshift: Amazon Redshift support for returning ClusterNamespaceArn in describeClusters

## 2.795.0
* feature: Backup: AWS Backup now supports cross-account backup, enabling AWS customers to securely copy their backups across their AWS accounts within their AWS organizations.
* feature: CloudFormation: This release adds ChangeSets support for Nested Stacks. ChangeSets offer a preview of how proposed changes to a stack might impact existing resources or create new ones.
* feature: CodeBuild: AWS CodeBuild - Adding Status field for Report Group
* feature: EC2: EC2 Fleet adds support of DeleteFleets API for instant type fleets. Now you can delete an instant type fleet and terminate all associated instances with a single API call.
* feature: Outposts: Mark the Name parameter in CreateOutpost as required.
* feature: S3Control: AWS S3 Storage Lens provides visibility into your storage usage and activity trends at the organization or account level, with aggregations by Region, storage class, bucket, and prefix.

## 2.794.0
* feature: Chime: This release adds CRUD APIs for Amazon Chime SipMediaApplications and SipRules. It also adds the API for creating outbound PSTN calls for Amazon Chime meetings.
* feature: Connect: This release adds support for user hierarchy group and user hierarchy structure. For details, see the Release Notes in the Amazon Connect Administrator Guide.
* feature: FMS: Added Firewall Manager policy support for AWS Network Firewall resources.
* feature: Macie2: The Amazon Macie API now has a lastRunErrorStatus property to indicate if account- or bucket-level errors occurred during the run of a one-time classification job or the latest run of a recurring job.
* feature: NetworkFirewall: (New Service) AWS Network Firewall is a managed network layer firewall service that makes it easy to secure your virtual private cloud (VPC) networks and block malicious traffic.
* feature: RDS: Support copy-db-snapshot in the one region on cross clusters and local cluster for RDSonVmware. Add target-custom-availability-zone parameter to specify where a snapshot should be copied.

## 2.793.0
* feature: CodePipeline: We show details about inbound executions and id of action executions in GetPipelineState API. We also add ConflictException to StartPipelineExecution, RetryStageExecution, StopPipelineExecution APIs.
* feature: DMS: Adding MoveReplicationTask feature to move replication tasks between instances
* feature: IoTSecureTunneling: Support using multiple data streams per tunnel using the Secure Tunneling multiplexing feature.
* feature: IoTSiteWise: This release supports Unicode characters for string operations in formulae computes in SiteWise. For more information, search for SiteWise in Amazon What's new or refer the SiteWise documentation.
* feature: QuickSight: Adding new parameters for dashboard persistence
* feature: SageMaker: This feature enables customers to encrypt their Amazon SageMaker Studio storage volumes with customer master keys (CMKs) managed by them in AWS Key Management Service (KMS).
* feature: ServiceCatalog: Support import of CloudFormation stacks into Service Catalog provisioned products.
* feature: Synthetics: AWS Synthetics now supports Environment Variables  to assign runtime parameters in the canary scripts.

## 2.792.0
* feature: ELBv2: Adds dualstack support for Network Load Balancers (TCP/TLS only), an attribute for WAF fail open for Application Load Balancers, and an attribute for connection draining for Network Load Balancers.
* feature: Shield: This release adds APIs for two new features: 1) Allow customers to bundle resources into protection groups and treat as a single unit. 2) Provide per-account event summaries to all AWS customers.
* feature: Textract: AWS Textract now allows customers to specify their own KMS key to be used for asynchronous jobs output results, AWS Textract now also recognizes handwritten text from English documents.

## 2.791.0
* feature: Iot: This release adds a batchMode parameter to the IotEvents, IotAnalytics, and Firehose actions which allows customers to send an array of messages to the corresponding services
* feature: LexModelBuildingService: Lex now supports es-ES, it-IT, fr-FR and fr-CA locales
* feature: Lightsail: This release adds support for Amazon Lightsail container services. You can now create a Lightsail container service, and deploy Docker images to it.
* feature: PersonalizeRuntime: Adds support to use dynamic filters with Personalize.
* feature: Polly: Amazon Polly adds new Australian English female voice - Olivia. Olivia is available as Neural voice only.
* feature: RoboMaker: This release introduces Robomaker Worldforge TagsOnCreate which allows customers to tag worlds as they are being generated by providing the tags while configuring a world generation job.
* feature: ServiceCatalogAppRegistry: AWS Service Catalog AppRegistry provides a repository of your applications, their resources, and the application metadata that you use within your enterprise.

## 2.790.0
* feature: Amplify: Whereas previously custom headers were set via the app's buildspec, custom headers can now be set directly on the Amplify app for both ci/cd and manual deploy apps.
* feature: DataBrew: This is the initial SDK release for AWS Glue DataBrew. DataBrew is a visual data preparation tool that enables users to clean and normalize data without writing any code.
* feature: ForecastService: Providing support of custom quantiles in CreatePredictor API.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for Automated ABR encoding and improved the reliability of embedded captions in accelerated outputs.
* feature: QuickSight: QuickSight now supports Column-level security and connecting to Oracle data source.
* feature: ServiceCatalog: Adding support to remove a Provisioned Product launch role via UpdateProvisionedProductProperties

## 2.789.0
* feature: EC2: This release adds support for Gateway Load Balancer VPC endpoints and VPC endpoint services
* feature: ELBv2: Added support for Gateway Load Balancers, which make it easy to deploy, scale, and run third-party virtual networking appliances.
* feature: SSM: Add SessionId as a filter for DescribeSessions API

## 2.788.0
* feature: DataSync: DataSync now enables customers to adjust the network bandwidth used by a running AWS DataSync task.
* feature: DynamoDB: This release adds supports for exporting Amazon DynamoDB table data to Amazon S3 to perform analytics at any scale.
* feature: ECS: This release provides native support for specifying Amazon FSx for Windows File Server file systems as volumes in your Amazon ECS task definitions.
* feature: ES: Adding support for package versioning in Amazon Elasticsearch Service
* feature: FSx: This release adds support for creating DNS aliases for Amazon FSx for Windows File Server, and using AWS Backup to automate scheduled, policy-driven backup plans for Amazon FSx file systems.
* feature: IoTAnalytics: AWS IoT Analytics now supports Late Data Notifications for datasets, dataset content creation using previous version IDs, and includes the LastMessageArrivalTime attribute for channels and datastores.
* feature: Macie2: Sensitive data findings in Amazon Macie now include enhanced location data for Apache Avro object containers and Apache Parquet files.
* feature: S3: S3 Intelligent-Tiering adds support for Archive and Deep Archive Access tiers; S3 Replication adds replication metrics and failure notifications, brings feature parity for delete marker replication
* feature: SSM: add a new filter to allow customer to filter automation executions by using resource-group which used for execute automation
* feature: StorageGateway: Added bandwidth rate limit schedule for Tape and Volume Gateways

## 2.787.0
* feature: DLM: Amazon Data Lifecycle Manager now supports the creation and retention of EBS-backed Amazon Machine Images
* feature: EC2: Network card support with four new attributes: NetworkCardIndex, NetworkPerformance, DefaultNetworkCardIndex, and MaximumNetworkInterfaces, added to the DescribeInstanceTypes API.
* feature: IoTSiteWise: Remove the CreatePresignedPortalUrl API
* feature: MediaLive: Support for SCTE35 ad markers in OnCuePoint style in RTMP outputs.

## 2.786.0
* feature: AppMesh: This release adds circuit breaking capabilities to your mesh with connection pooling and outlier detection support.
* feature: CloudWatchEvents: With this release, customers can now reprocess past events by storing the events published on event bus in an encrypted archive.
* feature: DynamoDB: This release adds a new ReplicaStatus INACCESSIBLE_ENCRYPTION_CREDENTIALS for the Table description, indicating when a key used to encrypt a regional replica table is not accessible.
* feature: EC2: Documentation updates for EC2.
* feature: ES: Amazon Elasticsearch Service now provides the ability to define a custom endpoint for your domain and link an SSL certificate from ACM, making it easier to refer to Kibana and the domain endpoint.
* feature: EventBridge: With this release, customers can now reprocess past events by storing the events published on event bus in an encrypted archive.
* feature: FraudDetector: Added support for deleting resources like Variables, ExternalModels, Outcomes, Models, ModelVersions, Labels, EventTypes and EntityTypes. Updated DeleteEvent operation to catch missing exceptions.
* feature: Kendra: Amazon Kendra now supports providing user context in your query requests, Tokens can be JSON or JWT format. This release also introduces support for Confluence cloud datasources.
* feature: Lambda: Support Amazon MQ as an Event Source.
* feature: RDS: Supports a new parameter to set the max allocated storage in gigabytes for the CreateDBInstanceReadReplica API.

## 2.785.0
* feature: AutoScaling: Capacity Rebalance helps you manage and maintain workload availability during Spot interruptions by proactively augmenting your Auto Scaling group with a new instance before interrupting an old one.
* feature: EC2: Added support for Client Connect Handler for AWS Client VPN. Fleet supports launching replacement instances in response to Capacity Rebalance recommendation.
* feature: ES: Amazon Elasticsearch Service now supports native SAML authentication that seamlessly integrates with the customers' existing SAML 2.0 Identity Provider (IdP).
* feature: Iot: Updated API documentation and added paginator for AWS Iot Registry ListThingPrincipals API.
* feature: MQ: Amazon MQ introduces support for RabbitMQ, a popular message-broker with native support for AMQP 0.9.1. You can now create fully-managed RabbitMQ brokers in the cloud.
* feature: MarketplaceMetering: Adding Vendor Tagging Support in MeterUsage and BatchMeterUsage API.
* feature: ServiceCatalog: Service Catalog API ListPortfolioAccess can now support a maximum PageSize of 100.
* feature: XRay: Releasing new APIs GetInsightSummaries, GetInsightEvents, GetInsight, GetInsightImpactGraph and updating GetTimeSeriesServiceStatistics API for AWS X-Ray Insights feature

## 2.784.0
* feature: EC2: This release adds support for the following features: 1. P4d instances based on NVIDIA A100 GPUs.  2. NetworkCardIndex attribute to support multiple network cards.

## 2.783.0
* bugfix: Types: Fix type of AWSError
* bugfix: Types: Update types for credential provider chain
* feature: Braket: This release supports tagging for Amazon Braket quantum-task resources. It also supports tag-based access control for quantum-task APIs.
* feature: DMS: Adding DocDbSettings to support DocumentDB as a source.
* feature: Imagebuilder: This feature increases the number of accounts that can be added to the Launch permissions within an Image Builder Distribution configuration.
* feature: Macie2: This release of the Amazon Macie API adds an eqExactMatch operator for filtering findings. With this operator you can increase the precision of your finding filters and suppression rules.
* feature: MediaLive: Support for HLS discontinuity tags in the child manifests. Support for incomplete segment behavior in the media output. Support for automatic input failover condition settings.

## 2.782.0
* feature: APIGateway: Support disabling the default execute-api endpoint for REST APIs.
* feature: CodeArtifact: Add support for tagging of CodeArtifact domain and repository resources.
* feature: EC2: Support for Appliance mode on Transit Gateway that simplifies deployment of stateful network appliances. Added support for AWS Client VPN Self-Service Portal.
* feature: ELBv2: Application Load Balancer (ALB) now supports the gRPC protocol-version. With this release, customers can use ALB to route and load balance gRPC traffic between gRPC enabled clients and microservices.
* feature: SESV2: This release enables customers to manage their own contact lists and end-user subscription preferences.
* feature: StorageGateway: Adding support for access based enumeration on SMB file shares, file share visibility on SMB file shares, and file upload notifications for all file shares
* feature: TypeScript: Add AWS.Endpoint to ServiceConfigurationOptions.endpoint type.

## 2.781.0
* feature: EC2: AWS Nitro Enclaves general availability. Added support to RunInstances for creating enclave-enabled EC2 instances. New APIs to associate an ACM certificate with an IAM role, for enclave consumption.
* feature: Iot: This release adds support for GG-Managed Job Namespace

## 2.780.0
* feature: Glue: AWS Glue machine learning transforms now support encryption-at-rest for labels and trained models.

## 2.779.0
* feature: Kendra: Amazon Kendra now supports indexing data from Confluence Server.
* feature: Neptune: This feature enables custom endpoints for Amazon Neptune clusters. Custom endpoints simplify connection management when clusters contain instances with different capacities and configuration settings.
* feature: SageMaker: This release enables customers to bring custom images for use with SageMaker Studio notebooks.

## 2.778.0
* feature: MediaTailor: MediaTailor now supports ad marker passthrough for HLS. Use AdMarkerPassthrough to pass EXT-X-CUE-IN, EXT-X-CUE-OUT, and EXT-X-SPLICEPOINT-SCTE35 from origin manifests into personalized manifests.
* feature: QuickSight: Support description on columns.

## 2.777.0
* feature: Appflow: Salesforce connector creation with customer provided client id and client secret, incremental pull configuration, salesforce upsert write operations and execution ID when on-demand flows are executed.
* feature: SNS: SNS now supports a new class of topics: FIFO (First-In-First-Out). FIFO topics provide strictly-ordered, deduplicated, filterable, encryptable, many-to-many messaging at scale.

## 2.776.0
* feature: CloudFront: CloudFront adds support for managing the public keys for signed URLs and signed cookies directly in CloudFront (it no longer requires the AWS root account).
* feature: EC2: instance-storage-info nvmeSupport added to DescribeInstanceTypes API
* feature: GlobalAccelerator: This release adds support for specifying port overrides on AWS Global Accelerator endpoint groups.
* feature: Glue: AWS Glue crawlers now support incremental crawls for the Amazon Simple Storage Service (Amazon S3) data source.
* feature: Kendra: This release adds custom data sources: a new data source type that gives you full control of the documents added, modified or deleted during a data source sync while providing run history metrics.

## 2.775.0
* bugfix: Credentials: Do not require credentials file when loading from config.
* feature: Batch: Adding evaluateOnExit to job retry strategies.
* feature: ElasticBeanstalk: EnvironmentStatus enum update to include Aborting, LinkingFrom and LinkingTo

## 2.774.0
* feature: CloudFront: Amazon CloudFront adds support for Origin Shield.
* feature: SSM: This Patch Manager release now supports Common Vulnerabilities and Exposure (CVE) Ids for missing packages via the DescribeInstancePatches API.
* feature: ServiceCatalog: An Admin can now update the launch role associated with a Provisioned Product. Admins and End Users can now view the launch role associated with a Provisioned Product.

## 2.773.0
* feature: MediaLive: The AWS Elemental MediaLive APIs and SDKs now support the ability to transfer the ownership of MediaLive Link devices across AWS accounts.

## 2.772.0
* feature: AccessAnalyzer: This release adds support for the ApplyArchiveRule api in IAM Access Analyzer.  The ApplyArchiveRule api allows users to apply an archive rule retroactively to existing findings in an analyzer.
* feature: Budgets: This release introduces AWS Budgets Actions, allowing you to define an explicit response(or set of responses)  to take when your budget exceeds it's action threshold.
* feature: CostExplorer: This release improves email validation for subscriptions on the SDK endpoints.
* feature: DMS: When creating Endpoints, Replication Instances, and Replication Tasks, the feature provides you the option to specify friendly name to the resources.
* feature: GroundStation: Adds error message attribute to DescribeContact DataflowDetails
* feature: Iot: Add new variable, lastStatusChangeDate, to DescribeDomainConfiguration  API
* feature: Macie2: This release of the Amazon Macie API adds support for pausing and resuming classification jobs. Also, sensitive data findings now include location data for up to 15 occurrences of sensitive data.
* feature: RDS: Return tags for all resources in the output of DescribeDBInstances, DescribeDBSnapshots, DescribeDBClusters, and DescribeDBClusterSnapshots API operations.
* feature: Rekognition: This SDK Release introduces new API (DetectProtectiveEquipment) for Amazon Rekognition. This release also adds ServiceQuotaExceeded exception to Amazon Rekognition IndexFaces API.
* feature: SSM: This Patch Manager release now supports searching for available packages from Amazon Linux and Amazon Linux 2 via the DescribeAvailablePatches API.
* feature: Transfer: Add support to associate VPC Security Groups at server creation.
* feature: WorkMail: Add CreateOrganization and DeleteOrganization API operations.
* feature: XRay: Enhancing CreateGroup, UpdateGroup, GetGroup and GetGroups APIs to support configuring X-Ray Insights Notifications. Adding TraceLimit information into X-Ray BatchGetTraces API response.

## 2.771.0
* bugfix: Test: Delete unused variable declarations from test
* feature: Amplify: Performance mode optimizes for faster hosting performance by keeping content cached at the edge for a longer interval - enabling can make code changes can take up to 10 minutes to roll out.
* feature: EKS: This release introduces a new Amazon EKS error code: "ClusterUnreachable"
* feature: MediaLive: WAV audio output. Extracting ancillary captions in MP4 file inputs. Priority on channels feeding a multiplex (higher priority channels will tend to have higher video quality).
* feature: ServiceCatalog: This new API takes either a ProvisonedProductId or a ProvisionedProductName, along with a list of 1 or more output keys and responds with the (key,value) pairs of those outputs.
* feature: Snowball: We added new APIs to allow customers to better manage their device shipping. You can check if your shipping label expired, generate a new label, and tell us that you received or shipped your job.

## 2.770.0
* feature: CloudWatchEvents: Amazon EventBridge (formerly called CloudWatch Events) adds support for target Dead-letter Queues and custom retry policies.
* feature: CostExplorer: You can now create hierarchical cost categories by choosing "Cost Category" as a dimension. You can also track the status of your cost category updates to your cost and usage information.
* feature: EC2: AWS EC2 RevokeSecurityGroupIngress and RevokeSecurityGroupEgress APIs will return IpPermissions which do not match with any existing IpPermissions for security groups in default VPC and EC2-Classic.
* feature: EventBridge: Amazon EventBridge adds support for target Dead Letter Queues (DLQs) and custom retry policies.
* feature: RDS: Supports a new parameter to set the max allocated storage in gigabytes for restore database instance from S3 and restore database instance to a point in time APIs.
* feature: Rekognition: This release provides location information for the manifest validation files.
* feature: SageMaker: This release enables Sagemaker customers to convert Tensorflow and PyTorch models to CoreML (ML Model) format.
* feature: Type: export client config interface on root as ConfigurationOptions

## 2.769.0
* feature: ComputeOptimizer: This release enables AWS Compute Optimizer to analyze EC2 instance-level EBS read and write operations, and throughput when generating recommendations for your EC2 instances and Auto Scaling groups.
* feature: CostExplorer: Enables Rightsizing Recommendations to analyze and present EC2 instance-level EBS metrics when generating recommendations. Returns AccessDeniedException if the account is not opted into Rightsizing
* feature: ElastiCache: This release introduces User and UserGroup to allow customers to have access control list of the Redis resources for AWS ElastiCache. This release also adds support for Outposts  for AWS ElastiCache.
* feature: MediaPackage: AWS Elemental MediaPackage provides access logs that capture detailed information about requests sent to a customer's MediaPackage channel.

## 2.768.0
* feature: DMS: Added new S3 endpoint settings to allow partitioning CDC data by date for S3 as target. Exposed some Extra Connection Attributes as endpoint settings for relational databases as target.
* feature: EC2: This release supports returning additional information about local gateway virtual interfaces, and virtual interface groups.
* feature: KinesisAnalyticsV2: Amazon Kinesis Analytics now supports StopApplication with 'force' option
* feature: MarketplaceCatalog: AWS Marketplace Catalog now supports FailureCode for change workflows to help differentiate client errors and server faults.

## 2.767.0
* feature: DynamoDB: This release adds a new ReplicaStatus REGION DISABLED for the Table description. This state indicates that the AWS Region for the replica is inaccessible because the AWS Region is disabled.
* feature: Glue: AWS Glue crawlers now support Amazon DocumentDB (with MongoDB compatibility) and MongoDB collections. You can choose to crawl the entire data set or only a small sample to reduce crawl time.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for AVC-I and VC3 encoding in the MXF OP1a container, Nielsen non-linear watermarking, and InSync FrameFormer frame rate conversion.
* feature: SageMaker: This release adds support for launching Amazon SageMaker Studio in your VPC. Use AppNetworkAccessType in CreateDomain API to disable access to public internet and restrict the network traffic to VPC.

## 2.766.0
* bugfix: lib: call customBackoff() only upon retryable errors
* feature: Batch: Support tagging for Batch resources (compute environment, job queue, job definition and job) and tag based access control on Batch APIs
* feature: ELBv2: This release adds support for tagging listeners, rules, and target groups on creation. This release also supported tagging operations through tagging api's for listeners and rules.
* feature: PersonalizeEvents: Adds new APIs to write item and user records to Datasets.
* feature: RDS: Adds the NCHAR Character Set ID parameter to the CreateDbInstance API for RDS Oracle.
* feature: S3: Amazon S3 Object Ownership is a new S3 feature that enables bucket owners to automatically assume ownership of objects that are uploaded to their buckets by other AWS Accounts.
* feature: ServiceDiscovery: Added support for optional parameters for DiscoverInstances API in AWS Cloud Map
* feature: docs: Update s_code Script Handling

## 2.765.0
* feature: AppSync: Exposes the wafWebAclArn field on GraphQL api records. The wafWebAclArn field contains the amazon resource name of a WAF Web ACL if the AWS AppSync API is associated with one.
* feature: Glue: Adding additional optional map parameter to get-plan api
* feature: Kafka: Added support for Enabling Zookeeper Encryption in Transit for AWS MSK.
* feature: QuickSight: QuickSight now supports connecting to AWS Timestream data source
* feature: WAFV2: AWS WAF is now available for AWS AppSync GraphQL APIs. AWS WAF protects against malicious attacks with AWS Managed Rules or your own custom rules. For more information see the AWS WAF Developer Guide.

## 2.764.0
* feature: ApplicationAutoScaling: This release extends Auto Scaling support for cluster storage of Managed Streaming for Kafka. Auto Scaling monitors and automatically expands storage capacity when a critical usage threshold is met.
* feature: DataSync: This release enables customers to create s3 location for S3 bucket's located on an AWS Outpost.
* feature: EMR: Amazon EMR customers can now use EC2 placement group to influence the placement of master nodes in a high-availability (HA) cluster across distinct underlying hardware to improve cluster availability.
* feature: Imagebuilder: EC2 Image Builder adds support for copying AMIs created by Image Builder to accounts specific to each Region.
* feature: Iot: AWS IoT Rules Engine adds Timestream action. The Timestream rule action lets you stream time-series data from IoT sensors and applications to Amazon Timestream databases for time series analysis.
* feature: MediaConnect: MediaConnect now supports reservations to provide a discounted rate for a specific outbound bandwidth over a period of time.
* feature: Pinpoint: Amazon Pinpoint - Features - Customers can start a journey based on an event being triggered by an endpoint or user.
* feature: S3: Amazon S3 on Outposts expands object storage to on-premises AWS Outposts environments, enabling you to store and retrieve objects using S3 APIs and features.
* feature: S3: Support S3 on Outposts Access Point and Bucket ARNs
* feature: S3Control: Amazon S3 on Outposts expands object storage to on-premises AWS Outposts environments, enabling you to store and retrieve objects using S3 APIs and features.
* feature: S3Outposts: Amazon S3 on Outposts expands object storage to on-premises AWS Outposts environments, enabling you to store and retrieve objects using S3 APIs and features.
* feature: SecurityHub: Added several new resource details objects. Added additional details for CloudFront distributions, IAM roles, and IAM access keys. Added a new ResourceRole attribute for resources.

## 2.763.0
* feature: Schemas: Added support for schemas of type JSONSchemaDraft4. Added ExportSchema API that converts schemas in AWS Events registry and Discovered schemas from OpenApi3  to JSONSchemaDraft4.
* feature: TimestreamQuery: (New Service) Amazon Timestream is a fast, scalable, fully managed, purpose-built time series database that makes it easy to store and analyze trillions of time series data points per day.
* feature: TimestreamWrite: (New Service) Amazon Timestream is a fast, scalable, fully managed, purpose-built time series database that makes it easy to store and analyze trillions of time series data points per day.

## 2.762.0
* feature: ApplicationAutoScaling: This release extends Application Auto Scaling support to AWS Comprehend Entity Recognizer endpoint, allowing automatic updates to provisioned Inference Units to maintain targeted utilization level.
* feature: RDS: This release adds the InsufficientAvailableIPsInSubnetFault error for RDS Proxy.

## 2.761.0
* feature: Batch: Support custom logging, executionRole, secrets, and linuxParameters (initProcessEnabled, maxSwap, swappiness, sharedMemorySize, and tmpfs). Also, add new context keys for awslogs.
* feature: ConfigService: Make the delivery-s3-bucket as an optional parameter for conformance packs and organizational conformance packs
* feature: EC2: This release supports returning additional information about local gateway resources, such as the local gateway route table.
* feature: FraudDetector: Increased maximum length of eventVariables values for GetEventPrediction from 256 to 1024.
* feature: STS: Documentation update for AssumeRole error

## 2.760.0
* feature: Amplify: Allow Oauth Token in CreateApp call to be a maximum of 1000 characters instead of 100
* feature: EKS: Amazon EKS now supports configuring your cluster's service CIDR during cluster creation.
* feature: SavingsPlans: Introducing Queued SavingsPlans that will enable customers to queue their purchase request of Savings Plans for future dates.
* feature: Synthetics: AWS Synthetics now supports AWS X-Ray Active Tracing feature. RunConfig is now an optional parameter with timeout updated from (60 - 900 seconds) to (3 - 840 seconds).
* feature: Textract: AWS Textract now supports output results for asynchronous jobs to customer specified s3 bucket.
* feature: TranscribeService: Amazon Transcribe now supports WebM, OGG, AMR and AMR-WB as input formats. You can also specify an output key as a location within your S3 buckets to store the output of your transcription jobs.

## 2.759.0
* feature: Backup: This release allows customers to enable or disable advanced backup settings in backup plan. As part of this feature AWS Backup added support for  Windows VSS backup option for EC2 resources.
* feature: CostExplorer: This release provides access to Cost Anomaly Detection Public Preview APIs. Cost Anomaly Detection finds cost anomalies based on your historical cost and usage using Machine Learning models.
* feature: QuickSight: Added Sheet information to DescribeDashboard, DescribeTemplate and DescribeAnalysis API response.
* feature: Translate: Improvements to DeleteTerminology API.

## 2.758.0
* bugfix: Authentication: assume-role credentials ignore profile region
* feature: Comprehend: Amazon Comprehend integrates with Amazon SageMaker GroundTruth to allow its customers to annotate their datasets using GroundTruth and train their models using Comprehend Custom APIs.
* feature: LexModelBuildingService: Lex now supports es-US locales
* feature: WorkMail: Adding support for Mailbox Export APIs

## 2.757.0
* feature: CloudWatchEvents: Add support for Redshift Data API Targets
* feature: EventBridge: Add support for Redshift Data API Targets
* feature: Glue: Adding support to update multiple partitions of a table in a single request
* feature: IoTSiteWise: This release supports IAM mode for SiteWise Monitor portals

## 2.756.0
* feature: CodeStarconnections: New integration with the GitHub provider type.
* feature: MediaLive: AWS Elemental MediaLive now supports batch operations, which allow users to start, stop, and delete multiple MediaLive resources with a single request.

## 2.755.0
* bugfix: Types: Update types for fetching credentials from config
* feature: APIGateway: Adds support for mutual TLS authentication for public regional REST Apis
* feature: ApiGatewayV2: Adds support for mutual TLS authentication and disableAPIExecuteEndpoint for public regional HTTP Apis
* feature: Comprehend: Amazon Comprehend now supports detecting Personally Identifiable Information (PII) entities in a document.
* feature: ES: Adds support for data plane audit logging in Amazon Elasticsearch Service.
* feature: Kendra: Amazon Kendra now supports additional file formats and metadata for FAQs.

## 2.754.0
* feature: Connect: This release adds support for contact flows and routing profiles. For details, see the Release Notes in the Amazon Connect Administrator Guide.
* feature: DLM: Customers can now provide multiple schedules within a single Data Lifecycle Manager (DLM) policy. Each schedule supports tagging, Fast Snapshot Restore (FSR) and cross region copy individually.
* feature: Greengrass: This release includes the ability to set run-time configuration for a Greengrass core. The Telemetry feature, also included in this release, can be configured via run-time configuration per core.
* feature: ServiceCatalog: Enhance DescribeProvisionedProduct API to allow useProvisionedProduct Name as Input, so customer can provide ProvisionedProduct Name instead of ProvisionedProduct Id to describe a ProvisionedProduct.

## 2.753.0
* feature: EC2: T4g instances are powered by AWS Graviton2 processors
* feature: Kafka: Added new API's to support SASL SCRAM Authentication with MSK Clusters.
* feature: Kendra: Amazon Kendra now returns confidence scores for 'document' query responses.
* feature: MediaLive: AWS Elemental MediaLive now supports CDI (Cloud Digital Interface) inputs which enable uncompressed video from applications on Elastic Cloud Compute (EC2), AWS Media Services, and from AWS partners
* feature: Organizations: AWS Organizations now enables you to add tags to the AWS accounts, organizational units, organization root, and policies in your organization.
* feature: SageMaker: Sagemaker Ground Truth: Added support for a new Streaming feature which helps to continuously feed data and receive labels in real time. This release adds a new input and output SNS data channel.
* feature: TranscribeService: Amazon Transcribe now supports automatic language identification, which enables you to transcribe audio files without needing to know the language in advance.

## 2.752.0
* feature: DocDB: Updated API documentation and added paginators for DescribeCertificates, DescribeDBClusterParameterGroups, DescribeDBClusterParameters, DescribeDBClusterSnapshots and DescribePendingMaintenanceActions
* feature: EC2: This release adds support for the T4G instance family to the EC2 ModifyDefaultCreditSpecification and GetDefaultCreditSpecification APIs.
* feature: ManagedBlockchain: Introducing support for Hyperledger Fabric 1.4. When using framework version 1.4, the state database may optionally be specified when creating peer nodes (defaults to CouchDB).
* feature: StepFunctions: This release of the AWS Step Functions SDK introduces support for AWS X-Ray.

## 2.751.0
* feature: WorkSpaces: Adds API support for WorkSpaces Cross-Region Redirection feature.

## 2.750.0
* feature: CloudFront: Cloudfront adds support for Brotli. You can enable brotli caching and compression support by enabling it in your Cache Policy.
* feature: S3: Bucket owner verification feature added. This feature introduces the x-amz-expected-bucket-owner and x-amz-source-expected-bucket-owner headers.
* feature: SSOAdmin: This is an initial release of AWS Single Sign-On (SSO) Access Management APIs. This release adds support for SSO operations which could be used for managing access to AWS accounts.

## 2.749.0
* feature: Glue: Adding support for partitionIndexes to improve GetPartitions performance.
* feature: KinesisAnalyticsV2: Kinesis Data Analytics is adding new AUTOSCALING application status for applications during auto scaling and also adding FlinkRunConfigurationDescription in the ApplicationDetails.
* feature: RedshiftData: The Amazon Redshift Data API is generally available. This release enables querying Amazon Redshift data and listing various database objects.

## 2.748.0
* bugfix: protocol: Allow error code extraction from pascal cased Code attribute in the JSON body response
* feature: ApiGatewayV2: You can now secure HTTP APIs using Lambda authorizers and IAM authorizers. These options enable you to make flexible auth decisions using a Lambda function, or using IAM policies, respectively.
* feature: CodeBuild: AWS CodeBuild - Support keyword search for test cases in DecribeTestCases API . Allow deletion of reports in the report group, before deletion of report group using the deleteReports flag.
* feature: ELBv2: Adds support for Application Load Balancers on Outposts.
* feature: LexModelBuildingService: Amazon Lex supports en-AU locale
* feature: QuickSight: Adds tagging support for QuickSight customization resources.  A user can now specify a list of tags when creating a customization resource and use a customization ARN in QuickSight's tagging APIs.

## 2.747.0
* feature: WorkSpaces: Adding support for Microsoft Office 2016 and Microsoft Office 2019 in BYOL Images
* feature: XRay: Enhancing CreateGroup, UpdateGroup, GetGroup and GetGroups APIs to support configuring X-Ray Insights

## 2.746.0
* bugfix: Types: Re-export ConfigBase on previous config typings
* feature: GuardDuty: GuardDuty findings triggered by failed events now include the error code name within the AwsApiCallAction section.
* feature: Kendra: Amazon Kendra now returns confidence scores for both 'answer' and 'question and answer' query responses.
* feature: MediaPackage: Enables inserting a UTCTiming XML tag in the output manifest of a DASH endpoint which a media player will use to help with time synchronization.
* feature: StepFunctions: This release of the AWS Step Functions SDK introduces support for payloads up to 256KB for Standard and Express workflows

## 2.745.0
* bugfix: XML: Fixed an array equality bug in the Node.js XML parser
* feature: EC2: This release adds a new transit gateway attachment state and resource type.
* feature: Macie2: This release of the Amazon Macie API introduces additional statistics for the size and count of Amazon S3 objects that Macie can analyze as part of a classification job.

## 2.744.0
* feature: CodeGuruReviewer: Add support for repository analysis based code reviews
* feature: SecurityHub: Added a PatchSummary object for security findings. The PatchSummary object provides details about the patch compliance status of an instance.

## 2.743.0
* bugfix: DocumentClient: Add options.wrapNumbers doc in DynamoDB.DocumentClient
* feature: CloudFront: CloudFront now supports real-time logging for CloudFront distributions. CloudFront real-time logs are more detailed, configurable, and are available in real time.
* feature: EC2: Amazon EC2 and Spot Fleet now support modification of launch template configs for a running fleet enabling instance type, instance weight, AZ, and AMI updates without losing the current fleet ID.

## 2.742.0
* feature: CUR: This release add MONTHLY as the new supported TimeUnit for ReportDefinition.
* feature: CloudFront: You can now manage CloudFront's additional, real-time metrics with the CloudFront API.
* feature: EMR: Amazon EMR adds support for ICMP, port -1, in Block Public Access Exceptions and API access for EMR Notebooks execution. You can now non-interactively execute EMR Notebooks and pass input parameters.

## 2.741.0
* feature: EC2: Introduces support to initiate Internet Key Exchange (IKE) negotiations for VPN connections from AWS. A user can now send the initial IKE message to their Customer Gateway (CGW) from VPN endpoints.
* feature: GameLift: GameLift FleetIQ as a standalone feature is now generally available. FleetIQ makes low-cost Spot instances viable for game hosting. Use GameLift FleetIQ with your EC2 Auto Scaling groups.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for WebM DASH outputs as well as H.264 4:2:2 10-bit output in MOV and MP4.

## 2.740.0
* bugfix: TypeScript type definitions: Deep imports of clients no longer reference entire SDK type definitions
* feature: Appflow: Amazon AppFlow is a fully managed integration service that securely transfers data between AWS services and SaaS applications. This update releases the first version of Amazon AppFlow APIs and SDK.
* feature: Route53Resolver: Route 53 Resolver adds support for resolver query logs

## 2.739.0
* feature: DMS: Added new endpoint settings to include columns with Null and Empty value when using Kinesis and Kafka as target. Added a new endpoint setting to set maximum message size when using Kafka as target.
* feature: EC2: This release enables customers to use VPC prefix lists in their transit gateway route tables, and it adds support for Provisioned IOPS SSD (io2) EBS volumes.
* feature: IoTSiteWise: Add traversalDirection to ListAssociatedAssetsRequest and add portal status to ListPortalsResponse
* feature: Kafka: Add UpdateConfiguration and DeleteConfiguration operations.
* feature: SSM: Add string length constraints to OpsDataAttributeName and OpsFilterValue.
* feature: XRay: AWS X-Ray now supports tagging on sampling rules and groups.

## 2.738.0
* feature: ApiGatewayV2: Customers can now create Amazon API Gateway HTTP APIs that route requests to AWS AppConfig, Amazon EventBridge, Amazon Kinesis Data Streams, Amazon SQS, and AWS Step Functions.

## 2.737.0
* feature: IVS: Amazon Interactive Video Service (IVS) now offers customers the ability to create private channels, allowing customers to restrict their streams by channel or viewer.
* feature: LakeFormation: Adding additional field in ListPermissions API response to return RAM resource share ARN if a resource were shared through AWS RAM service.
* feature: ServiceCatalog: Enhance SearchProvisionedProducts API to allow queries using productName and provisioningArtifactName. Added lastProvisioningRecordId and lastSuccessfulRecordId to Read ProvisionedProduct APIs
* feature: StorageGateway: Added WORM, tape retention lock, and custom pool features for virtual tapes.

## 2.736.0
* feature: CognitoIdentityServiceProvider: Adding the option to use a service linked role to publish events to Pinpoint.
* feature: DataSync: DataSync support for filters as input arguments to the ListTasks and ListLocations API calls.
* feature: IdentityStore: AWS Single Sign-On (SSO) Identity Store service provides an interface to retrieve all of your users and groups. It enables entitlement management per user or group for AWS SSO and other IDPs.
* feature: SESV2: This release includes new APIs to allow customers to add or remove email addresses from their account-level suppression list in bulk.
* feature: SecurityHub: New details for DynamoDB tables, Elastic IP addresses, IAM policies and users, RDS DB clusters and snapshots, and Secrets Manager secrets. Added details for AWS KMS keys and RDS DB instances.

## 2.735.0
* feature: ACM: ACM provides support for the new Private CA feature Cross-account CA sharing. ACM users can issue certificates signed by a private CA belonging to another account where the CA was shared with them.
* feature: ACMPCA: ACM Private CA is launching cross-account support. This allows customers to share their private CAs with other accounts, AWS Organizations, and organizational units to issue end-entity certificates.
* feature: ECR: This feature adds support for pushing and pulling Open Container Initiative (OCI) artifacts.
* feature: Kinesis: Updates API to latest version.
* feature: QuickSight: Amazon QuickSight now supports programmatic creation and management of analyses with new APIs.
* feature: RoboMaker: This release introduces RoboMaker Simulation WorldForge, a capability that automatically generates one or more simulation worlds.

## 2.734.0
* bugfix: ErrorParser: fix UnknownEndpoint exception not thrown in Node14(#3393)
* feature: AppStream: Adds support for the Desktop View feature
* feature: Braket: Fixing bug in our SDK model where device status and device type had been flipped.
* feature: EC2: New C5ad instances featuring AMD's 2nd Generation EPYC processors, offering up to 96 vCPUs, 192 GiB of instance memory, 3.8 TB of NVMe based SSD instance storage, and 20 Gbps in Network bandwidth
* feature: SageMaker: Amazon SageMaker now supports 1) creating real-time inference endpoints using model container images from Docker registries in customers' VPC 2) AUC(Area under the curve) as AutoPilot objective metric

## 2.733.0
* feature: Braket: Amazon Braket general availability with Device and Quantum Task operations.
* feature: CognitoIdentityServiceProvider: Adding ability to customize expiry for Refresh, Access and ID tokens.
* feature: EC2: Added MapCustomerOwnedIpOnLaunch and CustomerOwnedIpv4Pool to ModifySubnetAttribute to allow CoIP auto assign. Fields are returned in DescribeSubnets and DescribeNetworkInterfaces responses.
* feature: EKS: Adding support for customer provided EC2 launch templates and AMIs to EKS Managed Nodegroups. Also adds support for Arm-based instances to EKS Managed Nodegroups.
* feature: RDS: This release allows customers to specify a replica mode when creating or modifying a Read Replica, for DB engines which support this feature.

## 2.732.0
* feature: Cloud9: Add ConnectionType input parameter to CreateEnvironmentEC2 endpoint. New parameter enables creation of environments with SSM connection.
* feature: Comprehend: Amazon Comprehend Custom Entity Recognition now supports Spanish, German, French, Italian and Portuguese and up to 25 entity types per model.
* feature: EC2: Introduces support for IPv6-in-IPv4 IPsec tunnels. A user can now send traffic from their on-premise IPv6 network to AWS VPCs that have IPv6 support enabled.
* feature: FSx: This release adds the capability to create persistent file systems for throughput-intensive workloads using Hard Disk Drive (HDD) storage and an optional read-only Solid-State Drive (SSD) cache.
* feature: Iot: Audit finding suppressions: Device Defender enables customers to turn off non-compliant findings for specific resources on a per check basis.
* feature: Lambda: Support for creating Lambda Functions using 'java8.al2' and 'provided.al2'
* feature: Transfer: Adds security policies to control cryptographic algorithms advertised by your server, additional characters in usernames and length increase, and FIPS compliant endpoints in the US and Canada regions.
* feature: WorkSpaces: Adds optional EnableWorkDocs property to WorkspaceCreationProperties in the ModifyWorkspaceCreationProperties API

## 2.731.0
* feature: EC2: This release rolls back the EC2 On-Demand Capacity Reservations (ODCRs) release 1.11.831 published on 2020-07-30, which was deployed in error.
* feature: Lambda: Support Managed Streaming for Kafka as an Event Source. Support retry until record expiration for Kinesis and Dynamodb streams event source mappings.
* feature: S3: Add support for in-region CopyObject and UploadPartCopy through S3 Access Points

## 2.730.0
* feature: EC2: Remove CoIP Auto-Assign feature references.
* feature: Glue: Starting today, you can further control orchestration of your ETL workloads in AWS Glue by specifying the maximum number of concurrent runs for a Glue workflow.
* feature: SavingsPlans: Updates to the list of services supported by this API.

## 2.729.0
* feature: Glue: AWS Glue now adds support for Network connection type enabling you to access resources inside your VPC using Glue crawlers and Glue ETL jobs.
* feature: Organizations: Documentation updates for some new error reasons.
* feature: S3: Updates Amazon S3 API reference documentation. 
* feature: SMS: In this release, AWS Server Migration Service (SMS) has added new features: 1. APIs to work with application and instance level validation 2. Import application catalog from AWS Application Discovery Service 3. For an application you can start on-demand replication

## 2.728.0
* feature: EC2: This release supports Wavelength resources, including carrier gateways, and carrier IP addresses.
* feature: LexModelBuildingService: Amazon Lex supports the option to enable accuracy improvements and specify an intent classification confidence score threshold.
* feature: LexRuntime: Amazon Lex supports intent classification confidence scores along with a list of the top five intents.
* feature: Personalize: Add 'exploration' functionality
* feature: PersonalizeEvents: Adds support implicit and explicit impression input
* feature: PersonalizeRuntime: Adds support for implicit impressions

## 2.727.1
* bugfix: docs: Add awsdocs-legal-zone-copyright div

## 2.727.0
* feature: AppSync: AWS AppSync releases support for Direct Lambda Resolvers.
* feature: TranscribeService: Amazon Transcribe now supports custom language models, which can improve transcription accuracy for your specific use case.

## 2.726.0
* feature: SSM: Adds a waiter for CommandExecuted and paginators for various other APIs.

## 2.725.0
* feature: Chime: This release increases the CreateMeetingWithAttendee max attendee limit to 10.
* feature: PersonalizeRuntime: Adds support to use filters with Personalized Ranking recipe
* feature: StorageGateway: Add support for gateway VM deprecation dates
* feature: WAFV2: Add ManagedByFirewallManager flag to the logging configuration, which indicates whether AWS Firewall Manager controls the configuration.

## 2.724.0
* feature: CodeBuild: Adding support for BuildBatch, and CodeCoverage APIs. BuildBatch allows you to model your project environment in source, and helps start multiple builds with a single API call. CodeCoverage allows you to track your code coverage using AWS CodeBuild. 
* feature: EC2: EC2 On-Demand Capacity Reservations now adds support to bring your own licenses (BYOL) of Windows operating system to launch EC2 instances. 
* feature: GuardDuty: GuardDuty can now provide detailed cost metrics broken down by account, data source, and S3 resources, based on the past 30 days of usage.  This new feature also supports viewing cost metrics for all member accounts as a GuardDuty master.
* feature: Kafka: Amazon MSK has added a new API that allows you to reboot brokers within a cluster. 
* feature: SESV2: This release makes more API operations available to customers in version 2 of the Amazon SES API. With these additions, customers can now access sending authorization, custom verification email, and template API operations.  With this release, Amazon SES is also providing new and updated APIs to allow customers to request production access.
* feature: ServiceCatalog: This release adds support for ProvisionProduct, UpdateProvisionedProduct & DescribeProvisioningParameters by product name, provisioning artifact name and path name. In addition DescribeProvisioningParameters now returns a list of provisioning artifact outputs.

## 2.723.0
* feature: EC2: Adding support to target EC2 On-Demand Capacity Reservations within an AWS Resource Group to launch EC2 instances.
* feature: ECR: This release adds support for encrypting the contents of your Amazon ECR repository with customer master keys (CMKs) stored in AWS Key Management Service.
* feature: Firehose: This release includes a new Kinesis Data Firehose feature that supports data delivery to Https endpoint and to partners. You can now use Kinesis Data Firehose to ingest real-time data and deliver to Https endpoint and partners in a serverless, reliable, and salable manner.
* feature: GuardDuty: GuardDuty now supports S3 Data Events as a configurable data source type. This feature expands GuardDuty's monitoring scope to include S3 data plane operations, such as GetObject and PutObject. This data source is optional and can be enabled or disabled at anytime. Accounts already using GuardDuty must first enable the new feature to use it; new accounts will be enabled by default. GuardDuty masters can configure this data source for individual member accounts and GuardDuty masters associated through AWS Organizations can automatically enable the data source in member accounts.
* feature: ResourceGroups: Resource Groups released a new feature that enables you to create a group with an associated configuration that specifies how other AWS services interact with the group. There are two new operations `GroupResources` and `UngroupResources` to work on a group with a configuration. In this release, you can associate EC2 Capacity Reservations with a resource group. Resource Groups also added a new request parameter `Group` to replace `GroupName` for all existing operations.
* feature: ServiceDiscovery: Added new attribute AWS_EC2_INSTANCE_ID for RegisterInstance API 

## 2.722.0
* feature: AutoScaling: Now you can enable Instance Metadata Service Version 2 (IMDSv2) or disable the instance metadata endpoint with Launch Configurations.
* feature: EC2: Introduces support for tag-on-create capability for the following APIs: CreateVpnConnection, CreateVpnGateway, and CreateCustomerGateway. A user can now add tags while creating these resources. For further detail, please see AWS Tagging Strategies.
* feature: IVS: Added a new error code, PendingVerification, to differentiate between errors caused by insufficient IAM permissions and errors caused by account verification.
* feature: Imagebuilder: This release updates distribution configurations to allow periods in AMI names.
* feature: MediaLive: AWS Elemental MediaLive now supports several new features: EBU-TT-D captions in Microsoft Smooth outputs; interlaced video in HEVC outputs; video noise reduction (using temporal filtering) in HEVC outputs.
* feature: RDS: Adds reporting of manual cluster snapshot quota to DescribeAccountAttributes API
* feature: SecurityHub: Added UpdateSecurityHubConfiguration API. Security Hub now allows customers to choose whether to automatically enable new controls that are added to an existing standard that the customer enabled. For example, if you enabled Foundational Security Best Practices for an account, you can automatically enable new controls as we add them to that standard. By default, new controls are enabled.

## 2.721.0
* bugfix: Region: Add region validation using DNS Host label regex
* feature: DMS: Basic endpoint settings for relational databases, Preflight validation API.
* feature: DataSync: Today AWS DataSync releases support for self-managed object storage Locations and the new TransferMode Option.
* feature: EC2: m6gd, c6gd, r6gd instances are powered by AWS Graviton2 processors and support local NVMe instance storage
* feature: FraudDetector: Moved the eventTypeName attribute for PutExternalModel API to inputConfiguration. Model ID's no longer allow hyphens.
* feature: Glue: Add ability to manually resume workflows in AWS Glue providing customers further control over the orchestration of ETL workloads.

## 2.720.0
* feature: CloudWatch: AWS CloudWatch ListMetrics now supports an optional parameter (RecentlyActive) to filter results by only metrics that have received new datapoints in the past 3 hours. This enables more targeted metric data retrieval through the Get APIs
* feature: FraudDetector: GetPrediction has been replaced with GetEventPrediction. PutExternalModel has been simplified to accept a role ARN.
* feature: Kendra: Amazon Kendra now supports sorting query results based on document attributes. Amazon Kendra also introduced an option to enclose table and column names with double quotes for database data sources. 
* feature: MQ: Amazon MQ now supports LDAP (Lightweight Directory Access Protocol), providing authentication and authorization of Amazon MQ users via a customer designated LDAP server.
* feature: Macie2: This release of the Amazon Macie API introduces additional criteria for sorting and filtering query results for account quotas and usage statistics.
* feature: MediaConnect: You can now disable an entitlement to stop streaming content to the subscriber's flow temporarily. When you are ready to allow content to start streaming to the subscriber's flow again, you can enable the entitlement.
* feature: MediaPackage: The release adds daterange as a new ad marker option. This option enables MediaPackage to insert EXT-X-DATERANGE tags in HLS and CMAF manifests. The EXT-X-DATERANGE tag is used to signal ad and program transition events.
* feature: SageMaker: Sagemaker Ground Truth:Added support for OIDC (OpenID Connect) to authenticate workers via their own identity provider instead of through Amazon Cognito. This release adds new APIs (CreateWorkforce, DeleteWorkforce, and ListWorkforces) to SageMaker Ground Truth service.  Sagemaker Neo: Added support for detailed target device description by using TargetPlatform fields - OS, architecture, and accelerator. Added support for additional compilation parameters by using JSON field CompilerOptions.  Sagemaker Search: SageMaker Search supports transform job details in trial components.

## 2.719.0
* feature: ConfigService: Adding service linked configuration aggregation support along with new enums for config resource coverage
* feature: FSx: Adds support for AutoImport, a new FSx for Lustre feature that allows customers to configure their FSx file system to automatically update its contents when new objects are added to S3 or existing objects are overwritten.
* feature: Glue: Added new ConnectionProperties: "KAFKA_SSL_ENABLED" (to toggle SSL connections) and "KAFKA_CUSTOM_CERT" (import CA certificate file)
* feature: Lightsail: This release adds support for Amazon Lightsail content delivery network (CDN) distributions and SSL/TLS certificates.
* feature: WorkSpaces: Added UpdateWorkspaceImagePermission API to share Amazon WorkSpaces images across AWS accounts.

## 2.718.0
* bugfix: S3: Add validation for AccountId in S3 AccessPoint
* feature: MediaLive: The AWS Elemental MediaLive APIs and SDKs now support the ability to get thumbnails for MediaLive devices that are attached or not attached to a channel. Previously, this thumbnail feature was available only on the console.
* feature: QuickSight: New API operations - GetSessionEmbedUrl, CreateNamespace, DescribeNamespace, ListNamespaces, DeleteNamespace, DescribeAccountSettings, UpdateAccountSettings, CreateAccountCustomization, DescribeAccountCustomization, UpdateAccountCustomization, DeleteAccountCustomization. Modified API operations to support custom permissions restrictions - RegisterUser, UpdateUser, UpdateDashboardPermissions

## 2.717.0
* feature: CodeGuruProfiler: Amazon CodeGuru Profiler now supports resource tagging APIs, tags-on-create and tag-based access control features. You can now tag profiling groups for better resource and access control management.

## 2.716.0
* feature: CloudFront: CloudFront adds support for cache policies and origin request policies. With these new policies, you can now more granularly control the query string, header, and cookie values that are included in the cache key and in requests that CloudFront sends to your origin.
* feature: CodeBuild: AWS CodeBuild adds support for Session Manager and Windows 2019 Environment type
* feature: EC2: Added support for tag-on-create for CreateVpcPeeringConnection and CreateRouteTable. You can now specify tags when creating any of these resources. For more information about tagging, see AWS Tagging Strategies. Add poolArn to the response of DescribeCoipPools.
* feature: FMS: Added managed policies for auditing security group rules, including the use of managed application and protocol lists.
* feature: FraudDetector: Introduced flexible model training dataset requirements for Online Fraud Insights so that customers can choose any two inputs to train a model instead of being required to use 'email' and 'IP address' at minimum. Added support for resource ARNs, resource tags, resource-based IAM policies and identity-based policies that limit access to a resource based on tags. Added support for customer-managed customer master key (CMK) data encryption. Added new Event Type, Entity Type, and Label APIs. An event type defines the structure for an event sent to Amazon Fraud Detector, including the variables sent as part of the event, the entity performing the event, and the labels that classify the event. Introduced the GetEventPrediction API.
* feature: GroundStation: Adds optional MTU property to DataflowEndpoint and adds contact source and destination details to DescribeContact response.
* feature: RDS: Add a new SupportsParallelQuery output field to DescribeDBEngineVersions. This field shows whether the engine version supports parallelquery. Add a new SupportsGlobalDatabases output field to DescribeDBEngineVersions and DescribeOrderableDBInstanceOptions. This field shows whether global database is supported by engine version or the combination of engine version and instance class.

## 2.715.0
* bugfix: Types: Export missing TokenFileWebIdentityCredentials class
* feature: Connect: This release adds a set of Amazon Connect APIs to programmatically control call recording with start, stop, pause and resume functions.
* feature: EC2: Documentation updates for EC2
* feature: ElasticBeanstalk: Add waiters for `EnvironmentExists`, `EnvironmentUpdated`, and `EnvironmentTerminated`. Add paginators for `DescribeEnvironmentManagedActionHistory` and `ListPlatformVersions`.
* feature: Macie2: This release of the Amazon Macie API includes miscellaneous updates and improvements to the documentation.

## 2.714.2
* bugfix: Releasing: remove aws-sdk-2.714.0.tgz file

## 2.714.1
* bugfix: Logger: Fix the bug that SDK logs the sensitive data in structure, map, and list parameters

## 2.714.0
* feature: IVS: Introducing Amazon Interactive Video Service - a managed live streaming solution that is quick and easy to set up, and ideal for creating interactive video experiences.

## 2.713.0
* feature: AlexaForBusiness: Added support for registering an AVS device directly to a room using RegisterAVSDevice with a room ARN
* feature: AppMesh: AppMesh now supports Ingress which allows resources outside a mesh to communicate to resources that are inside the mesh. See https://docs.aws.amazon.com/app-mesh/latest/userguide/virtual_gateways.html
* feature: CloudWatchEvents: Amazon CloudWatch Events/EventBridge adds support for API Gateway as a target.
* feature: Comprehend: AWS Comprehend now supports Real-time Analysis with Custom Entity Recognition. 
* feature: EBS: This release introduces the following set of actions for the EBS direct APIs: 1. StartSnapshot, which creates a new Amazon EBS snapshot. 2. PutSnapshotBlock, which writes a block of data to a snapshot. 3. CompleteSnapshot, which seals and completes a snapshot after blocks of data have been written to it.
* feature: EventBridge: Amazon EventBridge adds support for API Gateway as a target.
* feature: SNS: This release adds support for SMS origination number as an attribute in the MessageAttributes parameter for the SNS Publish API.
* feature: SageMaker: This release adds the DeleteHumanTaskUi API to Amazon Augmented AI
* feature: SecretsManager: Adds support for filters on the ListSecrets API to allow filtering results by name, tag key, tag value, or description.  Adds support for the BlockPublicPolicy option on the PutResourcePolicy API to block resource policies which grant a wide range of IAM principals access to secrets. Adds support for the ValidateResourcePolicy API to validate resource policies for syntax and prevent lockout error scenarios and wide access to secrets. 
* feature: WAFV2: Added the option to use IP addresses from an HTTP header that you specify, instead of using the web request origin. Available for IP set matching, geo matching, and rate-based rule count aggregation.

## 2.712.0
* feature: CostExplorer: Customers can now see Instance Name alongside each rightsizing recommendation.
* feature: EC2: EC2 Spot now enables customers to tag their Spot Instances Requests on creation.
* feature: ForecastService: With this release, Amazon Forecast now supports the ability to add a tag to any resource via the launch of three new APIs: TagResouce, UntagResource and ListTagsForResource. A tag is a simple label consisting of a customer-defined key and an optional value allowing for easier resource management.
* feature: Organizations: We have launched a self-service option to make it easier for customers to manage the use of their content by AI services. Certain AI services (Amazon CodeGuru Profiler, Amazon Comprehend, Amazon Lex, Amazon Polly, Amazon Rekognition, Amazon Textract, Amazon Transcribe, and Amazon Translate), may use content to improve the service. Customers have been able to opt out of this use by contacting AWS Support, and now they can opt out on a self-service basis by setting an Organizations policy for all or an individual AI service as listed above. Please refer to the technical documentation for more details.

## 2.711.0
* feature: CloudFront: Amazon CloudFront adds support for a new security policy, TLSv1.2_2019.
* feature: EC2: DescribeAvailabilityZones now returns additional data about Availability Zones and Local Zones.
* feature: EFS: This release adds support for automatic backups of Amazon EFS file systems to further simplify backup management. 
* feature: Glue: AWS Glue Data Catalog supports cross account sharing of tables through AWS Lake Formation
* feature: LakeFormation:  AWS Lake Formation supports sharing tables with other AWS accounts and organizations
* feature: StorageGateway: Adding support for file-system driven directory refresh, Case Sensitivity toggle for SMB File Shares, and S3 Prefixes and custom File Share names

## 2.710.0
* feature: IoTSiteWise: This release supports optional start date and end date parameters for the GetAssetPropertyValueHistory API.
* feature: QuickSight: Add Theme APIs and update Dashboard APIs to support theme overrides.
* feature: RDS: Adds support for Amazon RDS on AWS Outposts.

## 2.709.0
* bugfix: S3: Fixed a bug where S3 client throws when client config is undefined and Bucket is an AccessPoint ARN
* feature: AppSync: AWS AppSync supports new 12xlarge instance for server-side API caching
* feature: Chime: This release supports third party emergency call routing configuration for Amazon Chime Voice Connectors.
* feature: CodeBuild: Support build status config in project source
* feature: Imagebuilder: EC2 Image Builder adds support for encrypted AMI distribution.
* feature: RDS: This release adds the exceptions KMSKeyNotAccessibleFault and InvalidDBClusterStateFault to the Amazon RDS ModifyDBInstance API.
* feature: SecurityHub: This release adds additional details for findings. There are now finding details for auto scaling groups, EC2 volumes, and EC2 VPCs. You can identify detected vulnerabilities and provide related network paths.

## 2.708.0
* feature: CodeGuruReviewer: Release GitHub Enterprise Server source provider integration
* feature: ComprehendMedical: This release adds the relationships between MedicalCondition and Anatomy in DetectEntitiesV2 API.
* feature: EC2: Added support for tag-on-create for CreateVpc, CreateEgressOnlyInternetGateway, CreateSecurityGroup, CreateSubnet, CreateNetworkInterface, CreateNetworkAcl, CreateDhcpOptions and CreateInternetGateway. You can now specify tags when creating any of these resources. For more information about tagging, see AWS Tagging Strategies.
* feature: ECR: Add a new parameter (ImageDigest) and a new exception (ImageDigestDoesNotMatchException) to PutImage API to support pushing image by digest.

## 2.707.0
* feature: CodeGuruProfiler: Amazon CodeGuru Profiler is now generally available. The Profiler helps developers to optimize their software, troubleshoot issues in production, and identify their most expensive lines of code. As part of general availability, we are launching: Profiling of AWS Lambda functions, Anomaly detection in CPU profiles, Color My Code on flame graphs, Expanding presence to 10 AWS regions.
* feature: CodeStarconnections: Updated and new APIs in support of hosts for connections to installed provider types. New integration with the GitHub Enterprise Server provider type.
* feature: EC2: Virtual Private Cloud (VPC) customers can now create and manage their own Prefix Lists to simplify VPC configurations.

## 2.706.0
* feature: CloudFormation: ListStackInstances and DescribeStackInstance now return a new `StackInstanceStatus` object that contains `DetailedStatus` values: a disambiguation of the more generic `Status` value. ListStackInstances output can now be filtered on `DetailedStatus` using the new `Filters` parameter.
* feature: CognitoIdentityServiceProvider: Don't require Authorization for InitiateAuth and RespondToAuthChallenge.
* feature: QuickSight: Added support for cross-region DataSource credentials copying.
* feature: SageMaker: The new 'ModelClientConfig' parameter being added for CreateTransformJob and DescribeTransformJob api actions enable customers to configure model invocation related parameters such as timeout and retry.

## 2.705.0
* feature: EC2: Added support for tag-on-create for Host Reservations in Dedicated Hosts. You can now specify tags when you create a Host Reservation for a Dedicated Host. For more information about tagging, see AWS Tagging Strategies.
* feature: Glue: This release adds new APIs to support column level statistics in AWS Glue Data Catalog

## 2.704.0
* feature: Amplify: This release of AWS Amplify Console introduces support for automatically creating custom subdomains for branches based on user-defined glob patterns, as well as automatically cleaning up Amplify branches when their corresponding git branches are deleted.
* feature: Backup: Customers can now manage and monitor their backups in a policied manner across their AWS accounts, via an integration between AWS Backup and AWS Organizations
* feature: CodeCommit: This release introduces support for reactions to CodeCommit comments. Users will be able to select from a pre-defined list of emojis to express their reaction to any comments.
* feature: EMR: Amazon EMR customers can now set allocation strategies for On-Demand and Spot instances in their EMR clusters with instance fleets. These allocation strategies use real-time capacity insights to provision clusters faster and make the most efficient use of available spare capacity to allocate Spot instances to reduce interruptions. 
* feature: FSx: This release adds the capability to take highly-durable, incremental backups of your FSx for Lustre persistent file systems. This capability makes it easy to further protect your file system data and to meet business and regulatory compliance requirements.
* feature: Honeycode: Introducing Amazon Honeycode - a fully managed service that allows you to quickly build mobile and web apps for teams without programming.
* feature: Organizations: This release adds support for a new backup policy type for AWS Organizations.

## 2.703.0
* feature: MediaTailor: AWS Elemental MediaTailor SDK now allows configuration of Bumper.
* feature: Organizations: Added a new error message to support the requirement for a Business License on AWS accounts in China to create an organization.

## 2.702.0
* bugfix: EFS: Check for ValidationException in integration tests
* feature: EC2: This release adds Tag On Create feature support for the ImportImage, ImportSnapshot, ExportImage and CreateInstanceExportTask APIs.
* feature: EMR: Adding support for MaximumCoreCapacityUnits parameter for EMR Managed Scaling. It allows users to control how many units/nodes are added to the CORE group/fleet. Remaining units/nodes are added to the TASK groups/fleet in the cluster.
* feature: RDS: Added paginators for various APIs.
* feature: Rekognition: This update adds the ability to detect black frames, end credits, shots, and color bars in stored videos
* feature: SQS: AWS SQS adds pagination support for ListQueues and ListDeadLetterSourceQueues APIs

## 2.701.0
* bugfix: Request Signing: Better handle colons in accessKeyIds when presigning URLs.
* feature: EC2: Adds support to tag elastic-gpu on the RunInstances api
* feature: MediaLive: AWS Elemental MediaLive now supports Input Prepare schedule actions. This feature improves existing input switching by allowing users to prepare an input prior to switching to it.
* feature: OpsWorksCM: Documentation updates for AWS OpsWorks CM.

## 2.700.0
* feature: RDS: Adding support for global write forwarding on secondary clusters in an Aurora global database.
* feature: Route53: Added a new ListHostedZonesByVPC API for customers to list all the private hosted zones that a specified VPC is associated with.
* feature: SESV2: You can now configure Amazon SES to send event notifications when the delivery of an email is delayed because of a temporary issue. For example, you can receive a notification if the recipient's inbox is full, or if there's a temporary problem with the receiving email server.
* feature: SSM: Added offset support for specifying the number of days to wait after the date and time specified by a CRON expression before running the maintenance window.

## 2.699.0
* bugfix: Global Services: Add default signing region for IAM and Route53 in China and GovCloud
* feature: AppMesh: Adds support for route and virtual node listener timeouts.
* feature: EC2: nvmeSupport added to DescribeInstanceTypes API
* feature: Route53: Add PriorRequestNotComplete exception to AssociateVPCWithHostedZone API
* feature: Snowball: AWS Snowcone is a portable, rugged and secure device for edge computing and data transfer. You can use Snowcone to collect, process, and move data to AWS, either offline by shipping the device to AWS or online by using AWS DataSync. With 2 CPUs and 4 GB RAM of compute and 8 TB of storage, Snowcone can run edge computing workloads and store data securely. Snowcone's small size (8.94" x 5.85" x 3.25" / 227 mm x 148.6 mm x 82.65 mm) allows you to set it next to machinery in a factory. Snowcone weighs about 4.5 lbs. (2 kg), so you can carry one in a backpack, use it with battery-based operation, and use the Wi-Fi interface to gather sensor data. Snowcone supports a file interface with NFS support. 

## 2.698.0
* feature: AutoScaling: Introducing instance refresh, a feature that helps you update all instances in an Auto Scaling group in a rolling fashion (for example, to apply a new AMI or instance type). You can control the pace of the refresh by defining the percentage of the group that must remain running/healthy during the replacement process and the time for new instances to warm up between replacements.
* feature: DataExchange: This release fixes a bug in the AWS Data Exchange Python and NodeJS SDKs. The 'KmsKeyArn' field in the create-job API was configured to be required instead of optional. We updated this field to be optional in this release.
* feature: Lambda: Adds support for using Amazon Elastic File System (persistent storage) with AWS Lambda. This enables customers to share data across function invocations, read large reference data files, and write function output to a persistent and shared store.
* feature: Polly: Amazon Polly adds new US English child voice - Kevin. Kevin is available as Neural voice only.

## 2.697.0
* feature: AlexaForBusiness: Adding support for optional tags in CreateBusinessReportSchedule, CreateProfile and CreateSkillGroup APIs
* feature: AppConfig: This release adds a hosted configuration source provider. Customers can now store their application configurations directly in AppConfig, without the need for an external configuration source.
* feature: Chime: feature: Chime: This release introduces the ability to create an AWS Chime SDK meeting with attendees.
* feature: CognitoIdentityServiceProvider: Updated all AuthParameters to be sensitive.
* feature: Iot: Added support for job executions rollout configuration, job abort configuration, and job executions timeout configuration for AWS IoT Over-the-Air (OTA) Update Feature.

## 2.696.0
* feature: Glue: You can now choose to crawl the entire table or just a sample of records in DynamoDB when using AWS Glue crawlers. Additionally, you can also specify a scanning rate for crawling DynamoDB tables.
* feature: StorageGateway: Display EndpointType in DescribeGatewayInformation

## 2.695.0
* feature: ECS: This release adds support for deleting capacity providers.
* feature: Imagebuilder: EC2 Image Builder now supports specifying a custom working directory for your build and test workflows. In addition, Image Builder now supports defining tags that are applied to ephemeral resources created by EC2 Image Builder as part of the image creation workflow. 
* feature: IotData: As part of this release, we are introducing a new feature called named shadow, which extends the capability of AWS IoT Device Shadow to support multiple shadows for a single IoT device. With this release, customers can store different device state data into different shadows, and as a result access only the required state data when needed and reduce individual shadow size.
* feature: LexModelBuildingService: This change adds the built-in AMAZON.KendraSearchIntent that enables integration with Amazon Kendra.

## 2.694.0
* feature: AppConfig: This release allows customers to choose from a list of predefined deployment strategies while starting deployments.
* feature: CodeArtifact: Added support for AWS CodeArtifact.
* feature: ComputeOptimizer: Compute Optimizer supports exporting recommendations to Amazon S3.
* feature: DLM: Reducing the schedule name of DLM Lifecycle policy from 500 to 120 characters. 
* feature: EC2: New C6g instances powered by AWS Graviton2 processors and ideal for running advanced, compute-intensive workloads; New R6g instances powered by AWS Graviton2 processors and ideal for running memory-intensive workloads.
* feature: Macie2: This release of the Amazon Macie API removes support for the ArchiveFindings and UnarchiveFindings operations. This release also adds UNKNOWN as an encryption type for S3 bucket metadata.
* feature: Shield: Corrections to the supported format for contact phone numbers and to the description for the create subscription action.

## 2.693.0
* feature: Transfer: This release updates the API so customers can test use of Source IP to allow, deny or limit access to data in their S3 buckets after integrating their identity provider.

## 2.692.0
* feature: ServiceDiscovery: Added support for tagging Service and Namespace type resources  in Cloud Map
* feature: Shield: This release adds the option for customers to identify a contact name and method that the DDoS Response Team can proactively engage when a Route 53 Health Check that is associated with a Shield protected resource fails.

## 2.691.0
* feature: APIGateway: Amazon API Gateway now allows customers of REST APIs to skip trust chain validation for backend server certificates for HTTP and VPC Link Integration. This feature enables customers to configure their REST APIs to integrate with backends that are secured with certificates vended from private certificate authorities (CA) or certificates that are self-signed.
* feature: CloudFront: Amazon CloudFront adds support for configurable origin connection attempts and origin connection timeout.
* feature: ElasticBeanstalk: These API changes enable an IAM user to associate an operations role with an Elastic Beanstalk environment, so that the IAM user can call Elastic Beanstalk actions without having access to underlying downstream AWS services that these actions call.
* feature: Personalize: [Personalize] Adds ability to create and apply filters.
* feature: PersonalizeRuntime: [Personalize] Adds ability to apply filter to real-time recommendations
* feature: Pinpoint: This release enables additional functionality for the Amazon Pinpoint journeys feature. With this release, you can send messages through additional channels, including SMS, push notifications, and custom channels.
* feature: SageMakerRuntime: You can now specify the production variant to send the inference request to, when invoking a SageMaker Endpoint that is running two or more variants.
* feature: ServiceCatalog: This release adds support for DescribeProduct and DescribeProductAsAdmin by product name, DescribeProvisioningArtifact by product name or provisioning artifact name, returning launch paths as part of DescribeProduct output and adds maximum length for provisioning artifact name and provisioning artifact description.

## 2.690.0
* feature: EC2: New C5a instances, the latest generation of EC2's compute-optimized instances featuring AMD's 2nd Generation EPYC processors. C5a instances offer up to 96 vCPUs, 192 GiB of instance memory, 20 Gbps in Network bandwidth; New G4dn.metal bare metal instance with 8 NVIDIA T4 GPUs.
* feature: Lightsail: This release adds the BurstCapacityPercentage and BurstCapacityTime instance metrics, which allow you to track the burst capacity available to your instance.
* feature: MediaPackageVod: You can now restrict direct access to AWS Elemental MediaPackage by securing requests for VOD content using CDN authorization. With CDN authorization, content requests require a specific HTTP header and authorization code.
* feature: SSM: SSM State Manager support for executing an association only at specified CRON schedule after creating/updating an association.

## 2.689.0
* feature: DirectConnect: This release supports the virtual interface failover test, which allows you to verify that traffic routes over redundant virtual interfaces when you bring your primary virtual interface out of service.
* feature: ES: Amazon Elasticsearch Service now offers support for cross-cluster search, enabling you to perform searches, aggregations, and visualizations across multiple Amazon Elasticsearch Service domains with a single query or from a single Kibana interface. New feature includes the ability to setup connection, required to perform cross-cluster search, between domains using an approval workflow.
* feature: ElastiCache: This release improves the Multi-AZ feature in ElastiCache by adding a separate flag and proper validations.
* feature: Glue: Adding databaseName in the response for GetUserDefinedFunctions() API.
* feature: IAM: GenerateServiceLastAccessedDetails will now return ActionLastAccessed details for certain S3 control plane actions
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for the encoding of VP8 or VP9 video in WebM container with Vorbis or Opus audio.

## 2.688.0
* feature: GuardDuty: Amazon GuardDuty findings now include S3 bucket details under the resource section if an S3 Bucket was one of the affected resources

## 2.687.0
* feature: Athena: This release adds support for connecting Athena to your own Apache Hive Metastores in addition to the AWS Glue Data Catalog. For more information, please see https://docs.aws.amazon.com/athena/latest/ug/connect-to-data-source-hive.html
* feature: EMR: Amazon EMR now supports encrypting log files with AWS Key Management Service (KMS) customer managed keys.
* feature: FSx: New capabilities to update storage capacity and throughput capacity of your file systems, providing the flexibility to grow file storage and to scale up or down the available performance as needed to meet evolving storage needs over time.
* feature: KMS: AWS Key Management Service (AWS KMS): If the GenerateDataKeyPair or GenerateDataKeyPairWithoutPlaintext APIs are called on a CMK in a custom key store (origin == AWS_CLOUDHSM), they return an UnsupportedOperationException. If a call to UpdateAlias causes a customer to exceed the Alias resource quota, the UpdateAlias API returns a LimitExceededException.
* feature: SageMaker: We are releasing HumanTaskUiArn as a new parameter in CreateLabelingJob and RenderUiTemplate which can take an ARN for a system managed UI to render a task. 
* feature: WorkLink: Amazon WorkLink now supports resource tagging for fleets.

## 2.686.0
* feature: Kafka: New APIs for upgrading the Apache Kafka version of a cluster and to find out compatible upgrade paths
* feature: MarketplaceCatalog: AWS Marketplace Catalog now supports accessing initial change payloads with DescribeChangeSet operation.
* feature: WorkMail: This release adds support for Amazon WorkMail organization-level retention policies.

## 2.685.0
* feature: ELBv2: This release added support for HTTP/2 ALPN preference lists for Network Load Balancers

## 2.684.0
* feature: DLM: Allowing cron expression in the DLM policy creation schedule. 
* feature: EC2: ebsOptimizedInfo, efaSupported and supportedVirtualizationTypes added to DescribeInstanceTypes API
* feature: ElastiCache: Amazon ElastiCache now allows you to use resource based policies to manage access to operations performed on ElastiCache resources. Also, Amazon ElastiCache now exposes ARN (Amazon Resource Names) for ElastiCache resources such as Cache Clusters and Parameter Groups. ARNs can be used to apply IAM policies to ElastiCache resources.
* feature: QuickSight: Add DataSetArns to QuickSight DescribeDashboard API response.
* feature: SSM: The AWS Systems Manager GetOpsSummary API action now supports multiple OpsResultAttributes in the request. Currently, this feature only supports OpsResultAttributes with the following TypeNames: [AWS:EC2InstanceComputeOptimizer] or [AWS:EC2InstanceInformation, AWS:EC2InstanceComputeOptimizer]. These TypeNames can be used along with either or both of the following: [AWS:EC2InstanceRecommendation, AWS:RecommendationSource]

## 2.683.0
* bugfix: DualStack: Add dualstack by modifying existing endpoint in config
* bugfix: EndpointDiscovery: * If at least one operation requires endpoint discovery then the SDK enables endpoint discovery by default including operational endpoint discovery operations; * Users can set config `endpointDiscoveryEnabled`, env `AWS_ENDPOINT_DISCOVERY_ENABLED`, config file entry `endpoint_discovery_enabled` to `false` to explictly disable endpoint discovery, even operations the require endpoint discovery will fail; * SDK throws if endpoint discovery is explicitly disabled but operation requires endpoint discovery; * Now SDK throws more clear error message when required endpoint operation fails
* bugfix: S3: throw exception when incomplete body is returned from CopyObject, UploadPartCopy, and CompleteMultipartUpload
* feature: IoTSiteWise: This release adds support for the standard deviation auto-computed aggregate and improved support for portal logo images in SiteWise.

## 2.682.0
* bugfix: Typings: When implementing `Credentials` interface's `refresh()` method, the callback needs a defined `AWSError` as arg but it may not exist in case of successful refresh. Hence, modifed the method typing to include the fact that the callback can be called with no error on success as described in the docs.
* feature: CodeBuild: CodeBuild adds support for tagging with report groups
* feature: EC2: From this release onwards ProvisionByoipCidr publicly supports IPv6. Updated ProvisionByoipCidr API to support tags for public IPv4 and IPv6 pools. Added NetworkBorderGroup to the DescribePublicIpv4Pools response.
* feature: S3: Deprecates unusable input members bound to Content-MD5 header. Updates example and documentation.
* feature: Synthetics: AWS CloudWatch Synthetics now supports configuration of allocated memory for a canary.

## 2.681.0
* feature: AppMesh: List APIs for all resources now contain additional information: when a resource was created, last updated, and its current version number.
* feature: Backup: This release allows customers to enable or disable AWS Backup support for an AWS resource type. This release also includes new APIs, update-region-settings and describe-region-settings, which can be used to opt in to a specific resource type. For all current AWS Backup customers, the default settings enable support for EBS, EC2, StorageGateway, EFS, DDB and RDS resource types. 
* feature: Chime: Amazon Chime enterprise account administrators can now set custom retention policies on chat data in the Amazon Chime application.
* feature: CodeDeploy: Amazon ECS customers using application and network load balancers can use CodeDeploy BlueGreen hook to invoke a CloudFormation stack update. With this update you can view CloudFormation deployment and target details via existing APIs and use your stack Id to list or delete all deployments associated with the stack.
* feature: MediaLive: AWS Elemental MediaLive now supports the ability to ingest the content that is streaming from an AWS Elemental Link device: https://aws.amazon.com/medialive/features/link/. This release also adds support for SMPTE-2038 and input state waiters.
* feature: SecurityHub: For findings related to controls, the finding information now includes the reason behind the current status of the control. A new field for the findings original severity allows finding providers to use the severity values from the system they use to assign severity.

## 2.680.0
* feature: Chime: You can now receive Voice Connector call events through SNS or SQS.
* feature: EC2: This release adds support for Federated Authentication via SAML-2.0 in AWS ClientVPN.
* feature: Health: Feature: Health: AWS Health added a new field to differentiate Public events from Account-Specific events in the API request and response. Visit https://docs.aws.amazon.com/health/latest/APIReference/API_Event.html to learn more.

## 2.679.0
* feature: Chime: Amazon Chime now supports redacting chat messages.
* feature: EC2: This release changes the RunInstances CLI and SDK's so that if you do not specify a client token, a randomly generated token is used for the request to ensure idempotency.
* feature: ECS: This release adds support for specifying environment files to add environment variables to your containers.
* feature: QLDB: Amazon QLDB now supports Amazon Kinesis data streams. You can now emit QLDB journal data, via the new QLDB Streams feature, directly to Amazon Kinesis supporting event processing and analytics among related use cases.

## 2.678.0
* feature: CloudFormation: This release adds support for the following features: 1. DescribeType and ListTypeVersions APIs now output a field IsDefaultVersion, indicating if a version is the default version for its type; 2. Add StackRollbackComplete waiter feature to wait until stack status is UPDATE_ROLLBACK_COMPLETE; 3. Add paginators in DescribeAccountLimits, ListChangeSets, ListStackInstances, ListStackSetOperationResults, ListStackSetOperations, ListStackSets APIs.
* feature: ECR: This release adds support for specifying an image manifest media type when pushing a manifest to Amazon ECR.
* feature: Glue: Starting today, you can stop the execution of Glue workflows that are running. AWS Glue workflows are directed acyclic graphs (DAGs) of Glue triggers, crawlers and jobs. Using a workflow, you can design a complex multi-job extract, transform, and load (ETL) activity that AWS Glue can execute and track as single entity. 
* feature: STS: API updates for STS

## 2.677.0
* feature: EC2: Amazon EC2 now supports adding AWS resource tags for associations between VPCs and local gateways, at creation time.
* feature: Imagebuilder: This release adds a new parameter (SupportedOsVersions) to the Components API. This parameter lists the OS versions supported by a component.

## 2.676.0
* feature: ElastiCache: Amazon ElastiCache now supports auto-update of ElastiCache clusters after the "recommended apply by date" of  service update has passed. ElastiCache will use your maintenance window to schedule the auto-update of applicable clusters. For more information, see https://docs.aws.amazon.com/AmazonElastiCache/latest/mem-ug/Self-Service-Updates.html and https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/Self-Service-Updates.html
* feature: Macie2: This release introduces a new major version of the Amazon Macie API. You can use this version of the API to develop tools and applications that interact with the new Amazon Macie.

## 2.675.0
* feature: WorkMail: Minor API fixes and updates to the documentation.

## 2.674.0
* feature: CodeGuruReviewer: Add Bitbucket integration APIs
* feature: EC2: M6g instances are our next-generation general purpose instances powered by AWS Graviton2 processors
* feature: Kendra: Amazon Kendra is now generally available. As part of general availability, we are launching * Developer edition * Ability to scale your Amazon Kendra index with capacity units * Support for new connectors * Support for new tagging API's * Support for Deleting data source * Metrics for data source sync operations * Metrics for query & storage utilization

## 2.673.0
* feature: SageMaker: This release adds a new parameter (EnableInterContainerTrafficEncryption) to CreateProcessingJob API to allow for enabling inter-container traffic encryption on processing jobs.

## 2.672.0
* feature: CloudWatchLogs: Amazon CloudWatch Logs now offers the ability to interact with Logs Insights queries via the new PutQueryDefinition, DescribeQueryDefinitions, and DeleteQueryDefinition APIs.
* feature: CodeBuild: Add COMMIT_MESSAGE enum for webhook filter types
* feature: EC2: Amazon EC2 now adds warnings to identify issues when creating a launch template or launch template version.
* feature: Lightsail: This release adds support for the following options in instance public ports: Specify source IP addresses, specify ICMP protocol like PING, and enable/disable the Lightsail browser-based SSH and RDP clients' access to your instance.
* feature: Route53: Amazon Route 53 now supports the EU (Milan) Region (eu-south-1) for latency records, geoproximity records, and private DNS for Amazon VPCs in that region.
* feature: SSM: This Patch Manager release supports creating patch baselines for Oracle Linux and Debian

## 2.671.0
* feature: CodeStarconnections: Added support for tagging resources in AWS CodeStar Connections
* feature: ComprehendMedical: New Batch Ontology APIs for ICD-10 and RxNorm will provide batch capability of linking the information extracted by Comprehend Medical to medical ontologies. The new ontology linking APIs make it easy to detect medications and medical conditions in unstructured clinical text and link them to RxNorm and ICD-10-CM codes respectively. This new feature can help you reduce the cost, time and effort of processing large amounts of unstructured medical text with high accuracy.

## 2.670.0
* feature: EC2: With this release, you can call ModifySubnetAttribute with two new parameters: MapCustomerOwnedIpOnLaunch and CustomerOwnedIpv4Pool, to map a customerOwnedIpv4Pool to a subnet. You will also see these two new fields in the DescribeSubnets response. If your subnet has a customerOwnedIpv4Pool mapped, your network interface will get an auto assigned customerOwnedIpv4 address when placed onto an instance.
* feature: SSM: AWS Systems Manager Parameter Store launches new data type to support aliases in EC2 APIs

## 2.669.0
* feature: EC2: With this release, you can include enriched metadata in Amazon Virtual Private Cloud (Amazon VPC) flow logs published to Amazon CloudWatch Logs or Amazon Simple Storage Service (S3). Prior to this, custom format VPC flow logs enriched with additional metadata could be published only to S3. With this launch, we are also adding additional metadata fields that provide insights about the location such as AWS Region, AWS Availability Zone, AWS Local Zone, AWS Wavelength Zone, or AWS Outpost where the network interface where flow logs are captured exists. 
* feature: S3Control: Amazon S3 Batch Operations now supports Object Lock.

## 2.668.0
* feature: EFS: Change the TagKeys argument for UntagResource to a URL parameter to address an issue with the Java and .NET SDKs.
* feature: SSM: Added TimeoutSeconds as part of ListCommands API response.

## 2.667.0
* feature: IoTEvents: Doc only update to correct APIs and related descriptions
* feature: Iot: AWS IoT Core released Fleet Provisioning for scalable onboarding of IoT devices to the cloud. This release includes support for customer's Lambda functions to validate devices during onboarding. Fleet Provisioning also allows devices to send Certificate Signing Requests (CSR) to AWS IoT Core for signing and getting a unique certificate. Lastly,  AWS IoT Core added a feature to register the same certificate for multiple accounts in the same region without needing to register the certificate authority (CA).
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for including AFD signaling in MXF wrapper.
* feature: Schemas: Add support for resource policies for Amazon EventBridge Schema Registry, which is now generally available.
* feature: StorageGateway: Adding support for S3_INTELLIGENT_TIERING as a storage class option

## 2.666.0
* feature: IoTSiteWise: AWS IoT SiteWise is a managed service that makes it easy to collect, store, organize and monitor data from industrial equipment at scale. You can use AWS IoT SiteWise to model your physical assets, processes and facilities, quickly compute common industrial performance metrics, and create fully managed web applications to help analyze industrial equipment data, prevent costly equipment issues, and reduce production inefficiencies.
* feature: TranscribeService: With this release, you can now use Amazon Transcribe to create medical custom vocabularies and use them in both medical real-time streaming and medical batch transcription jobs.
* feature: WAF: This release add migration API for AWS WAF Classic ("waf" and "waf-regional"). The migration API will parse through your web ACL and generate a CloudFormation template into your S3 bucket. Deploying this template will create equivalent web ACL under new AWS WAF ("wafv2").
* feature: WAFRegional: This release add migration API for AWS WAF Classic ("waf" and "waf-regional"). The migration API will parse through your web ACL and generate a CloudFormation template into your S3 bucket. Deploying this template will create equivalent web ACL under new AWS WAF ("wafv2").

## 2.665.0
* feature: ECR: This release adds support for multi-architecture images also known as a manifest list
* feature: KinesisVideo: Add "GET_CLIP" to the list of supported API names for the GetDataEndpoint API.
* feature: KinesisVideoArchivedMedia: Add support for the GetClip API for retrieving media from a video stream in the MP4 format.
* feature: MediaLive: AWS Elemental MediaLive now supports several new features: enhanced VQ for H.264 (AVC) output encodes; passthrough of timed metadata and of Nielsen ID3 metadata in fMP4 containers in HLS outputs; the ability to generate a SCTE-35 sparse track without additional segmentation, in Microsoft Smooth outputs;  the ability to select the audio from a TS input by specifying the audio track; and conversion of HDR colorspace in the input to an SDR colorspace in the output.
* feature: Route53: Amazon Route 53 now supports the Africa (Cape Town) Region (af-south-1) for latency records, geoproximity records, and private DNS for Amazon VPCs in that region.
* feature: SSM: SSM State Manager support for adding list association filter for Resource Group and manual mode of managing compliance for an association. 

## 2.664.0
* feature: AccessAnalyzer: This release adds support for inclusion of S3 Access Point policies in IAM Access Analyzer evaluation of S3 bucket access. IAM Access Analyzer now reports findings for buckets shared through access points and identifies the access point that permits access.
* feature: DMS: Adding minimum replication engine version for describe-endpoint-types api.
* feature: DataExchange: This release introduces AWS Data Exchange support for configurable encryption parameters when exporting data sets to Amazon S3. 
* feature: SageMaker: Change to the input, ResourceSpec, changing EnvironmentArn to SageMakerImageArn. This affects the following preview APIs: CreateDomain, DescribeDomain, UpdateDomain, CreateUserProfile, DescribeUserProfile, UpdateUserProfile, CreateApp and DescribeApp.

## 2.663.0
* feature: ElasticInference: This feature allows customers to describe the accelerator types and offerings on any region where Elastic Inference is available.
* feature: Iot: This release adds a new exception type to the AWS IoT SetV2LoggingLevel API.

## 2.662.0
* feature: ApplicationAutoScaling: This release supports Auto Scaling in Amazon Keyspaces for Apache Cassandra.
* feature: Firehose: You can now deliver streaming data to an Amazon Elasticsearch Service domain in an Amazon VPC. You can now compress streaming data delivered to S3 using Hadoop-Snappy in addition to Gzip, Zip and Snappy formats.
* feature: MediaPackageVod: Adds tagging support for PackagingGroups, PackagingConfigurations, and Assets
* feature: Pinpoint: This release of the Amazon Pinpoint API enhances support for sending campaigns through custom channels to locations such as AWS Lambda functions or web applications. Campaigns can now use CustomDeliveryConfiguration and CampaignCustomMessage to configure custom channel settings for a campaign.
* feature: RAM: AWS Resource Access Manager (RAM) provides a new ListResourceTypes action. This action lets you list the resource types that can be shared using AWS RAM.
* feature: RDS: Adds support for AWS Local Zones, including a new optional parameter AvailabilityZoneGroup for the DescribeOrderableDBInstanceOptions operation.
* feature: StorageGateway: Added AutomaticTapeCreation APIs
* feature: Transfer: This release adds support for transfers over FTPS and FTP in and out of Amazon S3, which makes it easy to migrate File Transfer Protocol over SSL (FTPS) and FTP workloads to AWS, in addition to the existing support for Secure File Transfer Protocol (SFTP).

## 2.661.0
* feature: CodeGuruReviewer: Add support for code review and recommendation feedback APIs.
* feature: ES: This change adds a new field 'OptionalDeployment' to ServiceSoftwareOptions to indicate whether a service software update is optional or mandatory. If True, it indicates that the update is optional, and the service software is not automatically updated. If False, the service software is automatically updated after AutomatedUpdateDate.
* feature: FMS: This release is to support AWS Firewall Manager policy with Organizational Unit scope. 
* feature: Redshift: Amazon Redshift support for usage limits

## 2.660.0
* feature: CostExplorer: Cost Explorer Rightsizing Recommendations integrates with Compute Optimizer and begins offering across instance family rightsizing recommendations, adding to existing support for within instance family rightsizing recommendations. 
* feature: EMR: Amazon EMR adds support for configuring a managed scaling policy for an Amazon EMR cluster. This enables automatic resizing of a cluster to optimize for job execution speed and reduced cluster cost.
* feature: GuardDuty: AWS GuardDuty now supports using AWS Organizations delegated administrators to create and manage GuardDuty master and member accounts.  The feature also allows GuardDuty to be automatically enabled on associated organization accounts.
* feature: Route53Domains: You can now programmatically transfer domains between AWS accounts without having to contact AWS Support

## 2.659.0
* feature: ApiGatewayV2: You can now export an OpenAPI 3.0 compliant API definition file for Amazon API Gateway HTTP APIs using the Export API.
* feature: CostExplorer: Cost Categories API is now General Available with new dimensions and operations support. You can map costs by account name, service, and charge type dimensions as well as use contains, starts with, and ends with operations. Cost Categories can also be used in RI and SP coverage reports.
* feature: Glue: Added a new ConnectionType "KAFKA" and a ConnectionProperty "KAFKA_BOOTSTRAP_SERVERS" to support Kafka connection.
* feature: IoTEvents: API update that allows users to add AWS Iot SiteWise actions while creating Detector Model in AWS Iot Events
* feature: Synthetics: Introducing CloudWatch Synthetics. This is the first public release of CloudWatch Synthetics.

## 2.658.0
* feature: FraudDetector: Added support for a new rule engine execution mode. Customers will be able to configure their detector versions to evaluate all rules and return outcomes from all 'matched' rules in the GetPrediction API response. Added support for deleting Detectors (DeleteDetector) and Rule Versions (DeleteRuleVersion).

## 2.657.0
* feature: AugmentedAIRuntime: This release updates Amazon Augmented AI ListHumanLoops and StartHumanLoop APIs.
* feature: EC2: Amazon EC2 now supports adding AWS resource tags for placement groups and key pairs, at creation time. The CreatePlacementGroup API will now return placement group information when created successfully. The DeleteKeyPair API now supports deletion by resource ID.
* feature: Glue: This release adds support for querying GetUserDefinedFunctions API without databaseName.
* feature: Imagebuilder: This release includes support for additional OS Versions within EC2 Image Builder.
* feature: IoTEvents: API update that allows users to customize event action payloads, and adds support for Amazon DynamoDB actions.
* feature: MediaConvert: AWS Elemental MediaConvert now allows you to specify your input captions frame rate for SCC captions sources.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now allows configuration of Avail Suppression.
* feature: MigrationHub: Adding ThrottlingException
* feature: RDS: This release adds support for Amazon RDS Proxy with PostgreSQL compatibility.
* feature: SageMaker: Amazon SageMaker now supports running training jobs on ml.g4dn and ml.c5n instance types. Amazon SageMaker supports in "IN" operation for Search now.
* feature: SecurityHub: Added a new BatchUpdateFindings action, which allows customers to update selected information about their findings. Security Hub customers use BatchUpdateFindings to track their investigation into a finding. BatchUpdateFindings is intended to replace the UpdateFindings action, which is deprecated.
* feature: Snowball: An update to the Snowball Edge Storage Optimized device has been launched. Like the previous version, it has 80 TB of capacity for data transfer. Now it has 40 vCPUs, 80 GiB, and a 1 TiB SATA SSD of memory for EC2 compatible compute. The 80 TB of capacity can also be used for EBS-like volumes for AMIs.

## 2.656.0
* bugfix: Monitoring: Set MaxRetriesExceeded on monitoring event only when the final retry fails
* feature: Chime: feature: Chime: This release introduces the ability to tag Amazon Chime SDK meeting resources.  You can use tags to organize and identify your resources for cost allocation. 
* feature: CodeGuruProfiler: CodeGuruProfiler adds support for resource based authorization to submit profile data.
* feature: EC2: This release provides the ability to include tags in EC2 event notifications. 
* feature: ECS: This release provides native support for specifying Amazon EFS file systems as volumes in your Amazon ECS task definitions.
* feature: MediaConvert: AWS Elemental MediaConvert SDK adds support for queue hopping. Jobs can now hop from their original queue to a specified alternate queue, based on the maximum wait time that you specify in the job settings.
* feature: MigrationHubConfig: Adding ThrottlingException

## 2.655.0
* feature: CodeGuruReviewer: API updates for CodeGuruReviewer 
* feature: MediaConnect: You can now send content from your MediaConnect flow to your virtual private cloud (VPC) without going over the public internet.

## 2.654.0
* feature: Chime: Amazon Chime proxy phone sessions let you provide two users with a shared phone number to communicate via voice or text for up to 12 hours without revealing personal phone numbers. When users call or message the provided phone number, they are connected to the other party and their private phone numbers are replaced with the shared number in Caller ID.
* feature: ElasticBeanstalk: This release adds a new action, ListPlatformBranches, and updates two actions, ListPlatformVersions and DescribePlatformVersion, to support the concept of Elastic Beanstalk platform branches.
* feature: S3: SDK will throw exception when CopyObject returns 200 status and empty body.
* feature: TranscribeService: This release adds support for batch transcription jobs within Amazon Transcribe Medical.

## 2.653.0
* feature: PersonalizeRuntime: Amazon Personalize: Add new response field "score" to each item returned by GetRecommendations and GetPersonalizedRanking (HRNN-based recipes only)
* feature: RoboMaker: Added support for limiting simulation unit usage, giving more predictable control over simulation cost

## 2.652.0
* feature: CloudWatch: Amazon CloudWatch Contributor Insights adds support for tags and tagging on resource creation. 
* feature: GameLift: Public preview of GameLift FleetIQ as a standalone feature. GameLift FleetIQ makes it possible to use low-cost Spot instances by limiting the chance of interruptions affecting game sessions. FleetIQ is a feature of the managed GameLift service, and can now be used with game hosting in EC2 Auto Scaling groups that you manage in your own account.
* feature: MediaLive: AWS Elemental MediaLive now supports Automatic Input Failover. This feature provides resiliency upstream of the channel, before ingest starts.

## 2.651.0
* feature: Iot: This release introduces Dimensions for AWS IoT Device Defender. Dimensions can be used in Security Profiles to collect and monitor fine-grained metrics.
* feature: MediaConnect: You can now send content from your virtual private cloud (VPC) to your MediaConnect flow without going over the public internet.

## 2.650.0
* feature: AppConfig: This release adds an event log to deployments. In the case of a deployment rollback, the event log details the rollback reason.
* feature: ElasticInference: This release includes improvements for the Amazon Elastic Inference service.
* feature: FMS: This release contains FMS wafv2 support.
* feature: Glue: Add two enums for MongoDB connection: Added "CONNECTION_URL" to "ConnectionPropertyKey" and added "MONGODB" to "ConnectionType"
* feature: Lambda: AWS Lambda now supports .NET Core 3.1
* feature: MediaStore: This release adds support for CloudWatch Metrics. You can now set a policy on your container to dictate which metrics MediaStore sends to CloudWatch.
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces MMS support for SMS messages.
* feature: Rekognition: This release adds DeleteProject and DeleteProjectVersion APIs to Amazon Rekognition Custom Labels.
* feature: StorageGateway: Adding audit logging support for SMB File Shares
* feature: WAFV2: Added support for AWS Firewall Manager for WAFv2 and PermissionPolicy APIs for WAFv2.

## 2.649.0
* feature: AccessAnalyzer: This release adds support for the creation and management of IAM Access Analyzer analyzers with type organization. An analyzer with type organization continuously monitors all supported resources within the AWS organization and reports findings when they allow access from outside the organization.

## 2.648.0
* feature: GlobalAccelerator: This update adds an event history to the ListByoipCidr API call. This enables you to see the changes that you've made for an IP address range that you bring to AWS Global Accelerator through bring your own IP address (BYOIP).
* feature: Kendra: The Amazon Kendra Microsoft SharePoint data source now supports include and exclude regular expressions and change log features. Include and exclude regular expressions enable you to  provide a list of regular expressions to match the display URL of SharePoint documents to either include or exclude documents respectively. When you enable the changelog feature it enables Amazon Kendra to use the SharePoint change log to determine which documents to update in the index.
* feature: ServiceCatalog: Added "LocalRoleName" as an acceptable Parameter for Launch type in CreateConstraint and UpdateConstraint APIs

## 2.647.0
* feature: FSx: This release includes two changes: a new lower-cost, storage type called HDD (Hard Disk Drive), and a new generation of the Single-AZ deployment type called Single AZ 2. The HDD storage type can be selected on Multi AZ 1 and Single AZ 2 deployment types.
* feature: SageMaker: This release updates Amazon Augmented AI CreateFlowDefinition API and DescribeFlowDefinition response.
* feature: SecurityHub: Security Hub has now made it easier to opt out of default standards when you enable Security Hub. We added a new Boolean parameter to EnableSecurityHub called EnableDefaultStandards. If that parameter is true, Security Hub's default standards are enabled. A new Boolean parameter for standards, EnabledByDefault, indicates whether a standard is a default standard. Today, the only default standard is CIS AWS Foundations Benchmark v1.2. Additional default standards will be added in the future.To learn more, visit our documentation on the EnableSecurityHub API action.

## 2.646.0
* feature: ApplicationInsights: Amazon CloudWatch Application Insights for .NET and SQL Server now integrates with Amazon CloudWatch Events (AWS CodeDeploy, AWS Health and Amazon EC2 state changes). This feature enables customers to view events related to problems detected by CloudWatch Application Insights, and reduce mean-time-to-resolution (MTTR).
* feature: CostExplorer: Customers can now receive Savings Plans recommendations at the member (linked) account level.
* feature: Detective: The new ACCEPTED_BUT_DISABLED member account status indicates that a member account that accepted the invitation is blocked from contributing data to the behavior graph. The reason is provided in the new DISABLED_REASON property. The new StartMonitoringMember operation enables a blocked member account.
* feature: ES: Adding support for customer packages (dictionary files) to Amazon Elasticsearch Service
* feature: ManagedBlockchain: Amazon Managed Blockchain now has support to publish Hyperledger Fabric peer node, chaincode, and certificate authority (CA) logs to Amazon CloudWatch Logs.
* feature: XRay: GetTraceSummaries - Now provides additional root cause attribute ClientImpacting which indicates whether root cause impacted trace client.

## 2.645.0
* feature: EKS: Adding new error codes: Ec2SubnetInvalidConfiguration and NodeCreationFailure for Nodegroups in EKS
* feature: Organizations: Introduces actions for giving a member account administrative Organizations permissions for an AWS service. You can run this action only for AWS services that support this feature.

## 2.644.0
* feature: ApiGatewayV2: Documentation updates to reflect that the default timeout for integrations is now 30 seconds for HTTP APIs.
* feature: EC2: Add EC2ThrottledException to throttledError
* feature: EKS: Adding new error code IamLimitExceeded for Nodegroups in EKS

## 2.643.0
* feature: ServiceCatalog: Added "productId" and "portfolioId" to responses from CreateConstraint, UpdateConstraint, ListConstraintsForPortfolio, and DescribeConstraint APIs

## 2.642.0
* bugfix: Credentials: Fix types for callback argument in get & refresh methods for Credentials to accept error optionally
* bugfix: s3: createBucket mutates params argument when endpoint is configured by appending CreateBucketConfigurationon key, this side effect is now fixed
* feature: MediaConnect: Feature adds the ability for a flow to have multiple redundant sources that provides resiliency to a source failing. The new APIs added to enable the feature are, AddFlowSources, RemoveFlowSource and UpdateFlow.
* feature: Personalize: [Personalize] Adds support for returning hyperparameter values of the best performing model in a HPO job.
* feature: RDS: Updated the MaxRecords type in DescribeExportTasks to Integer.

## 2.641.0
* feature: CI: add buildspec.yml from CodeBuild job
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for: AV1 encoding in File Group MP4, DASH and CMAF DASH outputs; PCM/WAV audio output in MPEG2-TS containers; and Opus audio in Webm inputs.

## 2.640.0
* bugfix: AWS.EventListeners.Core: add error message
* feature: CognitoIdentityServiceProvider: Additional response field "CompromisedCredentialsDetected" added to AdminListUserAuthEvents.
* feature: ECS: This release adds the ability to update the task placement strategy and constraints for Amazon ECS services.
* feature: ElastiCache: Amazon ElastiCache now supports Global Datastore for Redis. Global Datastore for Redis offers fully managed, fast, reliable and secure cross-region replication. Using Global Datastore for Redis, you can create cross-region read replica clusters for ElastiCache for Redis to enable low-latency reads and disaster recovery across regions. You can create, modify and describe a Global Datastore, as well as add or remove regions from your Global Datastore and promote a region as primary in Global Datastore.
* feature: S3Control: Amazon S3 now supports Batch Operations job tagging.
* feature: SSM: Resource data sync for AWS Systems Manager Inventory now includes destination data sharing. This feature enables you to synchronize inventory data from multiple AWS accounts into a central Amazon S3 bucket. To use this feature, all AWS accounts must be listed in AWS Organizations.

## 2.639.0
* feature: ApiGatewayV2: Amazon API Gateway HTTP APIs is now generally available. HTTP APIs offer the core functionality of REST API at up to 71% lower price compared to REST API, 60% lower p99 latency, and is significantly easier to use. As part of general availability, we added new features to route requests to private backends such as private ALBs, NLBs, and IP/ports. We also brought over a set of features from REST API such as Stage Variables, and Stage/Route level throttling. Custom domain names can also now be used with both REST And HTTP APIs.
* feature: EC2: Documentation updates for EC2
* feature: Iot: As part of this release, we are extending capability of AWS IoT Rules Engine to support IoT Cloudwatch log action. The IoT Cloudwatch log rule action lets you send messages from IoT sensors and applications to Cloudwatch logs for troubleshooting and debugging.
* feature: LexModelBuildingService: Amazon Lex now supports tagging for bots, bot aliases and bot channels. 
* feature: SecurityHub: The AWS Security Finding Format is being augmented with the following changes. 21 new resource types without corresponding details objects are added. Another new resource type, AwsS3Object, has an accompanying details object. Severity.Label is a new string field that indicates the severity of a finding. The available values are: INFORMATIONAL, LOW, MEDIUM, HIGH, CRITICAL. The new string field Workflow.Status indicates the status of the investigation into a finding. The available values are: NEW, NOTIFIED, RESOLVED, SUPPRESSED.

## 2.638.0
* feature: Redshift: Amazon Redshift now supports operations to pause and resume a cluster on demand or on a schedule.

## 2.637.0
* feature: EC2: Documentation updates for EC2
* feature: IoTEvents: API update that adds a new parameter, durationExpression, to SetTimerAction, and deprecates seconds
* feature: MarketplaceCommerceAnalytics: Change the disbursement data set to look past 31 days instead until the beginning of the month.
* feature: ServerlessApplicationRepository: AWS Serverless Application Repository now supports sharing applications privately with AWS Organizations.
* feature: TranscribeService: Amazon Transcribe's Automatic Content Redaction feature enables you to automatically redact sensitive personally identifiable information (PII) from transcription results. It replaces each instance of an identified PII utterance with a [PII] tag in the transcript.

## 2.636.0
* feature: DMS: Added new settings for Kinesis target to include detailed transaction info; to capture table DDL details; to use single-line unformatted json, which can be directly queried by AWS Athena if data is streamed into S3 through AWS Kinesis Firehose. Added CdcInsertsAndUpdates in S3 target settings to allow capture ongoing insertions and updates only.
* feature: EC2: Amazon Virtual Private Cloud (VPC) NAT Gateway adds support for tagging on resource creation.
* feature: MediaLive: AWS Elemental MediaLive now supports the ability to configure the Preferred Channel Pipeline for channels contributing to a Multiplex.

## 2.635.0
* feature: AppMesh: App Mesh now supports sharing a Mesh with other AWS accounts. Customers can use AWS Resource Access Manager to share their Mesh with other accounts in their organization to connection applications within a single service mesh. See https://docs.aws.amazon.com/app-mesh/latest/userguide/sharing.html for details.
* feature: EC2: This release provides customers with a self-service option to enable Local Zones.
* feature: GuardDuty: Amazon GuardDuty findings now include the OutpostArn if the finding is generated for an AWS Outposts EC2 host.
* feature: RoboMaker: Added support for streaming a GUI from robot and simulation applications
* feature: Signer: This release enables signing image format override in PutSigningProfile requests, adding two more enum fields, JSONEmbedded and JSONDetached. This release also extends the length limit of SigningProfile name from 20 to 64.

## 2.634.0
* feature: EC2: You can now create AWS Client VPN Endpoints with a specified VPC and Security Group. Additionally, you can modify these attributes when modifying the endpoint. 
* feature: EKS: Amazon EKS now supports adding a KMS key to your cluster for envelope encryption of Kubernetes secrets.
* feature: GuardDuty: Add a new finding field for EC2 findings indicating the instance's local IP address involved in the threat.
* feature: OpsWorksCM: Updated the Tag regex pattern to align with AWS tagging APIs.

## 2.633.0
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces support for integrating recommender models with email, push notification, and SMS message templates. You can now use these types of templates to connect to recommender models and add personalized recommendations to messages that you send from campaigns and journeys.

## 2.632.0
* feature: EC2: Amazon VPC Flow Logs adds support for tags and tagging on resource creation.

## 2.631.0
* feature: CloudWatch: Introducing Amazon CloudWatch Composite Alarms
* feature: ComprehendMedical: New Time Expression feature, part of DetectEntitiesV2 API will provide temporal relations to existing NERe entities such as Medication, Test, Treatment, Procedure and Medical conditions. 

## 2.630.0
* feature: ConfigService: Correcting list of supported resource types.

## 2.629.0
* feature: AccessAnalyzer: This release includes improvements and fixes bugs for the IAM Access Analyzer feature.
* feature: AppMesh: App Mesh now supports Transport Layer Security (TLS) between Virtual Nodes in a Mesh. Customers can use managed certificates from an AWS Certificate Manager Private Certificate Authority or bring their own certificates from the local file system to encrypt traffic between their workloads. See https://docs.aws.amazon.com/app-mesh/latest/userguide/virtual-node-tls.html for details.
* feature: AugmentedAIRuntime: This release updates Amazon Augmented AI ListHumanLoops API, DescribeHumanLoop response, StartHumanLoop response and type names of SDK fields. 
* feature: ConfigService: Accepts a structured query language (SQL) SELECT command and an aggregator name, performs the corresponding search on resources aggregated by the aggregator, and returns resource configurations matching the properties.
* feature: Glue: AWS Glue adds resource tagging support for Machine Learning Transforms and adds a new API, ListMLTransforms to support tag filtering.  With this feature, customers can use tags in AWS Glue to organize and control access to Machine Learning Transforms. 
* feature: QuickSight: Added SearchDashboards API that allows listing of dashboards that a specific user has access to.

## 2.628.0
* feature: GlobalAccelerator: This release adds support for adding tags to accelerators and bringing your own IP address to AWS Global Accelerator (BYOIP).
* feature: Lightsail: Adds support to create notification contacts in Amazon Lightsail, and to create instance, database, and load balancer metric alarms that notify you based on the value of a metric relative to a threshold that you specify.

## 2.627.0
* feature: EC2: This release changes the RunInstances CLI and SDK's so that if you do not specify a client token, a randomly generated token is used for the request to ensure idempotency.
* feature: SageMaker: SageMaker UpdateEndpoint API now supports retained variant properties, e.g., instance count, variant weight. SageMaker ListTrials API filter by TrialComponentName. Make ExperimentConfig name length limits consistent with CreateExperiment, CreateTrial, and CreateTrialComponent APIs.
* feature: SecurityHub: Security Hub has added to the DescribeProducts API operation a new response field called IntegrationTypes. The IntegrationTypes field lists the types of actions that a product performs relative to Security Hub such as send findings to Security Hub and receive findings from Security Hub.
* feature: TranscribeService: Amazon Transcribe's Automatic Content Redaction feature enables you to automatically redact sensitive personally identifiable information (PII) from transcription results. It replaces each instance of an identified PII utterance with a [PII] tag in the transcript.

## 2.626.0
* feature: Kafka: Amazon MSK has added support for Broker Log delivery to CloudWatch, S3, and Firehose.
* feature: Outposts: This release adds DeleteSite and DeleteOutpost. 
* feature: SecretsManager: This release increases the maximum allowed size of SecretString or SecretBinary from 10KB to 64KB in the CreateSecret, UpdateSecret, PutSecretValue and GetSecretValue APIs.
* feature: StepFunctions: This release adds support for CloudWatch Logs for Standard Workflows.

## 2.625.0
* bugfix: Access Point: Avoid mixing up S3 client config set by ManagedUpload with user-set client config
* feature: CloudWatchEvents: This release allows you to create and manage tags for event buses.
* feature: EventBridge: This release allows you to create and manage tags for event buses.
* feature: FSx: Announcing persistent file systems for Amazon FSx for Lustre that are ideal for longer-term storage and workloads, and a new generation of scratch file systems that offer higher burst throughput for spiky workloads.
* feature: Snowball: AWS Snowball adds a field for entering your GSTIN when creating AWS Snowball jobs in the Asia Pacific (Mumbai) region. 

## 2.624.0
* feature: Imagebuilder: This release of EC2 Image Builder increases the maximum policy document size for Image Builder resource-based policy APIs.
* feature: Redshift: Extend elastic resize to support resizing clusters to different instance types.

## 2.623.0
* bugfix: EndpointDiscovery: Update host header in requests when new endpoint is found; Throw error when endpoint discovery is required but not enabled
* feature: AppConfig: This release adds exponential growth type support for deployment strategies.
* feature: Pinpoint: As of this release of the Amazon Pinpoint API, the Title property is optional for the CampaignEmailMessage object. 
* feature: SavingsPlans: Added support for AWS Lambda in Compute Savings Plans

## 2.622.0
* feature: Lambda: AWS Lambda now supports Ruby 2.7
* feature: ServiceCatalog: "ListPortfolioAccess" API now has a new optional parameter "OrganizationParentId". When it is provided and if the portfolio with the "PortfolioId" given was shared with an organization or organizational unit with "OrganizationParentId", all accounts in the organization sub-tree under parent which inherit an organizational portfolio share will be listed, rather than all accounts with external shares. To accommodate long lists returned from the new option, the API now supports pagination.

## 2.621.0
* feature: AutoScaling: Amazon EC2 Auto Scaling now supports the ability to enable/disable target tracking, step scaling, and simple scaling policies.
* feature: Chime: Added AudioFallbackUrl to support Chime SDK client.
* feature: RDS: This release supports Microsoft Active Directory authentication for Amazon Aurora.

## 2.620.0
* feature: Cloud9: AWS Cloud9 now supports the ability to tag Cloud9 development environments. 
* feature: DynamoDB: Amazon DynamoDB enables you to restore your DynamoDB backup or table data across AWS Regions such that the restored table is created in a different AWS Region from where the source table or backup resides. You can do cross-region restores between AWS commercial Regions, AWS China Regions, and AWS GovCloud (US) Regions. 
* feature: EC2: Documentation updates for EC2
* feature: Rekognition: This update adds the ability to detect text in videos and adds filters to image and video text detection.

## 2.619.0
* feature: EC2: You can now enable Multi-Attach on Provisioned IOPS io1 volumes through the create-volume API.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now allows configuration of Personalization Threshold for HLS and DASH streams.
* feature: SecurityHub: Security Hub has released a new DescribeStandards API action. This API action allows a customer to list all of the standards available in an account. For each standard, the list provides the customer with the standard name, description, and ARN. Customers can use the ARN as an input to the BatchEnableStandards API action.  To learn more, visit our API documentation.
* feature: Shield: This release adds support for associating Amazon Route 53 health checks to AWS Shield Advanced protected resources.

## 2.618.0
* feature: MediaPackageVod: Adds support for DASH with multiple media presentation description periods triggered by presence of SCTE-35 ad markers in the manifest.Also adds optional configuration for DASH SegmentTemplateFormat to refer to segments by Number with Duration, Number with Timeline or Time with Timeline and compact the manifest by combining duplicate SegmentTemplate tags.

## 2.617.0
* feature: DirectoryService: Release to add the ExpirationDateTime as an output to ListCertificates so as to ease customers to look into their certificate lifetime and make timely decisions about renewing them.
* feature: EC2: This release adds support for tagging public IPv4 pools.
* feature: ES: Amazon Elasticsearch Service now offers fine-grained access control, which adds multiple capabilities to give tighter control over data. New features include the ability to use roles to define granular permissions for indices, documents, or fields and to extend Kibana with read-only views and secure multi-tenant support.
* feature: Glue: Adding ability to add arguments that cannot be overridden to AWS Glue jobs
* feature: Neptune: This launch enables Neptune start-db-cluster and stop-db-cluster. Stopping and starting Amazon Neptune clusters helps you manage costs for development and test environments. You can temporarily stop all the DB instances in your cluster, instead of setting up and tearing down all the DB instances each time that you use the cluster.
* feature: WorkMail: This release adds support for access control rules management  in Amazon WorkMail.

## 2.616.0
* feature: CloudFormation: This release of AWS CloudFormation StackSets allows you to centrally manage deployments to all the accounts in your organization or specific organizational units (OUs) in AWS Organizations. You will also be able to enable automatic deployments to any new accounts added to your organization or OUs. The permissions needed to deploy across accounts will automatically be taken care of by the StackSets service.
* feature: CognitoIdentityServiceProvider: Features:This release adds a new setting for a user pool to allow if customer wants their user signup/signin with case insensitive username. The current default setting is case sensitive, and for our next release we will change it to case insensitive.
* feature: EC2: Amazon EC2 Now Supports Tagging Spot Fleet.

## 2.615.0
* feature: KMS: The ConnectCustomKeyStore API now provides a new error code (SUBNET_NOT_FOUND) for customers to better troubleshoot if their "connect-custom-key-store" operation fails.

## 2.614.0
* feature: Imagebuilder: This version of the SDK includes bug fixes and documentation updates.
* feature: RoboMaker: This release adds support for simulation job batches

## 2.613.0
* feature: AppSync: AWS AppSync now supports X-Ray
* feature: CodeBuild: AWS CodeBuild adds support for Amazon Elastic File Systems
* feature: EC2: This release adds platform details and billing info to the DescribeImages API.
* feature: LexModelBuildingService: Amazon Lex now supports AMAZON.AlphaNumeric with regular expressions.

## 2.612.0
* feature: DLM: Updated the maximum number of tags that can be added to a snapshot using DLM to 45.
* feature: EC2: This release provides support for tagging when you create a VPC endpoint, or VPC endpoint service.
* feature: GroundStation: Adds dataflowEndpointRegion property to DataflowEndpointConfig. The dateCreated, lastUpdated, and tags properties on GetSatellite have been deprecated.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for fine-tuned QVBR quality level.
* feature: SecurityHub: Additional resource types are now supported in the AWS Security Finding Format (ASFF). The following new resource types are added, each having an accompanying resource details object with fields for security finding providers to populate: AwsCodeBuildProject, AwsEc2NetworkInterface, AwsEc2SecurityGroup, AwsElasticsearchDomain, AwsLambdaLayerVersion, AwsRdsDbInstance, and AwsWafWebAcl. The following resource types are added without an accompanying details object: AutoscalingAutoscalingGroup, AwsDynamoDbTable, AwsEc2Eip, AwsEc2Snapshot, AwsEc2Volume, AwsRdsDbSnapshot, AwsRedshiftCluster, and AwsS3Object. The number of allowed resources per finding is increased from 10 to 32. A new field is added in the Compliance object, RelatedRequirements. To learn more, visit our documentation on the ASFF.

## 2.611.0
* bugfix: node-s3-sqs: Respect the NODE_TLS_REJECT_UNAUTHORIZED environment under node when instantiating an http client sslAgent
* bugfix: parser: Now we can disable inserting empty array in xml parser if the member doesn't exist in response.
* feature: EC2: Amazon VPC Flow Logs adds support for 1-minute aggregation intervals.
* feature: Kafka: This release enables AWS MSK customers to list Apache Kafka versions that are supported on AWS MSK clusters. Also includes changes to expose additional details of a cluster's state in DescribeCluster and ListClusters APIs.
* feature: SSM: This feature ensures that an instance is patched up to the available patches on a particular date. It can be enabled by selecting the 'ApproveUntilDate' option as the auto-approval rule while creating the patch baseline. ApproveUntilDate - The cutoff date for auto approval of released patches. Any patches released on or before this date will be installed automatically.
* feature: StorageGateway: Adding KVM as a support hypervisor
* feature: WorkMail: This release adds support for tagging Amazon WorkMail organizations.

## 2.610.0
* feature: BigInt Support for DynamoDB Convert: Adding support for BigInt data type for DocumentDB Dynamo Client converter.
* bugfix: endpoint: add endpoint for us-iso-*
* bugfix: endpoint: add endpoint for us-isob-*
* feature: DataSync: AWS DataSync now supports FSx for Windows File Server Locations
* feature: ECS: This release provides support for tagging Amazon ECS task sets for services using external deployment controllers.
* feature: EKS: Adding new error codes for Nodegroups in EKS
* feature: OpsWorksCM: AWS OpsWorks for Chef Automate now supports in-place upgrade to Chef Automate 2. Eligible servers can be updated through the management console, CLI and APIs.

## 2.609.0
* feature: IAM: This release enables the Identity and Access Management policy simulator to simulate permissions boundary policies.
* feature: RDS: This SDK release introduces APIs that automate the export of Amazon RDS snapshot data to Amazon S3. The new APIs include: StartExportTask, CancelExportTask, DescribeExportTasks. These APIs automate the extraction of data from an RDS snapshot and export it to an Amazon S3 bucket. The data is stored in a compressed, consistent, and query-able format. After the data is exported, you can query it directly using tools such as Amazon Athena or Redshift Spectrum. You can also consume the data as part of a data lake solution. If you archive the data in S3 Infrequent Access or Glacier, you can reduce long term data storage costs by applying data lifecycle policies.

## 2.608.0
* feature: CodePipeline: AWS CodePipeline enables an ability to stop pipeline executions.
* feature: EC2: Add an enum value to the result of DescribeByoipCidrs to support CIDRs that are not publicly advertisable.
* feature: MarketplaceCommerceAnalytics: Remove 4 deprecated data sets, change some data sets available dates to 2017-09-15

## 2.607.0
* feature: AlexaForBusiness: Add support for CreatedTime and ConnectionStatusUpdatedTime in response of SearchDevices API.
* feature: ApplicationInsights: This release adds support for a list API to retrieve the configuration events logged during periodic updates to an application by Amazon CloudWatch Application Insights. 
* feature: CloudWatch: Updating DescribeAnomalyDetectors API to return AnomalyDetector Status value in response.
* feature: EC2: This release provides support for a preview of bringing your own IPv6 addresses (BYOIP for IPv6) for use in AWS.
* feature: KMS: The ConnectCustomKeyStore operation now provides new error codes (USER_LOGGED_IN and USER_NOT_FOUND) for customers to better troubleshoot if their connect custom key store operation fails. Password length validation during CreateCustomKeyStore now also occurs on the client side. 
* feature: Lambda: Added reason codes to StateReasonCode (InvalidSubnet, InvalidSecurityGroup) and LastUpdateStatusReasonCode (SubnetOutOfIPAddresses, InvalidSubnet, InvalidSecurityGroup) for functions that connect to a VPC.

## 2.606.0
* bugfix: iam: add IAM endpoint for us-isob-*
* feature: Batch: This release ensures INACTIVE job definitions are permanently deleted after 180 days.
* feature: CloudHSMV2: This release introduces resource-level and tag-based access control for AWS CloudHSM resources. You can now tag CloudHSM backups, tag CloudHSM clusters on creation, and tag a backup as you copy it to another region.
* feature: ECS: This release provides a public preview for specifying Amazon EFS file systems as volumes in your Amazon ECS task definitions.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for MP3 audio only outputs.
* feature: Neptune: This release includes Deletion Protection for Amazon Neptune databases.

## 2.605.0
* feature: DirectoryService: To reduce the number of errors our customers are facing, we have modified the requirements of input parameters for two of Directory Service APIs.
* feature: EC2: Client VPN now supports Port Configuration for VPN Endpoints, allowing usage of either port 443 or port 1194.
* feature: SageMaker: This release adds two new APIs (UpdateWorkforce and DescribeWorkforce) to SageMaker Ground Truth service for workforce IP whitelisting.

## 2.604.0
* feature: EC2: General Update to EC2 Docs and SDKs
* feature: SecurityHub: Add support for DescribeStandardsControls and UpdateStandardsControl. These new Security Hub API operations are used to track and manage whether a compliance standards control is enabled.

## 2.603.0
* feature: EC2: This release adds support for partition placement groups and instance metadata option in Launch Templates

## 2.602.0
* bugfix: util: Fix `name.endsWith is not a function` exception when inspecting some generated errors with some versions of nodejs
* feature: Backup: Cross-region backup is a new AWS Backup feature that allows enterprises to copy backups across multiple AWS services to different regions. 
* feature: EFS: This release adds support for managing EFS file system policies and EFS Access Points.

## 2.601.0
* feature: Chime: Add shared profile support to new and existing users
* feature: EC2: This release introduces the ability to tag egress only internet gateways, local gateways, local gateway route tables, local gateway virtual interfaces, local gateway virtual interface groups, local gateway route table VPC association and local gateway route table virtual interface group association. You can use tags to organize and identify your resources for cost allocation. 
* feature: RDS: This release adds an operation that enables users to override the system-default SSL/TLS certificate for new Amazon RDS DB instances temporarily, or remove the customer override.
* feature: RDSDataService: Retry on Serverless Aurora "Communications link failure"
* feature: SageMaker: SageMaker ListTrialComponents API filter by TrialName and ExperimentName.
* feature: Transfer: This release introduces a new endpoint type that allows you to attach Elastic IP addresses from your AWS account with your server's endpoint directly and whitelist access to your server by client's internet IP address(es) using VPC Security Groups.
* feature: WorkSpaces: Added the migrate feature to Amazon WorkSpaces.

## 2.600.0
* feature: FMS: AWS Firewall Manager now supports tagging, and tag-based access control, of policies.
* feature: Translate: This release adds a new family of APIs for asynchronous batch translation service that provides option to translate large collection of text or HTML documents stored in Amazon S3 folder. This service accepts a batch of up to 5 GB in size per API call with each document not exceeding 1 MB size and the number of documents not exceeding 1 million per batch. See documentation for more information. 

## 2.599.0
* feature: CodeBuild: Add encryption key override to StartBuild API in AWS CodeBuild.
* feature: MigrationHub: ListApplicationStates API provides a list of all application migration states

## 2.598.0
* feature: Comprehend: Amazon Comprehend now supports Multilabel document classification
* feature: EC2: This release supports service providers configuring a private DNS name for services other than AWS services and services available in the AWS marketplace. This feature allows consumers to access the service using an existing DNS name without making changes to their applications.
* feature: MediaPackage: You can now restrict direct access to AWS Elemental MediaPackage by securing requests for live content using CDN authorization. With CDN authorization, content requests require a specific HTTP header and authorization code.

## 2.597.0
* feature: ECR: Adds waiters for ImageScanComplete and LifecyclePolicyPreviewComplete
* feature: Lightsail: This release adds support for Certificate Authority (CA) certificate identifier to managed databases in Amazon Lightsail.

## 2.596.0
* feature: FSx: This release adds a new family of APIs (create-data-repository-task, describe-data-repository-task, and cancel-data-repository-task) that allow users to perform operations between their file system and its linked data repository.
* feature: Health: With this release, you can now centrally aggregate AWS Health events from all accounts in your AWS organization. Visit AWS Health documentation to learn more about enabling and using this feature: https://docs.aws.amazon.com/health/latest/ug/organizational-view-health.html. 

## 2.595.0
* feature: DeviceFarm: Introduced browser testing support through AWS Device Farm
* feature: EC2: This release introduces the ability to tag key pairs, placement groups, export tasks, import image tasks, import snapshot tasks and export image tasks. You can use tags to organize and identify your resources for cost allocation. 
* feature: EKS: Amazon EKS now supports restricting access to the API server public endpoint by applying CIDR blocks
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces versioning support for message templates.
* feature: RDS: This release adds an operation that enables users to specify whether a database is restarted when its SSL/TLS certificate is rotated. Only customers who do not use SSL/TLS should use this operation.
* feature: SSM: This release updates the attachments support to include AttachmentReference source for Automation documents.
* feature: SecurityHub: Additional resource types are now fully supported in the AWS Security Finding Format (ASFF). These resources include AwsElbv2LoadBalancer, AwsKmsKey, AwsIamRole, AwsSqsQueue, AwsLambdaFunction, AwsSnsTopic, and AwsCloudFrontDistribution. Each of these resource types includes an accompanying resource details object with fields for security finding providers to populate. Updates were made to the AwsIamAccessKey resource details object to include information on principal ID and name. To learn more, visit our documentation on the ASFF.
* feature: TranscribeService: AWS Transcribe now supports vocabulary filtering that allows customers to input words to the service that they don't want to see in the output transcript.

## 2.594.0
* feature: CodeStarconnections: Public beta for Bitbucket Cloud support in AWS CodePipeline through integration with AWS CodeStar connections.
* feature: DLM: You can now copy snapshots across regions using Data Lifecycle Manager (DLM). You can enable policies which, along with create, can now also copy snapshots to one or more AWS region(s). Copies can be scheduled for up to three regions from a single policy and retention periods are set for each region separately. 
* feature: EC2: We are updating the supportedRootDevices field to supportedRootDeviceTypes for DescribeInstanceTypes API to ensure that the actual value is returned, correcting a previous error in the model.
* feature: GameLift: Amazon GameLift now supports ARNs for all key GameLift resources, tagging for GameLift resource authorization management, and updated documentation that articulates GameLift's resource authorization strategy.
* feature: LexModelBuildingService: Amazon Lex now supports conversation logs and slot obfuscation.
* feature: PersonalizeRuntime: Add context map to get-recommendations and get-personalized-ranking request objects to provide contextual metadata at inference time
* feature: SSM: This release allows customers to add tags to Automation execution, enabling them to sort and filter executions in different ways, such as by resource, purpose, owner, or environment.
* feature: TranscribeService: Amazon Transcribe supports job queuing for the StartTranscriptionJob API.

## 2.593.0
* feature: EC2: This release introduces the ability to tag Elastic Graphics accelerators. You can use tags to organize and identify your accelerators for cost allocation.
* feature: OpsWorksCM: AWS OpsWorks CM now supports tagging, and tag-based access control, of servers and backups.

## 2.592.0
* feature: Iot: Added a new Over-the-Air (OTA) Update feature that allows you to use different, or multiple, protocols to transfer an image from the AWS cloud to IoT devices.
* feature: KinesisAnalyticsV2: Kinesis Data Analytics service now supports running Java applications using Flink 1.8.
* feature: MediaLive: AWS Elemental MediaLive now supports HLS ID3 segment tagging, HLS redundant manifests for CDNs that support different publishing/viewing endpoints, fragmented MP4 (fMP4), and frame capture intervals specified in milliseconds.
* feature: SSM: Added support for Cloud Watch Output and Document Version to the Run Command tasks in Maintenance Windows.

## 2.591.0
* feature: ComprehendMedical: New Ontology linking APIs will provides medication concepts normalization and Diagnoses codes from input text. In this release we will provide two APIs -  RxNorm and ICD10-CM. 
* feature: EC2: You can now configure your EC2 Fleet to preferentially use EC2 Capacity Reservations for launching On-Demand instances, enabling you to fully utilize the available (and unused) Capacity Reservations before launching On-Demand instances on net new capacity.
* feature: MQ: Amazon MQ now supports throughput-optimized message brokers, backed by Amazon EBS.

## 2.590.0
* feature: CodeBuild: CodeBuild adds support for cross account
* feature: Detective: This is the initial release of Amazon Detective.
* feature: SESV2: Added the ability to use your own public-private key pair to configure DKIM authentication for a domain identity.

## 2.589.0
* feature: AccessAnalyzer: This release includes improvements and fixes bugs for the IAM Access Analyzer feature.

## 2.588.0
* feature: EC2: This release allows customers to attach multiple Elastic Inference Accelerators to a single EC2 instance. It adds support for a Count parameter for each Elastic Inference Accelerator type you specify on the RunInstances and LaunchTemplate APIs.

## 2.587.0
* feature: Kendra: 1. Adding DocumentTitleFieldName as an optional configuration for SharePoint. 2. updating s3 object pattern to  support all s3 keys.

## 2.586.0
* feature: KMS: The Verify operation now returns KMSInvalidSignatureException on invalid signatures. The Sign and Verify operations now return KMSInvalidStateException when a request is made against a CMK pending deletion.
* feature: Kafka: AWS MSK has added support for Open Monitoring with Prometheus.
* feature: SSM: Adds the SSM GetCalendarState API and ChangeCalendar SSM Document type. These features enable the forthcoming Systems Manager Change Calendar feature, which will allow you to schedule events during which actions should (or should not) be performed.

## 2.585.0
* bugfix: Endpoint: fix bug in regional endpoints and add more tests
* feature: ApiGatewayV2: Amazon API Gateway now supports HTTP APIs (beta), enabling customers to quickly build high performance RESTful APIs that are up to 71% cheaper than REST APIs also available from API Gateway. HTTP APIs are optimized for building APIs that proxy to AWS Lambda functions or HTTP backends, making them ideal for serverless workloads. Using HTTP APIs, you can secure your APIs using OIDC and OAuth 2 out of box, quickly build web applications using a simple CORS experience, and get started immediately with automatic deployment and simple create workflows.
* feature: CORS: add CORS support for kinesis-video-signaling service
* feature: KinesisVideo: Introduces management of signaling channels for Kinesis Video Streams.
* feature: KinesisVideoSignalingChannels: Announcing support for WebRTC in Kinesis Video Streams, as fully managed capability. You can now use simple APIs to enable your connected devices, web, and mobile apps with real-time two-way media streaming capabilities.

## 2.584.0
* bugfix: S3: fix issues when SDK populates wrong path if access point arn contains forward slash
* feature: ApplicationAutoScaling: This release supports auto scaling of provisioned concurrency for AWS Lambda.
* feature: EBS: This release introduces the EBS direct APIs for Snapshots: 1. ListSnapshotBlocks, which lists the block indexes and block tokens for blocks in an Amazon EBS snapshot. 2. ListChangedBlocks, which lists the block indexes and block tokens for blocks that are different between two snapshots of the same volume/snapshot lineage. 3. GetSnapshotBlock, which returns the data in a block of an Amazon EBS snapshot.
* feature: Lambda: - Added the ProvisionedConcurrency type and operations. Allocate provisioned concurrency to enable your function to scale up without fluctuations in latency. Use PutProvisionedConcurrencyConfig to configure provisioned concurrency on a version of a function, or on an alias.
* feature: RDS: This release adds support for the Amazon RDS Proxy
* feature: Rekognition: This SDK Release introduces APIs for Amazon Rekognition Custom Labels feature (CreateProjects, CreateProjectVersion,DescribeProjects, DescribeProjectVersions, StartProjectVersion, StopProjectVersion and DetectCustomLabels).  Also new is  AugmentedAI (Human In The Loop) Support for DetectModerationLabels in Amazon Rekognition.
* feature: SageMaker: You can now use SageMaker Autopilot for automatically training and tuning candidate models using a combination of various feature engineering, ML algorithms, and hyperparameters determined from the user's input data. SageMaker Automatic Model Tuning now supports tuning across multiple algorithms. With Amazon SageMaker Experiments users can create Experiments, ExperimentTrials, and ExperimentTrialComponents to track, organize, and evaluate their ML training jobs. With Amazon SageMaker Debugger, users can easily debug training jobs using a number of pre-built rules provided by Amazon SageMaker, or build custom rules. With Amazon SageMaker Processing, users can run on-demand, distributed, and fully managed jobs for data pre- or post- processing or model evaluation. With Amazon SageMaker Model Monitor, a user can create MonitoringSchedules to automatically monitor endpoints to detect data drift and other issues and get alerted on them. This release also includes the preview version of Amazon SageMaker Studio with Domains, UserProfiles, and Apps. This release also includes the preview version of Amazon Augmented AI to easily implement human review of machine learning predictions by creating FlowDefinitions, HumanTaskUis, and HumanLoops.
* feature: StepFunctions: This release of the AWS Step Functions SDK introduces support for Express Workflows.

## 2.583.0
* feature: AugmentedAIRuntime: This release adds support for Amazon Augmented AI, which makes it easy to build workflows for human review of machine learning predictions.
* feature: Bucket: Add support for S3 access point. Access Points provide a customizable way to access the objects in a bucket, with a unique hostname and access policy that enforces the specific permissions and network controls for any request made through the access point.
* feature: CodeGuruProfiler: (New Service) Amazon CodeGuru Profiler analyzes application CPU utilization and latency characteristics to show you where you are spending the most cycles in your application. This analysis is presented in an interactive flame graph that helps you easily understand which paths consume the most resources, verify that your application is performing as expected, and uncover areas that can be optimized further.
* feature: CodeGuruReviewer: This is the preview release of Amazon CodeGuru Reviewer.
* feature: ComputeOptimizer: Initial release of AWS Compute Optimizer. AWS Compute Optimizer recommends optimal AWS Compute resources to reduce costs and improve performance for your workloads.
* feature: EC2: This release adds support for the following features: 1. An option to enable acceleration for Site-to-Site VPN connections, to improve connection performance by leveraging AWS Global Accelerator; 2. Inf1 instances featuring up to 16 AWS Inferentia chips, custom-built for ML inference applications to deliver low latency and high throughput performance. Use Inf1 instances to run high scale ML inference applications such as image recognition, speech recognition, natural language processing, personalization, and fraud detection at the lowest cost in the cloud. Inf1 instances will soon be available for use with Amazon SageMaker, Amazon EKS and Amazon ECS. To get started, see https://aws.amazon.com/ec2/instance-types/Inf1; 3. The ability to associate route tables with internet gateways and virtual private gateways, and define routes to insert network and security virtual appliances in the path of inbound and outbound traffic. For more information on Amazon VPC Ingress Routing, see https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html#gateway-route-table; 4. AWS Local Zones that place compute, storage, database, and other select services closer to you for applications that require very low latency to your end-users. AWS Local Zones also allow you to seamlessly connect to the full range of services in the AWS Region through the same APIs and tool sets; 5. Launching and viewing EC2 instances and EBS volumes running locally in Outposts. This release also introduces a new local gateway (LGW) with Outposts to enable connectivity between Outposts and local on-premises networks as well as the internet; 6. Peering Transit Gateways between regions simplifying creation of secure and private global networks on AWS; 7. Transit Gateway Multicast, enabling multicast routing within and between VPCs using Transit Gateway as a multicast router.
* feature: ECS: This release supports ECS Capacity Providers, Fargate Spot, and ECS Cluster Auto Scaling.  These features enable new ways for ECS to manage compute capacity used by tasks.
* feature: EKS: Introducing Amazon EKS with Fargate. Customers can now use Amazon EKS to launch pods directly onto AWS Fargate, the serverless compute engine built for containers on AWS. 
* feature: ES: UltraWarm storage provides a cost-effective way to store large amounts of read-only data on Amazon Elasticsearch Service. Rather than attached storage, UltraWarm nodes use Amazon S3 and a sophisticated caching solution to improve performance. For indices that you are not actively writing to and query less frequently, UltraWarm storage offers significantly lower costs per GiB. In Elasticsearch, these warm indices behave just like any other index. You can query them using the same APIs or use them to create dashboards in Kibana.
* feature: FraudDetector: Amazon Fraud Detector is a fully managed service that makes it easy to identify potentially fraudulent online activities such as online payment fraud and the creation of fake accounts. Amazon Fraud Detector uses your data, machine learning (ML), and more than 20 years of fraud detection expertise from Amazon to automatically identify potentially fraudulent online activity so you can catch more fraud faster.
* feature: Kendra: It is a preview launch of Amazon Kendra. Amazon Kendra is a managed, highly accurate and easy to use enterprise search service that is powered by machine learning.
* feature: NetworkManager: This is the initial SDK release for AWS Network Manager.
* feature: Outposts: This is the initial release for AWS Outposts, a fully managed service that extends AWS infrastructure, services, APIs, and tools to customer sites. AWS Outposts enables you to launch and run EC2 instances and EBS volumes locally at your on-premises location. This release introduces new APIs for creating and viewing Outposts. 
* feature: S3Control: Amazon S3 Access Points is a new S3 feature that simplifies managing data access at scale for shared data sets on Amazon S3. Access Points provide a customizable way to access the objects in a bucket, with a unique hostname and access policy that enforces the specific permissions and network controls for any request made through the access point. This represents a new way of provisioning access to shared data sets.
* feature: Textract: This SDK Release introduces Amazon Augmented AI support for Amazon Textract AnalyzeDocument API. Image byte payloads for synchronous operations have increased from 5 MB to 10 MB.

## 2.582.0
* feature: AccessAnalyzer: Introducing AWS IAM Access Analyzer, an IAM feature that makes it easy for AWS customers to ensure that their resource-based policies provide only the intended access to resources outside their AWS accounts.

## 2.581.0
* feature: EC2: AWS now provides a new BYOL experience for software licenses, such as Windows and SQL Server, that require a dedicated physical server. You can now enjoy the flexibility and cost effectiveness of using your own licenses on Amazon EC2 Dedicated Hosts, but with the simplicity, resiliency, and elasticity of AWS. You can specify your Dedicated Host management preferences, such as host allocation, host capacity utilization, and instance placement in AWS License Manager.  Once set up, AWS takes care of these administrative tasks on your behalf, so that you can seamlessly launch virtual machines (instances) on Dedicated Hosts just like you would launch an EC2 instance with AWS provided licenses.
* feature: Imagebuilder: This is the first release of EC2 Image Builder, a service that provides a managed experience for automating the creation of EC2 AMIs.
* feature: LicenseManager: AWS License Manager now automates discovery of bring-your-own-license usage across the customers organization. With few simple settings, customers can add bring your own license product information along with licensing rules, which would enable License Manager to automatically track the instances that have the specified products installed. If License Manager detects any violation of licensing rules, it would notify the customers designated license administrator to take corrective action.
* feature: Region: s3 client now support sending request to us-east-1 regional endpoint with `s3UsEast1RegionalEndpoint` client configuration set to `regional`
* feature: Schemas: This release introduces support for Amazon EventBridge schema registry, making it easy to discover and write code for events in EventBridge.

## 2.580.0
* feature: CognitoIdentityServiceProvider: This release adds a new setting for a user pool to configure which recovery methods a user can use to recover their account via the forgot password operation.
* feature: DirectoryService: This release will introduce optional encryption over LDAP network traffic using SSL certificates between customer's self-managed AD and AWS Directory Services instances. The release also provides APIs for Certificate management.
* feature: DynamoDB: 1) Amazon Contributor Insights for Amazon DynamoDB is a diagnostic tool for identifying frequently accessed keys and understanding database traffic trends. 2) Support for displaying new fields when a table's encryption state is Inaccessible or the table have been Archived.
* feature: ElasticInference: Amazon Elastic Inference allows customers to attach Elastic Inference Accelerators to Amazon EC2 and Amazon ECS tasks, thus providing low-cost GPU-powered acceleration and reducing the cost of running deep learning inference. This release allows customers to add or remove tags for their Elastic Inference Accelerators.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now allows configuration of the Live Pre-Roll feature for HLS and DASH streams.
* feature: Organizations: Introduces the DescribeEffectivePolicy action, which returns the contents of the policy that's in effect for the account.
* feature: RDSDataService: Type hints to improve handling of some specific parameter types (date/time, decimal etc) for ExecuteStatement and BatchExecuteStatement APIs
* feature: ResourceGroupsTaggingAPI: You can use tag policies to help standardize on tags across your organization's resources.
* feature: ServerlessApplicationRepository: AWS Serverless Application Repository now supports verified authors. Verified means that AWS has made a good faith review, as a reasonable and prudent service provider, of the information provided by the requester and has confirmed that the requester's identity is as claimed.
* feature: WorkSpaces: For the WorkspaceBundle API, added the image identifier and the time of the last update.

## 2.579.0
* feature: AlexaForBusiness: API update for Alexa for Business: This update enables the use of meeting room configuration that can be applied to a room profile. These settings help improve and measure utilization on Alexa for Business enabled rooms. New features include end meeting reminders, intelligent room release and room utilization analytics report.
* feature: AppConfig: Introducing AWS AppConfig, a new service that enables customers to quickly deploy validated configurations to applications of any size in a controlled and monitored fashion.
* feature: ApplicationAutoScaling: This release supports auto scaling of document classifier endpoints for Comprehend; and supports target tracking based on the average capacity utilization metric for AppStream 2.0 fleets. 
* feature: ApplicationInsights: CloudWatch Application Insights for .NET and SQL Server includes the follwing features: -Tagging Create and manage tags for your applications.-Custom log pattern matching. Define custom log patterns to be detected and monitored.-Resource-level permissions. Specify applications users can access.
* feature: Athena: This release adds additional query lifecycle metrics to the QueryExecutionStatistics object in GetQueryExecution response.
* feature: CloudWatch: This release adds a new feature called "Contributor Insights". "Contributor Insights" supports the following 6 new APIs (PutInsightRule, DeleteInsightRules, EnableInsightRules, DisableInsightRules, DescribeInsightRules and GetInsightRuleReport). 
* feature: CodeBuild: CodeBuild adds support for test reporting
* feature: CognitoIdentityServiceProvider: Amazon Cognito Userpools now supports Sign in with Apple as an Identity Provider.
* feature: Comprehend: Amazon Comprehend now supports real-time analysis with Custom Classification
* feature: CostExplorer: This launch provides customers with access to Cost Category Public Beta APIs.
* feature: DLM: You can now set time based retention policies on Data Lifecycle Manager. With this launch, DLM allows you to set snapshot retention period in the following interval units: days, weeks, months and years.
* feature: EC2: This release adds two new APIs: 1. ModifyDefaultCreditSpecification, which allows you to set default credit specification at the account level per AWS Region, per burstable performance instance family, so that all new burstable performance instances in the account launch using the new default credit specification. 2. GetDefaultCreditSpecification, which allows you to get current default credit specification per AWS Region, per burstable performance instance family. This release also adds new client exceptions for StartInstances and StopInstances.
* feature: ELBv2: This release of Elastic Load Balancing V2 adds new subnet features for Network Load Balancers and a new routing algorithm for Application Load Balancers. 
* feature: Greengrass: IoT Greengrass supports machine learning resources in 'No container' mode.
* feature: IoTSecureTunneling: This release adds support for IoT Secure Tunneling to remote access devices behind restricted firewalls.
* feature: Iot: This release adds: 1) APIs for fleet provisioning claim and template, 2) endpoint configuration and custom domains, 3) support for enhanced custom authentication, d) support for 4 additional audit checks: Device and CA certificate key quality checks, IoT role alias over-permissive check and IoT role alias access to unused services check, 5) extended capability of AWS IoT Rules Engine to support IoT SiteWise rule action. The IoT SiteWise rule action lets you send messages from IoT sensors and applications to IoT SiteWise asset properties
* feature: KMS: AWS Key Management Service (KMS) now enables creation and use of asymmetric Customer Master Keys (CMKs) and the generation of asymmetric data key pairs.
* feature: KinesisAnalyticsV2: Kinesis Data Analytics service adds support to configure Java applications to access resources in a VPC. Also releasing support to configure Java applications to set allowNonRestoreState flag through the service APIs.
* feature: Lambda: Added the function state and update status to the output of GetFunctionConfiguration and other actions. Check the state information to ensure that a function is ready before you perform operations on it. Functions take time to become ready when you connect them to a VPC.Added the EventInvokeConfig type and operations to configure error handling options for asynchronous invocation. Use PutFunctionEventInvokeConfig to configure the number of retries and the maximum age of events when you invoke the function asynchronously.Added on-failure and on-success destination settings for asynchronous invocation. Configure destinations to send an invocation record to an SNS topic, an SQS queue, an EventBridge event bus, or a Lambda function.Added error handling options to event source mappings. This enables you to configure the number of retries, configure the maximum age of records, or retry with smaller batches when an error occurs when a function processes a Kinesis or DynamoDB stream.Added the on-failure destination setting to event source mappings. This enables you to send discarded events to an SNS topic or SQS queue when all retries fail or when the maximum record age is exceeded when a function processes a Kinesis or DynamoDB stream.Added the ParallelizationFactor option to event source mappings to increase concurrency per shard when a function processes a Kinesis or DynamoDB stream.
* feature: LexRuntime: Amazon Lex adds "sessionId" attribute to the PostText and PostContent response.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for 8K outputs and support for QuickTime Animation Codec (RLE) inputs.
* feature: MediaLive: AWS Elemental MediaLive now supports the ability to create a multiple program transport stream (MPTS).
* feature: MediaPackageVod: Adds a domain name to PackagingGroups, representing the fully qualified domain name for Assets created in the group.
* feature: RAM: AWS RAM provides new APIs to view the permissions granted to principals in a resource share. This release also creates corresponding resource shares for supported services that use resource policies, as well as an API to promote them to standard shares that can be managed in RAM.
* feature: RDS: Cluster Endpoints can now be tagged by using --tags in the create-db-cluster-endpoint API
* feature: Redshift: This release contains changes for 1. Redshift Scheduler 2. Update to the DescribeNodeConfigurationOptions to include a new action type recommend-node-config
* feature: SESV2: This release includes support for automatically suppressing email addresses that result in hard bounce or complaint events at the account level, and for managing addresses on this account-level suppression list.
* feature: SSM: AWS Systems Manager Documents now supports more Document Types: ApplicationConfiguration, ApplicationConfigurationSchema and DeploymentStrategy. This release also extends Document Permissions capabilities and introduces a new Force flag for DeleteDocument API.
* feature: WAFV2: This release introduces new set of APIs ("wafv2") for AWS WAF. Major changes include single set of APIs for creating/updating resources in global and regional scope, and rules are configured directly into web ACL instead of being referenced. The previous APIs ("waf" and "waf-regional") are now referred as AWS WAF Classic. For more information visit: https://docs.aws.amazon.com/waf/latest/APIReference/Welcome.html

## 2.578.0
* feature: ACM: This release adds support for Tag-Based IAM for AWS Certificate Manager and adding tags to certificates upon creation.
* feature: ApplicationAutoScaling: Update default endpoint for Application Auto Scaling.
* feature: AutoScalingPlans: Update default endpoint for AWS Auto Scaling.
* feature: CodeBuild: Add Canonical ARN to LogsLocation.
* feature: EC2: This release adds two new APIs (DescribeInstanceTypes and DescribeInstanceTypeOfferings) that give customers access to instance type attributes and regional and zonal offerings.
* feature: EMR: Amazon EMR adds support for concurrent step execution and cancelling running steps. Amazon EMR has added a new Outpost ARN field in the ListCluster and DescribeCluster API responses that is populated for clusters launched in an AWS Outpost subnet.
* feature: ForecastService: This release adds two key updates to existing APIs. 1. Amazon Forecast can now generate forecasts in any quantile using the optional parameter forecastTypes in the CreateForecast API and 2. You can get additional details (metrics and relevant error messages) on your AutoML runs using the DescribePredictor and GetAccuracyMetrics APIs.
* feature: MediaPackageVod: Includes the submission time of Asset ingestion request in the API response for Create/List/Describe Assets.
* feature: Rekognition: This release adds enhanced face filtering support to the IndexFaces API operation, and introduces face filtering for CompareFaces and SearchFacesByImage API operations.
* feature: SSM: Add RebootOption and LastNoRebootInstallOperationTime for DescribeInstancePatchStates and DescribeInstancePatchStatesForPatchGroup API
* feature: STS: Support tagging for STS sessions and tag based access control for the STS APIs

## 2.577.0
* feature: Amplify: This release of AWS Amplify Console introduces support for backend environments. Backend environments are containers for AWS deployments. Each environment is a collection of AWS resources.
* feature: AppSync: AppSync: AWS AppSync now supports the ability to add, configure, and maintain caching for your AWS AppSync GraphQL API.
* feature: ConfigService: AWS Config launches Custom Configuration Items. A new feature which allows customers to publish resource configuration for third-party resources, custom, or on-premises servers.
* feature: Connect: This release adds a new API: StartChatContact. You can use it to programmatically start a chat on the specified Amazon Connect instance. Learn more here: https://docs.aws.amazon.com/connect/latest/APIReference/Welcome.html 
* feature: ConnectParticipant: This release adds 5 new APIs: CreateParticipantConnection, DisconnectParticipant, GetTranscript, SendEvent, and SendMessage. For Amazon Connect chat, you can use them to programmatically perform participant actions on the configured Amazon Connect instance. Learn more here: https://docs.aws.amazon.com/connect-participant/latest/APIReference/Welcome.html
* feature: DynamoDB: With this release, you can convert an existing Amazon DynamoDB table to a global table by adding replicas in other AWS Regions.
* feature: EC2: This release adds support for attaching AWS License Manager Configurations to Amazon Machine Image (AMI) using ImportImage API; and adds support for running different instance sizes on EC2 Dedicated Hosts
* feature: Glue: This release adds support for Glue 1.0 compatible ML Transforms.
* feature: LexModelBuildingService: Amazon Lex now supports Sentiment Analysis
* feature: LexRuntime: Amazon Lex now supports Sentiment Analysis
* feature: SSM: The release contains new API and API changes for AWS Systems Manager Explorer product.
* feature: TranscribeService: With this release, Amazon Transcribe now supports transcriptions from audio sources in Hebrew (he-IL), Swiss German (de-CH), Japanese (ja-JP), Turkish (tr-TR), Arabic-Gulf (ar-AE), Malay (ms-MY), Telugu (te-IN)

## 2.576.0
* feature: Chime: Adds APIs to create and manage meeting session resources for the Amazon Chime SDK
* feature: CloudTrail:  1. This release adds two new APIs, GetInsightSelectors and PutInsightSelectors, which let you configure CloudTrail Insights event delivery on a trail. An Insights event is a new type of event that is generated when CloudTrail detects unusual activity in your AWS account. In this release, only "ApiCallRateInsight" is a supported Insights event type. 2. This release also adds the new "ExcludeManagementEventSource" option to the existing PutEventSelectors API. This field currently supports only AWS Key Management Services.
* feature: CodeCommit: This release adds support for creating pull request approval rules and pull request approval rule templates in AWS CodeCommit. This allows developers to block merges of pull requests, contingent on the approval rules being satisfiied.
* feature: DLM: DLM now supports Fast Snapshot Restore. You can enable Fast Restore on snapshots created by DLM, provide the AZs and the number of snapshots to be enabled with this capability.
* feature: DataSync: Update to configure task to run periodically on a schedule
* feature: Discovery: New exception type for use with Migration Hub home region
* feature: EC2: This release of Amazon Elastic Compute Cloud (Amazon EC2) introduces support for Amazon Elastic Block Store (Amazon EBS) fast snapshot restores.
* feature: ECS: Added support for CPU and memory task-level overrides on the RunTask and StartTask APIs.  Added location information to Tasks.
* feature: FSx: Announcing a Multi-AZ deployment type for Amazon FSx for Windows File Server, providing fully-managed Windows file storage with high availability and redundancy across multiple AWS Availability Zones.
* feature: Firehose: With this release, Amazon Kinesis Data Firehose allows server side encryption with customer managed CMKs. Customer managed CMKs ( "Customer Master Keys") are AWS Key Management Service (KMS) keys that are fully managed by the customer. With customer managed CMKs, customers can establish and maintain their key policies, IAM policies, rotating policies and add tags. For more information about AWS KMS and CMKs, please refer to:  https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html. Please refer to the following link to create CMKs: https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys-create-cmk.html
* feature: MediaStore: This release fixes a broken link in the SDK documentation.
* feature: MigrationHub: New exception type for use with Migration Hub home region
* feature: MigrationHubConfig: AWS Migration Hub Config Service allows you to get and set the Migration Hub home region for use with AWS Migration Hub and Application Discovery Service
* feature: QuickSight: Amazon QuickSight now supports programmatic creation and management of data sources, data sets, dashboards and templates with new APIs. Templates hold dashboard metadata, and can be used to create copies connected to the same or different dataset as required. Also included in this release are APIs for SPICE ingestions, fine-grained access control over AWS resources using AWS Identity and Access Management (IAM) policies, as well AWS tagging. APIs are supported for both Standard and Enterprise Edition, with edition-specific support for specific functionality.
* feature: S3: This release introduces support for Amazon S3 Replication Time Control, a new feature of S3 Replication that provides a predictable replication time backed by a Service Level Agreement. S3 Replication Time Control helps customers meet compliance or business requirements for data replication, and provides visibility into the replication process with new Amazon CloudWatch Metrics.
* feature: StorageGateway: The new DescribeAvailabilityMonitorTest API provides the results of the most recent High Availability monitoring test. The new StartAvailabilityMonitorTest API verifies the storage gateway is configured for High Availability monitoring. The new ActiveDirectoryStatus response element has been added to the DescribeSMBSettings and JoinDomain APIs to indicate the status of the gateway after the most recent JoinDomain operation. The new TimeoutInSeconds parameter of the JoinDomain API allows for the configuration of the timeout in which the JoinDomain operation must complete.
* feature: TranscribeService: With this release Amazon Transcribe enables alternative transcriptions so that you can see different interpretations of transcribed audio.

## 2.575.0
* bugfix: IMDS: Signed IMDS workflow
* bugfix: IMDS: Type definitions update to signed IMDS workflow
* feature: AutoScaling: Amazon EC2 Auto Scaling now supports Instance Weighting and Max Instance Lifetime. Instance Weighting allows specifying the capacity units for each instance type included in the MixedInstancesPolicy and how they would contribute to your application's performance. Max Instance Lifetime allows specifying the maximum length of time that an instance can be in service. If any instances are approaching this limit, Amazon EC2 Auto Scaling gradually replaces them.
* feature: CloudFormation: This release of AWS CloudFormation StackSets enables users to detect drift on a stack set and the stack instances that belong to that stack set.
* feature: CodeBuild: Add support for ARM and GPU-enhanced build environments and a new SSD-backed Linux compute type with additional CPU and memory in CodeBuild
* feature: ConfigService: AWSConfig launches support for conformance packs. A conformance pack is a new resource type that allows you to package a collection of Config rules and remediation actions into a single entity. You can create and deploy conformance packs into your account or across all accounts in your organization
* feature: EC2: This release adds support for RunInstances to specify the metadata options for new instances; adds a new API, ModifyInstanceMetadataOptions, which lets you modify the metadata options for a running or stopped instance; and adds support for CreateCustomerGateway to specify a device name.
* feature: ELBv2: This release allows forward actions on Application Load Balancers to route requests to multiple target groups, based on the weight you specify for each target group.
* feature: IAM: IAM reports the timestamp when a role's credentials were last used to make an AWS request. This helps you identify unused roles and remove them confidently from your AWS accounts.
* feature: Iot: As part of this release, we are extending the capability of AWS IoT Rules Engine to send messages directly to customer's own web services/applications. Customers can now create topic rules with HTTP actions to route messages from IoT Core directly to URL's that they own. Ownership is proved by creating and confirming topic rule destinations.
* feature: Lambda: This release provides three new runtimes to support Node.js 12 (initially 12.13.0), Python 3.8 and Java 11.  

## 2.574.0
* feature: CloudFormation: This release introduces APIs for the CloudFormation Registry, a new service to submit and discover resource providers with which you can manage third-party resources natively in CloudFormation.
* feature: CostExplorer: add EstimatedOnDemandCostWithCurrentCommitment to GetSavingsPlansPurchaseRecommendationRequest API
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces support for using and managing message templates for messages that are sent through the voice channel. It also introduces support for specifying default values for message variables in message templates. 
* feature: S3: Added support for S3 Replication for existing objects. This release allows customers who have requested and been granted access to replicate existing S3 objects across buckets.
* feature: SSM: The release contains new API and API changes for AWS Systems Manager Explorer product.
* feature: SageMaker: Amazon SageMaker now supports multi-model endpoints to host multiple models on an endpoint using a single inference container.
* feature: SageMakerRuntime: Amazon SageMaker Runtime now supports a new TargetModel header to invoke a specific model hosted on multi model endpoints.

## 2.573.0
* bugfix: clock skew: update clock skew duration from 30s to 300s
* feature: Chime: This release adds support for Chime Room Management APIs
* feature: CognitoIdentityServiceProvider: This release adds a new option in the User Pool to allow specifying sender's name in the emails sent by Amazon Cognito. This release also adds support to add SES Configuration Set to the emails sent by Amazon Cognito.
* feature: EC2: You can now add tags while copying snapshots. Previously, a user had to first copy the snapshot and then add tags to the copied snapshot manually. Moving forward, you can specify the list of tags you wish to be applied to the copied snapshot as a parameter on the Copy Snapshot API. 
* feature: EKS: Introducing Amazon EKS managed node groups, a new feature that lets you easily provision worker nodes for Amazon EKS clusters and keep them up to date using the Amazon EKS management console, CLI, and APIs.
* feature: EMR: Access to the cluster ARN makes it easier for you to author resource-level permissions policies in AWS Identity and Access Management. To simplify the process of obtaining the cluster ARN, Amazon EMR has added a new field containing the cluster ARN to all API responses that include the cluster ID.
* feature: GuardDuty: This release includes new operations related to findings export, including: CreatePublishingDestination, UpdatePublishingDestination, DescribePublishingDestination, DeletePublishingDestination and ListPublishingDestinations.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for DolbyVision encoding, and SCTE35 & ESAM insertion to DASH ISO EMSG.
* feature: WorkSpaces: Added APIs to register your directories with Amazon WorkSpaces and to modify directory details. 

## 2.572.0
* feature: CognitoIdentityServiceProvider: This release adds a new setting at user pool client to prevent user existence related errors during authentication, confirmation, and password recovery related operations. This release also adds support to enable or disable specific authentication flows for a user pool client.
* feature: Connect: This release enhances the existing user management APIs and adds 3 new APIs - TagResource, UntagResource, and ListTagsForResource to support tagging Amazon Connect users, which facilitates more granular access controls for Amazon Connect users within an Amazon Connect instance. You can learn more about the new APIs here: https://docs.aws.amazon.com/connect/latest/APIReference/Welcome.html.
* feature: MarketplaceMetering: Added CustomerNotEntitledException in MeterUsage API for Container use case.
* feature: Personalize: Amazon Personalize: Adds ability to get batch recommendations by creating a batch inference job.
* feature: SSM: Updates support for adding attachments to Systems Manager Automation documents

## 2.571.0
* feature: CloudSearch: Amazon CloudSearch domains let you require that all traffic to the domain arrive over HTTPS. This security feature helps you block clients that send unencrypted requests to the domain.
* feature: DLM: You can now add tags to a lifecycle policy in Data Lifecycle Manager (DLM). Tags allow you to categorize your policies in different ways, such as by department, purpose or owner. You can also enable resource level permissions based on tags to set access control on ability to modify or delete a tagged policy.
* feature: DataExchange: Introducing AWS Data Exchange, a service that makes it easy for AWS customers to securely create, manage, access, and exchange data sets in the cloud.
* feature: Iot: This release adds the custom fields definition support in the index definition for AWS IoT Fleet Indexing Service. Custom fields can be used as an aggregation field to run aggregations with both existing GetStatistics API and newly added GetCardinality, GetPercentiles APIs. GetStatistics will return all statistics (min/max/sum/avg/count...) with this release. For more information, please refer to our latest documentation: https://docs.aws.amazon.com/iot/latest/developerguide/iot-indexing.html
* feature: SESV2: This is the first release of version 2 of the Amazon SES API. You can use this API to configure your Amazon SES account, and to send email. This API extends the functionality that exists in the previous version of the Amazon SES API.

## 2.570.0
* feature: CodePipeline: AWS CodePipeline now supports the use of variables in action configuration.
* feature: DynamoDB: Amazon DynamoDB enables you to restore your data to a new DynamoDB table using a point-in-time or on-demand backup. You now can modify the settings on the new restored table. Specifically, you can exclude some or all of the local and global secondary indexes from being created with the restored table. In addition, you can change the billing mode and provisioned capacity settings.
* feature: MarketplaceCatalog: This is the first release for the AWS Marketplace Catalog service which allows you to list, describe and manage change requests on your published entities on AWS Marketplace. 
* feature: TranscribeService: With this release, Amazon Transcribe now supports transcriptions from audio sources in Welsh English (en-WL), Scottish English(en-AB), Irish English(en-IE), Farsi(fa-IR), Tamil(ta-IN), Indonesian(id-ID), Portuguese (pt-PT), Dutch(nl-NL).

## 2.569.0
* feature: CloudFormation: The Resource Import feature enables customers to import existing AWS resources into new or existing CloudFormation Stacks.
* feature: CostExplorer: This launch provides customers with access to GetCostAndUsageWithResources API.

## 2.568.0
* feature: CognitoIdentity: This release adds support for disabling classic flow.

## 2.567.0
* feature: Comprehend: This release adds new languages (ar, hi, ko, ja, zh, zh-TW) for Amazon Comprehend's DetectSentiment, DetectEntities, DetectKeyPhrases, BatchDetectSentiment, BatchDetectEntities and BatchDetectKeyPhrases APIs
* feature: SSM: AWS Systems Manager Session Manager target length increased to 400.
* feature: SSO: This is an initial release of AWS Single Sign-On (SSO) end-user access. This release adds support for accessing AWS accounts assigned in AWS SSO using short term credentials.
* feature: SSOOIDC: This is an initial release of AWS Single Sign-On OAuth device code authorization service.

## 2.566.0
* feature: SavingsPlans: This is the first release of Savings Plans, a new flexible pricing model that offers low prices on Amazon EC2 and AWS Fargate usage.

## 2.565.0
* feature: CodeBuild: Add support for Build Number, Secrets Manager and Exported Environment Variables.
* feature: CostExplorer: This launch provides customers with access to Savings Plans management APIs.
* feature: EFS: EFS customers can select a lifecycle policy that automatically moves files that have not been accessed for 7 days into the EFS Infrequent Access (EFS IA) storage class. EFS IA provides price/performance that is cost-optimized for files that are not accessed every day.
* feature: SavingsPlans: This is the first release of Savings Plans, a new flexible pricing model that offers low prices on Amazon EC2 and AWS Fargate usage.
* feature: Signer: This release adds support for tagging code-signing profiles in AWS Signer.

## 2.564.0
* feature: CodeStarNotifications: This release adds a notification manager for events in repositories, build projects, deployments, and pipelines. You can now configure rules and receive notifications about events that occur for resources. Each notification includes a status message as well as a link to the resource (repository, build project, deployment application, or pipeline) whose event generated the notification.
* feature: Config: Allow shortcutting in customBackoff based on error

## 2.563.0
* feature: RoboMaker: RoboMaker Fleet Management launch a feature to verify your robot is ready to download and install the new robot application using a download condition file, which is a script run on the robot prior to downloading the new deployment. 

## 2.562.0
* feature: CloudTrail: This release adds two new APIs, GetTrail and ListTrails, and support for adding tags when you create a trail by using a new TagsList parameter on CreateTrail operations.
* feature: DMS: This release contains task timeline attributes in replication task statistics. This release also adds a note to the documentation for the CdcStartPosition task request parameter. This note describes how to enable the use of native CDC start points for a PostgreSQL source by setting the new slotName extra connection attribute on the source endpoint to the name of an existing logical replication slot.
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces support for using and managing journeys, and querying analytics data for journeys.

## 2.561.0
* feature: Amplify: This release of AWS Amplify Console introduces support for Web Previews. This feature allows user to create ephemeral branch deployments from pull request submissions made to a connected repository.  A pull-request preview deploys every pull request made to your Git repository to a unique preview URL.
* feature: S3: S3 Inventory now supports a new field 'IntelligentTieringAccessTier' that reports the access tier (frequent or infrequent) of objects stored in Intelligent-Tiering storage class.

## 2.560.0
* feature: ElastiCache: Amazon ElastiCache for Redis 5.0.5 now allows you to modify authentication tokens by setting and rotating new tokens. You can now modify active tokens while in use, or add brand-new tokens to existing encryption-in-transit enabled clusters that were previously setup without authentication tokens. This is a two-step process that allows you to set and rotate the token without interrupting client requests.

## 2.559.0
* feature: AppStream: Adds support for providing domain names that can embed streaming sessions
* feature: Cloud9: Added CREATING and CREATE_FAILED environment lifecycle statuses.  
* feature: Connect: enable cors to make connect service available in default browser built
* feature: X-ray, Connect, IotAnalytics: updated SERVICES.md for 3 services, x-ray, connect, IotAnalytics

## 2.558.0
* feature: S3: Adding support in SelectObjectContent for scanning a portion of an object specified by a scan range.

## 2.557.0
* feature: ECR: This release of Amazon Elastic Container Registry Service (Amazon ECR) introduces support for image scanning. This identifies the software vulnerabilities in the container image based on the Common Vulnerabilities and Exposures (CVE) database.
* feature: ElastiCache: Amazon ElastiCache adds support for migrating Redis workloads hosted on Amazon EC2 into ElastiCache by syncing the data between the source Redis cluster and target ElastiCache for Redis cluster in real time. For more information, see https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/migrate-to-elasticache.html.
* feature: Transfer: This release adds logical directories support to your AWS SFTP server endpoint, so you can now create logical directory structures mapped to Amazon Simple Storage Service (Amazon S3) bucket paths for users created and stored within the service. Amazon S3 bucket names and paths can now be hidden from AWS SFTP users, providing an additional level of privacy to meet security requirements. You can lock down your SFTP users' access to designated folders (commonly referred to as 'chroot'), and simplify complex folder structures for data distribution through SFTP without replicating files across multiple users.

## 2.556.0
* feature: AppMesh: This release adds support for the gRPC and HTTP/2 protocols.
* feature: Chime: * This release introduces Voice Connector PDX region and defaults previously created Voice Connectors to IAD. You can create Voice Connector Groups and add region specific Voice Connectors to direct telephony traffic across AWS regions in case of regional failures. With this release you can add phone numbers to Voice Connector Groups and can bulk move phone numbers between Voice Connectors, between Voice Connector and Voice Connector Groups and between Voice Connector Groups. Voice Connector now supports additional settings to enable SIP Log capture. This is in addition to the launch of Voice Connector Cloud Watch metrics in this release. This release also supports assigning outbound calling name (CNAM) to AWS account and individual phone numbers assigned to Voice Connectors. * Voice Connector now supports a setting to enable real time audio streaming delivered via Kinesis Audio streams. Please note that recording Amazon Chime Voice Connector calls with this feature maybe be subject to laws or regulations regarding the recording of telephone calls and other electronic communications. AWS Customer and their end users' have the responsibility to comply with all applicable laws regarding the recording, including properly notifying all participants in a recorded session or to a recorded communication that the session or communication is being recorded and obtain their consent.
* feature: EC2: This release updates CreateFpgaImage to support tagging FPGA images on creation
* feature: GameLift: Amazon GameLift offers expanded hardware options for game hosting: Custom game builds can use the Amazon Linux 2 operating system, and fleets for both custom builds and Realtime servers can now use C5, M5, and R5 instance types.
* feature: SageMaker: Adds support for the new family of Elastic Inference Accelerators (eia2) for SageMaker Hosting and Notebook Services

## 2.555.0
* feature: Connect: This release adds 4 new APIs ListQueues, ListPhoneNumbers, ListContactFlows, and ListHoursOfOperations, which can be used to programmatically list Queues, PhoneNumbers, ContactFlows, and HoursOfOperations configured for an Amazon Connect instance respectively. You can learn more about the new APIs here: https://docs.aws.amazon.com/connect/latest/APIReference/Welcome.html.
* feature: Polly: Amazon Polly adds new female voices: US Spanish - Lupe and Brazilian Portuguese - Camila; both voices are available in Standard and Neural engine.

## 2.554.0
* feature: IoTEvents: Add support for new serial evaluation method for events in a detector model.
* feature: OpsWorksCM: AWS OpsWorks for Chef Automate (OWCA) now allows customers to use a custom domain and respective certificate, for their AWS OpsWorks For Chef Automate servers. Customers can now provide a CustomDomain, CustomCertificate and CustomPrivateKey in CreateServer API to configure their Chef Automate servers with a custom domain and certificate.

## 2.553.0
* feature: CloudWatch: New Period parameter added to MetricDataQuery structure.

## 2.552.0
* feature: Batch: Adding support for Compute Environment Allocation Strategies 
* feature: RDS: Amazon RDS now supports Amazon RDS on VMware with the introduction of APIs related to Custom Availability Zones and Media installation.

## 2.551.0
* feature: IoTAnalytics: enable cors to make IoTAnalytics available in default browser build
* feature: Kafka: AWS MSK has added support for adding brokers to a cluster.
* feature: MarketplaceCommerceAnalytics: add 2 more values for the supporting sections - age of past due funds + uncollected funds breakdown
* feature: RoboMaker: This release adds support for ROS2 Dashing as a beta feature

## 2.550.0
* feature: KinesisVideoArchivedMedia: Add ON_DISCONTINUITY mode to the GetHLSStreamingSessionURL API

## 2.549.0
* bugfix: Request Signing: This change allows requests to a service to be signed if the api.json doesn't specify a signatureVersion or authtype, but the configuration has a signatureVersion specified. Prior to this change, the logic to create a signer would use signatureVersion specified in the config, but the code would never reach it if api.json signatureVersion or authtype weren't defined.
* feature: Personalize: AWS Personalize: Adds ability to create a solution version using FULL or UPDATE training mode
* feature: Retry: retry all 429 status code exceptions

## 2.548.0
* feature: Greengrass: Greengrass OTA service supports Raspbian/Armv6l platforms.

## 2.547.0
* feature: EC2: New EC2 M5n, M5dn, R5n, R5dn instances with 100 Gbps network performance and Elastic Fabric Adapter (EFA) for ultra low latency; New A1.metal bare metal instance powered by AWS Graviton Processors
* feature: FMS: Firewall Manager now supports Amazon VPC security groups, making it easier to configure and manage security groups across multiple accounts from a single place.
* feature: IoTAnalytics: Add `completionTime` to API call ListDatasetContents.
* feature: LexRuntime: Amazon Lex now supports Session API checkpoints

## 2.546.0
* feature: ElastiCache: Amazon ElastiCache now allows you to apply available service updates on demand to your Memcached and Redis Cache Clusters. Features included: (1) Access to the list of applicable service updates and their priorities. (2) Service update monitoring and regular status updates. (3) Recommended apply-by-dates for scheduling the service updates. (4) Ability to stop and later re-apply updates. For more information, see https://docs.aws.amazon.com/AmazonElastiCache/latest/mem-ug/Self-Service-Updates.html and https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/Self-Service-Updates.html
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for Dolby Atmos encoding, up to 36 outputs, accelerated transcoding with frame capture and preferred acceleration feature.

## 2.545.0
* feature: DataSync: Add Sync options to enable/disable TaskQueueing
* feature: Firehose: With this release, you can use Amazon Kinesis Firehose delivery streams to deliver streaming data to Amazon Elasticsearch Service version 7.x clusters. For technical documentation, look for CreateDeliveryStream operation in Amazon Kinesis Firehose API reference.

## 2.544.0
* feature: CORS: Add Xray to default browser SDK distribution
* feature: DirectConnect: This release adds a service provider field for physical connection creation and provides a list of available partner providers for each Direct Connect location.
* feature: Firehose: Amazon Kinesis Data Firehose now allows delivering data to Elasticsearch clusters set up in a different AWS account than the Firehose AWS account. For technical documentation, look for ElasticsearchDestinationConfiguration in the Amazon Kinesis Firehose API reference.
* feature: Glue: AWS Glue now provides ability to use custom certificates for JDBC Connections.
* feature: Pinpoint: This release of the Amazon Pinpoint API introduces support for using and managing message templates.
* feature: PinpointEmail: This release of the Amazon Pinpoint Email API introduces support for using and managing message templates.
* feature: Snowball: AWS Snowball Edge now allows you to perform an offline update to the software of your Snowball Edge device when your device is not connected to the internet. Previously, updating your Snowball Edge's software required that the device be connected to the internet or be sent back to AWS. Now, you can keep your Snowball Edge software up to date even if your device(s) cannot connect to the internet, or are required to run in an air-gapped environment. To complete offline updates, download the software update from a client machine with connection to the internet using the AWS Command Line Interface (CLI). Then, have the Snowball Edge device download and install the software update using the Snowball Edge device API. For more information about offline updates, visit the Snowball Edge documentation page.

## 2.543.0
* feature: CognitoIdentityServiceProvider: This release adds ClientMetadata input parameter to multiple Cognito User Pools operations, making this parameter available to the customer configured lambda triggers as applicable. 
* feature: MediaPackage: New Harvest Job APIs to export segment-accurate content windows from MediaPackage Origin Endpoints to S3. See https://docs.aws.amazon.com/mediapackage/latest/ug/harvest-jobs.html for more info

## 2.542.0
* feature: EC2: This release allows customers to purchase regional EC2 RIs on a future date.
* feature: ES: Amazon Elasticsearch Service now supports configuring additional options for domain endpoint, such as whether to require HTTPS for all traffic.

## 2.541.0
* feature: Lightsail: This release adds support for the automatic snapshots add-on for instances and block storage disks.

## 2.540.0
* feature: DocDB: This release provides support for describe and modify CA certificates.

## 2.539.0
* feature: MQ: Amazon MQ now includes the ability to scale your brokers by changing the host instance type. See the hostInstanceType property of UpdateBrokerInput (https://docs.aws.amazon.com/amazon-mq/latest/api-reference/brokers-broker-id.html#brokers-broker-id-model-updatebrokerinput), and pendingHostInstanceType property of DescribeBrokerOutput (https://docs.aws.amazon.com/amazon-mq/latest/api-reference/brokers-broker-id.html#brokers-broker-id-model-describebrokeroutput).
* feature: RDS: This release adds support for creating a Read Replica with Active Directory domain information. This release updates RDS API to indicate whether an OrderableDBInstanceOption supports Kerberos Authentication.
* feature: WAF: Lowering the threshold for Rate Based rule from 2000 to 100.

## 2.538.0
* feature: Amplify: This release adds access logs APIs and artifact APIs for AWS Amplify Console.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) removes FirelensConfiguration from the DescribeTask output during the FireLens public preview.

## 2.537.0
* feature: SSM: This release updates the AWS Systems Manager Parameter Store PutParameter and LabelParameterVersion APIs to return the "Tier" of parameter created/updated and the "parameter version" labeled respectively. 

## 2.536.0
* feature: DMS: This release adds a new DeleteConnection API to delete the connection between a replication instance and an endpoint. It also adds an optional S3 setting to specify the precision of any TIMESTAMP column values written to an S3 object file in .parquet format.
* feature: ForecastService: CORS support enabled on ForecastService and ForecastQueryService
* feature: GlobalAccelerator: API Update for AWS Global Accelerator to support for DNS aliasing.
* feature: SageMaker: Enable G4D and R5 instances in SageMaker Hosting Services

## 2.535.0
* feature: ComprehendMedical: Use Amazon Comprehend Medical to analyze medical text stored in the specified Amazon S3 bucket. Use the console to create and manage batch analysis jobs, or use the batch APIs to detect both medical entities and protected health information (PHI). The batch APIs start, stop, list, and retrieve information about batch analysis jobs. This release also includes DetectEntitiesV2 operation which returns the Acuity and Direction entities as attributes instead of types.
* feature: DataSync: Added S3StorageClass, OverwriteMode sync option, and ONLY_FILES_TRANSFERRED setting for the VerifyMode sync option.
* feature: TranscribeService: With this update Amazon Transcribe enables you to provide an AWS KMS key to encrypt your transcription output.

## 2.534.0
* feature: RDSDataService: RDS Data API now supports Amazon Aurora Serverless PostgreSQL databases.
* feature: Redshift: Adds API operation DescribeNodeConfigurationOptions and associated data structures.

## 2.533.0
* feature: EC2: G4 instances are Amazon EC2 instances based on NVIDIA T4 GPUs and are designed to provide cost-effective machine learning inference for applications, like image classification, object detection, recommender systems, automated speech recognition, and language translation. G4 instances are also a cost-effective platform for building and running graphics-intensive applications, such as remote graphics workstations, video transcoding, photo-realistic design, and game streaming in the cloud. To get started with G4 instances visit https://aws.amazon.com/ec2/instance-types/g4.
* feature: Greengrass: Greengrass OTA service now returns the updated software version in the PlatformSoftwareVersion parameter of a CreateSoftwareUpdateJob response
* feature: RDS: Add a new LeaseID output field to DescribeReservedDBInstances, which shows the unique identifier for the lease associated with the reserved DB instance. AWS Support might request the lease ID for an issue related to a reserved DB instance.
* feature: WorkSpaces: Adds the WorkSpaces restore feature

## 2.532.0
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for container image manifest digests. This enables you to identify all tasks launched using a container image pulled from ECR in order to correlate what was built with where it is running.
* feature: Glue: AWS Glue DevEndpoints now supports GlueVersion, enabling you to choose Apache Spark 2.4.3 (in addition to Apache Spark 2.2.1). In addition to supporting the latest version of Spark, you will also have the ability to choose between Python 2 and Python 3.
* feature: MediaConnect: When you grant an entitlement, you can now specify the percentage of the entitlement data transfer that you want the subscriber to be responsible for.

## 2.531.0
* bugfix: Dependency: Pin the dependency to the latest
* feature: APIGateway: Amazon API Gateway simplifies accessing PRIVATE APIs by allowing you to associate one or more Amazon Virtual Private Cloud (VPC) Endpoints to a private API. API Gateway will create and manage DNS alias records necessary for easily invoking the private APIs. With this feature, you can leverage private APIs in web applications hosted within your VPCs.
* feature: RAM: AWS RAM provides a new ListPendingInvitationResources API action that lists the resources in a resource share that is shared with you but that the invitation is still pending for
* feature: WAFRegional: Lowering the threshold for Rate Based rule from 2000 to 100.

## 2.530.0
* feature: Athena: This release adds DataManifestLocation field indicating the location and file name of the data manifest file. Users can get a list of files that the Athena query wrote or intended to write from the manifest file.
* feature: Personalize: [Personalize] Adds trainingHours to solutionVersion properties.

## 2.529.0
* feature: EKS: This release lets customers add tags to an Amazon EKS cluster. These tags can be used to control access to the EKS API for managing the cluster using IAM. The Amazon EKS TagResource API allows customers to associate tags with their cluster. Customers can list tags for a cluster using the ListTagsForResource API and remove tags from a cluster with the UntagResource API. Note: tags are specific to the EKS cluster resource, they do not propagate to other AWS resources used by the cluster.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added support for multi-DRM SPEKE with CMAF outputs, MP3 ingest, and options for improved video quality.

## 2.528.0
* feature: EC2: Fix for FleetActivityStatus and FleetStateCode enum
* feature: MediaLive: AWS Elemental MediaLive now supports High Efficiency Video Coding (HEVC) for standard-definition (SD), high-definition (HD), and ultra-high-definition (UHD) encoding with HDR support.Encoding with HEVC offers a number of advantages. While UHD video requires an advanced codec beyond H.264 (AVC), high frame rate (HFR) or High Dynamic Range (HDR) content in HD also benefit from HEVC's advancements. In addition, benefits can be achieved with HD and SD content even if HDR and HFR are not needed.
* feature: WorkMailMessageFlow: This release allows customers to access email messages as they flow to and from Amazon WorkMail.

## 2.527.0
* feature: ConfigService: Adding input validation for the OrganizationConfigRuleName string.
* feature: EC2: This release adds support for new data fields and log format in VPC flow logs.
* feature: MediaConnect: This release adds support for the RIST protocol on sources and outputs.
* feature: RDS: This release allows customers to specify a custom parameter group when creating a Read Replica, for DB engines which support this feature.
* feature: StepFunctions: Fixing letter case in Map history event details to be small case

## 2.526.0
* feature: StorageGateway: The CloudWatchLogGroupARN parameter of the UpdateGatewayInformation API allows for configuring the gateway to use a CloudWatch log-group where Storage Gateway health events will be logged. 

## 2.525.0
* bugfix: RDS: Make async RDS.Signer.getAuthToken call pass underlying credential errors to callback
* feature: AppMesh: This release adds support for http retry policies.
* feature: AppStream: IamRoleArn support in CreateFleet, UpdateFleet, CreateImageBuilder APIs
* feature: Credentials: Added chaining support in TokenFileWebIdentityCredentials
* feature: EC2: This release expands Site-to-Site VPN tunnel options to allow customers to restrict security algorithms and configure timer settings for VPN connections. Customers can specify these new options while creating new VPN connections, or they can modify the tunnel options on existing connections using a new API.
* feature: Endpoints: Sts client now supports sending requests to regional endpoints. You can opt in by setting stsRegionalEndpoints client config or AWS_STS_REGIONAL_ENDPOINTS environment or sts_regional_endpoints config file entry to 'regional'
* feature: MarketplaceCommerceAnalytics: Add FDP+FPS (monthly_revenue_field_demonstration_usage + monthly_revenue_flexible_payment_schedule)  to Marketplace Commerce Analytics Service
* feature: QLDB: (New Service) Amazon QLDB is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log owned by a central trusted authority. Amazon QLDB is a new class of serverless database that eliminates the need to engage in the complex development effort of building your own ledger-like applications and it automatically scales to support the demands of your application. Introduces Amazon QLDB API operations needed for managing Amazon QLDB ledgers. This includes the ability to manage Amazon QLDB ledgers, cryptographically verify documents, and export the journal in a ledger.
* feature: QLDBSession: (New Service) Amazon QLDB is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log owned by a central trusted authority. Amazon QLDB is a new class of serverless database that eliminates the need to engage in the complex development effort of building your own ledger-like applications and it automatically scales to support the demands of your application. Introduces Amazon QLDB API operations needed for interacting with data in Amazon QLDB ledgers.
* feature: RoboMaker: Support for Connectivity to Simulation. When you need to interact with the applications in your simulation job, you can connect to your robot application or simulation application with port forwarding. When you configure port forwarding, traffic will be forwarded from the simulation job port to the application port. Port forwarding makes it easy to connect with tools such as ROS Bridge and other tools. This can be useful when you want to debug or run custom tools to interact with your applications. 

## 2.524.0
* feature: ConfigService: AWS Config now includes the option for marking RemediationConfigurations as automatic, removing the need to call the StartRemediationExecution API. Manual control over resource execution rate is also included, and RemediationConfigurations are now ARN addressable. Exceptions to exclude account resources from being remediated can be configured with the new PutRemediationExceptions, DescribeRemediationExceptions, and DeleteRemediationExceptions APIs.

## 2.523.0
* feature: EKS: Amazon EKS DescribeCluster API returns a new OIDC issuer field that can be used to create OIDC identity provider for IAM for Service Accounts feature.
* feature: StepFunctions: Added support for new history events
* feature: TranscribeService: MediaFormat is now optional for StartTranscriptionJob API.

## 2.522.0
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for attaching Amazon Elastic Inference accelerators to your containers. This enables you to run deep learning inference workloads with hardware acceleration in a more efficient way.
* feature: GameLift: You can now make use of PKI resources to provide more secure connections between your game clients and servers.  To learn more, please refer to the public Amazon GameLift documentation.

## 2.521.0
* bugfix: Credentials: fix stsConfig typing on chainable_temporary_credentials
* feature: ApiGatewayManagementApi: You can use getConnection to return information about the connection (when it is connected, IP address, etc) and deleteConnection to disconnect the given connection
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for modifying the cluster settings for existing clusters, which enables you to toggle whether Container Insights is enabled or not. Support is also introduced for custom log routing using the ECS FireLens integration.
* feature: MQ: Adds support for updating security groups selection of an Amazon MQ broker.

## 2.520.0
* feature: ApplicationAutoScaling: With the current release, you can suspend and later resume any of the following scaling actions in Application Auto Scaling: scheduled scaling actions, dynamic scaling in actions, dynamic scaling out actions.
* feature: CodePipeline: Introducing pipeline execution trigger details in ListPipelineExecutions API.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for including Docker container IDs in the API response when describing and stopping tasks. This enables customers to easily map containers to the tasks they are associated with.
* feature: ElastiCache: Amazon ElastiCache for Redis now supports encryption at rest using customer managed customer master keys (CMKs) in AWS Key Management Service (KMS). Amazon ElastiCache now supports cluster names upto 40 characters for replicationGoups and upto 50 characters for cacheClusters.
* feature: Lambda: Adds a "MaximumBatchingWindowInSeconds" parameter to event source mapping api's. Usable by Dynamodb and Kinesis event sources.
* feature: S3: add support for AWS.S3.getSignedUrlPromise which returns a promise for S3 presigned url

## 2.519.0
* feature: GlobalAccelerator: API Update for AWS Global Accelerator Client IP Preservation
* feature: MediaConvert: This release adds the ability to send a job to an on-demand queue while simulating the performance of a job sent to a reserved queue. Use this setting to estimate the number of reserved transcoding slots (RTS) you need for a reserved queue.
* feature: SQS: Added support for message system attributes, which currently lets you send AWS X-Ray trace IDs through Amazon SQS.

## 2.518.0
* bugfix: Credentials: Update environment variable names in TokenFileWebIdentityCredentials
* feature: SSM: This feature adds "default tier" to the AWS Systems Manager Parameter Store for parameter creation and update. AWS customers can now set the "default tier" to one of the following values: Standard (default), Advanced or Intelligent-Tiering.  This allows customers to create advanced parameters or parameters in corresponding tiers with one setting rather than code change to specify parameter tiers.
* feature: SecurityHub: This release resolves an issue with the DescribeHub action, changes the MasterId and InvitationId parameters for AcceptInvitation to Required, and changes the AccountIds parameter for DeleteInvitations and DeclineInvitations to Required.

## 2.517.0
* feature: Credentials: Added TokenFileWebIdentityCredentials
* feature: EC2: This release of EC2 VM Import Export adds support for exporting Amazon Machine Image(AMI)s to a VM file
* feature: MediaPackageVod: Adds optional Constant Initialization Vector (IV) to HLS Encryption for MediaPackage VOD.
* feature: TranscribeService: Amazon Transcribe - support transcriptions from audio sources in Russian (ru-RU) and Chinese (zh-CN).

## 2.516.0
* feature: DataSync: This release adds support for SMB location type.
* feature: RDS: This release allows users to enable RDS Data API while creating Aurora Serverless databases. 

## 2.515.0
* feature: ElastiCache: ElastiCache extends support for Scale down for Redis Cluster-mode enabled and disabled replication groups 
* feature: ForecastQueryService: Amazon Forecast is a fully managed machine learning service that makes it easy for customers to generate accurate forecasts using their historical time-series data
* feature: ForecastService: Amazon Forecast is a fully managed machine learning service that makes it easy for customers to generate accurate forecasts using their historical time-series data
* feature: PersonalizeRuntime: Increased limits on number of items recommended and reranked: The maximum number of results returned from getRecommendations API has been increased to 200. The maximum number of items which can be reranked via getPersonalizedRanking API has been increased to 200.
* feature: SQS: This release provides a way to add metadata tags to a queue when it is created. You can use tags to organize and identify your Amazon SQS queues for cost allocation.
* feature: SageMaker: Amazon SageMaker now supports Amazon EFS and Amazon FSx for Lustre file systems as data sources for training machine learning models. Amazon SageMaker now supports running training jobs on ml.p3dn.24xlarge instance type. This instance type is offered as a limited private preview for certain SageMaker customers. If you are interested in joining the private preview, please reach out to the SageMaker Product Management team via AWS Support."

## 2.514.0
* feature: AlexaForBusiness: Adding support for optional locale input in CreateProfile and UpdateProfile APIs
* feature: AppStream: Includes API updates to support streaming through VPC endpoints for image builders and stacks.
* feature: ChainableTemporaryCredentials: Support for specifying STS client config when creating ChainableTemporaryCredentials to override endpoint or region.
* feature: SageMaker: Amazon SageMaker introduces Managed Spot Training. Increases the maximum number of metric definitions to 40 for SageMaker Training and Hyperparameter Tuning Jobs. SageMaker Neo adds support for Acer aiSage and Qualcomm QCS605 and QCS603. 
* feature: Transfer: New field in response of TestIdentityProvider

## 2.513.0
* feature: AppMesh: Fix for HttpMethod enum
* feature: CUR: New IAM permission required for editing AWS Cost and Usage Reports - Starting today, you can allow or deny IAM users permission to edit Cost & Usage Reports through the API and the Billing and Cost Management console. To allow users to edit Cost & Usage Reports, ensure that they have 'cur: ModifyReportDefinition' permission. Refer to the technical documentation (https://docs.aws.amazon.com/aws-cost-management/latest/APIReference/API_cur_ModifyReportDefinition.html) for additional details.

## 2.512.0
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for controlling the usage of swap space on a per-container basis for Linux containers.
* feature: EMR: Amazon EMR  has introduced an account level configuration called Block Public Access that allows you to block clusters with ports open to traffic from public IP sources (i.e. 0.0.0.0/0 for IPv4 and ::/0 for IPv6) from launching.  Individual ports or port ranges can be added as exceptions to allow public access.
* feature: RoboMaker: Two feature release: 1. AWS RoboMaker introduces log-based simulation. Log-based simulation allows you to play back pre-recorded log data such as sensor streams for testing robotic functions like localization, mapping, and object detection. Use the AWS RoboMaker SDK to test your robotic applications.  2.  AWS RoboMaker allow customer to setup a robot deployment timeout when CreateDeploymentJob.

## 2.511.0
* feature: AppMesh: This release adds support for http header based routing and route prioritization.
* feature: Athena: This release adds support for querying S3 Requester Pays buckets. Users can enable this feature through their Workgroup settings.
* feature: CodeCommit: This release adds an API, BatchGetCommits, that allows retrieval of metadata for multiple commits in an AWS CodeCommit repository.
* feature: EC2: This release adds an option to use private certificates from AWS Certificate Manager (ACM) to authenticate a Site-to-Site VPN connection's tunnel endpoints and customer gateway device. 
* feature: Glue: GetJobBookmarks API is withdrawn.
* feature: StorageGateway: CreateSnapshotFromVolumeRecoveryPoint API supports new parameter: Tags (to be attached to the created resource)

## 2.510.0
* feature: EC2: This release adds a new API called SendDiagnosticInterrupt, which allows you to send diagnostic interrupts to your EC2 instance.

## 2.509.0
* feature: AppSync: Adds a configuration option for AppSync GraphQL APIs

## 2.508.0
* feature: Rekognition: Adding new Emotion, Fear

## 2.507.0
* feature: GuardDuty: New "evidence" field in the finding model to provide evidence information explaining why the finding has been triggered. Currently only threat-intelligence findings have this field. Some documentation updates.
* feature: Iot: This release adds Quality of Service (QoS) support for AWS IoT rules engine republish action.
* feature: LexRuntime: Manage Amazon Lex session state using APIs on the client
* feature: MediaConvert: AWS Elemental MediaConvert has added support for multi-DRM SPEKE with CMAF outputs, MP3 ingest, and options for improved video quality. 
* feature: Redshift: Add expectedNextSnapshotScheduleTime and expectedNextSnapshotScheduleTimeStatus to redshift cluster object.

## 2.506.0
* feature: CodeBuild: CodeBuild adds CloudFormation support for SourceCredential
* feature: Glue: You can now use AWS Glue to find matching records across dataset even without identifiers to join on by using the new FindMatches ML Transform. Find related products, places, suppliers, customers, and more by teaching a custom machine learning transformation that you can use to identify matching matching records as part of your analysis, data cleaning, or master data management project by adding the FindMatches transformation to your Glue ETL Jobs. If your problem is more along the lines of deduplication, you can use the FindMatches in much the same way to identify customers who have signed up more than ones, products that have accidentally been added to your product catalog more than once, and so forth. Using the FindMatches MLTransform, you can teach a Transform your definition of a duplicate through examples, and it will use machine learning to identify other potential duplicates in your dataset. As with data integration, you can then use your new Transform in your deduplication projects by adding the FindMatches transformation to your Glue ETL Jobs. This release also contains additional APIs that support AWS Lake Formation.
* feature: LakeFormation: Lake Formation: (New Service) AWS Lake Formation is a fully managed service that makes it easier for customers to build, secure and manage data lakes.  AWS Lake Formation simplifies and automates many of the complex manual steps usually required to create data lakes including collecting, cleaning and cataloging data and securely making that data available for analytics and machine learning.
* feature: OpsWorksCM: This release adds support for Chef Automate 2 specific engine attributes.

## 2.505.0
* feature: ApplicationInsights: CloudWatch Application Insights for .NET and SQL Server now provides integration with AWS Systems Manager OpsCenter. This integration allows you to view and resolve problems and operational issues detected for selected applications.

## 2.504.0
* feature: DataSync: Support VPC endpoints.
* feature: EC2: Amazon EC2 now supports a new Spot allocation strategy "Capacity-optimized" that fulfills your request using Spot Instance pools that are optimally chosen based on the available Spot capacity.
* feature: Iot: In this release, AWS IoT Device Defender introduces audit mitigation actions that can be applied to audit findings to help mitigate security issues.

## 2.503.0
* feature: MediaConvert: MediaConvert adds support for specifying priority (-50 to 50) on jobs submitted to on demand or reserved queues
* feature: Polly: Amazon Polly adds support for Neural text-to-speech engine.
* feature: Route53: Amazon Route 53 now supports the Middle East (Bahrain) Region (me-south-1) for latency records, geoproximity records, and private DNS for Amazon VPCs in that region.

## 2.502.0
* feature: CodeCommit: This release supports better exception handling for merges.

## 2.501.0
* feature: Batch: AWS Batch now supports SDK auto-pagination and Job-level docker devices.
* feature: CloudWatchLogs: Allow for specifying multiple log groups in an Insights query, and deprecate storedByte field for LogStreams and interleaved field for FilterLogEventsRequest.
* feature: CostExplorer: Adds support for resource optimization recommendations.
* feature: EC2: You can now create EC2 Capacity Reservations using Availability Zone ID or Availability Zone name. You can view usage of Amazon EC2 Capacity Reservations per AWS account.
* feature: Glue: This release provides GetJobBookmark and GetJobBookmarks APIs. These APIs enable users to look at specific versions or all versions of the JobBookmark for a specific job. This release also enables resetting the job bookmark to a specific run via an enhancement of the ResetJobBookmark API.
* feature: Greengrass: Greengrass OTA service supports openwrt/aarch64 and openwrt/armv7l platforms.
* feature: MediaConnect: This release adds support for the Zixi pull protocol on outputs.

## 2.500.0
* feature: ECR: This release adds support for immutable image tags.
* feature: MediaConvert: AWS Elemental MediaConvert has added several features including support for: audio normalization using ITU BS.1770-3, 1770-4 algorithms, extension of job progress indicators, input cropping rectangle & output position rectangle filters per input, and dual SCC caption mapping to additional codecs and containers. 
* feature: MediaLive: AWS Elemental MediaLive is adding Input Clipping, Immediate Mode Input Switching, and Dynamic Inputs.

## 2.499.0
* feature: EC2: This release introduces support for split tunnel with AWS Client VPN, and also adds support for opt-in Regions in DescribeRegions API. In addition, customers can now also tag Launch Templates on creation.
* feature: Glue: This release provides GlueVersion option for Job APIs and WorkerType option for DevEndpoint APIs. Job APIs enable users to pick specific GlueVersion for a specific job and pin the job to a specific runtime environment. DevEndpoint APIs enable users to pick different WorkerType for memory intensive workload.
* feature: Pinpoint: This release adds support for programmatic access to many of the same campaign metrics that are displayed on the Amazon Pinpoint console. You can now use the Amazon Pinpoint API to monitor and assess performance data for campaigns, and integrate metrics data with other reporting tools. We update the metrics data continuously, resulting in a data latency timeframe that is limited to approximately two hours.
* feature: STS: New STS GetAccessKeyInfo API operation that returns the account identifier for the specified access key ID.

## 2.498.0
* feature: SSM: You can now use Maintenance Windows to select a resource group as the target. By selecting a resource group as the target of a Maintenance Window, customers can perform routine tasks across different resources such as Amazon Elastic Compute Cloud (AmazonEC2) instances, Amazon Elastic Block Store (Amazon EBS) volumes, and Amazon Simple Storage Service(Amazon S3) buckets within the same recurring time window.
* feature: SecretsManager: This release increases the maximum allowed size of SecretString or SecretBinary from 7KB to 10KB in the CreateSecret, UpdateSecret, PutSecretValue and GetSecretValue APIs. This release also increases the maximum allowed size of ResourcePolicy from 4KB to 20KB in the GetResourcePolicy and PutResourcePolicy APIs.

## 2.497.0
* feature: MQ: Adds support for AWS Key Management Service (KMS) to offer server-side encryption. You can now select your own customer managed CMK, or use an AWS managed CMK in your KMS  account.
* feature: Shield: Adding new VectorType (HTTP_Reflection) and related top contributor types to describe WordPress Pingback DDoS attacks.

## 2.496.0
* feature: IoTEvents: Adds support for IoT Events, Lambda, SQS and Kinesis Firehose actions.

## 2.495.0
* feature: Comprehend: Amazon Comprehend now supports multiple entities for custom entity recognition
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for cluster settings. Cluster settings specify whether CloudWatch Container Insights is enabled or disabled for the cluster.

## 2.494.0
* feature: ConfigService: This release adds more granularity to the status of an OrganizationConfigRule by adding a new status. It also adds an exception when organization access is denied.
* feature: DMS: S3 endpoint settings update: 1) Option to append operation column to full-load files. 2) Option to add a commit timestamp column to full-load and cdc files. Updated DescribeAccountAttributes to include UniqueAccountIdentifier.

## 2.493.0
* feature: ApiGatewayV2: Bug fix (Add tags field to Update Stage , Api and DomainName Responses )
* feature: ES: Amazon Elasticsearch Service now supports M5, C5, and R5 instance types.
* feature: IAM: Removed exception that was indicated but never thrown for IAM GetAccessKeyLastUsed API
* feature: RoboMaker: Added Melodic as a supported Robot Software Suite Version

## 2.492.0
* feature: CloudWatchEvents: Adds APIs for partner event sources, partner event buses, and custom event buses. These new features are managed in the EventBridge service.
* feature: EventBridge: Amazon EventBridge is a serverless event bus service that makes it easy to connect your applications with data from a variety of sources, including AWS services, partner applications, and your own applications.

## 2.491.0
* feature: QuickSight: Amazon QuickSight now supports embedding dashboards for all non-federated QuickSight users. This includes IAM users, AD users and users from the QuickSight user pool. The get-dashboard-embed-url API accepts QUICKSIGHT as identity type with a user ARN to authenticate the embeddable dashboard viewer as a non-federated user.
* feature: ServiceCatalog: This release adds support for Parameters in ExecuteProvisionedProductServiceAction and adds functionality to get the default parameter values for a Self-Service Action execution against a Provisioned Product via DescribeServiceActionExecutionParameters

## 2.490.0
* feature: Amplify: This release adds webhook APIs and manual deployment APIs for AWS Amplify Console.
* feature: CloudWatch: This release adds three new APIs (PutAnomalyDetector, DeleteAnomalyDetector, and DescribeAnomalyDetectors) to support the new feature, CloudWatch Anomaly Detection. In addition, PutMetricAlarm and DescribeAlarms APIs are updated to support management of Anomaly Detection based alarms.
* feature: ConfigService: AWS Config now supports a new set of APIs to manage AWS Config rules across your organization in AWS Organizations. Using this capability, you can centrally create, update, and delete AWS Config rules across all accounts in your organization. This capability is particularly useful if you have a need to deploy a common set of AWS Config rules across all accounts. You can also specify accounts where AWS Config rules should not be created. In addition, you can use these APIs from the master account in AWS Organizations to enforce governance by ensuring that the underlying AWS Config rules are not modifiable by your organization member accounts.These APIs work for both managed and custom AWS Config rules. For more information, see Enabling AWS Config Rules Across all Accounts in Your Organization in the AWS Config Developer Guide.The new APIs are available in all commercial AWS Regions where AWS Config and AWS Organizations are supported. For the full list of supported Regions, see AWS Regions and Endpoints in the AWS General Reference. To learn more about AWS Config, visit the AWS Config webpage. To learn more about AWS Organizations, visit the AWS Organizations webpage.
* feature: EFS: EFS customers can now enable Lifecycle Management for all file systems. You can also now select from one of four Lifecycle Management policies (14, 30, 60 and 90 days), to automatically move files that have not been accessed for the period of time defined by the policy, from the EFS Standard storage class to the EFS Infrequent Access (IA) storage class. EFS IA provides price/performance that is cost-optimized for files that are not accessed every day.
* feature: GameLift: GameLift FlexMatch now supports matchmaking of up to 200 players per game session, and FlexMatch can now automatically backfill your game sessions whenever there is an open slot.
* feature: KinesisVideo: Add "GET_DASH_STREAMING_SESSION_URL" as an API name to the GetDataEndpoint API.
* feature: KinesisVideoArchivedMedia: Adds support for the GetDASHStreamingSessionURL API. Also adds support for the Live Replay playback mode of the GetHLSStreamingSessionURL API.
* feature: WAF: Updated SDK APIs to add tags to WAF Resources: WebACL, Rule, Rulegroup and RateBasedRule. Tags can also be added during creation of these resources.
* feature: WAFRegional: Updated SDK APIs to add tags to WAF Resources: WebACL, Rule, Rulegroup and RateBasedRule. Tags can also be added during creation of these resources.

## 2.489.0
* feature: CostExplorer: This release introduces a new operation called GetUsageForecast, which allows you to programmatically access AWS Cost Explorer's forecasting engine on usage data (running hours, data transfer, etc).

## 2.488.0
* feature: EC2: AssignPrivateIpAddresses response includes two new fields: AssignedPrivateIpAddresses, NetworkInterfaceId
* feature: RDS: This release supports Cross-Account Cloning for Amazon Aurora clusters.
* feature: S3: Add S3 x-amz-server-side-encryption-context support.
* feature: SWF: This release adds APIs that allow adding and removing tags to a SWF domain, and viewing tags for a domain. It also enables adding tags when creating a domain.

## 2.487.0
* feature: MediaStore: This release adds support for tagging, untagging, and listing tags for AWS Elemental MediaStore containers.

## 2.486.0
* feature: DocDB: This release provides support for cluster delete protection and the ability to stop and start clusters.
* feature: EC2: This release adds support for specifying a maximum hourly price for all On-Demand and Spot instances in both Spot Fleet and EC2 Fleet.
* feature: Organizations: Specifying the tag key and tag value is required for tagging requests.
* feature: RDS: This release adds support for RDS DB Cluster major version upgrade 

## 2.485.0
* feature: AlexaForBusiness: This release allows developers and customers to add SIP addresses and international phone numbers to contacts.
* feature: EC2: You can now launch 8xlarge and 16xlarge instance sizes on the general purpose M5 and memory optimized R5 instance types.
* feature: Redshift: ClusterAvailabilityStatus: The availability status of the cluster for queries. Possible values are the following: Available, Unavailable, Maintenance, Modifying, Failed.
* feature: WorkSpaces: Minor API fixes for WorkSpaces.

## 2.484.0
* feature: DirectConnect: Tags will now be included in the API responses of all supported resources (Virtual interfaces, Connections, Interconnects and LAGs). You can also add tags while creating these resources.
* feature: EC2InstanceConnect: Amazon EC2 Instance Connect is a simple and secure way to connect to your instances using Secure Shell (SSH). With EC2 Instance Connect, you can control SSH access to your instances using AWS Identity and Access Management (IAM) policies as well as audit connection requests with AWS CloudTrail events. In addition, you can leverage your existing SSH keys or further enhance your security posture by generating one-time use SSH keys each time an authorized user connects.
* feature: WorkSpaces: Added support for the WorkSpaces restore feature and copying WorkSpaces Images across AWS Regions.

## 2.483.0
* feature: ApiGatewayV2: You can now perform tag operations on ApiGatewayV2 Resources (typically associated with WebSocket APIs)
* feature: CodeCommit: This release supports better exception handling for merges.

## 2.482.0
* feature: EC2: Starting today, you can use Traffic Mirroring  to copy network traffic from an elastic network interface of Amazon EC2 instances and then send it to out-of-band security and monitoring appliances for content inspection, threat monitoring, and troubleshooting. These appliances can be deployed as individual instances, or as a fleet of instances behind a Network Load Balancer with a User Datagram Protocol (UDP) listener. Traffic Mirroring supports filters and packet truncation, so that you only extract the traffic of interest to monitor by using monitoring tools of your choice.

## 2.481.0
* feature: APIGateway: Customers can pick different security policies (TLS version + cipher suite) for custom domains in API Gateway
* feature: ApiGatewayV2: Customers can get information about security policies set on custom domain resources in API Gateway
* feature: ApplicationInsights: CloudWatch Application Insights detects errors and exceptions from logs, including .NET custom application logs, SQL Server logs, IIS logs, and more, and uses a combination of built-in rules and machine learning, such as dynamic baselining, to identify common problems. You can then easily drill into specific issues with CloudWatch Automatic Dashboards that are dynamically generated. These dashboards contain the most recent alarms, a summary of relevant metrics, and log snippets to help you identify root cause.
* feature: ClientSideMonitoring: add a host config to client-side monitoring configuration, defaults to be '127.0.0.1'
* feature: ELBv2: This release adds support for UDP on Network Load Balancers
* feature: FSx: Starting today, you can join your Amazon FSx for Windows File Server file systems to your organization's self-managed Microsoft Active Directory while creating the file system. You can also perform in-place updates of file systems to keep your Active Directory configuration up to date.
* feature: ResourceGroupsTaggingAPI: Updated service APIs and documentation.
* feature: SSM: AWS Systems Manager now supports deleting a specific version of a SSM Document.
* feature: SecurityHub: This release includes a new Tags parameter for the EnableSecurityHub operation, and the following new operations: DescribeHub, CreateActionTarget, DeleteActionTarget, DescribeActionTargets, UpdateActionTarget, TagResource, UntagResource, and ListTagsforResource. It removes the operation ListProductSubscribers, and makes Title and Description required attributes of AwsSecurityFinding.
* feature: ServiceQuotas: Service Quotas enables you to view and manage your quotas for AWS services from a central location.

## 2.480.0
* feature: IAM: We are making it easier for you to manage your permission guardrails i.e. service control policies by enabling you to retrieve the last timestamp when an AWS service was accessed within an account or AWS Organizations entity.
* feature: MediaPackage: Added two new origin endpoint fields for configuring which SCTE-35 messages are treated as advertisements.

## 2.479.0
* feature: ACMPCA: ACM Private CA is launching Root CAs and hierarchy management, a new feature that expands the scope of ACM Private CA from supporting only subordinate issuing CAs, to now include a full CA hierarchy that includes root CAs - the cryptographic root of trust for an organization.
* feature: Glue: Starting today, you can now use workflows in AWS Glue to author directed acyclic graphs (DAGs) of Glue triggers, crawlers and jobs. Workflows enable orchestration of your ETL workloads by building dependencies between Glue entities (triggers, crawlers and jobs).  You can visually track status of the different nodes in the workflows on the console making it easier to monitor progress and troubleshoot issues. Also, you can share parameters across entities in the workflow.
* feature: Health: API improvements for the AWS Health service.
* feature: IoTEventsData: "The colon character ':' is now permitted in Detector Model 'key' parameter values.
* feature: RDS: This release adds support for RDS storage autoscaling

## 2.478.0
* feature: EC2: You can now launch new 12xlarge, 24xlarge, and metal instance sizes on the Amazon EC2 compute optimized C5 instance types featuring 2nd Gen Intel Xeon Scalable Processors.
* feature: ResourceGroupsTaggingAPI: You can use tag policies to help standardize on tags across your organization's resources.

## 2.477.0
* feature: Neptune: This release adds a feature to configure Amazon Neptune to publish audit logs to Amazon CloudWatch Logs.
* feature: RoboMaker: Add the ServiceUnavailableException (503) into CreateSimulationJob API.
* feature: ServiceCatalog: Restrict concurrent calls by a single customer account for CreatePortfolioShare and DeletePortfolioShare when sharing/unsharing to an Organization.

## 2.476.0
* feature: AppStream: Added 2 new values(WINDOWS_SERVER_2016, WINDOWS_SERVER_2019) for PlatformType enum.
* feature: CloudFront: A new datatype in the CloudFront API, AliasICPRecordal, provides the ICP recordal status for CNAMEs associated with distributions. AWS services in China customers must file for an Internet Content Provider (ICP) recordal if they want to serve content publicly on an alternate domain name, also known as a CNAME, that they have added to CloudFront. The status value is returned in the CloudFront response; you cannot configure it yourself. The status is set to APPROVED for all CNAMEs (aliases) in regions outside of China.
* feature: EC2: Correction to enumerations in EC2 client.

## 2.475.0
* feature: AppMesh: This release adds support for AWS Cloud Map as a service discovery method for virtual nodes.
* feature: EC2: G4 instances are Amazon EC2 instances based on NVIDIA T4 GPUs and are designed to provide cost-effective machine learning inference for applications, like image classification, object detection, recommender systems, automated speech recognition, and language translation. G4 instances are also a cost-effective platform for building and running graphics-intensive applications, such as remote graphics workstations, video transcoding, photo-realistic design, and game streaming in the cloud. To get started with G4 instances visit https://aws.amazon.com/ec2/instance-types/g4.
* feature: ElastiCache: This release is to add support for reader endpoint for cluster-mode disabled Amazon ElastiCache for Redis clusters.
* feature: GuardDuty: Support for tagging functionality in Create and Get operations for Detector, IP Set, Threat Intel Set, and Finding Filter resources and 3 new tagging APIs: ListTagsForResource, TagResource, and UntagResource.

## 2.474.0
* feature: ServiceCatalog: This release adds a new field named Guidance to update provisioning artifact, this field can be set by the administrator to provide guidance to end users about which provisioning artifacts to use.

## 2.473.0
* bugfix: Credentials: Refresh cached ini credentials from disk
* feature: SageMaker: The default TaskTimeLimitInSeconds of labeling job is increased to 8 hours. Batch Transform introduces a new DataProcessing field which supports input and output filtering and data joining. Training job increases the max allowed input channels from 8 to 20.

## 2.472.0
* feature: CodeBuild: AWS CodeBuild adds support for source version on project level.
* feature: CodeCommit: This release adds two merge strategies for merging pull requests: squash and three-way. It also adds functionality for resolving merge conflicts, testing merge outcomes, and for merging branches using one of the three supported merge strategies.
* feature: Personalize: Amazon Personalize is a machine learning service that makes it easy for developers to create individualized recommendations for customers using their applications.
* feature: PersonalizeEvents: Introducing Amazon Personalize  - a machine learning service that makes it easy for developers to create individualized recommendations for customers using their applications.
* feature: PersonalizeRuntime: Amazon Personalize is a machine learning service that makes it easy for developers to create individualized recommendations for customers using their applications.

## 2.471.0
* feature: EC2: Adds DNS entries and NLB ARNs to describe-vpc-endpoint-connections API response. Adds owner ID to describe-vpc-endpoints and create-vpc-endpoint API responses.

## 2.470.0
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for launching container instances using supported Amazon EC2 instance types that have increased elastic network interface density. Using these instance types and opting in to the awsvpcTrunking account setting provides increased elastic network interface (ENI) density on newly launched container instances which allows you to place more tasks on each container instance.
* feature: GuardDuty: Improve FindingCriteria Condition field names, support long-typed conditions and deprecate old Condition field names.
* feature: MediaConnect: This release adds support for encrypting entitlements using Secure Packager and Encoder Key Exchange (SPEKE).
* feature: Organizations: You can tag and untag accounts in your organization and view tags on an account in your organization.
* feature: SES: You can now specify whether the Amazon Simple Email Service must deliver email over a connection that is encrypted using Transport Layer Security (TLS).
* feature: SSM: OpsCenter is a new Systems Manager capability that allows you to view, diagnose, and remediate, operational issues, aka OpsItems, related to various AWS resources by bringing together contextually relevant investigation information. New APIs to create, update, describe, and get OpsItems as well as OpsItems summary API. 

## 2.469.0
* feature: Glue: Support specifying python version for Python shell jobs. A new parameter PythonVersion is added to the JobCommand data type.

## 2.468.0
* feature: EC2: This release adds support for Host Recovery feature which automatically restarts instances on to a new replacement host if failures are detected on Dedicated Host.
* feature: ElastiCache: Amazon ElastiCache now allows you to apply available service updates on demand. Features included: (1) Access to the list of applicable service updates and their priorities. (2) Service update monitoring and regular status updates. (3) Recommended apply-by-dates for scheduling the service updates, which is critical if your cluster is in ElastiCache-supported compliance programs. (4) Ability to stop and later re-apply updates. For more information, see https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/Self-Service-Updates.html
* feature: StorageGateway: AWS Storage Gateway now supports AWS PrivateLink, enabling you to administer and use gateways without needing to use public IP addresses or a NAT/Internet Gateway, while avoiding traffic from going over the internet.

## 2.467.0
* bugfix: Buffer: remove deprecated new Buffer() constructor in Node.js
* feature: EC2: Amazon EC2 I3en instances are the new storage-optimized instances offering up to 60 TB NVMe SSD instance storage and up to 100 Gbps of network bandwidth.

## 2.466.0
* feature: CodeCommit: This release adds APIs that allow adding and removing tags to a repository, and viewing tags for a repository. It also enables adding tags when creating a repository.
* feature: IoTAnalytics: IoT Analytics adds the option to use your own S3 bucket to store channel and data store resources. Previously, only service-managed storage was used.
* feature: IoTEvents: The AWS IoT Events service allows customers to monitor their IoT devices and sensors to detect failures or changes in operation and to trigger actions when these events occur
* feature: IoTEventsData: The AWS IoT Events service allows customers to monitor their IoT devices and sensors to detect failures or changes in operation and to trigger actions when these events occur
* feature: Kafka: Updated APIs for Amazon MSK to enable new features such as encryption in transit, client authentication, and scaling storage.
* feature: PinpointEmail: You can now specify whether the Amazon Pinpoint Email service must deliver email over a connection that is encrypted using Transport Layer Security (TLS).
* feature: RDS: This release adds support for Activity Streams for database clusters.
* feature: RDSDataService: The RDS Data API is generally available for the MySQL-compatible edition of Amazon Aurora Serverless in the US East (N. Virginia and Ohio), US West (Oregon), EU (Ireland), and Asia Pacific (Tokyo) regions. This service enables you to easily access Aurora Serverless clusters with web services-based applications including AWS Lambda and AWS AppSync. The new APIs included in this SDK release are ExecuteStatement, BatchExecuteStatement, BeginTransaction, CommitTransaction, and RollbackTransaction. The ExecuteSql API is deprecated; instead use ExecuteStatement which provides additional functionality including transaction support.
* feature: ServiceCatalog: Service Catalog ListStackInstancesForProvisionedProduct API enables customers to get details of a provisioned product with type "CFN_STACKSET". By passing the provisioned product id, the API will list account, region and status of each stack instances that are associated with this provisioned product.

## 2.465.0
* feature: DLM: Customers can now simultaneously take snapshots of multiple EBS volumes attached to an EC2 instance. With this new capability, snapshots guarantee crash-consistency across multiple volumes by preserving the order of IO operations. This new feature is fully integrated with Amazon Data Lifecycle Manager (DLM) allowing customers to automatically manage snapshots by creating lifecycle policies. 
* feature: EC2: Customers can now simultaneously take snapshots of multiple EBS volumes attached to an EC2 instance. With this new capability, snapshots guarantee crash-consistency across multiple volumes by preserving the order of IO operations. This new feature is fully integrated with Amazon Data Lifecycle Manager (DLM) allowing customers to automatically manage snapshots by creating lifecycle policies. 
* feature: IoTThingsGraph: Initial release.
* feature: SecurityHub: This update adds the ListProductSubscribers API, DescribeProducts API, removes CONTAINS as a comparison value for the StringFilter, and only allows use of EQUALS instead of CONTAINS in MapFilter.  

## 2.464.0
* feature: Chime: This release adds the ability to search and order toll free phone numbers for Voice Connectors.
* feature: GroundStation: AWS Ground Station is a fully managed service that enables you to control satellite communications, downlink and process satellite data, and scale your satellite operations efficiently and cost-effectively without having to build or manage your own ground station infrastructure.
* feature: PinpointEmail: This release adds support for programmatic access to Deliverability dashboard subscriptions and the deliverability data provided by the Deliverability dashboard for domains and IP addresses. The data includes placement metrics for campaigns that use subscribed domains to send email.
* feature: RDS: Add a new output field Status to DBEngineVersion which shows the status of the engine version (either available or deprecated). Add a new parameter IncludeAll to DescribeDBEngineVersions to make it possible to return both available and deprecated engine versions. These changes enable a user to create a Read Replica of an DB instance on a deprecated engine version.
* feature: RoboMaker: Added support for an additional robot software suite (Gazebo 9) and for cancelling deployment jobs.
* feature: StorageGateway: Introduce AssignTapePool operation to allow customers to migrate tapes between pools.
* feature: TranscribeService: Amazon Transcribe - support transcriptions from audio sources in Modern Standard Arabic (ar-SA).

## 2.463.0
* feature: CodeDeploy: AWS CodeDeploy now supports tagging for the application and deployment group resources.
* feature: Core: set environmental variable AWS_NODEJS_CONNECTION_REUSE_ENABLED to 1 to make SDK reuse connections by default if users don't supply custom agents.
* feature: MediaStoreData: MediaStore - This release adds support for chunked transfer of objects, which reduces latency by making an object available for downloading while it is still being uploaded.

## 2.462.0
* bugfix: Documentation: Update badges in README.md
* feature: EC2: New APIs to enable EBS encryption by default feature. Once EBS encryption by default is enabled in a region within the account, all new EBS volumes and snapshot copies are always encrypted

## 2.461.0
* feature: APIGateway: This release adds support for tagging of Amazon API Gateway resources.
* feature: Budgets: Added new datatype PlannedBudgetLimits to Budget model, and updated examples for AWS Budgets API for UpdateBudget, CreateBudget, DescribeBudget, and DescribeBudgets
* feature: DeviceFarm: This release introduces support for tagging, tag-based access control, and resource-based access control.
* feature: EC2: This release adds idempotency support for associate, create route and authorization APIs for AWS Client VPN Endpoints.
* feature: EFS: AWS EFS documentation updated to reflect the minimum required value for ProvisionedThroughputInMibps is 1 from the previously documented 0. The service has always required a minimum value of 1, therefor service behavior is not changed. 
* feature: ServiceCatalog: Service Catalog UpdateProvisionedProductProperties API enables customers to manage provisioned product ownership. Administrators can now update the user associated to a provisioned product to another user within the same account allowing the new user to describe, update, terminate and execute service actions in that Service Catalog resource. New owner will also be able to list and describe all past records executed for that provisioned product.
* feature: WorkLink: Amazon WorkLink is a fully managed, cloud-based service that enables secure, one-click access to internal websites and web apps from mobile phones. This release introduces new APIs to associate and manage website authorization providers with Amazon WorkLink fleets.
* feature: s3: Validate the `Expiration` parameter for `s3.getSignedUrl()` is number

## 2.460.0
* feature: AlexaForBusiness: This release contains API changes to allow customers to create and manage Network Profiles for their Shared devices
* feature: DataSync: Documentation update and refine pagination token on Datasync List API's

## 2.459.0
* feature: Kafka: Updated APIs for the Managed Streaming for Kafka service that let customers create clusters with custom Kafka configuration. 
* feature: MediaPackageVod: AWS Elemental MediaPackage now supports Video-on-Demand (VOD) workflows.  These new features allow you to easily deliver a vast library of source video Assets stored in your own S3 buckets using a small set of simple to set up Packaging Configurations and Packaging Groups.

## 2.458.0
* feature: AppStream: Includes APIs for managing subscriptions to AppStream 2.0 usage reports and configuring idle disconnect timeouts on AppStream 2.0 fleets.

## 2.457.0
* enhancement: Documentation: Added steps to generate documentation changes in CONTRIBUTION.md
* feature: MediaLive: Added channel state waiters to MediaLive.
* feature: S3: This release updates the Amazon S3 PUT Bucket replication API to include a new optional field named token, which allows you to add a replication configuration to an S3 bucket that has Object Lock enabled.

## 2.456.0
* feature: CodePipeline: This feature includes new APIs to add, edit, remove and view tags for pipeline, custom action type and webhook resources. You can also add tags while creating these resources.
* feature: EC2: Adding tagging support for VPC Endpoints and VPC Endpoint Services.
* feature: MediaPackage: Adds optional configuration for DASH SegmentTemplateFormat to refer to segments by Number with Duration, rather than Number or Time with SegmentTimeline.
* feature: TranscribeService: Amazon Transcribe - support transcriptions from audio sources in Indian English (en-IN) and Hindi (hi-IN).

## 2.455.0
* feature: Chime: Amazon Chime private bots GA release.
* feature: Comprehend: With this release AWS Comprehend now supports Virtual Private Cloud for Asynchronous Batch Processing jobs
* feature: EC2: Pagination support for ec2.DescribeSubnets, ec2.DescribeDhcpOptions 
* feature: StorageGateway: Add Tags parameter to CreateSnapshot and UpdateSnapshotSchedule APIs, used for creating tags on create for one off snapshots and scheduled snapshots.

## 2.454.0
* feature: DataSync: AWS DataSync now enables exclude and include filters to control what files and directories will be copied as part of a task execution.
* feature: IoTAnalytics: ContentDeliveryRule to support sending dataset to S3 and glue
* feature: Lambda: AWS Lambda now supports Node.js v10
* feature: core: Add support for requiresLength trait for streaming payload and send chunked transfer encode when allowed

## 2.453.0
* feature: Glue: AWS Glue now supports specifying existing catalog tables for a crawler to examine as a data source. A new parameter CatalogTargets is added to the CrawlerTargets data type. 
* feature: STS: AWS Security Token Service (STS) now supports passing IAM Managed Policy ARNs as session policies when you programmatically create temporary sessions for a role or federated user. The Managed Policy ARNs can be passed via the PolicyArns parameter, which is now available in the AssumeRole, AssumeRoleWithWebIdentity, AssumeRoleWithSAML, and GetFederationToken APIs. The session policies referenced by the PolicyArn parameter will only further restrict the existing permissions of an IAM User or Role for individual sessions.

## 2.452.0
* feature: IoT1ClickProjects: Added automatic pagination support for ListProjects and ListPlacements APIs.
* feature: KinesisAnalytics: Kinesis Data Analytics APIs now support tagging on applications.
* feature: KinesisAnalyticsV2: Kinesis Data Analytics APIs now support tagging on applications.
* feature: SageMaker: Workteams now supports notification configurations. Neo now supports Jetson Nano as a target device and NumberOfHumanWorkersPerDataObject is now included in the ListLabelingJobsForWorkteam response.
* feature: ServiceCatalog: Adds "Parameters" field in UpdateConstraint API, which will allow Admin user to update "Parameters" in created Constraints.

## 2.451.0
* feature: AlexaForBusiness: This release adds an API allowing authorized users to delete a shared device's history of voice recordings and associated response data.
* feature: AppSync: AWS AppSync now supports the ability to add additional authentication providers to your AWS AppSync GraphQL API as well as the ability to retrieve directives configured against fields or object type definitions during schema introspection.
* feature: SSM: Patch Manager adds support for Microsoft Application Patching.
* feature: StorageGateway: Add optional field AdminUserList to CreateSMBFileShare and UpdateSMBFileShare APIs.

## 2.450.0
* feature: ConfigService: AWS Config now supports tagging on PutConfigRule, PutConfigurationAggregator and PutAggregationAuthorization APIs.

## 2.449.0
* feature: CognitoIdentityServiceProvider: This release of Amazon Cognito User Pools introduces the new AdminSetUserPassword API that allows administrators of a user pool to change a user's password. The new password can be temporary or permanent.
* feature: MediaConvert: DASH output groups using DRM encryption can now enable a playback device compatibility mode to correct problems with playback on older devices. 
* feature: MediaLive: You can now switch the channel mode of your channels from standard to single pipeline and from single pipeline to standard. In order to switch a channel from single pipeline to standard all inputs attached to the channel must support two encoder pipelines.
* feature: WorkMail: Amazon WorkMail is releasing two new actions: 'GetMailboxDetails' and 'UpdateMailboxQuota'. They add insight into how much space is used by a given mailbox (size) and what its limit is (quota). A mailbox quota can be updated, but lowering the value will not influence WorkMail per user charges. For a closer look at the actions please visit https://docs.aws.amazon.com/workmail/latest/APIReference/API_Operations.html

## 2.448.0
* feature: AlexaForBusiness: This release allows developers and customers to send text and audio announcements to rooms.
* feature: KMS: AWS Key Management Service (KMS) can return an INTERNAL_ERROR connection error code if it cannot connect a custom key store to its AWS CloudHSM cluster. INTERNAL_ERROR is one of several connection error codes that help you to diagnose and fix a problem with your custom key store.

## 2.447.0
* feature: EC2: This release adds an API for the modification of a VPN Connection, enabling migration from a Virtual Private Gateway (VGW) to a Transit Gateway (TGW), while preserving the VPN endpoint IP addresses on the AWS side as well as the tunnel options.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces additional task definition parameters that enable you to define secret options for Docker log configuration, a per-container list contains secrets stored in AWS Systems Manager Parameter Store or AWS Secrets Manager.
* feature: XRay: AWS X-Ray now includes Analytics, an interactive approach to analyzing user request paths (i.e., traces). Analytics will allow you to easily understand how your application and its underlying services are performing. With X-Ray Analytics, you can quickly detect application issues, pinpoint the root cause of the issue, determine the severity of the issues, and identify which end users were impacted. With AWS X-Ray Analytics you can explore, analyze, and visualize traces, allowing you to find increases in response time to user requests or increases in error rates. Metadata around peak periods, including frequency and actual times of occurrence, can be investigated by applying filters with a few clicks. You can then drill down on specific errors, faults, and response time root causes and view the associated traces. 

## 2.446.0
* bugfix: DocumentClient: Fixes issue stringifying sets by only including values.
* feature: CodePipeline: This release contains an update to the PipelineContext object that includes the Pipeline ARN, and the Pipeline Execution Id. The ActionContext object is also updated to include the Action Execution Id.
* feature: DirectConnect: This release adds support for AWS Direct Connect customers to use AWS Transit Gateway with AWS Direct Connect gateway to route traffic between on-premise networks and their VPCs.
* feature: ManagedBlockchain: (New Service) Amazon Managed Blockchain is a fully managed service that makes it easy to create and manage scalable blockchain networks using popular open source frameworks.
* feature: S3Control: Add support for Amazon S3 Batch Operations.
* feature: ServiceCatalog: Admin users can now associate/disassociate aws budgets with a portfolio or product in Service Catalog. End users can see the association by listing it or as part of the describe portfolio/product output. A new optional boolean parameter, "DisableTemplateValidation", is added to ProvisioningArtifactProperties data type. The purpose of the parameter is to enable or disable the CloudFormation template validtion when creating a product or a provisioning artifact.

## 2.445.0
* feature: EC2: Adds support for Elastic Fabric Adapter (EFA) ENIs. 
* feature: Transfer: This release adds support for per-server host-key management. You can now specify the SSH RSA private key used by your SFTP server.

## 2.444.0
* feature: IAM: AWS Security Token Service (STS) enables you to request session tokens from the global STS endpoint that work in all AWS Regions. You can configure the global STS endpoint to vend session tokens that are compatible with all AWS Regions using the new IAM SetSecurityTokenServicePreferences API. 
* feature: SNS: With this release AWS SNS adds tagging support for Topics.

## 2.443.0
* feature: DynamoDB: This update allows you to tag Amazon DynamoDB tables when you create them. Tags are labels you can attach to AWS resources to make them easier to manage, search, and filter. 
* feature: GameLift: This release introduces the new Realtime Servers feature, giving game developers a lightweight yet flexible solution that eliminates the need to build a fully custom game server. The AWS SDK updates provide support for scripts, which are used to configure and customize Realtime Servers.
* feature: Inspector: AWS Inspector - Improve the ListFindings API response time and decreases the maximum number of agentIDs from 500 to 99.
* feature: Lambda: AWS Lambda now supports the GetLayerVersionByArn API.

## 2.442.0
* feature: AlexaForBusiness: This release adds support for the Alexa for Business gateway and gateway group APIs.
* feature: EC2: You can now launch the new Amazon EC2 general purpose burstable instance types T3a that feature AMD EPYC processors.
* feature: MediaConnect: Adds support for ListEntitlements pagination.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now includes a new parameter to support origin servers that produce single-period DASH manifests.
* feature: RDS: A new parameter "feature-name" is added to the add-role and remove-role db cluster APIs. The value for the parameter is optional for Aurora MySQL compatible database clusters, but mandatory for Aurora PostgresQL. You can find the valid list of values using describe db engine versions API.
* feature: Route53: Amazon Route 53 now supports the Asia Pacific (Hong Kong) Region (ap-east-1) for latency records, geoproximity records, and private DNS for Amazon VPCs in that region.
* feature: SSM: This release updates AWS Systems Manager APIs to allow customers to configure parameters to use either the standard-parameter tier (the default tier) or the advanced-parameter tier. It allows customers to create parameters with larger values and attach parameter policies to an Advanced Parameter. 
* feature: StorageGateway: AWS Storage Gateway now supports Access Control Lists (ACLs) on File Gateway SMB shares, enabling you to apply fine grained access controls for Active Directory users and groups.
* feature: Textract: This release adds support for checkbox also known as SELECTION_ELEMENT in Amazon Textract.

## 2.441.0
* feature: CostExplorer: enable cors
* feature: ResourceGroups: The AWS Resource Groups service increased the query size limit to 4096 bytes.
* feature: TranscribeService: Amazon Transcribe - support transcriptions from audio sources in Spanish Spanish (es-ES).
* feature: WorkSpaces: Added a new reserved field.

## 2.440.0
* feature: Discovery: The Application Discovery Service's DescribeImportTasks and BatchDeleteImportData APIs now return additional statuses for error reporting.
* feature: Kafka: Amazon Kafka - Added tagging APIs
* feature: Organizations: AWS Organizations is now available in the AWS GovCloud (US) Regions, and we added a new API action for creating accounts in those Regions. For more information, see CreateGovCloudAccount in the AWS Organizations API Reference. 
* feature: RDS: This release adds the TimeoutAction parameter to the ScalingConfiguration of an Aurora Serverless DB cluster. You can now configure the behavior when an auto-scaling capacity change can't find a scaling point.
* feature: WorkLink: Amazon WorkLink is a fully managed, cloud-based service that enables secure, one-click access to internal websites and web apps from mobile phones. This release introduces new APIs to link and manage internal websites and web apps with Amazon WorkLink fleets. 

## 2.439.0
* feature: EC2: This release adds support for requester-managed Interface VPC Endpoints (powered by AWS PrivateLink). The feature prevents VPC endpoint owners from accidentally deleting or otherwise mismanaging the VPC endpoints of some AWS VPC endpoint services.
* feature: Polly: Amazon Polly adds Arabic language support with new female voice - "Zeina"

## 2.438.0
* bugfix: Parser: Alloc new buffers from 0 offset when parsing the sensitive blob data and zero out the node shared buffer pool.
* bugfix: computeSha256: Before running instanceof, verify that the operand is a function
* feature: CognitoIdentityServiceProvider: This release adds support for the new email configuration in Amazon Cognito User Pools. You can now specify whether Amazon Cognito emails your users by using its built-in email functionality or your Amazon SES email configuration.
* feature: MQ: This release adds the ability to retrieve information about broker engines and broker instance options. See Broker Engine Types and Broker Instance Options in the Amazon MQ REST API Reference.
* feature: Redshift: DescribeResize can now return percent of data transferred from source cluster to target cluster for a classic resize.
* feature: StorageGateway: This change allows you to select either a weekly or monthly maintenance window for your volume or tape gateway. It also allows you to tag your tape and volume resources on creation by adding a Tag value on calls to the respective api endpoints.

## 2.437.0
* feature: Comprehend: With this release AWS Comprehend provides confusion matrix for custom document classifier.
* feature: Glue: AWS Glue now supports workerType choices in the CreateJob, UpdateJob, and StartJobRun APIs, to be used for memory-intensive jobs.
* feature: MediaConvert: Rectify incorrect modelling of DisassociateCertificate method
* feature: MediaLive: Today AWS Elemental MediaLive (https://aws.amazon.com/medialive/) adds the option to create "Single Pipeline" channels, which offers a lower-cost option compared to Standard channels. MediaLive Single Pipeline channels have a single encoding pipeline rather than the redundant dual Availability Zone (AZ) pipelines that MediaLive provides with a "Standard" channel.
* feature: docs: update doc operation example to use 'NUMBER_VALUE' instead of 0 in input

## 2.436.0
* feature: EKS: Added support to enable or disable publishing Kubernetes cluster logs in AWS CloudWatch

## 2.435.0
* bugfix: integration: remove rds create DB security group test
* feature: Batch: Support for GPU resource requirement in RegisterJobDefinition and SubmitJob
* feature: Comprehend: With this release AWS Comprehend  adds tagging support for document-classifiers and entity-recognizers.

## 2.434.0
* feature: EC2: Add paginators.
* feature: SecurityHub: This update includes 3 additional error codes: AccessDeniedException, InvalidAccessException, and ResourceConflictException. This update also removes the error code ResourceNotFoundException from the GetFindings, GetInvitationsCount, ListInvitations, and ListMembers operations. 

## 2.433.0
* feature: EMR: Amazon EMR adds the ability to modify instance group configurations on a running cluster through the new "configurations" field in the ModifyInstanceGroups API.

## 2.432.0
* feature: CloudWatch: Added 3 new APIs, and one additional parameter to PutMetricAlarm API, to support tagging of CloudWatch Alarms.
* feature: Comprehend: With this release AWS Comprehend supports encryption of output results of analysis jobs and volume data on the storage volume attached to the compute instance that processes the analysis job.
* feature: Greengrass: Greengrass APIs now support tagging operations on resources

## 2.431.0
* feature: MediaLive: This release adds a new output locking mode synchronized to the Unix epoch.
* feature: PinpointEmail: This release adds support for using the Amazon Pinpoint Email API to tag the following types of Amazon Pinpoint resources: configuration sets; dedicated IP pools; deliverability dashboard reports; and, email identities. A tag is a label that you optionally define and associate with these types of resources. Tags can help you categorize and manage these resources in different ways, such as by purpose, owner, environment, or other criteria. A resource can have as many as 50 tags. For more information, see the Amazon Pinpoint Email API Reference.
* feature: ServiceCatalog: Adds "Tags" field in UpdateProvisionedProduct API. The product should have a new RESOURCE_UPDATE Constraint with TagUpdateOnProvisionedProduct field set to ALLOWED for it to work. See API docs for CreateConstraint for more information
* feature: WorkSpaces: Amazon WorkSpaces adds tagging support for WorkSpaces Images, WorkSpaces directories, WorkSpaces bundles and IP Access control groups.

## 2.430.0
* feature: AppMesh: This release includes AWS Tagging integration for App Mesh, VirtualNode access logging, TCP routing, and Mesh-wide external traffic egress control. See https://docs.aws.amazon.com/app-mesh/latest/APIReference/Welcome.html for more details.
* feature: EC2: You can now launch the new Amazon EC2 R5ad and M5ad instances that feature local NVMe attached SSD instance storage (up to 3600 GB). M5ad and R5ad feature AMD EPYC processors that offer a 10% cost savings over the M5d and R5d EC2 instances.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for external deployment controllers for ECS services with the launch of task set management APIs. Task sets are a new primitive for controlled management of application deployments within a single ECS service.
* feature: ELBv2: This release adds support for routing based on HTTP headers, methods, query string or query parameters and source IP addresses in Application Load Balancer.
* feature: S3: S3 Glacier Deep Archive provides secure, durable object storage class for long term data archival. This SDK release provides API support for this new storage class.
* feature: StorageGateway: This change allows you to select a pool for archiving virtual tapes. Pools are associated with S3 storage classes. You can now choose to archive virtual tapes in either S3 Glacier or S3 Glacier Deep Archive storage class. CreateTapes API now takes a new PoolId parameter which can either be GLACIER or DEEP_ARCHIVE. Tapes created with this parameter will be archived in the corresponding storage class.
* feature: Transfer:  This release adds PrivateLink support to your AWS SFTP server endpoint, enabling the customer to access their SFTP server within a VPC, without having to traverse the internet. Customers can now can create a server and specify an option whether they want the endpoint to be hosted as public or in their VPC, and with the in VPC option, SFTP clients and users can access the server only from the customer's VPC or from their on-premises environments using DX or VPN. This release also relaxes the SFTP user name requirements to allow underscores and hyphens.

## 2.429.0
* feature: Credentials: enables use of credentials_process for sourcing credentials from an external process https://docs.aws.amazon.com/cli/latest/topic/config-vars.html#sourcing-credentials-from-external-processes
* feature: Glue: This new feature will now allow customers to add a customized csv classifier with classifier API. They can specify a custom delimiter, quote symbol and control other behavior they'd like crawlers to have while recognizing csv files

## 2.428.0
* feature: DirectConnect: Direct Connect gateway enables you to establish connectivity between your on-premise networks and Amazon Virtual Private Clouds (VPCs) in any commercial AWS Region (except in China) using AWS Direct Connect connections at any AWS Direct Connect location. This release enables multi-account support for Direct Connect gateway, with multi-account support for Direct Connect gateway, you can associate up to ten VPCs from any AWS account with a Direct Connect gateway. The AWS accounts owning VPCs and the Direct Connect gateway must belong to the same AWS payer account ID. This release also enables Direct Connect Gateway owners to allocate allowed prefixes from each associated VPCs.
* feature: FMS: AWS Firewall Manager now allows customer to centrally enable AWS Shield Advanced DDoS protection for their entire AWS infrastructure, across accounts and applications.
* feature: IoT1ClickDevicesService: This release adds tagging support for AWS IoT 1-Click Device resources. Use these APIs to add, remove, or list tags on Devices, and leverage the tags for various authorization and billing scenarios. This release also adds the ARN property for DescribeDevice response object.
* feature: IoTAnalytics: This change allows you to specify the number of versions of IoT Analytics data set content to be retained. Previously, the number of versions was managed implicitly via the setting of the data set's retention period.
* feature: MediaConvert: This release adds support for detailed job progress status and S3 server-side output encryption. In addition, the anti-alias filter will now be automatically applied to all outputs
* feature: Retry: make RequestThrottleException retryable
* feature: RoboMaker: Added additional progress metadata fields for robot deployments
* feature: TranscribeService: Amazon Transcribe - With this release Amazon Transcribe enhances the custom vocabulary feature to improve accuracy by providing customization on pronunciations and output formatting. 

## 2.427.0
* feature: IoT1ClickProjects: This release adds tagging support for AWS IoT 1-Click Project resources. Use these APIs to add, remove, or list tags on Projects, and leverage the tags for various authorization and billing scenarios. This release also adds the ARN property to projects for DescribeProject and ListProject responses.
* feature: TranscribeService: Amazon Transcribe - support transcriptions from audio sources in German (de-DE) and Korean (ko-KR).

## 2.426.0
* bugfix: Paginator: still send '{}' in body for requests other than GET
* feature: CloudWatchEvents: Added 3 new APIs, and one additional parameter to the PutRule API, to support tagging of CloudWatch Events rules.
* feature: CognitoIdentityServiceProvider: This release adds tags and tag-based access control support to Amazon Cognito User Pools.
* feature: Iot: This release adds the GetStatistics API for the AWS IoT Fleet Indexing Service, which allows customers to query for statistics about registered devices that match a search query. This release only supports the count statistics. For more information about this API, see https://docs.aws.amazon.com/iot/latest/apireference/API_GetStatistics.html
* feature: Lightsail: This release adds the DeleteKnownHostKeys API, which enables Lightsail's browser-based SSH or RDP clients to connect to the instance after a host key mismatch.

## 2.425.0
* feature: CodePipeline: Add support for viewing details of each action execution belonging to past and latest pipeline executions that have occurred in customer's pipeline. The details include start/updated times, action execution results, input/output artifacts information, etc. Customers also have the option to add pipelineExecutionId in the input to filter the results down to a single pipeline execution.
* feature: CognitoIdentity: This release adds tags and tag-based access control support to Amazon Cognito Identity Pools (Federated Identities). 
* feature: MarketplaceMetering: This release increases AWS Marketplace Metering Service maximum usage quantity to 2147483647 and makes parameters usage quantity and dryrun optional.
* feature: cors: add cors support for IAM and ResouceGroups services

## 2.424.0
* bugfix: Paginator: fix the issue where paginator keys are ignored in GET requests
* bugfix: Request: Fix nextPage() method signature
* feature: ConfigService: AWS Config adds a new API called SelectResourceConfig to run advanced queries based on resource configuration properties.
* feature: EKS: Added support to control private/public access to the Kubernetes API-server endpoint

## 2.423.0
* feature: Chime: This release adds support for the Amazon Chime Business Calling and Voice Connector features.
* feature: DMS: S3 Endpoint Settings added support for 1) Migrating to Amazon S3 as a target in Parquet format 2) Encrypting S3 objects after migration with custom KMS Server-Side encryption. Redshift Endpoint Settings added support for encrypting intermediate S3 objects during migration with custom KMS Server-Side encryption. 
* feature: EC2: DescribeFpgaImages API now returns a new DataRetentionSupport attribute to indicate if the AFI meets the requirements to support DRAM data retention. DataRetentionSupport is a read-only attribute.

## 2.422.0
* feature: ACM: AWS Certificate Manager has added a new API action, RenewCertificate. RenewCertificate causes ACM to force the renewal of any private certificate which has been exported.
* feature: ACMPCA: AWS Certificate Manager (ACM) Private CA allows customers to manage permissions on their CAs. Customers can grant or deny AWS Certificate Manager permission to renew exported private certificates.
* feature: CloudWatch: New Messages parameter for the output of GetMetricData, to support new metric search functionality.
* feature: ConfigService: AWS Config - add ability to tag, untag and list tags for ConfigRule, ConfigurationAggregator and AggregationAuthorization resource types. Tags can be used for various scenarios including tag based authorization.
* feature: EC2: This release adds tagging support for Dedicated Host Reservations.
* feature: Iot: In this release, AWS IoT introduces support for tagging OTA Update and Stream resources. For more information about tagging, see the AWS IoT Developer Guide.
* feature: SageMaker: Amazon SageMaker Automatic Model Tuning now supports random search and hyperparameter scaling.

## 2.421.0
* feature: ConfigService: Config released Remediation APIs allowing Remediation of Config Rules

## 2.420.0
* bugfix: ManageUpload: abort request stream when body is smaller than 5MB
* feature: ServerlessApplicationRepository: The AWS Serverless Application Repository now supports associating a ZIP source code archive with versions of an application.

## 2.419.0
* feature: CostExplorer: The only change in this release is to make TimePeriod a required parameter in GetCostAndUsageRequest.
* feature: ElasticBeanstalk: Elastic Beanstalk added support for tagging, and tag-based access control, of all Elastic Beanstalk resources.
* feature: Glue: CreateDevEndpoint and UpdateDevEndpoint now support Arguments to configure the DevEndpoint. 
* feature: QuickSight: Amazon QuickSight user and group operation results now include group principal IDs and user principal IDs. This release also adds "DeleteUserByPrincipalId", which deletes users given their principal ID. The update also improves role session name validation.

## 2.418.0
* bugfix: cloudfront: Fix whitespace removal on custom policy
* feature: CodeBuild: CodeBuild also now supports Git Submodules.  CodeBuild now supports opting out of Encryption for S3 Build Logs.  By default these logs are encrypted.
* feature: SageMaker: SageMaker notebook instances now support enabling or disabling root access for notebook users. SageMaker Neo now supports rk3399 and rk3288 as compilation target devices.

## 2.417.0
* feature: AppMesh: This release includes a new version of the AWS App Mesh APIs. You can read more about the new APIs here: https://docs.aws.amazon.com/app-mesh/latest/APIReference/Welcome.html.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces additional task definition parameters that enable you to define dependencies for container startup and shutdown, a per-container start and stop timeout value, as well as an AWS App Mesh proxy configuration which eases the integration between Amazon ECS and AWS App Mesh.
* feature: GameLift: Amazon GameLift-hosted instances can now securely access resources on other AWS services using IAM roles. See more details at https://aws.amazon.com/releasenotes/amazon-gamelift/.
* feature: Greengrass: Greengrass group UID and GID settings can now be configured to use a provided default via FunctionDefaultConfig. If configured, all Lambda processes in your deployed Greengrass group will by default start with the provided UID and/or GID, rather than by default starting with UID "ggc_user" and GID "ggc_group" as they would if not configured. Individual Lambdas can also be configured to override the defaults if desired via each object in the Functions list of your FunctionDefinitionVersion.
* feature: MediaLive: This release adds a MediaPackage output group, simplifying configuration of outputs to AWS Elemental MediaPackage.
* feature: RDS: You can configure your Aurora database cluster to automatically copy tags on the cluster to any automated or manual database cluster snapshots that are created from the cluster. This allows you to easily set metadata on your snapshots to match the parent cluster, including access policies. You may enable or disable this functionality while creating a new cluster, or by modifying an existing database cluster.

## 2.416.0
* feature: DirectConnect: Exposed a new available port speeds field in the DescribeLocation api call.
* feature: EC2: This release adds pagination support for ec2.DescribeVpcs, ec2.DescribeInternetGateways and ec2.DescribeNetworkAcls APIs

## 2.415.0
* feature: MediaLive: This release adds support for pausing and unpausing one or both pipelines at scheduled times.
* feature: StorageGateway: ActivateGateway, CreateNFSFileShare and CreateSMBFileShare APIs support a new parameter: Tags (to be attached to the created resource). Output for DescribeNFSFileShare, DescribeSMBFileShare and DescribeGatewayInformation APIs now also list the Tags associated with the resource. Minimum length of a KMSKey is now 7 characters.
* feature: Textract: This release is intended ONLY for customers that are officially part of the Amazon Textract Preview program.  If you are not officially part of the Amazon Textract program THIS WILL NOT WORK.  Our two main regions for Amazon Textract Preview are N. Virginia and Dublin.  Also some members have been added to Oregon and Ohio.  If you are outside of any of these AWS regions, Amazon Textract Preview definitely will not work. If you would like to be part of the Amazon Textract program, you can officially request sign up here - https://pages.awscloud.com/textract-preview.html. To set expectations appropriately, we are aiming to admit new preview participants once a week until General Availability.

## 2.414.0
* feature: MediaPackage: This release adds support for user-defined tagging of MediaPackage resources. Users may now call operations to list, add and remove tags from channels and origin-endpoints. Users can also specify tags to be attached to these resources during their creation. Describe and list operations on these resources will now additionally return any tags associated with them.
* feature: SSM: This release updates AWS Systems Manager APIs to support service settings for AWS customers.  A service setting is a key-value pair that defines how a user interacts with or uses an AWS service, and is typically created and consumed by the AWS service team. AWS customers can read a service setting via GetServiceSetting API and update the setting via UpdateServiceSetting API or ResetServiceSetting API, which are introduced in this release. For example, if an AWS service charges money to the account based on a feature or service usage, then the AWS service team might create a setting with the default value of "false".   This means the user can't use this feature unless they update the setting to "true" and  intentionally opt in for a paid feature.

## 2.413.0
* feature: EC2: This release adds support for modifying instance event start time which allows users to reschedule EC2 events.

## 2.412.0
* bugfix: ComprehendMedical: enable cors on ComprehendMedical, update SERVICES.md
* feature: AlexaForBusiness: This release adds the PutInvitationConfiguration API to configure the user invitation email template with custom attributes, and the GetInvitationConfiguration API to retrieve the configured values.
* feature: ApiGatewayV2: Marking certain properties as explicitly required and fixing an issue with the GetApiMappings operation for ApiMapping resources.
* feature: SSM: AWS Systems Manager State Manager now supports associations using documents shared by other AWS accounts.

## 2.411.0
* feature: CUR: Adding support for Athena and new report preferences to the Cost and Usage Report API.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added several features including support for: auto-rotation or user-specified rotation of 0, 90, 180, or 270 degrees; multiple output groups with DRM; ESAM XML documents to specify ad insertion points; Offline Apple HLS FairPlay content protection. 
* feature: Pinpoint: This release adds support for the Amazon Resource Groups Tagging API to Amazon Pinpoint, which means that you can now add and manage tags for Amazon Pinpoint projects (apps), campaigns, and segments. A tag is a label that you optionally define and associate with Amazon Pinpoint resource. Tags can help you categorize and manage these types of resources in different ways, such as by purpose, owner, environment, or other criteria. For example, you can use tags to apply policies or automation, or to identify resources that are subject to certain compliance requirements. A project, campaign, or segment can have as many as 50 tags. For more information about using and managing tags in Amazon Pinpoint, see the Amazon Pinpoint Developer Guide at https://docs.aws.amazon.com/pinpoint/latest/developerguide/welcome.html. For more information about the Amazon Resource Group Tagging API, see the Amazon Resource Group Tagging API Reference at https://docs.aws.amazon.com/resourcegroupstagging/latest/APIReference/Welcome.html.

## 2.410.0
* feature: AutoScaling: Added support for passing an empty SpotMaxPrice parameter to remove a value previously set when updating an Amazon EC2 Auto Scaling group.
* feature: CostExplorer: Added metrics to normalized units.
* feature: ELBv2: This release enables you to use the existing client secret when modifying a rule with an action of type authenticate-oidc.
* feature: MediaStore: This release adds support for access logging, which provides detailed records for the requests that are made to objects in a container.

## 2.409.0
* feature: Athena: This release adds tagging support for Workgroups to Amazon Athena. Use these APIs to add, remove, or list tags on Workgroups, and leverage the tags for various authorization and billing scenarios.
* feature: Cloud9: Adding EnvironmentLifecycle to the Environment data type.
* feature: Glue: AWS Glue adds support for assigning AWS resource tags to jobs, triggers, development endpoints, and crawlers. Each tag consists of a key and an optional value, both of which you define. With this capacity, customers can use tags in AWS Glue to easily organize and identify your resources, create cost allocation reports, and control access to resources. 
* feature: StepFunctions: This release adds support for tag-on-create. You can now add tags when you create AWS Step Functions activity and state machine resources. For more information about tagging, see AWS Tagging Strategies.

## 2.408.0
* feature: CodeBuild: Add support for CodeBuild local caching feature
* feature: KinesisVideoArchivedMedia: In this release, HLS playback of KVS streams can be configured to output MPEG TS fragments using the ContainerFormat parameter. HLS playback of KVS streams can also be configured to include the EXT-X-PROGRAM-DATE-TIME field using the DisplayFragmentTimestamp parameter.
* feature: Transfer: Bug fix: increased the max length allowed for request parameter NextToken when paginating List operations

## 2.407.0
* feature: CodeCommit: This release adds an API for adding / updating / deleting / copying / moving / setting file modes for one or more files directly to an AWS CodeCommit repository without requiring a Git client.
* feature: DirectConnect: Documentation updates for AWS Direct Connect
* feature: MediaLive: This release adds support for VPC inputs, allowing you to push content from your Amazon VPC directly to MediaLive.

## 2.406.0
* feature: DirectoryService: This release adds support for tags during directory creation (CreateDirectory, CreateMicrosoftAd, ConnectDirectory).
* feature: EFS: Amazon EFS now supports adding tags to file system resources as part of the CreateFileSystem API . Using this capability, customers can now more easily enforce tag-based authorization for EFS file system resources.
* feature: Iot: AWS IoT - AWS IoT Device Defender adds support for configuring behaviors in a security profile with statistical thresholds. Device Defender also adds support for configuring multiple data-point evaluations before a violation is either created or cleared.
* feature: SSM: AWS Systems Manager now supports adding tags when creating Activations, Patch Baselines, Documents, Parameters, and Maintenance Windows

## 2.405.0
* feature: Athena: This release adds support for Workgroups to Amazon Athena. Use Workgroups to isolate users, teams, applications or workloads in the same account, control costs by setting up query limits and creating Amazon SNS alarms, and publish query-related metrics to Amazon CloudWatch. 
* feature: SecretsManager: This release increases the maximum allowed size of SecretString or SecretBinary from 4KB to 7KB in the CreateSecret, UpdateSecret, PutSecretValue and GetSecretValue APIs.

## 2.404.0
* feature: ApplicationAutoScaling: Documentation updates for Application Auto Scaling
* feature: Iot: In this release, IoT Device Defender introduces support for tagging Scheduled Audit resources.

## 2.403.0
* feature: EC2: This release adds tagging and ARN support for AWS Client VPN Endpoints.You can now run bare metal workloads on EC2 M5 and M5d instances. m5.metal and m5d.metal instances are powered by custom Intel Xeon Scalable Processors with a sustained all core frequency of up to 3.1 GHz. m5.metal and m5d.metal offer 96 vCPUs and 384 GiB of memory. With m5d.metal, you also have access to 3.6 TB of NVMe SSD-backed instance storage. m5.metal and m5d.metal instances deliver 25 Gbps of aggregate network bandwidth using Elastic Network Adapter (ENA)-based Enhanced Networking, as well as 14 Gbps of bandwidth to EBS.You can now run bare metal workloads on EC2 z1d instances. z1d.metal instances are powered by custom Intel Xeon Scalable Processors with a sustained all core frequency of up to 4.0 GHz. z1d.metal offers 48 vCPUs, 384 GiB of memory, and 1.8 TB of NVMe SSD-backed instance storage. z1d.metal instances deliver 25 Gbps of aggregate network bandwidth using Elastic Network Adapter (ENA)-based Enhanced Networking, as well as 14 Gbps of bandwidth to EBS.
* feature: KinesisVideo: Adds support for Tag-On-Create for Kinesis Video Streams. A list of tags associated with the stream can be created at the same time as the stream creation.

## 2.402.0
* feature: EFS: Customers can now use the EFS Infrequent Access (IA) storage class to more cost-effectively store larger amounts of data in their file systems. EFS IA is cost-optimized storage for files that are not accessed every day. You can create a new file system and enable Lifecycle Management to automatically move files that have not been accessed for 30 days from the Standard storage class to the IA storage class.
* feature: MediaTailor: This release adds support for tagging AWS Elemental MediaTailor resources.
* feature: Rekognition: GetContentModeration now returns the version of the moderation detection model used to detect unsafe content.

## 2.401.0
* feature: AppStream: This update enables customers to find the start time, max expiration time, and connection status associated with AppStream streaming session.
* feature: CodeBuild: Add customized webhook filter support
* feature: MediaPackage: Adds optional configuration for DASH to compact the manifest by combining duplicate SegmentTemplate tags. Adds optional configuration for DASH SegmentTemplate format to refer to segments by "Number" (default) or by "Time".

## 2.400.0
* feature: DLM: This release is to correct the timestamp format to ISO8601 for the DateCreated and DateModified files in the GetLifecyclePolicy response object.
* feature: ECS: Amazon ECS introduces the PutAccountSettingDefault API, an API that allows a user to set the default ARN/ID format opt-in status for all the roles and users in the account. Previously, setting the account's default opt-in status required the use of the root user with the PutAccountSetting API.

## 2.399.0
* feature: ES: Feature: Support for three Availability Zone deployments
* feature: GameLift: This release delivers a new API action for deleting unused matchmaking rule sets. More details are available at https://aws.amazon.com/releasenotes/?tag=releasenotes%23keywords%23amazon-gamelift.
* feature: MediaLive: This release adds tagging of channels, inputs, and input security groups.
* feature: RoboMaker: Added support for tagging and tag-based access control for AWS RoboMaker resources. Also, DescribeSimulationJob now includes a new failureReason field to help debug simulation job failures

## 2.398.0
* feature: EC2: Add Linux with SQL Server Standard, Linux with SQL Server Web, and Linux with SQL Server Enterprise to the list of allowed instance platforms for On-Demand Capacity Reservations.
* feature: FSx: New optional ExportPath parameter added to the CreateFileSystemLustreConfiguration object for user-defined export paths. Used with the CreateFileSystem action when creating an Amazon FSx for Lustre file system.

## 2.397.0
* feature: EC2: ec2.DescribeVpcPeeringConnections pagination support
* feature: Shield: The DescribeProtection request now accepts resource ARN as valid parameter.

## 2.396.0
* feature: CodeCommit: This release supports a more graceful handling of the error case when a repository is not associated with a pull request ID in a merge request in AWS CodeCommit.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for GPU workloads by enabling you to create clusters with GPU-enabled container instances.
* feature: WorkSpaces: This release sets ClientProperties as a required parameter.

## 2.395.0
* feature: CodeCommit: The PutFile API will now throw new exception FilePathConflictsWithSubmodulePathException when a submodule exists at the input file path; PutFile API will also throw FolderContentSizeLimitExceededException when the total size of any folder on the path exceeds the limit as a result of the operation.
* feature: DeviceFarm: Introduces a new rule in Device Pools - "Availability". Customers can now ensure they pick devices that are available (i.e., not being used by other customers).
* feature: MediaConnect: This release adds support for tagging, untagging, and listing tags for existing AWS Elemental MediaConnect resources.
* feature: MediaLive: This release adds support for Frame Capture output groups and for I-frame only manifests (playlists) in HLS output groups.

## 2.394.0
* feature: CodeBuild: This release adds support for cross-account ECR images and private registry authentication. 
* feature: ECR: Amazon ECR updated the default endpoint URL to support AWS Private Link.
* feature: ELBv2: Elastic Load Balancing now supports TLS termination on Network Load Balancers. With this launch, you can offload the decryption/encryption of TLS traffic from your application servers to the Network Load Balancer. This enables you to run your backend servers optimally and keep your workloads secure. Additionally, Network Load Balancers preserve the source IP of the clients to the back-end applications, while terminating TLS on the load balancer.  When TLS is enabled on an NLB, Access Logs can be enabled for the load balancer, and log entries will be emitted for all TLS connections.
* feature: PinpointSMSVoice: Added the ListConfigurationSets operation, which returns a list of the configuration sets that are associated with your account.
* feature: RDS: The Amazon RDS API allows you to add or remove Identity and Access Management (IAM) role associated with a specific feature name with an RDS database instance. This helps with capabilities such as invoking Lambda functions from within a trigger in the database, load data from Amazon S3 and so on

## 2.393.0
* bugfix: S3 managed uploader: S3 managed uploader will not uriEscape tags when doing a multi-part upload.
* feature: ACMPCA: Added TagOnCreate parameter to the CreateCertificateAuthority operation, updated the Tag regex pattern to align with AWS tagging APIs, and added RevokeCertificate limit.
* feature: ApiGatewayManagementApi: Fixes a typo in the 'max' constraint.
* feature: WorkLink: This is the initial SDK release for Amazon WorkLink. Amazon WorkLink is a fully managed, cloud-based service that enables secure, one-click access to internal websites and web apps from mobile phones. With Amazon WorkLink, employees can access internal websites as seamlessly as they access any other website. IT administrators can manage users, devices, and domains by enforcing their own security and access policies via the AWS Console or the AWS SDK.

## 2.392.0
* feature: AppStream: This API update includes support for tagging Stack, Fleet, and ImageBuilder resources at creation time.
* feature: DMS: Update for DMS TestConnectionSucceeds waiter
* feature: Discovery: The Application Discovery Service's import APIs allow you to import information about your on-premises servers and applications into ADS so that you can track the status of your migrations through the Migration Hub console.
* feature: FMS: This release provides support for cleaning up web ACLs during Firewall Management policy deletion. You can now enable the DeleteAllPolicyResources flag and it will delete all system-generated web ACLs.
* feature: SSM: AWS Systems Manager State Manager now supports configuration management of all AWS resources through integration with Automation. 

## 2.391.0
* feature: EC2: Adjust EC2's available instance types.
* feature: Glue: AllocatedCapacity field is being deprecated and replaced with MaxCapacity field

## 2.390.0
* feature: Lightsail: This release adds functionality to the CreateDiskSnapshot API that allows users to snapshot instance root volumes. It also adds various documentation updates.
* feature: Pinpoint: This release updates the PutEvents operation. AppPackageName, AppTitle, AppVersionCode, SdkName fields will now be accepted as a part of the event when submitting events.
* feature: Rekognition: GetLabelDetection now returns bounding box information for common objects and a hierarchical taxonomy of detected labels. The version of the model used for video label detection is also returned. DetectModerationLabels now returns the version of the model used for detecting unsafe content.
* feature: credentials: make resolvedProfile cached inenumerable

## 2.389.0
* feature: Backup: AWS Backup is a unified backup service designed to protect AWS services and their associated data. AWS Backup simplifies the creation, migration, restoration, and deletion of backups, while also providing reporting and auditing
* feature: DynamoDB: Amazon DynamoDB now integrates with AWS Backup, a centralized backup service that makes it easy for customers to configure and audit the AWS resources they want to backup, automate backup scheduling, set retention policies, and monitor all recent backup and restore activity. AWS Backup provides a fully managed, policy-based backup solution, simplifying your backup management, and helping you meet your business and regulatory backup compliance requirements. For more information, see the Amazon DynamoDB Developer Guide.

## 2.388.0
* feature: MediaConvert: IMF decode from a Composition Playlist for IMF specializations App #2 and App #2e; up to 99 input clippings; caption channel selection for MXF; and updated rate control for CBR jobs. Added support for acceleration in preview
* feature: StorageGateway: JoinDomain API supports two more  parameters: organizational unit(OU) and domain controllers.  Two new APIs are introduced: DetachVolume and AttachVolume.

## 2.387.0
* feature: RDSDataService: Documentation updates for RDS Data API.
* feature: client side monitoring: Add a new environmental variable AWS_ENDPOINT_DISCOVERY_ENABLED to work along with AWS_ENABLE_ENDPOINT_DISCOVERY
* feature: client side monitoring: CSM now can be enabled globally only from environment without code change

## 2.386.0
* feature: EC2: EC2 Spot: a) CreateFleet support for Single AvailabilityZone requests and b) support for paginated DescribeSpotInstanceRequests.
* feature: Iot: This release adds tagging support for rules of AWS IoT Rules Engine. Tags enable you to categorize your rules in different ways, for example, by purpose, owner, or environment. For more information about tagging, see AWS Tagging Strategies (https://aws.amazon.com/answers/account-management/aws-tagging-strategies/). For technical documentation, look for the tagging operations in the AWS IoT Core API reference or User Guide (https://docs.aws.amazon.com/iot/latest/developerguide/tagging-iot.html).
* feature: SageMaker: SageMaker Training Jobs now support Inter-Container traffic encryption.

## 2.385.0
* feature: DocDB: Amazon DocumentDB (with MongoDB compatibility) is a fast, reliable, and fully-managed database service. Amazon DocumentDB makes it easy for developers to set up, run, and scale MongoDB-compatible databases in the cloud.
* feature: Redshift: DescribeSnapshotSchedules returns a list of snapshot schedules. With this release, this API will have a list of clusters and number of clusters associated with the schedule.
* feature: s3: Improved sigv4 documentation on getSignedUrl operation

## 2.384.0
* feature: DeviceFarm: "This release provides support for running Appium Node.js and Appium Ruby tests on AWS Device Farm.

## 2.383.0
* bugfix: credentials: Make CredentialProviderChain coalesce resolvation synchronous
* bugfix: typings: update Attribute value to any for transaction operations input and output
* feature: IoTAnalytics: ListDatasetContents now has a filter to limit results by date scheduled.
* feature: MediaStoreData: enable cors to make MediaStoreData available in default browser build

## 2.382.0
* bugfix: CredentailProviderChain: CredentialProviderChain.resolve now coalesces calls, so that concurrent requests for a service instance which has yet to resolve credentials will not result in a stampede to assign config.credentials
* bugfix: documentation: swap abstract Yard tag for custom tags to support compatibility with google-closure-compiler
* feature: ACMPCA: This release marks the introduction of waiters in ACM PCA, which allow you to control the progression of your code based on the presence or state of certain resources. Waiters can be implemented in the DescribeCertificateAuthorityAuditReport, GetCertificate, and GetCertificateAuthorityCsr API operations.
* feature: DynamoDB: Added provisionedThroughPut exception on the request level for transaction APIs.
* feature: EC2MetadataCredentials: refresh now passes an error to callback if metadata service responds with expired credentials
* feature: PinpointSMSVoice: Configuration sets can now use Amazon SNS as an event destination.
* feature: StepFunctions: This release adds support for cost allocation tagging. You can now create, delete, and list tags for AWS Step Functions activity and state machine resources. For more information about tagging, see AWS Tagging Strategies.

## 2.381.0
* bugfix: S3: fix putObject using stream <1mb
* feature: CognitoIdentityServiceProvider: Amazon Cognito now has API support for updating the Secure Sockets Layer (SSL) certificate for the custom domain for your user pool.
* feature: Comprehend: This SDK release adds functionality to stop training Custom Document Classifier or Custom Entity Recognizer in Amazon Comprehend.
* feature: Firehose: Support for specifying customized s3 keys and supplying a separate prefix for failed-records
* feature: KinesisVideoMedia: enable cors to make KinesisVideoMedia available by default in browser build
* feature: MediaLive: This release provides support for ID3 tags and video quality setting for subgop_length.
* feature: TranscribeService: With this release, Amazon Transcribe now supports transcriptions from audio sources in Italian (it-IT).

## 2.380.0
* feature: EC2: This release adds support for specifying partition as a strategy for EC2 Placement Groups. This new strategy allows one to launch instances into partitions that do not share certain underlying hardware between partitions, to assist with building and deploying highly available replicated applications. 
* feature: SageMaker: Batch Transform Jobs now supports TFRecord as a Split Type. ListCompilationJobs API action now supports SortOrder and SortBy inputs.
* feature: WAF: This release adds rule-level control for rule group. If a rule group contains a rule that blocks legitimate traffic, previously you had to override the entire rule group to COUNT in order to allow the traffic. You can now use the UpdateWebACL API to exclude specific rules within a rule group. Excluding rules changes the action for the individual rules to COUNT. Excluded rules will be recorded in the new "excludedRules" attribute of the WAF logs.
* feature: WAFRegional: This release adds rule-level control for rule group. If a rule group contains a rule that blocks legitimate traffic, previously you had to override the entire rule group to COUNT in order to allow the traffic. You can now use the UpdateWebACL API to exclude specific rules within a rule group. Excluding rules changes the action for the individual rules to COUNT. Excluded rules will be recorded in the new "excludedRules" attribute of the WAF logs.

## 2.379.0
* bugfix: S3: fix fo #2418, putObject with key as substring of bucket results in extra folder
* feature: ApiGatewayManagementApi: This is the initial SDK release for the Amazon API Gateway Management API, which allows you to directly manage runtime aspects of your APIs. This release makes it easy to send data directly to clients connected to your WebSocket-based APIs.
* feature: ApiGatewayV2: This is the initial SDK release for the Amazon API Gateway v2 APIs. This SDK will allow you to manage and configure APIs in Amazon API Gateway; this first release provides the capabilities that allow you to programmatically setup and manage WebSocket APIs end to end. 
* feature: EC2: Client VPN, is a client-based VPN service. With Client VPN, you can securely access resources in AWS as well as access resources in on-premises from any location using OpenVPN based devices. With Client VPN, you can set network based firewall rules that can restrict access to networks based on Active Directory groups.
* feature: ElasticBeanstalk: This release adds a new resource that Elastic Beanstalk will soon support, EC2 launch template, to environment resource descriptions.

## 2.378.0
* feature: ECR: This release adds support for ECR repository tagging.
* feature: QuickSight: Amazon QuickSight's RegisterUser API now generates a user invitation URL when registering a user with the QuickSight identity type. This URL can then be used by the registered QuickSight user to complete the user registration process. This release also corrects some HTTP return status codes.

## 2.377.0
* feature: AlexaForBusiness: Released new APIs for managing private skill access to Enrolled Users.  These API's are the equivalent of the A4B console for Private Skills checkbox "Available for Users".
* feature: Comprehend: enable cors

## 2.376.0
* feature: PinpointEmail: This release adds new operations for the Amazon Pinpoint Deliverability Dashboard. You can use the Deliverability Dashboard to view response and inbox placement metrics for the domains that you use to send email. You can also perform tests on individual email messages to determine how often your messages are delivered to the inbox on several major email providers.

## 2.375.0
* feature: EKS: Added support for updating kubernetes version of Amazon EKS clusters.
* feature: Glue: API Update for Glue: this update enables encryption of password inside connection objects stored in AWS Glue Data Catalog using DataCatalogEncryptionSettings.  In addition, a new "HidePassword" flag is added to GetConnection and GetConnections to return connections without passwords.
* feature: Route53: You can now specify a new region, eu-north-1 (in Stockholm, Sweden), as a region for latency-based or geoproximity routing.
* feature: SageMaker: Amazon SageMaker Automatic Model Tuning now supports early stopping of training jobs. With early stopping, training jobs that are unlikely to generate good models will be automatically stopped during a Hyperparameter Tuning Job.

## 2.374.0
* feature: Connect: This update adds the GetContactAttributes operation to retrieve the attributes associated with a contact.
* feature: MediaStore: This release adds Delete Object Lifecycling to AWS MediaStore Containers.

## 2.373.0
* feature: AlexaForBusiness: Alexa for Business now allows IT administrators to create ad-hoc or scheduled usage reports, which help customers understand how Alexa is used in their workplace. To learn how to create usage reports, see https://docs.aws.amazon.com/a4b/latest/ag/creating-reports.html
* feature: DynamoDB: Add DynamoDB document client support for transaction operations
* feature: EC2: You can now launch the larger-sized P3dn.24xlarge instance that features NVIDIA Tesla V100s with double the GPU memory, 100Gbps networking and local NVMe storage.
* feature: IAM: We are making it easier for you to manage your AWS Identity and Access Management (IAM) policy permissions by enabling you to retrieve the last timestamp when an IAM entity (e.g., user, role, or a group) accessed an AWS service. This feature also allows you to audit service access for your entities.

## 2.372.0
* feature: CodeBuild: Support personal access tokens for GitHub source and app passwords for Bitbucket source
* feature: ELBv2: This release allows Application Load Balancers to route traffic to Lambda functions, in addition to instances and IP addresses.
* feature: MediaLive: This release enables the AWS Elemental MediaConnect input type in AWS Elemental MediaLive. This can then be used to automatically create and manage AWS Elemental MediaConnect Flow Outputs when you create a channel using those inputs.

## 2.371.0
* feature: CostExplorer: Add normalized unit support for both GetReservationUtilization and GetReservationCoverage API.
* feature: MQ: This release adds support for cost allocation tagging. You can now create, delete, and list tags for AmazonMQ resources. For more information about tagging, see AWS Tagging Strategies.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now includes a new parameter to control the Location tag of DASH manifests.

## 2.370.0
* feature: Health: AWS Health API DescribeAffectedEntities operation now includes a field that returns the URL of the affected entity.
* feature: S3: S3 Inventory reports can now be generated in Parquet format by setting the Destination Format to be 'Parquet'.

## 2.369.0
* feature: DeviceFarm: Customers can now schedule runs without a need to create a Device Pool. They also get realtime information on public device availability.
* feature: StorageGateway: API list-local-disks returns a list of the gateway's local disks. This release adds a field DiskAttributeList to these disks.

## 2.368.0
* bugfix: md5: enable SDK to calculate content MD5 for more new S3 operations
* feature: S3: Fixed issue with Content-MD5 for S3 PutObjectLegalHold, PutObjectRetention and PutObjectLockConfiguration.

## 2.367.0
* feature: CloudWatchEvents: Support for Managed Rules (rules that are created and maintained by the AWS services in your account) is added.
* feature: ELBv2: This release allows Application Load Balancers to route traffic to Lambda functions, in addition to instances and IP addresses.
* feature: Kafka: This is the initial SDK release for Amazon Managed Streaming for Kafka (Amazon MSK). Amazon MSK is a service that you can use to easily build, monitor, and manage Apache Kafka clusters in the cloud.
* feature: Lambda: AWS Lambda now supports Lambda Layers and Ruby as a runtime. Lambda Layers are a new type of artifact that contains arbitrary code and data, and may be referenced by zero, one, or more functions at the same time.  You can also now develop your AWS Lambda function code using the Ruby programming language.
* feature: S3: Fixed issue with ObjectLockRetainUntilDate in S3 PutObject
* feature: ServerlessApplicationRepository: AWS Serverless Application Repository now supports nested applications. You can nest individual applications as components of a larger application to make it easy to assemble and deploy new serverless architectures. 
* feature: StepFunctions: AWS Step Functions is now integrated with eight additional AWS services: Amazon ECS, AWS Fargate, Amazon DynamoDB, Amazon SNS, Amazon SQS, AWS Batch, AWS Glue, and Amazon SageMaker. To learn more, please see https://docs.aws.amazon.com/step-functions/index.html
* feature: XRay: GetTraceSummaries - Now provides additional information regarding your application traces such as Availability Zone, Instance ID, Resource ARN details, Revision, Entry Point, Root Cause Exceptions and Root Causes for Fault, Error and Response Time.

## 2.366.0
* feature: AppMesh: AWS App Mesh is a service mesh that makes it easy to monitor and control communications between microservices of an application. AWS App Mesh APIs are available for preview in eu-west-1, us-east-1, us-east-2, and us-west-2 regions.
* feature: EC2: Adds the following updates: 1. You can now hibernate and resume Amazon-EBS backed instances using the StopInstances and StartInstances APIs. For more information about using this feature and supported instance types and operating systems, visit the user guide. 2. Amazon Elastic Inference accelerators are resources that you can attach to current generation EC2 instances to accelerate your deep learning inference workloads. With Amazon Elastic Inference, you can configure the right amount of inference acceleration to your deep learning application without being constrained by fixed hardware configurations and limited GPU selection. 3. AWS License Manager makes it easier to manage licenses in AWS and on premises when customers run applications using existing licenses from a variety of software vendors including Microsoft, SAP, Oracle, and IBM.
* feature: LicenseManager: AWS License Manager makes it easier to manage licenses in AWS and on premises when customers run applications using existing licenses from a variety of software vendors including Microsoft, SAP, Oracle, and IBM. AWS License Manager automatically tracks and controls license usage once administrators have created and enforced rules that emulate the terms of their licensing agreements. The capabilities of AWS License Manager are available through SDK and Tools, besides the management console and CLI.
* feature: Lightsail: This update adds the following features: 1. Copy instance and disk snapshots within the same AWS Region or from one region to another in Amazon Lightsail. 2. Export Lightsail instance and disk snapshots to Amazon Elastic Compute Cloud (Amazon EC2). 3. Create an Amazon EC2 instance from an exported Lightsail instance snapshot using AWS CloudFormation stacks. 4. Apply tags to filter your Lightsail resources, or organize your costs, or control access.
* feature: SageMaker: Amazon SageMaker now has Algorithm and Model Package entities that can be used to create Training Jobs, Hyperparameter Tuning Jobs and hosted Models. Subscribed Marketplace products can be used on SageMaker to create Training Jobs, Hyperparameter Tuning Jobs and Models. Notebook Instances and Endpoints can leverage Elastic Inference accelerator types for on-demand GPU computing. Model optimizations can be performed with Compilation Jobs. Labeling Jobs can be created and supported by a Workforce. Models can now contain up to 5 containers allowing for inference pipelines within Endpoints. Code Repositories (such as Git) can be linked with SageMaker and loaded into Notebook Instances. Network isolation is now possible on Models, Training Jobs, and Hyperparameter Tuning Jobs, which restricts inbound/outbound network calls for the container. However, containers can talk to their peers in distributed training mode within the same security group. A Public Beta Search API was added that currently supports Training Jobs.
* feature: ServiceDiscovery: AWS Cloud Map lets you define friendly names for your cloud resources so that your applications can quickly and dynamically discover them. When a resource becomes available (for example, an Amazon EC2 instance running a web server), you can register a Cloud Map service instance. Then your application can discover service instances by submitting DNS queries or API calls.

## 2.365.0
* feature: DynamoDB: Amazon DynamoDB now supports the following features: DynamoDB on-demand and transactions. DynamoDB on-demand is a flexible new billing option for DynamoDB capable of serving thousands of requests per second without capacity planning. DynamoDB on-demand offers simple pay-per-request pricing for read and write requests so that you only pay for what you use, making it easy to balance costs and performance. Transactions simplify the developer experience of making coordinated, all-or-nothing changes to multiple items both within and across tables. The new transactional APIs provide atomicity, consistency, isolation, and durability (ACID) in DynamoDB, helping developers support sophisticated workflows and business logic that requires adding, updating, or deleting multiple items using native, server-side transactions. For more information, see the Amazon DynamoDB Developer Guide.
* feature: FSx: Amazon FSx provides fully-managed third-party file systems optimized for a variety of enterprise and compute-intensive workloads.
* feature: RDS: Amazon Aurora Global Database. This release introduces support for Global Database, a feature that allows a single Amazon Aurora database to span multiple AWS regions. Customers can use the feature to replicate data with no impact on database performance, enable fast local reads with low latency in each region, and improve disaster recovery from region-wide outages. You can create, modify and describe an Aurora Global Database, as well as add or remove regions from your Global Database.
* feature: SecurityHub: AWS Security Hub is a security and compliance center that correlates AWS security findings and performs automated compliance checks

## 2.364.0
* feature: CloudWatchLogs: Six new APIs added to support CloudWatch Logs Insights. The APIs are StartQuery, StopQuery, GetQueryResults, GetLogRecord, GetLogGroupFields, and DescribeQueries.
* feature: CodeDeploy: Support for Amazon ECS service deployment - AWS CodeDeploy now supports the deployment of Amazon ECS services. An Amazon ECS deployment uses an Elastic Load Balancer, two Amazon ECS target groups, and a listener to reroute production traffic from your Amazon ECS service's original task set to a new replacement task set. The original task set is terminated when the deployment is complete. Success of a deployment can be validated using Lambda functions that are referenced by the deployment. This provides the opportunity to rollback if necessary. You can use the new ECSService, ECSTarget, and ECSTaskSet data types in the updated SDK to create or retrieve an Amazon ECS deployment.
* feature: ComprehendMedical: The first release of Comprehend Medical includes two APIs, detectPHI and detectEntities. DetectPHI extracts PHI from your clinical text, and detectEntities extracts entities such as medication, medical conditions, or anatomy. DetectEntities also extracts attributes (e.g. dosage for medication) and identifies contextual traits (e.g. negation) for each entity.
* feature: EC2: With VPC sharing, you can now allow multiple accounts in the same AWS Organization to launch their application resources, like EC2 instances, RDS databases, and Redshift clusters into shared, centrally managed VPCs.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for blue/green deployment feature. Customers can now update their ECS services in a blue/green deployment pattern via using AWS CodeDeploy.
* feature: KinesisAnalytics: Improvements to error messages, validations, and more to the Kinesis Data Analytics APIs.
* feature: KinesisAnalyticsV2: Amazon Kinesis Data Analytics now supports Java-based stream processing applications, in addition to the previously supported SQL. Now, you can use your own Java code in Amazon Kinesis Data Analytics to build and run stream processing applications. This new capability also comes with an update to the previous Amazon Kinesis Data Analytics APIs to enable support for different runtime environments and more.
* feature: MarketplaceMetering: RegisterUsage operation added to AWS Marketplace Metering Service, allowing sellers to meter and entitle Docker container software use with AWS Marketplace. For details on integrating Docker containers with RegisterUsage see: https://docs.aws.amazon.com/marketplace/latest/userguide/entitlement-and-metering-for-paid-products.html
* feature: MediaConnect: This is the initial release for AWS Elemental MediaConnect, an ingest and transport service for live video. This new AWS service allows broadcasters and content owners to send high-value live content into the cloud, securely transmit it to partners for distribution, and replicate it to multiple destinations around the globe.
* feature: Translate: This release includes the new custom terminology feature. Using custom terminology with your translation requests enables you to make sure that your brand names, character names, model names, and other unique content is translated exactly the way you need it, regardless of its context and the Amazon Translate algorithm's decision. See the documentation for more information.

## 2.363.0
* feature: EC2: Adds the following updates: 1. Transit Gateway helps easily scale connectivity across thousands of Amazon VPCs, AWS accounts, and on-premises networks. 2. Amazon EC2 A1 instance is a new Arm architecture based general purpose instance. 3. You can now launch the new Amazon EC2 compute optimized C5n instances that can utilize up to 100 Gbps of network bandwidth.
* feature: GlobalAccelerator: AWS Global Accelerator is a network layer service that helps you improve the availability and performance of the applications that you offer to your global customers. Global Accelerator uses the AWS global network to direct internet traffic from your users to your applications running in AWS Regions. Global Accelerator creates a fixed entry point for your applications through static anycast IP addresses, and routes user traffic to the optimal endpoint based on performance, application health and routing policies that you can configure. Global Accelerator supports the following features at launch: static anycast IP addresses, support for TCP and UDP, support for Network Load Balancers, Application Load Balancers and Elastic-IP address endpoints,  continuous health checking, instant regional failover, fault isolating Network Zones, granular traffic controls, and client affinity.
* feature: Greengrass: Support Greengrass Connectors and allow Lambda functions to run without Greengrass containers.
* feature: IoTAnalytics: Added an optional list of dataset content delivery configuration for CreateDataset and UpdateDataset. DescribeDataset will now include the list of delivery configuration, and will be an empty array if none exist.
* feature: Iot: As part of this release, we are extending capability of AWS IoT Rules Engine to support IoT Events rule action. The IoT Events rule action lets you send messages from IoT sensors and applications to IoT Events for pattern recognition and event detection.
* feature: KMS: AWS Key Management Service (KMS) now enables customers to create and manage dedicated, single-tenant key stores in addition to the default KMS key store. These are known as custom key stores and are deployed using AWS CloudHSM clusters. Keys that are created in a KMS custom key store can be used like any other customer master key in KMS.
* feature: S3: Four new Amazon S3 Glacier features help you reduce your storage costs by making it even easier to build archival applications using the Amazon S3 Glacier storage class. S3 Object Lock enables customers to apply Write Once Read Many (WORM) protection to objects in S3 in order to prevent object deletion for a customer-defined retention period. S3 Inventory now supports fields for reporting on S3 Object Lock. "ObjectLockRetainUntilDate", "ObjectLockMode", and "ObjectLockLegalHoldStatus" are now available as valid optional fields.
* feature: SMS: In this release, AWS Server Migration Service (SMS) has added multi-server migration support to simplify the application migration process. Customers can migrate all their application-specific servers together as a single unit as opposed to moving individual server one at a time. The new functionality includes - 1. Ability to group on-premises servers into applications and application tiers. 2. Auto-generated CloudFormation Template and Stacks for launching migrated servers into EC2. 3. Ability to run post-launch configuration scripts to configure servers and applications in EC2. In order for SMS to launch servers into your AWS account using CloudFormation Templates, we have also updated the ServerMigrationServiceRole IAM policy to include appropriate permissions. Refer to Server Migration Service documentation for more details. 

## 2.362.0
* bugfix: Config: fix useDualstack typing
* feature: Amplify: Release of AWS Amplify: Everything you need to develop & deploy cloud-powered mobile and web apps.
* feature: DataSync: AWS DataSync simplifies, automates, and accelerates moving and replicating data between on-premises storage and AWS services over the network.
* feature: RoboMaker: (New Service) AWS RoboMaker is a service that makes it easy to develop, simulate, and deploy intelligent robotics applications at scale. 
* feature: S3: The INTELLIGENT_TIERING storage class is designed to optimize storage costs by automatically moving data to the most cost effective storage access tier, without performance impact or operational overhead. This SDK release provides API support for this new storage class.
* feature: Snowball: AWS announces the availability of AWS Snowball Edge Compute Optimized to run compute-intensive applications is disconnected and physically harsh environments. It comes with 52 vCPUs, 208GB memory, 8TB NVMe SSD, and 42TB S3-compatible storage to accelerate local processing and is well suited for use cases such as full motion video processing, deep IoT analytics, and continuous machine learning in bandwidth-constrained locations. It features new instances types called SBE-C instances that are available in eight sizes and multiple instances can be run on the device at the same time. Optionally, developers can choose the compute optimized device to include a GPU and use SBE-G instances for accelerating their application performance. 
* feature: Transfer: AWS Transfer for SFTP is a fully managed service that enables transfer of secure data over the internet into and out of Amazon S3. SFTP is deeply embedded in data exchange workflows across different industries such as financial services, healthcare, advertising, and retail, among others.
* feature: protocol: Add support for 'endpoint' trait in API operation model

## 2.361.0
* feature: Rekognition: This release updates the DetectFaces and IndexFaces operation. When the Attributes input parameter is set to ALL, the face location landmarks includes 5 new landmarks: upperJawlineLeft, midJawlineLeft, chinBottom, midJawlineRight, upperJawlineRight.

## 2.360.0
* feature: AppSync: AWS AppSync now supports: 1. Pipeline Resolvers - Enables execution of one or more operations against multiple data sources in order, on a single GraphQL field. This allows orchestration of actions by composing code into a single Resolver, or share code across Resolvers.  2. Aurora Serverless Data Source - Built-in resolver for executing GraphQL operations with the new Aurora Serverless Data API, including connection management functionality.
* feature: AutoScalingPlans: In this release, AWS Auto Scaling adds three features: 1) Predictive scaling for EC2 Auto Scaling, which analyzes your application workload history to forecast future capacity requirements, 2) an option to replace existing scaling policies that are associated with the resources in your scaling plan, and 3) an option that allows you to use predictive scaling with or without your plan's dynamic scaling feature.
* feature: CloudFront: With Origin Failover capability in CloudFront, you can setup two origins for your distributions - primary and secondary, such that your content is served from your secondary origin if CloudFront detects that your primary origin is unavailable. These origins can be any combination of AWS origins or non-AWS custom HTTP origins. For example, you can have two Amazon S3 buckets that serve as your origin that you independently upload your content to. If an object that CloudFront requests from your primary bucket is not present or if connection to your primary bucket times-out, CloudFront will request the object from your secondary bucket. So, you can configure CloudFront to trigger a failover in response to either HTTP 4xx or 5xx status codes.
* feature: CloudWatch: Amazon CloudWatch now supports alarms on metric math expressions.
* feature: DeviceFarm: Disabling device filters
* feature: MediaLive: You can now include the media playlist(s) from both pipelines in the HLS master manifest for seamless failover.
* feature: QuickSight: Amazon QuickSight is a fully managed, serverless, cloud business intelligence system that allows you to extend data and insights to every user in your organization. The first release of APIs for Amazon QuickSight introduces embedding and user/group management capabilities. The get-dashboard-embed-url API allows you to obtain an authenticated dashboard URL that can be embedded in application domains whitelisted for QuickSight dashboard embedding. User APIs allow you to programmatically expand and manage your QuickSight deployments while group APIs allow easier permissions management for resources within QuickSight.
* feature: RDSDataService: The RDS Data API Beta is available for the MySQL-compatible edition of Amazon Aurora Serverless in the US East (N. Virginia) Region. This API enables you to easily access Aurora Serverless with web services-based applications including AWS Lambda and AWS AppSync.
* feature: SSM: AWS Systems Manager Distributor helps you securely distribute and install software packages.
* feature: XRay: Groups build upon X-Ray filter expressions to allow for fine tuning trace summaries and service graph results. You can configure groups by using the AWS X-Ray console or by using the CreateGroup API. The addition of groups has extended the available request fields to the GetServiceGraph API. You can now specify a group name or group ARN to retrieve its service graph.

## 2.359.0
* feature: Batch: Adding multinode parallel jobs, placement group support for compute environments.
* feature: CloudFormation: Use the CAPABILITY_AUTO_EXPAND capability to create or update a stack directly from a stack template that contains macros, without first reviewing the resulting changes in a change set first.
* feature: CloudTrail: This release supports creating a trail in CloudTrail that logs events for all AWS accounts in an organization in AWS Organizations. This helps enable you to define a uniform event logging strategy for your organization. An organization trail is applied automatically to each account in the organization and cannot be modified by member accounts. To learn more, please see the AWS CloudTrail User Guide https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html
* feature: ConfigService: In this release, AWS Config adds support for aggregating the configuration data of AWS resources into multi-account and multi-region aggregators. AWS Config adds four APIs to query and retrieve aggregated resource configurations. 1) BatchGetAggregateResourceConfig, returns the current configuration items for resources that are present in your AWS Config aggregator. 2) GetAggregateDiscoveredResourceCounts, returns the resource counts across accounts and regions that are present in your AWS Config aggregator. 3) GetAggregateResourceConfig, returns current configuration item that is aggregated for your specific resource in a specific source account and region. 4) ListAggregateDiscoveredResources, accepts a resource type and returns a list of resource identifiers that are aggregated for a specific resource type across accounts and regions.
* feature: DeviceFarm: Customers can now schedule runs without a need to create a Device Pool. They also get realtime information on public device availability.
* feature: EC2: Adding AvailabilityZoneId to DescribeAvailabilityZones
* feature: Iot: IoT now supports resource tagging and tag based access control for Billing Groups, Thing Groups, Thing Types, Jobs, and Security Profiles. IoT Billing Groups help you group devices to categorize and track your costs. AWS IoT Device Management also introduces three new features: 1. Dynamic thing groups. 2. Jobs dynamic rollouts. 3. Device connectivity indexing. Dynamic thing groups lets you to create a group of devices using a Fleet Indexing query. The devices in your group will be automatically added or removed when they match your specified query criteria. Jobs dynamic rollout allows you to configure an exponentially increasing rate of deployment for device updates and define failure criteria to cancel your job. Device connectivity indexing allows you to index your devices' lifecycle events to discover whether devices are connected or disconnected to AWS IoT.
* feature: Lambda: AWS Lambda now supports python3.7 and  the Kinesis Data Streams (KDS) enhanced fan-out and HTTP/2 data retrieval features for Kinesis event sources.
* feature: MediaConvert: AWS Elemental MediaConvert SDK has added several features including support for: SPEKE full document encryption, up to 150 elements for input stitching, input and motion image insertion, AWS CLI path arguments in S3 links including special characters, AFD signaling, additional caption types, and client-side encrypted input files.
* feature: RDS: This release adds a new parameter to specify VPC security groups for restore from DB snapshot, restore to point int time and create read replica operations. For more information, see Amazon RDS Documentation.
* feature: WorkDocs: With this release, clients can now use the GetResources API to fetch files and folders from the user's SharedWithMe collection. And also through this release, the existing DescribeActivities API has been enhanced to support additional filters such as the ActivityType and the ResourceId.
* feature: WorkSpaces: Added new APIs to Modify and Describe WorkSpaces client properties for users in a directory. With the new APIs, you can enable/disable remember me option in WorkSpaces client for users in a directory.

## 2.358.0
* feature: Comprehend: Amazon Comprehend Custom Entities automatically trains entity recognition models using your entities and noun-based phrases. 
* feature: CostExplorer: This release introduces a new operation called GetCostForecast operation, which allows you to programmatically access AWS Cost Explorer's forecasting engine and is now generally available.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for additional Docker flags as Task Definition parameters. Customers can now configure their ECS Tasks to use pidMode (pid) and ipcMode (ipc) Docker flags.
* feature: SSM: AWS Systems Manager Automation now allows you to execute and manage Automation workflows across multiple accounts and regions. 
* feature: WorkSpaces: Added new Bring Your Own License (BYOL) automation APIs. With the new APIs, you can list available management CIDR ranges for dedicated tenancy, enable your account for BYOL, describe BYOL status of your account, and import BYOL images. Added new APIs to also describe and delete WorkSpaces images. 

## 2.357.0
* feature: CodeBuild: Adding queue phase and configurable queue timeout to CodeBuild.
* feature: Comprehend: Amazon Comprehend Custom Classification automatically trains classification models using your text and custom labels.
* feature: DMS: Settings structures have been added to our DMS endpoint APIs to support Kinesis and Elasticsearch as targets. We are introducing the ability to configure custom DNS name servers on a replication instance as a beta feature. 
* feature: DirectConnect: This release enables DirectConnect customers to have logical redundancy on virtual interfaces within supported DirectConnect locations.
* feature: ECS: In this release, Amazon ECS introduces multiple features. First, ECS now supports integration with Systems Manager Parameter Store for injecting runtime secrets. Second, ECS introduces support for resources tagging. Finally, ECS introduces a new ARN and ID Format for its resources, and provides new APIs for opt-in to the new formats. 
* feature: IAM: We are making it easier for you to manage your AWS Identity and Access Management (IAM) resources by enabling you to add tags to your IAM principals (users and roles). Adding tags on IAM principals will enable you to write fewer policies for permissions management and make policies easier to comprehend.  Additionally, tags will also make it easier for you to grant access to AWS resources.
* feature: Pinpoint: 1. With Amazon Pinpoint Voice, you can use text-to-speech technology to deliver personalized voice messages to your customers. Amazon Pinpoint Voice is a great way to deliver transactional messages -- such as one-time passwords and identity confirmations -- to customers. 2. Adding support for Campaign Event Triggers. With Campaign Event Triggers you can now schedule campaigns to execute based on incoming event data and target just the source of the event.
* feature: PinpointSMSVoice: With Amazon Pinpoint Voice, you can use text-to-speech technology to deliver personalized voice messages to your customers. Amazon Pinpoint Voice is a way to deliver transactional messages -- such as one-time passwords and appointment confirmations to customers.
* feature: RAM: This is the initial release of AWS Resource Access Manager (RAM) which provides you the ability to share your resources across AWS accounts or within your AWS Organization. You can now create resources centrally and use AWS RAM to share those resources with other accounts, eliminating the need to provision and manage resources in every account. When you share a resource with another account, that account is granted access. Any policies and permissions in that account apply to the shared resource. 
* feature: RDS: Introduces DB Instance Automated Backups for the MySQL, MariaDB, PostgreSQL, Oracle and Microsoft SQL Server database engines. You can now retain Amazon RDS automated backups (system snapshots and transaction logs) when you delete a database instance. This allows you to restore a deleted database instance to a specified point in time within the backup retention period even after it has been deleted, protecting you against accidental deletion of data. For more information, see Amazon RDS Documentation.
* feature: Redshift: With this release, Redshift is providing API's for better snapshot management by supporting user defined automated snapshot schedules, retention periods for manual snapshots, and aggregate snapshot actions including batch deleting user snapshots, viewing account level snapshot storage metrics, and better filtering and sorting on the describe-cluster-snapshots API. Automated snapshots can be scheduled to be taken at a custom interval and the schedule created can be reused across clusters. Manual snapshot retention periods can be set at the cluster, snapshot, and cross-region-copy level. The retention period set on a manual snapshot indicates how many days the snapshot will be retained before being automatically deleted.
* feature: Route53Resolver: This is the first release of the Amazon Route 53 Resolver API.  Customers now have the ability to create and manage Amazon Route 53 Resolver endpoints and Amazon Route 53 Resolver rules. 
* feature: S3: Add support for new S3 Block Public Access bucket-level APIs. The new Block Public Access settings allow bucket owners to prevent public access to S3 data via bucket/object ACLs or bucket policies.
* feature: S3Control: Add support for new S3 Block Public Access account-level APIs. The Block Public Access settings allow account owners to prevent public access to S3 data via bucket/object ACLs or bucket policies.
* feature: TranscribeService: With this release, Amazon Transcribe now publicly supports transcriptions from audio sources in British English (en-GB), Australian English (en-AU), and Canadian French (fr-CA). Amazon Transcribe now also supports the following languages in Private beta: Germany German (de-DE), Brazil Portuguese (pt-BR), France French (fr-FR).

## 2.356.0
* feature: AutoScaling: EC2 Auto Scaling now allows users to provision and automatically scale instances across purchase options (Spot, On-Demand, and RIs) and instance types in a single Auto Scaling group (ASG).
* feature: EC2: Amazon EC2 Fleet now supports a new request type "Instant" that you can use to provision capacity synchronously across instance types & purchase models and CreateFleet will return the instances launched in the API response.
* feature: MediaTailor: AWS Elemental MediaTailor SDK now returns a manifest endpoint prefix for clients to initiate a DASH playback session.
* feature: ResourceGroups: The AWS Resource Groups service added support for AWS CloudFormation stack-based groups.
* feature: SNS: Added an optional request parameter, named Attributes, to the Amazon SNS CreateTopic API action. For more information, see the Amazon SNS API Reference (https://docs.aws.amazon.com/sns/latest/api/API_CreateTopic.html).
* feature: SageMaker: SageMaker now makes the final set of metrics published from training jobs available in the DescribeTrainingJob results.  Automatic Model Tuning now supports warm start of hyperparameter tuning jobs.  Notebook instances now support a larger number of instance types to include instances from the ml.t3, ml.m5, ml.c4, ml.c5 families.
* feature: ServiceCatalog: Adds support for Cloudformation StackSets in Service Catalog

## 2.355.0
* feature: Chime: This release adds support in ListUsers API to filter the list by an email address.
* feature: Redshift: Amazon Redshift provides the option to defer non-mandatory maintenance updates to a later date.

## 2.354.0
* bugfix: Endpoint Discovery: Not to inspect environmental variables in browsers
* feature: Batch: Adding EC2 Launch Template support in AWS Batch Compute Environments.
* feature: Budgets: 1. Added budget performance history, enabling you to see how well your budgets matched your actual costs and usage.                                                                                             2. Added budget performance history, notification state, and last updated time, enabling you to see how well your budgets matched your actual costs and usage, how often your budget alerts triggered, and when your budget was last updated.
* feature: CloudFormation: The Drift Detection feature enables customers to detect whether a stack's actual configuration differs, or has drifted, from its expected configuration as defined within AWS CloudFormation.
* feature: CodePipeline: Add support for cross-region pipeline with accompanying definitions as needed in the AWS CodePipeline API Guide.
* feature: Firehose: With this release, Amazon Kinesis Data Firehose allows you to enable/disable server-side encryption(SSE) for your delivery streams ensuring encryption of data at rest. For technical documentation, look at https://docs.aws.amazon.com/firehose/latest/dev/encryption.html
* feature: Polly: Amazon Polly adds new female voices: Italian - Bianca, Castilian Spanish - Lucia and new language: Mexican Spanish with new female voice - Mia.
* feature: RDS: API Update for RDS: this update enables Custom Endpoints, a new feature compatible with Aurora Mysql, Aurora PostgreSQL and Neptune that allows users to configure a customizable endpoint that will provide access to their instances in a cluster. 

## 2.353.0
* feature: MediaPackage: As a part of SPEKE DRM encryption, MediaPackage now supports encrypted content keys. You can enable this enhanced content protection in an OriginEndpoint's encryption settings. When this is enabled, MediaPackage indicates to the key server that it requires an encrypted response. To use this, your DRM key provider must support content key encryption. For details on this feature, see the AWS MediaPackage User Guide at https://docs.aws.amazon.com/mediapackage/latest/ug/what-is.html.

## 2.352.0
* feature: DLM: Amazon Data Lifecycle Manager adds support for copying EBS volume tags to EBS snapshots. AWS resource tags allow customers to add metadata and apply access policies to your Amazon Elastic Block Store (Amazon EBS) resources. Starting today, customers can use Amazon Data Lifecycle Manager (DLM) to copy tags on EBS volumes to EBS snapshots. This allows customers to easily set snapshot metadata, such as access policies, to match the parent volume. Customers can enable this functionality on new or existing lifecycle policies. They can also choose to disable it at a future date.  
* feature: Endpoint Discovery: Some services provide endpoint discovery operations (e.g. 'DescribeEndpoints()'). This SDK feature, if turned on, will automatically request endpoints from services if needed and cache the endpoints returned.
* feature: MediaLive: You can now switch a live channel between preconfigured inputs. This means assigned inputs for a running channel can be changed according to a defined schedule. You can also use MP4 files as inputs.

## 2.351.0
* feature: CostExplorer: Enable Payer Accounts to View Linked Account Recommendations. Payer Accounts can specify "LINKED" as scope in the request now. In the response, there is a new filed called AccountId in ReservationPurchaseRecommendationDetail for indicating which account is this recommendation detail belongs to.
* feature: DMS: Update the DMS TestConnectionSucceeds waiter.
* feature: EC2: VM Import/Export now supports generating encrypted EBS snapshots, as well as AMIs backed by encrypted EBS snapshots during the import process.

## 2.350.0
* feature: APIGateway: AWS WAF integration with APIGW. Changes for adding webAclArn as a part of  Stage output. When the user calls a get-stage or get-stages, webAclArn will also be returned as a part of the output.
* feature: EC2: You can now launch the new Amazon EC2 memory optimized R5a and general purpose M5a instances families that feature AMD EPYC processors.
* feature: Pinpoint: This update adds the ability to send transactional email by using the SendMessage API. Transactional emails are emails that you send directly to specific email addresses. Unlike campaign-based email that you send from Amazon Pinpoint, you don't have to create segments and campaigns in order to send transactional email.
* feature: PinpointEmail: This is the first release of the Amazon Pinpoint Email API. You can use this API to configure and send transactional email from your Amazon Pinpoint account to specific email addresses. Unlike campaign-based email that you send from Amazon Pinpoint, you don't have to create segments and campaigns in order to send transactional email. 
* feature: WAFRegional: You can now use AWS WAF to configure protections for your Amazon API Gateway APIs.  This will enable you to block (or count) undesired traffic to your APIs based on the different AWS WAF rules and conditions you create. For more information about AWS WAF, see the AWS WAF Developer Guide.

## 2.349.0
* bugfix: ManagedUpload: add fix for #2304: handle situation of same part being sent twice
* feature: EKS: Adds waiters for ClusterActive and ClusterDeleted
* feature: ServerlessApplicationRepository: New AWS Serverless Application Repository APIs that support creating and reading a broader set of AWS CloudFormation templates, as well as enhancements to our existing APIs.

## 2.348.0
* feature: CloudDirectory: ListObjectParents API now supports a bool parameter IncludeAllLinksToEachParent, which if set to true, will return a ParentLinks list instead of a Parents map; BatchRead API now supports ListObjectParents operation.
* feature: Rekognition: This release updates the DetectLabels operation. Bounding boxes are now returned for certain objects, a hierarchical taxonomy is now available for labels, and you can now get the version of the detection model used for detection.

## 2.347.0
* feature: ServiceCatalog: Service Catalog integration with AWS Organizations, enables customers to more easily create and manage a portfolio of IT services across an organization. Administrators can now take advantage of the AWS account structure and account groupings configured in AWS Organizations to share Service Catalog Portfolios increasing agility and reducing risk. With this integration the admin user will leverage the trust relationship that exists within the accounts of the Organization to share portfolios to the entire Organization, a specific Organizational Unit or a specific Account.

## 2.346.0
* feature: ConfigService: With this release, AWS Config updated the ResourceType values. The updated list includes AWS Systems Manager AssociationCompliance and PatchCompliance, AWS Shield regional Protection, AWS Config ResourceCompliance, and AWS CodePipeline Pipeline.
* feature: Greengrass: Greengrass APIs now support bulk deployment operations, and APIs that list definition versions now support pagination.
* feature: MediaStoreData: The object size limit is increased from 10MB to 25MB and the content type is more permissive.

## 2.345.0
* feature: Chime: This is the initial release for the Amazon Chime AWS SDK. In this release, Amazon Chime adds support for administrative actions on users and accounts. API Documentation is also updated on https://docs.aws.amazon.com/chime/index.html
* feature: Credentials: httpsOptions for STS in SharedIniFileCredentials
* feature: DMS: Add waiters for TestConnectionSucceeds, EndpointDeleted, ReplicationInstanceAvailable, ReplicationInstanceDeleted, ReplicationTaskReady, ReplicationTaskStopped, ReplicationTaskRunning and ReplicationTaskDeleted.
* feature: RDS: This release adds the listener connection endpoint for SQL Server Always On to the list of fields returned when performing a describe-db-instances operation.

## 2.344.0
* bugfix: Core: Fixes issue where connectTimeout timers would not be cleared if a request errored out. Only affects node.js.
* feature: SSM: Compliance Severity feature release for State Manager. Users now have the ability to select compliance severity to their association in state manager console or CLI.
* feature: SageMaker: SageMaker notebook instances can now have a volume size configured.

## 2.343.0
* feature: EC2: As part of this release we are introducing EC2 On-Demand Capacity Reservations. With On-Demand Capacity Reservations, customers can reserve the exact EC2 capacity they need, and can keep it only for as long as they need it.

## 2.342.0
* feature: AlexaForBusiness: We extended the functionality of the Alexa for Business SDK, including additional support for third-party Alexa built-in devices, managing private and public skills, and conferencing setup.
* feature: CodeStar: This release lets you create projects from source code and a toolchain definition that you provide.

## 2.341.0
* feature: EC2: Provides customers the ability to Bring Your Own IP (BYOIP) prefix.  You can bring part or all of your public IPv4 address range from your on-premises network to your AWS account. You continue to own the address range, but AWS advertises it on the internet.

## 2.340.0
* feature: Inspector: Finding will be decorated with ec2 related metadata
* feature: Shield: AWS Shield Advanced API introduced a new service-specific AccessDeniedException which will be thrown when accessing individual attack information without sufficient permission.

## 2.339.0
* feature: Configuration: cache shared ini files for later use
* feature: SSM: Rate Control feature release for State Manager. Users now have the ability to apply rate control parameters similar to run command to their association in state manager console or CLI.
* feature: WorkSpaces: Added support for PowerPro and GraphicsPro WorkSpaces bundles.

## 2.338.0
* feature: AppStream: This API update adds support for creating, managing, and deleting users in the AppStream 2.0 user pool.
* feature: MediaLive: This release allows you to now turn on Quality-Defined Variable Bitrate (QVBR) encoding for your AWS Elemental MediaLive channels. You can now deliver a consistently high-quality video viewing experience while reducing overall distribution bitrates by using Quality-Defined Variable Bitrate (QVBR) encoding with AWS Elemental MediaLive. QVBR is a video compression technique that automatically adjusts output bitrates to the complexity of source content and only use the bits required to maintain a defined level of quality. This means using QVBR encoding, you can save on distribution cost, while maintaining, or increasing video quality for your viewers.
* feature: Route53: This change allows customers to disable health checks.

## 2.337.0
* bugfix: npmignore: update npmignore to exclude unit tests from npm
* feature: CloudWatchEvents: AWS Events - AWS Organizations Support in Event-Bus Policies. This release introduces a new parameter in the PutPermission API named Condition. Using the Condition parameter, customers can allow one or more AWS Organizations to access their CloudWatch Events Event-Bus resource.

## 2.336.0
* feature: Glue: New Glue APIs for creating, updating, reading and deleting Data Catalog resource-based policies.
* feature: Lightsail: Adds support for Lightsail managed databases.
* feature: ResourceGroups: AWS Resource Groups service added a new feature to filter resource groups by resource-type when using the ListGroups operation.

## 2.335.0
* feature: RDS: This release adds a new parameter to specify the DB instance or cluster parameter group for restore from DB snapshot and restore to point int time operations. For more information, see Amazon RDS Documentation.
* feature: ServiceCatalog: AWS Service Catalog enables you to reduce administrative maintenance and end-user training while adhering to compliance and security measures. With service actions, you as the administrator can enable end users to perform operational tasks, troubleshoot issues, run approved commands, or request permissions within Service Catalog. Service actions are defined using AWS Systems Manager documents, where you have access to pre-defined actions that implement AWS best practices, such asEC2 stop and reboot, as well as the ability to define custom actions.

## 2.334.0
* feature: CloudTrail: The LookupEvents API now supports two new attribute keys: ReadOnly and AccessKeyId

## 2.333.0
* feature: Athena: 1. GetQueryExecution API changes to return statementType of a submitted Athena query.  2. GetQueryResults API changes to return the number of rows added to a table when a CTAS query is executed.
* feature: DirectConnect: This release adds support for Jumbo Frames over AWS Direct Connect. You can now set MTU value when creating new virtual interfaces. This release also includes a new API to modify MTU value of existing virtual interfaces.
* feature: EC2: You can now launch the smaller-sized G3 instance called g3s.xlarge. G3s.xlarge provides 4 vCPU, 30.5 GB RAM and a NVIDIA Tesla M60 GPU. It is ideal for remote workstations, engineering and architectural applications, and 3D visualizations and rendering for visual effects.
* feature: MediaConvert: Added Paginators for all the MediaConvert list operations
* feature: TranscribeService: With this release, Amazon Transcribe now supports transcriptions from audio sources in British English (en-UK), Australian English (en-AU), and Canadian French (fr-CA).

## 2.332.0
* feature: Comprehend: This release adds French, Italian, German and Portuguese language support for all existing synchronous and asynchronous APIs
* feature: ES: Amazon Elasticsearch Service now supports customer-scheduled service software updates. When new service software becomes available, you can request an update to your domain and benefit from new features more quickly. If you take no action, we update the service software automatically after a certain time frame.
* feature: TranscribeService: With this update Amazon Transcribe now supports deleting completed transcription jobs. 

## 2.331.0
* feature: SSM: Adds StartDate, EndDate, and ScheduleTimezone to CreateMaintenanceWindow and UpdateMaintenanceWindow; Adds NextExecutionTime to GetMaintenanceWindow and DescribeMaintenanceWindows; Adds CancelMaintenanceWindowExecution, DescribeMaintenanceWindowSchedule and DescribeMaintenanceWindowsForTarget APIs.

## 2.330.0
* feature: IoTJobsDataPlane: We are releasing job execution timeout functionalities to customers. Device can now set and update their job execution timeout. 
* feature: Iot: We are releasing job execution timeout functionalities to customers. Customer now can set job execution timeout on the job level when creating a job. 

## 2.329.0
* feature: DirectoryService: SDK changes to create a new type of trust for active directory

## 2.328.0
* feature: APIGateway: Adding support for multi-value parameters in TestInvokeMethod and TestInvokeAuthorizer.
* feature: CodeBuild: Add resolved source version field in build output
* feature: SSM:  Adds RejectedPatchesAction to baseline to enable stricted validation of the rejected Patches List ; Add InstalledRejected and InstallOverrideList to compliance reporting
* feature: StorageGateway: AWS Storage Gateway now enables you to specify folders and subfolders when you update your file gateway's view of your S3 objects using the Refresh Cache API.

## 2.327.0
* feature: SageMaker: Waiter for SageMaker Batch Transform Jobs.

## 2.326.0
* feature: GuardDuty: Support optional FindingPublishingFrequency parameter in CreateDetector and UpdateDetector operations, and ClientToken on Create* operations

## 2.325.0
* bugfix: ParameterValidation: Uri parameters are now validated to ensure they contain at least 1 character. This fixes issues with S3 where passing Key with an empty string can sometimes cause a different operation to be called.
* feature: CodeStar: This release enables tagging CodeStar Projects at creation. The CreateProject API now includes optional tags parameter.
* feature: EC2: You can now use EC2 High Memory instances with 6 TiB memory (u-6tb1.metal), 9 TiB memory (u-9tb1.metal), and 12 TiB memory (u-12tb1.metal), which are ideal for running large in-memory databases, including production deployments of SAP HANA. These instances offer 448 logical processors, where each logical processor is a hyperthread on 224 cores. These instance deliver high networking throughput and lower latency with up to 25 Gbps of aggregate network bandwidth using Elastic Network Adapter (ENA)-based Enhanced Networking. These instances are EBS-Optimized by default, and support encrypted and unencrypted EBS volumes. This instance is only available in host-tenancy. You will need an EC2 Dedicated Host for this instance type to launch an instance.

## 2.324.0
* feature: APIGateway: Adding support for OpenAPI 3.0 import and export.
* feature: CodeCommit: This release adds API support for getting the contents of a file, getting the contents of a folder, and for deleting a file in an AWS CodeCommit repository.
* feature: MQ: Amazon MQ supports ActiveMQ 5.15.6, in addition to 5.15.0. Automatic minor version upgrades can be toggled. Updated the documentation.

## 2.323.0
* feature: Glue: AWS Glue now supports data encryption at rest for ETL jobs and development endpoints. With encryption enabled, when you run ETL jobs, or development endpoints, Glue will use AWS KMS keys to write encrypted data at rest. You can also encrypt the metadata stored in the Glue Data Catalog using keys that you manage with AWS KMS. Additionally, you can use AWS KMS keys to encrypt the logs generated by crawlers and ETL jobs as well as encrypt ETL job bookmarks. Encryption settings for Glue crawlers, ETL jobs, and development endpoints can be configured using the security configurations in Glue. Glue Data Catalog encryption can be enabled via the settings for the Glue Data Catalog.
* feature: OpsWorksCM: This release introduces a new API called ExportServerEngineAttribute to Opsworks-CM. You can use this API call to export engine specific attributes like the UserData script used for unattended bootstrapping of new nodes that connect to the server. 
* feature: RDS: This release includes Deletion Protection for RDS databases.

## 2.322.0
* feature: DirectoryService: API changes related to launch of cross account for Directory Service.
* feature: EC2: Add pagination support for ec2.describe-route-tables API. 

## 2.321.0
* feature: Connect: This update adds the Amazon Connect Metrics API, which lets you get current metric data and historical metric data within 24 hours for the queues in your Amazon Connect instance.
* feature: RDS:  Adds DB engine version requirements for option group option settings, and specifies if an option setting requires a value.

## 2.320.0
* feature: MediaConvert: To offer lower prices for predictable, non-urgent workloads, we propose the concept of Reserved Transcode pricing. Reserved Transcode pricing Reserved Transcoding pricing would offer the customer access to a fixed parallel processing capacity for a fixed monthly rate. This capacity would be stated in terms of number of Reserved Transcode Slots (RTSs). One RTS would be able to process one job at a time for a fixed monthly fee.

## 2.319.0
* feature: DirectoryService: Added CreateLogSubscription, DeleteLogSubscription, and ListLogSubscriptions APIs for Microsoft AD. Customers can now opt in to have Windows security event logs from the domain controllers forwarded to a log group in their account.
* feature: EC2: You can now launch f1.4xlarge, a new instance size within the existing f1 family which provides two Xilinx Virtex Field Programmable Arrays (FPGAs) for acceleration. FPGA acceleration provide additional performance and time sensitivity for specialized accelerated workloads such as clinical genomics and real-time video processing. F1.4xlarge instances are available in the US East (N. Virginia), US West (Oregon), GovCloud (US), and EU West (Dublin) AWS Regions.
* feature: RDS: This launch enables RDS start-db-cluster and stop-db-cluster. Stopping and starting Amazon Aurora clusters helps you manage costs for development and test environments. You can temporarily stop all the DB instances in your cluster, instead of setting up and tearing down all the DB instances each time that you use the cluster.

## 2.318.0
* feature: CloudWatch: Amazon CloudWatch adds the ability to request png image snapshots of metric widgets using the GetMetricWidgetImage API.
* feature: Organizations: Introducing a new exception - AccountOwnerNotVerifiedException which will be returned for InviteAccountToOrganization call for unverified accounts.
* feature: S3: S3 Cross Region Replication now allows customers to use S3 object tags to filter the scope of replication. By using S3 object tags, customers can identify individual objects for replication across AWS Regions for compliance and data protection. Cross Region Replication for S3 enables automatic and asynchronous replication of objects to another AWS Region, and with this release customers can replicate at a bucket level, prefix level or by using object tags.

## 2.317.0
* feature: ES: Amazon Elasticsearch Service adds support for node-to-node encryption for new domains running Elasticsearch version 6.0 and above
* feature: Rekognition: This release updates the Amazon Rekognition IndexFaces API operation. It introduces a QualityFilter parameter that allows you to automatically filter out detected faces that are deemed to be of low quality by Amazon Rekognition. The quality bar is based on a variety of common use cases.  You can filter low-quality detected faces by setting QualityFilter to AUTO, which is also the default setting. To index all detected faces regardless of quality, you can specify NONE.  This release also provides a MaxFaces parameter that is useful when you want to only index the most prominent and largest faces in an image and don't want to index other faces detected in the image, such as smaller faces belonging to people standing in the background.

## 2.316.0
* feature: CloudWatch: Amazon CloudWatch adds the ability to publish values and counts using PutMetricData
* feature: CodeBuild: Support build logs configuration.
* feature: EC2: Added support for customers to tag EC2 Dedicated Hosts on creation.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for additional Docker flags as Task Definition parameters. Customers can now configure their ECS Tasks to use systemControls (sysctl), pseudoTerminal (tty), and interactive (i) Docker flags.
* feature: ElastiCache: ElastiCache for Redis added support for adding and removing read-replicas from any cluster with no cluster downtime, Shard naming: ElastiCache for Redis customers have the option of allowing ElastiCache to create names for their node groups (shards) or generating their own node group names. For more information, see https:// docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/API_NodeGroupConfiguration.html, ShardsToRetain: When reducing the number of node groups (shards) in an ElastiCache for Redis (cluster mode enabled) you have the option of specifying which node groups to retain or which node groups to remove. For more information, see https:// docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/API_ModifyReplicationGroupShardConfiguration.html, ReservationARN: ReservedNode includes an ARN, ReservationARN, member which identifies the reserved node. For more information, see https:// docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/API_ReservedCacheNode.html
* feature: ElasticTranscoder: Added support for MP2 container

## 2.315.0
* feature: Polly: Amazon Polly adds Mandarin Chinese language support with new female voice - "Zhiyu"

## 2.314.0
* bugfix: ReactNative: Fixes issue where attempting to use a Blob object as input to an operation would cause a parameter validaiton error in release mode.
* feature: Connect: This update adds the Amazon Connect Update Contact Attributes API, which lets you update contact attributes for contacts in your Amazon Connect instance.
* feature: EC2: Pagination Support for DescribeNetworkInterfaces API
* feature: FMS: This update of Amazon Fire Wall Manager adds the ability to scope down the policy as well as to get all the member accounts belonging to a certain Fire Wall Manager admin account.

## 2.313.0
* feature: SSM: Session Manager is a fully managed AWS Systems Manager capability that provides interactive one-click access to Amazon EC2 Linux and Windows instances.

## 2.312.0
* feature: CloudHSMV2: With this release, we are adding 2 new APIs. DeleteBackup deletes a specified AWS CloudHSM backup. A backup can be restored up to 7 days after the DeleteBackup request. During this 7-day period, the backup will be in state PENDING_DELETION. Backups can be restored using the RestoreBackup API, which will move the backup from state PENDING_DELETION back to ACTIVE.
* feature: Redshift: Adding support to Redshift to change the encryption type after cluster creation completes.

## 2.311.0
* feature: CloudWatchLogs: * Adding a log prefix parameter for filter log events API and minor updates to the documentation
* feature: ConfigService: Adding a new field "createdBy" to the ConfigRule data model. The field is populated only if the rule is service linked i.e the rule is created by a service. The field is empty for normal rules created by customer.

## 2.310.0
* feature: APIGateway: Add support for Active X-Ray with API Gateway
* feature: CodeCommit: This release adds additional optional fields to the pull request APIs.
* feature: MediaConvert: This release adds support for Cost Allocation through tagging and also enables adding, editing, and removal of tags from the MediaConvert console.

## 2.309.0
* feature: AppStream: Added support for enabling persistent application settings for a stack. When these settings are enabled, changes that users make to applications and Windows settings are automatically saved after each session and applied to the next session.
* feature: DynamoDB: New feature for Amazon DynamoDB.
* feature: ELB: Documentation update for DescribeAccountLimits API to include classic-registered-instances.
* feature: S3: Parquet input format support added for the SelectObjectContent API

## 2.308.0
* feature: Rekognition: This release introduces a new API called DescribeCollection to Amazon Rekognition. You can use DescribeCollection to get information about an existing face collection. Given the ID for a face collection, DescribeCollection returns the following information: the number of faces indexed into the collection, the version of the face detection model used by the collection, the Amazon Resource Name (ARN) of the collection and the creation date/time of the collection.

## 2.307.0
* feature: EKS: Amazon EKS DescribeCluster API returns a platformVersion attribute which allows you to identify the features that are currently enabled for your clusters. The Amazon EKS platform version represents capabilities of the cluster control plane, such as which Kubernetes API server flags are enabled, as well as the current Kubernetes patch version. 
* feature: WAF: This change includes support for the WAF FullLogging feature through which Customers will have access to all the logs of requests that are inspected by a WAF WebACL. The new APIs allow Customers to manage association of a WebACL with one or more supported "LogDestination" and redact any request fields from the logs. 
* feature: WAFRegional: This change includes support for the WAF FullLogging feature through which Customers will have access to all the logs of requests that are inspected by a WAF WebACL. The new APIs allow Customers to manage association of a WebACL with one or more supported "LogDestination" and redact any request fields from the logs. 

## 2.306.0
* feature: CodeBuild: Support multiple sources and artifacts for CodeBuild projects. 
* feature: SageMaker: VolumeKmsKeyId now available in Batch Transform Job 

## 2.305.0
* feature: CORS: add cors support for pricing API. Make Pricing client available by default in browsers SDK.
* feature: Glue: AWS Glue now supports data encryption at rest for ETL jobs and development endpoints. With encryption enabled, when you run ETL jobs, or development endpoints, Glue will use AWS KMS keys to write encrypted data at rest. You can also encrypt the metadata stored in the Glue Data Catalog using keys that you manage with AWS KMS. Additionally, you can use AWS KMS keys to encrypt the logs generated by crawlers and ETL jobs as well as encrypt ETL job bookmarks. Encryption settings for Glue crawlers, ETL jobs, and development endpoints can be configured using the security configurations in Glue. Glue Data Catalog encryption can be enabled via the settings for the Glue Data Catalog.
* feature: MediaPackage: MediaPackage now provides input redundancy. Channels have two ingest endpoints that can receive input from encoders. OriginEndpoints pick one of the inputs receiving content for playback and automatically switch to the other input if the active input stops receiving content. Refer to the User Guide (https://docs.aws.amazon.com/mediapackage/latest/ug/what-is.html) for more details on this feature.
* feature: Monitoring: Inactive code for future SDK instrumentation and telemetry.
* feature: SageMakerRuntime: SageMaker Runtime supports CustomAttributes header which allows customers provide additional information in a request for an inference submitted to a model or in the response about the inference returned by a model hosted at an Amazon SageMaker endpoint.

## 2.304.0
* feature: Glue: New Glue APIs for creating, updating, reading and deleting Data Catalog resource-based policies.
* feature: XRay: Support for new APIs that enable management of sampling rules.

## 2.303.0
* feature: IoTAnalytics: Added new listDatasetContent API that shows you the list of dataset contents for the corresponding versions
* feature: Iot: This release adds support to create a Stream and Code signing for Amazon FreeRTOS job along with Over-the-air updates.
* feature: Signer: AWS Signer is a new feature that allows Amazon FreeRTOS (AFR) Over The Air (OTA) customers to cryptographically sign code using code-signing certificates managed by AWS Certificate Manager. 

## 2.302.0
* feature: Glue: AWS Glue now supports data encryption at rest for ETL jobs and development endpoints. With encryption enabled, when you run ETL jobs, or development endpoints, Glue will use AWS KMS keys to write encrypted data at rest. You can also encrypt the metadata stored in the Glue Data Catalog using keys that you manage with AWS KMS. Additionally, you can use AWS KMS keys to encrypt the logs generated by crawlers and ETL jobs as well as encrypt ETL job bookmarks. Encryption settings for Glue crawlers, ETL jobs, and development endpoints can be configured using the security configurations in Glue. Glue Data Catalog encryption can be enabled via the settings for the Glue Data Catalog.

## 2.301.0
* feature: CloudWatchEvents: Added Fargate and NetworkConfiguration support to EcsParameters.
* feature: CognitoIdentityServiceProvider: Amazon Cognito now has API support for creating custom domains for our hosted UI for User Pools.

## 2.300.0
* feature: IoTAnalytics: AWS IoT Analytics announces three new features:  (1) Bring Your Custom Container - import your custom authored code containers. (2) Automate Container Execution - lets you automate the execution of containers hosting custom authored analytical code or Jupyter Notebooks to perform continuous analysis. (3) Incremental Data Capture with Customizable Time Windows - enables users to perform analysis on new incremental data captured since the last analysis.
* feature: Iot: This release adds support for IoT Thing Group Indexing and Searching functionality.
* feature: LexModelBuildingService: Amazon Lex builds bot in two stages. After the first it sets status to READY_BASIC_TESTING. In this state the bot will match user inputs that exactly match the utterances configured for the bot's intents and values in the slot types. 
* feature: MediaLive: Adds two APIs for working with Channel Schedules: BatchUpdateSchedule and DescribeSchedule. These APIs allow scheduling actions for SCTE-35 message insertion and for static image overlays.
* feature: Rekognition: This release introduces a new API called DescribeCollection to Amazon Rekognition.  You can use DescribeCollection to get information about an existing face collection. Given the ID for a face collection, DescribeCollection returns the following information: the number of faces indexed into the collection, the version of the face detection model used by the collection, the Amazon Resource Name (ARN) of the collection and the creation date/time of the collection.

## 2.299.0
* feature: Snowball: Snowball job states allow customers to track the status of the Snowball job. We are launching a new Snowball job state "WithSortingFacility"!  When customer returns the Snowball to AWS, the device first goes to a sorting facility before it reaches an AWS data center.  Many customers have requested us to add a new state to reflect the presence of the device at the sorting facility for better tracking. Today when a customer returns  the Snowball, the state first changes from "InTransitToAWS" to "WithAWS". With the addition of new state, the device will move from "InTransitToAWS" to "WithAWSSortingFacility", and then to "WithAWS".  There are no other changes to the API at this time besides adding this new state.

## 2.298.0
* feature: EC2: Added support for T3 Instance type in EC2. To learn more about T3 instances, please see https://aws.amazon.com/ec2/instance-types/t3/
* feature: ElasticBeanstalk: Elastic Beanstalk adds the "Privileged" field to the "CPUUtilization" type, to support enhanced health reporting in Windows environments.
* feature: RDS: Adds a paginator for the DescribeDBClusters operation.

## 2.297.0
* bugfix: S3: Fixes issue when making cross-region S3 calls where the object key is truncated if the key prefix matched the bucket name and path style addressing is not used.
* feature: DynamoDB: Added SSESpecification block to update-table command which allows users to modify table Server-Side Encryption. Added two new fields (SSEType and KMSMasterKeyId) to SSESpecification block used by create-table and update-table commands. Added new SSEDescription Status value UPDATING.
* feature: MediaConvert: This release fixes backward-incompatible changes from a previous release. That previous release changed non-required job settings to required, which prevented jobs and job templates from merging correctly. The current change removes validation of required settings from the SDK and instead centralizes the validation in the service API. For information on required settings, see the Resources chapter of the AWS Elemental MediaConvert API Reference https://docs.aws.amazon.com/mediaconvert/latest/apireference/resources.html

## 2.296.0
* feature: DAX: DAX CreateClusterRequest is updated to include IamRoleArn as a required request parameter. 
* feature: SageMaker: Added an optional boolean parameter, 'DisassociateLifecycleConfig', to the UpdateNotebookInstance operation. When set to true, the lifecycle configuration associated with the notebook instance will be removed, allowing a new one to be set via a new 'LifecycleConfigName' parameter.

## 2.295.0
* feature: Discovery: The Application Discovery Service's Continuous Export APIs allow you to analyze your on-premises server inventory data, including system performance and network dependencies, in Amazon Athena.
* feature: EC2: The 'Attribute' parameter DescribeVolumeAttribute request has been marked as required - the API has always required this parameter, but up until now this wasn't reflected appropriately in the SDK.
* feature: MediaConvert: Added WriteSegmentTimelineInRepresentation option for Dash Outputs
* feature: Redshift: You can now resize your Amazon Redshift cluster quickly. With the new ResizeCluster action, your cluster is available for read and write operations within minutes
* feature: SSM: AWS Systems Manager Inventory now supports groups to quickly see a count of which managed instances are and arent configured to collect one or more Inventory types

## 2.294.0
* feature: DeviceFarm: Support for running tests in a custom environment with live logs/video streaming, full test features parity and reduction in overall test execution time.

## 2.293.0
* feature: AutoScaling: Add batch operations for creating/updating and deleting scheduled scaling actions.
* feature: CloudFront: Lambda@Edge Now Provides You Access to the Request Body for HTTP POST/PUT Processing. With this feature, you can now offload more origin logic to the edge and improve end-user latency. Developers typically use Web/HTML forms or Web Beacons/Bugs as a mechanism to collect data from the end users and then process that data at their origins servers. For example, if you are collecting end user behavior data through a web beacon on your website, you can use this feature to access the user behavior data and directly log it to an Amazon Kinesis Firehose endpoint from the Lambda function, thereby simplifying your origin infrastructure.
* feature: ES: Amazon Elasticsearch Service adds support for no downtime, in-place upgrade for Elasticsearch version 5.1 and above.

## 2.292.0
* feature: SageMaker: SageMaker updated the default endpoint URL to support Private Link via the CLI/SDK.

## 2.291.0
* feature: MediaConvert: This release adds support for a new rate control mode, Quality-Defined Variable Bitrate (QVBR) encoding, includes updates to optimize transcoding performance, and resolves previously reported bugs.

## 2.290.0
* feature: DAX: Add the SSESpecification field to CreateCluster to allow creation of clusters with server-side encryption, and add the SSEDescription field to DescribeClusters to display the status of server-side encryption for a cluster. 
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for Docker volumes and Docker volume drivers. Customers can now configure their ECS Tasks to use Docker volumes, enabling stateful and storage-intensive applications to be deployed on ECS.
* feature: RDS: Launch RDS Aurora Serverless

## 2.289.0
* feature: SSM: AWS Systems Manager Automation is launching two new features for Automation Execution Rate Control based on tags and customized parameter maps. With the first feature, customer can target their resources by specifying a Tag with Key/Value. With the second feature, Parameter maps rate control, customers can benefit from customization of input parameters.
* feature: SecretsManager: This release introduces a ForceDeleteWithoutRecovery parameter to the DeleteSecret API enabling customers to force the deletion of a secret without any recovery window

## 2.288.0
* feature: CloudWatchLogs: Documentation Update
* feature: CodeBuild: Release semantic versioning feature for CodeBuild
* feature: EC2: Amazon VPC Flow Logs adds support for delivering flow logs directly to S3
* feature: Pinpoint: This release includes a new batch API call for Amazon Pinpoint which can be used to update endpoints and submit events. This call will accept events from clients such as mobile devices and AWS SDKs. This call will accept requests which has multiple endpoints and multiple events attached to those endpoints in a single call. This call will update the endpoints attached and will ingest events for those endpoints. The response from this call will be a multipart response per endpoint/per event submitted.
* feature: SSM: Two new filters ExecutionStage and DocumentName will be added to ListCommands so that customers will have more approaches to query their commands.

## 2.287.0
* bugfix: Typings: Updates typings-generator to remove unused model types.
* feature: DynamoDB:  Amazon DynamoDB Point-in-time recovery (PITR) provides continuous backups of your table data. DynamoDB now supports the ability to self-restore a deleted PITR enabled table. Now, when a table with PITR enabled is deleted, a system backup is automatically created and retained for 35 days (at no additional cost). System backups allow you to restore the deleted PITR enabled table to the state it was just before the point of deletion. For more information, see the Amazon DynamoDB Developer Guide.
* feature: Health: Updates the ARN structure vended by AWS Health API. All ARNs will now include the service and type code of the associated event, as vended by DescribeEventTypes.

## 2.286.2
* bugfix: type: remove undefined exceptions from SubscribeToShardEventStream

## 2.286.1
* bugfix: react-native: Fixes issue where promise methods are undefined when using react-native 0.56.0. See [this issue](https://github.com/facebook/metro/issues/208) for more information.
* feature: Kinesis: Updates API to latest version.
* feature: Polly: Amazon Polly enables female voice Aditi to speak Hindi language
* feature: ResourceGroups: AWS Resource Groups service added a new feature to filter group resources by resource-type when using the ListGroupResources operation.
* feature: SSM: This release updates AWS Systems Manager APIs to let customers create and use service-linked roles to register and edit Maintenance Window tasks.

## 2.285.1
* feature: StorageGateway: AWS Storage Gateway now enables you to create stored volumes with AWS KMS support.
* feature: TranscribeService: With this update Amazon Transcribe now supports channel identification. It transcribes audio from separate channels and combines them into a single transcription. 

## 2.284.1
* feature: Connect: This update includes the new User Management APIs and the Federation API used for SAML authentication. The User Management APIs let you create and manage users in your Amazon Connect instance programmatically. The Federation API enables authentication between AWS and your existing identity provider using tokens.
* feature: ES: Amazon Elasticsearch Service adds support for enabling Elasticsearch error logs, providing you valuable information for troubleshooting your Elasticsearch domains quickly and easily. These logs are published to the Amazon CloudWatch Logs service and can be turned on or off at will.
* feature: Iot: As part of this release we are introducing a new IoT security service, AWS IoT Device Defender, and extending capability of AWS IoT to support Step Functions rule action. The AWS IoT Device Defender is a fully managed service that helps you secure your fleet of IoT devices. For more details on this new service, go to https://aws.amazon.com/iot-device-defender. The Step Functions rule action lets you start an execution of AWS Step Functions state machine from a rule.
* feature: KMS: Added a KeyID parameter to the ListAliases operation. This parameter allows users to list only the aliases that refer to a particular AWS KMS customer master key. All other functionality remains intact.
* feature: MediaConvert: Fixes an issue with modeled timestamps being labeled with the incorrect format.

## 2.283.1
* feature: CloudHSMV2: This update  to the AWS CloudHSM API adds copy-backup-to-region, which allows you to copy a backup of a cluster from one region to another. The copied backup can be used in the destination region to create a new AWS CloudHSM cluster as a clone of the original cluster. 
* feature: DirectConnect: 1. awsDeviceV2 field is introduced for Connection/Lag/Interconnect/VirtualInterface/Bgp Objects, while deprecating the awsDevice field for Connection/Lag/Interconnect Objects. 2. region field is introduced for VirtualInterface/Location objects 
* feature: Glue: Glue Development Endpoints now support association of multiple SSH public keys with a development endpoint.
* feature: Iot: get rid of documentParameters field from CreateJob API
* feature: MQ: Modified the CreateBroker, UpdateBroker, and DescribeBroker operations to support integration with Amazon CloudWatch Logs. Added a field to indicate the IP address(es) that correspond to wire-level endpoints of broker instances. While a single-instance broker has one IP address, an active/standby broker for high availability has 2 IP addresses. Added fields to indicate the time when resources were created. Updated documentation for Amazon MQ.
* feature: SageMaker: Added SecondaryStatusTransitions to DescribeTrainingJob to provide more visibility into SageMaker training job progress and lifecycle.

## 2.282.1
* feature: CodeBuild: Add artifacts encryptionDisabled and build encryptionKey.
* feature: EC2: This change provides the EC2/Spot customers with two new allocation strategies -- LowestN for Spot instances, and OD priority for on-demand instances.
* feature: Inspector: inspector will return ServiceTemporarilyUnavailableException when service is under stress
* feature: Redshift: When we make a new version of Amazon Redshift available, we update your cluster during its maintenance window. By selecting a maintenance track, you control whether we update your cluster with the most recent approved release, or with the previous release. The two values for maintenance track are current and trailing. If you choose the current track, your cluster is updated with the latest approved release. If you choose the trailing track, your cluster is updated with the release that was approved previously.The new API operation for managing maintenance tracks for a cluster is DescribeClusterTracks. In addition, the following API operations have new MaintenanceTrackName parameters:  Cluster,  PendingModifiedValues,  ModifyCluster,  RestoreFromClusterSnapshot,  CreateCluster,  Snapshot
* feature: SSM: This release updates AWS Systems Manager APIs to allow customers to attach labels to history parameter records and reference history parameter records via labels.  It also adds Parameter Store integration with AWS Secrets Manager to allow referencing and retrieving AWS Secrets Manager's secrets from Parameter Store.

## 2.281.1
* feature: EC2: R5 is the successor to R4 in EC2's memory-optimized instance family. R5d is a variant of R5 that has local NVMe SSD. Z1d instances deliver both high compute and high memory. Z1d instances use custom Intel Xeon Scalable Processors running at up to 4.0 GHz, powered by sustained all-core Turbo Boost. They are available in 6 sizes, with up to 48 vCPUs, 384 GiB of memory, and 1.8 TB of local NVMe storage.
* feature: ECS: This release of Amazon Elastic Container Service (Amazon ECS) introduces support for private registry authentication using AWS Secrets Manager. With private registry authentication, private Docker images can be used in a task definition.
* feature: ELBv2: We are introducing two new actions in Application Load Balancer. Redirects and Fixed Response. These features will allow you to improve user experience and security posture. By using redirect actions in your Application Load Balancer, you can improve the security of your user requests and by using fixed-response, you can enhance the customer experience by displaying branded error pages during application maintenance or outages.

## 2.280.1
* bugfix: Serialization: fix timestamp serialization issue in querystring; Update the logic of formatting the timestamp;
* feature: CORS: make Translate service available in browser version of SDK by default
* feature: DynamoDB: With this SDK update, APIs UpdateGlobalTableSettings and DescribeGlobalTableSettings now allow consistently configuring AutoScaling settings for a DynamoDB global table. Previously, they would only allow consistently setting IOPS. Now new APIs are being released, existing APIs are being extended.

## 2.279.1
* feature: ConfigService: Setting internal length limits on resourceId for APIs.  

## 2.278.1
* feature: MediaPackage: Adds support for DASH OriginEnpoints with multiple media presentation description periods triggered by presence of SCTE-35 ad markers in Channel input streams.

## 2.277.1
* feature: IoTAnalytics: This change allows publishing of channel/datastore size as part of the describe-channel/describe-datastore APIs. We introduce an optional boolean parameter 'includeStatistics' in the Describe request. If the user sets this parameter to true, the describe response will return the resource size and timestamp at which the size was recorded. If the parameter is set to false, the size won't be computed or returned.
* feature: serviceId: add service id to all current clients. It will be used as unique identifier for service clients

## 2.276.1
* bugfix: TypeScript: Updates waitFor methods to accept $waiter configuration in parameter fields.
* bugfix: Typings: Fixes incorrect typings for AWS.EventListeners. Renamed CORE field to Core.
* feature: CORS: KinesisVideo and KinesisVideoArchivedMedia support CORS. This change make the services available in browser version of SDK by default
* feature: Comprehend: This release gives customers the ability to tokenize (find word boundaries) text and for each word provide a label for the part of speech, using the DetectSyntax operation. This API is useful to analyze text for specific conditions like for example finding nouns and the correlating adjectives to understand customer feedback. 
* feature: Polly: Amazon Polly adds new API for asynchronous synthesis to S3
* feature: SageMaker: Amazon SageMaker has added the capability for customers to run fully-managed, high-throughput batch transform machine learning models with a simple API call. Batch Transform is ideal for high-throughput workloads and predictions in non-real-time scenarios where data is accumulated over a period of time for offline processing.
* feature: Snowball: AWS Snowball Edge announces the availability of Amazon EC2 compute instances that run on the device. AWS Snowball Edge is a 100-TB ruggedized device built to transfer data into and out of AWS with optional support for local Lambda-based compute functions. With this feature, developers and administrators can run their EC2-based applications on the device providing them with an end to end vertically integrated AWS experience. Designed for data pre-processing, compression, machine learning, and data collection applications, these new instances, called SBE1 instances, feature 1.8 GHz Intel Xeon D processors up to 16 vCPUs, and 32 GB of memory. The SBE1 instance type is available in four sizes and multiple instances can be run on the device at the same time. Customers can now run compute instances using the same Amazon Machine Images (AMIs) that are used in Amazon EC2.

## 2.275.1
* feature: AppStream: This API update adds support for sharing AppStream images across AWS accounts within the same region.
* feature: KinesisVideo: Adds support for HLS video playback of Kinesis Video streams using the KinesisVideo client by including "GET_HLS_STREAMING_SESSION_URL" as an additional APIName parameter in the GetDataEndpoint input.
* feature: KinesisVideoArchivedMedia: Adds support for HLS video playback of Kinesis Video streams by providing the GetHLSStreamingSessionURL function in the KinesisVideoArchivedMedia client.

## 2.274.1
* feature: AppSync: This release adds support for configuring HTTP  endpoints as data sources for your AWS AppSync GraphQL API.
* feature: CodeBuild: Update CodeBuild CreateProject API - serviceRole is a required input 
* feature: DLM: Amazon Data Lifecycle Manager (DLM) for EBS Snapshots provides a simple, automated way to back up data stored on Amazon EBS volumes. You can define backup and retention schedules for EBS snapshots by creating lifecycle policies based on tags. With this feature, you no longer have to rely on custom scripts to create and manage your backups. This feature is now available in the US East (N. Virginia), US West (Oregon), and Europe (Ireland) AWS regions at no additional cost.
* feature: EFS: Amazon EFS now allows you to instantly provision the throughput required for your applications independent of the amount of data stored in your file system, allowing you to optimize throughput for your applications performance needs. Starting today, you can provision the throughput your applications require quickly with a few simple steps using AWS Console, AWS CLI or AWS API to achieve consistent performance.
* feature: IAM: SDK release to support IAM delegated administrator feature. The feature lets customers attach permissions boundary to IAM principals. The IAM principals cannot operate exceeding the permission specified in permissions boundary.

## 2.273.1
* feature: APIGateway: Support for fine grain throttling for API gateway. 
* feature: CostExplorer: Starting today, you can access custom Reserved Instance (RI) purchase recommendations for your Amazon Redshift, Amazon ElastiCache, and Amazon Elasticsearch reservations via AWS Cost Explorer API, in addition to accessing RI purchase recommendations for your Amazon EC2 and Amazon RDS reservations.
* feature: S3: S3 Select support for BZIP2 compressed input files
* feature: SSM: Support Conditional Branching OnFailure for SSM Automation

## 2.272.1
* feature: AppStream: This API update adds pagination to the DescribeImages API to support future features and enhancements.
* feature: CodeBuild: API changes to CodeBuild service, support report build status for Github sources
* feature: EC2: Support CpuOptions field in Launch Template data and allow Launch Template name to contain hyphen.
* feature: Glue: AWS Glue adds the ability to crawl DynamoDB tables.

## 2.271.1
* feature: ApplicationAutoScaling: The release adds support for custom resource auto scaling.
* feature: CostExplorer: AWS Cost Explorer provides you with Reserved Instance (RI) purchase recommendations based on your total cross-account Amazon EC2 and Amazon RDS usage. Starting today, linked accounts can also access custom RI purchase recommendations for specific linked accounts directly via AWS Cost Explorer API.
* feature: DMS: Added support for DmsTransfer endpoint type and support for re-validate option in table reload API.
* feature: Lambda: Add support for .NET Core 2.1 to Lambda.
* feature: TranscribeService: You can now specify an Amazon S3 output bucket to store the transcription of your audio file when you call the StartTranscriptionJob operation. 

## 2.270.1
* feature: MediaConvert: This release adds support for the following 1) users can specify tags to be attached to queues, presets, and templates during creation of those resources on MediaConvert. 2) users can now view the count of jobs in submitted state and in progressing state on a per queue basis.
* feature: ServerlessApplicationRepository: Added required fields and documentation updates for AWS Serverless Application Repository.

## 2.269.1
* bugfix: browser: Fixed an issue with the browser XML parser logic where the incorrect value may be returned if a complex shape (map, structure) had an immediate child and a nested descendant with the same tag name.
* feature: CORS: The SecretsManager service supports CORS. This change adds the service to the browser version of the SDK by default.
* feature: Pinpoint: This release of the Amazon Pinpoint SDK adds the ability to create complex segments and validate phone numbers for SMS messages. It also adds the ability to get or delete endpoints based on user IDs, remove attributes from endpoints, and list the defined channels for an app.
* feature: SageMaker: Amazon SageMaker NotebookInstances supports 'Updating' as a NotebookInstanceStatus.  In addition, DescribeEndpointOutput now includes Docker repository digest of deployed Model images.

## 2.268.1
* feature: ACM: Adds a "CertificateValidated" waiter to AWS Certificate Manager clients, which polls on a new certificate's validation state.
* feature: EC2: Added support for customers to tag EC2 Dedicated Hosts
* feature: Redshift: Feature 1 - On-demand cluster release version - When Amazon Redshift releases a new cluster version, you can choose to upgrade to that version immediately instead of waiting until your next maintenance window. You can also choose to roll back to a previous version. The two new APIs added for managing cluster release version are - ModifyClusterDbRevision, DescribeClusterDbRevisions. Feature 2 - Upgradeable reserved instance - You can now exchange one Reserved Instance for a new Reserved Instance with no changes to the terms of your existing Reserved Instance (term, payment type, or number of nodes). The two new APIs added for managing these upgrades are - AcceptReservedNodeExchange, GetReservedNodeExchangeOfferings. 

## 2.267.1
* feature: SSM: Execution History and StartAssociationOnce release for State Manager. Users now have the ability to view association execution history with DescribeAssociationExecutions and DescribeAssociationExecutionTargets. Users can also execute an association by calling StartAssociationOnce.

## 2.266.1
* feature: ElasticBeanstalk: Elastic Beanstalk adds "Suspended" health status to the EnvironmentHealthStatus enum type and updates document.
* feature: Lambda: Support for SQS as an event source.
* feature: StorageGateway: AWS Storage Gateway now enables you to use Server Message Block (SMB) protocol  to store and access objects in Amazon Simple Storage Service (S3). 

## 2.265.1
* feature: CloudFront: Unpublish delete-service-linked-role API.
* feature: CodePipeline: UpdatePipeline may now throw a LimitExceededException when adding or updating Source Actions that use periodic checks for change detection
* feature: Comprehend: This release gives customers the option to batch process a set of documents stored within an S3 bucket in addition to the existing synchronous nature of the current Comprehend API.

## 2.264.1
* feature: Inspector: Introduce four new APIs to view and preview Exclusions.  Exclusions show which intended security checks are excluded from an assessment, along with reasons and recommendations to fix.  The APIs are CreateExclusionsPreview, GetExclusionsPreview, ListExclusions, and DescribeExclusions.
* feature: S3: Add AllowQuotedRecordDelimiter to Amazon S3 Select API. Please refer to https://docs.aws.amazon.com/AmazonS3/latest/API/RESTObjectSELECTContent.html for usage details.
* feature: SecretsManager: This release adds support for resource-based policies that attach directly to your secrets. These policies provide an additional way to control who can access your secrets and what they can do with them. For more information, see https://docs.aws.amazon.com/secretsmanager/latest/userguide/auth-and-access_resource-based-policies.html in the Secrets Manager User Guide.

## 2.263.1
* feature: AlexaForBusiness:  Introduce DeviceNotRegisteredException for AWSMoneypenny
* feature: AppStream: This API update enables customers to find their VPC private IP address and ENI ID associated with AppStream streaming sessions.

## 2.262.1
* feature: CloudDirectory: SDK release to support Flexible Schema initiative being carried out by Amazon Cloud Directory. This feature lets customers using new capabilities like: variant typed attributes, dynamic facets and AWS managed Cloud Directory schemas.

## 2.261.1
* feature: Macie: Amazon Macie is a security service that uses machine learning to automatically discover, classify, and protect sensitive data in AWS. With this release, we are launching the following Macie HTTPS API operations: AssociateMemberAccount, AssociateS3Resources, DisassociateMemberAccount, DisassociateS3Resources, ListMemberAccounts, ListS3Resources, and UpdateS3Resources. With these API operations you can issue HTTPS requests directly to the service.
* feature: Neptune: Deprecates the PubliclyAccessible parameter that is not supported by Amazon Neptune.
* feature: SSM: Adds Amazon Linux 2 support to Patch Manager

## 2.260.1
* feature: ACMPCA: CA Restore is a new feature within AWS Certificate Manager Private Certificate Authority (ACM PCA) that allows you to restore a private certificate authority that has been deleted. When you issue the DeleteCertificateAuthority call, you can now specify the number of days (7-30, with 30 being the default) in which the private certificate authority will remain in the DELETED state. During this time, the private certificate authority can be restored with the RestoreCertificateAuthority API call and then be returned to the PENDING_CERTIFICATE or DISABLED state, depending upon the state prior to deletion.  Summary of API Changes: 1). Added RestoreCertificateAuthority API call; 2). Added optional PermanentDeletionTimeInDays parameter to DeleteCertificateAuthority API call. If this parameter is not specified, the DeleteCertificateAuthority API call will use a 30 day restore period as default.
* feature: MediaLive: AWS Elemental MediaLive now makes Reserved Outputs and Inputs available through the AWS Management Console and API. You can reserve outputs and inputs with a 12 month commitment in exchange for discounted hourly rates. Pricing is available at https://aws.amazon.com/medialive/pricing/
* feature: RDS: This release adds a new parameter to specify the retention period for Performance Insights data for RDS instances. You can either choose 7 days (default) or 731 days. For more information, see Amazon RDS Documentation.

## 2.259.1
* bugfix: S3: Fixes edge case where event message lengths were sometimes incorrectly calculated.
* feature: MediaConvert: This release adds language code support according to the ISO-639-3 standard. Custom 3-character language codes are now supported on input and output for both audio and captions.

## 2.258.1
* bugfix: Core: Updates SDK to attempt to determine the Content-Length of a payload when an operation uses the unsigned-body trait. Content-Length will still not be calculated for non-file streams. This will allow file streams to be passed to MediaStoreData.putObject.
* feature: APIGateway: Support for PRIVATE endpoint configuration type
* feature: DynamoDB: Added two new fields SSEType and KMSMasterKeyArn to SSEDescription block in describe-table output.
* feature: IoTAnalytics: With this release, AWS IoT Analytics allows you to tag resources. Tags are metadata that you can create and use to manage your IoT Analytics resources. For more information about tagging, see AWS Tagging Strategies. For technical documentation, look for the tagging operations in the AWS IoT Analytics API reference or User Guide.

## 2.257.1
* feature: SSM: Added support for new parameter, CloudWatchOutputConfig, for SendCommand API. Users can now have RunCommand output sent to CloudWatchLogs.
* feature: ServiceCatalog: Introduced new length limitations for few of the product fields.

## 2.256.1
* feature: DeviceFarm: Adding VPCEndpoint support for Remote access. Allows customers to be able to access their private endpoints/services running in their VPC during remote access.
* feature: ECS: Introduces daemon scheduling capability to deploy one task per instance on selected instances in a cluster.  Adds a "force" flag to the DeleteService API to delete a service without requiring to scale down the number of tasks to zero.
* feature: S3: Adds support for S3 Select.

## 2.255.1
* feature: CloudDirectory: Amazon Cloud Directory now supports optional attributes on Typed Links, giving users the ability to associate and manage data on Typed Links. 
* feature: StorageGateway:  AWS Storage Gateway now enables you to create cached volumes and tapes with AWS KMS support.

## 2.254.1
* feature: MediaTailor: Fixes a bug in the request URIs for MediaTailor PlaybackConfiguration operations.

## 2.253.1
* feature: MediaLive: AWS Elemental MediaLive now makes channel log information available through Amazon CloudWatch Logs. You can set up each MediaLive channel with a logging level; when the channel is run, logs will automatically be published to your account on Amazon CloudWatch Logs

## 2.252.1
* feature: CostExplorer: Cost Explorer API is providing programmatic access to RI saving metrics to enable customers to optimize their reservations.
* feature: Polly: Amazon Polly adds new French voice - "Lea"
* feature: RDS: This release adds customizable processor features for RDS instances.
* feature: Shield: DDoS Response Team access management for AWS Shield

## 2.251.1
* feature: AppStream: Amazon AppStream 2.0 adds support for Google Drive for G Suite. With this feature, customers will be able to connect their G Suite accounts with AppStream 2.0 and enable Google Drive access for an AppStream 2.0 stack. Users of the stack can then link their Google Drive using their G Suite login credentials and use their existing files stored in Drive with their AppStream 2.0 applications. File changes will be synced automatically to Google cloud. 
* feature: EC2: You are now able to use instance storage (up to 3600 GB of NVMe based SSD) on M5 instances, the next generation of EC2's General Purpose instances in us-east-1, us-west-2, us-east-2, eu-west-1 and ca-central-1. M5 instances offer up to 96 vCPUs, 384 GiB of DDR4 instance memory, 25 Gbps in Network bandwidth and improved EBS and Networking bandwidth on smaller instance sizes and provide a balance of compute, memory and network resources for many applications.
* feature: EKS: Amazon Elastic Container Service for Kubernetes (Amazon EKS) is a fully managed service that makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS. Amazon EKS runs the Kubernetes control plane for you across multiple AWS availability zones to eliminate a single point of failure. Amazon EKS is certified Kubernetes conformant so you can use existing tooling and plugins from partners and the Kubernetes community. Applications running on any standard Kubernetes environment are fully compatible and can be easily migrated to Amazon EKS. 
* feature: MediaConvert: This release adds the support for Common Media Application Format (CMAF) fragmented outputs, RF64 WAV audio output format, and HEV1 or HEVC1 MP4 packaging types when using HEVC in DASH or CMAF outputs.
* feature: SageMaker: Amazon SageMaker has added the ability to run hyperparameter tuning jobs. A hyperparameter tuning job will create and evaluate multiple training jobs while tuning algorithm hyperparameters, to optimize a customer specified objective metric.

## 2.250.1
* feature: DirectoryService: Added ResetUserPassword API. Customers can now reset their users' passwords without providing the old passwords in Simple AD and Microsoft AD.
* feature: Iot: We are releasing force CancelJob and CancelJobExecution functionalities to customers.
* feature: MediaTailor: AWS Elemental MediaTailor is a personalization and monetization service that allows scalable server-side ad insertion. The service enables you to serve targeted ads to viewers while maintaining broadcast quality in over-the-top (OTT) video applications. This SDK allows user access to the AWS Elemental MediaTailor configuration interface.
* feature: SNS: The SNS Subscribe API has been updated with two new optional parameters: Attributes and ReturnSubscriptionArn. Attributes is a map of subscription attributes which can be one or more of: FilterPolicy, DeliveryPolicy, and RawMessageDelivery. ReturnSubscriptionArn is a boolean parameter that overrides the default behavior of returning "pending confirmation" for subscriptions that require confirmation instead of returning the subscription ARN.

## 2.249.1
* feature: ELBv2: This release of Elastic Load Balancing introduces user authentication on Application Load Balancer.
* feature: Neptune: Amazon Neptune is a fast, reliable graph database service that makes it easy to build and run applications that work with highly connected datasets. Neptune supports popular graph models Property Graph and W3C's Resource Description Frame (RDF), and their respective query languages Apache TinkerPop Gremlin 3.3.2 and SPARQL 1.1. 

## 2.248.1
* feature: PI: Performance Insights is a feature of Amazon Relational Database Service (RDS) that helps you quickly assess the load on your database, and determine when and where to take action. You can use the SDK to retrieve Performance Insights data and integrate your monitoring solutions.

## 2.247.1
* feature: AppStream: This API update enables customers to control whether users can transfer data between their local devices and their streaming applications through file uploads and downloads, clipboard operations, or printing to local devices
* feature: ConfigService: AWS Config adds support for retention period, allowing you to specify a retention period for your AWS Config configuration items.
* feature: Glue: AWS Glue now sends a delay notification to Amazon CloudWatch Events when an ETL job runs longer than the specified delay notification threshold.
* feature: Iot: We are exposing DELETION_IN_PROGRESS as a new job status in regards to the release of DeleteJob API.

## 2.246.1
* feature: CodeBuild: AWS CodeBuild Adds Support for Windows Builds.
* feature: RDS: This release adds CloudWatch Logs integration capabilities to RDS Aurora MySQL clusters

## 2.245.1
* feature: ECS: Amazon Elastic Container Service (ECS) adds service discovery for services that use host or bridged network mode. ECS can now also register instance IPs for active tasks using bridged and host networking with Route 53, making them available via DNS.
* feature: Inspector: We are launching the ability to target all EC2 instances. With this launch, resourceGroupArn is now optional for CreateAssessmentTarget and UpdateAssessmentTarget. If resourceGroupArn is not specified, all EC2 instances in the account in the AWS region are included in the assessment target.

## 2.244.1
* feature: CloudFormation: 1) Filtered Update for StackSet based on Accounts and Regions: This feature will allow flexibility for the customers to roll out updates on a StackSet based on specific Accounts and Regions.   2) Support for customized ExecutionRoleName: This feature will allow customers to attach ExecutionRoleName to the StackSet thus ensuring more security and controlling the behavior of any AWS resources in the target accounts.

## 2.243.1
* feature: Iot: We are releasing DeleteJob and DeleteJobExecution APIs to allow customer to delete resources created using AWS IoT Jobs.

## 2.242.1
* feature: CognitoIdentityServiceProvider: Amazon Cognito User Pools now supports federation for users to sign up and sign in with any identity provider following the OpenID Connect standard. Amazon Cognito User Pools now returns the User Pool's Amazon Resource Name (ARN) from the CreateUserPool, UpdateUserPool, and DescribeUserPool APIs.
* feature: EC2: You are now able to use instance storage (up to 1800 GB of NVMe based SSD) on C5 instances, the next generation of EC2's compute optimized instances in us-east-1, us-west-2, us-east-2, eu-west-1 and ca-central-1. C5 instances offer up to 72 vCPUs, 144 GiB of DDR4 instance memory, 25 Gbps in Network bandwidth and improved EBS and Networking bandwidth on smaller instance sizes to deliver improved performance for compute-intensive workloads.You can now run bare metal workloads on EC2 with i3.metal instances. As a new instance size belonging to the I3 instance family, i3.metal instances have the same characteristics as other instances in the family, including NVMe SSD-backed instance storage optimized for low latency, very high random I/O performance, and high sequential read throughput. I3.metal instances are powered by 2.3 GHz Intel Xeon processors, offering 36 hyper-threaded cores (72 logical processors), 512 GiB of memory, and 15.2 TB of NVMe SSD-backed instance storage. These instances deliver high networking throughput and lower latency with up to 25 Gbps of aggregate network bandwidth using Elastic Network Adapter (ENA)-based Enhanced Networking.

## 2.241.1
* feature: ServiceCatalog: Users can now pass a new option to ListAcceptedPortfolioShares called portfolio-share-type with a value of AWS_SERVICECATALOG in order to access Getting Started Portfolios that contain selected products representing common customer use cases.

## 2.240.1
* feature: ConfigService: Update ResourceType enum with values for XRay resource

## 2.239.1
* feature: CodeBuild: Adding support for more override fields for StartBuild API, add support for idempotency token field  for StartBuild API in AWS CodeBuild.
* feature: IoT1ClickDevicesService: AWS IoT 1-Click makes it easy for customers to incorporate simple ready-to-use IoT devices into their workflows. These devices can trigger AWS Lambda functions that implement business logic. In order to build applications using AWS IoT 1-Click devices, programmers can use the AWS IoT 1-Click Devices API and the AWS IoT 1-Click Projects API. Learn more at https://aws.amazon.com/documentation/iot-1-click/
* feature: IoT1ClickProjects: AWS IoT 1-Click makes it easy for customers to incorporate simple ready-to-use IoT devices into their workflows. These devices can trigger AWS Lambda functions that implement business logic. In order to build applications using AWS IoT 1-Click devices, programmers can use the AWS IoT 1-Click Devices API and the AWS IoT 1-Click Projects API. Learn more at https://aws.amazon.com/documentation/iot-1-click/.
* feature: XML: Replaces XMLBuilder dependency with a light-weight XML builder.

## 2.238.1
* feature: Firehose: With this release, Amazon Kinesis Data Firehose can convert the format of your input data from JSON to Apache Parquet or Apache ORC before storing the data in Amazon S3. Parquet and ORC are columnar data formats that save space and enable faster queries compared to row-oriented formats like JSON.

## 2.237.1
* feature: GameLift: AutoScaling Target Tracking scaling simplification along with StartFleetActions and StopFleetActions APIs to suspend and resume automatic scaling at will.

## 2.236.1
* feature: Budgets: Updating the regex for the NumericValue fields.
* feature: EC2: Enable support for latest flag with Get Console Output
* feature: RDS: Changes to support the Aurora MySQL Backtrack feature.

## 2.235.1
* feature: EC2: Enable support for specifying CPU options during instance launch.

## 2.234.1
* feature: AlexaForBusiness: This release adds the new Device status "DEREGISTERED". This release also adds DEVICE_STATUS as the new DeviceEventType.
* feature: Budgets: "With this release, customers can use AWS Budgets to monitor how much of their Amazon EC2, Amazon RDS, Amazon Redshift, and Amazon ElastiCache instance usage is covered by reservations, and receive alerts when their coverage falls below the threshold they define."
* feature: ES: This change brings support for Reserved Instances to AWS Elasticsearch.
* feature: S3: Added BytesReturned details for Progress and Stats Events for Amazon S3 Select . 

## 2.233.1
* feature: GuardDuty: Amazon GuardDuty is adding five new API operations for creating and managing filters. For each filter, you can specify a criteria and an action. The action you specify is applied to findings that match the specified criteria.

## 2.232.1
* feature: AppSync: This release adds support for authorizing your AWS AppSync endpoint with an OpenID Connect compliant service and also to configure your AWS AppSync endpoint to log requests to Amazon CloudWatch Logs.
* feature: CodeBuild: CodeBuild now supports CORS. The CodeBuild service is now included in the default browser version of the SDK.
* feature: ConfigService: Update ResourceType enum with values for Lambda, ElasticBeanstalk, WAF and ElasticLoadBalancing resources

## 2.231.1
* feature: CodePipeline: Added support for webhooks with accompanying definitions as needed in the AWS CodePipeline API Guide.
* feature: EC2: Amazon EC2 Fleet is a new feature that simplifies the provisioning of Amazon EC2 capacity across different EC2 instance types, Availability Zones, and the On-Demand, Reserved Instance, and Spot Instance purchase models. With a single API call, you can now provision capacity to achieve desired scale, performance, and cost.
* feature: SSM: Added support for new parameter, DocumentVersion, for SendCommand API. Users can now specify version of SSM document to be executed on the target(s).

## 2.230.1
* feature: AlexaForBusiness: Adds ListDeviceEvents API to get a paginated list of device events (such as ConnectionStatus). This release also adds ConnectionStatus field to GetDevice and SearchDevices API.
* feature: DynamoDB: Adds two new APIs UpdateGlobalTableSettings and DescribeGlobalTableSettings. This update introduces new constraints in the CreateGlobalTable and UpdateGlobalTable APIs . Tables must have the same write capacity units. If Global Secondary Indexes exist then they must have the same write capacity units and key schema.
* feature: GuardDuty: You can disable the email notification when inviting GuardDuty members using the disableEmailNotification parameter in the InviteMembers operation.
* feature: Route53Domains: This release adds a SubmittedSince attribute to the ListOperations API, so you can list operations that were submitted after a specified date and time.
* feature: SageMaker: SageMaker has added support for VPC configuration for both Endpoints and Training Jobs. This allows you to connect from the instances running the Endpoint or Training Job to your VPC and any resources reachable in the VPC rather than being restricted to resources that were internet accessible.
* feature: WorkSpaces: Added new IP Access Control APIs, an API to change the state of a Workspace, and the ADMIN_MAINTENANCE WorkSpace state. With the new IP Access Control APIs, you can now create/delete IP Access Control Groups, add/delete/update rules for IP Access Control Groups, Associate/Disassociate IP Access Control Groups to/from a WorkSpaces Directory, and Describe IP Based Access Control Groups.

## 2.229.1
* feature: CodeDeploy: AWS CodeDeploy has a new exception that indicates when a GitHub token is not valid.
* feature: XRay: Added PutEncryptionConfig and GetEncryptionConfig APIs for managing data encryption settings. Use PutEncryptionConfig to configure X-Ray to use an AWS Key Management Service customer master key to encrypt trace data at rest.

## 2.228.1
* feature: ElasticBeanstalk: Support tracking Elastic Beanstalk resources in AWS Config.

## 2.227.1
* feature: AutoScalingPlans: The release adds the operation UpdateScalingPlan for updating a scaling plan and the support for tag filters as an application source.
* feature: IoTAnalytics: Introducing AWS IoT Analytics SDK. AWS IoT Analytics provides advanced data analysis for AWS IoT. It allows you to collect large amounts of device data, process messages, store them, and then query the data and run sophisticated analytics to make accurate decisions in your IoT applications and machine learning use cases. AWS IoT Analytics enables advanced data exploration through integration with Jupyter Notebooks and data visualization through integration with Amazon QuickSight.
* feature: Iot: Add IotAnalyticsAction which sends message data to an AWS IoT Analytics channel

## 2.226.1
* feature: Firehose: With this release, Amazon Kinesis Data Firehose allows you to tag your delivery streams. Tags are metadata that you can create and use to manage your delivery streams. For more information about tagging, see AWS Tagging Strategies. For technical documentation, look for the tagging operations in the Amazon Kinesis Firehose API reference.
* feature: MediaLive: With AWS Elemental MediaLive you can now output live channels as RTMP (Real-Time Messaging Protocol) and RTMPS as the encrypted version of the protocol (Secure, over SSL/TLS). RTMP is the preferred protocol for sending live streams to popular social platforms which  means you can send live channel content to social and sharing platforms in a secure and reliable way while continuing to stream to your own website, app or network.

## 2.225.1
* feature: CodePipeline: Added new SourceRevision structure to Execution Summary with accompanying definitions as needed in the AWS CodePipeline API Guide.
* feature: CostExplorer: Starting today, you can identify opportunities for Amazon RDS cost savings using AWS Cost Explorer's API to access your Amazon RDS Reserved Instance Purchase Recommendations
* feature: DeviceFarm: Adding support for VPCEndpoint feature. Allows customers to be able to access their private endpoints/services running in their VPC during test automation.
* feature: EC2: Added support for customers to see the time at which a Dedicated Host was allocated or released.
* feature: RDS: The ModifyDBCluster operation now includes an EngineVersion parameter. You can use this to upgrade the engine for a clustered database.
* feature: SSM: Added new APIs DeleteInventory and DescribeInventoryDeletions, for customers to delete their custom inventory data.

## 2.224.1
* feature: DMS: Native Change Data Capture start point and task recovery support in Database Migration Service.  
* feature: Glue: "AWS Glue now supports timeout values for ETL jobs. With this release, all new ETL jobs have a default timeout value of 48 hours. AWS Glue also now supports the ability to start a schedule or job events trigger when it is created."
* feature: MediaPackage: Adds a new OriginEndpoint package type CmafPackage in MediaPackage. Origin endpoints can now be configured to use the Common Media Application Format (CMAF) media streaming format. This version of CmafPackage only supports HTTP Live Streaming (HLS) manifests with fragmented MP4.
* feature: SSM: Added TooManyUpdates exception for AddTagsToResource and RemoveTagsFromResource API
* feature: WorkMail: Amazon WorkMail adds the ability to grant users and groups with "Full Access", "Send As" and "Send on Behalf" permissions on a given mailbox.

## 2.223.1
* feature: CloudDirectory: Cloud Directory customers can fetch attributes within a facet on an object with the new GetObjectAttributes API and can fetch attributes from multiple facets or objects with the BatchGetObjectAttributes operation.

## 2.222.1
* feature: Batch: Support for Timeout in SubmitJob and RegisterJobDefinition

## 2.221.1
* feature: ACM: AWS Certificate Manager has added support for AWS Certificate Manager Private Certificate Authority (CA). Customers can now request private certificates with the RequestCertificate API, and also export private certificates with the ExportCertificate API.
* feature: ACMPCA: AWS Certificate Manager (ACM) Private Certificate Authority (CA) is a managed private CA service that helps you easily and securely manage the lifecycle of your private certificates. ACM Private CA provides you a highly-available private CA service without the upfront investment and ongoing maintenance costs of operating your own private CA. ACM Private CA extends ACM's certificate management capabilities to private certificates, enabling you to manage public and private certificates centrally.
* feature: CloudWatch: The new GetMetricData API enables you to collect batch amounts of metric data and optionally perform math expressions on the data. With one GetMetricData call you can retrieve as many as 100 different metrics and a total of 100,800 data points.
* feature: ConfigService: AWS Config introduces multi-account multi-region data aggregation features. Customers can create an aggregator (a new resource type) in AWS Config that collects AWS Config data from multiple source accounts and regions into an aggregator account. Customers can aggregate data from individual account(s) or an organization and multiple regions. In this release, AWS Config adds several API's for multi-account multi-region data aggregation.
* feature: FMS: This release is the initial release version for AWS Firewall Manager, a new AWS service that makes it easy for customers to centrally configure WAF rules across all their resources (ALBs and CloudFront distributions) and across accounts.
* feature: S3: ONEZONE_IA storage class stores object data in only one Availability Zone at a lower price than STANDARD_IA. This SDK release provides API support for this new storage class.
* feature: SageMaker: SageMaker is now supporting many additional instance types in previously supported families for Notebooks, Training Jobs, and Endpoints. Training Jobs and Endpoints now support instances in the m5 family in addition to the previously supported instance families. For specific instance types supported please see the documentation for the SageMaker API.
* feature: SecretsManager: AWS Secrets Manager enables you to easily create and manage the secrets that you use in your customer-facing apps.  Instead of embedding credentials into your source code, you can dynamically query Secrets Manager from your app whenever you need credentials.  You can automatically and frequently rotate your secrets without having to deploy updates to your apps.  All secret values are encrypted when they're at rest with AWS KMS, and while they're in transit with HTTPS and TLS.
* feature: TranscribeService: Amazon Transcribe is an automatic speech recognition (ASR) service that makes it easy for developers to add speech to text capability to their applications. 

## 2.220.1
* feature: DeviceFarm: Added Private Device Management feature. Customers can now manage their private devices efficiently - view their status, set labels and apply profiles on them. Customers can also schedule automated tests and remote access sessions on individual instances in their private device fleet.
* feature: Lambda: added nodejs8.10 as a valid runtime
* feature: Translate: This release increases the maximum size of input text to 5,000 bytes. Amazon Translate now supports automatic language detection of the input text. The translation models have been improved to increase accuracy. See the documentation for more information.

## 2.219.1
* feature: APIGateway: Amazon API Gateway now supports resource policies for APIs making it easier to set access controls for invoking APIs.
* feature: CloudFront: You can now use a new Amazon CloudFront capability called Field-Level Encryption to further enhance the security of sensitive data, such as credit card numbers or personally identifiable information (PII) like social security numbers. CloudFront's field-level encryption further encrypts sensitive data in an HTTPS form using field-specific encryption keys (which you supply) before a POST request is forwarded to your origin. This ensures that sensitive data can only be decrypted and viewed by certain components or services in your application stack. Field-level encryption is easy to setup. Simply configure the fields that have to be further encrypted by CloudFront using the public keys you specify and you can reduce attack surface for your sensitive data.
* feature: ES: This adds Amazon Cognito authentication support to Kibana.

## 2.218.1
* feature: Connect: Amazon Connect is a contact center as a service (CCaS) solution that offers easy, self-service configuration and enables dynamic, personal, and natural customer engagement at any scale. With this release of the Amazon Connect SDK, Outbound APIs (StartOutboundVoiceContact, StopContact) are now generally available. This release supports CTR generation for calls generated through the new APIs. Additionally IAM permissions are supported for the new APIs. 

## 2.217.1
* bugfix: DocumentClient: Fixes a bug with the minified version of the browser SDK where sending Sets of data with the DynamoDB DocumentClient would cause an error to be returned from the service.
* feature: AlexaForBusiness: Adds operations for creating and managing address books of phone contacts for use in A4B managed shared devices.
* feature: CloudFormation: Enabling resource level permission control for StackSets APIs. Adding support for customers to use customized AdministrationRole to create security boundaries between different users.
* feature: Greengrass: Greengrass APIs now support creating Machine Learning resource types and configuring binary data as the input payload for Greengrass Lambda functions.
* feature: SSM: This Patch Manager release supports creating patch baselines for CentOS.

## 2.216.1
* feature: IAM: Add support for Longer Role Sessions. Four APIs manage max session duration: GetRole, ListRoles, CreateRole, and the new API UpdateRole. The max session duration integer attribute is measured in seconds.
* feature: MTurk: Added a new attribute "ActionsGuarded" to QualificationRequirement: This update allows MTurk Requester customers using the AWS SDK to control which Workers can see and preview their HITs. We now support hiding HITs from unqualified Workers' search results.
* feature: STS: Change utilizes the Max Session Duration attribute introduced for IAM Roles and allows STS customers to request session duration up to the Max Session Duration of 12 hours from AssumeRole based APIs.

## 2.215.1
* feature: ACM: AWS Certificate Manager has added support for customers to disable Certificate Transparency logging on a per-certificate basis.

## 2.214.1
* feature: DynamoDB: Point-in-time recovery (PITR) provides continuous backups of your DynamoDB table data. With PITR, you do not have to worry about creating, maintaining, or scheduling backups. You enable PITR on your table and your backup is available for restore at any point in time from the moment you enable it, up to a maximum of the 35 preceding days. PITR provides continuous backups until you explicitly disable it. For more information, see the Amazon DynamoDB Developer Guide.

## 2.213.1
* feature: AppStream: Feedback URL allows admins to provide a feedback link or a survey link for collecting user feedback while streaming sessions. When a feedback link is provided, streaming users will see a "Send Feedback" choice in their streaming session toolbar. On selecting this choice, user will be redirected to the link provided in a new browser tab. If a feedback link is not provided, users will not see the "Send Feedback" option. 
* feature: CodeBuild: Adding support for branch filtering when using webhooks with AWS CodeBuild. 
* feature: ECS: Amazon Elastic Container Service (ECS) now includes integrated Service Discovery using Route 53 Auto Naming. Customers can now specify a Route 53 Auto Naming service as part of an ECS service. ECS will register task IPs with Route 53, making them available via DNS in your VPC.

## 2.212.1
* feature: CloudWatchEvents: Added SQS FIFO queue target support
* feature: ConfigService: AWS Config adds support for BatchGetResourceConfig API, allowing you to batch-retrieve the current state of one or more of your resources.
* feature: CostExplorer: This launch will allow customers to access their Amazon EC2 Reserved Instance (RI) purchase recommendations programmatically via the AWS Cost Explorer API. 
* feature: ECS: Amazon ECS users can now mount a temporary volume in memory in containers and specify the shared memory that a container can use through the use of docker's 'tmpfs' and 'shm-size' features respectively. These fields can be specified under linuxParameters in ContainerDefinition in the Task Definition Template.
* feature: Glue: API Updates for DevEndpoint: PublicKey is now optional for CreateDevEndpoint. The new DevEndpoint field PrivateAddress will be populated for DevEndpoints associated with a VPC.
* feature: MediaLive: AWS Elemental MediaLive has added support for updating Inputs and Input Security Groups. You can update Input Security Groups at any time and it will update all channels using that Input Security Group. Inputs can be updated as long as they are not attached to a currently running channel.

## 2.211.1
* bugfix: dependency: Pins ieee754 to 1.1.8 to avoid timestamp issue reported in issue #1977

## 2.211.0
* feature: ElasticBeanstalk: AWS Elastic Beanstalk is launching a new public API named DescribeAccountAttributes which allows customers to access account level attributes. In this release, the API will support quotas for resources such as applications, application versions, and environments.

## 2.210.0
* feature: Organizations: This release adds additional reason codes to improve clarity to exceptions that can occur.
* feature: Pinpoint: With this release, you can delete endpoints from your Amazon Pinpoint projects. Customers can now specify one of their leased dedicated long or short codes to send text messages.
* feature: SageMaker: This release provides support for ml.p3.xlarge instance types for notebook instances.  Lifecycle configuration is now available to customize your notebook instances on start; the configuration can be reused between multiple notebooks.  If a notebook instance is attached to a VPC you can now opt out of internet access that by default is provided by SageMaker.

## 2.209.0
* feature: ServiceDiscovery: This release adds support for custom health checks, which let you check the health of resources that aren't accessible over the internet. For example, you can use a custom health check when the instance is in an Amazon VPC.

## 2.208.0
* feature: CloudHSMV2: CreateCluster can now take both 8 and 17 character Subnet IDs. DeleteHsm can now take both 8 and 17 character ENI IDs.
* feature: Iot: We added new fields to the response of the following APIs. (1) describe-certificate: added new generationId, customerVersion fields (2) describe-ca-certificate: added new generationId, customerVersion and lastModifiedDate fields (3) get-policy: added generationId, creationDate and lastModifiedDate fields
* feature: Redshift: DescribeClusterSnapshotsMessage with ClusterExists flag returns snapshots of existing clusters. Else both existing and deleted cluster snapshots are returned

## 2.207.0
* feature: ECS: Amazon Elastic Container Service (ECS) now supports container health checks. Customers can now specify a docker container health check command and parameters in their task definition. ECS will monitor, report and take scheduling action based on the health status.
* feature: MigrationHub: Unused key LABEL removed from ResourceAttrbute
* feature: Pinpoint: With this release, you can export endpoints from your Amazon Pinpoint projects. You can export a) all of the endpoints assigned to a project or b) the subset of endpoints assigned to a segment.

## 2.206.0
* feature: MediaLive: Updates API to model required traits and minimum/maximum constraints.

## 2.205.0
* feature: CloudWatchEvents: Added BatchParameters to the PutTargets API
* feature: EC2: Added support for modifying Placement Group association of instances via ModifyInstancePlacement API.
* feature: SSM: This Inventory release supports the status message details reported by the last sync for the resource data sync API.
* feature: ServiceCatalog: This release of ServiceCatalog adds the DeleteTagOption API.
* feature: StorageGateway: AWS Storage Gateway (File) support for two new file share attributes are added.           1. Users can specify the S3 Canned ACL to use for new objects created in the file share.         2. Users can create file shares for requester-pays buckets.

## 2.204.0
* feature: ApplicationAutoScaling: Application Auto Scaling now supports automatic scaling of SageMaker Production Variants on an Endpoint.

## 2.203.0
* feature: Route53: Added support for creating LBR rules using ap-northeast-3 region.

## 2.202.0
* feature: AppStream: This API update is to enable customers to copy their Amazon AppStream 2.0 images within and between AWS Regions

## 2.201.0
* feature: CostExplorer: Added GetReservationCoverage API for retrieving reservation coverage information.

## 2.200.0
* feature: CodeCommit: This release adds an API for adding a file directly to an AWS CodeCommit repository without requiring a Git client.
* feature: EC2: Adds support for tagging an EBS snapshot as part of the API call that creates the EBS snapshot
* feature: ServerlessApplicationRepository: Added support for delete-application API and the ability for developers to set a homepage for their application. The homepage is a URL with more information about the application, for example the location of your GitHub repository for the application. 

## 2.199.0
* feature: AutoScaling: Amazon EC2 Auto Scaling support for service-linked roles
* feature: WAF: The new PermissionPolicy APIs in AWS WAF Regional allow customers to attach resource-based policies to their entities.
* feature: WAFRegional: The new PermissionPolicy APIs in AWS WAF Regional allow customers to attach resource-based policies to their entities.

## 2.198.0
* feature: ConfigService: With this release, AWS Config updated the ConfigurationItemStatus enum values. The values prior to this update did not represent appropriate values returned by GetResourceConfigHistory. You must update your code to enumerate the new enum values so this is a breaking change.  To map old properties to new properties, use the following descriptions: New discovered resource - Old property: Discovered, New property: ResourceDiscovered. Updated resource - Old property: Ok, New property: OK. Deleted resource - Old property: Deleted, New property: ResourceDeleted or ResourceDeletedNotRecorded. Not-recorded resource - Old property: N/A, New property: ResourceNotRecorded or ResourceDeletedNotRecorded.

## 2.197.0
* feature: RDS: Updates RDS API to indicate whether a DBEngine supports read replicas.

## 2.196.0
* feature: GameLift: Updates to allow Fleets to run on On-Demand or Spot instances.
* feature: MediaConvert: Nielsen ID3 tags can now be inserted into transport stream (TS) and HLS outputs. For more information on Nielsen configuration you can go to https://docs.aws.amazon.com/mediaconvert/latest/apireference/jobs.html#jobs-nielsenconfiguration

## 2.195.0
* feature: AppSync: AWS AppSync now supports for None Data Source, CreateApiKey now supports setting expiration on API keys, new API UpdateApiKey supports updating expiration on API keys. 
* feature: LexModelBuildingService: Amazon Lex now provides the ability to export and import your Amazon Lex chatbot definition as a JSON file.

## 2.194.0
* feature: Route53: Added support for creating Private Hosted Zones and metric-based healthchecks in the ap-northeast-3 region for whitelisted customers.

## 2.193.0
* feature: CognitoIdentityServiceProvider: Support for user migration using AWS Lambda trigger. Support to obtain signing certificate for user pools.
* feature: EC2: Network interfaces now supply the following additional status of "associated" to better distinguish the current status.
* feature: GuardDuty: Added PortProbeAction information to the Action section of the port probe-type finding.
* feature: KMS: This release of AWS Key Management Service includes support for InvalidArnException in the RetireGrant API.

## 2.192.0
* feature: EC2: Users can now better understand the longer ID opt-in status of their account using the two new APIs DescribeAggregateIdFormat and DescribePrincipalIdFormat
* feature: LexModelBuildingService: You can now define a response for your Amazon Lex chatbot directly from the AWS console. A response consists of messages dynamically selected from a group of pre-defined messages, populated by the developer.
* feature: LexRuntime: You can now define a response for your Amazon Lex chatbot directly from the AWS console. A response consists of messages dynamically selected from a group of pre-defined messages, populated by the developer.

## 2.191.0
* feature: AppStream: Adds support for allowing customers to provide a redirect URL for a stack. Users will be redirected to the link provided by the admin at the end of their streaming session. 
* feature: Budgets: Making budgetLimit and timePeriod optional, and updating budgets docs. 
* feature: DMS: This release includes the addition of two new APIs: describe replication instance task logs and reboot instance. The first allows user to see how much storage each log for a task on a given instance is occupying. The second gives users the option to reboot the application software on the instance and force a fail over for MAZ instances to test robustness of their integration with our service. 
* feature: DirectoryService: Updated the regex of some input parameters to support longer EC2 identifiers.
* feature: DynamoDB: Amazon DynamoDB now supports server-side encryption using a default service key (alias/aws/dynamodb) from the AWS Key Management Service (KMS). AWS KMS is a service that combines secure, highly available hardware and software to provide a key management system scaled for the cloud. AWS KMS is used via the AWS Management Console or APIs to centrally create encryption keys, define the policies that control how keys can be used, and audit key usage to prove they are being used correctly. For more information, see the Amazon DynamoDB Developer Guide.
* feature: GameLift: Amazon GameLift FlexMatch added the StartMatchBackfill API.  This API allows developers to add new players to an existing game session using the same matchmaking rules and player data that were used to initially create the session.
* feature: MediaLive: AWS Elemental MediaLive has added support for updating channel settings for idle channels. You can now update channel name, channel outputs and output destinations, encoder settings, user role ARN, and input specifications. Channel settings can be updated in the console or with API calls. Please note that running channels need to be stopped before they can be updated. We've also deprecated the 'Reserved' field.
* feature: MediaStore: AWS Elemental MediaStore now supports per-container CORS configuration.

## 2.190.0
* feature: Glue: This new feature will now allow customers to add a customized json classifier. They can specify a json path to indicate the object, array or field of the json documents they'd like crawlers to inspect when they crawl json files. 
* feature: SSM: This Patch Manager release supports configuring Linux repos as part of patch baselines, controlling updates of non-OS security packages and also creating patch baselines for SUSE12
* feature: ServiceCatalog: This release of Service Catalog adds SearchProvisionedProducts API and ProvisionedProductPlan APIs.
* feature: ServiceDiscovery: This release adds support for registering CNAME record types and creating Route 53 alias records that route traffic to Amazon Elastic Load Balancers using Amazon Route 53 Auto Naming APIs.

## 2.189.0
* feature: Kinesis: Using ListShards a Kinesis Data Streams customer or client can get information about shards in a data stream (including meta-data for each shard) without obtaining data stream level information.
* feature: OpsWorks: AWS OpsWorks Stacks supports EBS encryption and HDD volume types. Also, a new DescribeOperatingSystems API is available, which lists all operating systems supported by OpsWorks Stacks.

## 2.188.0
* feature: DeviceFarm: Add InteractionMode in CreateRemoteAccessSession for DirectDeviceAccess feature.
* feature: MediaLive: Add InputSpecification to CreateChannel (specification of input attributes is used for channel sizing and affects pricing);  add NotFoundException to DeleteInputSecurityGroups.

## 2.187.0
* feature: AlexaForBusiness: Supports new field for DeviceStatusInfo which provides details about the DeviceStatus following a DeviceSync operation.
* feature: CodeBuild: Adding support for Shallow Clone and GitHub Enterprise in AWS CodeBuild.
* feature: GuardDuty: Added the missing AccessKeyDetails object to the resource shape.
* feature: Lambda: AWS Lambda now supports Revision ID on your function versions and aliases, to track and apply conditional updates when you are updating your function version or alias resources.
* feature: MetadataService: Allow environmental disabling of the AWS.MetadataService client by setting the AWS_EC2_METADATA_DISABLED environment variable to a truthy value.

## 2.186.0
* feature: Budgets: Add additional costTypes: IncludeDiscount, UseAmortized,  to support finer control for different charges included in a cost budget.

## 2.185.0
* feature: Glue: New AWS Glue DataCatalog APIs to manage table versions and a new feature to skip archiving of the old table version when updating table.
* feature: TranscribeService: Amazon Transcribe Public Preview Release

## 2.184.0
* feature: SageMaker: CreateTrainingJob and CreateEndpointConfig now supports KMS Key for volume encryption. 

## 2.183.0
* feature: ApplicationAutoScaling: Application Auto Scaling is adding support for Target Tracking Scaling for ECS services.
* feature: AutoScalingPlans: AWS Auto Scaling enables you to quickly discover all of the scalable resources underlying your application and set up application scaling in minutes using built-in scaling recommendations.
* feature: RDS: With this release you can now integrate RDS DB instances with CloudWatch Logs. We have added parameters to the operations for creating and modifying DB instances (for example CreateDBInstance) to allow you to take advantage of this capability through the CLI and API. Once you enable this feature, a stream of log events will publish to CloudWatch Logs for each log type you enable.

## 2.182.0
* feature: Lambda: Support for creating Lambda Functions using 'dotnetcore2.0' and 'go1.x'. 

## 2.181.0
* feature: Glue: Support is added to generate ETL scripts in Scala which can now be run by  AWS Glue ETL jobs. In addition, the trigger API now supports firing when any conditions are met (in addition to all conditions). Also, jobs can be triggered based on a "failed" or "stopped" job run (in addition to a "succeeded" job run). 

## 2.180.0
* feature: ELB: Added OperationNotPermittedException to indicate that you cannot create a classic load balancer while deleting the Elastic Load Balancing service-linked role.
* feature: ELBv2: Added OperationNotPermittedException to indicate that you cannot create a load balancer while deleting the Elastic Load Balancing service-linked role.
* feature: RDS: Read Replicas for Amazon RDS for MySQL, MariaDB, and PostgreSQL now support Multi-AZ deployments.Amazon RDS Read Replicas enable you to create one or more read-only copies of your database instance within the same AWS Region or in a different AWS Region. Updates made to the source database are asynchronously copied to the Read Replicas. In addition to providing scalability for read-heavy workloads, you can choose to promote a Read Replica to become standalone a DB instance when needed.Amazon RDS Multi-AZ Deployments provide enhanced availability for database instances within a single AWS Region. With Multi-AZ, your data is synchronously replicated to a standby in a different Availability Zone (AZ). In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby, minimizing disruption to your applications.You can now combine Read Replicas with Multi-AZ as part of a disaster recovery strategy for your production databases. A well-designed and tested plan is critical for maintaining business continuity after a disaster. Since Read Replicas can also be created in different regions than the source database, your Read Replica can be promoted to become the new production database in case of a regional disruption.You can also combine Read Replicas with Multi-AZ for your database engine upgrade process. You can create a Read Replica of your production database instance and upgrade it to a new database engine version. When the upgrade is complete, you can stop applications, promote the Read Replica to a standalone database instance and switch over your applications. Since the database instance is already a Multi-AZ deployment, no additional steps are needed.For more information, see the Amazon RDS User Guide.

## 2.179.0
* feature: DirectoryService: On October 24 we introduced AWS Directory Service for Microsoft Active Directory (Standard Edition), also known as AWS Microsoft AD (Standard Edition), which is a managed Microsoft Active Directory (AD) that is optimized for small and midsize businesses (SMBs). With this SDK release, you can now create an AWS Microsoft AD directory using API. This enables you to run typical SMB workloads using a cost-effective, highly available, and managed Microsoft AD in the AWS Cloud.

## 2.178.0
* feature: CodeDeploy: The AWS CodeDeploy API was updated to support DeleteGitHubAccountToken, a new method that deletes a GitHub account connection.
* feature: Route53: This release adds an exception to the CreateTrafficPolicyVersion API operation.

## 2.177.0
* feature: Inspector: Added 2 new attributes to the DescribeAssessmentTemplate response, indicating the total number of assessment runs and last assessment run ARN (if present.)

## 2.176.0
* feature: WorkSpaces: Modify WorkSpaces have been updated with flexible storage and switching of hardware bundles feature. The following configurations have been added to ModifyWorkSpacesProperties: storage and compute. This update provides the capability to configure the storage of a WorkSpace. It also adds the capability of switching hardware bundle of a WorkSpace by specifying an eligible compute (Value, Standard, Performance, Power).

## 2.175.0
* feature: EC2: This release fixes an issue with tags not showing in DescribeAddresses responses.
* feature: ECS: Amazon ECS users can now set a health check initialization wait period of their ECS services, the services that are associated with an Elastic Load Balancer (ELB) will wait for a period of time before the ELB become healthy. You can now configure this in Create and Update Service.
* feature: Inspector: PreviewAgents API now returns additional fields within the AgentPreview data type. The API now shows the agent health and availability status for all instances included in the assessment target. This allows users to check the health status of Inspector Agents before running an assessment. In addition, it shows the instance ID, hostname, and IP address of the targeted instances.
* feature: SageMaker: SageMaker Models no longer support SupplementalContainers.  API's that have been affected are CreateModel and DescribeModel.

## 2.174.0
* feature: CodeBuild: Adding support allowing AWS CodeBuild customers to select specific curated image versions.
* feature: EC2: Elastic IP tagging enables you to add key and value metadata to your Elastic IPs so that you can search, filter, and organize them according to your organization's needs.
* feature: KinesisAnalytics: Kinesis Analytics now supports AWS Lambda functions as output.

## 2.173.0
* feature: ConfigService: Update ResourceType enum with values for WAF, WAFRegional, and CloudFront resources
* feature: Iot: This release adds support for code signed Over-the-air update functionality for Amazon FreeRTOS. Users can now create and schedule Over-the-air updates to their Amazon FreeRTOS devices using these new APIs. 

## 2.172.0
* feature: APIGateway: API Gateway now adds support for calling API with compressed payloads using one of the supported content codings, tagging an API stage for cost allocation, and returning API keys from a custom authorizer for use with a usage plan.
* feature: Route53: Route 53 added support for a new China (Ningxia) region, cn-northwest-1. You can now specify cn-northwest-1 as the region for latency-based or geoproximity routing. Route 53 also added support for a new EU (Paris) region, eu-west-3. You can now associate VPCs in eu-west-3 with private hosted zones and create alias records that route traffic to resources in eu-west-3.

## 2.171.0
* feature: AppStream: This API update is to enable customers to add tags to their Amazon AppStream 2.0 resources

## 2.170.0
* feature: APIGateway: Adds support for Cognito Authorizer scopes at the API method level.

## 2.169.0
* feature: WorkMail: Today, Amazon WorkMail released an administrative SDK and enabled AWS CloudTrail integration. With the administrative SDK, you can natively integrate WorkMail with your existing services. The SDK enables programmatic user, resource, and group management through API calls. This means your existing IT tools and workflows can now automate WorkMail management, and third party applications can streamline WorkMail migrations and account actions. 

## 2.168.0
* feature: CognitoIdentityServiceProvider: Exposing the hosted UI domain name for a user pool that has a domain configured.
* feature: LexModelBuildingService: The GetBotChannelAssociation API now returns the status and failure reason, if any, for a bot channel.
* feature: SageMaker: CreateModel API Update:  The request parameter 'ExecutionRoleArn' has changed from optional to required.

## 2.167.0
* feature: AppStream: This API update is to support the feature that allows customers to automatically consume the latest Amazon AppStream 2.0 agent as and when published by AWS.
* feature: CloudWatch: With this launch, you can now create a CloudWatch alarm that alerts you when M out of N datapoints of a metric are breaching your predefined threshold, such as three out of five times in any given five minutes interval or two out of six times in a thirty minutes interval. When M out of N datapoints are not breaching your threshold in an interval, the alarm will be in OK state. Please note that the M datapoints out of N datapoints in an interval can be of any order and does not need to be consecutive. Consequently, you can now get alerted even when the spikes in your metrics are intermittent over an interval.

## 2.166.0
* feature: ES: Added support for encryption of data at rest on Amazon Elasticsearch Service using AWS KMS
* feature: SES: Customers can customize the emails that Amazon SES sends when verifying new identities. This feature is helpful for developers whose applications send email through Amazon SES on behalf of their customers.

## 2.165.0
* feature: CloudDirectory: Amazon Cloud Directory makes it easier for you to apply schema changes across your directories with in-place schema upgrades. Your directories now remain available while backward-compatible schema changes are being applied, such as the addition of new fields. You also can view the history of your schema changes in Cloud Directory by using both major and minor version identifiers, which can help you track and audit schema versions across directories.
* feature: SageMaker: Initial waiters for common SageMaker workflows.

## 2.164.0
* feature: Iot: Add error action API for RulesEngine. 
* feature: ServiceCatalog: ServiceCatalog has two distinct personas for its use, an "admin" persona (who creates sets of products with different versions and prescribes who has access to them) and an "end-user" persona (who can launch cloud resources based on the configuration data their admins have given them access to).  This API update will allow admin users to deactivate/activate product versions, end-user will only be able to access and launch active product versions. 
* feature: ServiceDiscovery: Amazon Route 53 Auto Naming lets you configure public or private namespaces that your microservice applications run in. When instances of the service become available, you can call the Auto Naming API to register the instance, and Amazon Route 53 automatically creates up to five DNS records and an optional health check. Clients that submit DNS queries for the service receive an answer that contains up to eight healthy records.

## 2.163.0
* feature: Budgets: Add additional costTypes to support finer control for different charges included in a cost budget.

## 2.162.0
* feature: SageMaker: Preparing to release updated waiters week of December 4, 2017 for all supported SDKs.

## 2.161.0
* feature: APIGateway: Added support Private Integration and VPC Link features in API Gateway. This allows to create an API with the API Gateway private integration, thus providing clients access to HTTP/HTTPS resources in an Amazon VPC from outside of the VPC through a VpcLink resource.
* feature: AlexaForBusiness: Alexa for Business is now generally available for production use. Alexa for Business makes it easy for you to use Alexa in your organization. The Alexa for Business SDK gives you APIs to manage Alexa devices, enroll users, and assign skills at scale. For more information about Alexa for Business, go to https://aws.amazon.com/alexaforbusiness 
* feature: Cloud9: Adds support for creating and managing AWS Cloud9 development environments. AWS Cloud9 is a cloud-based integrated development environment (IDE) that you use to write, run, and debug code.
* feature: EC2: Adds the following updates: 1. Spread Placement ensures that instances are placed on distinct hardware in order to reduce correlated failures. 2. Inter-region VPC Peering allows customers to peer VPCs across different AWS regions without requiring additional gateways, VPN connections or physical hardware 
* feature: Lambda: AWS Lambda now supports the ability to set the concurrency limits for individual functions, and increasing memory to 3008MB.
* feature: ServerlessApplicationRepository: First release of the AWS Serverless Application Repository SDK

## 2.160.0
* feature: AutoScaling: You can now use Auto Scaling with EC2 Launch Templates via the CreateAutoScalingGroup and UpdateAutoScalingGroup APIs.
* feature: EC2: Adds the following updates: 1. T2 Unlimited enables high CPU performance for any period of time whenever required 2. You are now able to create and launch EC2 m5 and h1 instances
* feature: Lightsail: This release adds support for load balancer and TLS/SSL certificate management. This set of APIs allows customers to create, manage, and scale secure load balanced applications on Lightsail infrastructure. To provide support for customers who manage their DNS on Lightsail, we've added the ability create an Alias A type record which can point to a load balancer DNS name via the CreateDomainEntry API http://docs.aws.amazon.com/lightsail/2016-11-28/api-reference/API_CreateDomainEntry.html.
* feature: ResourceGroups: AWS Resource Groups lets you search and group AWS resources from multiple services based on their tags.
* feature: SSM: This release updates AWS Systems Manager APIs to enable executing automations at controlled rate, target resources in a resource groups and execute entire automation at once or single step at a time. It is now also possible to use YAML, in addition to JSON, when creating Systems Manager documents.
* feature: WAF: This release adds support for rule group and managed rule group. Rule group is a container of rules that customers can create, put rules in it and associate the rule group to a WebACL. All rules in a rule group will function identically as they would if each rule was individually associated to the WebACL. Managed rule group is a pre-configured rule group composed by our security partners and made available via the AWS Marketplace. Customers can subscribe to these managed rule groups, associate the managed rule group to their WebACL and start using them immediately to protect their resources.
* feature: WAFRegional: This release adds support for rule group and managed rule group. Rule group is a container of rules that customers can create, put rules in it and associate the rule group to a WebACL. All rules in a rule group will function identically as they would if each rule was individually associated to the WebACL. Managed rule group is a pre-configured rule group composed by our security partners and made available via the AWS Marketplace. Customers can subscribe to these managed rule groups, associate the managed rule group to their WebACL and start using them immediately to protect their resources.

## 2.159.0
* feature: Comprehend: Amazon Comprehend is an AWS service for gaining insight into the content of text and documents . It develops insights by recognizing the entities, key phrases, language, sentiments, and other common elements in a document. For more information, go to the Amazon Comprehend product page. To get started, see the Amazon Comprehend Developer Guide.
* feature: DynamoDB: Amazon DynamoDB now supports the following features: Global Table and On-Demand Backup. Global Table is a fully-managed, multi-region, multi-master database. DynamoDB customers can now write anywhere and read anywhere with single-digit millisecond latency by performing database operations closest to where end users reside. Global Table also enables customers to disaster-proof their applications, keeping them running and data accessible even in the face of natural disasters or region disruptions. Customers can set up Global Table with just a few clicks in the AWS Management Console-no application rewrites required. On-Demand Backup capability is to protect data from loss due to application errors, and meet customers' archival needs for compliance and regulatory reasons. Customers can backup and restore their DynamoDB table data anytime, with a single-click in the AWS management console or a single API call. Backup and restore actions execute with zero impact on table performance or availability. For more information, see the Amazon DynamoDB Developer Guide.
* feature: ECS: Amazon Elastic Container Service (Amazon ECS) released a new launch type for running containers on a serverless infrastructure. The Fargate launch type allows you to run your containerized applications without the need to provision and manage the backend infrastructure. Just register your task definition and Fargate launches the container for you. 
* feature: Glacier: This release includes support for Glacier Select, a new feature that allows you to filter and analyze your Glacier archives and store the results in a user-specified S3 location.
* feature: Greengrass: Greengrass OTA feature allows updating Greengrass Core and Greengrass OTA Agent. Local Resource Access feature allows Greengrass Lambdas to access local resources such as peripheral devices and volumes.
* feature: IoTJobsDataPlane: This release adds support for new the service called Iot Jobs. This client is built for the device SDK to use Iot Jobs Device specific APIs.
* feature: Iot: This release adds support for a number of new IoT features, including AWS IoT Device Management (Jobs, Fleet Index and Thing Registration), Thing Groups, Policies on Thing Groups, Registry & Job Events, JSON Logs, Fine-Grained Logging Controls, Custom Authorization and AWS Service Authentication Using X.509 Certificates.
* feature: KinesisVideo: Announcing Amazon Kinesis Video Streams, a fully managed video ingestion and storage service. Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for machine learning, analytics, and processing. You can also stream other time-encoded data like RADAR and LIDAR signals using Kinesis Video Streams.
* feature: KinesisVideoArchivedMedia: Announcing Amazon Kinesis Video Streams, a fully managed video ingestion and storage service. Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for machine learning, analytics, and processing. You can also stream other time-encoded data like RADAR and LIDAR signals using Kinesis Video Streams.
* feature: KinesisVideoMedia: Announcing Amazon Kinesis Video Streams, a fully managed video ingestion and storage service. Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for machine learning, analytics, and processing. You can also stream other time-encoded data like RADAR and LIDAR signals using Kinesis Video Streams.
* feature: Rekognition: This release introduces Amazon Rekognition support for video analysis.
* feature: S3: This release includes support for Glacier Select, a new feature that allows you to filter and analyze  your Glacier storage class objects and store the results in a user-specified S3 location.
* feature: SageMaker: Amazon SageMaker is a fully-managed service that enables data scientists and developers to quickly and easily build, train, and deploy machine learning models, at scale.
* feature: SageMakerRuntime: Amazon SageMaker is a fully-managed service that enables data scientists and developers to quickly and easily build, train, and deploy machine learning models, at scale.
* feature: Translate: Public preview release of Amazon Translate and the Amazon Translate Developer Guide. For more information, see the Amazon Translate Developer Guide.

## 2.158.0
* feature: APIGateway: Changes related to CanaryReleaseDeployment feature. Enables API developer to create a deployment as canary deployment and test API changes with percentage of customers before promoting changes to all customers.
* feature: AppSync: AWS AppSync is an enterprise-level, fully managed GraphQL service with real-time data synchronization and offline programming features.
* feature: Batch: Add support for Array Jobs which allow users to easily submit many copies of a job with a single API call.  This change also enhances the job dependency model to support N_TO_N and sequential dependency chains. The ListJobs and DescribeJobs APIs now have the ability to list or describe the status of entire Array Jobs or individual elements within the array.
* feature: CodeDeploy: Support for AWS Lambda function deployment - AWS CodeDeploy now supports the deployment of AWS Lambda functions. A Lambda deployment uses a Lambda function alias to shift traffic to a new version. You select a deployment configuration that specifies exactly how traffic shifts to your new version. Success of a deployment can be validated using Lambda functions that are referenced by the deployment. This provides the opportunity to rollback if necessary.
* feature: CognitoIdentityServiceProvider: AWS Cognito SDK has been updated to support new Cognito user-pool objects and operations for advanced security
* feature: EC2: Adds the following updates: 1. You are now able to host a service powered by AWS PrivateLink to provide private connectivity to other VPCs. You are now also able to create endpoints to other services powered by PrivateLink including AWS services, Marketplace Seller services or custom services created by yourself or other AWS VPC customers. 2. You are now able to save launch parameters in a single template that can be used with Auto Scaling, Spot Fleet, Spot, and On Demand instances. 3. You are now able to launch Spot instances via the RunInstances API, using a single additional parameter. RunInstances will response synchronously with an instance ID should capacity be available for your Spot request. 4. A simplified Spot pricing model which delivers low, predictable prices that adjust gradually, based on long-term trends in supply and demand. 5. Amazon EC2 Spot can now hibernate Amazon EBS-backed instances in the event of an interruption, so your workloads pick up from where they left off. Spot can fulfill your request by resuming instances from a hibernated state when capacity is available.
* feature: GuardDuty: Enable Amazon GuardDuty to continuously monitor and process AWS data sources to identify threats to your AWS accounts and workloads.  You can add customization by uploading additional threat intelligence lists and IP safe lists. You can list security findings, suspend, and disable the service. 
* feature: Lambda: Lambda aliases can now shift traffic between two function versions, based on preassigned weights.
* feature: MQ: This is the initial SDK release for Amazon MQ. Amazon MQ is a managed message broker service for Apache ActiveMQ that makes it easy to set up and operate message brokers in the cloud. 
* feature: credentials_provider: Add general purpose RemoteCredentials and derive ECSCredentials from it

## 2.157.0
* feature: MediaConvert: AWS Elemental MediaConvert is a file-based video conversion service that transforms media into formats required for traditional broadcast and for internet streaming to multi-screen devices.
* feature: MediaLive: AWS Elemental MediaLive is a video service that lets you easily create live outputs for broadcast and streaming delivery.
* feature: MediaPackage: AWS Elemental MediaPackage is a just-in-time video packaging and origination service that lets you format highly secure and reliable live outputs for a variety of devices.
* feature: MediaStore: AWS Elemental MediaStore is an AWS storage service optimized for media. It gives you the performance, consistency, and low latency required to deliver live and on-demand video content. AWS Elemental MediaStore acts as the origin store in your video workflow.
* feature: MediaStoreData: AWS Elemental MediaStore is an AWS storage service optimized for media. It gives you the performance, consistency, and low latency required to deliver live and on-demand video content. AWS Elemental MediaStore acts as the origin store in your video workflow.

## 2.156.0
* bugfix: Presigner: Update presigner to only hoist headers in v2
* feature: ACM: AWS Certificate Manager now supports the ability to import domainless certs and additional Key Types as well as an additional validation method for DNS.

## 2.155.0
* feature: APIGateway: Add support for Access logs and customizable integration timeouts
* feature: CloudFormation: 1) Instance-level parameter overrides (CloudFormation-StackSet feature): This feature will allow the customers to override the template parameters on specific stackInstances. Customers will also have ability to update their existing instances with/without parameter-overrides using a new API "UpdateStackInstances"                                                                                                                                                                                                                                                         2) Add support for SSM parameters in CloudFormation - This feature will allow the customers to use Systems Manager parameters in CloudFormation templates. They will be able to see values for these parameters in Describe APIs.
* feature: CodeBuild: Adding support for accessing Amazon VPC resources from AWS CodeBuild, dependency caching and build badges.
* feature: EMR: Enable Kerberos on Amazon EMR. 
* feature: Rekognition: This release includes updates to Amazon Rekognition for the following APIs. The new DetectText API allows you to recognize and extract textual content from images. Face Model Versioning has been added to operations that deal with face detection.
* feature: Shield: The AWS Shield SDK has been updated in order to support Elastic IP address protections, the addition of AttackProperties objects in DescribeAttack responses, and a new GetSubscriptionState operation.
* feature: StorageGateway: AWS Storage Gateway now enables you to get notification when all your files written to your NFS file share have been uploaded to Amazon S3. Storage Gateway also enables guessing of the MIME type for uploaded objects based on file extensions.
* feature: XRay: Added automatic pagination support for AWS X-Ray APIs in the SDKs that support this feature.

## 2.154.0
* feature: CodeCommit: AWS CodeCommit now supports pull requests. You can use pull requests to collaboratively review code changes for minor changes or fixes, major feature additions, or new versions of your released software.
* feature: CostExplorer: The AWS Cost Explorer API gives customers programmatic access to AWS cost and usage information, allowing them to perform adhoc queries and build interactive cost management applications that leverage this dataset.
* feature: Firehose: This release includes a new Kinesis Firehose feature that supports Splunk as Kinesis Firehose delivery destination. You can now use Kinesis Firehose to ingest real-time data to Splunk in a serverless, reliable, and salable manner. This release also includes a new feature that allows you to configure Lambda buffer size in Kinesis Firehose data transformation feature. You can now customize the data buffer size before invoking Lambda function in Kinesis Firehose for data transformation. This feature allows you to flexibly trade-off processing and delivery latency with cost and efficiency based on your specific use cases and requirements. 
* feature: Kinesis: Customers can now obtain the important characteristics of their stream with DescribeStreamSummary. The response will not include the shard list for the stream but will have the number of open shards, and all the other fields included in the DescribeStream response.
* feature: WorkDocs: DescribeGroups API and miscellaneous enhancements

## 2.153.0
* feature: ApplicationAutoScaling: This SDK update contains support for Target Tracking scaling for EC2 Spot Fleet. It allows you to scale an EC2 Spot Fleet using a Target Tracking scaling policy.
* feature: DMS: Support for migration task assessment. Support for data validation after the migration.
* feature: RDS: Amazon RDS now supports importing MySQL databases by using backup files from Amazon S3.
* feature: S3: Added ORC to the supported S3 Inventory formats.

## 2.152.0
* bugfix: S3: Reverts default signatureVersion for S3 presigned URLs to the lowest signatureVersion the region supports. 2.150.0 changed the default signatureVersion of all presigned URLs to v4. This change does not affect S3 clients that had the signatureVersion explicitly defined.
* feature: ApplicationAutoScaling: Application Auto Scaling now supports automatic scaling of Amazon Aurora replicas
* feature: EC2: You are now able to create and launch EC2 x1e smaller instance sizes
* feature: Glue: API update for AWS Glue. New crawler configuration attribute enables customers to specify crawler behavior. New XML classifier enables classification of XML data.
* feature: Organizations: This release adds APIs that you can use to enable and disable integration with AWS services designed to work with AWS Organizations. This integration allows the AWS service to perform operations on your behalf on all of the accounts in your organization. Although you can use these APIs yourself, we recommend that you instead use the commands provided in the other AWS service to enable integration with AWS Organizations.
* feature: Route53: You can use Route 53's GetAccountLimit/GetHostedZoneLimit/GetReusableDelegationSetLimit APIs to view your current limits (including custom set limits) on Route 53 resources such as hosted zones and health checks. These APIs also return the number of each resource you're currently using to enable comparison against your current limits.

## 2.151.0
* feature: APIGateway: 1. Extended GetDocumentationParts operation to support retrieving documentation parts resources without contents.  2. Added hosted zone ID in the custom domain response.
* feature: Polly: Amazon Polly adds Korean language support with new female voice - "Seoyeon" and new Indian English female voice - "Aditi"
* feature: SES: SES launches Configuration Set Reputation Metrics and Email Pausing Today, two features that build upon the capabilities of the reputation dashboard. The first is the ability to export reputation metrics for individual configuration sets. The second is the ability to temporarily pause email sending, either at the configuration set level, or across your entire Amazon SES account.
* feature: StepFunctions: You can now use the UpdateStateMachine API to update your state machine definition and role ARN. Existing executions will continue to use the previous definition and role ARN. You can use the DescribeStateMachineForExecution API to determine which state machine definition and role ARN is associated with an execution

## 2.150.0
* feature: ECS: Added new mode for Task Networking in ECS, called awsvpc mode. Mode configuration parameters to be passed in via awsvpcConfiguration. Updated APIs now use/show this new mode - RegisterTaskDefinition, CreateService, UpdateService, RunTask, StartTask.
* feature: ECS: Remove localhost restriction for ECS credential provider
* feature: Lightsail: Lightsail now supports attached block storage, which allows you to scale your applications and protect application data with additional SSD-backed storage disks. This feature allows Lightsail customers to attach secure storage disks to their Lightsail instances and manage their attached disks, including creating and deleting disks, attaching and detaching disks from instances, and backing up disks via snapshot.
* feature: Route53: When a Route 53 health check or hosted zone is created by a linked AWS service, the object now includes information about the service that created it. Hosted zones or health checks that are created by a linked service can't be updated or deleted using Route 53.
* feature: SSM: EC2 Systems Manager GetInventory API adds support for aggregation.

## 2.149.0
* feature: EC2: Introduces the following features: 1. Create a default subnet in an Availability Zone if no default subnet exists. 2. Spot Fleet integrates with Elastic Load Balancing to enable you to attach one or more load balancers to a Spot Fleet request. When you attach the load balancer, it automatically registers the instance in the Spot Fleet to the load balancers which distributes incoming traffic across the instances. 

## 2.148.0
* feature: ApplicationAutoScaling: Application Auto Scaling customers are now able to schedule adjustments to their MinCapacity and MaxCapacity, which makes it possible to pre-provision adequate capacity for anticipated demand and then reduce the provisioned capacity as demand lulls.
* feature: EC2: AWS PrivateLink for Amazon Services - Customers can now privately access Amazon services from their Amazon Virtual Private Cloud (VPC), without using public IPs, and without requiring the traffic to traverse across the Internet.
* feature: ElastiCache: This release adds online resharding for ElastiCache for Redis offering, providing the ability to add and remove shards from a running cluster. Developers can now dynamically scale-out or scale-in their Redis cluster workloads to adapt to changes in demand. ElastiCache will resize the cluster by adding or removing shards and redistribute hash slots uniformly across the new shard configuration, all while the cluster continues to stay online and serves requests.
* feature: Logger: Update the request logger to exclude sensitive input parammeters from being logged

## 2.147.0
* feature: ELBv2: Added a new limit related to Network Load Balancers on the number of targets per load balancer per AZ.
* feature: RDS: DescribeOrderableDBInstanceOptions now returns the minimum and maximum allowed values for storage size, total provisioned IOPS, and provisioned IOPS per GiB for a DB instance.
* feature: S3: This releases adds support for 4 features: 1. Default encryption for S3 Bucket, 2. Encryption status in inventory and Encryption support for inventory.  3. Cross region replication of KMS-encrypted objects, and 4. ownership overwrite for CRR. 

## 2.146.0
* feature: EC2: You are now able to create and launch EC2 C5 instances, the next generation of EC2's compute-optimized instances, in us-east-1, us-west-2 and eu-west-1. C5 instances offer up to 72 vCPUs, 144 GiB of DDR4 instance memory, 25 Gbps in Network bandwidth and improved EBS and Networking bandwidth on smaller instance sizes to deliver improved performance for compute-intensive workloads.
* feature: KMS: Documentation updates for AWS KMS. 
* feature: Pricing: This is the initial release of AWS Price List Service.
* feature: StepFunctions: Documentation update.

## 2.145.0
* feature: ECS: Amazon ECS users can now add devices to their containers and enable init process in containers through the use of docker's 'devices' and 'init' features. These fields can be specified under linuxParameters in ContainerDefinition in the Task Definition Template. 

## 2.144.0
* feature: APIGateway: This release supports creating and managing Regional and Edge-Optimized API endpoints.

## 2.143.0
* feature: DirectConnect: AWS DirectConnect now provides support for Global Access for Virtual Private Cloud (VPC) via a new feature called Direct Connect Gateway. A Direct Connect Gateway will allow you to group multiple Direct Connect Private Virtual Interfaces (DX-VIF) and Private Virtual Gateways (VGW) from different AWS regions (but belonging to the same AWS Account) and pass traffic from any DX-VIF to any VPC in the grouping.

## 2.142.0
* feature: Configuration: Allow the logger by SDK clients to be controlled via the environment if not defined programmatically. If the `AWSJS_DEBUG` environment variable is set to a truthy value and no other logger is defined, the global `console` object will be used.
* feature: DirectConnect: AWS DirectConnect now provides support for Global Access for Virtual Private Cloud (VPC) via a new feature called Direct Connect Gateway. A Direct Connect Gateway will allow you to group multiple Direct Connect Private Virtual Interfaces (DX-VIF) and Private Virtual Gateways (VGW) from different AWS regions (but belonging to the same AWS Account) and pass traffic from any DX-VIF to any VPC in the grouping.

## 2.141.0
* feature: CloudFront: You can now specify additional options for MinimumProtocolVersion, which controls the SSL/TLS protocol that CloudFront uses to communicate with viewers. The minimum protocol version that you choose also determines the ciphers that CloudFront uses to encrypt the content that it returns to viewers.
* feature: EC2: You are now able to create and launch EC2 P3 instance, next generation GPU instances, optimized for machine learning and high performance computing applications. With up to eight NVIDIA Tesla V100 GPUs, P3 instances provide up to one petaflop of mixed-precision, 125 teraflops of single-precision, and 62 teraflops of double-precision floating point performance, as well as a 300 GB/s second-generation NVLink interconnect that enables high-speed, low-latency GPU-to-GPU communication. P3 instances also feature up to 64 vCPUs based on custom Intel Xeon E5 (Broadwell) processors, 488 GB of DRAM, and 25 Gbps of dedicated aggregate network bandwidth using the Elastic Network Adapter (ENA).

## 2.140.0
* feature: ConfigService: AWS Config support for CodeBuild Project resource type
* feature: ElastiCache: Amazon ElastiCache for Redis today announced support for data encryption both for data in-transit and data at-rest. The new encryption in-transit functionality enables ElastiCache for Redis customers to encrypt data for all communication between clients and Redis engine, and all intra-cluster Redis communication. The encryption at-rest functionality allows customers to encrypt their S3 based backups. Customers can begin using the new functionality by simply enabling this functionality via AWS console, and a small configuration change in their Redis clients. The ElastiCache for Redis service automatically manages life cycle of the certificates required for encryption, including the issuance, renewal and expiration of certificates. Additionally, as part of this launch, customers will gain the ability to start using the Redis AUTH command that provides an added level of authentication.
* feature: Glue: AWS Glue: Adding a new API, BatchStopJobRun, to stop one or more job runs for a specified Job. 
* feature: Pinpoint: Added support for APNs VoIP messages. Added support for collapsible IDs, message priority, and TTL for APNs and FCM/GCM.

## 2.139.0
* feature: Organizations: This release supports integrating other AWS services with AWS Organizations through the use of an IAM service-linked role called AWSServiceRoleForOrganizations. Certain operations automatically create that role if it does not already exist.

## 2.138.0
* feature: EC2: Adding pagination support for DescribeSecurityGroups for EC2 Classic and VPC Security Groups

## 2.137.0
* feature: SQS: Added support for tracking cost allocation by adding, updating, removing, and listing the metadata tags of Amazon SQS queues.
* feature: SSM: EC2 Systems Manager versioning support for Parameter Store. Also support for referencing parameter versions in SSM Documents.

## 2.136.0
* feature: Lightsail: This release adds support for Windows Server-based Lightsail instances. The GetInstanceAccessDetails API now returns the password of your Windows Server-based instance when using the default key pair. GetInstanceAccessDetails also returns a PasswordData object for Windows Server instances containing the ciphertext and keyPairName. The Blueprint data type now includes a list of platform values (LINUX_UNIX or WINDOWS). The Bundle data type now includes a list of SupportedPlatforms values (LINUX_UNIX or WINDOWS).

## 2.135.0
* feature: ES: This release adds support for VPC access to Amazon Elasticsearch Service.

## 2.134.0
* feature: CORS: The LexModelBuildingService supports CORS. This change adds the service to the browser version of the SDK by default.
* feature: EC2: You can now change the tenancy of your VPC from dedicated to default with a single API operation. For more details refer to the documentation for changing VPC tenancy.
* feature: ES: AWS Elasticsearch adds support for enabling slow log publishing. Using slow log publishing options customers can configure and enable index/query slow log publishing of their domain to preferred AWS Cloudwatch log group.
* feature: RDS: Adds waiters for DBSnapshotAvailable and DBSnapshotDeleted.
* feature: WAF: This release adds support for regular expressions as match conditions in rules, and support for geographical location by country of request IP address as a match condition in rules.
* feature: WAFRegional: This release adds support for regular expressions as match conditions in rules, and support for geographical location by country of request IP address as a match condition in rules.

## 2.133.0
* feature: CodeCommit: This release includes the DeleteBranch API and a change to the contents of a Commit object.
* feature: DMS: This change includes addition of new optional parameter to an existing API
* feature: ElasticBeanstalk: Added the ability to add, delete or update Tags
* feature: Polly: Amazon Polly exposes two new voices: "Matthew" (US English) and "Takumi" (Japanese)
* feature: RDS: You can now call DescribeValidDBInstanceModifications to learn what modifications you can make to your DB instance. You can use this information when you call ModifyDBInstance.

## 2.132.0
* feature: ECR: Adds support for new API set used to manage Amazon ECR repository lifecycle policies. Amazon ECR lifecycle policies enable you to specify the lifecycle management of images in a repository. The configuration is a set of one or more rules, where each rule defines an action for Amazon ECR to apply to an image. This allows the automation of cleaning up unused images, for example expiring images based on age or status. A lifecycle policy preview API is provided as well, which allows you to see the impact of a lifecycle policy on an image repository before you execute it
* feature: SES: Added content related to email template management and templated email sending operations.

## 2.131.0
* feature: EC2: This release includes updates to AWS Virtual Private Gateway.
* feature: ELBv2: Server Name Indication (SNI) is an extension to the TLS protocol by which a client indicates the hostname to connect to at the start of the TLS handshake. The load balancer can present multiple certificates through the same secure listener, which enables it to support multiple secure websites using a single secure listener. Application Load Balancers also support a smart certificate selection algorithm with SNI. If the hostname indicated by a client matches multiple certificates, the load balancer determines the best certificate to use based on multiple factors including the capabilities of the client.
* feature: OpsWorksCM: Provide engine specific information for node associations.

## 2.130.0
* feature: ConfigService: Revert: Added missing enumeration values for ConfigurationItemStatus

## 2.129.0
* feature: ConfigService: Added missing enumeration values for ConfigurationItemStatus

## 2.128.0
* feature: Redshift: DescribeEventSubscriptions API supports tag keys and tag values as request parameters. 

## 2.127.0
* feature: KinesisAnalytics: Kinesis Analytics now supports schema discovery on objects in S3.  Additionally, Kinesis Analytics now supports input data preprocessing through Lambda.
* feature: Route53Domains: Added a new API that checks whether a domain name can be transferred to Amazon Route 53.

## 2.126.0
* feature: EC2: This release includes service updates to AWS VPN.
* feature: SSM: EC2 Systems Manager support for tagging SSM Documents. Also support for tag-based permissions to restrict access to SSM Documents based on these tags.

## 2.125.0
* feature: AppStream: Includes APIs for managing and accessing image builders, and deleting images.
* feature: CodeBuild: Adding support for Building GitHub Pull Requests in AWS CodeBuild
* feature: MTurk: Today, Amazon Mechanical Turk (MTurk) supports SQS Notifications being delivered to Customers' SQS queues when different stages of the MTurk workflow are complete.  We are going to create new functionality so that Customers can leverage SNS topics as a destination for notification messages when various stages of the MTurk workflow are complete. 
* feature: Organizations: This release flags the HandshakeParty structure's Type and Id fields as 'required'. They effectively were required in the past, as you received an error if you did not include them. This is now reflected at the API definition level. 
* feature: Route53: This change allows customers to reset elements of health check.

## 2.124.0
* feature: Pinpoint: Added two new push notification channels: Amazon Device Messaging (ADM) and, for push notification support in China, Baidu Cloud Push. Added support for APNs auth via .p8 key file. Added operation for direct message deliveries to user IDs, enabling you to message an individual user on multiple endpoints.

## 2.123.0
* feature: CloudFormation: You can now prevent a stack from being accidentally deleted by enabling termination protection on the stack. If you attempt to delete a stack with termination protection enabled, the deletion fails and the stack, including its status, remains unchanged. You can enable termination protection on a stack when you create it. Termination protection on stacks is disabled by default. After creation, you can set termination protection on a stack whose status is CREATE_COMPLETE, UPDATE_COMPLETE, or UPDATE_ROLLBACK_COMPLETE.

## 2.122.0
* feature: ConfigService: AWS Config support for DynamoDB tables and Auto Scaling resource types
* feature: ECS: Amazon ECS users can now add and drop Linux capabilities to their containers through the use of docker's cap-add and cap-drop features. Customers can specify the capabilities they wish to add or drop for each container in their task definition. 

## 2.121.0
* feature: Budgets: Including "DuplicateRecordException" in UpdateNotification and UpdateSubscriber. 
* feature: CloudWatchLogs: Adds support for associating LogGroups with KMS Keys.
* feature: EC2: Add EC2 APIs to copy Amazon FPGA Images (AFIs) within the same region and across multiple regions, delete AFIs, and modify AFI attributes. AFI attributes include name, description and granting/denying other AWS accounts to load the AFI.

## 2.120.0
* feature: AppStream: API updates for supporting On-Demand fleets.
* feature: CodePipeline: This change includes a PipelineMetadata object that is part of the output from the GetPipeline API that includes the Pipeline ARN, created, and updated timestamp.
* feature: Greengrass: Reset Deployments feature allows you to clean-up the cloud resource so you can delete the group. It also cleans up the core so that it goes back to the pre-deployment state.
* feature: LexRuntime: Request attributes can be used to pass client specific information from the client to Amazon Lex as part of each request.
* feature: RDS: Introduces the --option-group-name parameter to the ModifyDBSnapshot CLI command. You can specify this parameter when you upgrade an Oracle DB snapshot. The same option group considerations apply when upgrading a DB snapshot as when upgrading a DB instance.  For more information, see http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.Oracle.html#USER_UpgradeDBInstance.Oracle.OGPG.OG

## 2.119.0
* feature: EC2: Fixed bug in EC2 clients preventing ElasticGpuSet from being set.

## 2.118.0
* feature: EC2: Amazon EC2 now lets you opt for Spot instances to be stopped in the event of an interruption instead of being terminated.  Your Spot request can be fulfilled again by restarting instances from a previously stopped state, subject to availability of capacity at or below your preferred price.  When you submit a persistent Spot request, you can choose from "terminate" or "stop" as the instance interruption behavior.  Choosing "stop" will shutdown your Spot instances so you can continue from this stopped state later on.  This feature is only available for instances with Amazon EBS volume as their root device.
* feature: IAM: A new API, DeleteServiceLinkedRole, submits a service-linked role deletion request and returns a DeletionTaskId, which you can use to check the status of the deletion.
* feature: SES: Amazon Simple Email Service (Amazon SES) now lets you customize the domains used for tracking open and click events. Previously, open and click tracking links referred to destinations hosted on domains operated by Amazon SES. With this feature, you can use your own branded domains for capturing open and click events.

## 2.117.0
* feature: APIGateway: Add a new enum "REQUEST" to '--type <value>' field in the current create-authorizer API, and make "identitySource" optional.

## 2.116.0
* bugfix: clock skew: put the updating clock skew logic to each service client instead of using global config
* feature: CodeBuild: Supporting Parameter Store in environment variables for AWS CodeBuild
* feature: ServiceCatalog: This release of Service Catalog adds API support to copy products.

## 2.115.0
* feature: AutoScaling: Customers can create Life Cycle Hooks at the time of creating Auto Scaling Groups through the CreateAutoScalingGroup API
* feature: CloudWatchEvents: Exposes ConcurrentModificationException as one of the valid exceptions for PutPermission and RemovePermission operation.
* feature: EC2: You are now able to create and launch EC2 x1e.32xlarge instance, a new EC2 instance in the X1 family, in us-east-1, us-west-2, eu-west-1, and ap-northeast-1. x1e.32xlarge offers 128 vCPUs, 3,904 GiB of DDR4 instance memory, high memory bandwidth, large L3 caches, and leading reliability capabilities to boost the performance and reliability of in-memory applications.

## 2.114.0
* feature: EC2: Fixed bug in EC2 clients preventing HostOfferingSet from being set

## 2.113.0
* feature: DeviceFarm: DeviceFarm has added support for two features - RemoteDebugging and Customer Artifacts. Customers  can now do remote Debugging on their Private Devices and can now retrieve custom files generated by their tests on the device and the device host (execution environment) on both public and private devices. 

## 2.112.0
* feature: CloudWatchLogs: Adds support for the PutResourcePolicy, DescribeResourcePolicy and DeleteResourcePolicy APIs.

## 2.111.0
* feature: EC2: With Tagging support, you can add Key and Value metadata to search, filter and organize your NAT Gateways according to your organization's needs.
* feature: ELBv2: The feature enables the new Network Load Balancer that is optimized to handle volatile traffic patterns while using a single static IP address per Availability Zone. Network Load Balancer operates at the connection level (Layer 4), routing connections to Amazon EC2 instances and containers, within Amazon Virtual Private Cloud (Amazon VPC) based on IP protocol data.
* feature: LexModelBuildingService: Amazon Lex provides the ability to export your Amazon Lex chatbot definition as a JSON file that can be added to the target platform. The JSON configuration file contains the structure of your Amazon Lex chatbot, including the intent schema with utterances, slots, prompts and slot-types.
* feature: Route53: You can configure Amazon Route 53 to log information about the DNS queries that Amazon Route 53 receives for your domains and subdomains. When you configure query logging, Amazon Route 53 starts to send logs to CloudWatch Logs. You can use various tools, including the AWS console, to access the query logs.

## 2.110.0
* feature: Budgets: Add an optional "thresholdType" to notifications to support percentage or absolute value thresholds.

## 2.109.0
* feature: CodeStar: Added support to tag CodeStar projects. Tags can be used to organize and find CodeStar projects on key-value pairs that you can choose. For example, you could add a tag with a key of "Release" and a value of "Beta" to projects your organization is working on for an upcoming beta release.

## 2.108.0
* feature: GameLift: GameLift VPC resources can be peered with any other AWS VPC. R4 memory-optimized instances now available to deploy.
* feature: Mobile: AWS Mobile Hub is an integrated experience designed to help developers build, test, configure and release cloud-based applications for mobile devices using Amazon Web Services. AWS Mobile Hub provides a console and API for developers, allowing them to quickly select desired features and integrate them into mobile applications. Features include NoSQL Database, Cloud Logic, Messaging and Analytics. With AWS Mobile Hub, you pay only for the underlying services that Mobile Hub provisions based on the features you choose in the Mobile Hub console.
* feature: SSM: Adding KMS encryption support to SSM Inventory Resource Data Sync. Exposes the ClientToken parameter on SSM StartAutomationExecution to provide idempotent execution requests.

## 2.107.0
* feature: CodeBuild: The AWS CodeBuild HTTP API now provides the BatchDeleteBuilds operation, which enables you to delete existing builds.
* feature: EC2: Descriptions for Security Group Rules enables customers to be able to define a description for ingress and egress security group rules . The Descriptions for Security Group Rules feature supports one description field per Security Group rule for both ingress and egress rules . Descriptions for Security Group Rules provides a simple way to describe the purpose or function of a Security Group Rule allowing for easier customer identification of configuration elements .      Prior to the release of Descriptions for Security Group Rules , customers had to maintain a separate system outside of AWS if they wanted to track Security Group Rule mapping and their purpose for being implemented. If a security group rule has already been created and you would like to update or change your description for that security group rule you can use the UpdateSecurityGroupRuleDescription API.
* feature: ELBv2: This change now allows Application Load Balancers to distribute traffic to AWS resources using their IP addresses as targets in addition to the instance IDs. You can also load balance to resources outside the VPC hosting the load balancer using their IP addresses as targets. This includes resources in peered VPCs, EC2-Classic, and on-premises locations reachable over AWS Direct Connect or a VPN connection.
* feature: LexModelBuildingService: Amazon Lex now supports synonyms for slot type values. If the user inputs a synonym, it will be resolved to the corresponding slot value.

## 2.106.0
* feature: ApplicationAutoScaling: Application Auto Scaling now supports the DisableScaleIn option for Target Tracking Scaling Policies. This allows customers to create scaling policies that will only add capacity to the target.
* feature: Organizations: The exception ConstraintViolationException now contains a new reason subcode MASTERACCOUNT_MISSING_CONTACT_INFO to make it easier to understand why attempting to remove an account from an Organization can fail. We also improved several other of the text descriptions and examples.

## 2.105.0
* feature: ConfigService: Increased the internal size limit of resourceId
* feature: EC2: Provides capability to add secondary CIDR blocks to a VPC.

## 2.104.0
* feature: CloudFormation: Rollback triggers enable you to have AWS CloudFormation monitor the state of your application during stack creation and updating, and to roll back that operation if the application breaches the threshold of any of the alarms you've specified.
* feature: GameLift: Update spelling of MatchmakingTicket status values for internal consistency.
* feature: RDS: Option group options now contain additional properties that identify requirements for certain options. Check these properties to determine if your DB instance must be in a VPC or have auto minor upgrade turned on before you can use an option. Check to see if you can downgrade the version of an option after you have installed it.

## 2.103.0
* feature: Rekognition: Update the enum value of LandmarkType and GenderType to be consistent with service response

## 2.102.0
* feature: SSM: Changes to associations in Systems Manager State Manager can now be recorded. Previously, when you edited associations, you could not go back and review older association settings. Now, associations are versioned, and can be named using human-readable strings, allowing you to see a trail of association changes. You can also perform rate-based scheduling, which allows you to schedule associations more granularly.

## 2.101.0
* feature: Firehose: This change will allow customers to attach a Firehose delivery stream to an existing Kinesis stream directly. You no longer need a forwarder to move data from a Kinesis stream to a Firehose delivery stream. You can now run your streaming applications on your Kinesis stream and easily attach a Firehose delivery stream to it for data delivery to S3, Redshift, or Elasticsearch concurrently.
* feature: Route53: Amazon Route 53 now supports CAA resource record type. A CAA record controls which certificate authorities are allowed to issue certificates for the domain or subdomain.

## 2.100.0
* feature: GameLift: The Matchmaking Grouping Service is a new feature that groups player match requests for a given game together into game sessions based on developer configured rules.

## 2.99.0
* feature: EC2: Fixed bug in EC2 clients preventing HostReservation from being set

## 2.98.0
* feature: Batch: This release enhances the DescribeJobs API to include the CloudWatch logStreamName attribute in ContainerDetail and ContainerDetailAttempt
* feature: CloudHSMV2: CloudHSM provides hardware security modules for protecting sensitive data and cryptographic keys within an EC2 VPC, and enable the customer to maintain control over key access and use. This is a second-generation of the service that will improve security, lower cost and provide better customer usability.
* feature: EFS: Customers can create encrypted EFS file systems and specify a KMS master key to encrypt it with.
* feature: Glue: AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics. You can create and run an ETL job with a few clicks in the AWS Management Console. You simply point AWS Glue to your data stored on AWS, and AWS Glue discovers your data and stores the associated metadata (e.g. table definition and schema) in the AWS Glue Data Catalog. Once cataloged, your data is immediately searchable, queryable, and available for ETL. AWS Glue generates the code to execute your data transformations and data loading processes. AWS Glue generates Python code that is entirely customizable, reusable, and portable. Once your ETL job is ready, you can schedule it to run on AWS Glue's fully managed, scale-out Spark environment. AWS Glue provides a flexible scheduler with dependency resolution, job monitoring, and alerting. AWS Glue is serverless, so there is no infrastructure to buy, set up, or manage. It automatically provisions the environment needed to complete the job, and customers pay only for the compute resources consumed while running ETL jobs. With AWS Glue, data can be available for analytics in minutes.
* feature: MigrationHub: AWS Migration Hub provides a single location to track migrations across multiple AWS and partner solutions. Using Migration Hub allows you to choose the AWS and partner migration tools that best fit your needs, while providing visibility into the status of your entire migration portfolio. Migration Hub also provides key metrics and progress for individual applications, regardless of which tools are being used to migrate them. For example, you might use AWS Database Migration Service, AWS Server Migration Service, and partner migration tools to migrate an application comprised of a database, virtualized web servers, and a bare metal server. Using Migration Hub will provide you with a single screen that shows the migration progress of all the resources in the application. This allows you to quickly get progress updates across all of your migrations, easily identify and troubleshoot any issues, and reduce the overall time and effort spent on your migration projects. Migration Hub is available to all AWS customers at no additional charge. You only pay for the cost of the migration tools you use, and any resources being consumed on AWS. 
* feature: SSM: Systems Manager Maintenance Windows include the following changes or enhancements: New task options using Systems Manager Automation, AWS Lambda, and AWS Step Functions; enhanced ability to edit the targets of a Maintenance Window, including specifying a target name and description, and ability to edit the owner field; enhanced ability to edits tasks; enhanced support for Run Command parameters; and you can now use a --safe flag when attempting to deregister a target. If this flag is enabled when you attempt to deregister a target, the system returns an error if the target is referenced by any task. Also, Systems Manager now includes Configuration Compliance to scan your fleet of managed instances for patch compliance and configuration inconsistencies. You can collect and aggregate data from multiple AWS accounts and Regions, and then drill down into specific resources that aren't compliant.
* feature: StorageGateway: Add optional field ForceDelete to DeleteFileShare api.

## 2.97.0
* bugfix: REST-JSON serialization: Automatically add a content-type header of application/json to requests with a JSON body
* feature: CodeDeploy: Adds support for specifying Application Load Balancers in deployment groups, for both in-place and blue/green deployments.
* feature: CognitoIdentityServiceProvider: We have added support for features for Amazon Cognito User Pools that enable application developers to easily add and customize a sign-up and sign-in user experience, use OAuth 2.0, and integrate with Facebook, Google, Login with Amazon, and SAML-based identity providers.
* feature: EC2: Provides customers an opportunity to recover an EIP that was released

## 2.96.0
* feature: CloudDirectory: Enable BatchDetachPolicy
* feature: CodeBuild: Supporting Bitbucket as source type in AWS CodeBuild.

## 2.95.0
* bugfix: credentials: add typescript definition for resolvePromise()
* bugfix: typings: add readablestream type to clients that support streaming
* feature: ElasticBeanstalk: Add support for paginating the result of DescribeEnvironments     Include the ARN of described environments in DescribeEnvironments output

## 2.94.0
* feature: CodeDeploy: AWS CodeDeploy now supports the use of multiple tag groups in a single deployment group (an intersection of tags) to identify the instances for a deployment. When you create or update a deployment group, use the new ec2TagSet and onPremisesTagSet structures to specify up to three groups of tags. Only instances that are identified by at least one tag in each of the tag groups are included in the deployment group.
* feature: ConfigService: Added new API, GetDiscoveredResourceCounts, which returns the resource types, the number of each resource type, and the total number of resources that AWS Config is recording in the given region for your AWS account.
* feature: EC2: Ec2 SpotInstanceRequestFulfilled waiter update
* feature: ELBv2: Add TargetInService and TargetDeregistered waiters 
* feature: Pinpoint: This release of the Pinpoint SDK enables App management - create, delete, update operations, Raw Content delivery for APNs and GCM campaign messages and From Address override.
* feature: SES: This update adds information about publishing email open and click events. This update also adds information about publishing email events to Amazon Simple Notification Service (Amazon SNS).

## 2.93.0
* feature: DynamoDB: Add a `wrapNumbers` option to the Document Client to direct the client not to convert number attributes to JavaScript numbers.
* feature: Inspector: Inspector's StopAssessmentRun API has been updated with a new input option - stopAction. This request parameter can be set to either START_EVALUATION or SKIP_EVALUATION. START_EVALUATION (the default value, and the previous behavior) stops the AWS agent data collection and begins the results evaluation for findings generation based on the data collected so far. SKIP_EVALUATION cancels the assessment run immediately, after which no findings are generated.
* feature: SSM: Adds a SendAutomationSignal API to SSM Service. This API is used to send a signal to an automation execution to change the current behavior or status of the execution.

## 2.92.0
* feature: EC2: The CreateDefaultVPC API enables you to create a new default VPC . You no longer need to contact AWS support, if your default VPC has been deleted.
* feature: KinesisAnalytics: Added additional exception types and clarified documentation.

## 2.91.0
* feature: CloudWatch: This release adds high resolution features to CloudWatch, with support for Custom Metrics down to 1 second and Alarms down to 10 seconds.
* feature: EC2: Amazon EC2 Elastic GPUs allow you to easily attach low-cost graphics acceleration to current generation EC2 instances. With Amazon EC2 Elastic GPUs, you can configure the right amount of graphics acceleration to your particular workload without being constrained by fixed hardware configurations and limited GPU selection.

## 2.90.0
* feature: CloudDirectory: Cloud Directory adds support for additional batch operations.
* feature: CloudFormation: AWS CloudFormation StackSets enables you to manage stacks across multiple accounts and regions.

## 2.89.0
* feature: AppStream: Amazon AppStream 2.0 image builders and fleets can now access applications and network resources that rely on Microsoft Active Directory (AD) for authentication and permissions. This new feature allows you to join your streaming instances to your AD, so you can use your existing AD user management tools. 
* feature: EC2: Spot Fleet tagging capability allows customers to automatically tag instances launched by Spot Fleet. You can use this feature to label or distinguish instances created by distinct Spot Fleets. Tagging your EC2 instances also enables you to see instance cost allocation by tag in your AWS bill.

## 2.88.0
* feature: EMR: Amazon EMR now includes the ability to use a custom Amazon Linux AMI and adjustable root volume size when launching a cluster.

## 2.87.0
* feature: Budgets: Update budget Management API's to list/create/update RI_UTILIZATION type budget. Update budget Management API's to support DAILY timeUnit for RI_UTILIZATION type budget.

## 2.86.0
* feature: CognitoIdentityServiceProvider: Allows developers to configure user pools for email/phone based signup and sign-in.
* feature: Lambda: Lambda@Edge lets you run code closer to your end users without provisioning or managing servers. With Lambda@Edge, your code runs in AWS edge locations, allowing you to respond to your end users at the lowest latency. Your code is triggered by Amazon CloudFront events, such as requests to and from origin servers and viewers, and it is ready to execute at every AWS edge location whenever a request for content is received. You just upload your Node.js code to AWS Lambda and Lambda takes care of everything required to run and scale your code with high availability. You only pay for the compute time you consume - there is no charge when your code is not running.

## 2.85.0
* feature: Discovery: Adding feature to the Export API for Discovery Service to allow filters for the export task to allow export based on per agent id.
* feature: EC2: New EC2 GPU Graphics instance

## 2.84.0
* bugfix: S3: Updates S3 client to no longer attempt to determine a bucket's region when a request is aborted.
* feature: APIGateway: Adds support for management of gateway responses.
* feature: EC2: X-ENI (or Cross-Account ENI) is a new feature that allows the attachment or association of Elastic Network Interfaces (ENI) between VPCs in different AWS accounts located in the same availability zone. With this new capability, service providers and partners can deliver managed solutions in a variety of new architectural patterns where the provider and consumer of the service are in different AWS accounts.

## 2.83.0
* feature: AutoScaling: Auto Scaling now supports a new type of scaling policy called target tracking scaling policies that you can use to set up dynamic scaling for your application.

## 2.82.0
* feature: DirectoryService: You can now improve the resilience and performance of your Microsoft AD directory by deploying additional domain controllers. Added UpdateNumberofDomainControllers API that allows you to update the number of domain controllers you want for your directory, and DescribeDomainControllers API that allows you to describe the detailed information of each domain controller of your directory. Also added the 'DesiredNumberOfDomainControllers' field to the DescribeDirectories API output for Microsoft AD.
* feature: KMS: This release of AWS Key Management Service introduces the ability to determine whether a key is AWS managed or customer managed.
* feature: Kinesis: You can now encrypt your data at rest within an Amazon Kinesis Stream using server-side encryption. Server-side encryption via AWS KMS makes it easy for customers to meet strict data management requirements by encrypting their data at rest within the Amazon Kinesis Streams, a fully managed real-time data processing service.
* feature: SSM: Amazon EC2 Systems Manager now expands Patching support to Amazon Linux, Red Hat and Ubuntu in addition to the already supported Windows Server.

## 2.81.0
* bugfix: Core: The SDK will now throw an InvalidHeader error when a header's value is not stringifiable. See #1598.
* bugfix: apigateway: ApiGateway.getExports will no longer override user-supplied 'accepts' with 'application/json'
* feature: CloudWatch: We are excited to announce the availability of APIs and CloudFormation support for CloudWatch Dashboards. You can use the new dashboard APIs or CloudFormation templates to dynamically build and maintain dashboards to monitor your infrastructure and applications. There are four new dashboard APIs - PutDashboard, GetDashboard, DeleteDashboards, and ListDashboards APIs. PutDashboard is used to create a new dashboard or modify an existing one whereas GetDashboard is the API to get the details of a specific dashboard. ListDashboards and DeleteDashboards are used to get the names or delete multiple dashboards respectively. Getting started with dashboard APIs is similar to any other AWS APIs. The APIs can be accessed through AWS SDK or through CLI tools.
* feature: Route53: Bug fix for InvalidChangeBatch exception.

## 2.80.0
* feature: S3: API Update for S3: Adding Object Tagging Header to MultipartUpload Initialization

## 2.79.0
* bugfix: LexRuntime: Adds support for non-file streams as an input to postContent.
* feature: CloudWatchEvents: CloudWatch Events now allows different AWS accounts to share events with each other through a new resource called event bus. Event buses accept events from AWS services, other AWS accounts and PutEvents API calls. Currently all AWS accounts have one default event bus. To send events to another account, customers simply write rules to match the events of interest and attach an event bus in the receiving account as the target to the rule. The PutTargets API has been updated to allow adding cross account event buses as targets. In addition, we have released two new APIs - PutPermission and RemovePermission - that enables customers to add/remove permissions to their default event bus.
* feature: GameLift: Allow developers to download GameLift fleet creation logs to assist with debugging.
* feature: SSM: Adding Resource Data Sync support to SSM Inventory.  New APIs:  * CreateResourceDataSync - creates a new resource data sync configuration,  * ListResourceDataSync - lists existing resource data sync configurations,  * DeleteResourceDataSync - deletes an existing resource data sync configuration. 

## 2.78.0
* feature: ServiceCatalog: Proper tagging of resources is critical to post-launch operations such as billing, cost allocation, and resource management. By using Service Catalog's TagOption Library, administrators can define a library of re-usable TagOptions that conform to company standards, and associate these with Service Catalog portfolios and products. Learn how to move your current tags to the new library, create new TagOptions, and view and associate your library items with portfolios and products. Understand how to ensure that the right tags are created on products launched through Service Catalog and how to provide users with defined selectable tags.

## 2.77.0
* feature: Lambda: The Lambda Invoke API will now throw new exception InvalidRuntimeException (status code 502) for invokes with deprecated runtimes.

## 2.76.0
* feature: CodePipeline: A new API, ListPipelineExecutions, enables you to retrieve summary information about the most recent executions in a pipeline, including pipeline execution ID, status, start time, and last updated time. You can request information for a maximum of 100 executions. Pipeline execution data is available for the most recent 12 months of activity.
* feature: DMS: Added tagging for DMS certificates.
* feature: ELB: Add retry error state to InstanceInService waiter for ElasticLoadBalancer
* feature: Lightsail: This release adds a new nextPageToken property to the result of the GetOperationsForResource API. Developers can now get the next set of items in a list by making subsequent calls to GetOperationsForResource API with the token from the previous call. This release also deprecates the nextPageCount property, which previously returned null (use the nextPageToken property instead). This release also deprecates the customImageName property on the CreateInstancesRequest class, which was previously ignored by the API.
* feature: Route53: This release reintroduces the HealthCheckInUse exception.

## 2.75.0
* feature: DAX: Amazon DynamoDB Accelerator (DAX) is a fully managed, highly available, in-memory cache for DynamoDB that delivers up to a 10x performance improvement - from milliseconds to microseconds - even at millions of requests per second. DAX does all the heavy lifting required to add in-memory acceleration to your DynamoDB tables, without requiring developers to manage cache invalidation, data population, or cluster management.
* feature: Route53: Amazon Route 53 now supports multivalue answers in response to DNS queries, which lets you route traffic approximately randomly to multiple resources, such as web servers. Create one multivalue answer record for each resource and, optionally, associate an Amazon Route 53 health check with each record, and Amazon Route 53 responds to DNS queries with up to eight healthy records.
* feature: S3: Allows forward slashes in Bucket names when using SigV4 to create or retrieve objects. This is to maintain compatibility with behavior when using SigV2. In new code, Buckets should not contain forward slashes. Instead, directories should be part of an object's key.
* feature: SSM: Adding hierarchy support to the SSM Parameter Store API. Added support tor tagging. New APIs: GetParameter - retrieves one parameter, DeleteParameters - deletes multiple parameters (max number 10), GetParametersByPath - retrieves parameters located in the hierarchy. Updated APIs: PutParameter - added ability to enforce parameter value by applying regex (AllowedPattern), DescribeParameters - modified to support Tag filtering.
* feature: WAFRegional: You can now create, edit, update, and delete a new type of WAF rule with a rate tracking component.

## 2.74.0
* feature: WorkDocs: This release provides a new API to retrieve the activities performed by WorkDocs users.

## 2.73.0
* feature: Organizations: Improvements to Exception Modeling

## 2.72.0
* feature: XRay: Add a response time histogram to the services in response of GetServiceGraph API.

## 2.71.0
* feature: DynamoDB: Adds two new functions to the AWS.DynamoDB.Converter namespace: one to convert full DynamoDB items (such as what you might receive for events in a DynamoDB stream) into plain vanilla JavaScript objects and one to convert JavaScript objects back into DynamoDB items
* feature: EC2: Adds API to describe Amazon FPGA Images (AFIs) available to customers, which includes public AFIs, private AFIs that you own, and AFIs owned by other AWS accounts for which you have load permissions.
* feature: ECS: Added support for cpu, memory, and memory reservation container overrides on the RunTask and StartTask APIs.
* feature: Iot: Revert the last release: remove CertificatePem from DescribeCertificate API.
* feature: ServiceCatalog: Added ProvisioningArtifactSummaries to DescribeProductAsAdmin's output to show the provisioning artifacts belong to the product. Allow filtering by SourceProductId in SearchProductsAsAdmin for AWS Marketplace products. Added a verbose option to DescribeProvisioningArtifact to display the CloudFormation template used to create the provisioning artifact.Added DescribeProvisionedProduct API. Changed the type of ProvisionedProduct's Status to be distinct from Record's Status. New ProvisionedProduct's Status are AVAILABLE, UNDER_CHANGE, TAINTED, ERROR. Changed Record's Status set of values to CREATED, IN_PROGRESS, IN_PROGRESS_IN_ERROR, SUCCEEDED, FAILED.

## 2.70.0
* feature: ApplicationAutoScaling: Application Auto Scaling now supports automatic scaling of read and write throughput capacity for DynamoDB tables and global secondary indexes.

## 2.69.0
* feature: ConfigService: With this release AWS Config supports the Amazon CloudWatch alarm resource type.

## 2.68.0
* feature: RDS: API Update for RDS: this update enables copy-on-write, a new Aurora MySQL Compatible Edition feature that allows users to restore their database, and support copy of TDE enabled snapshot cross region.
* feature: S3: Switches S3 to use signatureVersion "v4" by default. To continue using signatureVersion "v2", set the signatureVersion: "v2" option in the S3 service client configuration. Presigned URLs will continue using "v2" by default.

## 2.67.0
* feature: EFS: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: OpsWorks: Tagging Support for AWS OpsWorks Stacks

## 2.66.0
* feature: Iot: In addition to using certificate ID, AWS IoT customers can now obtain the description of a certificate with the certificate PEM.
* feature: Pinpoint: Starting today Amazon Pinpoint adds SMS Text and Email Messaging support in addition to Mobile Push Notifications, providing developers, product managers and marketers with multi-channel messaging capabilities to drive user engagement in their applications. Pinpoint also enables backend services and applications to message users directly and provides advanced user and app analytics to understand user behavior and messaging performance.
* feature: Rekognition: API Update for AmazonRekognition: Adding RecognizeCelebrities API

## 2.65.0
* feature: CodeBuild: Add support to APIs for privileged containers. This change would allow performing privileged operations like starting the Docker daemon inside builds possible in custom docker images.
* feature: Greengrass: AWS Greengrass is software that lets you run local compute, messaging, and device state synchronization for connected devices in a secure way. With AWS Greengrass, connected devices can run AWS Lambda functions, keep device data in sync, and communicate with other devices securely even when not connected to the Internet. Using AWS Lambda, Greengrass ensures your IoT devices can respond quickly to local events, operate with intermittent connections, and minimize the cost of transmitting IoT data to the cloud.

## 2.64.0
* bugfix: S3: Calling send multiple times on an S3 ManagedUpload with leavePartsOnError set to true should no longer result in truncated files being uploaded to S3. Calling send multiple times is not supported with streams.
* feature: Iot: Update client side validation for SalesForce action.

## 2.63.0
* feature: AppStream: AppStream 2.0 Custom Security Groups allows you to easily control what network resources your streaming instances and images have access to. You can assign up to 5 security groups per Fleet to control the inbound and outbound network access to your streaming instances to specific IP ranges, network protocols, or ports.
* feature: AutoScaling: Autoscaling resource model update.
* feature: Iot:  Added Salesforce action to IoT Rules Engine.

## 2.62.0
* feature: KinesisAnalytics: Kinesis Analytics publishes error messages CloudWatch logs in case of application misconfigurations
* feature: WorkDocs: This release includes new APIs to manage tags and custom metadata on resources and also new APIs to add and retrieve comments at the document level.

## 2.61.0
* feature: CodeDeploy: AWS CodeDeploy has improved how it manages connections to GitHub accounts and repositories. You can now create and store up to 25 connections to GitHub accounts in order to associate AWS CodeDeploy applications with GitHub repositories. Each connection can support multiple repositories. You can create connections to up to 25 different GitHub accounts, or create more than one connection to a single account. The ListGitHubAccountTokenNames command has been introduced to retrieve the names of stored connections to GitHub accounts that you have created. The name of the connection to GitHub used for an AWS CodeDeploy application is also included in the ApplicationInfo structure.  Two new fields, lastAttemptedDeployment and lastSuccessfulDeployment, have been added to DeploymentGroupInfo to improve the handling of deployment group information in the AWS CodeDeploy console. Information about these latest deployments can also be retrieved using the GetDeploymentGroup and BatchGetDeployment group requests. Also includes a region update  (us-gov-west-1).
* feature: CognitoIdentityServiceProvider: Added support within Amazon Cognito User Pools for 1) a customizable hosted UI for user sign up and sign in and 2) integration of external identity providers.
* feature: ELBv2: Update the existing DescribeRules API to support pagination.

## 2.60.0
* bugfix: Core: Fixes issue where some TimeStamp shapes had an incorrect timestampFormat. Specifically affects S3.putBucketLifecycleConfiguration when using Date fields.
* feature: RDS: Amazon RDS customers can now easily and quickly stop and start their DB instances.

## 2.59.0
* bugfix: S3: Update ManagedUploader body verification to allow empty strings
* feature: CloudDirectory: Cloud Directory has launched support for Typed Links, enabling customers to create object-to-object relationships that are not hierarchical in nature. Typed Links enable customers to quickly query for data along these relationships. Customers can also enforce referential integrity using Typed Links, ensuring data in use is not inadvertently deleted.

## 2.58.0
* feature: AppStream: Support added for persistent user storage, backed by S3.
* feature: Rekognition: Updated the CompareFaces API response to include orientation information, unmatched faces, landmarks, pose, and quality of the compared faces.

## 2.57.0
* feature: IAM: The unique ID and access key lengths were extended from 32 to 128
* feature: STS: The unique ID and access key lengths were extended from 32 to 128.
* feature: StorageGateway: Two Storage Gateway data types, Tape and TapeArchive, each have a new response element, TapeUsedInBytes. This element helps you manage your virtual tapes. By using TapeUsedInBytes, you can see the amount of data written to each virtual tape.

## 2.56.0
* feature: DMS: This release adds support for using Amazon S3 and Amazon DynamoDB as targets for database migration, and using MongoDB as a source for database migration. For more information, see the AWS Database Migration Service documentation.

## 2.55.0
* bugfix: ReactNative: Requests will always have a Content-Type header if they also have a body. Works around an issue caused by React Native's Android XMLHttpRequest implementation that requires the Content-Type header to be present if there is a request body.
* feature: ResourceGroupsTaggingAPI: You can now specify the number of resources returned per page in GetResources operation, as an optional parameter, to easily manage the list of resources returned by your queries.

## 2.54.0
* feature: Athena: This release adds support for Amazon Athena. Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.
* feature: Lightsail: This release adds new APIs that make it easier to set network port configurations on Lightsail instances. Developers can now make a single request to both open and close public ports on an instance using the PutInstancePublicPorts operation.

## 2.53.0
* feature: Polly: Amazon Polly adds new German voice "Vicki"

## 2.52.0
* feature: CodeDeploy: This release introduces the previousRevision field in the responses to the GetDeployment and BatchGetDeployments actions. previousRevision provides information about the application revision that was deployed to the deployment group before the most recent successful deployment.  Also, the fileExistsBehavior parameter has been added for CreateDeployment action requests. In the past, if the AWS CodeDeploy agent detected files in a target location that weren't part of the application revision from the most recent successful deployment, it would fail the current deployment by default. This new parameter provides options for how the agent handles these files: fail the deployment, retain the content, or overwrite the content.
* feature: GameLift: Allow developers to specify how metrics are grouped in CloudWatch for their GameLift fleets. Developers can also specify how many concurrent game sessions activate on a per-instance basis.
* feature: Inspector: Adds ability to produce an assessment report that includes detailed and comprehensive results of a specified assessment run.

## 2.51.0
* feature: SSM: UpdateAssociation API now supports updating document name and targets of an association. GetAutomationExecution API can return FailureDetails as an optional field to the StepExecution Object, which contains failure type, failure stage as well as other failure related information for a failed step.

## 2.50.0
* bugfix: ReactNative: Fixes issue where binary responses were empty in iOS (e.g. s3.getObject)
* feature: ELB: Add a new API to allow customers to describe their account limits, such as load balancer limit, target group limit etc.
* feature: ELBv2: Add a new API to allow customers to describe their account limits, such as load balancer limit, target group limit etc.
* feature: LexModelBuildingService: Releasing new DeleteBotVersion, DeleteIntentVersion and DeleteSlotTypeVersion APIs.
* feature: Organizations: AWS Organizations APIs that return an Account object now include the email address associated with the account’s root user.
* bugfix: Request: Updates node.js request handling to obey socket read timeouts after response headers have been received. Previously timeouts were being ignored once headers were received, sometimes causing connections to hang.

## 2.49.0
* feature: ECS: Exposes container instance registration time in ECS:DescribeContainerInstances.
* feature: Lambda: Support for UpdateFunctionCode DryRun option
* feature: MarketplaceEntitlementService: AWS Marketplace Entitlement Service enables AWS Marketplace sellers to determine the capacity purchased by their customers.

## 2.48.0
* feature: CloudFormation: Adding back the removed waiters and paginators.

## 2.47.0
* feature: CloudFormation: API update for CloudFormation: New optional parameter ClientRequestToken which can be used as an idempotency token to safely retry certain operations as well as tagging StackEvents.
* feature: RDS: The DescribeDBClusterSnapshots API now returns a SourceDBClusterSnapshotArn field which identifies the source DB cluster snapshot of a copied snapshot.
* feature: React Native: Adds support for running the SDK in React Native. See the README for instructions.
* feature: Rekognition: Fix for missing file type check
* feature: SQS: Adding server-side encryption (SSE) support to SQS by integrating with AWS KMS; adding new queue attributes to SQS CreateQueue, SetQueueAttributes and GetQueueAttributes APIs to support SSE.
* feature: Snowball: The Snowball API has a new exception that can be thrown for list operation requests.

## 2.46.0
* bugfix: SharedIniFileCredentials: This fix reverts a regression introduced in version 2.44.0 in which the value returned by os.homedir would be used in preference over the value of the HOME environment variable
* feature: RDS: With Amazon Relational Database Service (Amazon RDS) running MySQL or Amazon Aurora, you can now authenticate to your DB instance using IAM database authentication.
* feature: RDS: Adds AWS.RDS.Signer class to generate auth tokens for connecting to a database.

## 2.45.0
* bugfix: Promise: Fixes an issue introduced in v2.44.0 where payload members on some CloudFront and S3 operations weren't hoisted when using promises. This issue was introduced in and could affect users that were accessing fields on a response that weren't documented, but were available for backwards compatibility.
* bugfix: Request: Make `$response` property of resolved promise value non-enumerable to prevent serialization errors
* feature: AppStream: The new feature named "Default Internet Access" will enable Internet access from AppStream 2.0 instances - image builders and fleet instances. Admins will check a flag either through AWS management console for AppStream 2.0 or through API while creating an image builder or while creating/updating a fleet.
* feature: Kinesis: Adds a new waiter, StreamNotExists, to Kinesis.

## 2.44.0
* feature: DeviceFarm: API Update for AWS Device Farm: Support for Deals and Promotions 
* feature: ELBv2: Adding LoadBalancersDeleted waiter for Elasticloadbalancingv2
* feature: EnvironmentVariable: Load config from ~/.aws/config if AWS_SDK_LOAD_CONFIG is set
* feature: EnvironmentVariable: Add support for specifying the location of the shared config file via the AWS_CONFIG_FILE environment variable. This variable is only honored if AWS_SDK_LOAD_CONFIG is set to a truthy value.
* feature: EnvironmentVariable: Add support for the AWS_SHARED_CREDENTIALS_FILE environment variable if AWS_SDK_LOAD_CONFIG is set
* feature: Promises: Binds response object to the data object with which successful request promises are resolved

## 2.43.0
* feature: APIGateway: Add support for "embed" property.
* feature: CodeStar: AWS CodeStar is a cloud-based service for creating, managing, and working with software development projects on AWS. An AWS CodeStar project creates and integrates AWS services for your project development toolchain. AWS CodeStar also manages the permissions required for project users.
* feature: EC2: Adds support for creating an Amazon FPGA Image (AFI) from a specified design checkpoint (DCP).
* feature: IAM: This changes introduces a new IAM role type, Service Linked Role, which works like a normal role but must be managed via services' control. 
* feature: Lambda: Lambda integration with CloudDebugger service to enable customers to enable tracing for the Lambda functions and send trace information to the CloudDebugger service.
* feature: LexModelBuildingService: Amazon Lex is a service for building conversational interfaces into any application using voice and text.
* feature: Polly: API Update for Amazon Polly: Add support for speech marks
* feature: Rekognition: Given an image, the API detects explicit or suggestive adult content in the image and returns a list of corresponding labels with confidence scores, as well as a taxonomy (parent-child relation) for each label.

## 2.42.0
* bugfix: Parser: Makes casting payload blobs to strings an exceptional behavior rather than the default
* feature: Lambda: You can use tags to group and filter your Lambda functions, making it easier to analyze them for billing allocation purposes. For more information, see Tagging Lambda Functions.  You can now write or upgrade your Lambda functions using Python version 3.6. For more information, see Programming Model for Authoring Lambda Functions in Python. Note: Features will be rolled out in the US regions on 4/19.

## 2.41.0
* feature: APIGateway: API Gateway request validators
* feature: Batch: API Update for AWS Batch: Customer provided AMI for MANAGED Compute Environment 
* feature: GameLift: Allows developers to utilize an improved workflow when calling our Queues API and introduces a new feature that allows developers to specify a maximum allowable latency per Queue.
* feature: OpsWorks: Cloudwatch Logs agent configuration can now be attached to OpsWorks Layers using CreateLayer and UpdateLayer. OpsWorks will then automatically install and manage the CloudWatch Logs agent on the instances part of the OpsWorks Layer.

## 2.40.0
* feature: Redshift: This update adds the GetClusterCredentials API which is used to get temporary login credentials to the cluster. AccountWithRestoreAccess now has a new member AccountAlias, this is the identifier of the AWS support account authorized to restore the specified snapshot. This is added to support the feature where the customer can share their snapshot with the Amazon Redshift Support Account without having to manually specify the AWS Redshift Service account ID on the AWS Console/API.

## 2.39.0
* feature: ElastiCache: ElastiCache added support for testing the Elasticache Multi-AZ feature with Automatic Failover.
* feature: Http: Adds a connectTimeout option that allows slow-to-establish socket connections to be quickly abandoned

## 2.38.0
* feature: CloudWatch: Amazon Web Services announced the immediate availability of two additional alarm configuration rules for Amazon CloudWatch Alarms. The first rule is for configuring missing data treatment. Customers have the options to treat missing data as alarm threshold breached, alarm threshold not breached, maintain alarm state and the current default treatment. The second rule is for alarms based on percentiles metrics that can trigger unnecassarily if the percentile is calculated from a small number of samples. The new rule can treat percentiles with low sample counts as same as missing data. If the first rule is enabled, the same treatment will be applied when an alarm encounters a percentile with low sample counts.

## 2.37.0
* feature: LexRuntime: Adds support to PostContent for speech input

## 2.36.0
* feature: CloudDirectory: ListObjectAttributes now supports filtering by facet.

## 2.35.0
* feature: CloudFormation: Adding paginators for ListExports and ListImports
* feature: CloudFront: Amazon CloudFront now supports user configurable HTTP Read and Keep-Alive Idle Timeouts for your Custom Origin Servers
* feature: ResourceGroupsTaggingAPI: Resource Groups Tagging APIs can help you organize your resources and enable you to simplify resource management, access management, and cost allocation.
* feature: StorageGateway: File gateway mode in AWS Storage gateway provides access to objects in S3 as files on a Network File System (NFS) mount point. Once a file share is created, any changes made externally to the S3 bucket will not be reflected by the gateway. Using the cache refresh feature in this update, the customer can trigger an on-demand scan of the keys in their S3 bucket and refresh the file namespace cached on the gateway. It takes as an input the fileShare ARN and refreshes the cache for only that file share. Additionally there is new functionality on file gateway that allows you configure what squash options they would like on their file share, this allows a customer to configure their gateway to not squash root permissions. This can be done by setting options in NfsOptions for CreateNfsFileShare and UpdateNfsFileShare APIs.

## 2.34.0
* features: Batch: Customers can now provide a retryStrategy as part of the RegisterJobDefinition and SubmitJob API calls.
* features: EC2: Customers can now tag their Amazon EC2 Instances and Amazon EBS Volumes at the time of their creation.

## 2.33.0
* feature: core: Adds support for 'v4' and 'v4-unsigned-body' authtype traits.
* bugfix: ManagedUpload: Ensures multi-part upload locations are URI-decoded to match single-part upload locations.

## 2.32.0
* feature: S3: Adds a means of specifying tags to apply to objects of any size uploaded with AWS.S3.ManagedUploader
* feature: ApplicationAutoScaling: Application AutoScaling is launching support for a new target resource (AppStream 2.0 Fleets) as a scalable target.

## 2.31.0
* feature: DynamoDB: Adds ability to customize retry delays for DynamoDB. This previously worked for all services except DynamoDB. Also adds jitter to DynamoDB retries. See `AWS.Config.retryDelayOptions` for more information.
* feature: Waiter: Allow customization of a waiter using a special `$waiter` key
* feature: Lambda: Adds support for new runtime Node.js v6.10 for AWS Lambda service. :tada:
* feature: ELBv2: Adding waiters for Elastic Load Balancing V2
* feature: Discovery: Adds export configuration options to the API.

## 2.30.0
* feature: DynamoDb: Allow objects with inheritance chains to be converted to MapAttributeValues instead of undefined
* bugfix: CredentialsError: Update AWS.Config.getCredentials to overwrite the name (in addition to message and code) of errors thrown by underlying credential providers.

## 2.29.0
* feature: protocol: The SDK can now support JSON-value string shapes in headers
* feature: Pinpoint: Added ability to segment endpoints by user attributes in addition to endpoint attributes.
* feature: Pinpoint: Added functionality to publish raw app analytics and campaign events data as events streams to Kinesis and Kinesis Firehose.
* feature: ELBv2: Adding waiters for LoadBalancers in ELBv2.
* feature: MarketplaceCommerceAnalytics: This update adds a new data set, us_sales_and_use_tax_records, which enables AWS Marketplace sellers to programmatically access to their U.S. Sales and Use Tax report data.

## 2.28.0
* feature: DeviceFarm: Network shaping allows users to simulate network connections and conditions while testing their Android, iOS, and web apps with AWS Device Farm.
* feature: CloudWatchEvents: This update extends Target Data Type for configuring Target behavior during invocation.

## 2.27.0
* bugfix: TemporaryCredentials: Ensure master credentials are not expired before using them to refresh temporary credentials
* feature: CodeDeploy: Add paginators for Codedeploy
* feature: EMR: This release includes support for instance fleets in Amazon EMR

## 2.26.0
* feature: APIGateway: API Gateway has added support for ACM certificates on custom domain names. Both Amazon-issued certificates and uploaded third-part certificates are supported.
* feature: CloudDirectory: Introduces a new Cloud Directory API that enables you to retrieve all available parent paths for any type of object (a node, leaf node, policy node, and index node) in a hierarchy.

## 2.25.0
* feature: WorkDocs: Amazon WorkDocs API provides full administrator level access to WorkDocs site resources, allowing developers to integrate their applications to manage WorkDocs users, content and permissions programmatically.

## 2.24.0
* feature: RDS: Add support to using encrypted clusters as cross-region replication masters. Update CopyDBClusterSnapshot API to support encrypted cross region copy of Aurora cluster snapshots.

## 2.23.0
* feature: Budgets: When creating or editing a budget via the AWS Budgets API you can define notifications that are sent to subscribers when the actual or forecasted value for cost or usage exceeds the notificationThreshold associated with the budget notification object. Starting today, the maximum allowed value for the notificationThreshold was raised from 100 to 300. This change was made to give you more flexibility when setting budget notifications.
* feature: OpsWorksCM: OpsWorks for Chef Automate has added a new field "AssociatePublicIpAddress" to the CreateServer request, "CloudFormationStackArn" to the Server model and "TERMINATED" server state.

## 2.22.0
* bugfix: MechanicalTurkRequester: Rename MechanicalTurkRequester to MTurk

## 2.21.0
* feature: DynamoDB: Time to Live (TTL) is a feature that allows you to define when items in a table expire and can be purged from the database, so that you don't have to track expired data and delete it manually. With TTL enabled on a DynamoDB table, you can set a timestamp for deletion on a per-item basis, allowing you to limit storage usage to only those records that are relevant.
* feature: DynamoDBStreams: Time to Live (TTL) is a feature that allows you to define when items in a table expire and can be purged from the database, so that you don't have to track expired data and delete it manually. With TTL enabled on a DynamoDB table, you can set a timestamp for deletion on a per-item basis, allowing you to limit storage usage to only those records that are relevant.
* feature: IAM: This release adds support for AWS Organizations service control policies (SCPs) to SimulatePrincipalPolicy operation. If there are SCPs associated with the simulated user's account, their effect on the result is captured in the OrganizationDecisionDetail element in the EvaluationResult.
* feature: MechanicalTurkRequester: Amazon Mechanical Turk is a web service that provides an on-demand, scalable, human workforce to complete jobs that humans can do better than computers, for example, recognizing objects in photos.
* feature: Organizations: AWS Organizations is a web service that enables you to consolidate your multiple AWS accounts into an organization and centrally manage your accounts and their resources.

## 2.20.0
* feature: ES: Added three new API calls to expose Amazon Elasticsearch imposed limits.

## 2.19.0
* bugfix: XHR: Fixes an issue where the callback provided to an operation would not fire if a request was aborted after being sent. The bug only affected the browser SDK.
* feature: S3: Added an instance method to S3 clients to create POST form data with presigned upload policies
* feature: DynamoDB: Expose DynamoDB DocumentClient marshaller/unmarshaller as AWS.DynamoDB.Converter

## 2.18.0
* feature: GameLift: Allow developers to configure global queues for creating GameSessions. Allow PlayerData on PlayerSessions to store player-specific data.
* feature: Route53: Added support for operations CreateVPCAssociationAuthorization and DeleteVPCAssociationAuthorization to throw a ConcurrentModification error when a conflicting modification occurs in parallel to the authorizations in place for a given hosted zone.
* feature: ElasticBeanstalk: Elastic Beanstalk adds support for creating and managing custom platform.

## 2.17.0
* bugfix: TypeScript: Enable the configuration credentials to be nulled so that the global config is not used.
* feature: EC2: Added the billingProduct parameter to the RegisterImage API.

## 2.16.0
* feature: DirectConnect: This update will introduce the ability for Direct Connect customers to take advantage of Link Aggregation (LAG). This allows you to bundle many individual physical interfaces into a single logical interface, referred to as a LAG. This makes administration much simpler as the majority of configuration is done on the LAG while you are free to add or remove physical interfaces from the bundle as bandwidth demand increases or decreases. A concrete example of the simplification added by LAG is that customers need only a single BGP session as opposed to one session per physical connection.

## 2.15.0
* feature: CognitoIdentity: Allows createIdentityPool and updateIdentityPool API to set server side token check value on identity pool.
* feature: ConfigService: AWS Config now supports a new test mode for the PutEvaluations API. Set the TestMode parameter to true in your custom rule to verify whether your AWS Lambda function will deliver evaluation results to AWS Config. No updates occur to your existing evaluations, and evaluation results are not sent to AWS Config.

## 2.14.0
* feature: KMS: This release of AWS Key Management Service introduces the ability to tag keys. Tagging keys can help you organize your keys and track your KMS costs in the cost allocation report. This release also increases the maximum length of a key ID to accommodate ARNs that include a long key alias.

## 2.13.0
* feature: Ec2: Adds support for the new Modify Volumes apis.

## 2.12.0
* feature: StorageGateway: File gateway mode in AWS Storage gateway provides access to objects in S3 as files on a Network File System (NFS) mount point. This is done by creating Nfs file shares using existing APIs CreateNfsFileShare. Using the feature in this update, the customer can restrict the clients that have read/write access to the gateway by specifying the list of clients as a list of IP addresses or CIDR blocks. This list can be specified using the API CreateNfsFileShare while creating new file shares, or UpdateNfsFileShare while update existing file shares. To find out the list of clients that have access, the existing API DescribeNfsFileShare will now output the list of clients that have access.

## 2.11.0
* bugfix: TypeScript: Add `endpoint` property to AWS.S3 instance declaration.
* feature: EC2: This feature allows customers to associate an IAM profile to running instances that do not have any.
* feature: Rekognition: DetectFaces and IndexFaces operations now return an estimate of the age of the face as an age range.

## 2.10.0
* bugfix: JSON: Fixes issue caused when trying to unmarshall null binary shapes.
* bugfix: TypeScript: Add `credentialProvider` as an optional parameter of `ConfigurationOptions`.
* feature: LexRuntime: Amazon Lex is a service for building conversational interactions into any application using voice or text.

## 2.9.0
* feature: EC2: Adds instance health check functionality to replace unhealthy EC2 Spot fleet instances with fresh ones
* feature: CloudDirectory: Amazon Cloud Directory is a highly scalable, high performance, multi-tenant directory service in the cloud. Its web-based directories make it easy for you to organize and manage application resources such as users, groups, locations, devices, policies, and the rich relationships between them.
* feature: CodeDeploy: This release of AWS CodeDeploy introduces support for blue/green deployments. In a blue/green deployment, the current set of instances in a deployment group is replaced by new instances that have the latest application revision installed on them. After traffic is rerouted behind a load balancer to the replacement instances, the original instances can be terminated automatically or kept running for other uses.
* feature: RDS: Added support for the `ModifyDBSnapshot` and `ModifyDBSnapshotMessage` operations

## 2.8.0
* bugfix: RDS: Fixes issue wherein the wrong parameter name was used for cross region presigned urls.
* feature: ELBv2: Application Load Balancers now support native Internet Protocol version 6 (IPv6) in an Amazon Virtual Private Cloud (VPC). With this ability, clients can now connect to the Application Load Balancer in a dual-stack mode via either IPv4 or IPv6.
* feature: RDS: Adds cross region read replica copying.

## 2.7.28
* feature: CognitoIdentityCredentials: Adds `clientConfig` as an optional parameter to the `CognitoIdentityCredentials` constructor. This parameter can be used to pass in client configuration to the underlying service clients.
* feature: TemporaryCredentials: Allows passing of master credentials to the TemporaryCredentials provider.
* feature: CodeCommit: Added new API to list the different files between 2 commits
* feature: ECS: Amazon ECS now supports a state for container instances that can be used to drain a container instance in preparation for maintenance or cluster scale down.

## 2.7.27
* bugfix: Performance: This change reverts a request body cast in the node HTTP handler that caused a performance regression.
* feature: ACM: Updated response elements for DescribeCertificate API in support of managed renewal.

## 2.7.26
* feature: EC2: Amazon EC2 Spot instances now support dedicated tenancy, providing the ability to run Spot instances single-tenant manner on physically isolated hardware within a VPC to satisfy security, privacy, or other compliance requirements. Dedicated Spot instances can be requested using RequestSpotInstances and RequestSpotFleet.

## 2.7.25
* feature: RDS: Updates AWS.RDS API to the latest version.

## 2.7.24
* bugfix: HTTP: Ensure that buffers are not created with Buffer.from in node 4.0-4.4
* bugfix: core: Deprecate v2.7.23

## 2.7.23
* bugfix: S3: Convert string bodies to buffers to ensure correct encoding is used
* feature: DynamoDB: Adds support for tagging tables and indexes.

## 2.7.22
* feature: CUR: The AWS Cost and Usage Report Service API allows you to enable and disable the Cost & Usage report, as well as modify the report name, the data granularity, and the delivery preferences.
* bugfix: DynamoDB.DocumentClient: Allows objects created using Object.create(null) to be properly serialized by the DDB document client.

## 2.7.21
* feature: ConfigService: Updates putConfigRule to support using/writing rules based on the OversizedConfigurationItemChangeNotification message type.
* feature: MarketplaceCommerceAnalytics: Added support for data set disbursed_amount_by_instance_hours, with historical data available starting 2012-09-04. New data is published to this data set every 30 days.
* bugfix: DynamoDB.DocumentClient: Fixes issue where empty strings in nested members were not removed when convertEmptyValues was set.
* bugfix: CognitoIdentityCredentials: Fixes issue where the cached identity id would sometimes not be retrieved when SDK is run while offline.

## 2.7.20
* feature: CodeDeploy: CodeDeploy supports IAM Session Arns in addition to IAM User Arns for on premise host authentication.
* feature: ECS: Amazon EC2 Container Service (ECS) now supports the ability to customize the placement of tasks on container instances.

## 2.7.19
* feature: APIGateway: This update introduces two new operations used to dynamically discover SDK types and what configuration each type accepts.
* feature: ElasticBeanstalk: Adds a new feature for managing Application Version Lifecycle.
* feature: IAM: Adds service-specific credentials to IAM service to make it easier to onboard CodeCommit customers. These are username/password credentials that work with a single service.

## 2.7.18
* feature: Rekognition: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: EC2: Adds cross region encrypted snapshot copying (CopyDBSnapshot).
* feature: ECR: Amazon ECR now implements Docker Image Manifest V2, Schema 2 providing the ability to use multiple tags per image, support for storing Windows container images, and compatibility with the Open Container Initiative (OCI) image format. With this update, customers can also add tags to an image via PutImage and delete tags using BatchDeleteImage.

## 2.7.17
* bugfix: Promises: Fixes issue introduced in v2.6.12. Calling AWS.config.setPromisesDependency(null) will once again force the SDK to use native promises if they are available.
* feature: Firehose: The processing feature enables users to process and modify records before Amazon Firehose delivers them to destinations.
* feature: StorageGateway: File gateway is a new mode in the AWS Storage Gateway that support a file interface into S3, alongside the current block-based volume and VTL storage. File gateway combines a service and virtual software appliance, enabling you to store and retrieve objects in Amazon S3 using industry standard file protocols such as NFS. The software appliance, or gateway, is deployed into your on-premises environment as a virtual machine (VM) running on VMware ESXi. The gateway provides access to objects in S3 as files on a Network File System (NFS) mount point.

## 2.7.16
* feature: DocumentClient: Add a constructor option to convert empty strings, sets, and binary strings to a Dynamo NULL typed field
* feature: Discovery: Adds new APIs to group discovered servers into Applications with get summary and neighbors. Includes additional filters for ListConfigurations and DescribeAgents API.
* feature: CognitoIdentity: Added fine-grained role-based access control for Cognito identity pools. Developers can configure an identity pool to get the IAM role from an authenticated user's token, or they can configure rules that will map a user to a different role

## 2.7.15
* bugfix: Buffer: Update base64 encode/decode to use Buffer.fill when available and throw an error if a number is provided.
* bugfix: XRay: Add X-Amzn-Trace-Id to list of unsigned headers to prevent signature mismatch errors if the header value is modified while the request is in flight.
* feature: Cognito: Add new regions and endpoints for Amazon Cognito Identity, Amazon Cognito Sync, and Amazon Cognito Identity Provider.
* feature: CognitoIdentityServiceProvider: User Pools now offers groups as an easy way to manage users and their permissions.
* feature: SSM: Add support for Patch Baseline and Patch Compliance APIs

## 2.7.14
* feature: Batch: AWS Batch is a batch computing service that lets customers define queues and compute environments and then submit work as batch jobs.
* feature: DMS: Adds support for SSL enabled Oracle endpoints and task modification.
* feature: CloudWatchLogs: Amazon CloudWatch announces detailed billing to CloudWatch Logs. You can now get usage and cost per log group. You can also add tags on your log groups to get a fine-grained view on cost for logs across business dimension such as cost center, application name, AWS services such as Lambda, CloudTrail, ECS, and other. Up to 50 tags can be added to each log group.

## 2.7.13
* feature: CloudFront:  Add lambda function associations to cache behaviors.
* feature: RDS: Add cluster create data to DBCluster APIs.
* feature: WAFRegional: With this new feature, customers can use AWS WAF directly on Application Load Balancers in a VPC within available regions to protect their websites and web services from malicious attacks such as SQL injection, Cross Site Scripting, bad bots, etc.

## 2.7.12
* feature: S3: Add the Version ID field to the Get and Put object tagging operations.

## 2.7.11
* bugfix: TypeScript: Exposes typings for classes that live on service namespaces (i.e. DynamoDB.DocumentClient). Also exposes interfaces off of service namespaces to allow easier migration from some 3rd party typings. Interfaces will continue to be exposed via Service.Types as well.
* bugfix: TypeScript: Removes remaining `reference` comments from definitions.
* feature: ConfigService: Increases the number of config rules for all accounts from 25 to 50.
* feature: EC2: Adds T2.xlarge, T2.2xlarge, and R4 instance types.

## 2.7.10
* feature: APIGateway: You can now publish your APIs on Amazon API Gateway as products on the AWS Marketplace. Use the SDK to associate your APIs on API Gateway with Marketplace Product Codes. API Gateway will then send metering data to the Marketplace Metering Service on your behalf. Also, API Gateway now supports documenting your API.
* feature: Appstream: Announcing Amazon AppStream 2.0 - a secure, fully managed desktop application streaming service that provides users instant access to their apps from a web browser.
* feature: CodeBuild: AWS CodeBuild is a fully-managed build service in the cloud. CodeBuild compiles source code, runs tests, and produces packages that are ready to deploy. CodeBuild eliminates the need to provision, manage, and scale your own build servers. CodeBuild scales continuously and processes multiple builds concurrently, so your builds are never waiting in a queue. You can get started quickly with CodeBuild’s prepackaged build environments, or you can use custom build environments to use your own build tools. With CodeBuild, you only pay by the minute.
* feature: DirectConnect: API Update for IPv6 for Direct Connect.
* feature: EC2: Adds IPv6 Support for EC2 and new F1 Instance types.
* feature: ElasticBeanstalk: Integrates AWS CodeBuild into ElasticBeanstalk.
* feature: Health: When your business is counting on the performance of your cloud solutions, having relevant and timely insights into events impacting your AWS resources is essential. The AWS Health API serves as the primary source for you to receive personalized information related to your AWS infrastructure, guiding your through scheduled changes, and accelerating the troubleshooting of issues impacting your AWS resources and accounts. At launch, the APIs will be available to Business and Enterprise Support customers.
* feature: Lambda: Adds new API `getAccountSettings`, dotnetcore 1.0 runtime support, DeadLetterConfig, and event source mappings with kinesis streams.
* feature: OpsWorksCM: AWS OpsWorks for Chef Automate gives customers a single tenant Chef Automate server. The Chef Automate server is fully managed by AWS and supports automatic backup, restore and upgrade operations.
* feature: Pinpoint: Amazon Pinpoint makes it easy to run targeted campaigns to improve user engagement. Pinpoint helps you understand your users behavior, define who to target, what messages to send, when to deliver them, and tracks the results of the campaign.
* feature: Shield: AWS Shield is a managed Distributed Denial of Service (DDoS) protection for web applications running on AWS.
* feature: SSM: Amazon EC2 Systems Manager is a flexible and easy to use management service that enables enterprises to securely manage and administer their workloads running on-premises or in the AWS cloud, using a single unified experience. These tasks include collecting system inventory, AWSmaintaining consistent state, ad hoc remote execution, automating imaging creation, applying OS patches, and managing configuration parameters.
* feature: StepFunctions: Adds support for the AWS Step Functions API.
* feature: XRay: AWS X-Ray helps developers analyze and debug distributed applications. With X-Ray, you can understand how your application and its underlying services are performing to identify and troubleshoot the root cause of performance issues and errors.

## 2.7.9
* feature: Polly: Adds `AWS.Polly.Presigner` to create presigned urls for `synthesizeSpeech`.
* feature: Polly: Amazon Polly is a service that turns text into lifelike speech, making it easy to develop applications that use high-quality speech to increase engagement and accessibility. With Amazon Polly the developers can build speech-enabled apps that work in multiple geographies.
* feature: Lightsail: An extremely simplified VM creation and management service.
* feature: Rekognition: Amazon Rekognition is a service that makes it easy to add image analysis to your applications. With Rekognition, you can detect objects, scenes, and faces in images. You can also search and compare faces. Rekognition’s API enables you to quickly add sophisticated deep learning-based visual search and image classification to your applications. 
* feature: Snowball: This release of AWS Snowball introduces a new job type, new APIs, and the new AWS Snowball Edge device to support local compute and storage use cases. The local compute is AWS Lambda powered by AWS Greengrass, and the local storage is compatible with Amazon S3. Each 100 TB Snowball Edge can use the storage and compute power of the AWS cloud locally in places where connecting to the internet may not be an option. Additionally, Snowball Edges can be used in clusters for applications that require greater data durability.

## 2.7.8
* feature: core: The SDK will now automatically provide a version 4 UUID for top-level operation parameters that are modeled with the `idempotencyToken` flag. Users may continue to provide their own tokens.
* feature: S3: Updates the AWS.S3 API to the latest version.

## 2.7.7
* feature: CloudFormation: List-imports API is to list all stacks of user's namespace that are using a specific output.
* feature: Glacier: Allow customers to retrieve their data with different tiers.
* feature: Route53: Expand current IPAddress field to accept IPv6 address.
* feature: S3: Allow customers to specify different restore tiers when accessing their data.

## 2.7.6
* feature: CloudTrail: This release of AWS CloudTrail supports configuring your trail with event selectors. Use event selectors to specify the type of events that you want your trails to log. You can configure event selectors to log read-only, write-only, or all events. CloudTrail supports logging Amazon S3 object level APIs such as GetObject, DeleteObject, and PutObject. You can configure event selectors for your trail to log object level operations.
* feature: ECS: ECS will include a new field named `version` in API responses relating to tasks and container instances. Version is a number that increments every time a change has been made to the associated resource. Users replicating their ECS resource state can use the version field reported by the ECS APIs to determine if their local state is fresh.

## 2.7.5
* bugfix: TypeScript: Stubs DOM interfaces and removes type reference to node.
* feature: ElasticTranscoder: Support for multiple media input files that can be stitched together.
* feature: Lambda: Adds support for Environment variables.
* feature: Gamelift: Provide the ability to remote access into GameLift managed servers.
* feature: EMR: Automatic Scaling of EMR clusters based on metrics. Adds support for cancelling a pending Amazon EMR step.
* feature: ApplicationAutoScaling: Adds support for a new target resource (EMR Instance Groups) as a scalable target.

## 2.7.4
* feature: MarketplaceMetering: Allows third parties to send metering records.
* feature: SQS: Updates the latest version of the SQS API.
* feature: CloudWatch: Amazon CloudWatch now supports Percentiles as a statistical function.
* feature: APIGateway: Allows defining an encoding for the API per content type in order to support 'binary' use case.

## 2.7.3
* feature: Route53: Adds support for cross account VPC association.
* feature: ServiceCatalog: This release enables Service Catalog users to perform administer operations via API.

## 2.7.2
* feature: ElastiCache: Additional parameter to 2 create apis to provide an auth Token for Redis.
* feature: DirectoryService: Adds support for SchemaExtensions.
* feature: Kinesis: Adds DescribeLimits API which displays customer's current shard limit and the number of open shards that are being used. Also adds a 'display stream creation timestamp' feature to DescribeStream API.

## 2.7.1
* feature: CognitoIdentityServiceProvider: Adds schema attributes to CreateUserPool.
* bugfix: TypeScript: Updates definitions to work when `noImplicitAny` and `strictNullChecks` are set to `true`.

## 2.7.0
* feature: TypeScript: Adds typescript definition files to the SDK.
* feature: CloudWatchLogs: Amazon CloudWatch Metrics to Logs is a capability that helps pivot from your logs-extracted metrics directly to the corresponding logs.

## 2.6.15
* feature: DirectConnect: AWS Direct Connect provides three new APIs to support basic tagging on Direct Connect resources.

## 2.6.14
* feature: SES: Amazon Simple Email Service (Amazon SES) now enables you to track your bounce, complaint, delivery, sent, and rejected email metrics with fine-grained granularity.

## 2.6.13
* feature: CloudFormation: Adding ResourcesToSkip parameter to ContinueUpdateRollback API, adding support for ListExports, new ChangeSet types and Transforms.

## 2.6.12
* feature: CredentialProviderChain: Adds promise support for the `resolve` method on the AWS.CredentialProviderChain class. Corresponding promise method is called `resolvePromise`.
* feature: Credentials: Adds promise support for the `get` and `refresh` methods of the AWS.Credentials class. Corresponding promise methods are called `getPromise` and `refreshPromise`.
* feature: ManagedUpload: Adds promise support for S3.ManagedUpload. Calling `s3.upload(params).promise()` will return a promise.
* feature: SMS: AWS Server Migration Service (SMS) is an agentless service which makes it easier and faster for you to migrate thousands of on-premises workloads to AWS. AWS SMS allows you to automate, schedule, and track incremental replications of live server volumes, making it easier for you to coordinate large-scale server migrations.

## 2.6.11
* feature: Budgets: Adds the AWS Budgets service API via AWS.Budgets.

## 2.6.10
* feature: CloudFront: Ability to use Amazon CloudFront to deliver your content both via IPv6 and IPv4 using HTTP/HTTPS.
* feature: IoT: Updates IoT API to the latest available version.
* feature: RDS: Updates RDS to support accessing other AWS services by gassociating an IAM role with necessary permissions to your DB cluster.

## 2.6.9
* bugfix: s3: Propagate an error from a stream to s3.upload callback #1169
* feature: S3: Adds support for using dualstack with accelerate endpoints.
* feature: ACM: This change allows users to import third-party SSL/TLS certificates into ACM.
* feature: ElasticBeanstalk: Adds CodeCommit integraion. DescribeApplicationVersions updated to support pagination.
* feature: GameLift: New APIs to protect game developer resource (builds, alias, fleets, instances, game sessions and player sessions) against abuse.

## 2.6.8
* feature: ECR: DescribeImages is a new api used to expose image metadata which today includes image size and image creation timestamp.
* feature: ElastiCache: Elasticache is launching a new major engine release of Redis, 3.2 (providing stability updates and new command sets over 2.8), as well as ElasticSupport for enabling Redis Cluster in 3.2, which provides support for multiple node groups to horizontally scale data, as well as superior engine failover capabilities.

## 2.6.7
* feature: CognitoIdentityServiceProvider: Added new operation "AdminCreateUser" that creates a new user in the specified user pool and sends a welcome message via email or phone (SMS).
* feature: Route53: Retries PriorRequestNotComplete errors.

## 2.6.6
* feature: EC2: Adding support for EC2 Convertible RIs and the EC2 RI regional benefit.
* feature: S3: S3 API update with partNumber extension and a bug fix to address list-objects command failing when a bucket is marked with request-pays.

## 2.6.5
* bugfix: apiVersion: Fixes an issue where some service clients would fail to instantiate if an older apiVersion was specified.
* feature: CloudFormation: Adds support for specifying an IAM service role for CloudFormation stack operations.

## 2.6.4
* bugfix: Browser: Updates `url` and `querystring` dependencies to be controlled by the SDK instead of tools like browserify or webpack.
* bugfix: Config: Fixes an issue where specifying service-specific config on the global AWS.config object would fail if the service had not yet been instantiated.
* feature: CodeDeploy: AWS CodeDeploy now integrates with Amazon CloudWatch alarms, making it possible to stop a deployment if there is a change in the state of a specified alarm for a number of consecutive periods, as specified in the alarm threshold. AWS CodeDeploy also now supports automatically rolling back a deployment if certain conditions are met, such as a deployment failure or an activated alarm.
* feature: EMR: Added support for Security Configurations which can be used to enable encryption at-rest and in-transit for certain applications on Amazon EMR.
* feature: RDS: Provide local time zone support for AWS RDS SqlServer database instances.
* feature: Redshift: This release of Amazon Redshift introduces Enhanced VPC Routing. When you use Amazon Redshift Enhanced VPC Routing, Amazon Redshift forces all COPY and UNLOAD traffic between your cluster and your data repositories through your Amazon VPC.

## 2.6.3
* bugfix: Node_Https: Fixes an issue caused when https.globalAgent is set to false.
* feature: Iot: Updates registerCertificate operation, and allows users to specify cannedAcl for S3 action.
* feature: RDS: Updates describeDbCluster operation to allow specifying a ReaderEndpoint for accessing cluster readers.

## 2.6.2
* feature: ServiceCatalog: Updates the API for AWS.ServiceCatalog.

## 2.6.1
* bugfix: SDK: Fixes an issue that caused all services to be loaded into memory when requiring the SDK. This issue was introduced in version `2.6.0` of the SDK, and address #1124.

## 2.6.0
* feature: CloudFront: Adds HTTP2 support for Amazon CloudFront distributions.
* feature: MetadataService: Adds retry logic to the EC2 Metadata Service, so that EC2MetadataCredentials will retry TimeoutError. This retry logic is also added to ECSCredentials. Resolves #692
* feature: ServiceCatalog: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: Tools: Adds support for bundling the SDK with webpack. Also adds support for creating node.js bundles using webpack or browserify.

## 2.5.6
* feature: RDS: Adds new operation describeSourceRegions to provide list of all the source region names and endpoints for any region. Source regions are the regions where current region can get a replica or copy a snapshot from.

## 2.5.5
* feature: CognitoIdentityServiceProvider: Adds support for bulk import of users.
* feature: GameLift: Adds Linux support.
* feature: Iot: Adds Iot as a default service in the browser distribution of the AWS SDK for JavaScript.
* feature: RDS: Adds information in response of describeOptionGroupOptions about options that conflict with each other.

## 2.5.4
* feature: CloudFront: CloudFront is adding a Querystring Whitelist Option. Customers will be able to choose to forward certain querystring keys instead of a.) all of them or b.) none of them.
* feature: CodePipeline: CodePiepline has introduced a new feature to return pipeline execution details. Execution details consists of source revisions that are running in the pipeline. Customers will be able to tell what source revisions that are running through the stages in pipeline by fetching execution details of each stage.
* feature: Route53: With this release, Route 53 will support the following new features: support for the NAPTR DNS record type, a new testDNSAnswer API which enables customers to send a test query against a specific name server using spoofed delegation nameserver, resolver, and ECS IPs, and support metric-based health check in ap-south-1 region.

## 2.5.3
* feature: RDS: Adds resource ARNs to Describe APIs.

## 2.5.2
* bugfix: Waiter: Fixes bug in `clusterDeleted` waiter for AWS.Redshift.
* feature: EC2: Adds  new APIs supporting dedicated host reservations. Also adds new property to response of `describeSpotFleetRequests` to indicate  the activity status of spot fleet requests.
* feature: Request: eachItem method stops iteration on returning false (like eachPage)
* feature: WorkSpaces: Adds new APIs to support the launch and management of WorkSpaces that are paid for and used by the hour.

## 2.5.1
* feature: ACM: Increase tagging limit from 10 to 50.
* feature: APIGateway: Amazon API Gateway now supports API usage plans. Usage plans allows you to easily manage and monetize your APIs for your API-based business.
* feature: ECS: Adds support for memory reservation and network mode on task definitions. Also adds splunk as a supported log driver.

## 2.5.0
* feature: AutoScaling: Adds 3 new APIs for ELB L7 integration: attachLoadBalancerTargetGroups, detachLoadBalancerTargetGroups, and describeLoadBalancerTargetGroups.
* feature: ECS: Adds ECS support for ELBv2. Supports Application Load Balancer target groups to enable dynamic ports and path-based routing.
* feature: ELBv2: Adds new backwards incompatible application load balancer API version.  Application load balancers are a new load balancer that is now supported by the Elastic Load Balancing service. Application load balancers support HTTP/2, WebSockets, routing based on URL path, and routing to multiple ports on a single instance.
* feature: KMS: Adds support for importing customer-supplied cryptographic keys. New import key feature lets you import keys from your own key management infrastructure to KMS for greater control over generation and storage of keys and meeting compliance requirements of sensitive workloads.
* feature: KinesisAnalytics: Adds the new service Amazon Kinesis Analytics, a fully managed service for continuously querying streaming data using standard SQL. With Kinesis Analytics, you can write standard SQL queries on streaming data and gain actionable insights in real-time, without having to learn any new programming skills. The service allows you to build applications that continuously read data from streaming data sources, process that data using standard SQL, and send the processed data to up to four destinations of your choice. Kinesis Analytics enables you to generate time-series analytics, feed a real-time dashboard, create real-time alarms and notifications, and much more.
* feature: S3: Adds support for IPv6/IPv4 Dualstack endpoint. A new opt-in boolean  option `use Dualstack` can be specified for S3 service clients: `new AWS.S3({useDualstack: true})`. Alternatively, to configure it once for all subsequent S3 service clients: `AWS.config.update({s3: {useDualstack: true}})`.
* feature: Snowball: Adds Amazon Snowball, a new job management service.

## 2.4.14
* feature: CloudFront: Amazon CloudFront now supports tagging for Web and Streaming distributions. Tags make it easier for you to allocate costs and optimize spending by categorizing and grouping AWS resources.
* feature: ECR: Adds filtering of ListImages requests based on whether an image is tagged or untagged.
* feature: MarketplaceCommerceAnalytics: Adds the `startSupportDataExport` operation.

## 2.4.13
* feature: ApplicationAutoScaling: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: AutoScaling: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: CodeDeploy: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: GameLift: Provides a new Search API for GameLift, which allows game developers to retrieve filtered and sorted lists of their GameSessions.
* feature: RDS: You can now use the AWS Management Console to easily move your DB instance to a different VPC, or to a different subnet group in the same VPC. For more information, see Updating the VPC for a DB Instance. If your DB instance is not in a VPC, you can now use the AWS Management Console to easily move your DB instance into a VPC. You can now copy the source files from a MySQL database to an Amazon Simple Storage Service (Amazon S3) bucket, and then restore an Amazon Aurora DB cluster from those files. This option can be considerably faster than migrating data using mysqldump.

## 2.4.12
* bugfix: Request: Adds a content-length check for the stream returned from `createReadStream()`, and the stream will emit an error when the bytes received are fewer than specified by the response content-length header.
* bugfix: S3: Reverts behavior introduced in version `2.4.0` of the SDK to default the `signatureVersion` of S3 clients to `v4`. S3 clients instantiated without a user-defined `signatureVersion` will now default to `v2` unless the region only supports `v4` signing. This change is being made due to issues sending non-ascii characters in headers when using `v4` signing.
* feature: CloudWatchLogs: Updates the `putMetricFilter` operation.
* feature: EMR: Adds enhanced debugging.
* feature: Iot: Adds `listOutgoingCertificates` and support for allowing autoregistration.
* feature: MachineLearning: Adds compute time and entity timestamp to multiple operations.
* feature: RDS: Support for license model and versioning of option groups.
* feature: Route53Domains: Adds new APIs to renew domains for a specified duration, get domain suggestions, and view billing.

## 2.4.11
* feature: APIGateway: Adds support for authentication through Cognito User Pools.
* feature: CognitoIdentityServiceProvider: Introduces support for Your User Pools.
* feature: DirectoryService: Enables routing to on-premises public IP for Microsoft Active Directory.
* feature: EC2: Enables resolution of DNS queries from a peered VPC to a private IP address.
* feature: ES: Updates to Elasticsearch version 2.3, which offers improved performance, memory management, and security. It also offers several new features includinng pipeline aggregations to perform advanced analytics like moving averages and derivatives, and enhancements to geospatial queries.
* feature: Waiter: Adds Waiters for AWS.CodeDeploy.

## 2.4.10
* feature: util: Parse ini files containing comments using #
* feature: Iot: Adds support for thing types. Thing types are entities that store a description of common features of Things that are of the same logical type. Also adds support for `:` in Thing name. Adds a separator in Firehose action.

## 2.4.9
* feature: ACM: Adds reason for failure when describing certificates.
* feature: ConfigService: Adds support for RDS and ACM resources types and introduces two new APIs: DeleteEvaluationResults and StartConfigRulesEvaluation. Updated PutConfigRule API can now create Config rules that are triggered by both configuration changes and periodicity.
* feature: ElasticTranscoder: Adds WAV file format output support.
* feature: Paginator: Adds paginator for SSM DescribeInstanceInformation operation.

## 2.4.8
* feature: CloudFormation: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: CloudHSM: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: DeviceFarm: Adds session-based APIs.
* feature: EMR: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: ElastiCache: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: ElasticBeanstalk: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: Redshift: CORS support added. Now a default service in the browser build of the JavaScript SDK.
* feature: SSM: Adds notification support.
