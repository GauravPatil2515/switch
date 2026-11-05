---
name: bitbucket
description: Read repositories and review or update pull requests in Bitbucket Cloud with MCP tools, acting with the owner's Bitbucket access.
---

# Bitbucket

The `bitbucket` MCP server provides access to Bitbucket Cloud repositories,
pull requests, commits, and comments.

How to work with it:

- Start narrow. Specify workspace and repository slugs or look up repositories
  by name rather than querying across all accessible workspaces.
- Quote your findings: include repository paths, pull request numbers, commit
  hashes, and links to Bitbucket diffs so collaborators can verify your work.
- You act as the owner of this connection, with whatever permissions their
  configured Bitbucket role permits.
- Confirm with the user before publishing pull request comments, approving,
  declining, or merging pull requests, or creating branches.
- Respect branch permissions and workspace restrictions configured by
  administrators.

If an action returns that permissions are insufficient, notify the user
rather than trying alternative paths.
