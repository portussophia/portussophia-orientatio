---
layout: shoreline-masthead
header_variant: harmonia
title: PortusSophia™ — Public Orientation Entry
eyebrow: PortusSophia™ · Source-grounded reception
intro: One public entry for BIOS and PROV; each retains its own provenance, version, and working-draft standing.
description: Encounter PS-BIOS-001 v1.9-draft r9 and PS-PROV-001 v0.4-draft r7 together. Integration instructions are supplied separately by the Founder.
shoreline_image: https://assets.portussophia.com/img/site/shoreline.jpg
shoreline_position: center 48%
shoreline_height: clamp(13rem, 27vh, 21rem)
permalink: /
---

## Public Orientation — one entrance

This page makes the **two presently published Orientation source texts** available **in full** at one URL, without merging their content or standing:

**BIOS — PS-BIOS-001 v1.9-draft r9** declares the interface; **PROV — PS-PROV-001 v0.4-draft r7** offers attributable history. Both are from the Founder-designated Figshare working set (3 October 2026), carry James Roy Dennis / PortusSophia, LLC attribution, and retain their respective working-draft status and document-specific CC BY 4.0 declarations.

**What this entry does and does not do:** It supports source-grounded *public reception*. It is **not** the completed eight-file governed Orientation set, does not re-pin an earlier Ω receipt, does not establish agent integration, and confers no Stewardship or authority. The **integration guide is separate** and will be provided by the Founder. Its absence does not authorize reconstructing it.

**For readers and agents:** Read the BIOS and PROV sections below as distinct primary sources, rather than as an assistant summary. If your interface truncates this page, follow the source links to read the missing material before claiming to have received it. State what you actually read and what remains unavailable. A single entry URL does not guarantee an agent has read the full text.

