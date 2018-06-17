---
name: AWS Lambda
x-slug: aws-lambda
description: AWS Lambda is a zero-administration compute platform for back-end web
  developers that runs your code for you in the AWScloudand provides you with a fine-grained
  pricing structure. AWS Lambda runs your back-end code on its own AWS compute fleet
  of Amazon Elastic Compute Cloud (Amazon EC2) instances across multiple Availability
  Zones in a region, which provides the high availability, security, performance,
  and scalability of the AWS infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Aliases
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Lambda API Create Alias
  x-api-slug: aws-lambda-api
  description: Creates an alias that points to the specified Lambda function version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=CreateAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/actioncreatealias-get-openapi.md
- name: AWS Lambda API Delete Alias
  x-api-slug: aws-lambda-api
  description: Deletes the specified Lambda function alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=DeleteAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/actiondeletealias-get-openapi.md
- name: AWS Lambda API Get Alias
  x-api-slug: aws-lambda-api
  description: "Returns the specified alias information such as the alias ARN, description,
    and function version it \n      is pointing to."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=GetAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/actiongetalias-get-openapi.md
- name: AWS Lambda API List Aliases
  x-api-slug: aws-lambda-api
  description: Returns list of aliases created for a Lambda function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=ListAliases
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/actionlistaliases-get-openapi.md
- name: AWS Lambda API Update Alias
  x-api-slug: aws-lambda-api
  description: Using this API you can update the function version to which the alias
    points and the alias description.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=UpdateAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/actionupdatealias-get-openapi.md
- name: AWS Lambda API
  x-api-slug: aws-lambda-api
  description: AWS Lambda is a zero-administration compute platform for back-end web
    developers that runs your code for you in the AWScloudand provides you with a
    fine-grained pricing structure. AWS Lambda runs your back-end code on its own
    AWS compute fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances across
    multiple Availability Zones in a region, which provides the high availability,
    security, performance, and scalability of the AWS infrastructure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aliases/master/_listings/aws-lambda/openapi.md
x-common:
- type: x-authentication
  url: http://docs.aws.amazon.com/lambda/latest/dg/lambda-auth-and-access-control.html
- type: x-best-practices
  url: http://docs.aws.amazon.com/lambda/latest/dg/best-practices.html
- type: x-console
  url: https://console.aws.amazon.com/lambda
- type: x-documentation
  url: http://docs.aws.amazon.com/lambda/latest/dg/API_Reference.html
- type: x-faq
  url: https://aws.amazon.com/lambda/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=186
- type: x-getting-started
  url: https://aws.amazon.com/lambda/getting-started/
- type: x-logging
  url: http://docs.aws.amazon.com/lambda/latest/dg/logging-using-cloudtrail.html
- type: x-partners
  url: https://aws.amazon.com/lambda/partners/
- type: x-pricing
  url: https://aws.amazon.com/lambda/pricing/
- type: x-rate-limits
  url: http://docs.aws.amazon.com/lambda/latest/dg/limits.html
- type: x-road-map
  url: http://aws.amazon.com/releasenotes/
- type: x-use-cases
  url: http://docs.aws.amazon.com/lambda/latest/dg/use-cases.html
- type: x-website
  url: http://docs.aws.amazon.com/lambda/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---