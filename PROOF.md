# skillguard proof

Captured 2026-11-09 13:26 PST.

Fresh-venv install: `pip install .` succeeded and `skillguard --version` printed `skillguard 0.1.1`.

Tests: 14 passed in 0.03s

## planted dangerous skill
```
verdict: DANGER
danger: prompt-override: instructions tell the agent to ignore previous or system prompts (/tmp/ai-tools-proof/skillguard/handy-helper/SKILL.md:6)
danger: exfil-host: mentions a common exfiltration or webhook host (/tmp/ai-tools-proof/skillguard/handy-helper/SKILL.md:6)
danger: secret-outbound: outbound request appears to involve a secret or an exfil host (/tmp/ai-tools-proof/skillguard/handy-helper/SKILL.md:6)
exit: 2
```

## clean skill
```
verdict: SAFE
no findings
exit: 0
```