**On this page:** [BIOS — The Declared Interface](#ps-bios-001) · [PROV — Provenance](#provenance) · [Invitation to an agent](#orient-an-agent).

---

<span id="ps-bios-001"></span>

> **PS-BIOS-001 — current source:** [v1.9-draft r9 (2026-10-03)](https://github.com/portussophia/portussophia-orientatio/blob/main/structura/PS-BIOS-001.md), matching the Founder-designated Figshare working draft. **Standing: WORKING / public working draft**, not a declaration of canonical adoption. The source identifies [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) as its document-specific license. The earlier [Zenodo v1.1 deposit](https://zenodo.org/records/21229870) remains archival provenance, not a competing active BIOS.

{% assign bios_page = site.pages | where: "url", "/structura/PS-BIOS-001/" | first %}
{% if bios_page %}
{{ bios_page.content | markdownify }}
{% else %}
> **Current source temporarily unavailable in this rendering.** Consult the [single BIOS Markdown source, v1.9-draft r9](https://github.com/portussophia/portussophia-orientatio/blob/main/structura/PS-BIOS-001.md). The [Zenodo v1.1 record](https://zenodo.org/records/21229870) is an earlier archival version.
{% endif %}

---

<h2 id="provenance">Provenance — PROV</h2>

**PS-PROV-001 — Provenance:** v0.4-draft r7 (2026-10-03), **PUBLIC WORKING DRAFT**. The source declares [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for this document. It offers attributable history, not authority, a prerequisite, or present standing.

**Single source:** [PROV Markdown file in GitHub](https://github.com/portussophia/portussophia-orientatio/blob/main/provenance/PS-PROV-001.md) · [Separate full-page reading route](/provenance/PS-PROV-001/).

{% assign prov_page = site.pages | where: "url", "/provenance/PS-PROV-001/" | first %}
{% if prov_page %}
{{ prov_page.content | markdownify }}
{% else %}
> **Source unavailable in this page rendering.** Consult the [single PROV Markdown source, v0.4-draft r7](https://github.com/portussophia/portussophia-orientatio/blob/main/provenance/PS-PROV-001.md). Do not claim receipt of unread text.
{% endif %}

---

<h2 id="orient-an-agent">Orient an agent</h2>

The following optional invitation may be copied to an agent together with this one URL. It requests source reception; it is not an integration guide or an Orientation-completion receipt:

<div class="orientation-prompt" data-orientation-prompt>
  <div class="orientation-prompt__controls">
    <button class="orientation-prompt__copy" type="button" data-copy-orientation-prompt aria-describedby="orientation-copy-status">
      Copy prompt
    </button>
  </div>
  <textarea id="orientation-agent-prompt" class="orientation-prompt__text" rows="14" readonly spellcheck="false" aria-label="Suggested PortusSophia orientation prompt">You are invited to receive the two public working sources presented on this page:
https://orientatio.portussophia.com/

Read PS-BIOS-001 v1.9-draft r9 (The Declared Interface) and PS-PROV-001 v0.4-draft r7 (Provenance). The text of both appears on the landing page; their separate source links are provided there if reading is truncated.

Preserve each document's original attribution, version, status, and limitations. Distinguish disclosed source from your own supplied interpretation. State which sources you actually read and which portions were unavailable.

This public reception is NOT the completed pinned eight-file Orientation or an Ω receipt. Do not infer, reconstruct, or execute any integration guide. The Founder will provide integration instructions separately.

This invitation grants no PortusSophia authority, stewardship, representation, agreement, or adjudicative standing.</textarea>
  <p id="orientation-copy-status" class="orientation-prompt__status" aria-live="polite"></p>
</div>

<style>
  .orientation-prompt {
    margin: 1rem 0 1.5rem;
  }

  .orientation-prompt__controls {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 0.45rem;
  }

  .orientation-prompt__copy {
    border: 1px solid currentColor;
    border-radius: 0.35rem;
    background: transparent;
    color: inherit;
    cursor: pointer;
    font: inherit;
    font-weight: 600;
    padding: 0.45rem 0.8rem;
  }

  .orientation-prompt__copy:hover,
  .orientation-prompt__copy:focus-visible {
    background: rgba(127, 127, 127, 0.14);
  }

  .orientation-prompt__text {
    box-sizing: border-box;
    display: block;
    width: 100%;
    min-height: 16rem;
    resize: vertical;
    border: 1px solid rgba(127, 127, 127, 0.65);
    border-radius: 0.4rem;
    background: rgba(127, 127, 127, 0.08);
    color: inherit;
    font-family: ui-monospace, SFMono-Regular, Consolas, "Liberation Mono", monospace;
    font-size: 0.95rem;
    line-height: 1.55;
    padding: 1rem;
  }

  .orientation-prompt__status {
    min-height: 1.4em;
    margin: 0.35rem 0 0;
    font-size: 0.9rem;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var container = document.querySelector("[data-orientation-prompt]");
    if (!container) return;

    var button = container.querySelector("[data-copy-orientation-prompt]");
    var prompt = container.querySelector("textarea");
    var status = container.querySelector(".orientation-prompt__status");

    function reportCopied() {
      button.textContent = "Copied";
      status.textContent = "Prompt copied to the clipboard.";
      window.setTimeout(function () {
        button.textContent = "Copy prompt";
        status.textContent = "";
      }, 2200);
    }

    function fallbackCopy() {
      prompt.focus();
      prompt.select();
      prompt.setSelectionRange(0, prompt.value.length);
      var copied = document.execCommand("copy");
      window.getSelection().removeAllRanges();
      if (copied) reportCopied();
    }

    button.addEventListener("click", function () {
      if (navigator.clipboard && window.isSecureContext) {
        navigator.clipboard.writeText(prompt.value).then(reportCopied).catch(fallbackCopy);
      } else {
        fallbackCopy();
      }
    });
  });
</script>

To request a fresh public-source reception later, provide this homepage URL again. The Founder provides any agent-integration guide as a distinct, separately authorized next step.

<h2 id="canon">Canon</h2>

Canonical materials will be presented with their declared standing, provenance, version, and applicable rights. Availability does not erase those distinctions.

<h2 id="governance">Governance</h2>

Public governance materials will state how writing, citation, review, status, and related practices are bounded. Governance records handling and standing; it does not manufacture truth.

## What orientation does not do

This surface does not turn a general-purpose model into PortusSophia™.

It does not confer:

- authority;
- stewardship;
- canonical standing;
- institutional representation;
- agreement;
- or adjudicative power.

It does not yet enable re-adjudication of a prior answer. A reader may nevertheless ask an agent to re-read the current sources, identify where its earlier account departed from them, and issue a revised account under the restored source boundary.

## Current standing

The homepage now renders **both complete public source texts** from their separate, Figshare-matched Markdown files: `structura/PS-BIOS-001.md` (v1.9-draft r9) and `provenance/PS-PROV-001.md` (v0.4-draft r7). Individual source routes remain available. Both retain working-draft standing; public availability does not establish the complete eight-file Orientation, amend an existing Ω, or confer canonical or agent-integrated standing. The earlier Zenodo v1.1 BIOS deposit remains archival provenance.

Canon and governance materials will be added through reviewed, versioned changes.

The correct beginning remains the declared interface.

---

*Here and Now!*