# Development Status

## Public status

Street Fighter II: CPS1 to SNES is an independently developed, non-commercial SNES implementation using the original Street Fighter II: The World Warrior CPS1 arcade game as a behavioral and audiovisual reference, targeting standard Super Nintendo hardware without enhancement chips or additional hardware. Full gameplay integration is not yet complete.

Presentation Demo 0.1 (T16) is publicly released as a pre-release. The statuses below distinguish this presentation scope from behaviors tested in separate builds and ongoing development.

## Status definitions

- **Validated in dedicated builds:** the identified component or behavior has been tested in builds focused on that scope; complete-game integration is not implied.
- **Validated in an integrated demonstration:** the identified presentation flow has been validated within the publicly released T16 sequence; full gameplay is outside that scope.
- **Publicly released presentation:** included in the published T16 presentation demo; complete gameplay is not implied.
- **In development:** implementation or broader coverage remains ongoing, even where selected results have been validated.
- **Pending integration:** integration into the complete gameplay experience remains unfinished.

## Development areas

| Area | Status | Validation scope and remaining work |
| --- | --- | --- |
| Intro | Publicly released presentation | Arcade introductory presentation validated separately; also included in the publicly released T16 presentation flow. |
| Title Screen | Publicly released presentation | Title presentation validated separately; also included in the publicly released T16 presentation flow. |
| Player Select | Publicly released presentation | Character selection validated within the publicly released T16 presentation sequence. |
| Travel/VS | Publicly released presentation | VS presentation validated within the publicly released T16 presentation sequence; no separate claim of complete travel behavior. |
| Character Graphics | In development | Character graphics and animation remain in progress. |
| Gameplay | Validated in dedicated builds; in development | Several behaviors implemented and tested in dedicated builds; complete combat and match behavior are not established by these tests. |
| Audio | Selected sequences validated; in development | Selected music, sound-effect, and voice sequences validated; broader implementation remains ongoing. The released presentation includes music, sound effects, and character announcements; complete audio coverage is not claimed. |
| Stages | In development | Backgrounds and associated visual effects remain in progress. |
| HUD | In development | HUD presentation and associated visual effects remain in progress. |
| Full Integration | Pending integration | Full gameplay integration is not yet complete; component results do not validate the complete game. |

## Public presentation release

[Presentation Demo 0.1 — Internal Build T16](PRESENTATION_DEMO_0_1.md) was [published on GitHub](https://github.com/InnenWahrheit/Street-Fighter-II-CPS1-to-SNES/releases/tag/presentation-demo-v0.1) on November 15, 2026 as a pre-release, tagged `presentation-demo-v0.1`. Its integrated presentation includes the introduction, title, credit/start interaction, character selection, and travel/VS sequence. It is not a complete playable game and does not establish integration of separately tested gameplay behaviors.

The maintainer reports successful testing of the T16 presentation sequence on original Super Nintendo hardware, bsnes, and Snes9x, with no execution failures or behavioral differences observed in the reported tests. These results apply only to the reported test scope; they do not establish universal compatibility across hardware revisions or emulator versions.

Hardware revisions, emulator versions, and detailed validation records are not specified in the release. These are maintainer-reported results, not independent tests performed for this documentation update.

## Reporting progress

Public updates should describe concrete observations and distinguish intended work, work in progress, and verified results. A claim of verification should identify what was tested, the relevant revision or milestone, the test environment, and any limitations. Emulator observations alone do not establish verification on standard SNES hardware.

Do not infer overall completion from individual demonstrations or assign unsupported completion percentages. List unverified areas as unverified, and record known compromises without implying that every development area has been tested.

## Availability and scheduling

A progress report, demonstration, or internal milestone is not a public release. The T16 presentation demo is available through the published release linked above; no future build or delivery date is promised. Future release availability must be confirmed by an explicit announcement under the [Release Policy](RELEASE_POLICY.md).

Public status updates must remain at the level of goals, observed behavior, and limitations. They must not disclose source code, internal tools, memory management details, conversion techniques, ROM files, patches, or copyrighted assets.

See the [README](../README.md) for project context and the [Changelog](../CHANGELOG.md) for recorded public-facing changes.
