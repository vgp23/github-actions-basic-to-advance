# GitHub Actions: Basic to Advanced

This repository is a comprehensive learning resource for GitHub Actions, containing multiple practical examples and workflows that demonstrate automation techniques ranging from basic to advanced levels.

## 📋 Repository Structure

```
.github/
├── workflows/          # GitHub Actions workflow definitions
│   ├── basic_1.yaml
│   ├── basic_2.yaml
│   ├── medium.yaml
│   ├── advanced_1.yaml
│   ├── advanced_2.yaml
│   └── reusable-simple.yaml
└── actions/            # Custom GitHub Actions
    ├── composite/      # Composite actions combining multiple actions
    ├── js-actions/     # JavaScript-based custom actions
    └── jenkins-python-actions/  # Jenkins integration with Python
docs/
├── Osama_GitHub_Actions.pdf    # Comprehensive GitHub Actions documentation
python-src/
├── script.py           # Python scripts used in workflows
├── requirements.txt    # Requirement files used by script
script-src/
├── script.sh           # Shell scripts used in workflows
```

## Workflow Examples

### 🟢 Basic Workflows

**Files:** `basic_1.yaml`, `basic_2.yaml`

Simple workflow examples demonstrating:
- Triggering on `push`, `pull_request`, and `issues` events
- Using GitHub Action secrets
- `schedule` with cron expressions for automated recurring tasks
- Multiple jobs and dependencies


> **Use case:** Getting started with GitHub Actions, running basic CI tasks like tests and linting.

### 🟡 Medium Workflows

**File:** `medium.yaml`

Intermediate workflow examples featuring:
- `workflow_dispatch` for manual triggering via GitHub UI


> **Use case:** Running tasks that requires input such as a Python script

### 🔴 Advanced Workflows

**Files:** `advanced_1.yaml`, `advanced_2.yaml`

Sophisticated workflows combining:
- **Docker containers** as job environments
- **JavaScript GitHub Actions** for custom scripting
- **Composite Actions** for reusable action combinations
- **Reusable workflows** for DRY principles

**Custom Actions:**
- `js-actions/` - JavaScript-based custom action
- `composite/` - Composite action bundling multiple steps
- `jenkins-python-actions/` - Jenkins integration with Python

> **Use case:** Building modular, maintainable, scalable CI/CD pipelines with reusable components.


## Getting Started

1. Fork and clone this repository:
   ```bash
   git clone https://github.com/your-username/github-actions-basic-to-advance.git
   cd github-actions-basic-to-advance
   ```
2. Explore the workflows in `.github/workflows/` to understand different automation patterns

3. Review the custom actions in `.github/actions/` to learn how to create reusable components

4. Check the `docs/Osama_GitHub_Actions.pdf` for comprehensive documentation

5. A change
---