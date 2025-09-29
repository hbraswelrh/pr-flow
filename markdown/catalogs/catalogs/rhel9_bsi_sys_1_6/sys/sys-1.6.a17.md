---
x-trestle-global:
  sort-id: sys-01.06.a17
---

# sys-1.6.a17 - \[REPLACE_ME\] Running Containers Without Privileges

## Control Statement

(1) A container runtime and any instantiated containers SHOULD only be executed by a non- privileged system account that does not have (and cannot gain) elevated rights to the container service or host operating system. (2) The container runtime SHOULD be encapsulated by additional measures, such as using the virtualisation extensions of CPUs. (3) If containers are to take over tasks of the host system in exceptional cases, privileges on the host system SHOULD be limited to the minimum necessary. (4)Exceptions SHOULD be adequately documented.
