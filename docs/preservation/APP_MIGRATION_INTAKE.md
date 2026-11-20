# UNIVERSALIS-App Migration Intake

**Status:** Proposed public intake process; no legacy artifact has been migrated by this document.

## Destination rule

UNIVERSALIS-App is the canonical home for public UNIVERSALIS user-facing product requirements, workflows, interactions, and presentation. UNIVERSALIS-OS owns platform architecture, OS services, public contracts, permissions, and system security. If one source mixes app and OS content, split it into linked artifacts and preserve the original public source locator.

## Intake sequence

1. Identify a public source artifact by repository, path, branch/commit, and blob or content hash.
2. Record author/owner, original status, date, license/rights, dependencies, and exact claims or requirements it supports.
3. Confirm that the material is intended for public release, rights-cleared, and free of private C2O content or inference risks.
4. Decide whether it defines app behavior. Route OS or cross-app contracts to UNIVERSALIS-OS and record the public cross-reference.
5. Select an operation: move verbatim, adapt, split, link, reimplement, or retain as source-only history. Explain the choice; retain meaning and provenance.
6. Stage the proposed destination in a review branch. Include destination path, source-to-destination mapping, and any transformations.
7. Verify content, links, identifiers, hashes where applicable, privacy/publication classification, and app-to-OS contract alignment.
8. Record review and owner acceptance separately from evidence status. Update the public source index only after destination verification.

## Elemental assessment and lifecycle

Use separate Air, Earth, Fire, Water, and Spirit ratings with a short rationale for each. The working 0–5 scale is descriptive and uncalibrated; it is not a measurement and scores must not be aggregated as research results. Keep lifecycle states distinct: Discovered, Classified, Proposed, Simulated, Migrated, Verified, Accepted. No state implies the next. Use public source identifiers and omit private source paths, internal IDs, or private operational details.

## Intake record

| Field | Entry |
|---|---|
| Public Source ID / Artifact ID | |
| Alchemical class | Primary / Supporting / Shared specification / Historical / Duplicate / Unresolved / Obsolete |
| Air / Earth / Fire / Water / Spirit ratings and rationale | |
|---|---|
| Migration ID | |
| Public source repository / path / ref / blob | |
| Source author / owner / date / status | |
| License / rights / public-release check | |
| Artifact type and app behavior covered | |
| Destination path and canonical owner | |
| Migration action and rationale | |
| Related public OS contract / dependencies | |
| Destination revision / hash | |
| Verification evidence / reviewer | |
| Acceptance status / open obligations | |

## Completion rule

A source item is migrated only when its destination is reviewed, its provenance and public cross-links work, and its relevant checks pass. Do not import private C2O content, private source paths, personal data, credentials, or private operational evidence. Keep source repositories and their histories intact while migration is underway. Repository closure is outside this App intake process and requires the full cross-repository reconciliation recorded in UNIVERSALIS-OS.

## Continuity

Use the [UNIVERSALIS-App Continuity Record](../continuity/CONTINUITY_RECORD.md) as the dated restart point for public-safe completed work, evidence, open obligations, and the next action. Refresh it after material milestones; verify live repository and PR state when resuming. Do not disclose private C2O details.
