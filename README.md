# Amazon EFS (amazon-efs)
Amazon Elastic File System (EFS) provides a simple, serverless, set-and-forget elastic file system for use with AWS cloud services and on-premises resources. EFS is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/efs/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, EFS, Elastic File System, File Storage, NFS, Serverless, Storage

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EFS API
API for managing Amazon EFS file systems, mount targets, and related resources.

**Human URL:** [https://aws.amazon.com/efs/](https://aws.amazon.com/efs/)

#### Properties

- [Documentation](https://docs.aws.amazon.com/efs/latest/ug/)
- [OpenAPI](openapi/amazon-efs-openapi.yml)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/elasticfilesystem/2015-02-01/openapi.yaml)
- [JSONSchema](json-schema/amazon-efs-filesystem-schema.json)
- [JSONLD](json-ld/amazon-efs-context.jsonld)
- [Pricing](https://aws.amazon.com/efs/pricing/)
- [GettingStarted](https://aws.amazon.com/efs/getting-started/)
- [FAQ](https://aws.amazon.com/efs/faqs/)
- [Documentation](https://docs.aws.amazon.com/efs/latest/ug/)
- [APIReference](https://docs.aws.amazon.com/efs/latest/ug/API_Reference.html)
- [Documentation](https://docs.aws.amazon.com/cli/latest/reference/efs/)
- [Security](https://docs.aws.amazon.com/efs/latest/ug/security.html)
- [JSONStructure](json-structure/amazon-efs-filesystem-structure.json)
- [Example](examples/amazon-efs-filesystem-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/)
- [Documentation](https://docs.aws.amazon.com/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://status.aws.amazon.com/)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-web-services)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-efs-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-efs-vocabulary.yaml)
- [NaftikoCapability](capabilities/efs-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Elastic Scalability | Automatically grows and shrinks as you add and remove files with no provisioning required. |
| Multiple Storage Classes | Standard, Infrequent Access, and Archive storage classes with automatic lifecycle management. |
| Multi-AZ Replication | Data automatically replicated across multiple Availability Zones for 99.999999999% durability. |
| Concurrent Access | Thousands of EC2 instances and Lambda functions can access the same file system simultaneously. |
| EFS Access Points | Application-specific entry points with customized directory access and POSIX permissions. |
| AWS Backup Integration | Centralized backup management for EFS file systems with policy-based retention. |

## Use Cases

| Name | Description |
|------|-------------|
| Containerized Application Storage | Persistent shared storage for containerized applications running on ECS or EKS. |
| Machine Learning | Shared training data storage accessible simultaneously by multiple compute instances. |
| Content Management | Shared file storage for web servers and CMS platforms requiring concurrent file access. |
| DevOps and Code Sharing | Centralized code and configuration storage accessible by development teams and CI/CD pipelines. |
| Big Data Analytics | High-throughput shared storage for analytics workloads requiring parallel data access. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Mount EFS file systems on EC2 instances using the NFS protocol. |
| Amazon ECS | Provide persistent shared storage for ECS tasks with EFS volume drivers. |
| Amazon EKS | Use the Amazon EFS CSI driver to mount EFS file systems as Kubernetes persistent volumes. |
| AWS Lambda | Access EFS file systems from Lambda functions for shared data storage and large model loading. |
| AWS Backup | Automated backup of EFS file systems with centralized policy management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Efs](openapi/amazon-efs-openapi.yml)

### JSON Schema

- [Amazon Efs Filesystem](json-schema/amazon-efs-filesystem-schema.json)
- [Efs Openapi Describe File Systems Response](json-schema/efs-openapi-describe-file-systems-response-schema.json)
- [Efs Openapi File System](json-schema/efs-openapi-file-system-schema.json)
- [Efs Openapi Mount Target](json-schema/efs-openapi-mount-target-schema.json)

### JSON Structure

- [Amazon Efs Filesystem](json-structure/amazon-efs-filesystem-structure.json)
- [Efs Openapi Describe File Systems Response](json-structure/efs-openapi-describe-file-systems-response-structure.json)
- [Efs Openapi File System](json-structure/efs-openapi-file-system-structure.json)
- [Efs Openapi Mount Target](json-structure/efs-openapi-mount-target-structure.json)

### JSON-LD

- [Amazon Efs](json-ld/amazon-efs-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Efs](capabilities/shared/efs.yaml) — 20 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Efs Management](capabilities/efs-management.yaml) | 5 | managing EFS file systems, mount targets, and access points for storage administrators |

## Vocabulary

- [Amazon EFS Vocabulary](vocabulary/amazon-efs-vocabulary.yaml) — Unified taxonomy mapping 1 resources, 3 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Efs Spectral Rules](rules/amazon-efs-spectral-rules.yml) — 28 rules enforcing Amazon EFS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com