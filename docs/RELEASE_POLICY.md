# Public Release Policy

## Scope

This policy governs public release decisions and communication for Street Fighter II CPS1 to SNES, an independent, non-commercial project targeting standard SNES hardware without enhancement chips.

Publishing documentation, describing progress, or showing a demonstration does not make a playable build publicly available. This policy itself announces no build or release date.

## Public documentation boundaries

Public documentation may describe project goals, development areas, verified observations, known limitations, and release decisions. It must not include source code, internal tools, memory management details, conversion techniques, ROM files, patches, or copyrighted assets. Public issues, pull requests, and attachments must respect the same boundaries.

No future distribution is authorized merely because the project is non-commercial. Any proposed public material must be reviewed for permission to share it. Material that cannot be distributed with appropriate permission must be excluded.

## Review and approval

Every proposed public release requires:

1. A defined scope identifying exactly what is proposed for publication.
2. Review of the proposed material for the public content boundaries and applicable rights.
3. Evidence supporting any functional or hardware compatibility claims, with unverified areas clearly identified.
4. Release notes describing verified changes, known issues, and relevant limitations.
5. Explicit maintainer approval of the final material and a separate, deliberate publication decision.

Prepare documentation and release proposals on separate branches and submit them through pull requests. A merged documentation pull request does not authorize a playable release. Do not merge automatically, enable automatic merging, or publish releases automatically as part of documentation work.

## Release announcements

An approved release announcement must identify:

- The release identifier and publication date.
- Exactly what is available and where the approved material can be obtained.
- Verified changes and the scope of testing, including standard SNES hardware validation when claimed.
- Known issues, compromises, and unverified behavior.

Announce only material that is actually available at the stated location. Do not describe unreleased or privately tested builds as publicly downloadable. Do not use unsupported completion percentages or promise dates without an explicit maintainer commitment.

## Status and changelog maintenance

Keep the [Development Status](DEVELOPMENT_STATUS.md), [Changelog](../CHANGELOG.md), and [README](../README.md) consistent with approved announcements. Keep pending changes under **Unreleased** until publication is confirmed. Documentation-only changes should be identified as such and must not imply gameplay progress or a playable release.

If an announcement is inaccurate or approved material becomes unavailable, correct the public record promptly and explain the affected availability or claim.
