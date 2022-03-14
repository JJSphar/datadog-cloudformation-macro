# datadog-cloudformation-macro

This repository contains Datadog CloudFormation macros to use with raw CloudFormation templates or SAM/CDK deployments.

* [Datadog Serverless Macro](https://github.com/DataDog/datadog-cloudformation-macro/tree/master/serverless): installs Datadog Lambda Library to Python and Node.js Lambda functions to collect custom metrics and traces

This fork contains some small quality-of-life changes to:
* Not override explictly-provided environment variable tags
* Apply env and service tags to other Serverless resources in the template
