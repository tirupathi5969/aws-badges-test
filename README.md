# 🚀 aws-badges-test | CI/CD Dashboard

> **Real-time Deployment Monitoring**
> This dashboard provides a live, visual representation of the current state of our deployment pipeline for this microservice.

### 📉 Pipeline Architecture

```mermaid
graph LR
    S((Source)) --> B(Build) --> D(Dev) --> ST(Staging) --> U(UAT) --> P((Production))
    
    style S fill:#f3f4f6,stroke:#333
    style P fill:#f3f4f6,stroke:#333
```

### 📊 Live Stage Monitoring

| Stage | Activity | Current Status | Last Updated | 🔑 Commit | 👤 Author |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01. Source** | 📡 Listener | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Source.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Source-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Source-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Source-author.svg) |
| **02. Build** | 🏗️ Compile | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Build.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Build-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Build-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-Build-author.svg) |
| **03. Dev** | 🧪 Deploy | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-DevDeploy-author.svg) |
| **04. Staging** | 🚀 Deploy | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-StagingDeploy-author.svg) |
| **05. UAT** | 🚥 Review | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-UATDeploy-author.svg) |
| **06. Production** | 💎 Live | ![Status](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy.svg) | ![Time](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-timestamp.svg) | ![Commit](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-commitId.svg) | ![Author](https://dsikuhnjgrtfw.cloudfront.net/test-badges-1-Pipeline-kndYpoWCdWZw/test-badges-1-Pipeline-kndYpoWCdWZw-ProductionDeploy-author.svg) |

---

### 🛡️ Smart Infrastructure
*   **Discovery**: Automatic repository & README mapping via AWS API.
*   **Performance**: Native Camo Purge Protocol for sub-second updates.
*   **Security**: Private S3 storage via CloudFront OAC.

---
<sub>*Status badges feature live **animated progress bars** during active deployments.*</sub>
