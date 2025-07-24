# Kernel Platform Manifest Sync and Usage Guide

This repository contains the manifest for synchronizing source code repositories related to the Xiaomi SM8450 kernel platform.

The manifest and related projects are maintained on the branch [lineage-22.2](https://github.com/pavelc4-playground/kernel_manifest/tree/lineage-22.2).

---

## Prerequisites

Before syncing the repositories, ensure you have the following installed on your Linux system:

- Git  
- Repo
  
---

## How to Sync the Repositories

1. **Create a working directory, initialize repo with manifest, and sync all projects:**

   ```bash
   mkdir kernel_platform
   cd kernel_platform
   
2. **Initialize repo with manifest:**

   ```bash
     repo init -u https://github.com/marble-indonesia/kernel_manifest.git -b lineage-22.2 

3. **Sync source:**
    ```bash
     repo sync -j32
