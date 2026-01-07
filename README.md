# Vibe Pipeline Repository

This repo hosts the configuration for the **Vibe Pipeline Agent**.

## Structure

All logic is contained in the hidden folder: **`.vibe/`**

```
.vibe/
├── instructions.md        # The Master Rules (Single Source of Truth)
├── agents/
│   └── pipeline.agent.md  # The Agent definition
└── templates/             # Starter templates for new projects
```

## How to use in your project

1. **Copy the `.vibe` folder** into the root of your target project.

   ```bash
   cp -r /path/to/vibe-pipeline/.vibe ./
   ```

2. **Run your AI Agent** (Copilot, Cursor, etc.):
   > "Read `.vibe/instructions.md` and start the Pipeline Agent."

That's it. The agent will read the instructions and follow the **BA -> DEV -> QC** workflow automatically.
