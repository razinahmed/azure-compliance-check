# Azure Compliance Check

![Security](https://img.shields.io/badge/Security-Tool-red)
![Bash](https://img.shields.io/badge/Bash-Script-green)
![Azure](https://img.shields.io/badge/Azure-Cloud-blue)
![License](https://img.shields.io/badge/License-MIT-blue)

An Azure compliance auditing tool that validates cloud resource configurations against security benchmarks and regulatory standards such as CIS, NIST, and SOC 2.

## Description

Azure Compliance Check automates the assessment of Azure resource configurations to ensure they meet industry compliance standards. It scans subscriptions, resource groups, and individual resources for policy violations, generating actionable reports with remediation guidance.

## Features

- Automated compliance scanning for Azure subscriptions
- CIS Azure Foundations Benchmark checks
- NIST 800-53 and SOC 2 control mapping
- Network Security Group (NSG) rule validation
- Storage account encryption and access policy checks
- Identity and access management (IAM) auditing
- Compliance report generation with pass/fail status
- Makefile-based build and test workflow

## Tech Stack

- **Language:** Bash
- **Platform:** Microsoft Azure
- **Tools:** Azure CLI (`az`)
- **Target OS:** Linux / macOS / WSL
- **Build Tool:** GNU Make

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/azure-compliance-check.git
cd azure-compliance-check

# Install Azure CLI if not already installed
# https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

# Authenticate with Azure
az login

# Run compliance checks
make build
make test
```

## Usage

```bash
# Build and test
make build
make test
```

## Project Structure

```
azure-compliance-check/
  styles/
    theme.css          # UI theme configuration
  Makefile             # Build and test automation
  SECURITY.md          # Security policy
  LICENSE              # MIT License
```

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
