# Galagit Lint Infrastructure

Standalone linting rules and scripts for Rust projects.

## Contents

- `lint/ast-rules/` - ast-grep YAML rules
- `lint/custom-rules/` - Custom script-based lint rules  
- `nix/scripts/` - Lint runner and pre-commit hooks
- `sgconfig.yml` - ast-grep configuration

## Usage

This repo is designed to be composed into other projects via galagit virtual workspaces,
or can be used directly by copying the contents.
