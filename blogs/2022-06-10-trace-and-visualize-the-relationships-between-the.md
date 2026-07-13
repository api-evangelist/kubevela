---
title: "Trace and visualize the relationships between the kubernetes resources with KubeVela"
url: "https://kubevela.io/blog/2022/06/10/visualize-resources/"
date: "2022-06-10"
feed_url: "https://kubevela.io/blog/rss.xml"
---
One of the biggest requests from KubeVela community is to provide a transparent delivery process for resources in the application. For example, many users prefer to use Helm Chart to package a lot of complex YAML, but once there is any issue during the deployment, such as the underlying storage can not be provided normally, the associated resources are not created normally, or the underlying configuration is incorrect, etc., even a small problem will be a huge threshold for troubleshooting due to the black box of Helm chart. Especially in the modern hybrid multi-cluster environment, there is a
