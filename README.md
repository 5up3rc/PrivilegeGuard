### Introduction

PrivilegeGuard blocks common local privilege escalation in Linux Kernel.

### How does it work?

Unless a binary is owned by root and has SUID bit set, all calls to `commit_creds()` would be rejected.

### Compatibilities

Tested on Arch Linux, Kernel version 3.9.6 (Compatiable with GRsec patch set)
