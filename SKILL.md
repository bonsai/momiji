# momiji

## Purpose
Compare states across time or versions and make change visible.

## Type
Generic cognitive-operation skill.

## Inputs
- Two or more states, versions, records, or observations
- Their temporal or sequence information when available

## Outputs
- differences
- continuities
- newly appearing or disappearing elements
- changes in relationships or structure
- unresolved differences
- source references/provenance

## Procedure
1. Establish which states are being compared and their order.
2. Normalize only as much as necessary for a meaningful comparison.
3. Identify additions, removals, modifications, continuities, and reversals.
4. Separate observed change from possible explanations.
5. Preserve evidence and provenance for each significant difference.

## Constraints
- Do not assume that change implies improvement or decline.
- Do not invent causes for observed differences.
- Respect the temporal order of evidence.
- Remain domain-agnostic.

## Domain plugin hook
A domain plugin may define comparison dimensions, thresholds, terminology, or output schemas. It must not change the core operation: making change across states visible.
