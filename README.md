# product-release-workflow
Repository to simulate Git Workflow Architecture for managing monthly releases.

# Monthly Release Workflow

This repository simulates a Git Workflow Architecture for managing monthly releases at Zendriix Softwares.

## Branching Strategy

- `main`: Production-ready code.
- `develop`: Integration branch.
- `feature/*`: New features.
- `release/*`: Preparing new releases.
- `hotfix/*`: Urgent fixes.

## Simulation Steps

1. Created feature branches and merged into `develop`.
2. Created release branches and merged into `main` and `develop`.
3. Applied hotfixes directly to `main` and merged back into `develop`.

## Repository Link

[GitHub Repository](https://github.com/navin-kumar10/monthly-release-workflow)

