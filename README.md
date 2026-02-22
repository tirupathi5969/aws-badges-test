# 🚀 AWS CI/CD Pipeline Status

> **Real-time pipeline monitoring for `aws-badges-test-pipeline`**
> 
> This dashboard provides a live, visual representation of the current state of our deployment pipeline across all environments.

### 📉 Visual Flow

```mermaid
graph LR
    S[Source] --> B[Build]
    B --> D[Dev Deploy]
    D --> ST[Staging Deploy]
    ST --> U[UAT Deploy]
    U --> P[Production Deploy]
    
    style S fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style P fill:#bfb,stroke:#333,stroke-width:2px
```

### 📊 Pipeline Flow

| Stage | Activity | Current Status | Last Updated | 🔑 Commit | 👤 Triggered By |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01. Source** | Repository Listeners | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Source.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Source-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Source-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Source-author.svg) |
| **02. Build** | Artifact Compilation | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Build.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Build-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Build-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-Build-author.svg) |
| **03. Dev** | Development Deploy | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-author.svg) |
| **04. Staging** | Staging Deploy | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-author.svg) |
| **05. UAT** | User Acceptance | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-author.svg) |
| **06. Production** | Live Environment | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-author.svg) |

---

### 🛡️ Deployment Security & Logs
*   **Artifact Store**: Private S3 with CloudFront OAC.
*   **Cache Strategy**: Native Camo Purge (Live Image Updates).
*   **Infrastructure**: AWS Lambda + CloudWatch Events.



========


graph LR
    S((Source)) --> B(Build) --> D(Dev) --> ST(Staging) --> U(UAT) --> P((Production))
    
    style S fill:#f3f4f6,stroke:#333
    style P fill:#f3f4f6,stroke:#333

---
<sub>*Status badges are updated automatically on every pipeline state change.*</sub>
