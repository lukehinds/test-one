# test-two

Contains:
- GitHub Action `.github/workflows/test.yml`
- Basic Dependabot configuration `.github/dependabot.yml`
```yaml
version: 2
updates:
  - package-ecosystem: "npm"
    directory: "/"
    schedule:
      interval: "weekly"
```

Result should be:
- No changes
