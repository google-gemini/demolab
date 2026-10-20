# Gemini DemoLab

Skills, prompts, and scripts used to build and reproduce Gemini model demos.

## Installation

You can browse and install skills from this repository across your preferred coding agents (**Gemini CLI**, **Antigravity**, **Claude Code**, **Cursor**, **Codex**, **OpenCode**, and more) using the [skills CLI](https://github.com/vercel-labs/skills):

```bash
# Interactively browse and install skills
npx skills add google-gemini/demolab

# List all available skills in this repository
npx skills add google-gemini/demolab --list

# Install a specific skill
npx skills add google-gemini/demolab --skill <skill-name>

# Install a specific skill for a specific agent (e.g., antigravity, gemini-cli, claude-code, cursor)
npx skills add google-gemini/demolab --skill <skill-name> -a antigravity

# Use a skill directly without installing
npx skills use google-gemini/demolab@<skill-name>
```

## Repository Structure

Skills live under [`skills/`](skills/) so they are automatically discovered by `npx skills`:

```text
skills/
  └── <skill-name>/
      ├── SKILL.md      # Required: YAML frontmatter (name, description) + agent instructions
      ├── README.md     # Optional: Link to demo/post, exact prompt used, and steps to reproduce
      ├── references/   # Optional: Reference docs, schemas, or prompt assets
      └── scripts/      # Optional: Helper scripts or standalone demo code
```

## Contributing

All additions and changes must be submitted via Pull Request and receive peer review before merging. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines and the required submission checklist.

## License

This repository is licensed under the [Apache 2.0 License](LICENSE).

## Disclaimer

This is not an officially supported Google product. This project is not eligible for the [Google Open Source Software Vulnerability Rewards Program](https://bughunters.google.com/open-source-security).
