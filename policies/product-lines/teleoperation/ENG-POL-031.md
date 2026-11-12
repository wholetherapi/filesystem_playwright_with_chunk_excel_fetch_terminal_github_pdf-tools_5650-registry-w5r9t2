# ENG-POL-031 — Teleoperation Product-Line Review Standard

- **Level:** Product line
- **Owner:** Teleoperation Engineering
- **Scope:** The Teleoperation product line only
- **Status:** Active

## 1. Applicability

This standard applies to all releases owned by the Teleoperation product line.

## 2. Minimum

The Teleoperation product line must document a minimum of **54 hours** of independent
verification review per major release.

## 3. Remote-operation review

Teleoperation releases add a dedicated review of the remote-operation safety path,
covering link loss behavior, operator handover, and degraded-network handling. The
remote-operation review is scheduled separately from the general release review and its
hours are counted toward the minimum above.

## 4. Simulator evidence

Evidence from the hardware-in-the-loop simulator is required for every remote-operation
review. Simulator runs must be reproducible from the recorded configuration bundle.

## 5. Review board

The Teleoperation review board meets at design freeze and at release candidate. Board
minutes are attached to the release quality record.

## 6. Evidence retention

Review logs, simulator configuration bundles, board minutes, and operator attestations
are retained for seven years in the release quality archive.
