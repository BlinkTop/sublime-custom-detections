# Sublime Custom Detections

Custom Sublime Security detection rules and supporting artifacts for interview/demo lab work.

## Structure

- `detection-rules/` - production-ready Sublime detection rules in `.yml` format.
- `lists/` - reference lists used by rules, if needed.
- `tests/` - test cases, notes, and sample expectations for rule development.

## Rule Format

Sublime rule files should use `.yml` and include at minimum:

```yaml
name: "Rule name"
description: "What the rule detects and why it matters."
type: rule
source: |
  type.inbound
```

Do not add draft `.yml` files unless they are intended for Sublime to ingest. Keep experimental notes in Markdown until the rule is ready.
