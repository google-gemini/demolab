# How to Contribute

We'd love to accept your patches, demos, skills, and contributions to this project.

## Before You Begin

### Sign our Contributor License Agreement

Contributions to this project must be accompanied by a [Contributor License Agreement](https://cla.developers.google.com/about) (CLA). You (or your employer) retain the copyright to your contribution; this simply gives us permission to use and redistribute your contributions as part of the project.

If you or your current employer have already signed the Google CLA (even if it was for a different project), you probably don't need to do it again.

Visit <https://cla.developers.google.com/> to see your current agreements or to sign a new one.

### Review our Community Guidelines

This project follows [Google's Open Source Community Guidelines](https://opensource.google/conduct/).

## Adding a Demo Skill

1. Create a new directory under `skills/<skill-name>/` (or run `npx skills init skills/<skill-name>`).
2. Add a `SKILL.md` with required `name` and `description` YAML frontmatter so it can be discovered and installed via [`npx skills`](https://github.com/vercel-labs/skills):
   ```markdown
   ---
   name: my-demo-skill
   description: Brief description of what this skill does and when to use it.
   ---

   # My Demo Skill

   Instructions for the agent to follow when this skill is activated.
   ```
3. *(Optional)* Add a `README.md` inside `skills/<skill-name>/` with links to the demo post/video, the exact prompt used, and steps to reproduce, and place any helper scripts inside `skills/<skill-name>/scripts/`.

## Contribution Process

### Code Reviews

All submissions, including submissions by project members, require a pull request and at least one approving review before merging. Consult [GitHub Help](https://help.github.com/articles/about-pull-requests/) for more information on using pull requests.

### Submission Checklist

Before opening a pull request, verify that your submission meets these requirements:

1. **Google Copyright Header**: Include the standard Apache 2.0 copyright header (`Copyright 2026 Google LLC`, `SPDX-License-Identifier: Apache-2.0`) at the top of all source code and script files.
2. **Public APIs Only**: Use only publicly available Gemini APIs and services.
3. **No Secrets or Credentials**: Never commit API keys, `.env` files, or credentials.
4. **No Internal References**: Do not include internal links, bug references, or internal hostnames in code, comments, prompts, or documentation.
