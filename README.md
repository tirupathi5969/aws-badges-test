# dm-bos-web-app

Create status-badges and commit-id badges according to CodeBuild/CodePipeline states. 
The badges are uploaded to S3 bucket, and then you can link to those badges (SVG files) in your README.md

| Stage | CodeBuild | CodePipeline | Commit Id |
|-------|-----------|--------------|-----------|
| dev | ![Build Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/Dev-dm-bos-web-app.svg) | ![Pipeline Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/dm-bos-web-app.svg) | ![Commit Id](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/dm-bos-web-app-commitId.svg) |
| staging | ![Build Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/Staging-dm-bos-web-app.svg) | | |
| uat | ![Build Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/UAT-dm-bos-web-app.svg) | | |
| prod | ![Build Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/Production-dm-bos-web-app.svg) | | |
