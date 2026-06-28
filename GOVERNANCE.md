# Governance
 
> **Project name is not finalized.** This document refers to the project as
> *the Project* and to its GitHub organization as *the Organization*. Both will
> be a neutral, community-owned home — not derived from any third-party
> trademark.
 
This document describes how the Project is governed: the roles people can hold,
how decisions are made, and how those rules can change. It exists so the Project
never again depends on a single person, and so the path from first contribution
to maintainer is open and predictable.
 
## Principles
 
- **Meritocracy.** Influence is earned through sustained, good-faith
  contribution — not by title or history.
- **Transparency.** Significant decisions happen in the open, in issues, pull
  requests, or discussions, with a written record.
- **Shared ownership.** The Organization is administered by several people. No
  single individual holds exclusive keys.
- **Low barrier to entry, clear path up.** Anyone can contribute; advancement
  criteria are explicit.
- **Respect for upstream.** We preserve the upstream license and authorship and
  stay technically compatible where reasonable.
## Roles
 
Roles form a ladder. Each level includes the rights of the levels below it.
 
### User
Anyone who uses the Project. No obligations. Encouraged to file issues, join
discussions, and help others.
 
### Contributor
Anyone with at least one merged pull request (code, docs, tests, design, or
infrastructure). Contributors are credited in the project history.
 
### Member
A Contributor with a track record of regular, quality participation.
 
- **Becoming a Member:** several merged contributions plus ongoing
  participation (reviews, triage, discussions). Nominated by any Maintainer and
  confirmed by lazy consensus of the Council.
- **Rights:** issue/PR triage (labeling, assigning), participation in
  non-binding discussion of all decisions, listed in `MEMBERS`.
### Maintainer
A Member trusted with merge rights and release responsibilities.
 
- **Becoming a Maintainer:** sustained, substantial contribution over at least
  ~3 months and demonstrated good judgment in reviews. Nominated by a
  Maintainer and approved by a Council vote (see *Decision-making*).
- **Rights & duties:** merge pull requests, cut releases, vote on Council
  matters, mentor new contributors, uphold the Code of Conduct.
### Maintainer Emeritus
A former Maintainer who has stepped back or become inactive (see *Inactivity*).
Recognized for past contributions; retains no merge or voting rights. May return
to active Maintainer status by request to the Council, subject to a confirming
vote.
 
## The Council
 
The Council is the group of active Maintainers. It is the Project's
decision-making body of last resort.
 
- **Initial composition:** former members of the original team who commit to
  active participation, together with one or more proven community contributors,
  so the path is open from day one.
- **Size:** kept small for velocity — ideally an **odd number (3 or 5)** to avoid
  deadlock — and grown as the Project grows.
- **Activity is a condition.** Council seats are for active Maintainers, not a
  permanent honorary title.
## Decision-making
 
Most decisions never need a formal vote. We escalate only when necessary.
 
### Lazy consensus (default)
The default for everyday work. A proposal (typically a pull request or an issue)
is considered accepted if no Maintainer raises a substantive objection within a
reasonable review window (**at least 72 hours** for non-trivial changes). Silence
is assent. Any Maintainer may request more time.
 
### Formal vote (reserved for significant matters)
A vote is required for:
 
- changes to this governance document or the Code of Conduct;
- adding or removing Maintainers, or moving a Maintainer to Emeritus;
- release policy and supported-version decisions;
- the project name, branding, and the Organization's ownership;
- contested architectural decisions where lazy consensus failed.
Rules for a formal vote:
 
- **Who votes:** active Maintainers (Council).
- **Where:** in a public issue or discussion, with votes recorded as
  `+1` / `0` / `-1` and a short rationale.
- **Quorum:** more than half of active Maintainers must cast a vote.
- **Thresholds:** a **simple majority** of votes cast for ordinary matters; a
  **two-thirds (2/3) supermajority** for governance changes, and for adding or
  removing Maintainers.
- **Window:** votes stay open at least **5 days** unless all Maintainers vote
  earlier.
- **Tie-breaking:** ties default to the status quo (the proposal does not pass).
  If the Council has designated a Technical Lead, that person may cast the
  deciding vote on technical (non-governance) ties.
### Conflicts of interest
Anyone with a material conflict of interest on a decision should disclose it and
abstain from the vote on that matter.
 
## Inactivity
 
To keep the Council from ossifying — the exact failure this Project exists to
fix — Maintainers who are unreachable or inactive for **6 months** (no reviews,
merges, or Council participation) move to **Maintainer Emeritus**. This is not a
punishment; it keeps the active roster honest. Returning is straightforward (see
*Maintainer Emeritus*).
 
## Removing a Maintainer
 
Beyond inactivity, a Maintainer may be removed for repeated Code of Conduct
violations or actions that seriously harm the Project. Removal requires a
two-thirds vote of the other active Maintainers. The affected person is notified
and given a chance to respond before the vote concludes.
 
## The Organization
 
- The Project lives in a neutral GitHub Organization with **multiple owners**
  (admins), never a personal account.
- Critical credentials (org ownership, package registries, domains, signing
  keys) are held by at least two Maintainers.
- If the Project grows, the Council may adopt a fiscal host or foundation to
  hold assets and donations transparently.
## Code of Conduct
 
All participants are expected to follow the Project's `CODE_OF_CONDUCT.md`.
Maintainers are responsible for enforcing it fairly and consistently.
 
## Amending this document
 
Changes to this document follow the *formal vote* process and require a
**two-thirds** supermajority of the Council. Proposed changes are made via pull
request so the history of governance is itself transparent.
 
---
 
*This is a living document. It will be refined as the Project and its community
grow.*
