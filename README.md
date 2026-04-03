# Spatial Epi Lab Handbook

Welcome to the **Spatial Epi Lab GitHub organization**.

This GitHub space is a shared home for lab code, project documentation, and reproducible research workflows. The goal is to make scripts, methods, and project structure easier to find, understand, and reuse.

## What this GitHub organization is for

This organization is intended to serve as a simple, transparent, and durable place to store:

- analysis code
- scripts and reusable functions
- notebooks
- methods notes
- project-level documentation
- figure and table generation workflows
- environment/setup files

The emphasis is on **code and documentation**, not raw data storage or day-to-day communication.

## What should go here

Examples of content that belong in this GitHub organization include:

- Python, R, or other analysis scripts
- Jupyter notebooks or Quarto documents
- workflow documentation
- project README files
- code used to generate manuscript figures and tables
- small example datasets that are open and non-sensitive
- package/environment files such as `requirements.txt`, `environment.yml` etc. 

## What should NOT go here

The following should generally **NOT** be stored in GitHub:

- raw data
- large datasets
- sensitive or restricted data
- protected health information (PHI)
- passwords, tokens, or API keys
- messy temporary files
- local machine-specific outputs
- unpublished materials that are not ready to be shared within the lab, let's aim to be cautious first with sharing 

When in doubt, GitHub should hold the **code and documentation needed to understand or reproduce the work**, while data should live in the appropriate approved storage location.

## Organization philosophy

This GitHub organization is meant to be lightweight and useful.

It is **not** intended to create extra process or overhead. Instead, it should help lab members:

- know where to look for project code
- understand what a repository contains
- pick up or revisit work more easily
- share methods in a transparent way
- support reproducibility over time

## Recommended repository structure

Most project repositories should follow a simple structure something like:

```text
project-name/
├── README.md
├── docs/
├── src/
├── notebooks/
├── outputs/
└── environment.yml
