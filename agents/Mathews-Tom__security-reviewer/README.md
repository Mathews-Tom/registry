# security-reviewer

OWASP Top 10 vulnerability scanner for codebases. Maps attack surfaces, traces data flows from entry points to sinks, and produces severity-ranked findings with exploit scenarios and remediation code.

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/Mathews-Tom/security-reviewer
```

## What It Can Do

- Scan codebases against OWASP Top 10 vulnerability categories
- Trace tainted data flows from user input to dangerous sinks
- Detect SQL injection, XSS, SSRF, authentication bypass, and insecure deserialization
- Generate severity-ranked findings with CVSS-style scoring
- Produce exploit scenarios demonstrating impact
- Provide remediation code snippets for each finding

## Structure

```
security-reviewer/
  agent.yaml        # Agent configuration
  SOUL.md            # Behavioral instructions and review methodology
  icon.png           # 256x256 agent icon
  banner.png         # 1200x630 agent banner
```

## Built with

Built with [gitagent](https://github.com/open-gitagent/gitagent).
