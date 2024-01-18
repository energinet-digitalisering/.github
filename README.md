# Digital Incubator

A mono repository that contains all the code, infrastructure, and documentation for the Digital Incubator department at Energinet.

## Getting Started

This is a monorepo and it relies on Git submodules to include code from other repositories in the Digital Incubator. Therefore, after cloning the repo, you need to run the following command:

```bash
git submodule update --init --recursive
```

Alternatively you can clone the monorepo with the `--recurse-submodules` flag:

```bash
git clone --recurse-submodules git@github.com:energinet-digitalisering/.github.git
```

> [!NOTE]
> Submodules are configured to clone with SSH, so it requires adding your public SSH key to DevOps and GitHub, respectively. You will not be able to clone the submodules with HTTPS. This decision was made, as HTTPS will require authentication on every request, where as SSH can do this automatically when the public key is shared.

## Overview

<!-- readme-tree start -->
```

```
<!-- readme-tree end -->

## Contribution

To contribute to the monorepo issues and pull requests should be created in the respective repository where the change is being made. If the change is cross-cutting, then issues and pull requests should be created for each change required in the respective repositories.
