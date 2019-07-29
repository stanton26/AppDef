---
layout: single
title: "What is Appdefense?"
permalink: /workshop-manual-partner/
date: 2018-06-01
tags: workshop
classes: wide
author_profile: false
---
# Introduction

AppDefense is a data center endpoint security product that protects applications running in a virtualized environment.

AppDefense learns the intended state of set applications, and responds if the app deviates from its intended state.

# How does it work? 
AppDefense works inside the vSphere hypervisor to learn and monitor the behavior of an application running in the VM (virtual machine). 

The chance of AppDefense being compromised is greatly reduced due to its position inside the vSphere hypervisor. 

AppDefense takes a proactive approach by learning and understanding an application's intended state of behavior. After learning the intended state, AppDefense automatically responds if behavior deviates from the intended state.
 
After AppDefense detects a threat, AppDefense automates a response using vSphere and NSX DataCenter allowing for: 
- Block process communication. 
- Snapshot an endpoint for forensic analysis.
- Suspend or shut down endpoint.

### Workshop URL's

Appdefense Manager Login <https://appdefense.vmware.com/app/sign-in-user>

Learn how Appdefense works from Tom Corn: <https://www.youtube.com/watch?v=HiJgn6GGX5w>

Get an overview of the Appdefense quick start guide by Stanton Thomas:





## Labs

Lab Name | Description
[Working-with-your-SDDC](https://vmc-field-team.github.io/labs-partner/working-with-sddc-partner-lab/){:target="_blank"} | Learn the basics of running a a VMware Cloud on AWS SDDC environment
[AWS-Integration](https://vmc-field-team.github.io/labs-partner/aws-integration-partner-lab/){:target="_blank"} | Learn how to integrate with native AWS services such as RDS and EFS
[Distributed-Firewall](https://vmc-field-team.github.io/labs-partner/distributed-firewall-partner-lab/){:target="_blank"} | Learn the basics on how to create east-west firewall rules using NSX Distributed Firewall Capabilities
[Workload-Operations](https://vmc-field-team.github.io/labs-partner/workload-operations){:target="_blank} | Go through some of the basic operations of VM deployment and monitoring
[API-Lab](https://vmc-field-team.github.io/labs-partner/api-partner-lab){:target="_blank"} | Learn the basics of API operations on VMware Cloud on AWS 
[VPN-Lab](https://vmc-field-team.github.io/labs-partner/vpn-lab){:target="_blank"} | Learn the basics of configuring a VPN on VMware Cloud on AWS
[Site-Recovery-Lab](https://vmc-field-team.github.io/labs-partner/site-recovery-lab) | Learn the basics of enabling Site Recovery and configuring cloud to cloud DR