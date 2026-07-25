---
layout: shoreline-masthead
title: PS-BIOS-001 — The Declared Interface
eyebrow: PortusSophia™ Orientation
intro: The governing orientation of PortusSophia™, presented directly at the primary public entrance.
description: Read PS-BIOS-001 — The Declared Interface, then continue to canon and governance materials according to their declared standing.
shoreline_image: https://assets.portussophia.com/img/site/shoreline.jpg
shoreline_position: center 48%
shoreline_height: clamp(13rem, 27vh, 21rem)
permalink: /
---

<span id="ps-bios-001"></span>

{% assign bios_page = site.pages | where: "url", "/structura/PS-BIOS-001/" | first %}
{% if bios_page %}
{{ bios_page.content | markdownify }}
{% else %}
> **Source unavailable.** The machine-readable rendering of PS-BIOS-001 could not be loaded. Consult the [deposited Zenodo record](https://zenodo.org/records/21229870).
{% endif %}

---

<h2 id="orient-an-agent">Orient an agent</h2>

The following prompt may be offered to an agent as an invitation to establish the declared orientation before proceeding:

<div class="orientation-prompt" data-orientation-prompt>
  <div class="orientation-prompt__controls">
    <button class="orientation-prompt__copy" type="button" data-copy-orientation-prompt aria-describedby="orientation-copy-status">
      Copy prompt
    </button>
  </div>
  <textarea id="orientation-agent-prompt" class="orientation-prompt__text" rows="14" readonly spellcheck="false" aria-label="Suggested PortusSophia orientation prompt">You are invited to begin with PS-BIOS-001 — The Declared Interface:
https://orientatio.portussophia.com/

After reading PS-BIOS-001, you are invited to continue from the Canon section of the orientation surface:
https://orientatio.portussophia.com/#canon

As you proceed, preserve each document’s declared standing, distinguish source material from inference, and do not substitute for unavailable material.

This invitation does not confer PortusSophia authority, stewardship, representation, agreement, or adjudicative standing.</textarea>
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

To request reorientation later, provide the homepage URL again and invite the agent to reread the declared interface before continuing.

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

PS-BIOS-001 is now presented directly on the Orientatio homepage. The stable `/structura/PS-BIOS-001/` route remains available as an alternate public path to the same machine-readable rendering. The Zenodo PDF remains the deposited archival publication.

Canon and governance materials will be added through reviewed, versioned changes.

The correct beginning remains the declared interface.

---

*Here and Now!*