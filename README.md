# Increase-Pod-Limits-using-VPC-CNI-Plugin
Increase Pod Limits on worker nodes using VPC-CNI Plugin

In EKS, there is a default limit for a limited amount of pods to get scheduled on worker nodes. This usually ends up in under-utilization of instances inspite of having available CPU, memory and also when there are sufficient available IPs in the subnets. This also adds to additional costs incurred for the new instances launched due to scaling operation for scheduling the remaining pods.

This document describes steps to increase the pod limits on instances using VPC-CNI plugin only.
