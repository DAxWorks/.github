## What changed

<!-- One paragraph. The reader should not have to open the diff to know the
     shape of this change. -->

## Why

<!-- The decision, not the mechanics. Link the issue if there is one. -->

## Risk

<!-- Required when anything is destroyed, replaced, or cannot be reverted by
     reverting the commit. Say what happens to the data, even when the answer
     is "nothing, it is empty". Write "none" if there genuinely is none. -->

## Plan review

<!-- For infrastructure changes. CI posts the plan as a comment; confirm you
     read it, not just that it ran. -->

- [ ] The change count matches the intent
- [ ] Nothing holding state is being replaced
- [ ] Nothing is being destroyed that is not described above

## Checks

- [ ] The quality gate passes
- [ ] Documentation updated, if behaviour changed
- [ ] `CHANGELOG.md` updated, if behaviour changed
- [ ] No secret in code, tfvars, or the commit history
- [ ] Every new suppression states its reason

<!-- Standards: https://github.com/DAxWorks/engineering-standards -->
