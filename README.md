# gh-action

## Purpose

This repository serves as a **webhook event source** for GitHub webhook testing and assessment purposes. It is designed to trigger GitHub events that will be sent to the `gh-webhook` repository via configured webhooks.

## Events Generated

This repository generates the following GitHub events:

- **Push**: Triggered when code is pushed to any branch
- **Pull Request**: Triggered when a pull request is opened
- **Merge**: Triggered when a pull request is merged

## Webhook Usage

This repository is configured to send webhook events to the `gh-webhook` endpoint. The webhook configuration is done manually in the GitHub repository settings and is not included in this codebase for security reasons.

## Assessment Purpose

This repository exists solely for assessment/testing purposes and is intentionally minimal. It contains no backend code - only files necessary to generate GitHub events.

## How to Use

1. Configure a webhook in this repository's GitHub settings pointing to your `gh-webhook` endpoint
2. Perform actions in this repository (push, create PR, merge PR) to trigger events
3. Events will be automatically sent to the configured webhook endpoint

---

**Note**: This repository is part of a GitHub webhook integration assessment.
