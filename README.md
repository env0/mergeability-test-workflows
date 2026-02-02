# Mergeability Test Workflows

This is a **public repository** used for testing org-level required workflow rulesets.

## Purpose

GitHub org-level rulesets can require workflows from public repositories to pass before merging. This repo hosts test workflows for [env0/mergeability-qa-test](https://github.com/env0/mergeability-qa-test).

## Workflows

- `required-workflow.yml` - Simple workflow that can be required via org-level ruleset

## Usage

This repo is referenced by org-level rulesets to test the `requiredWorkflows` field in the GitHub GraphQL API for PR mergeability.
