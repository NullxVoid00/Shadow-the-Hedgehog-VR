# Shadow the Hedgehog VR

**In development · No public mod release yet · PC VR**

Bring Shadow's weapons, speed and action into PC VR. This project adapts **FoxWorkshop Shadow Recompiled**, adding tracked weapon handling, physical interaction experiments, comfort options and a dedicated installer/launcher.

[Future downloads & release notes](https://github.com/NullxVoid00/Shadow-the-Hedgehog-VR/releases) · [Report an issue](https://github.com/NullxVoid00/Shadow-the-Hedgehog-VR/issues) · [Abyssal Light Games](https://nullxvoid00.github.io/)

## Release status

This is the public project and future release hub. **There is no downloadable mod build published here yet.** The repository currently contains project information and release documentation; GitHub's **Code → Download ZIP** downloads those documents, not an installable mod.

When a build is ready, its installer or archive, supported game version, controls, installation steps and known issues will be published under [Releases](https://github.com/NullxVoid00/Shadow-the-Hedgehog-VR/releases). Use **Watch → Custom → Releases** to follow future downloads. No release date is announced.

## What is being developed

| Area | Current development work |
| --- | --- |
| **Tracked weapons** | The development branch includes weapon fitting, hand-to-hand transfer, physical pickup and native melee swing requests, with button fallbacks. |
| **World interaction** | Physical vehicle steering/aiming and supported environment interactions are implemented for further testing. |
| **Comfort and presentation** | Snap/smooth turning, movement options, HUD controls, Quest instructions and stereo rendering for real-time cutscenes are included. |
| **Installer and launcher** | Local development setup verifies the supported base, installs a VR patch, selects a launch-specific OpenXR runtime, and supports repair/removal. |
| **Progress** | Earlier Steam Link headset testing confirmed both-eye menus and improved gameplay; newer interaction and presentation changes need a retest. |

## Target setup

- **Game / platform:** Windows x64; FoxWorkshop Shadow Recompiled v1.0.0 with its supported Xbox game release. Prepare the original recomp with your own game before applying a future VR release.
- **VR setup:** OpenXR PC VR with tracked controllers. The launcher includes SteamVR / Steam Link, Virtual Desktop / VDXR, and system-runtime choices. No standalone Quest build is currently offered.
- **Game ownership:** Supply your own required game files. No commercial game data, ROM, disc image, BIOS or save data is provided by this repository.

## Development controls

These are the current documented starting mappings, not a finalized release manual. The instructions shipped with a future build take precedence.

| Input | Action |
| --- | --- |
| Left / right stick | Move / smooth or snap turn |
| Weapon-hand trigger | Native weapon or attack action |
| Grip near a weapon / second hand | Supported pickup / handoff |
| Deliberate melee swing | Native melee request in the development build |
| Right stick: press and release | Start / pause |
| Both stick clicks: hold one second | Recenter |

## Known limitations and next work

- Full-game coverage, weapon families, vehicles, rails, special forms and altered gravity still require gameplay testing.
- Physical crouching does not resize native collision; roomscale movement uses a restricted native path rather than a complete capsule solution.
- The new weapon/body alignment and physical damage interactions need headset acceptance.
- Optional prerecorded-movie depth conversion estimates missing depth from private game files. It is separate from genuine stereo real-time cutscenes and no game-derived cache is included here.

Builds, automated checks and desktop captures do not by themselves establish headset comfort, full-game compatibility or a release-ready experience. The descriptions above distinguish implemented development work from unfinished work.

## Installing a future release

Installation instructions will accompany each published build. Until then, there is no supported public installation procedure or binary to download from this repository. Game-version and runtime requirements may change as development continues.

## Feedback

Use [Issues](https://github.com/NullxVoid00/Shadow-the-Hedgehog-VR/issues) for questions or reports. For a future build, include its version, game version, headset/runtime and clear reproduction steps. Remove personal paths and private information from logs, and do not attach game files or saves.

## Credits

VR project by **NullxVoid / Abyssal Light Games**. This is an unofficial fan project and is not affiliated with or endorsed by the original game's creators or publishers.

- [Shadow Recompiled — FoxWorkshop](https://github.com/FoxWorkshop/ShadowRecomp) — Upstream recompilation foundation; this repository is the separate VR project hub.

Original games, names and assets belong to their respective owners. Upstream code and dependencies retain their own licenses. Future distributions will include the applicable notices and source obligations; this documentation hub does not relicense upstream or game material.

## Maintaining releases

See the [release guide](docs/RELEASE_GUIDE.md) and [release notes template](docs/RELEASE_TEMPLATE.md).

*Project information reviewed 2026-11-16 against local development documentation. This date is not a release or headset-certification date.*
