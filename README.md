# CloudFormation Nexus

In this repository I have collected a number of generic CloudFormation templates that are quite opinionated on form and function.

For example, in most cases Parameters are alphabetically sorted in order to improve readibility and thumb searching.

All parameters are prefaced with a namespace indicating the type of resource they are. This serves to better group them and makes understanding the template easier.

Namespacing for all declarations follows the convention of: 
- Resource
- Environment
- Specific Attributes

At the top of each YAML template is the following:
- AWSTemplateFormatVersion
- Description (brief explanation of template for reference in CloudFormation console)
- Metadata
    - Author
    - Description (further overview of template; explanation of syntax, conventions; any latest changes worth noting)

Every YAML template will have the following sections:
- Parameters
- Resources
- Outputs

Optional sections include:
- Conditions (placed before Resources)

