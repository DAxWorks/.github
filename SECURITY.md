# Security policy

DAxWorks designs and operates cloud infrastructure for its clients. This policy
covers how to report a security issue in anything DAxWorks publishes or
operates.

---

## Reporting a vulnerability

**Email [security@daxworks.io](mailto:security@daxworks.io).** Include:

- What the issue is, and where: a repository and file, or a hostname
- What an attacker could do with it
- How to reproduce it, if it is reproducible
- Whether it is already public

**Please do not open a public issue for a security report**, and please do not
test against a live client environment. A report describing the flaw is enough;
proving it on production is not.

If the issue affects a system DAxWorks operates on behalf of a client, say so.
Client notification is a contractual obligation and starts earlier than any
public disclosure.

---

## What to expect

| | |
|---|---|
| Acknowledgement | Within 3 business days |
| Initial assessment | Within 10 business days |
| Progress updates | Until the issue is closed or declined |

DAxWorks is a small consultancy, not a product vendor. These are commitments to
respond, not a support-level agreement, and the timeline for a fix depends on
whose system the issue is in.

**Where the issue is in a client's environment, the client decides remediation
and disclosure.** DAxWorks will report it to them promptly and advise, but it is
not DAxWorks' decision to make public.

---

## Scope

**In scope:** repositories published by DAxWorks, and infrastructure DAxWorks
operates under a current engagement.

**Out of scope:** client applications, content and third-party services that
DAxWorks does not operate. Where the boundary between platform and application
sits is defined per engagement in its statement of work.

---

## Safe harbour

DAxWorks will not pursue a report made in good faith that:

- Avoids privacy violations, data destruction, and service degradation
- Uses only accounts you own or have explicit permission to test
- Gives reasonable time to respond before any public disclosure

There is no bounty programme.

---

## How DAxWorks builds

The baseline applied to every engagement, and the levels above it, are documented
in the engineering standards: no long-lived cloud credentials, no secrets in
code, private networking with session-based administrative access, encryption at
rest and in transit, least privilege scoped by resource, and deletion protection
on anything holding state.
