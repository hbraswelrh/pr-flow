---
x-trestle-global:
  sort-id: sys-01.06.a19
---

# sys-1.6.a19 - \[REPLACE_ME\] Including Data Stores In Containers

## Control Statement

(1) Containers SHOULD ONLY be able to access the mass storage and directories necessary for operation. (2) Permissions SHOULD only be explicitly assigned where needed. (3) If the container runtime for a container includes local storage, the access rights in the file system SHOULD be restricted to the service account of the container. (4) If network storage is used, the permissions SHOULD be set on the network storage itself
