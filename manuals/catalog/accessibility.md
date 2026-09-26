# Catalog accessibility manual

Product area: catalog. Entries follow the review grammar.

## Open findings

The focus order finding is tracked here.
- [ ] ACTION: Keyboard focus order <!-- wcag: SC-101; owner: Mina -->

The following lines do not satisfy the grammar and are ignored.
- [ ] action: Lowercase prefix is not an ACTION entry <!-- wcag: SC-101; owner: Dana -->
  - [ ] ACTION: Indented entries are nested and ignored <!-- wcag: SC-101; owner: Dana -->
- [ ] ACTION: <!-- wcag: SC-101; owner: Dana -->
- [ ] ACTION: Unclosed WCAG comment is malformed <!-- wcag: SC-101; owner: Dana
- [X] ACTION: Uppercase X is not a resolved marker <!-- wcag: SC-101; owner: Dana -->

## Resolved findings

- [x] ACTION: Skip link has an accessible name <!-- wcag: sc-101; owner: Omar  -->

The duplicate below collapses into the line 8 record.
- [ ] ACTION: Keyboard focus order <!-- wcag: SC-101; owner: Ana -->

## Ignored examples

```text
- [ ] ACTION: Fenced entries are ignored <!-- wcag: SC-101; owner: Mina -->
- [x] ACTION: Fenced entries without a comment are ignored too
```
