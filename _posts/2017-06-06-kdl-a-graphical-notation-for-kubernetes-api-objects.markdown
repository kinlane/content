---
title: 'KDL: A Graphical Notation for Kubernetes API Objects'
date: 2017-06-06 20:50:00 Z
---

[I am learning about Kubernetes Deployment Language (KDL) today](https://blog.openshift.com/kdl-notation-kubernetes-app-deploy/), trying to understand their approach to defining their notion of Kubernetes API objects. It feels like an interesting evolution in how we define our infrastructure, and begin standardizing the API layer for it so that we can orchestrate as we need.

They are standardizing the Kubernetes API objects into the following buckets:

Cluster - The orchestration level of things.
Compute - The individual compute level.
Networking - The networking layer of it all.
Storage - Storage behind our APIs.

This has elements of my API lifecycle research, as well as a containerized, clustered, BaaS 2.0 in my view. Standardizing how we define and describe the essential layers of our infrastructure. I can see standardizing the testing, monitoring, performance, security, and other critical aspects of doing this at scale.

I'm fascinated at how fast YAML has become the default orchestration template language for folks in the cloud containerization space. I'll add KDL to my API definition and container research and keep an eye on what they are up to, and keep an eye out for other approaches to standardizing the API layer for deploying, managing, and scaling our API infrastructure.