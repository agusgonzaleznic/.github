# Security policy

This policy covers every public repository under [github.com/agusgonzaleznic](https://github.com/agusgonzaleznic)
that doesn't have a security policy of its own. A repository may describe what it protects, and
what is in scope, in its README or its docs.

## Reporting a vulnerability

Please don't open a public issue for a security problem. Report it privately instead:

1. Open the **Security** tab of the affected repository.
2. Choose **Report a vulnerability**.
3. Describe the problem, the steps to reproduce it, and what an attacker could do with it.

The report stays private between you and me until a fix is published, and it gives us a private
fork to work in.

If private vulnerability reporting isn't available to you, please use the contact details on my
GitHub profile, [github.com/agusgonzaleznic](https://github.com/agusgonzaleznic). There is no
dedicated security mailbox, so please don't send a report to an address you found anywhere else.

### What helps

- The affected version, release or commit.
- A minimal reproduction: the smallest set of steps, or the smallest input, that shows the problem.
- What an attacker gains. The impact decides the severity.

## Response expectations

These are personal projects that I maintain in my own time, so what follows is a best-effort
commitment and not a service level agreement:

| Stage | Best-effort target |
|---|---|
| Acknowledgement that the report arrived | Within 7 days |
| A first assessment and a view on severity | Within 30 days |
| A fix for a confirmed high-severity issue | As soon as practical, ahead of other work |

If you haven't heard anything after 30 days, a polite nudge on the same private thread is welcome.
There is no bug bounty and no payment. I'm glad to credit you in the release notes and the commit
message, if you want that.

Please allow a reasonable window for a fix before you publish anything. There is no fixed embargo
period: we agree the timing of the disclosure on the report thread.

## Supported versions

Security fixes go into the default branch, and into a new release for repositories that publish
releases. Older commits and releases aren't patched.

Thank you for reporting responsibly.
