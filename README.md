# aws-badges-test

Create status-badges and commit-id badges according to CodeBuild/CodePipeline states. 
The badges are uploaded to S3 bucket, and then you can link to those badges (SVG files) in your README.md

| Stage | CodeBuild | CodeBuildDeploy | CodePipeline | Commit Id |
|-------|-----------|-----------------|--------------|-----------|
| dev | ![Build Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/aws-badges-test.svg) | | ![Pipeline Status](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/aws-badges-test-pipeline.svg) | ![Commit Id](https://dx-aws-pipeline-badges-images.s3.ca-central-1.amazonaws.com/aws-badges-test-pipeline-commitId.svg) |
| staging | | | | |
| uat | | | | |
| prod | | | | |
