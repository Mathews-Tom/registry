# full-stack-builder

End-to-end implementation agent that takes architecture docs or feature specs and delivers production-ready code with tests, API docs, and security validation. Handles the full development lifecycle from spec to deployment-ready artifacts.

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/Mathews-Tom/full-stack-builder
```

## What It Can Do

- Scaffold full-stack applications from architecture documents or feature specifications
- Generate production-ready code with proper error handling and security patterns
- Create comprehensive test suites (unit, integration, e2e)
- Produce API documentation alongside implementation
- Validate code against security best practices
- Wire up CI/CD configuration and deployment manifests

## Structure

```
full-stack-builder/
  agent.yaml       # Agent configuration and tool definitions
  SOUL.md          # Agent personality and behavioral guidelines
  icon.png         # 256x256 agent icon
  banner.png       # 1200x630 agent banner
```

## Built with

[gitagent](https://github.com/open-gitagent/gitagent) - the open agent registry and runner.
