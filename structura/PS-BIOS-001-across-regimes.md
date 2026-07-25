---
layout: shoreline-masthead
title: PS-BIOS-001 Across Regimes
eyebrow: Interpretive Orientation Map · Non-Canonical
intro: A bounded map of how the declared disciplines of PS-BIOS-001 may condition inquiry across several non-equivalent regimes.
description: An interpretive, non-canonical map of PS-BIOS-001 across science, ethics, governance, and computation.
permalink: /structura/PS-BIOS-001/across-regimes/
---

<div class="bios-regime-map">
  <section class="bios-regime-standing" aria-labelledby="bios-regime-standing-title">
    <p class="bios-regime-kicker">Standing</p>
    <h2 id="bios-regime-standing-title">Interpretive orientation map</h2>
    <p>This page is not part of the deposited text of PS-BIOS-001. It does not extend, revise, or replace <em>The Declared Interface</em>.</p>
  </section>

  <div class="bios-regime-intro">
    <p>The correspondences below show how one declared orientation may encounter different failure conditions without treating the regimes as equivalent. Each correspondence remains bounded by the regime in which it is proposed.</p>
    <p><a class="button-link secondary" href="/#ps-bios-001">Read PS-BIOS-001 — <em>The Declared Interface</em> →</a></p>
  </div>

  <section class="bios-regime-section" aria-labelledby="bios-regime-table-title">
    <div class="bios-regime-heading">
      <p class="bios-regime-kicker">Comparative orientation</p>
      <h2 id="bios-regime-table-title">Across regimes</h2>
      <p>One orientation; distinct failure conditions, restraints, and preserved capacities.</p>
    </div>

    <div class="bios-regime-table-wrap" role="region" aria-label="PS-BIOS-001 across regimes comparison" tabindex="0">
      <table class="bios-regime-table">
        <colgroup>
          <col class="bios-regime-col-regime">
          <col class="bios-regime-col-failure">
          <col class="bios-regime-col-discipline">
          <col class="bios-regime-col-constrains">
          <col class="bios-regime-col-preserves">
        </colgroup>
        <thead>
          <tr>
            <th scope="col">Regime</th>
            <th scope="col">Recurring Failure Mode</th>
            <th scope="col">BIOS Discipline</th>
            <th scope="col">Constrains Against</th>
            <th scope="col">Preserves Capacity For</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row" data-label="Regime">Science</th>
            <td data-label="Recurring Failure Mode">Ambiguity suppression, model overreach, category collapse</td>
            <td data-label="BIOS Discipline">Non-Resolution; distinction before synthesis; capacity horizons</td>
            <td data-label="Constrains Against">Premature closure; treating formalization as exhaustive; importing correspondence across regimes</td>
            <td data-label="Preserves Capacity For">Honest uncertainty; model revision; emergence of previously unavailable distinctions</td>
          </tr>
          <tr>
            <th scope="row" data-label="Regime">Ethics</th>
            <td data-label="Recurring Failure Mode">Absolutism, coercion, reduction of participants to positions</td>
            <td data-label="BIOS Discipline">Dignity, Respect, Kindness; Non-Closure</td>
            <td data-label="Constrains Against">Moral totalization; unnecessary injury; foreclosure of responsible disagreement</td>
            <td data-label="Preserves Capacity For">Irreducible participation; disciplined disagreement; continued inquiry</td>
          </tr>
          <tr>
            <th scope="row" data-label="Regime">Governance</th>
            <td data-label="Recurring Failure Mode">Authority expansion, rule proliferation, legitimacy loss</td>
            <td data-label="BIOS Discipline">Self-binding; declared standing; Non-Coercive Emergence</td>
            <td data-label="Constrains Against">Using BIOS as law or unquestionable authority; collapsing evaluation into decision</td>
            <td data-label="Preserves Capacity For">Bounded governance; inspectable standing; multi-participant coherence without compelled agreement</td>
          </tr>
          <tr>
            <th scope="row" data-label="Regime">Computation</th>
            <td data-label="Recurring Failure Mode">Over-formalization, provenance loss, ambiguity collapse</td>
            <td data-label="BIOS Discipline">Declared interface; distinction-first posture; source-boundary discipline</td>
            <td data-label="Constrains Against">Treating BIOS as an executable specification; silent assumption import; false uniformity</td>
            <td data-label="Preserves Capacity For">Provenance-aware systems; bounded inference; explicit unresolved states</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <aside class="bios-regime-restraint" aria-labelledby="bios-regime-restraint-title">
    <p class="bios-regime-kicker">Reading restraint</p>
    <h2 id="bios-regime-restraint-title">Orientation is not application</h2>
    <p>This map should not be used to claim that PS-BIOS-001 supplies a complete scientific method, ethical doctrine, governance model, or computational specification. It identifies possible orienting correspondences only. Their adequacy must be examined within the regime to which each row belongs.</p>
    <p class="bios-regime-closing"><em>Orientation remains prior to application.</em></p>
  </aside>
</div>

