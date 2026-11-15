# Development Status

## Public status

Street Fighter II: CPS1 to SNES is an independent, non-commercial project targeting standard Super Nintendo hardware without enhancement chips or additional hardware. Several presentation components and gameplay behaviors have been validated within limited build scopes. Full gameplay integration is not yet complete.

The statuses below reflect the project achievements reported for this documentation update. They do not establish a complete playable game, public build availability, or comprehensive hardware compatibility. Test environments and detailed validation records are not provided here; no broader hardware verification is claimed.

## Status definitions

- **Validated in dedicated builds:** the identified component or behavior has been tested in builds focused on that scope; complete-game integration is not implied.
- **Validated in an integrated demonstration:** the identified presentation flow has been validated within the internal demonstration; full gameplay is outside that scope.
- **In development:** implementation or broader coverage remains ongoing, even where selected results have been validated.
- **Pending integration:** integration into the complete gameplay experience remains unfinished.

## Development areas

| Area | Status | Validation scope and remaining work |
| --- | --- | --- |
| Intro | Validated in dedicated builds | Arcade introductory presentation validated separately; also included in the internal T16 presentation flow. |
| Title Screen | Validated in dedicated builds | Title presentation validated separately; also included in the internal T16 presentation flow. |
| Player Select | Validated in an integrated demonstration | Character selection validated within the internal presentation demonstration. |
| Travel/VS | Validated in an integrated demonstration | VS presentation validated within the internal presentation demonstration; no separate claim of complete travel behavior. |
| Character Graphics | In development | Character graphics and animation remain in progress. |
| Gameplay | Validated in dedicated builds; in development | Several behaviors implemented and tested in dedicated builds; complete combat and match behavior are not established by these tests. |
| Audio | Selected sequences validated; in development | Selected music, sound-effect, and voice sequences validated; broader implementation remains ongoing. No specific test environment is asserted here. |
| Stages | In development | Backgrounds and associated visual effects remain in progress. |
| HUD | In development | HUD presentation and associated visual effects remain in progress. |
| Full Integration | Pending integration | Full gameplay integration is not yet complete; component results do not validate the complete game. |

## First public preview candidate

[Presentation Demo 0.1 — Internal Build T16](PRESENTATION_DEMO_0_1.md) demonstrates the integrated introductory presentation, title sequence, character selection, and VS flow. It is a presentation-focused preview candidate, not a complete playable game. The internal demonstration does not establish integration of the separately tested gameplay behaviors.

The actual ROM or patch has not been approved for distribution. This candidate is not publicly available, and no release date is announced.

## Reporting progress

Public updates should describe concrete observations and distinguish intended work, work in progress, and verified results. A claim of verification should identify what was tested, the relevant revision or milestone, the test environment, and any limitations. Emulator observations alone do not establish verification on standard SNES hardware.

Do not infer overall completion from individual demonstrations or assign unsupported completion percentages. List unverified areas as unverified, and record known compromises without implying that every development area has been tested.

## Availability and scheduling

A progress report, demonstration, or internal milestone is not a public release. This document announces no download, release date, or delivery commitment. Future release availability must be confirmed by an explicit announcement under the [Release Policy](RELEASE_POLICY.md).

Public status updates must remain at the level of goals, observed behavior, and limitations. They must not disclose source code, internal tools, memory management details, conversion techniques, ROM files, patches, or copyrighted assets.

See the [README](../README.md) for project context and the [Changelog](../CHANGELOG.md) for recorded public-facing changes.
