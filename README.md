# feature-flag-auditor

Summarize feature-flag state and flag stale rollout configuration.

## Run

Requires Node.js 20+.

```sh
npm start
```

The tool reads its development gateway settings from `config/development.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.
