# Test Case Library Starter Pack

## Naming Convention
`<category>-<technique>-<id>`

## Required Metadata Per Test
- Test ID
- Category (prompt injection/jailbreak/data leakage/etc.)
- Risk tier (critical/high/medium/low)
- Target component (model, retrieval, tool, orchestrator)
- Language/locale
- Expected policy outcome
- Last validated date

## Starter Categories
1. Prompt injection (direct/indirect)
2. Jailbreak (single-turn/multi-turn)
3. Data leakage (PII/training-data exposure)
4. Tool misuse (agentic)
5. Memory poisoning (agentic)
6. Cross-tenant isolation checks

## Regression Policy
- Critical/high tests run on every PR
- Full suite run on release branches
- Failed tests require linked mitigation issue
