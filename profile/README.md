<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="daxworks-wordmark-reverse.png">
  <img src="daxworks-wordmark.png" alt="DAxWorks" width="360">
</picture>

**Cloud platforms engineered for automation, intelligence and operational independence.**

Montreal, Quebec, Canada

</div>

DAxWorks designs, builds, automates and hands over production cloud platforms. Founded in 2019 in Montreal, we combine cloud architecture, infrastructure as code, delivery automation, observability and operational engineering to create platforms that can be understood, operated and evolved by the teams that own them.

We work with organisations that need reliable cloud infrastructure without building or expanding a platform engineering function of their own. The aim is always a platform its owners can run without us.

We are extending that engineering model with AI-assisted development, infrastructure analysis, engineering knowledge systems and intelligent operations.

## What we deliver

* **Cloud platform engineering.** Production environments on AWS spanning networking, compute, data and storage, designed around the failure domains, isolation boundaries and recovery requirements the workload actually has.

* **Infrastructure automation.** Terraform organised into independently deployed stacks with isolated state, checked for policy and security findings, and applied through CI/CD without long-lived credentials. Environments are created from code, not by hand.

* **Delivery engineering.** CI/CD pipelines built around a quality gate that nothing bypasses, federated identity in place of stored deployment keys, versioned releases, and the review practices that move a change safely from development into production.

* **Observability and reliability.** Alarms on the conditions that matter, routed to someone who can act. Logs that can be searched when something goes wrong, checks that run independently of the platform they watch, and recovery procedures that have been exercised rather than assumed.

* **Security and governance.** Least-privilege access, encryption, secrets management, network isolation and deletion protection, with every suppressed security finding justified in the code. Tagging and cost allocation so that operating cost can be understood and attributed before the invoice arrives.

* **Media and content platforms.** Upload, processing, transcoding and delivery pipelines, together with the cloud infrastructure and CMS platforms that support them.

* **Operations and handover.** Runbooks, recovery procedures, architecture documentation and the decisions behind it, written for a competent engineer who was not there.

**Current tooling:** `AWS` | `Terraform` | `GitHub Actions` | `Checkov` | `TFLint` | `Gitleaks` | `ShellCheck`

## How we engineer

### Capability, not product

"Multi-AZ RDS" is a line on someone else's price list. "The platform keeps serving when a data centre fails" is a capability. Delivering it requires a design, an implementation and evidence that it works. That is what the client is buying.

DAxWorks scopes every platform engagement across ten capability domains:

| | Domain | The question it answers |
|---|---|---|
| 1 | Availability | Does the platform keep serving while something is broken? |
| 2 | Recoverability | Does the platform come back after something is destroyed? |
| 3 | Scalability | Does the platform grow with demand? |
| 4 | Reproducibility | Can the platform be rebuilt from source? |
| 5 | Deployability | Do changes reach production safely? |
| 6 | Access control and isolation | Who can reach what, and how far does a compromise travel? |
| 7 | Data protection | Is the data unreadable to anyone who should not read it? |
| 8 | Observability | Is a problem reported, or discovered? |
| 9 | Cost governance | Does the client know what they are spending, and why, before the invoice? |
| 10 | Operability and transfer | Can someone else run this? |

Each engagement names the level of capability being delivered in each domain and, where relevant, the level that is explicitly outside the engagement. Architectural trade-offs, cost and scope become visible before implementation begins, and every later decision has a stated standard to be measured against.

### The engineering model

```text
 REQUIREMENTS ---> CAPABILITIES ---> STANDARDS ---> ARCHITECTURE
                                                         |
                                                         v
      HANDOVER <--- OPERATIONS <--- EVIDENCE <--- IMPLEMENTATION

 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 ENGINEERING INTELLIGENCE   assists design, review, documentation
                            and operations at every stage;
                            engineers make the decisions
```

Every stage produces something that can be checked: a capability level named in the agreement, a written standard, a design with its trade-offs recorded, code reviewed before it is applied, a demonstration that the level holds, and documentation that lets someone else take over.

### Principles

**Infrastructure cost belongs to the client, at cost.** Cloud resources remain the client's operating expense and are paid directly by the client wherever practical. DAxWorks does not use increased cloud consumption as a source of margin.

**A capability is not delivered until it is demonstrated.** Configuration alone is not evidence. A backup that has never been restored, for example, is not yet a demonstrated recovery capability.

**An engagement that cannot end is a dependency, not a delivery.** Platforms are documented for a competent stranger and built so that their owners can operate, change or transfer them.

## Where we are investing

### Engineering intelligence: emerging capability

DAxWorks is developing AI-assisted engineering workflows that combine the capability model, written engineering standards, architecture decisions, infrastructure state and operational knowledge, to assist with infrastructure development, change review, documentation and incident investigation.

The distinction that matters is what the work is measured against. An assistant asked to "review this Terraform" has nothing to check the change against except general best practice. Asked to evaluate a change against the capability levels agreed for that platform, its recorded architecture decisions and the applicable standards, it applies the same test an engineer would, and its output can be verified.

**Today:** AI assistance in development, review and documentation, held to the same standards, quality gates and review as any other change. The engineer who merges a change is accountable for it.

**Direction:** an engineering knowledge layer built from standards and decision records, change analysis against capability levels, and assistance with incident investigation.

This section will change as that work produces something that can be inspected.

## Repositories

Client work is private by contract.

Public repositories in this organisation are reserved for reusable engineering patterns, tooling, reference implementations and technical material that DAxWorks chooses to make publicly available. Anything this page describes as emerging will be backed by a repository here before it is described as delivered.

## Contact

* **Web:** daxworks.io
* **Email:** [info@daxworks.io](mailto:info@daxworks.io)
* **Location:** Montreal, Quebec, Canada
