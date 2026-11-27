# C2O–UNIVERSALIS UNIVERSALIS Application (UNIVERSALIS-App)

**Repository:** `C2O-UNIVERSALIS/UNIVERSALIS-App`  
**Repository role:** Public/open-source UNIVERSALIS Application edition  
**Operating Intelligence:** UNIVERSALIS  
**Master source:** [C2O–UNIVERSALIS Master Application (MApp)](https://github.com/C2O-UNIVERSALIS/C2O-UNIVERSALIS-MApp)  
**Research Plan:** [Research Plan.md](Research%20Plan.md)

## Purpose

UNIVERSALIS-App is the public/open-source UNIVERSALIS edition of the C2O–UNIVERSALIS Application system. Its application-domain source lineage is MApp, subject to item-level rights, licensing, provenance, security, privacy, and release review. UNIVERSALIS is its assigned Operating Intelligence.

UNIVERSALIS-App is the Application counterpart to UNIVERSALIS-OS. Both are UNIVERSALIS editions, with UNIVERSALIS-OS derived from MOS and UNIVERSALIS-App derived from MApp. Their actual interfaces, dependencies, shared responsibilities, and independent operating requirements must be established through research and versioned contracts rather than presumed.

## Six-repository architecture

1. **C2O-UNIVERSALIS-MOS** — private Master source repository for the Operating System domain.
2. **C2O-UNIVERSALIS-MApp** — private Master source repository for the Application domain.
3. **C2O-OS** — private-source C2O Operating System edition, derived from MOS.
4. **C2O-App** — private-source C2O Application edition, derived from MApp.
5. **UNIVERSALIS-OS** — public/open-source UNIVERSALIS Operating System edition, derived from MOS.
6. **UNIVERSALIS-App** — public/open-source UNIVERSALIS Application edition, derived from MApp.

MOS and MApp are coordinated Master source domains, not additional product editions. C2O and UNIVERSALIS are distinct, coordinated Operating Intelligences. C2O is assigned to C2O-OS and C2O-App; UNIVERSALIS is assigned to UNIVERSALIS-OS and UNIVERSALIS-App.

## Repository boundaries

- UNIVERSALIS-App maintains its own public-edition identity, application-domain research, approved public materials, evidence, tests, and lifecycle records.
- MApp remains the Master source repository for the Application domain; UNIVERSALIS-App does not silently modify or assume authority over MApp.
- MOS remains the Master source repository for the Operating System domain.
- UNIVERSALIS-App and UNIVERSALIS-OS retain distinct repository identities and responsibilities; cross-repository interfaces and dependencies must be explicit, versioned, and reviewed.
- Private-source material, credentials, policies, implementation details, and uncleared third-party material must not be transferred into UNIVERSALIS-App without appropriate rights, review, and explicit authorization.
- UNIVERSALIS-App must remain independently operable without access to private Master repositories, private C2O source code, private credentials, or undisclosed private services.
- Repository presence, source lineage, folder parity, a commit, successful check, or proposed design does not by itself establish acceptance, implementation, verification, licensing, publication, or release authorization.

## Structural alignment

UNIVERSALIS-App is required to use the common folder hierarchy established across all six repositories. Its directory structure is aligned to MApp and C2O-App. Repository-specific content and Research Plans may differ while corresponding folder paths remain aligned.

The inherited Application Applicability Register path is retained as part of the common structure. Its records in this repository must be interpreted and maintained for the UNIVERSALIS-App edition, with MApp retained as the Master-source lineage. Structural placeholders, indexes, registers, and folder presence do not by themselves establish completed research, validated applicability, implementation, or verification.

## Public-release and licensing boundary

The presence of an artifact in MApp or C2O-App does not grant permission to copy, modify, redistribute, publish, sublicense, or release it in UNIVERSALIS-App. Each proposed public artifact requires documented source identification, rights and license review, attribution and notice review, provenance, security and privacy review, and explicit release authorization.

No license grant is made by this README or by the existence of this repository. A public license must be added only after the relevant rights holder or authorized agent has approved the exact license and the applicable contents. Unknown, missing, disputed, or unverified rights remain unresolved and must not be treated as permission.

## Research status

The [UNIVERSALIS-App Research Plan](Research%20Plan.md) adapts the common research methodology to the public/open-source UNIVERSALIS Application edition. It does not predetermine findings or capabilities, grant implementation authority, or authorize publication of uncleared material.
