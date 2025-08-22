# /init command

The `/init` command bootstraps a `GEMINI.md` file for your project. When invoked, the command analyzes the current directory and creates a tailored instruction file that the Gemini agent will use as context.

## Usage

1. Run Gemini CLI in the root of your project.
2. At the prompt, type `/init`.
3. If no `GEMINI.md` exists, the CLI creates one and asks Gemini to inspect the project and populate the file.
4. Review the generated content and commit the file to version control.

If a `GEMINI.md` already exists, the command prints an informational message and makes no changes.

## Example

```bash
gemini
> /init
```

The CLI will create `GEMINI.md` and populate it using an AI-generated analysis of the project. Treat the result as a starting point—edit the file as needed to reflect your project's conventions.
