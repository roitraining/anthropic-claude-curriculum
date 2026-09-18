# Cloud Provider Setup Addendum (Delivery Fill-In)

This class routes Claude Code through the student organization's cloud account. **Cloud-provider routing is supported in the Claude Code CLI and IDE extensions**, not the Claude Desktop Code tab.

Duplicate this file per delivery and fill in only the provider you are teaching. Keep steps accurate to current vendor docs; link out rather than inventing IAM screenshots.

## Provider in use for this delivery

- [ ] Amazon Bedrock
- [ ] Google Vertex AI / Gemini (Vertex)
- [ ] Microsoft Foundry (Azure)

## Pre-class checklist (1 week out)

- [ ] Model access requested/approved in the org cloud
- [ ] Student identities or lab roles created with least privilege
- [ ] Quotas confirmed for classroom headcount
- [ ] Claude Code install instructions published
- [ ] Sample repo distributed (clone URL + branch naming scheme)
- [ ] Pinned model ID chosen and written below

**Pinned model ID for class:** `______________________________`

## Student setup (fill with exact commands)

### 1. Install and login prerequisites

```bash
# TODO: org-specific install/login commands
```

### 2. Environment variables / config

```bash
# TODO: exact env var names for this provider
# Example shape only: replace with real values from current docs
# export CLAUDE_CODE_USE_PROVIDER=...
```

### 3. Verify connectivity

```bash
# TODO: addendum "hello" verification command or prompt
```

**Expected success signal:** _(e.g., Claude Code responds; status shows org-cloud route)_

## Trust and governance notes (fill from current policy)

- Where prompts/completions may be logged: _(link)_
- Retention posture: _(link)_
- Who to contact for IAM errors during class: _(name/channel)_

## Classroom troubleshooting

| Symptom | Likely cause | First fix |
| :--- | :--- | :--- |
| Auth error | Wrong account / missing role | Re-run login; confirm project/subscription |
| Model not found | No access or wrong pin | Check allowlist and pinned ID |
| Quota exceeded | Classroom burst | Stagger labs; request quota |

## Related leave-behinds

- Lab 2: Refactoring and Test Generation
- Official Claude Code docs
- Official docs for the selected cloud's model access path
