# cdk_ecsbluegreen
Setup CDK: Initialize a new CDK app.
Define ECS Cluster and Task Definition: Create an ECS cluster and task definition.
Define ECR Repository: Create an ECR repository to store Docker images.
Define ECS Service with CodeDeploy: Create an ECS service integrated with CodeDeploy for blue-green deployments.
Define CodePipeline for CI/CD: Create a CI/CD pipeline using AWS CodePipeline and AWS CodeBuild.

cdk init app --language=typescript

npm install @aws-cdk/aws-ecs @aws-cdk/aws-ecr @aws-cdk/aws-codedeploy @aws-cdk/aws-codepipeline @aws-cdk/aws-codepipeline-actions @aws-cdk/aws-codebuild

