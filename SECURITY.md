# Security

Star compute is licensed under [Apache-2.0](LICENSE) and published by SoulCraft-Org. Report a security problem privately, never in a public issue.

| Step | How |
| --- | --- |
| Report | GitHub private vulnerability reporting: the repo's Security tab, **Report a vulnerability** |
| Never | open a public issue for a security problem, or paste a key value anywhere |
| Then | the fix lands by pull request, and the advisory names the reporter unless they ask otherwise |

| In scope | A finding looks like |
| --- | --- |
| The docs | A key value, or personal data, in any file |
| `.github/workflows/` | A step that runs untrusted input, or an unpinned action |
