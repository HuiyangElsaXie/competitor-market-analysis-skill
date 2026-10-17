# Tool availability and loaded rules

Execution used functions.exec with tools.exec_command, Windows PowerShell, and the designated local Python executable with -X utf8. No external business tools were executed.

Loaded rule hashes (SHA-256, actual file bytes):
- `SKILL.md`: `7a559365d60c1273608dc384ce4072b313218f6104902bcdf799c9f9810845d0`
- `references/output-template.md`: `92b8ed6f47ac1b6386c62750c2aaa2b8133cc0d27a353e56aa9507d9edaf025c`

The initial PowerShell output damaged Unicode typography in SKILL.md. It was reread using the designated Python and json.dumps(..., ensure_ascii=True); no damaged text was inferred. The template was loaded through the same Python read.

Unexecuted: web/browser, connectors/accounts, paid APIs, installations, Git operations, image tools, business tools, repository examples/cases, unrelated runs/reviews and private files. No actual external availability was tested because task instructions prohibited these actions. No live vendor inspection occurred.

Ordinary pre-submission checks: compared each row to its own supplied source; separated channel from automation, fee facts from monetary amounts and total cost; checked required template sections and dates. No post-submission review or repair was performed.
