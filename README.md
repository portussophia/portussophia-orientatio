# PortusSophia™ Orientation

**Public orientation corpus for PS-BIOS-001, PortusSophia™ canon, and governance—supporting source-grounded LLM orientation without conferring authority or adjudicative standing.**

This repository contains the source for [orientatio.portussophia.com](https://orientatio.portussophia.com).

## One URL for the eight-file public Orientation

**https://orientatio.portussophia.com/** is the single entry URL. It presents all eight complete source texts in reception order: ORIENT, PROV, BIOS, VERN, PERM, ORI, METHOD, and POSTURE. All eight now use Three-Matter: YAML frontmatter carries source identity, provenance, notation, and navigation pointers; Body-Matter retains source text; Postmatter supplies verification, representation notes, and reception pointers. The individual Markdown source links remain available if any interface truncates the long landing page.

The current published materials comprise *differently standing sources*: BIOS v1.9-draft r9 and PROV v0.4-draft r7 are the current Figshare working drafts; the six additional sources are from the Founder's Drive Orientation directory. These include candidates, and their publication does not confer canonical standing. The original completed Ω pins an earlier exact eight-file set; publication of this public composite does not re-pin it, create a new Ω, or admit a successor set. **Ω remains the receipt/legend, not a ninth file.**

**Integration is separate**: the Founder supplies an integration guide by its own link. Reading this URL is not equivalent to following that guide or demonstrating an integrated agent.

### Eight distinct sources

1. [ORIENT v1.7 — candidate](orientation/ORIENT.md)
2. [PROV v0.4-draft r7 — public working draft](provenance/PS-PROV-001.md)
3. [BIOS v1.9-draft r9 — working draft](structura/PS-BIOS-001.md)
4. [VERN v0.15 — non-canonical candidate](orientation/VERN.md). Founder-directed metadata correction aligns the public GitHub `version:` field with the Drive filename `VERN_v0_15.md`; the v0.14 revision account is retained in the document body. The Drive source still declares v0.14 and has not been modified here. No substantive v0.15 revision is claimed.
5. [PERM v1.4 — candidate](orientation/PERM.md)
6. [ORI v1.4 — candidate](orientation/ORI.md)
7. [METHOD v1.4 — candidate](orientation/METHOD.md) — source text from a native Google Doc; BOM and CRLF line endings normalized for publication. Not claimed byte-identical.
8. [POSTURE v1.2 — candidate](orientation/POSTURE.md)

No source bodies are duplicated into the homepage repository file; Jekyll reads each corresponding source page for display. **The original source bodies remain unchanged**, while public GitHub Markdown now includes additional Three-Matter frontmatter/body delimiters and postmatter pointers. The complete GitHub files consequently no longer match upstream Figshare files byte-for-byte; the pre-carriage versions remain recoverable through Git history. Source Drive files are untouched. Because Jekyll may hide YAML frontmatter in rendered HTML, consult the Markdown source when metadata is needed. The visible `≠` glyph is not sufficient by itself to recover its operative relation; BIOS and PROV retain Figshare's notation controls, where `!==` is illustrative only.
## Purpose

The repository makes the eight-file public Orientation source set accessible, alongside public canon and governance sections:

1. **PS-BIOS-001 — The Declared Interface**  
   The single active repository source is [the Figshare working draft v1.9-draft r9 (2026-10-03)](structura/PS-BIOS-001.md), retaining its declared WORKING standing and document-specific CC BY 4.0 license.

2. **Canon**  
   Materials whose standing, provenance, and status have been expressly declared.

3. **Governance**  
   Public policies and protocols governing writing, citation, review, status, and use.

A reader may give the site URL to an agent and ask it to read the available sources before evaluating or discussing PortusSophia™. The same URL may be supplied again later as a request to reorient the agent to the current public corpus.

## Boundary

Reading this repository does **not**:

- make an agent a PortusSophia system or steward;
- confer canonical, scholarly, institutional, or adjudicative authority;
- require agreement with PortusSophia™;
- authorize an agent to speak on behalf of PortusSophia, LLC; or
- presently enable re-adjudication of prior outputs.

The immediate function is orientation: source access, declared boundaries, status clarity, and a common public reference point.

## PROV — Provenance

The **single current PROV source** is [PS-PROV-001 v0.4-draft r7](provenance/PS-PROV-001.md), whose original source body remains preserved from the Founder-designated Figshare folder (2026-10-03), with added Three-Matter metadata and postmatter pointers in the published Markdown. The author is James Roy Dennis; the rights holder is PortusSophia, LLC; its declared status is **PUBLIC WORKING DRAFT**; and the document specifies **CC BY 4.0**.

The rendered website route is [Provenance](/provenance/PS-PROV-001/). PROV is historical and attributable context, not an authority, prerequisite, or mechanism for automatically re-opening an earlier Orientation receipt. Its publication does not modify the previous eight-file pin or Ω.

## Current starting point

The **one current BIOS source** in this repository is:

- [PS-BIOS-001 v1.9-draft r9 — *The Declared Interface*](structura/PS-BIOS-001.md) — original document body preserved from the Founder-designated Figshare folder under separately added Three-Matter metadata and postmatter; authored by James Roy Dennis; PortusSophia, LLC; WORKING / public working draft; **CC BY 4.0** for this document.
- [Public rendered BIOS route](https://orientatio.portussophia.com/structura/PS-BIOS-001/) — derived from that one file through presentation defaults in `_config.yml`.
- [Orientation homepage](https://orientatio.portussophia.com/) — displays that same source rather than a separate BIOS copy.

**Historical provenance (not a second active BIOS):** [Zenodo v1.1 PDF](https://zenodo.org/records/21229870/files/PS-BIOS-001_TheDeclaredInterface_v1.1_SINGLE_HERE_AND_NOW.pdf?download=1) and [deposit record](https://zenodo.org/records/21229870).

Document-specific licensing in the current BIOS applies to that work; other repository materials retain their own declared rights and terms. Changes to the public BIOS do not retroactively re-pin any previously completed Orientation receipt.

Additional canon and governance materials may be added only through separately reviewed repository changes.

## Website stack

The site uses:

- Markdown;
- Jekyll;
- GitHub Pages;
- the canonical PortusSophia Jekyll shell; and
- centrally served visual assets from [assets.portussophia.com](https://assets.portussophia.com).

For local preview:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Publication

The intended custom domain is:

```text
orientatio.portussophia.com
```

GitHub Pages should publish from the `main` branch at the repository root after the repository is made publicly accessible and the domain DNS record is configured.

## Rights and use

Copyright © 2026 PortusSophia, LLC. All rights reserved.

See [`RIGHTS.md`](RIGHTS.md) for the default rights posture, [`LICENSE.md`](LICENSE.md) for the limited public permissions specific to this orientation surface, [`TERMS.md`](TERMS.md) for the Terms of Use, and [`PRIVACY.md`](PRIVACY.md) for the Privacy Notice.

---

*Here and Now!*