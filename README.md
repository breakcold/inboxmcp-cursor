# LinkedIn Inbox by InboxMCP

![InboxMCP LinkedIn blue logo](assets/logo-linkedin.svg)

Use the hosted LinkedIn, WhatsApp, Telegram and Instagram tools and included skills to manage your inboxes, read messages, research profiles, and prepare outreach. InboxMCP shows proposed replies in chat for approval before sending them.

## Connect your account

After this plugin is available in the marketplace, install InboxMCP and complete its OAuth sign-in in your browser. Connect your own LinkedIn, WhatsApp, Telegram or Instagram accounts through InboxMCP, then ask the agent to check your account connection.

The plugin connects to `https://inbox-mcp.com/mcp` over Streamable HTTP. It runs no local executable and contains no credentials. Use the browser sign-in flow. Do not paste passwords, cookies, or access tokens into chat.

An InboxMCP account and at least one connected LinkedIn, WhatsApp, Telegram or Instagram account are required. Users start with a trial and then need an active subscription for connected-account actions. Payment and subscription management happen on the InboxMCP website through Stripe.

## Try the included workflows

- "Find LinkedIn inbox messages waiting for a reply and draft a response. Do not send it."
- "Research a LinkedIn profile and draft a relevant introduction. Do not send it."
- "Help me prepare LinkedIn outreach messages and connection requests for my approval."

The `inbox` skill lists conversations from every connected account, reads them, and drafts replies on any network. The `whatsapp-telegram-instagram` skill adds reactions, contact profiles, group members, and approved Instagram photo posts. The `linkedin-inbox` skill reads LinkedIn conversations and drafts replies. The `linkedin-research` skill searches people and summarizes profiles. The `linkedin-outreach` skill sends approved messages and invitations, schedules paced batches, checks delivery results, and publishes approved text posts.

## Understand the limits

Sending messages, inviting contacts, scheduling outreach, and publishing posts require approval of the exact content and recipients or audience. Reading does not authorize sending or marking a conversation read.

LinkedIn permissions, connection degree, quotas, and cooldowns apply. InboxMCP paces actions and reports remaining limits. The connector cannot cancel, pause, or resume scheduled outreach. It cannot edit or delete a published post. Scheduling a job does not prove delivery.

InboxMCP supports LinkedIn. It does not read Gmail or other email inboxes.

## Data and support

Tool requests go to InboxMCP. The server accesses LinkedIn through Unipile. Consult the [privacy policy](https://inbox-mcp.com/privacy) for current data handling and retention, and the [terms of service](https://inbox-mcp.com/terms) for service conditions.

Documentation is at [inbox-mcp.com/docs](https://inbox-mcp.com/docs). Contact support at support@inbox-mcp.com.

## Review status

This package is prepared for marketplace review. Package checks and public OAuth discovery do not establish successful installation in Cursor or Grok Bot. Authenticated host discovery and a draft-only workflow still need verification before claiming host compatibility has been tested.

## License

MIT. See [LICENSE](LICENSE).
