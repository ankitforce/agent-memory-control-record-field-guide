# Agent Memory Control Record Field Guide

Reusable artifacts for defining, enforcing, and auditing an AI agent's memory lifecycle.

Canonical article: [The Agent Memory Control Record](https://ankitkumar3514.substack.com/agent-memory-control-record)

## Start here

1. Read [docs/operating-model.md](docs/operating-model.md).
2. Validate a record with [schemas/memory-control-record.schema.json](schemas/memory-control-record.schema.json).
3. Adapt [templates/memory-control-record.example.json](templates/memory-control-record.example.json).
4. Use [checklists/implementation-checklist.md](checklists/implementation-checklist.md) before rollout.

## For people

Use this package to make data classification, scope, retention, change authority, and enforcement evidence explicit before enabling persistent agent memory.

## For agents

Read [AGENTS.md](AGENTS.md) before producing or modifying a record. Do not invent data classifications, retention periods, or approval identities.

## Included and excluded

Included: a portable record schema, example, controls, and implementation checklist.

Excluded: provider credentials, production customer data, provider-specific deployment scripts, and legal retention advice.
