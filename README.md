# Snow Moon — Open Production Pipeline

**Project:** *Snow Moon*  
**Writing credit:** Vitalik Buterin *(confirm exact credit and permitted wording against the source project)*  
**Direction:** Idowu Daniel  
**Format:** Short film / episodic adaptation  
**Editing software:** CapCut  
**Repository status:** Production documentation starter — replace all TODOs and add the actual materials before announcing the repository as complete.

## About

This repository documents the production process behind *Snow Moon*: screenplay and scene planning, character references, storyboards, AI-assisted image/video prompts, generated clips, sound assets, and CapCut post-production.

The aim is to make the meaningful production materials available so other creators can understand the workflow and build on materials they are permitted to reuse. This repository is a documentation and asset-sharing project; it does not redistribute CapCut, third-party models, commercial services, or other software.

## Repository map

- [`01-source-and-adaptation/`](01-source-and-adaptation/) — source references, adaptation notes, and attribution.
- [`02-screenplay/`](02-screenplay/) — scripts and scene breakdowns.
- [`03-character-design/`](03-character-design/) — character bible and reference images.
- [`04-storyboards/`](04-storyboards/) — storyboard images and shot planning.
- [`05-prompts/`](05-prompts/) — prompts, iterations, settings, and generation logs.
- [`06-production-workflow/`](06-production-workflow/) — end-to-end process, shot list, and continuity notes.
- [`07-generated-media/`](07-generated-media/) — selected generated clips or pointers to large hosted files.
- [`08-audio/`](08-audio/) — music and sound-effects inventory and credits.
- [`09-post-production-capcut/`](09-post-production-capcut/) — CapCut editing notes, export settings, and project-file guidance.
- [`10-tools-and-models/`](10-tools-and-models/) — tools, model versions, settings, limitations, and dependencies.
- [`11-release/`](11-release/) — final-film links, version notes, and release checklist.
- [`docs/`](docs/) — reproduction guide, lessons learned, and contribution guidance.

## Production pipeline

1. **Adaptation:** document the source material used and explain adaptation choices.
2. **Screenplay:** divide the story into scenes and shots.
3. **Character design:** define each character's visual identity and continuity constraints.
4. **Storyboarding:** plan framing, camera angle, action, and transitions.
5. **Prompt development:** record prompts and relevant settings used to generate each asset.
6. **Clip generation:** map generated clips to scene and shot IDs.
7. **Audio:** record music and sound-effect sources, licenses, and timing notes.
8. **CapCut editing:** document timeline structure, transitions, color adjustments, audio mix, and export settings.
9. **Release:** link to the final film and describe any known limitations.

## Start here

1. Read [`docs/REPRODUCTION-GUIDE.md`](docs/REPRODUCTION-GUIDE.md).
2. Check [`01-source-and-adaptation/ATTRIBUTION-AND-RIGHTS.md`](01-source-and-adaptation/ATTRIBUTION-AND-RIGHTS.md).
3. Replace the templates' `TODO` fields with accurate production information.
4. Add the actual script, character references, storyboards, prompts, and workflow notes.
5. Audit every asset before publishing it.
6. Use [`11-release/RELEASE-CHECKLIST.md`](11-release/RELEASE-CHECKLIST.md) before announcing the repository.

## Assets and large files

Do not commit credentials, API keys, private information, or assets you do not have permission to redistribute. GitHub repositories have file-size limits; use Git LFS or a suitable external host for large video files, and link to them from the repository. If a file is hosted externally, document its license and access requirements. Do not upload commercial model weights or third-party software installers.

Suggested approach:
- Commit text documentation, prompt logs, small images, and metadata directly.
- Consider Git LFS for large source media when appropriate.
- For externally hosted clips, include stable links plus file names, scene IDs, checksums if practical, and reuse terms.

## Licensing

**Do not assume that the original project's GPL v3 license automatically covers every asset in this repository.** Verify the source project's license and any adaptation-specific requirements before release. Add a `LICENSE` file only after deciding which repository materials you have the authority to license and under what terms. Third-party music, fonts, model outputs, stock material, and commercial tools may have separate terms.

See [`LICENSE-AND-THIRD-PARTY-NOTICE.md`](LICENSE-AND-THIRD-PARTY-NOTICE.md) and [`01-source-and-adaptation/ATTRIBUTION-AND-RIGHTS.md`](01-source-and-adaptation/ATTRIBUTION-AND-RIGHTS.md). This repository is not legal advice.

## Credits

- **Project:** *Snow Moon*
- **Direction:** Idowu Daniel
- **Writing / source-work credit:** Vitalik Buterin — confirm the exact wording and source attribution.
- **Editing:** CapCut
- **Other tools, models, and contributors:** TODO — complete `10-tools-and-models/TOOLS-AND-MODELS.md` and `CREDITS.md`.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Contributions should improve reproducibility, documentation, accessibility, or reusable assets. Contributors must identify third-party dependencies and confirm that they have permission to share submitted material.

## Project status

This repository template is not yet a complete production archive. It becomes a meaningful open-production release when the actual materials, prompt logs, credits, tool versions, and rights notes have been added and reviewed.
