# test-actions-public

This repository contains GitHub Actions workflows for testing different runner environments.

## Workflows

### ARM Ubuntu Workflow
- **File**: `.github/workflows/arm-workflow.yml`
- **Runner**: `ubuntu-22.04-arm`
- **Purpose**: Tests functionality on ARM-based Ubuntu 22.04 runners
- **Features**:
  - System information display
  - Architecture verification
  - Basic development tools testing
  - Simple C program compilation and execution

The workflow runs on push, pull requests, and can be manually triggered via workflow_dispatch.