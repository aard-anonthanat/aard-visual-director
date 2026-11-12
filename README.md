# AARD Visual Director

**An open, platform-independent Agent Skill for creative image direction and prompt engineering.**

AARD Visual Director helps compatible AI agents develop original visual concepts, art-direct images, design fashion and costumes, work with reference images, and write clear image-generation prompts.

- **Version:** 1.0.0
- **Author:** AARD Anonthanat
- **License:** MIT
- **Format:** Agent Skills (`SKILL.md`)

## What it does

- Develops distinctive image concepts across portrait, fashion, editorial, cinematic, surreal, fantasy, futuristic, historical, product, and environmental imagery.
- Builds art direction around composition, environment, palette, lighting, camera language, materials, styling, mood, and story.
- Writes copy-ready prompts, normally in English.
- Helps preserve user-specified characteristics from reference images, within the limits of the image-generation tool.
- Adapts to the image tool named by the user instead of assuming every platform uses the same syntax.

## Creative principles

1. Unexpected combinations, with visual purpose.
2. Beyond-obvious concepts instead of predictable clichés.
3. Visual storytelling and a memorable focal moment.
4. One strong artistic surprise per concept.
5. Genuine diversity across a concept set.
6. Coherent, premium art direction over random complexity.

## Default behavior

When the user asks for image ideas and does not specify a number, the skill provides **6 distinct concepts**. Each normally includes a title, a short explanation in the user's language, and a copy-ready English prompt of approximately **800–1,000 characters**. User-specified quantities and length limits take priority.

The skill does **not** generate an image unless the user explicitly asks and the host application provides an image-generation capability.

## Repository structure

```text
aard-visual-director/
├── SKILL.md
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── references/
│   ├── creative-direction.md
│   ├── prompt-engineering.md
│   └── reference-image-workflow.md
└── examples/
    ├── concept-set-example.md
    └── prompt-revision-example.md
```

## Installation

Agent Skills are portable files, but **the host application must support the Agent Skills format**. The exact installation location and activation behavior vary by tool.

### Option 1 — Download

1. Open this repository on GitHub.
2. Select **Code → Download ZIP**.
3. Extract the ZIP file.
4. Place the `aard-visual-director` folder in the skills directory used by your compatible agent.
5. Restart or refresh the agent if required by that application.

### Option 2 — Clone

```bash
git clone https://github.com/aard-anonthanat/aard-visual-director.git
```

Replace `OWNER` with the GitHub account or organization that publishes this repository. Then follow your agent's instructions for registering local skills.

### Option 3 — Manual use

If your AI tool does not support Agent Skills directly, open `SKILL.md` and paste its instructions into the tool's custom-instructions or project-instructions area, if available. Some features may need to be adapted manually.

## Usage examples

Once installed in a compatible agent, try:

- "Create six unusual 9:16 cinematic portrait concepts."
- "Design a contemporary Thai-inspired formal costume in cream, gold, and pastel green."
- "Use this reference image and preserve the subject's recognizable facial features. Change only the wardrobe and setting."
- "Rewrite this image prompt for Nano Banana in 900 characters."
- "Develop a six-scene visual sequence for a 30-second music video."

## Compatibility

This skill is platform-independent at the instruction level. It does not guarantee identical results across tools. Image generation, reference-image handling, aspect-ratio controls, and prompt limits depend on the host application and model.

## License

The skill's text and bundled documentation are released under the [MIT License](LICENSE).

The name **AARD Visual Director** and the AARD brand identifiers are project identifiers. The MIT license does not grant trademark rights or permission to imply official endorsement by the project author.

## Credits

Created by **AARD Anonthanat**.

If you build on this project, contributions and attribution are appreciated. See [CONTRIBUTING.md](CONTRIBUTING.md).
