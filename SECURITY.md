# Security Policy · 資安政策

## Reporting a vulnerability · 回報漏洞

**Please do not open a public issue.** Use GitHub's private reporting instead:
open the repository's **Security** tab → **Report a vulnerability**.
If that button is missing, open one on [htlin222/.github](https://github.com/htlin222/.github/security/advisories/new) and name the affected repository.

請勿公開開 issue，請到該 repo 的 **Security → Report a vulnerability** 私下回報。

Please include: affected repository and version or commit, how to reproduce, and the impact you expect.
You will get a first reply within about a week. Fixes are released as soon as practical and credited to you unless you prefer otherwise.

## Especially relevant here · 特別注意

Several projects touch clinical workflows, hospital systems or third-party medical services. Please report privately if you find:

- a way for **patient or personal data** to leak (logs, caches, exports, published pages);
- **secrets** committed to a repository or exposed by a deployed site;
- a path that lets someone act on a user's account (tokens, cookies, OAuth relays, self-hosted Workers);
- clinical output that is **silently wrong** in a way that could harm a patient.

## Supported versions · 支援版本

Only the latest release (or `main` when there are no releases) receives fixes.
