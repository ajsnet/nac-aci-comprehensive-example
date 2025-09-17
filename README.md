[![Terraform Version](https://img.shields.io/badge/terraform-%5E1.8-blue)](https://www.terraform.io)

# Network-as-Code - Comprehensive example for ACI

This example is part of the Cisco [*Network as Code*](https://netascode.cisco.com) project. Its goal is to allow users to instantiate network fabrics in minutes using an easy to use, opinionated data model. It takes away the complexity of having to deal with references, dependencies or loops. By completely separating data (defining variables) from logic (infrastructure declaration), it allows the user to focus on describing the intended configuration while using a set of maintained and tested Terraform Modules without the need to understand the low-level ACI object model. More information can be found here: [https://netascode.cisco.com/solutions/aci/comprehensive_example](https://netascode.cisco.com/solutions/aci/comprehensive_example).

# Purpose of this project
This project is a fork of http://github.com/netascode/nac-aci-comprehensive-example.  The purpose is to explore editing the sample configuration to leverage the built-in ACI functionality that creates "system-" objects that was added to ACI in version 5.2.7 rather than relying on templates for groups/policy names or manually managing the same.  The fabric settings will also be altered such that it will work by default with ACI Simulator, which is a common/likely target use case for this example.

