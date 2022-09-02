- [AWS Cfn Lint Atom](https://atom.io/packages/atom-cfn-lint#:~:text=Atom-cfn-lint%20will%20work%20with%20JSON%20and%20YAML%20files,assuming%20that%20the%20file%20is%20a%20CloudFormation%20template.)
- [parameters - 1](https://aws.amazon.com/blogs/devops/using-the-new-cloudformation-parameter-types/#:~:text=CloudFormation%20currently%20supports%20the%20following%20parameter%20types%3A%201,8%20AWS%3A%3AEC2%3A%3AVPC%3A%3AId%20%E2%80%93%20A%20VPC%20ID%20More%20items)
- [parameters - 2](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html)
- [Pseudo parameter](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/pseudo-parameter-reference.html)
- [Depends On](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-dependson.html)
- [Intrinsic functions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)
- [Deleting Policy](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-deletionpolicy.html)

Advanced Concepts & 3rd Party Tools
Former2
Former2 allows you to generate IaC (ex. CloudFormation templates) from existing resources https://github.com/iann0036/former2

Everything happens in the browser (it’s a client-side web app)

Requires IAM keys with ReadOnlyAccess

The following outputs are currently supported:

CloudFormation templates

Terraform

Troposphere

CDK (Cfn Primitives) – TypeScript, Python, C#, Java

CDK for Terraform – TypeScript

Pulumi – TypeScript

Diagram – an embedded version of draw.io


TaskCat
A tool that automates the testing of CloudFormation templates https://github.com/aws-quickstart/taskcat

Deploys your template in multiple AWS Regions simultaneously

Generates a report with a pass/fail result for each Region

You provide

AWS Regions and the number of AZs you want to include in the test

Template parameters’ values



cfn-nag
A tool that looks for patterns in CloudFormation templates that may indicate insecure infrastructure https://github.com/stelligent/cfn_nag

Examples:

IAM rule and Security Group rules that are too permissive (wildcards)

Access logs and Encryption that aren’t enabled

Password literals



CloudFormation cheatsheet
Summarizes the usage of !Ref and !GetAtt with CloudFormation resources https://theburningmonk.com/cloudformation-ref-and-getatt-cheatsheet/



aws-cfn-template-flip
A tool that converts CloudFormation templates between JSON and YAML formats https://github.com/awslabs/aws-cfn-template-flip



cfn-diagram
A tool to visualize CloudFormation/SAM/CDK templates as diagrams https://github.com/mhlabs/cfn-diagram

Generates https://draw.io and HTML diagrams

Select only the resources you want (filter by resource type/name)

Different layouts

Supports JSON and YAML



cfn-format
A tool that reads a CloudFormation template and outputs a cleanly-formatted copy adhering to CloudFormation standards https://github.com/awslabs/aws-cloudformation-template-formatter



awesome-cloudformation
Reference list for open-source projects related to CloudFormation: https://github.com/aws-cloudformation/awesome-cloudformation



