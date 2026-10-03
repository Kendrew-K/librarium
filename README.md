# Librarium

Librarium teaches the purpose, architecture, component connections, and concrete flows of any software project, including inherited projects. The learner chooses the starting point, pace, depth, and next topic. Code explanations are available on request. Visuals appear only when explicitly requested. There are no required quizzes, exercises, checks, or foundations.

## Files

- [Canonical skill](skills/librarium/SKILL.md)
- [Requested visuals and optional illustrations](skills/librarium/references/visuals.md)
- [Teaching examples](skills/librarium/references/examples.md)
- [Validation and provenance](docs/validation/librarium.md)
- [Approved design](docs/superpowers/specs/2026-10-03-librarium-design.md) and [implementation plan](docs/superpowers/plans/2026-10-03-librarium.md)

## Setup

The source of truth is `skills/librarium/`. Copy the entire folder, including references, into a host's discovery directory; do not maintain different teaching instructions for each host. After source updates, refresh installed copies. Install a copy using the locations below.

| Host | Personal installation | Project installation | Explicit invocation |
| --- | --- | --- | --- |
| Codex | `~/.agents/skills/librarium/` | `<project>/.agents/skills/librarium/` | `$librarium Teach me this project` |
| Claude Code | `~/.claude/skills/librarium/` | `<project>/.claude/skills/librarium/` | `/librarium Teach me this project` |

On Windows, `~` means your user profile directory. Choose one discovery scope per host to avoid duplicate names. Open the target project in the host, confirm Librarium is available in its skill selector, and start a new session if discovery has not refreshed. Personal installation is useful for teaching several existing projects. The plain `skills/` source folder here is a delivery location, not an assertion of automatic host discovery.

These locations and invocation forms were checked against [official Codex skill guidance](https://learn.chatgpt.com/docs/build-skills) and [official Claude Code skill guidance](https://code.claude.com/docs/en/skills) on October 3, 2026. Codex also supports explicit skill references using `$`; the official [skill creation guide](https://developers.openai.com/plugins/build/skills) demonstrates that syntax. Actual discovery and invocation of this package have not been tested in either host.

Claude Code is the verified Claude setup target. Local personal skills do not automatically become available in Claude Cowork or cloud sessions; consult the linked Claude guidance for account-enabled skills. No cloud upload is included here. `learn` and `teach-me` are not installed aliases.

Without installation, ask a file-capable host: “Read `<absolute path>/skills/librarium/SKILL.md` and use it to teach me the project at `<project path>`.” This is a request to read instructions, not a registered slash command.

## Starting a lesson

“I know basic Python and inherited this project. Use Librarium to explain its architecture. Start with how data enters the system.”

“Skip the overview; explain the queue worker. Go deeper into code when I ask.”

“Draw the request flow.” This explicitly requests a visual; ordinary teaching stays in text.

## Limits

Teaching is read-only unless a separate request authorizes changes. The skill supplies instructions, not an application, runtime, plugin, or image generator. Optional illustration tools must exist in the active host. It does not verify production behavior from source alone. The skill is original Librarium content; optional third-party capabilities are not bundled. See validation for tested scope and limitations.

## License

Original Librarium content is available under the [MIT License](LICENSE). Optional third-party skills and tools retain their own licenses.