<style>
  .bios-regime-map {
    width: min(92vw, 82rem);
    max-width: none;
    margin-inline-start: 50%;
    transform: translateX(-50%);
  }

  .bios-regime-standing,
  .bios-regime-restraint {
    max-width: 72ch;
    padding: clamp(1.35rem, 3vw, 2rem);
    border: 1px solid var(--rule, #cfc5b5);
    border-left: 0.35rem solid var(--gold, #b88a2b);
    background: rgba(255, 255, 255, 0.42);
    box-shadow: 0 0.8rem 2rem rgba(13, 27, 42, 0.07);
  }

  .bios-regime-standing h2,
  .bios-regime-restraint h2,
  .bios-regime-heading h2 {
    margin: 0.2rem 0 0.8rem;
    color: var(--navy, #0d1b2a);
  }

  .bios-regime-standing p:last-child,
  .bios-regime-restraint p:last-child {
    margin-bottom: 0;
  }

  .bios-regime-kicker {
    margin: 0;
    color: var(--gold-dark, #8a651c);
    font-size: 0.78rem;
    font-weight: 800;
    letter-spacing: 0.09em;
    text-transform: uppercase;
  }

  .bios-regime-intro {
    max-width: 72ch;
    margin: clamp(1.75rem, 4vw, 2.75rem) 0;
  }

  .bios-regime-intro p {
    font-size: 1.04rem;
    line-height: 1.72;
  }

  .bios-regime-section {
    margin-top: clamp(2.5rem, 5vw, 4rem);
  }

  .bios-regime-heading {
    max-width: 72ch;
    margin-bottom: 1.4rem;
  }

  .bios-regime-heading > p:last-child {
    margin-bottom: 0;
    color: var(--warm-slate, #4d5560);
  }

  .bios-regime-table-wrap {
    overflow-x: auto;
    border: 1px solid var(--rule, #cfc5b5);
    border-radius: 0.65rem;
    background: var(--paper, #f4efe6);
    box-shadow: 0 1rem 2.4rem rgba(13, 27, 42, 0.09);
  }

  .bios-regime-table {
    width: 100%;
    min-width: 68rem;
    margin: 0;
    border-collapse: separate;
    border-spacing: 0;
    table-layout: fixed;
    font-size: 0.98rem;
    line-height: 1.55;
  }

  .bios-regime-col-regime { width: 10%; }
  .bios-regime-col-failure { width: 19%; }
  .bios-regime-col-discipline { width: 20%; }
  .bios-regime-col-constrains { width: 25%; }
  .bios-regime-col-preserves { width: 26%; }

  .bios-regime-table th,
  .bios-regime-table td {
    padding: 1.15rem 1.1rem;
    vertical-align: top;
    border: 0;
    border-bottom: 1px solid var(--rule, #cfc5b5);
    text-align: left;
    overflow-wrap: anywhere;
  }

  .bios-regime-table thead th {
    position: sticky;
    top: 0;
    z-index: 1;
    background: var(--navy, #0d1b2a);
    color: #fff;
    font-size: 0.82rem;
    font-weight: 800;
    letter-spacing: 0.035em;
    line-height: 1.35;
    text-transform: uppercase;
  }

  .bios-regime-table tbody th {
    color: var(--navy, #0d1b2a);
    font-size: 1.02rem;
    font-weight: 800;
  }

  .bios-regime-table tbody tr:nth-child(even) th,
  .bios-regime-table tbody tr:nth-child(even) td {
    background: rgba(13, 27, 42, 0.035);
  }

  .bios-regime-table tbody tr:last-child th,
  .bios-regime-table tbody tr:last-child td {
    border-bottom: 0;
  }

  .bios-regime-table tbody tr:hover th,
  .bios-regime-table tbody tr:hover td {
    background: rgba(184, 138, 43, 0.09);
  }

  .bios-regime-restraint {
    margin-top: clamp(2.5rem, 5vw, 4rem);
  }

  .bios-regime-closing {
    padding-top: 0.8rem;
    border-top: 1px solid var(--rule, #cfc5b5);
    color: var(--navy, #0d1b2a);
    font-family: var(--font-serif, Georgia, serif);
    font-size: 1.08rem;
  }

  @media (max-width: 760px) {
    .bios-regime-map {
      width: min(92vw, 42rem);
    }

    .bios-regime-table-wrap {
      overflow: visible;
      border: 0;
      border-radius: 0;
      background: transparent;
      box-shadow: none;
    }

    .bios-regime-table,
    .bios-regime-table thead,
    .bios-regime-table tbody,
    .bios-regime-table tr,
    .bios-regime-table th,
    .bios-regime-table td {
      display: block;
      width: 100%;
      min-width: 0;
    }

    .bios-regime-table thead {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      white-space: nowrap;
      border: 0;
    }

    .bios-regime-table tbody tr {
      margin-bottom: 1.25rem;
      overflow: hidden;
      border: 1px solid var(--rule, #cfc5b5);
      border-radius: 0.65rem;
      background: var(--paper, #f4efe6);
      box-shadow: 0 0.75rem 1.8rem rgba(13, 27, 42, 0.08);
    }

    .bios-regime-table tbody th,
    .bios-regime-table tbody td,
    .bios-regime-table tbody tr:nth-child(even) th,
    .bios-regime-table tbody tr:nth-child(even) td {
      padding: 0.9rem 1rem;
      border-bottom: 1px solid var(--rule, #cfc5b5);
      background: transparent;
    }

    .bios-regime-table tbody th {
      background: var(--navy, #0d1b2a) !important;
      color: #fff;
      font-size: 1.16rem;
    }

    .bios-regime-table tbody td::before {
      display: block;
      margin-bottom: 0.25rem;
      color: var(--gold-dark, #8a651c);
      content: attr(data-label);
      font-size: 0.72rem;
      font-weight: 800;
      letter-spacing: 0.07em;
      text-transform: uppercase;
    }

    .bios-regime-table tbody tr > :last-child {
      border-bottom: 0;
    }
  }
</style>
