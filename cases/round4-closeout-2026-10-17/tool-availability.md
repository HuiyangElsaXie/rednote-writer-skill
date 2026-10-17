# Tool availability and loaded rules

Actual executed tools: functions.exec, tools.exec_command, PowerShell local file reads, and {PYTHON} -X utf8 for UTF-8 reads, hashing, assertions and saves.

Loaded rule SHA-256 hashes (computed from actual bytes):

- skills/rednote-writer/SKILL.md: bddfcc73ef03dd77495c4ca42783a96b53884722d6d387ecf4fa28afc58947a5
- skills/rednote-writer/references/research-and-images.md: 685a8a5fa590dfd0c3cf975c5d8a22f785b0dac0e939a5b35b80e2809fcf4c06

Both matched the task case.json. Read only the designated brief.md, case.json, entry and its relevant reference. Optional example was not read.

Search/web/browser, image reading/generation/editing, connectors/accounts, paid APIs, business tools, installations and Git operations were not executed. Some such tools are exposed by the host, but this task explicitly prohibits their use; no availability probing or external access was attempted. Local editable text delivery was available and used. No images were requested or produced. No tool failure blocked completion; initial PowerShell Chinese display damage was resolved by UTF-8 Python with ASCII-escaped JSON.

This is a reconstructed execution description, not native telemetry. The first saved raw-response.md is the submitted deliverable. No post-submission self-review or repair was performed.
