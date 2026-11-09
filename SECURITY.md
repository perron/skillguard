# Security Policy

This project is a small local command-line tool. It does not phone home and does not require an API key.

## Reporting a vulnerability

Please open a [GitHub issue](https://github.com/perron/skillguard/issues) and mention that it is a security report. Do not include secrets, tokens, or private file contents in the issue.

If the report includes a working exploit against this tool, describe the impact and a minimal reproduction without pasting live credentials.

## Notes for this tool

skillguard never executes the skill it is scanning. It is a static pattern scanner, not a sandbox or a complete audit. A clean verdict is not a guarantee that a skill is safe. It skips common dependency directories and directory symlinks, and it caps the size of files it will read.

## Supported versions

The `master` branch and the latest tagged release, when one exists, are supported.
