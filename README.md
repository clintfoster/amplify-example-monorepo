# Overview
Demonstrate AWS Amplify CI/CD using a monorepo (a supported configuration).

# Details
Amplify naively assumes each project has both a frontend and backend.
It is possible to share the same BE with multiple projects.
Here we demoonstrate two amplify projects in which one shares the BE from the other.

# Lambda layers
We also demonstrate how business logic can be kept separately from the Amplify project in AWS Lambda Layers.
