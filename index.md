---
layout: shoreline-masthead
title: PortusSophia™ Orientation
eyebrow: PS-BIOS-001 · The Declared Interface
intro: A public, versioned source boundary through which readers and agents may approach PortusSophia™ from its declared orientation.
description: Read the declared interface, canon, and governance materials before evaluating or discussing PortusSophia™.
shoreline_image: https://assets.portussophia.com/img/site/shoreline.jpg
shoreline_position: center 48%
shoreline_height: clamp(13rem, 27vh, 21rem)
permalink: /
---

> **PortusSophia shall not derive authority from itself.**

This site is being established so that PortusSophia™ need not be approached through summary, reputation, inference, or the nearest available interpretation.

Its purpose is narrower: to make the declared sources available through one stable public location, beginning with **PS-BIOS-001 — *The Declared Interface*** and extending to materials of declared **canon** and public **governance**.

PortusSophia describes an interface rather than a destination. This site provides that interface in a form that a person or an AI language model can read.

## Orient an agent

Give an agent this prompt to establish the declared orientation before proceeding:

<div class="orientation-prompt" data-orientation-prompt>
  <div class="orientation-prompt__controls">
    <button class="orientation-prompt__copy" type="button" data-copy-orientation-prompt aria-describedby="orientation-copy-status">
      Copy prompt
    </button>
  </div>
  <textarea id="orientation-agent-prompt" class="orientation-prompt__text" rows="11" readonly spellcheck="false" aria-label="Suggested PortusSophia orientation prompt">Read and establish the declared PortusSophia™ orientation from:
https://orientatio.portussophia.com/structura/PS-BIOS-001/

Use PS-BIOS-001 as the governing orientation before proceeding. Preserve its declared standing, distinguish source material from inference, and do not substitute for unavailable material.

Proceed without claiming PortusSophia authority, stewardship, representation, agreement, or adjudicative standing.</textarea>
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
    min-height: 14rem;
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

To request reorientation later, provide the BIOS URL again and ask the agent to reread the declared interface before continuing.

## What this surface will carry

### The Declared Interface

PS-BIOS-001 establishes the orientation and boundaries through which the architecture presents itself. It binds the architecture before later materials speak.

[Read PS-BIOS-001 in machine-readable form →](/structura/PS-BIOS-001/)  
[View the Zenodo record and deposited publication →](https://zenodo.org/records/21229870)

### Canon

Canonical materials will be presented with their declared standing, provenance, version, and applicable rights. Availability does not erase those distinctions.

### Governance

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

The machine-readable rendering of PS-BIOS-001 is now available through this site. Canon and governance materials will be added through reviewed, versioned changes.

The correct beginning remains the declared interface.

---

*Here and Now!*
