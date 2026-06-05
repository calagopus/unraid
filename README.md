# Community Apps Starter Template

Use this repository as a GitHub template when you want a clean starting point for a new Community Apps submission repository.

## Quick Start

1. Click **Use this template** on GitHub and create your own repository.
2. Replace the placeholder values in `ca_profile.xml`, `templates/example-app.xml`, and `plugins/example-plugin.xml`.
3. Replace `icon.svg` with your own repository icon, or update `ca_profile.xml` to point at a hosted icon you control.
4. Keep one XML file per Docker app under `templates/`.
5. Keep one XML wrapper per plugin under `plugins/`.
6. Delete the example files you do not need.
7. Commit and push your repository.
8. Run **Validate** and **Scan** in the Community Apps submit flow: `/submit`.

## Starter Files

- `README.md`: onboarding notes for whoever maintains the repository.
- `LICENSE`: starter MIT license text. Replace the placeholder copyright line.
- `.gitignore`: keeps common OS junk out of the repo.
- `icon.svg`: starter repository icon referenced by `ca_profile.xml`.
- `ca_profile.xml`: repository overview and support metadata shown in Community Apps.
- `templates/example-app.xml`: starter Docker application template.
- `plugins/example-plugin.xml`: starter plugin wrapper.

## Submission Notes

- Keep `ca_profile.xml` in the repository root.
- Every Docker app entry needs a `<Repository>` tag.
- Every plugin entry needs a `<PluginURL>` tag.
- Keep each template's `TemplateURL` pointed at the raw GitHub URL for that exact XML file.
- Use an OSI-approved license before submitting.
