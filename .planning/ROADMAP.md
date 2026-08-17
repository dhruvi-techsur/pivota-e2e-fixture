# Roadmap

Deterministic fixture consumed by Pivota's L1 e2e suite. Pivota reads this file
to derive phases; the suite never writes to this repository.

## Phase 1: Seeded foundation

**Status**: pending

Baseline phase. Exists so `phases/sync` yields at least one phase, which in turn
gives the kanban board a phase card — the parent every other card descends from.

## Phase 2: Seeded follow-up

**Status**: pending

A second phase, so dependency and ordering behaviour has something to order.

## Phase 3: Seeded completed

**Status**: completed (2026-01-01)

Completed on purpose: milestone percentage, "phases completed" counters and the
done-column rendering all need a finished phase to be non-zero.
