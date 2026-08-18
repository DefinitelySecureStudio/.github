# Constitution conformance record

## Constitutional alignment

- Constitution: [Definitely Secure Studio Constitution v1.0.0](https://github.com/DefinitelySecureStudio/studio/tree/constitution/v1.0.0)
- Constitution tag: `constitution/v1.0.0`
- Constitution commit: [`a9cc8a503aa30e17820edc62ac95f7cbe10e0564`](https://github.com/DefinitelySecureStudio/studio/commit/a9cc8a503aa30e17820edc62ac95f7cbe10e0564)
- Status: `Conforming` (effective only after accountable-owner approval and merge of the adopting pull request)
- Assessed scope: organization governance, community-health defaults, repository templates, inherited policies, and default-promotion controls in this repository
- Excluded scope: downstream repositories' local overrides and GitHub controls they own; runtime systems and creative records, which this repository does not contain
- Accountable owner: [`@andrewperis`](https://github.com/andrewperis), organization owner
- Assessment revision and date: `6168fdc5ca518fee4e87f38ed5a69bc8bfa5d2b5`; 2026-08-17
- Checklist revision: `a9cc8a503aa30e17820edc62ac95f7cbe10e0564`
- Applicable profiles: universal; repository and production-system; ADR, RFC, and stable-specification
- Evidence: this record; repository files at the assessed revision; GitHub settings verified 2026-08-17; adoption issue [#2](https://github.com/DefinitelySecureStudio/.github/issues/2); adopting pull request
- Active constitutional exceptions: None
- Residual risk: inherited defaults can be replaced by repository-local files; each downstream repository remains responsible for assessing its effective policy
- Next review: 2026-11-17, or earlier on a Constitution change, organization-default promotion, governance/visibility/ownership change, material template change, incident, stale evidence, or exception

Before the adopting pull request is approved and merged, this is a proposed
record and the repository remains `Transition required`. Merge is the owner's
A4 governance approval of the exact diff and records the adopting commit in the
pull request and issue timelines. No sensitive evidence was needed; sensitive
reports remain in GitHub private security advisories or an approved restricted
Studio channel.

## Findings and settings evidence

| ID | Severity | Disposition | Evidence |
| --- | --- | --- | --- |
| GH-1 | Major | Resolved 2026-08-17 | Secret scanning, push protection, vulnerability alerts, and Dependabot security updates were enabled. |
| GH-2 | Minor | Resolved 2026-08-17 | The undocumented Projects setting was already disabled; Wiki and Discussions are disabled. |
| GH-3 | Advisory | Accepted residual risk | Local repository files can override inherited defaults; `README.md` explains inheritance and downstream assessments cover effective policy. |

## Checklist evidence

`P` means Pass and `N/A` means Not applicable with the stated rationale. The
item IDs follow the order of the pinned compliance checklist.

### Assessment identity

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| I1 | P | Identity, revision, purpose, public environment, audience, scope, and exclusions are stated above. |
| I2 | P | Version, immutable tag, full commit, and checklist revision are pinned above. |
| I3 | P | `@andrewperis` is owner and required CODEOWNER; the automation-authored proposal requires their human review and merge. |
| I4 | P | Profiles, evidence, date, freshness boundary, status, findings, and triggers are recorded here. |
| I5 | P | This record is reader-safe; restricted security evidence remains in private advisories. |

### Universal profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| U1 | P | `README.md` and `GOVERNANCE.md` identify Studio standards, organization owners, maintainers, and repository authorities. |
| U2 | P | Defaults defer to Studio architecture and repository-local authorities without redefining them. |
| U3 | P | The PR template now requires delegation, governing authority, and human approval evidence for material changes. |
| U4 | P | `GOVERNANCE.md`, CODEOWNERS, branch protection, and the updated PR template preserve human A4 decisions. |
| U5 | P | Contribution, security, and review rules require escalation for sensitive or out-of-scope work. |
| U6 | P | Governance distinguishes public Canon, private Lore, proposals, approvals, and merge effects. |
| U7 | P | `GOVERNANCE.md` assigns Canon to Universe and Lore to the private Lore authority. |
| U8 | N/A | This repository contains no Canon promotion, correction, deprecation, or retcon record. |
| U9 | P | Defaults prohibit private Lore in public content and direct sensitive handling to restricted channels. |
| U10 | N/A | This repository generates no creative work against Canon or Lore context. |
| U11 | P | The PR template requires exact validation, dependency links, provenance, and accountable approval for material defaults. |
| U12 | P | Templates distinguish evidence, impact, validation, and sensitive material rather than treating omission as success. |
| U13 | N/A | No nondeterministic generation workflow is present. |
| U14 | N/A | No generated or released artifact bytes are produced here. |
| U15 | P | Git history, protected `main`, required reviews, and GitHub audit timelines preserve consequential changes. |
| U16 | P | `SECURITY.md`, contribution rules, and PR checks cover trust, disclosure, data, rights, and incident boundaries. |
| U17 | P | Least-privilege ownership and private-reporting rules minimize access and recipients. |
| U18 | P | Defaults explicitly prohibit secrets in source, issues, logs, fixtures, and releases. |
| U19 | P | Confidentiality rules follow copies, reports, private Lore, and unreleased material. |
| U20 | N/A | No provider processes protected Studio data in this repository. |
| U21 | P | Contribution and PR rules require third-party provenance, permission, licenses, and notices. |
| U22 | P | Questionable security, privacy, rights, or disclosure issues stop public handling and use the private route. |
| U23 | P | The PR template defines independent validation and domain-impact checks. |
| U24 | P | Automated checks are bounded; accountable maintainers approve changes. |
| U25 | P | Git is the durable authoritative home; history and portable Markdown provide independent recovery. |
| U26 | N/A | No provider-specific production feature or dependency exists. |
| U27 | N/A | No data migration is present. |

### ADR, RFC, and stable-specification profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| A1 | P | `GOVERNANCE.md` assigns organization-wide decisions to Studio and keeps repository responsibilities separate. |
| A2 | P | The PR template requires governing decision, exact Constitution reference, impact, validation, owner, and approval. |
| A3 | P | Defaults are implementation-neutral contribution and governance controls. |
| A4 | P | Compatibility, downstream PRs, validation, and rollout are required when applicable. |
| A5 | P | Security, privacy, rights, accessibility, provenance, and failure impact are explicit checklist concerns. |
| A6 | P | The template directs constitutional meaning to the governing Studio process; a default cannot amend it. |

### Repository and production-system profile

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| R1 | P | `README.md`, `LICENSE`, `NOTICE`, and Studio architecture define public visibility, responsibility, owner, content boundary, and license. |
| R2 | P | `main` protection requires one review, stale dismissal, CODEOWNER review, conversation resolution, and blocks force-push/deletion; security reporting and merge controls are configured. |
| R3 | P | Cross-repository dependencies are links to immutable governing records or companion work; this repository publishes no runtime artifact. |
| R4 | P | Public templates prohibit secrets, private Lore, unpublished Canon, protected context, and unlicensed material. |
| R5 | P | This file is the required reader-safe declaration. |

### Assessment outcome

| ID | Result | Evidence or rationale |
| --- | --- | --- |
| O1 | P | GH-1 through GH-3 are classified; no unresolved Blocker exists. |
| O2 | P | The effective final status is exactly `Conforming`; pre-merge status remains `Transition required`. |
| O3 | P | Approval is limited to the exact assessed revision and adoption diff. |
| O4 | P | Date and material re-review triggers are stated above. |

## Approval

Owner approval is the recorded review and merge of the adopting pull request by
`@andrewperis`. That event, not preparation of this file, moves the repository
from `Transition required` to the declared revision-scoped `Conforming` status.
