# serverless-serverless-027fbab2

> Auto-generated documentation by CodeInsights

## Overview

<br/>

## Project Information

- **Language**: go
- **Framework**: Jest
- **Total Files**: 18
- **Modules**: 1

## Project Structure

- **Source directories**: binary-installer, packages/engine, packages/framework-dist, packages/mcp, packages/serverless, packages/serverless/lib/plugins/aws/dev/local-lambda/test/handlers/js, packages/serverless/lib/plugins/aws/invoke-local/runtime-wrappers/java, packages/sf-core, packages/sf-core-installer, packages/standards, packages/util, release-scripts
- **Test directories**: packages/engine/test, packages/mcp/tests, packages/serverless/test, packages/sf-core/tests

## Module Architecture

```
- serverless-serverless-027fbab2 (85 components)
```

## Modules

| Module | Path | Files |
|--------|------|-------|
| [serverless-serverless-027fbab2](serverless-serverless-027fbab2.md) | `` | 0 |

## Getting Started

See the individual module documentation for detailed information.

---

## Original README

[![Serverless Framework AWS Lambda AWS DynamoDB AWS API Gateway](https://github.com/serverless/serverless/assets/2752551/66a8c6a9-bc4a-4116-b139-90c12963337e)](https://serverless.com)

<br/>

<div align="center">
  <a aria-label="Serverless.com" href="https://serverless.com">Website</a>
  &nbsp;•&nbsp;
  <a aria-label="Serverless Framework Documentation" href="https://serverless.com/framework/docs/">Documentation</a>
  &nbsp;•&nbsp;
  <a aria-label="Serverless Inc Twitter" href="https://twitter.com/goserverless">X / Twitter</a>
  &nbsp;•&nbsp;
  <a aria-label="Serverless Framework Community Slack" href="https://serverless.com/slack">Community Slack</a>
  &nbsp;•&nbsp;
  <a aria-label="Serverless Framework Community Forum" href="https://forum.serverless.com">Forum</a>
</div>

<br/>
<br/>

**The Serverless Framework** – Makes it easy to use AWS Lambda and other managed cloud services to build applications that auto-scale, cost nothing when idle, and result in radically low maintenance.

The Serverless Framework is a command-line tool with approachable YAML syntax to deploy both your code and cloud infrastructure needed to make tons of serverless application use-cases, like APIs, front-ends, data pipelines and scheduled tasks. It's a multi-language framework that supports Node.js, Typescript, Python, Go, Java, and more. It's also completely extensible via over 1,000 plugins which add more serverless use-cases and workflows to the Framework.

Actively maintained by [Serverless Inc](https://www.serverless.com).

<br/>

# Serverless Framework - V.4

<div align="center" style="max-width: 500px; margin: auto;">
  <a href="https://www.youtube.com/watch?v=UQL_PPJUFOU" target="_blank">
    <img src="https://github.com/serverless/serverless/assets/2752551/2fc23656-df76-4d8a-b775-f4cc8ed2068d" alt="Serverless Framework V.4 Overview Video" style="width: 100%; max-width: 500px;">
  </a>
</div>

<br/>

**January 2026** – V.4 continues to feature significant updates. Review them all below. In January 2026 we released support for numerous new features like Managed Instances, Durable Functions, Built-in AppSync & Prune plugins, and built-in AWS Login & SSO support. As always, we are more excited about the serverless future than ever.

## New Features In V.4

Here's a list of everything that's new in V.4, so far:

- **Managed instances** – Native support for EC2-backed Lambda execution to enable higher throughput, predictable capacity, and long-running workloads.
- **Durable functions** – Built-in support for durable, stateful workflows and long-running orchestrations.
- **Lambda tenant isolation mode:** Use tenant isolation mode to create distinct Lambda compute environments per tenant to help reduce noisy neighbor effects and isolate high-traffic customers more cleanly.
- **HTTP response streaming:** Stream logs, long-running reports, partial responses, or AI LLM responses from Lambda with API Gateway HTTP APIs.
- **Per-function IAM roles:** Add per-function IAM policies or switch the entire service to use per-function policies.
- **Built-in plugins**: Popular community plugins are now first-class, built-in features of the framework, including Python requirements, AppSync, Prune, API Gateway Service Proxy, and more.
- **Improved Custom Domain Support:** You no longer need an external plugin to automatically configure custom domains and SSL certificates for your APIs and more. It's now built into the [Serverless Framework CLI](https://www.serverless.com/framework/docs/providers/aws/guide/domains).
- **Integration with Doppler:** You can now easily fetch Secrets from Doppler via [Serverless Framework Variables](https://www.serverless.com/framework/docs/guides/variables/doppler).
- **Introducing [Serverless MCP](https://www.serverless.com/framework/docs/guides/mcp):** Built for Cursor, Windsurf, and other AI-powered IDEs, it auto-detects cloud resources from your code, fetching logs, state, and config from AWS, enabling you to debug serverless apps directly in your IDE — no AWS console visit needed! Supports Serverless Framework, Cloudformation, and more.
- **Introducing the [Serverless Container Framework](https://github.com/serverless/containers):** One solution to deploy serverless workloads everywhere - This is a new YAML file that works with the Serverless Framework CLI that gives you one experience to easily deploy containers to AWS Lambda and AWS ECS Fargate and migrate between them w/ zero-downtime — all without re-architecting. We launched this as a way to reduce large Lambda bills and give folks flexibility, but it is rapidly become the greatest developer experience for containers on AWS. Support for Google Cloud Run, Azure and more are coming soon.
- **Support for AWS SAM, AWS CloudFormation, & Traditional Serverless Framework Projects:** Now, you can use one tool to deploy all three of these IaC project files. [More info here](https://www.serverless.com/framework/docs/guides/sam)
- **Native TypeScript Support:** You