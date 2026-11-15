# Street Fighter II: CPS1 to SNES

*Bringing the original arcade experience closer to the Super Nintendo.*

An independently developed, non-commercial SNES implementation using the original Street Fighter II: The World Warrior CPS1 arcade game as a behavioral and audiovisual reference, targeting standard Super Nintendo hardware without enhancement chips or additional hardware.

**No enhancement chips. No additional hardware. Just the Super Nintendo.**

## Project goals

The project aims to preserve the feel and character of the arcade experience within the capabilities of the standard SNES. Priorities include responsive controls, faithful combat behavior, recognizable visual presentation, and an audio experience consistent with the original game's identity.

These are development goals, not claims of completed features or exact arcade equivalence. Hardware constraints may require compromises, which should be described openly in public updates.

## Development areas

- **Arcade introduction and title presentation:** validated in dedicated builds.
- **Character selection and VS presentation:** publicly released in the T16 presentation sequence.
- **Character graphics and animation:** development in progress.
- **Gameplay mechanics:** several behaviors implemented and tested in dedicated builds; broader development continues.
- **Arcade music, sound effects, and voices:** selected sequences validated; broader implementation ongoing.
- **Backgrounds, HUD, and visual effects:** development in progress.
- **Full gameplay integration:** not yet complete.

## Development status

Component validation establishes progress within the tested scope; it does not establish that the complete game is integrated or validated. See [Development Status](docs/DEVELOPMENT_STATUS.md) for the distinction between dedicated builds, the publicly released T16 presentation sequence, ongoing development, and pending integration.

## Public presentation release

[Presentation Demo 0.1 — Internal Build T16](https://github.com/InnenWahrheit/Street-Fighter-II-CPS1-to-SNES/releases/tag/presentation-demo-v0.1) was published on November 15, 2026 as a public **pre-release**, tagged `presentation-demo-v0.1`. “Internal Build T16” identifies the build; the presentation demo is publicly released.

The release includes the introduction, title, credit/start interaction, character selection, travel/VS presentation, and music, sound effects, and character announcements in that sequence. It is a presentation preview, not a complete playable game; full gameplay integration remains unfinished.

The release page links to `SF2_CPS1_SNES_Presentation_Demo_0.1_TESTED.zip` in its description. See the [published release documentation](docs/PRESENTATION_DEMO_0_1.md) for scope, download information, and limitations.

The maintainer reports successful testing of the T16 presentation sequence on original Super Nintendo hardware, bsnes, and Snes9x, with no execution failures or behavioral differences observed in the reported tests. These results apply only to the reported test scope; they do not establish universal compatibility across hardware revisions or emulator versions.

## Public releases

Development updates and demonstrations do not imply that a build is available for download. Any future public release requires an explicit maintainer decision and a release announcement identifying what is available, its validation scope, and known limitations. No release date is promised here.

See the [Release Policy](docs/RELEASE_POLICY.md) for the full process. This repository's public documentation does not distribute game files or third-party assets.

## Documentation

- [Development Status](docs/DEVELOPMENT_STATUS.md): goals, evidence standards, and public progress reporting.
- [Presentation Demo 0.1](docs/PRESENTATION_DEMO_0_1.md): published presentation release scope, download information, and reported tests.
- [Changelog](CHANGELOG.md): recorded public-facing changes.
- [Contributing](CONTRIBUTING.md): feedback and documentation contribution guidelines.
- [Release Policy](docs/RELEASE_POLICY.md): review, approval, and release communication requirements.

## Independence and rights

This is an unofficial project, unaffiliated with and not endorsed by Capcom or Nintendo. Street Fighter II and related names and materials belong to their respective rights holders. The project's non-commercial purpose does not grant permission to redistribute third-party material, and this documentation grants no such permission.
