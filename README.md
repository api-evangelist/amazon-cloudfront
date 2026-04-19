# Amazon CloudFront (amazon-cloudfront)
Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds across 750+ globally dispersed Points of Presence.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudFront, CDN, Content Delivery, Edge

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudFront API
API for managing CloudFront distributions, origins, behaviors, cache policies, and edge functions for global content delivery.

**Human URL:** [https://aws.amazon.com/cloudfront/](https://aws.amazon.com/cloudfront/)

#### Tags:

 - AWS, CloudFront, CDN, Content Delivery

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloudfront/latest/APIReference/)
- [OpenAPI](openapi/amazon-cloudfront-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/cloudfront/latest/APIReference/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudfront/)
- [SpectralRules](rules/amazon-cloudfront-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudfront-vocabulary.yaml)
- [NaftikoCapability](capabilities/content-delivery.yaml)

## Features

| Name | Description |
|------|-------------|
| Global Edge Network | Deliver content from 750+ globally distributed Points of Presence for low latency. |
| DDoS Protection | Built-in AWS Shield Standard protection for all CloudFront distributions at no extra cost. |
| Edge Functions | Deploy serverless code at edge locations with CloudFront Functions and Lambda@Edge. |
| HTTPS Encryption | Secure content delivery with HTTPS and field-level encryption capabilities. |
| Origin Shield | Additional caching layer to reduce load on origins and improve cache hit rates. |

## Use Cases

| Name | Description |
|------|-------------|
| Website Acceleration | Fast, secure global content delivery for web applications. |
| Video Streaming | Live and on-demand video streaming with Media Services integration. |
| API Acceleration | Low-latency API delivery with edge termination and WebSocket support. |
| Software Distribution | Scale patch and software update delivery globally to millions of endpoints. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Serve static content from S3 buckets through CloudFront distributions. |
| AWS Lambda@Edge | Run Lambda functions at CloudFront edge locations for request customization. |
| AWS WAF | Filter malicious traffic with WAF rules applied at the CloudFront edge. |
| AWS ACM | Use ACM SSL/TLS certificates with CloudFront distributions. |
| Amazon Route 53 | Route traffic to CloudFront distributions using Route 53 aliases. |

## Artifacts

### OpenAPI

- [Amazon CloudFront API](openapi/amazon-cloudfront-openapi.yml)

### JSON Schema

- [Distribution](json-schema/cloudfront-distribution-schema.json)
- [DistributionConfig](json-schema/cloudfront-distribution-config-schema.json)
- [Origin](json-schema/cloudfront-origin-schema.json)
- [CacheBehavior](json-schema/cloudfront-cache-behavior-schema.json)
- [Invalidation](json-schema/cloudfront-invalidation-schema.json)

### JSON-LD

- [Amazon CloudFront Context](json-ld/amazon-cloudfront-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudFront](capabilities/shared/cloudfront.yaml) — 7 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Content Delivery Network Management](capabilities/content-delivery.yaml) | Amazon CloudFront | 7 | Platform Engineer |

## Vocabulary

- [Amazon CloudFront Vocabulary](vocabulary/amazon-cloudfront-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudFront Spectral Rules](rules/amazon-cloudfront-spectral-rules.yml) — 19 rules enforcing Amazon CloudFront API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
