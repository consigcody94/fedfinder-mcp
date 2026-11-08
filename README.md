# FedFinder MCP connector

Research government contracting opportunities in your AI workspace. Connect your FedFinder account, inspect source evidence and decide which opportunities deserve a pursuit.

[Website](https://www.fedfinder.net) · [Create an account](https://www.fedfinder.net/signup) · [Connection guide](https://www.fedfinder.net/connector-docs/connect) · [Pricing](https://www.fedfinder.net/pricing)

## Connect the hosted server

Add a remote MCP connection in an AI application that supports Streamable HTTP and OAuth:

```text
https://app.fedfinder.net/mcp
```

Choose OAuth, sign in on `app.fedfinder.net` and review the requested permissions. No local server installation or client secret is needed for this connection. Your AI application's subscription or administrator settings may affect access.

This repository contains connection documentation and marketplace metadata for the hosted service. It does not contain FedFinder's application source or a self-hosted server distribution.

## What you can do

- Search stored federal opportunities and inspect an individual notice.
- Research awards, vendors and DLA parts solicitations with supported filters.
- Consult your saved company context and account matches when your plan and permissions allow.
- Save an explicitly approved opportunity to your research shortlist. Eligible Pro and Intel connections can also create a pursuit or update its next action.

Tools and limits depend on your subscription and granted scopes. The authenticated `tools/list` response determines what is available to your connection. See the [tool reference](https://www.fedfinder.net/connector-docs/tools) and [plans and limits](https://www.fedfinder.net/connector-docs/plans-and-limits).

## Try a read-only search

Ask your connected assistant:

> Use FedFinder to find up to five open federal opportunities for NAICS 541810. Show each identifier, agency, response deadline and official source link when available. Keep missing evidence unresolved. Do not save or change anything.

Replace the example NAICS code with your business's actual code. Then request one result using its returned identifier and review the original notice and amendments.

Searches use stored records, not a guarantee of complete or current government coverage. Company context helps research; the connector does not provide a computed eligibility determination or a probability of winning.

## Keep saves and pursuits distinct

A research shortlist save is not a Pursuit Board record. Ask your assistant to confirm the exact record and change before any write. FedFinder does not submit bids, quotes or proposals to government systems.

## Access and help

A compatible FedFinder subscription is required. Current plan access, prices and billing terms are on the [pricing page](https://www.fedfinder.net/pricing).

Read the [security and permissions guide](https://www.fedfinder.net/connector-docs/security) for consent and disconnection. Never put account passwords, API keys or bearer tokens in a repository, issue or chat message.

[FedFinder documentation](https://www.fedfinder.net/connector-docs) · [Privacy](https://www.fedfinder.net/privacy) · [Terms](https://www.fedfinder.net/terms)
