# Privacy Policy — "Claude MCP Lesage"

_Last updated: September 15, 2026_

## 1. Who we are

"Claude MCP Lesage" (the "App") is a private, single-user integration between QuickBooks Online and a locally installed Model Context Protocol (MCP) server. It is operated by Anthony Lesage (the "Operator") exclusively for QuickBooks Online companies he owns or manages. There are no other users.

## 2. What data the App accesses

Through Intuit's official QuickBooks Online Accounting API, the App reads and writes accounting data of the connected companies: chart of accounts, journal entries, invoices, customers, vendors, payments, sales-tax codes and financial reports. Access is limited to the `com.intuit.quickbooks.accounting` scope.

## 3. Where the data goes

- The MCP server runs on the Operator's own computer. Data retrieved from QuickBooks Online is returned to the AI assistant client (Claude, by Anthropic) running on that same computer, at the Operator's request, and is processed under Anthropic's terms of service.
- OAuth tokens (access and refresh tokens) are stored in a local file on the Operator's computer, readable only by the Operator's user account.
- No QuickBooks data is stored in any database, sold, shared with third parties, or used for advertising or analytics.

## 4. Retention

QuickBooks data is not retained by the App beyond the duration of each request. OAuth tokens are kept until the connection is revoked, then deleted.

## 5. Security

Tokens are kept out of version control and out of the AI client configuration. Communication with Intuit uses HTTPS only. Deletion of QuickBooks records is disabled at the server level.

## 6. Revoking access

The Operator can revoke access at any time by disconnecting the App from the QuickBooks Online company (Intuit account → Apps) or by deleting the App in the Intuit Developer Portal.

## 7. Contact

alesage@tervene.com
