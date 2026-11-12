# Quantum Metric for Codex and ChatGPT

Analyze funnels, errors, friction and session replays in Quantum Metric to find and fix digital experience issues.

## Install

**ChatGPT:** go to chatgpt.com/plugins, select + › Add custom MCP server, enter a name and `https://api.quantummetric.com/mcp`, set Authentication to OAuth, create the plugin, then install it.

**Codex:**

```bash
codex plugin marketplace add https://github.com/quantummetric/qm-plugin-codex.git
```

## Configure

The server uses Quantum Metric sign-in (OAuth). Every call runs as you, with your role, permissions, workspace and timezone. No token is created or stored.

| Setting | Value |
|---|---|
| Endpoint | `https://api.quantummetric.com/mcp` |
| Subscription | Chosen when you sign in |

## Skills

- `getting-started`: confirms the subscription, workspace and timezone, and fixes common connection problems
- `data-analysis`: answers funnel, conversion, error and trend questions with verified numbers
- `session-review`: explains what a user experienced in one or more sessions

## Support

support@quantummetric.com

## Privacy

[Quantum Metric Privacy Policy](https://www.quantummetric.com/legal/privacy-policy)

## Terms

[Quantum Metric Terms and Conditions](https://iam.quantummetric.com/terms-and-conditions)

## License

MIT
