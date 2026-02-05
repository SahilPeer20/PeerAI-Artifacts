# NFR: Cold Start Latency

**Product:** Serverless

**Category:** Performance

**Priority:** High

## Description

The serverless platform must ensure that the cold start latency for any function invocation does not exceed 1 second under normal operating conditions.

## Measurement Criteria

Measure the time taken from function invocation to execution start for cold starts across 1000 invocations.

## Acceptance Threshold

95% of cold starts must complete within 1 second.

