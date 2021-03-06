# etcd Documentation Project Plan

This repository is created to track and share the etcd and etcd-operator documentation plan with stakeholders.

## High Level Objectives

* Create documentation for new features.
* Create documentation for UI changes.
* Respond to documentation defects on various forums.
* Create documentation for etcd-related features in other product lines

## Assumptions and Risks

* Developers' time is limited and priced
* Severity and priority of a defect or feature are not always known
* Documentation resource might need support in setting up complex test deployment

## Engineering Resources

* Xiang Li
* Anthony
* Haseeb
* Hongchao Deng
* gyuho lee
* Colin (solution engineering)
* Duffie Cooley (solution engineering)
* Brandon Philips (CTO)

## Documentation

* Radhika

## Doc Management

Kevin Mitts

## Etcd Documentation Deliverables and Outlines

The Documentation plan is derived from discussions with the Engineering manager, Xiang Li. The following table lists the high level list of tasks and approximate timeline for completion.

Feature | Feature Contact (tech review) | Engineering Contact | Sol Eng / Field / Support Contact | Peer Reviewers | Effort(days) |  Approx date of completion |Status | 
--- | --- | --- | --- |--- |--- |--- |--- |
Update Kubernetes upstream doc | Xiang Li | Xiang Li | Caleb Miles |Kubernetes upstream Doc SIG |7 days | unknown |PR submitted on 6/13 - awiting feedback. Pinged on Kubernetes doc-sig |
Building etcd (Documentation/dl_build.md) | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 6/16 |merged |
Setting up local cluster (Documentation/dev-guide/local_cluster.md) | Anthony /Haseeb/ | Xiang | unknown |Anthony | 3 |6/20 |submitted PR |
Interacting with etcd (Documentation/dev-guide/interacting_v3.md) | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 6/23 |might need to re-org with content in other files|
gprc gateway(dev-guide/api_grpc_gateway.md)| Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 2 | 6/28 ||
gRPC naming and discovery (dev-guide/grpc_naming.md) | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 3 | 7/3  ||
gPRC proxy(op-guide/grpc_proxy.md) | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/6 ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
--- | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 4 | 7/ ||
Updating glossary terms (developing concept docs) | Anthony /Haseeb/gyuho lee | Xiang| unknown |Anthony | 7 | 7/30 |on-going|



## Etcd-Operator Documentation Deliverables and Outlines

Feature | Feature Contact (tech review) | Engineering Contact | Sol Eng / Field / Support Contact | Peer Reviewers | Effort(days) |  Approx date of completion |Status | 
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |
--- | --- | --- | --- |--- |--- |--- |--- |

## Related Documentation Tasks

Disaster recovery of clusters (Tectonic/Bootkube/etcd). Under research mode.
Ref: 
     [disaster recovery](https://github.com/diegs/bootkube/blob/1090923ac1caeef3dfed6ceb1b533c36232cd0a1/Documentation/disaster-recovery.md)

     https://github.com/coreos-inc/tectonic/pull/1736
