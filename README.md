# AWS Spatial Computing Index Page

This page provides a single-source of discovery for Spatial Computing related AWS solutions and sample projects on Github.

## Contents
- [Solutions](#solutions)
    - [Amazon Visual Asset Management System](#amazon-visual-asset-management-system)
    - [AWS Data Transformation Pipeline CDK Constructs](#aws-data-transformation-pipeline-cdk-constructs)
- [Samples](#samples)
    - [Amazon GameLift Streams React Starter Sample](#amazon-gamelift-streams-react-starter-sample)  
    - [Pixel Streaming on Amazon Elastic Kubernetes Service](#pixel-streaming-on-amazon-elastic-kubernetes-service)
    - [Spatial Real Time Translation](#spatial-real-time-translation)
    - [Amazon Cognito and Unity Integration](#amazon-cognito-and-unity-integration)
    - [Unity Build Server with AWS CDK](#unity-build-server-with-aws-cdk)
    - [NVIDIA Omniverse Nucleus on Amazon EC2](#nvidia-omniverse-nucleus-on-amazon-ec2)
    - [Amazon Polly with Epic Games Metahumans](#amazon-polly-with-epic-games-metahumans)
    - [Amazon Sumerian Hosts for Web3D](#amazon-sumerian-hosts-for-web3d)
    - [Deploying Unreal Engine Pixel Streaming Server on Amazon EC2](#deploying-unreal-engine-pixel-streaming-server-on-amazon-ec2)
    - [Amazon GameLift Unreal Engine](#amazon-gamelift-unreal-engine)
    - [Amazon GameLift Unity](#amazon-gamelift-unity)
    - [Amazon EC2 Cluster for Unreal Swarms](#amazon-ec2-cluster-for-unreal-swarms)
    - [Simple Game Studio on AWS](#amazon-ec2-cluster-for-unreal-swarms)
    - [Game Production in the Cloud Example Pipeline](#game-production-in-the-cloud-example-pipeline)
    - [AWS Gaming Unity Labs Sample](#aws-gaming-unity-labs-sample)
    - [Amazon API Gateway WebSocket API and Unity WebSocket Client Component](#amazon-api-gateway-websocket-api-and-unity-websocket-client-component)
    - [Berkeley Room Designer](#berkeley-room-designer)
    - [Empower Your WebXR App Using AWS Serverless Architecture](#empower-your-webxr-app-using-aws-serverless-architecture)
    - [Generative AI Avatar Chat](#generative-ai-avatar-chat)
- [Archive](#archive)
    - [AWS Spatial Computing Samples](#aws-spatial-computing-samples)
    - [Amazon Sumerian Hosts Samples](#amazon-sumerian-hosts-samples)
    - [Amazon Sumerian ARCore Starter App](#amazon-sumerian-arcore-starter-app)
    - [Amazon Sumerian ARKit Starter App](#amazon-sumerian-arkit-starter-app)
- [Security](#security)
- [License](#license-summary)

## Solutions

### [Amazon Visual Asset Management System](https://github.com/awslabs/visual-asset-management-system)

Visual Asset Management System (VAMS) is a purpose-built, AWS native solution for the management and distribution of specialized visual assets used in spatial computing. VAMS offers a simplified solution for organizations to ingest, store, and manage visual assets in the cloud, which empowers any user with a web browser to upload, manage, visualize, transform, and retrieve visual assets. Existing workflows that leverage both custom code and pre-built or third-party applications can also be migrated to VAMS and ran in the AWS cloud, as opposed to being limited by the on-premise capacity available. VAMS is customizable and expandable with option of being further tailored to specific use-cases by development teams.

### [AWS Data Transformation Pipeline CDK Constructs](https://github.com/awslabs/data-transformation-pipeline-cdk-constructs)
The AWS Data Transformation Pipeline Constructs Library is an open-source extension of the AWS Cloud Development Kit (AWS CDK) that provides multi-service, well-architected patterns for quickly defining solutions in code to create predictable and repeatable infrastructure, called constructs. The goal of AWS Data Transformation Pipeline CDK Constructs is to help developers build data transformation pipelines with pattern-based definitions for their architecture.

## Samples

### [Amazon GameLift Streams React Starter Sample](https://github.com/aws-samples/sample-amazon-gamelift-streams-react-app)
The Amazon GameLift Streams React Starter sample repository allows developers to quickly get up and running with Amazon GameLift Streams. Amazon GameLift Streams helps game developers deliver game streaming experiences at up to 1080p resolution and 60 frames-per-second (fps) across devices. Publishers can deploy their game content in minutes, without modifications, onto fully-managed cloud-based GPU instances and deliver them directly to any device with a web browser.

### [Pixel Streaming on Amazon Elastic Kubernetes Service](https://github.com/aws-samples/pixel-streaming-on-eks)
Pixel Streaming is a remote rendering library in Unreal Engine. In this sample we show how to use Pixel Streaming with Amazon Elastic Kubernetes Service (EKS). By using EKS, we can utilize a scalable and cost-efficient cloud rendering environment.

### [Spatial Real Time Translation](https://github.com/aws-samples/spatial-real-time-translation)
In this sample we show how Amazon Transcribe, Amazon Translate, and Amazon Polly can be used together to produce a near real-time speech-to-speech translator solution for your next VR project.

### [Unity Build Server with AWS CDK](https://github.com/aws-samples/unity-build-server-with-aws-cdk)

This AWS CDK sample projects deploys a Unity Build Server and Unity License Server on Amazon EC2. Unity Build Servers enable you to scale your build capacity with both automated and on-demand builds on Amazon EC2 hardware. Leverage floating licenses to easily deploy and manage build infrastructure at scale.

### [Amazon Cognito and Unity Integration](https://github.com/aws-samples/amazon-cognito-unity-integration)
This project demonstrates the seamless integration of Unity with AWS services, showcasing the utilization of Cognito User Pool and Identity Pool for secure JWT token-based authentication. The application uses AWS Identity and Access Management (IAM) to interact with API Gateway, Lambda functions, S3, and DynamoDB.

### [NVIDIA Omniverse Nucleus on Amazon EC2](https://github.com/aws-samples/nvidia-omniverse-nucleus-on-amazon-ec2)

NVIDIA Omniverse Nucleus is the database and collaboration engine that enables real-time exchange of USD data. With Omniverse Nucleus, you can connect multiple users working in their preferred 3D applications, providing a single source of truth for their 3D data. Nucleus operates under a publish-and-subscribe model and enables efficient live synchronization between Omniverse applications. It transmits changes to USD scenes in real-time between connected applications. This repository provides the steps and infrastructure for an Omniverse Enterprise Nucleus Server deployment on Amazon EC2.

### [Amazon Polly with Epic Games Metahumans](https://github.com/aws-samples/amazon-polly-metahumans)

This Unreal Engine sample project demonstrates how to bring Epic Games' MetaHuman digital characters to life using the Amazon Polly text-to-speech service from AWS. Use this project as a starting point for creating your own Unreal Engine applications that leverage Amazon Polly to give voice to your MetaHumans using one of 16 different English language voices spanning 5 dialects. Or extend this project to use any of Polly's 60+ voices covering 20+ languages and 13+ dialects.

### [Amazon Sumerian Hosts for Web3D](https://github.com/aws-samples/amazon-sumerian-hosts)

Amazon Sumerian Hosts (Hosts) is an experimental open source project that aims to make it easy to create interactive animated 3D characters for Babylon.js, three.js, and other web 3D frameworks. It leverages AWS services including Amazon Polly (text-to-speech) and Amazon Lex (chatbot).

### [Deploying Unreal Engine Pixel Streaming Server on Amazon EC2](https://github.com/aws-samples/deploying-unreal-engine-pixel-streaming-server-on-ec2)

This sample is for those who use Unreal Engine 4 to build content and wish to deploy this content to an audience via UE4 pixel streams. Content examples include but are not limited to: interactive entertainment, architectural visualization, high fidelity car configurators, or anyone who needs to let users access high quality interactive content via thin clients such as web browsers.

### [Amazon GameLift Unreal Engine](https://github.com/aws-samples/amazon-gamelift-unreal-engine)

This repository contains code used for the video series, Building Games on AWS: Amazon GameLift with Unreal Engine. For the full guide, please see the video series.

### [Amazon GameLift Unity](https://github.com/aws-samples/amazon-gamelift-unity)

This sample code shows how to set up a basic GameLift server and client for games using the Unity Game Engine. It consists of a Unity project that has been configured to be built in two ways, as a SERVER or a CLIENT. In CLIENT configuration, the preprocessor symbol CLIENT is defined. In SERVER configuration, the preprocessor SERVER is defined. 

### [Amazon EC2 Cluster for Unreal Swarms](https://github.com/aws-samples/ec2-cluster-for-unreal-swarms)

This example allows you to run Unreal Swarm cluster on AWS. The CDK or Cloudformation templates create a new VPC for the Swarm EC2 instances to run in and it also uses EC2 Image Builder to automatically create a custom AMI as the base for your cluster. It also creates a S3 bucket where you will upload the Unreal Engine 4 dependencies packaged into a ZIP archive. This S3 bucket is also used as destination for EC2 Image Builder logs.

### [Simple Game Studio on AWS](https://github.com/aws-samples/simple-game-studio-on-aws)

With this CDK application, you can easily build a simple and customizable game studio on AWS. The default setting covers a build farm, a source code repository, CI tool, workstation, and backups. If you are suffered from long build time, build farm management, slow response from CI tool, this project could help your time.

### [Game Production in the Cloud Example Pipeline](https://github.com/aws-samples/game-production-in-the-cloud-example-pipeline)

Quickly deploy a Cloud Game Development environment for you and your team, with this AWS Sample. Once deployed, you will have high performance virtual workstation, central version control system, and acceleration of compute heavy tasks by distributing the work to other machines on demand. 

The CDK (or CloudFormation templates) creates a new AWS Virtual Private Cloud (VPC), a customizable virtual workstation, a Perforce Helix Core server, and an Unreal Engine 4 Swarm cluster. The latter can be used to accelerate Unreal Engine 4 lighting builds using the vast compute resources available in AWS.

### [AWS Gaming Unity Labs Sample](https://github.com/aws-samples/aws-gaming-unity-labs-sample)

This repository contains a sample Unity game project that is used by several Self Paced Labs to demonstrate the use of the AWS Mobile SDK for Unity.

### [Amazon API Gateway WebSocket API and Unity WebSocket Client Component](https://github.com/aws-samples/amazon-api-gateway-websocket-api-and-unity-websocket-client-component)

This sample project demonstrates deploying an Amazon API Gateway WebSocket API and building a Unity WebSocket Client component. The project includes AWS CDK code that deploys the cloud resources and a Unity project. The Unity project includes a .NET implementation of a WebSocket Client and sample game code using the WebSocket Client.

### [Berkeley Room Designer](https://github.com/aws-samples/berkeley-room-designer)

This repository contains a (web-based and CLI) room designer which utilizes and collates furnishings from the [Amazon Berkeley Objects Dataset](https://amazon-berkeley-objects.s3.amazonaws.com/index.html) and is primarily intended to be a sample for working with it.

### [Empower Your WebXR App Using AWS Serverless Architecture](https://github.com/aws-samples/aws-serverless-example-for-webxr)

This repository contains an example solution on how to enhance your WebXR applications using AWS Serverless Services, providing scalable, efficient, and seamless user experiences.

### [Generative AI Avatar Chat](https://github.com/aws-samples/generative-ai-avatar-chat)

This repository contains a sample implementation of a Generative AI chatbot interfaced with a 3D avatar. The project includes AWS CDK code that deploys the cloud resources and the React-babylon frontend web application. Generative AI Chat is powered by Amazon Bedrock.

## Archive
The below projects are no longer active. They remain listed in this index for referential and tracking purposes.

### [AWS Spatial Computing Samples](https://github.com/aws-samples/aws-spatial-computing-samples)

This repository contains sample code for Spatial Computing applications on AWS

### [Amazon Sumerian Hosts Samples](https://github.com/aws-samples/amazon-sumerian-host-samples)

You will learn how simple and seamless it is to build an interactive and immersive Human-like Sumerian Hosts(without having to touch or press any button) on your AR/VR applications using Alexa. We are going to build a Sumerian Scene with a Host that answers your questions regarding AWS services, and uses TV to display videos about these services. We can ask the host to display content on TV directly, or ask about any AWS service or interrupt the Host at any point of time while she is explaining about a topic and ask further questions. This makes the Host more human like and interactive as she can listen to you when interrupted and take cross questions.

### [Amazon Sumerian ARCore Starter App](https://github.com/aws-samples/amazon-sumerian-arcore-starter-app)

A sample Android project that demonstrates how to create a simple augmented reality experience using Google's ARCore with the Amazon Sumerian service.

### [Amazon Sumerian ARKit Starter App](https://github.com/aws-samples/amazon-sumerian-arkit-starter-app)

A sample XCode project that demonstrates how to create a simple augmented reality experience using Apple's ARKit with the Amazon Sumerian service.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the [LICENSE](./LICENSE) file.
