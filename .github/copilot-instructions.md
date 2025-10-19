# GitHub Copilot Instructions for homemade-piPhone

## Repository Overview

This repository contains the homemade piPhone project - an open-source project for making your own landline phone with a Raspberry Pi and a 3D printer.

## Project Purpose

The homemade piPhone project aims to provide documentation, designs, and code for building a functional landline phone using readily available hardware like Raspberry Pi. The project welcomes contributors and provides a collaborative environment for improving and expanding the project.

## Repository Structure

```
.
├── .github/              # GitHub configuration files
│   └── ISSUE_TEMPLATE/   # Issue templates for project contributions
├── docs/                 # Project website (GitHub Pages)
│   ├── images/           # Images and assets for the website
│   ├── index.html        # Website homepage
│   └── README.md         # Website documentation
├── README.md             # Main project README
├── LICENSE               # Project license
└── .gitignore            # Git ignore patterns (Python-focused)
```

## Technology Stack

- **Hardware**: Raspberry Pi
- **Manufacturing**: 3D printing
- **Documentation**: Markdown, HTML
- **Deployment**: GitHub Pages for documentation
- **Expected Code**: Python (based on .gitignore configuration)

## Coding Standards and Best Practices

### General Guidelines

1. **Keep it simple**: This is a maker project - prioritize clarity and accessibility over complex abstractions
2. **Document everything**: Assume contributors may be new to Raspberry Pi or Python development
3. **Hardware considerations**: Remember that code will run on Raspberry Pi hardware with specific constraints
4. **Community-focused**: Write code that is easy for the community to understand and contribute to

### Python Code (when applicable)

- Follow PEP 8 style guidelines
- Use clear, descriptive variable and function names
- Add docstrings to functions and classes
- Include comments for hardware-specific interactions
- Handle errors gracefully, especially for hardware I/O operations
- Consider Raspberry Pi resource constraints (memory, CPU)

### HTML/CSS/JavaScript (for website)

- Keep the website simple and accessible
- Ensure mobile responsiveness
- Maintain consistent styling with existing pages
- Optimize images for web delivery

### Documentation

- Use clear, beginner-friendly language
- Include images and diagrams where helpful
- Provide step-by-step instructions for hardware setup
- Document dependencies and prerequisites
- Include troubleshooting sections

## File Patterns

### Code Files
- Python files for Raspberry Pi functionality
- Hardware interface code
- Configuration files

### Documentation Files
- Markdown files for general documentation
- HTML files for the GitHub Pages website
- Image assets in `docs/images/`

### Configuration Files
- GitHub Actions workflows (if any)
- Issue templates
- Project configuration files

## Testing Guidelines

When adding code to this repository:

1. **Hardware testing**: If code interacts with hardware, document testing procedures
2. **Simulated testing**: Provide ways to test code without physical hardware when possible
3. **Unit tests**: Add unit tests for non-hardware-dependent logic
4. **Integration notes**: Document how to test complete hardware integration

## Contribution Workflow

1. Contributors can join the project by filling out the [join form](https://github.com/homemade-piPhone/homemade-piPhone/issues/new?template=join-the-project.md)
2. Use issue templates in `.github/ISSUE_TEMPLATE/` for structured contributions
3. Update documentation in the `docs/` folder for website changes
4. Follow the existing code structure and style

## Website Management

- The `docs/` folder contains the GitHub Pages website
- Website is automatically deployed from the `main` branch
- Use GitHub Codespaces for editing (recommended)
- Changes to `docs/` are reflected at https://homemade-piphone.github.io

## Important Considerations

### Hardware Context
- Code should be compatible with Raspberry Pi OS
- Consider GPIO pin interactions
- Account for audio hardware interfaces
- Think about power consumption and efficiency

### User Experience
- Many users may be makers/hobbyists, not professional developers
- Instructions should be beginner-friendly
- Provide clear error messages
- Include visual aids and diagrams

### Open Source Community
- Be welcoming to new contributors
- Maintain clear communication
- Document decisions and rationale
- Respect the project's collaborative nature

## When Making Changes

1. **Understand the context**: This is a hardware project with software components
2. **Test when possible**: Provide testing guidance even without physical hardware
3. **Document thoroughly**: Explain not just what, but why
4. **Consider the audience**: Makers and hobbyists of varying skill levels
5. **Maintain simplicity**: Don't over-engineer solutions
6. **Update docs**: Keep the website and README current with code changes

## Questions to Consider

When suggesting code or changes, think about:

- Will this work on a Raspberry Pi?
- Can users without hardware test this?
- Is this documented clearly enough for beginners?
- Does this fit the project's maker/hobbyist focus?
- Are there any hardware safety considerations?

## Additional Resources

- [Project Website](https://homemade-piphone.github.io)
- [Contributors](https://github.com/homemade-piPhone/homemade-piPhone/graphs/contributors)
- [GitHub Pages Settings](https://github.com/homemade-piPhone/homemade-piPhone/settings/pages)
- [Actions Monitoring](https://github.com/homemade-piPhone/homemade-piPhone/actions)
