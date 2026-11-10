# Gemini DemoLab

A library of creative, frontend, and experimental agent skills from the Gemini team.

## About

[Skills](https://agentskills.io/) are a lightweight, open technique for giving
your coding agent reusable craft, design direction, and workflow guidance right
when a task needs them - without bloating every prompt.

This repository hosts skills built and tested by the Gemini team for designing
and building standout apps, web interfaces, and interactive demos.

## Skills in this repo

| Skill | Description |
| :--- | :--- |
| [`gemini-frontend-design`](skills/gemini-frontend-design) | Design and build polished websites and web apps tailored to the brief. Covers opening screen format, layout, color, typography, custom imagery, copy, and motion when creating or redesigning web interfaces. |

### Performance

- **`gemini-frontend-design`**: Every model has its own unique design quirks;
  this skill has been drafted to get the best out of Gemini 4 models for
  frontend design. Our evaluations found that users prefer frontend designs
  generated with this skill over frontend designs with no skills 67% of the
  time, and 75% of the time against popular third-party frontend design skills.

## Installation

You can install individual skills or the full DemoLab plugin across your
preferred AI coding assistants and package managers:

### Using [Vercel skills CLI](https://skills.sh)

```sh
# Install a specific skill (recommended)
npx skills add google-gemini/demolab --skill gemini-frontend-design

# Interactively browse and install skills
npx skills add google-gemini/demolab --list
```

### Using [Context7 skills CLI](https://context7.com)

```sh
# Install a specific skill (recommended)
npx ctx7 skills install /google-gemini/demolab gemini-frontend-design

# Interactively browse and install skills
npx ctx7 skills install /google-gemini/demolab
```

### Antigravity

Install through the AGY CLI:

```sh
agy plugin install https://github.com/google-gemini/demolab
```

### Claude Code

```sh
# Register the marketplace
/plugin marketplace add google-gemini/demolab

# Install the plugin
/plugin install demolab@demolab
```

### Cursor

Install via the editor command:

```text
/add-plugin google-gemini/demolab
```

### OpenAI Codex

```sh
# Add the marketplace source
codex plugin marketplace add https://github.com/google-gemini/demolab

# Install the plugin
codex plugin add demolab@demolab
```

## More info

Looking for skills covering the Gemini API, Live API, and official SDKs? Check
out [google-gemini/gemini-skills](https://github.com/google-gemini/gemini-skills)
and the [coding agents setup guide](https://aistudio.google.com/docs/coding-agents.md).

## License

This repository is licensed under the [Apache 2.0 License](LICENSE).

## Disclaimer

This is not an officially supported Google product. This project is not
eligible for the [Google Open Source Software Vulnerability Rewards
Program](https://bughunters.google.com/open-source-security).
