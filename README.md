# TS-Assets

Centralized asset management for the TS ecosystem.

## Overview

TS-Assets provides a centralized location for all brand assets, logos, icons, and images used across the TS ecosystem applications.

## Quick Start

1. **Browse Assets**: Visit the [images](./images/) directory to see all available assets
2. **Download**: Use the direct GitHub raw URLs to access assets
3. **Integration**: Reference assets in your applications using the provided URLs

## Asset Categories

### Logos

- Primary TS logos in multiple color schemes (Dark, Light, Mid, White)
- Logo marks and thumbnails
- High-resolution versions for print and digital use

### Icons

- Application icons for mobile and web platforms
- UI icons for interface elements
- Social media and platform-specific icons

### Images

- Brand color palettes and guidelines
- Marketing materials and promotional graphics
- Screenshots and mockups

## Usage

### Direct URLs

All assets are accessible via GitHub raw URLs:

```
https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/[filename]
```

### Examples

```html
<!-- Dark theme logo -->
<img src="https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Dark.svg" alt="TS Logo">

<!-- Light theme logo -->
<img src="https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Light.svg" alt="TS Logo">
```

## Documentation

For detailed documentation, see the [docs](./docs/) directory:

- [API Reference](./docs/api.md) - Programmatic access to assets
- [Deployment Guide](./docs/deployment.md) - Asset management workflow
- [README](./docs/README.md) - Comprehensive documentation

## Contributing

1. **Add Assets**: Place new assets in the `images/` directory
2. **Update Documentation**: Keep documentation current with asset changes
3. **Follow Naming**: Use consistent naming conventions
4. **Optimize**: Ensure assets are optimized for web use

## Automation

This repository is integrated with the TS-Docs automation system. Changes to documentation files will automatically:

1. Trigger validation checks
2. Update the centralized documentation site
3. Deploy changes to the live documentation

## Support

For questions about assets or the automation system:

- Check the documentation in the `docs/` directory
- Review the GitHub Actions workflow for automation details
- Contact the development team for assistance
