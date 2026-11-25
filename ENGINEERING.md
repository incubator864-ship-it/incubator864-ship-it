# Engineering notebook

## Current project

[Kubernetes and Terraform security lab](https://github.com/incubator864-ship-it/kubernetes-terraform-security-lab)

The workbench compares baseline and tuned detections against synthetic events, including malicious near matches, missing telemetry, and a documented blind spot. Twelve Python tests pass. GitHub Actions has deployed it to a disposable Kubernetes cluster and verified RBAC, nonroot execution, token mounts, filesystem restrictions, and Pod Security admission. The cluster is deleted after verification.

- [Setup and verification](https://github.com/incubator864-ship-it/kubernetes-terraform-security-lab#readme)
- [Engineering decisions](https://github.com/incubator864-ship-it/kubernetes-terraform-security-lab/blob/main/docs/engineering-notes.md)
- [Validation record](https://github.com/incubator864-ship-it/kubernetes-terraform-security-lab/blob/main/docs/validation.md)

## Topics to develop through the lab

1. Terraform plans, state, drift, and reproducible provider versions.
2. Kubernetes identity, RBAC, workload restrictions, and admission failures.
3. Audit logging and the limits of API telemetry compared with runtime telemetry.
4. Splunk ingestion and detections with documented field mappings and false positives.
5. Falcon Kubernetes coverage and integration, subject to authorized lab access.

These are planned learning topics, not completed project claims. Notes and evidence will be linked as each phase is tested.
