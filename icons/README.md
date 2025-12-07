# OSSAfrica Icons

This directory contains icon sets and individual icons for use in applications, websites, and documentation.

## Icon Categories

- **Application Icons**: Icons for software applications
- **Web Icons**: Icons for website navigation and UI
- **Social Icons**: Social media platform icons
- **Action Icons**: Icons representing actions (download, share, etc.)
- **Status Icons**: Icons for states (success, error, warning, info)

## Standard Sizes

Provide icons in multiple sizes:
- 16x16 px (small, UI elements)
- 24x24 px (standard UI)
- 32x32 px (medium)
- 48x48 px (large)
- 64x64 px (extra large)
- 128x128 px (app icons)
- 256x256 px (high-res)
- 512x512 px (very high-res)

## Format Requirements

### Vector (Required)
- **SVG**: Scalable vector format
  - Use simple paths
  - Optimize for small file size
  - Remove unnecessary metadata

### Raster (Recommended)
- **PNG**: With transparency
  - Provide multiple sizes
  - Use PNG-8 for simple icons
  - Use PNG-24 for complex icons with transparency

## Design Guidelines

### Visual Style
- **Consistency**: Maintain consistent style across icon set
- **Simplicity**: Clear, recognizable shapes at small sizes
- **Alignment**: Align to pixel grid for crisp rendering
- **Weight**: Consistent stroke width (typically 2px at 24x24)

### Color
- Provide icons in multiple color variations:
  - Monochrome (black)
  - Monochrome (white)
  - Primary brand color
  - Full color (when appropriate)

### Grid and Spacing
- Use a consistent grid system (e.g., 24x24 with 2px padding)
- Maintain optical balance
- Ensure icons appear same size even with different shapes

## File Structure

```
icons/
├── app-icons/       # Application icons
├── ui-icons/        # User interface icons
├── social-icons/    # Social media icons
└── sets/           # Complete icon sets
    └── set-name/
        ├── svg/
        └── png/
            ├── 16x16/
            ├── 24x24/
            ├── 32x32/
            └── 48x48/
```

## File Naming Convention

```
[category]-[name]-[size].[ext]

Examples:
- ui-download-24x24.svg
- social-twitter-32x32.png
- app-icon-ossafrica-128x128.png
```

## SVG Optimization

Optimize SVG files using tools like SVGO:
```bash
svgo input.svg -o output.svg
```

Remove unnecessary elements:
- Comments
- Hidden layers
- Editor-specific data
- Excessive decimal precision

## Contributing

When contributing icons:
1. Follow the design guidelines for consistency
2. Provide both SVG and PNG formats
3. Include multiple sizes (at minimum: 24x24, 48x48)
4. Optimize file size
5. Test rendering at smallest size
6. Include source files (AI, Sketch, Figma)
7. Document any special usage considerations

## Icon Sets

When contributing a complete icon set:
1. Ensure all icons follow same style
2. Provide comprehensive size range
3. Include documentation and usage guide
4. Provide examples of icons in use
5. Include license information
