# Awesome Cursor Rules

A collection of baseline Cursor AI rules for consistent development practices across projects. These rules provide generic standards for code quality, commit practices, and development workflows.

## Installation

### As a Git Submodule

Add these rules to your project as a git submodule in the `.cursor/rules` directory:

```bash
# Add the submodule
git submodule add https://github.com/queen-of-code/awesome-cursor.git .cursor/rules

# Commit the submodule
git add .gitmodules .cursor/rules
git commit -m "Add awesome-cursor rules as submodule"
```

### For New Contributors

When cloning a repository that uses these rules, initialize the submodules:

```bash
git submodule update --init --recursive
```

## Updating Rules

To update to the latest version of the rules:

```bash
# Update the submodule to the latest version
git submodule update --remote .cursor/rules

# Commit the update
git add .cursor/rules
git commit -m "Update cursor rules to latest version"
```

## What's Included

This repository contains baseline Cursor AI rules (`.mdc` files) that establish consistent patterns for:

- Development workflows
- Code quality standards  
- Commit and branching practices
- Success criteria definitions

## Usage

Once installed as a submodule, Cursor AI will automatically detect and apply the rules from the `.cursor/rules` directory in your project.

## Contributing

To contribute new rules or improve existing ones, please open a pull request with your proposed changes.

## License

MIT License - see [LICENSE](LICENSE) file for details.