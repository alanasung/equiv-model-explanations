<p align="center">
  <h1 align="center">Explanations That Survive Functionally Equivalent Models</h1>
  <p align="center"><strong>Check whether component-level explanations remain stable across models trained to the same function.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Explanations That Survive Functionally Equivalent Models**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Check whether component-level explanations remain stable across models trained to the same function.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
