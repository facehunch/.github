<p align="center"><img src="https://raw.githubusercontent.com/facehunch/.github/main/profile/logo.png" width="80" alt="Facehunch logo"></p>

# Facehunch

**Photo-search context with clear limits.**

Facehunch helps readers understand photo-search methods, source pages and the limits of a visual result. Its guides distinguish finding copies of a photograph from comparing faces across different photographs. The workspace presents a fictional sample and consented API tests; the current FaceCheck test index does not produce reliable identity matches.

[Website](https://facehunch.com) · [MCP repository](https://github.com/facehunch/mcp-server) · [Agent skill](https://github.com/facehunch/agent-skill) · [npm package](https://www.npmjs.com/package/facehunch-mcp)

## What you can do with Facehunch

### Choose the right question

Start with copies, a source page or a visual comparison. These are different tasks and call for different methods.

### Read beyond a thumbnail

Consider captions and publication context instead of treating an isolated image as a conclusion.

### Keep uncertainty visible

Separate an observation from an inference. A similar appearance does not verify who a person is.

### Understand the current preview

Paid searches are disabled. Facehunch does not offer private-profile access or formal background checks.

## Connect Facehunch to your AI workspace

The public integrations connect an existing Facehunch account to compatible MCP clients. Browser sign-in and a consent screen let you review the requested access. The MCP exposes the focused workflow below; it does not expose every feature of the product.

1. Locate a report that already exists in the user’s account.
2. Read its status and access state; preserve dates and source URLs exactly as returned.
3. Summarize what the stored report contains without inferring identity or treating a similarity score as verification.

The MCP does not initiate new face searches, identify people, infer sensitive traits or research personal information. It only retrieves existing owned reports. Locked results remain hidden. An empty report list means the account has no saved reports, not that a photograph has no online matches. Test results are not identity verification.

| Resource | Start here |
| --- | --- |
| Hosted MCP and desktop connector | [Setup, tool catalogue and examples](https://github.com/facehunch/mcp-server) |
| Agent skill | [Task guidance and installation](https://github.com/facehunch/agent-skill) |
| npm | [`facehunch-mcp`](https://www.npmjs.com/package/facehunch-mcp) |
| Desktop extension | [MCPB downloads](https://github.com/facehunch/mcp-server/releases) |

## Explore Facehunch

- [Photo search and its limits](https://facehunch.com/)
- [Reverse image search explained](https://facehunch.com/reverse-image-search)
- [Face search versus reverse image search](https://facehunch.com/blog/face-search-vs-reverse-image-search)
- [Photo-search privacy](https://facehunch.com/blog/photo-search-privacy)
- [Test-mode help centre](https://facehunch.com/help-center)
- [Photo removal](https://facehunch.com/data-removal)

## Feedback

For connector bugs or setup questions, [open an issue](https://github.com/facehunch/mcp-server/issues) with a redacted error and your client version. Keep account tokens, private content and credentials out of public issues. The connector and skill are MIT-licensed; using the hosted product requires an account and its applicable terms.
