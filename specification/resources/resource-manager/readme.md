# Resource
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Resource.



---
## Getting Started 
To build the SDK for Resource, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration for generating APIs


---
#### Basic Information 
These are the global settings for the Resource API.

``` yaml
# common 
title: Resource
description: Resource Client
openapi-type: arm
tag: package-2017-05

```


# Tag: package-2017-05

These settings apply only when `--tag=package-2017-05` is specified on the command line.

``` yaml $(tag) == 'package-2017-05'
input-file:
- Microsoft.Authorization/2016-09-01/locks.json
- Microsoft.Authorization/2016-12-01/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2017-05-10/resources.json
- Microsoft.Resources/2016-06-01/subscriptions.json
- Microsoft.Scheduler/2016-09-01/links.json
- Microsoft.Solutions/2016-09-01-preview/managedapplications.json

```
 
# Tag: package-2016-09

These settings apply only when `--tag=package-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-2016-09'
input-file:
- Microsoft.Authorization/2016-09-01/locks.json
- Microsoft.Authorization/2016-04-01/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2016-09-01/resources.json
- Microsoft.Resources/2016-06-01/subscriptions.json
- Microsoft.Resources/2016-09-01/links.json

```
 
# Tag: package-2016-07

These settings apply only when `--tag=package-2016-07` is specified on the command line.

``` yaml $(tag) == 'package-2016-07'
input-file:
- Microsoft.Authorization/2015-01-01/locks.json
- Microsoft.Authorization/2016-04-01/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2016-07-01/resources.json
- Microsoft.Resources/2016-06-01/subscriptions.json

```
 
# Tag: package-2016-06

These settings apply only when `--tag=package-2016-06` is specified on the command line.

``` yaml $(tag) == 'package-2016-06'
input-file:
- Microsoft.Authorization/2015-01-01/locks.json
- Microsoft.Authorization/2016-04-01/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2016-02-01/resources.json
- Microsoft.Resources/2016-06-01/subscriptions.json

```
 
# Tag: package-2016-04

These settings apply only when `--tag=package-2016-04` is specified on the command line.

``` yaml $(tag) == 'package-2016-04'
input-file:
- Microsoft.Authorization/2015-01-01/locks.json
- Microsoft.Authorization/2016-04-01/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2016-02-01/resources.json
- Microsoft.Resources/2015-11-01/subscriptions.json

```
 
# Tag: package-2016-02

These settings apply only when `--tag=package-2016-02` is specified on the command line.

``` yaml $(tag) == 'package-2016-02'
input-file:
- Microsoft.Authorization/2015-01-01/locks.json
- Microsoft.Authorization/2015-10-01-preview/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2016-02-01/resources.json
- Microsoft.Resources/2015-11-01/subscriptions.json

```
 
# Tag: package-2015-12

These settings apply only when `--tag=package-2015-12` is specified on the command line.

``` yaml $(tag) == 'package-2015-12'
input-file:
- Microsoft.Authorization/2015-01-01/locks.json
- Microsoft.Authorization/2015-10-01-preview/policy.json
- Microsoft.Features/2015-12-01/features.json
- Microsoft.Resources/2015-11-01/resources.json
- Microsoft.Resources/2015-11-01/subscriptions.json

```


---
#### Language-specific settings: CSharp

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  # override the default output folder
  output-folder: $(output-folder)/csharp
```
