# Change Log

## [Unreleased]

### Fixed
- Consolidated duplicate CSS variables for light and dark themes into a single, well-structured block.
- Removed duplicate `.skills-tags` selector to improve stylesheet maintainability.
- Corrected the scoping of light-mode variables by moving them to the `:root` selector within the corresponding media query.


## Public project selection — issue #23 (2026-10-17)

Reviewed public repository metadata, READMEs, and top-level contents on GitHub. No private repositories were inspected for inclusion. Existing six cards and their destinations are retained.

- Add [PromptVault](https://github.com/DochertyDev/PromptVault): implemented React app with prompt templates, workflows, local persistence, and tests; directly supports the AI practice. Its public [demo](https://dochertydev.github.io/PromptVault/) provides a product entry point.
- Add [TravelRanker](https://github.com/DochertyDev/TravelRanker): implemented single-file app with destination ranking, trip matching, and history; demonstrates a different interactive product. Public [demo](https://dochertydev.github.io/TravelRanker/).
- Add [Salesforce CRM Analytics](https://github.com/DochertyDev/Salesforce-CRM-Analytics): actual opportunity-team and NHL recipe/dashboard JSON plus import instructions, relevant to the Salesforce analytics practice. Link to repository only; requires a CRM Analytics org and dataset-ID configuration, so do not present it as a live web app. The standardization folder has a placeholder dashboard, so the description claims only recipes and dashboard definitions present elsewhere.
- Leave out [work-skills](https://github.com/DochertyDev/work-skills): useful public workflow/skill library, but overlaps existing developer tooling and is less representative as a product card. Its README explicitly notes limits on live agent validation.
- Leave out [ScriptureSteps](https://github.com/DochertyDev/ScriptureSteps): implemented React reading tracker with local persistence and a public demo, but less closely tied to the consulting/AI/platform focus than the three additions.
- Leave out [Video-Games](https://github.com/DochertyDev/Video-Games): small game folders and a minimal README, without a unified product demo or sufficiently documented user journey.

Descriptions are summaries of public documentation, not claims that all product workflows or Salesforce imports were independently validated. Project visuals are coordinated separately in issue #24.

### Coordinated project illustrations (#23 / #24)

The three added cards include original inline SVG conceptual illustrations, created for this portfolio, using the Atlas navy/ice-blue palette and platform layers. They show prompt templates/workflows, illustrative destination tiers, and datasets/recipes/dashboards. These are diagrams, not product screenshots or personal data; no third-party imagery or fonts were copied. The travel demo starts empty, analytics requires an org, and PromptVault has no repository screenshot license, so original diagrams explain their purpose more reliably. SVGs are embedded as data images with descriptive alt text; no extra runtime assets are needed. PR for #24 supplies the shared Atlas frame and locally retained screenshots for the six existing cards. Merge both for the full nine-project treatment.
