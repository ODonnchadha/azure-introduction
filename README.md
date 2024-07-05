## INTRODUCTION TO AZURE

- INTRODUCTION:
  = "To the cloud!" Managed services. Managed solutions. Used somewhere else.
    - Fault tolerance: Redundancy. Backups.
    - High availability: Sharing.
    - Scalability: Forecast versus automatic scaling. On-demand resources. With peak hours.
    - Elasticity: Reverse of scalability. Reduce to meet need at that moment.
      - Grow and shrink to meet ongoing needs.

- AZURE ORGANIZATION AND INFRASTRUCTURE:
  - "Organization and relationships."
  1. What is Azure? Microsoft's public cloud computing platform.
    - Two hundred individual products and services.
    - Build, run, and manage applications on Microsoft's *global* infrastruction:
      - Infrastructure as a Service: IaaS.
      - Platform as a Service: PaaS. (Managed services.)
      - Software as a Service: SaaS. (Managed services.)
      - Pay-as-you-go pricing. No up-front commitment for resources.
        - Operational expense.
  2. Azure Global Infrastructure:
    - Datacenter infrastructure:
    - Breakdown between regions and availability zones:
      - Region: Group of datacenters in a single geographic location.
      - Availability zone: One of several unique physical locations in a region.
        - Providing an addditional layer of fault tolerance.
  3. Azure Services:
    - Available business (managed) services. Via portal page.
      - Solutiuons. Services.
      - IaaS: Virtual servers. You maintain OS.
      - PaaS: Cloud vendor maintains infrastructure. You focus on code and data.
      - SaaS: Vendor provides full software stack.
    - Azure Resource Manager (ARM.):
      - Interaction: SDKs. ARM: Single portal. Centralized management layer.
        - CLI. Application access. Authentication.
  4. Resource Hierarchy and Organization:
    a. Organization:
      - Tenant: Management Groups: Subscriptions: Resource Groups: Resources.
        - Access and policies granted to parrents are inherited by child levels.
        - A child can only have one parent. Similiar to OS file structure.
    b. Tracking: (Segmentating.) Payment.
    c. Limiting: Access to different sets of resources. Or not.
  5. Identity and Access Management. (IAM:)
    - Who? Azure Active Directory. (Azure AD,) Cloud-based identity service.
      - One per tenant. Who are you? Identity equals 'security principle.'
      = Manage end users (people) or applications.
      - End user: email format.
    - Can do what? Azure Role-Based Access COntrol. (Azure RBAC.)
      - Access controlled via roles. "What are you allowed to do?"
      - Assign roles to a security principle.
      - Roles are collections of specific permissions.
      = Roles: General and specific types.
    - On which resources? Scope. Scope of access in resource heirarchy.
      - The set of resources allowed to access. "On which resources?"
      - Roles granted to various layers of resource heirarchy.
      - Lower levels inherit roles from higher levels.
  6. Monitoring Your Azure Environment:
    - Are resources performing as expected?
    - Are there errors I need to be aware of?
    - Who is making changes to my cloud environment?
    - Azure Monitor: Cloud visiility. "What's happening?"
      - Logs: Text-based event(s) record(s).
        - "Who created the resource and when?" "Why is Windows throwing an error?"
      - Metrics:
        - Telemetry-based performance data:
          - CPU Utilization. Latency.

- CORE SERVICES:
  - Fundamental building blocks.