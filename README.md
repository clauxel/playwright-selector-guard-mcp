# Playwright Selector Guard MCP

Detect brittle Playwright selectors and route safe healing suggestions.

Paid remote MCP for Playwright selector risk checks, healing suggestions, action receipts, human approvals, and failure exports.

## Public Endpoints

- Website: https://playwrightselectorguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://playwrightselectorguard.clauxel.com/mcp
- Server card: https://playwrightselectorguard.clauxel.com/server-card.json
- Registry name: `com.clauxel.playwrightselectorguard/playwrightselectorguard-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_selector_risk`
- `suggest_selector_healing`
- `record_action_receipt`
- `request_human_approval`
- `export_selector_failure`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://playwrightselectorguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://playwrightselectorguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://playwrightselectorguard.clauxel.com/server-card.json
- MCP endpoint: https://playwrightselectorguard.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
