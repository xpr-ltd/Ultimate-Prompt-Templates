# Art Style Prompt Templates & Visual Standards 🎨

This directory contains visual style standards and system instructions designed to customize image generation models (such as Midjourney, DALL-E 3, Stable Diffusion, or custom GPT/Gemini image generators) for specialized illustration styles.

Each subfolder contains specific guidelines, rules, or system instructions to maintain stylistic consistency across various projects.

---

## 📂 Subdirectory Overview

```text
artstyle/
├── character_illustrator/       # Flat vector biblical character illustrations
│   ├── flat_vector_biblical.md  # Detailed style guide
│   ├── instructions.txt         # System prompt for image generation
│   └── sample_images/           # Visual reference assets
│
├── educational_illustrator/     # Story-driven digital illustrations for children (8-14)
│   ├── mordern_narrative.md     # Primary narrative style standard
│   └── accent_doodle_clean.md   # Supporting doodle/clean sketch standard
│
└── minimalistic_3d_illustrator/ # Clean, premium product-style 3D visuals
    └── instructions.txt         # System prompt for 3D visual creation
```

---

## 🛠️ Detailed Style Breakdown

### 1. [Character Illustrator](./character_illustrator)
Designed to generate high-quality biblical character illustrations with a cohesive, editorial look suitable for educational games, Bible charades, flashcards, and animations.
*   **[flat_vector_biblical.md](./character_illustrator/flat_vector_biblical.md)**: Defines the visual standard including geometric anatomy, subtle chibi-influenced proportions, minimal facial features, a muted earth-tone color palette, and framing constraints.
*   **[instructions.txt](./character_illustrator/instructions.txt)**: A system prompt that instructs an image generator to strictly follow the flat vector biblical style, using local sample images as primary visual references for proportions and rendering.

### 2. [Educational Illustrator](./educational_illustrator)
A dual-style system designed for educational books and adventure media targeted at children ages **8–14**.
*   **[mordern_narrative.md](./educational_illustrator/mordern_narrative.md)**: Defines the primary storybook illustration style—warm, optimistic, culturally grounded, future-facing, and semi-flat with soft cinematic lighting.
*   **[accent_doodle_clean_sketch.md](./educational_illustrator/accent_doodle_clean_sketch.md)**: Defines the companion doodle style used for reflection notes, activity margins, and quick humorous visual metaphors to keep the content engaging.

### 3. [Minimalistic 3D Illustrator](./minimalistic_3d_illustrator)
Optimized for premium, contemporary product-style 3D visuals.
*   **[instructions.txt](./minimalistic_3d_illustrator/instructions.txt)**: Instructs the model to generate elegant, uncluttered 3D shapes resting on a horizontal reflective white tabletop surface with soft studio lighting, gentle ambient occlusion shadows, and extensive negative space.

---

## 🚀 Setup & Usage Instructions

1.  **Read the Style Standards**: Review the `.md` style guide files in each folder to understand the precise design language, constraints, and prohibited elements.
2.  **Configure System Prompts**: For folders with `instructions.txt`, copy the file contents and paste them into the system prompt or developer instructions box of your custom image generation assistant.
3.  **Provide Image References**: Where applicable (such as in `character_illustrator`), ensure your generation pipeline or model has access to the sample reference images for exact visual alignment.
