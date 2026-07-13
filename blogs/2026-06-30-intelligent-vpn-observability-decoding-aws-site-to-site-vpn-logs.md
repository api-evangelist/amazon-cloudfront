---
title: "Intelligent VPN Observability: Decoding AWS Site-to-Site VPN Logs"
url: "https://aws.amazon.com/blogs/networking-and-content-delivery/intelligent-vpn-observability-decoding-aws-site-to-site-vpn-logs/"
date: "2026-06-30"
author: ""
feed_url: "https://aws.amazon.com/blogs/networking-and-content-delivery/feed/"
---
This post introduces a serverless observability pipeline for AWS Site-to-Site VPN using BGP and IKE logging, combining CloudWatch Logs subscription filters, Amazon SQS FIFO deduplication, and Amazon Bedrock analysis to correlate BGP and IKE logs into a single timeline. It delivers consolidated incident reports via Amazon SNS email or AWS DevOps Agent integrations with Slack and ticketing systems, reducing VPN troubleshooting time.
