# Publishing a Shadow the Hedgehog VR release

This repository is prepared for future GitHub Releases. No binaries or release tags have been published as part of creating the project hub.

1. Prepare the intended installer or mod archive from the correct project revision. Verify it contains only distributable material and the required dependency notices/corresponding source. Keep game files, BIOS, saves, private logs and credentials out of the package.
2. Test the exact packaged build with the documented game version and runtime. Record what was tested on a headset, what was checked only on desktop, and what remains unverified.
3. Calculate SHA-256 checksums for each attachment, for example with `Get-FileHash -Algorithm SHA256 -LiteralPath '<release-file>'` in PowerShell.
4. Open [Draft a new release](https://github.com/NullxVoid00/Shadow-the-Hedgehog-VR/releases/new). Choose a version tag such as `v0.1.0-alpha.1`, target the intended documentation commit, and use `docs/RELEASE_TEMPLATE.md` as the notes. The source revision used to build a binary should also be recorded in the notes if it lives elsewhere.
5. Attach the installer/archive, checksums, and any required notices/source supplement. Mark unfinished experimental builds as **pre-release**. Save a draft while preparing; publish when that specific build is ready to share.
6. Verify the downloads from the published release. Update the README's release status, compatibility and installation sections to match that build, and update its entry on the portfolio if the public availability changed.

Keep binary downloads as Release attachments. The automatic GitHub source ZIP contains the files in this hub and is not the mod installer. A public source-code release can be added separately after reviewing its scope and dependencies.

## Before publishing

- [ ] Release title/tag and exact build revision recorded.
- [ ] Supported game edition/build and PC VR runtime stated.
- [ ] Install, update, removal and save-preservation behavior explained.
- [ ] Controls and current limitations included.
- [ ] Actual headset testing separated from automated/desktop checks.
- [ ] Package contents, dependency notices and source obligations reviewed.
- [ ] SHA-256 checksums match the uploaded files.
- [ ] Pre-release flag matches the build's state.
