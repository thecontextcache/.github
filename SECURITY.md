# Security Policy

This policy applies to every repository in the `thecontextcache` organization and to the hosted service at `thecontextcache.com`.

## Reporting a vulnerability

Email **support@thecontextcache.com** with the subject line `SECURITY`. Include:

- what you found and where (URL, endpoint, package, or repository path),
- steps to reproduce or a proof of concept,
- the impact as you understand it.

You will get an acknowledgement within 3 business days. We ask that you give us a reasonable time to fix the issue before any public disclosure, and that you do not access, modify, or retain data that is not yours while testing.

Please do not report security issues through public GitHub issues, discussions, or pull requests.

## Scope

In scope: the hosted API and web app, the MCP server package (`@contextcache/mcp`), the browser extension, and the CLI.

Out of scope: denial of service, volumetric attacks, social engineering, reports from automated scanners without a demonstrated impact, and issues in third-party services we do not operate.

## What we do on our side

- Dependency alerts and automated security updates are enabled on every repository.
- CI runs static analysis and dependency audits on every push and pull request.
- Production runs behind Cloudflare with no public inbound ports; all administrative access is over a private network.
- Captured content is never used to train models. See [Data handling](https://thecontextcache.com/data-handling).

## Supported versions

Only the current hosted release and the latest published package versions receive security fixes.
