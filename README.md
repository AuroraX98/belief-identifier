# Belief Identifier: Limiting Beliefs and Core Belief Inquiry

Belief Identifier is an MIT-licensed AI skill for ChatGPT, Claude, and Codex that helps identify limiting beliefs, core beliefs, and self-definitions through precise personal self-inquiry. It is based on teachings about beliefs, core beliefs, emotions, and thoughts from **Bashar, channeled by Darryl Anka**, and **Elan, channeled by Andrew**. It helps you examine an unwanted situation, follow the thoughts and meanings you report, and explore what you believe about yourself.

It validates your experience while keeping unverified claims about other people or external events open to examination. It asks one open question per turn and follows your answers without imposing an interpretation.

**Download:** [Installable ZIP](https://github.com/AuroraX98/belief-identifier/raw/refs/heads/main/downloads/belief-identifier.zip) · [Complete chat attachment](chatgpt/Belief-Identifier.md) · [Efficiency and investigation prompts](docs/PROMPTS.md)

After setup, start with:

> Use Belief Identifier to investigate what I don't prefer, clarify what I do prefer, and identify the beliefs behind my feelings and recurring thoughts. Ask one focused question at a time.

## How the inquiry works

The skill begins with the unwanted situation, what you would prefer, and how you feel. It skips information you have already supplied. From a specific thought, it explores the meaning you give the situation and what that meaning seems to say about you.

It checks assumptions, evidence in your own account, contradictions, and real constraints. A suggested belief remains a candidate until you confirm that it fits. Supporting beliefs and possible core beliefs stay distinct; the skill does not force every concern into a deeper explanation.

The included bank of 44 author-supplied questions is used contextually. Motivation questions compare what a belief appears to protect or provide with what you fear about responding as you would prefer. They do not presume an unconscious benefit or hidden motive.

The skill helps you explore alternative definitions you can actually believe. Here, letting go means examining a meaning, allowing feelings to be present, testing a preferred definition, and checking what you report afterward. An old thought returning is something to examine, without assuming failure.

You can request a summary table or diagram showing confirmed beliefs, tentative possibilities, supporting beliefs, possible core beliefs, and unresolved questions. The inquiry stops immediately when you ask.

## Optional visualization and sources

With your consent, the skill can offer a 3–5 minute love and white-light visualization after enough inquiry to establish its relevance. Emotional intensity should remain manageable. You can stop at any point, and the skill checks what you actually noticed afterward.

The spiritual source material comes from Bashar and Elan teachings as reproduced in the Superphysics Essassani archive. The visualization is a custom combination, not a purported exact technique from either speaker. [Source notes](belief-identifier/references/source-notes.md) link to the reviewed transmissions and record access and attribution limits.

There are no guarantees of release or healing, memory erasure, an exact emotion-to-belief mapping, or altered history. The skill avoids invented psychological diagnoses and leaves uncertain interpretations uncertain.

## Install and use in ChatGPT and Claude

These instructions were checked against official documentation on October 3, 2026. Features and organization permissions can vary. The files have been structurally validated; a live installation in each recipient's ChatGPT or Claude account has not been tested.

### ChatGPT and Codex

Standalone skills work in the ChatGPT desktop app and Codex CLI/IDE. Select skills with `@` in ChatGPT or `$` in Codex. Prefer the built-in `$skill-installer`; native folder discovery is documented at `~/.agents/skills`. See [OpenAI’s skill guide](https://learn.chatgpt.com/docs/build-skills).

Ask your desktop local assistant:

> Use the skill installer to install https://github.com/AuroraX98/belief-identifier/tree/main/belief-identifier.

For a chat setup where native installation is unavailable, [download Belief-Identifier.md](https://github.com/AuroraX98/belief-identifier/raw/refs/heads/main/chatgpt/Belief-Identifier.md), attach it to a new chat, and send:

> Read the entire attached file. Confirm you can access all of it before proceeding, then follow its instructions for this chat. If you cannot read it, say so.

This is a proposed prompt setup; account and file support varies. It is not native installation. No API setup is needed.

### Claude

Enable code execution and file creation. Open **Customize > Skills > + > + Create skill > Upload a skill**. Upload the [skill ZIP](https://github.com/AuroraX98/belief-identifier/raw/refs/heads/main/downloads/belief-identifier.zip), containing the `belief-identifier` folder. Enable it, then ask naturally: “Use Belief Identifier to help me explore this situation.” Organization controls may limit access. See [Claude’s usage guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

The ZIP keeps the complete skill folder together, following [Claude’s packaging guidance](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills).

## Package contents

The package contains:

- `README.md` and `docs/PROMPTS.md` for documentation and copy/paste prompts.
- `belief-identifier/SKILL.md` and four references: `questions.md`, `teachings.md`, `visualization.md`, and `source-notes.md`.
- `chatgpt/Belief-Identifier.md`, combining the complete skill instructions and all four references in one file.
- `belief-identifier/agents/openai.yaml`, `LICENSE`, `downloads/belief-identifier.zip`, and `downloads/SHA256SUMS`.

The entire deep-focus instruction body is embedded, with no separate dependency. The package includes instructions and references without executable code or network tools. No personal investigation transcript is included.

## License

MIT covers the original Belief Identifier instructions and the included MIT-licensed deep-focus instructions. See [LICENSE](LICENSE). Source links and summaries do not grant rights to Bashar, Elan, or Superphysics source material; their rights remain with their respective holders. This project is an independent adaptation and does not claim official endorsement.
