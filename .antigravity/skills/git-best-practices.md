---
name: Git Best Practices
description: Guidelines for version control and commit messages
---

# Git Best Practices

## Commit Messages

### Structure
```text
<type>: <subject>

<body>

<footer>
```

### Rules
1. **Separate subject from body with a blank line.**
2. **Limit the subject line to 50 characters.**
3. **Capitalize the subject line.**
4. **Do not end the subject line with a period.**
5. **Use the imperative mood in the subject line.**
   - Example: "Add feature" not "Added feature" or "Adds feature"
6. **Wrap the body at 72 characters.**
7. **Use the body to explain _what_ and _why_ vs. _how_.**

### Common Types
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation
