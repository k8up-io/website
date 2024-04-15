---
title: K8up
description: Welcome to K8up - a Kubernetes Backup Operator
---

## Kubernetes Backup Operator

{{< intro >}}
K8up (pronounced /keɪtæpp/ or simply "ketchup") is a Kubernetes Operator distributed via a [Helm chart](https://github.com/k8up-io/k8up/tree/master/charts/k8up), compatible with [OpenShift](https://www.openshift.com/) and plain [Kubernetes](https://kubernetes.io/).
{{< /intro >}}

{{< cards count=3 >}}

{{< card >}}
## Self-Service
User self-service for backup and restore operations
{{< /card >}}

{{< card >}}
## Multi-Tenancy
Fully multi-tenant way to allow backups and restore
{{< /card >}}

{{< card >}}
## Metrics Included
See how your backups do and alert on misbehaviour
{{< /card >}}

{{< /cards >}}

{{< cards count=3 >}}

{{< card >}}
## Application Aware
Create application consistent backups
{{< /card >}}

{{< card >}}
## Data Archival
Regularly creation of data archivals to long term storage
{{< /card >}}

{{< card >}}
## Mulitple Backup Targets
Restic is used under the hood, support S3, SFTP, Rest, Local and many other targets
{{< /card >}}

{{< /cards >}}

## Facts

{{< columns >}}
{{< column >}}
It allows cluster operators to:

* Backup all PVCs marked as `ReadWriteMany`, `ReadWriteOnce` or with a specific label.
* Perform individual, on-demand backups.
* Schedule backups to be executed on a regular basis.
* Schedule archival (for example to AWS Glacier), usually executed in longer intervals.
* Perform "Application Aware" backups, containing the output of any tool capable of writing to `stdout`.
* Check the backup repository for its integrity.
* Prune old backups from a repository.
* Restore backups with the help of the k8up CLI tool.
{{< /column >}}
{{< column >}}
K8up is:

* Stable and production ready since 2019.
* Based on top of [restic](https://restic.net/), it can store backups in any S3-compatible storage, such as Amazon S3 or [Minio](https://github.com/minio/minio).
* Written in [Go](https://golang.org/).
* A [CNCF Sandbox](https://www.cncf.io/sandbox-projects/) Open Source project, [hosted at GitHub](https://github.com/k8up-io/k8up).
{{< /column >}}
{{< /columns >}}

{{< spacer >}}

{{< img src="/images/cncf.svg" >}}