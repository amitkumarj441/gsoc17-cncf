[![Stories in Ready](https://badge.waffle.io/amitkumarj441/gsoc17-cncf.png?label=ready&title=Ready)](https://waffle.io/amitkumarj441/gsoc17-cncf?utm_source=badge)
# Google Summer of Code 2017 - Standardizing Kubernetes Logs (CNCF)
   Code before pondering. Multipurpose learning
   
:rocket: Project tracker - Create and implement a data model to standardize Kubernetes logs (CNCF)

##  :bow:Student Portfolio

   - Name   : Amit Kumar Jaiswal
   - E-mail : amitkumarj441@gmail.com
   - Github : [amitkumarj441](https://github.com/amitkumarj441)
   - Twitter: [AMIT_GKP](https://twitter.com/AMIT_GKP)
   - Web    : https://amitkumarj441.github.io/
   
##  :tada:Links

   - [GSoC 2017 Proposal](https://docs.google.com/document/d/1SSjZR7QqkFvbt720lbDm8hZg0ckj_ixUwupIT7K3DI0/edit?usp=sharing)
   - [CNCF Blog](https://www.cncf.io/blog/2017/05/04/cncf-brings-kubernetes-coredns-opentracing-prometheus-google-summer-code-2017/)
   - [GSoC with CNCF](https://medium.com/@AMIT_GKP/gsoc-with-cncf-4d619866d01f)
   - [Waffle Board](https://waffle.io/amitkumarj441/gsoc17-cncf/)
   
## Tasks :

  - 1st Evaluation Tasks [30th May - 30th June 2017]
    
     - [x] Deploying OpenShift + Logging + ViaQ bits [ Skip MUX configuration]
     - [x] Setting up common data model used by Elasticsearch and Kibana
     - [x] Configuration of Fluentd with Testing
     
   - Mid Evaluation Tasks [30th June - 28th July 2017]
   
      - [x] Creating Pods and its configuration 
      - [x] Setting up the pipeline into Elasticsearch
      - [x] Configuring and streaming logs from Fluentd into Elasticsearch
      - [x] Launch Elasticsearch as a replication controller
   
   - Final Evaluation Tasks [28th July - 21st August 2017]
   
      - [x] Change easily fluentd pod configuration 
      - [x] Structuring Kubernetes logs  
      - [x] Create filter to rewrite "origin-node" and "origin-master" logs
      - [x] Create filter with Kubernetes logs structure
      - [x] Display Kubernetes components logs in Kibana      

## Demo!

[![GSoC with CNCF (Kubernetes)](http://img.youtube.com/vi/1SuseQnqqW8/maxresdefault.jpg)](https://www.youtube.com/watch?v=1SuseQnqqW8)

## Blog posts

   - [GSoC with Kubernetes@CNCF](https://medium.com/@AMIT_GKP/gsoc-with-cncf-4d619866d01f)
   - [GSoC 2017@CNCF](https://www.cncf.io/blog/2017/09/05/gsoc-17-create-implement-data-model-standardize-kubernetes-logs/)
   
## Pull Requests and Issues

**Repository: ViaQ**

Total Pull Requests Created/Merged: 4

   1. [ViaQ/Main#5](https://github.com/ViaQ/Main/pull/5) - Added Patch OpenShift Ansible
   2. [ViaQ/Main#10](https://github.com/ViaQ/Main/pull/10) - Updated Fluentd Pod Config
   3. [ViaQ/Main#21](https://github.com/ViaQ/Main/pull/21) - Update link [README-mux.md -> README-install.md]
   4. [ViaQ/Relp#15](https://github.com/ViaQ/Relp/pull/15) - Typo Fixed
   
**Repository: OpenShift Origin**

Total Pull Requests Created: 1

   1. [openshift/origin-aggregated-logging#517](https://github.com/openshift/origin-aggregated-logging/pull/517) - Update to Fluentd and logging components 
   
Total Issues Opened: 1

   1. [openshift/origin-aggregated-logging#549](https://github.com/openshift/origin-aggregated-logging/issues/549) - Prometheus exporter to expose metrics from Elasticsearch
   
**Repository: Kubernetes Incubator/Kubespray**

Total Pull Requests Created/Merged: 1

   1. [kubernetes-incubator/kubespray#1408](https://github.com/kubernetes-incubator/kubespray/pull/1408) - Remove deprecated `enable-cri` flag in Kubernetes 1.7
   
**Repository: Kubernetes**

Total Issues Opened: 1

   1. [kubernetes/kubernetes#51405](https://github.com/kubernetes/kubernetes/issues/51405) - Fluentd filter to process Kubernetes logs
