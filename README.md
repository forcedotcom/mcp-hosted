# Salesforce Hosted MCP Servers

Salesforce's hosted MCP servers allow AI assistants like Claude, ChatGPT, and more connect securely to your Salesforce logic and assets using the [Model Context Protocol](https://modelcontextprotocol.io). Hosted MCP servers are now generally available (GA).

MCP is an open standard — think of it as USB-C for AI integrations. Any MCP-compatible client can connect to Salesforce through a single, standardized interface with enterprise-grade authentication and governance built in.

## Documentation

Documentation for MCP servers is available in multiple locations, each serving a different audience and purpose. We're using a car analogy to explain each of the distinct documentation options. 

<table>
<tr>
<td width="260"><img src="documentation/images/getting-started.png" alt="Getting started — learn to drive" width="240"></td>
<td>
<h3>Basic Administration — Salesforce Help &amp; Training</h3>
<p><strong><a href="https://help.salesforce.com/s/articleView?id=sf.mcp_servers.htm">Configure MCP Servers in Setup</a></strong></p>
<p>Enable and disable servers, create custom servers, attach APIs and Flows, manage External Client Apps. Help &amp; Training covers questions about anything you'd do in Salesforce Setup.</p>
<p><em>Help &amp; Training teaches you the basics of how to drive this new car.</em></p>
</td>
</tr>
<tr>
<td width="260"><img src="documentation/images/administration.png" alt="Administration — the reference manual" width="240"></td>
<td>
<h3>Server Reference and Building Custom Servers — Salesforce Developers</h3>
<p><strong><a href="https://developer.salesforce.com/docs/platform/hosted-mcp-servers">Developer Guide for Hosted MCP Servers</a></strong></p>
<p>Browse available servers and tools, build custom MCP servers, and understand authentication for Claude, ChatGPT, et. al. If your question is about which APIs are available or how to authenticate, start here.</p>
<p><em>Developer docs represent the owner's manual with detailed specs.</em></p>
</td>
</tr>
<tr>
<td width="260"><img src="documentation/images/advanced-development.png" alt="Advanced development — the mechanic's workshop" width="240"></td>
<td>
<h3>Best Practice Patterns &amp; Community — This Wiki</h3>
<p><strong><a href="../../wiki">Wiki Home</a></strong></p>
<p>This repo will become a hub for more advanced development and architecture topics, updated on an ad-hoc basis as the MCP space evolves. Best practices, architecture patterns, client-specific concerns, and more can change on a weekly basis. This wiki provides a channel for all of us to keep each other up-to-date.</p>
<p><em>The wiki and issues list are a mechanic's forum where people share what works in the real world.</em></p>
</td>
</tr>
</table>

---

## Quick Links

- [FAQ](../../wiki/FAQ)
- [Available Servers and Tools](https://developer.salesforce.com/docs/platform/hosted-mcp-servers/references/reference/servers-reference.html)
- [Configure Your MCP Client](../../wiki/Configure-Your-MCP-Client)

## Have a Question or Idea?

We use GitHub Issues to track feedback on the MCP server experience:

- **[Request a feature](../../issues/new?template=feature-request.yml)** — Suggest new tools, servers, or capabilities
- **[Suggest a doc improvement](../../issues/new?template=doc-improvement.yml)** — Flag gaps, unclear instructions, or missing examples
- **[Ask a question](../../issues/new?template=question.yml)** — Anything else about MCP servers

For connection problems or potential bugs, please [contact Salesforce Support](https://help.salesforce.com).
