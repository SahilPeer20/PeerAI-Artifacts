# Feature: Hybrid Development Mode (`serverless dev`)

**Product:** Serverless

**Epic:** s: Serverless Framework v4

**Priority:** Medium

**Status:** Generated

## Description

**As a** backend developer or indie developer  
**I want** to trigger my local code with real cloud events without redeploying  
**So that** I can iterate and debug serverless functions rapidly, reducing deployment friction and costs

**Summary**:  
Hybrid Development Mode allows developers to use the `serverless dev` command to proxy real cloud events (e.g., API Gateway requests, SQS messages) to their local machine, where code executes instantly. This dramatically speeds up the edit-test-debug cycle, reduces accidental production errors, and lowers cloud costs during development.

