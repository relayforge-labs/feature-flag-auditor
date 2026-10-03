# feature-flag-auditor

Summarize feature-flag state and flag stale rollout configuration.

## Run

Requires Node.js 20+.

```sh
npm start
```

The tool reads its development gateway settings from `config/development.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.

## Model

This example targets the `gpt-6-luna` frontier model through the configured OpenAI-compatible router.
