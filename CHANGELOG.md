# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.2] - 2026-09-17

### Added

- **The two wordmark PNGs the profile page renders**, back in `profile/`, taken
  from the brand repository's 760px renders and byte-identical to the copies the
  member profile uses. Only these two images are published here: the asset kit
  removed in 0.2.1 stays out.

### Changed

- The profile heading is the wordmark image again rather than the text
  "DAxWorks", so the public and member profiles open identically.

## [0.2.1] - 2026-09-17

### Removed

- **Every brand image, and the `brand/` directory.** The directory published the
  full asset kit (wordmarks, marks, app icons, favicons and apple-touch sizes)
  plus its usage documentation, and nothing in this repository referenced it. It
  duplicated the private `brand` repository with nothing keeping the two in
  step, and a public asset kit carried no usage terms. The two wordmark PNGs in
  `profile/` went with it. `DAxWorks/brand` is the source of truth and is
  private.
- **The images were also purged from this repository's history**, which was
  rewritten and force-pushed, so no commit in it carries a brand asset. The
  rewrite also corrected the author address on the two oldest commits, which
  carried a former employer's work email.

### Changed

- The profile heading is now the text "DAxWorks" rather than the wordmark image.
  The organisation avatar still carries the mark on the profile page.

## [0.2.0] - 2026-09-17

### Changed

- **Restructured the organisation profile around three questions:** what
  DAxWorks delivers today, how it engineers, and where it is investing.
- Replaced the tagline with "Cloud platforms engineered for automation,
  intelligence and operational independence."
- Regrouped the services into seven delivery areas, worded from the engineering
  standards and the capability catalogue, and closed the list with a tooling
  line limited to tools the organisation's repositories actually use.
- Presented the ten capability domains as a table, with the question each domain
  answers.

### Added

- **Engineering intelligence, labelled as an emerging capability.** What is in
  use today is kept separate from the direction, and the profile commits to
  backing anything described as emerging with a repository in this organisation
  before describing it as delivered.
- The engineering model diagram, from requirements to handover, with evidence as
  a stage of its own.
- A third principle: an engagement that cannot end is a dependency, not a
  delivery.
- `CHANGELOG.md` and `VERSION`.

### Removed

- Horizontal rule separators between profile sections.

## [0.1.0] - 2026-09-09

Recorded retrospectively from the git history. The repository was not versioned
before 0.2.0.

### Added

- The organisation profile, using DAxWorks alone and stating the founding year.
- Organisation-wide pull request template, issue templates and security policy,
  with `security@daxworks.io` as the security contact.
- The full service and scoping description.
- The DAxWorks brand assets, and the wordmark at the head of the profile.

### Removed

- The license file.
