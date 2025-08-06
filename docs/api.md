# TS-Assets API Documentation

<!-- GitHub Source: TS-Assets -->

> 📝 **Source:** [View this file on GitHub](https://github.com/zadie-studio/TS-Assets/blob/main/docs/api.md) • TS-Assets


## Overview

TS-Assets provides programmatic access to brand assets through a simple API structure.

## Asset URLs

All assets are accessible via direct URLs following this pattern:

```
https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/[filename]
```

## Asset Categories

### Logos

#### Primary Logos
- `TS-logo-Dark.svg` - Dark theme logo
- `TS-logo-Light.svg` - Light theme logo
- `TS-logo-Mid.svg` - Medium theme logo
- `TS-logo-White.svg` - White logo for dark backgrounds

#### Logo Marks
- `TS-mark-Dark.svg` - Dark theme logo mark
- `TS-mark-Light.svg` - Light theme logo mark
- `TS-mark-Mid.svg` - Medium theme logo mark
- `TS-mark-White.svg` - White logo mark

#### Thumbnails
- `TS-Thumbnail-dark.svg` - Dark thumbnail
- `TS-Thumbnail-light.svg` - Light thumbnail

### Icons

#### Application Icons
- `TS-icon-round.png` - Round application icon
- Various app store icons and platform-specific assets

### Images

#### Brand Assets
- `TS-Brand-Colors.png` - Brand color palette
- Various logo versions in different sizes and formats

## Usage Examples

### Web Applications

```html
<!-- Dark theme logo -->
<img src="https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Dark.svg" alt="TS Logo">

<!-- Light theme logo -->
<img src="https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Light.svg" alt="TS Logo">
```

### React Applications

```jsx
import React from 'react';

const Logo = ({ theme = 'dark' }) => {
  const logoSrc = theme === 'dark' 
    ? 'https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Dark.svg'
    : 'https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Light.svg';
    
  return <img src={logoSrc} alt="TS Logo" />;
};
```

### CSS Background Images

```css
.ts-logo-dark {
  background-image: url('https://raw.githubusercontent.com/zadie-studio/TS-Assets/main/images/TS-logo-Dark.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
```

## Best Practices

1. **Use SVG when possible** - Scalable and smaller file sizes
2. **Choose appropriate theme** - Match your application's theme
3. **Optimize for performance** - Consider caching strategies
4. **Maintain aspect ratios** - Don't stretch or distort logos

## Version Control

Assets are versioned through Git. To reference a specific version:

```
https://raw.githubusercontent.com/zadie-studio/TS-Assets/[commit-hash]/images/[filename]
```

## Updates

Assets are updated through the TS-Assets repository. Changes are automatically propagated to all consuming applications through the documentation automation system. 