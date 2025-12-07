# Social Media Graphics

This directory contains graphics optimized for various social media platforms.

## Platform Specifications

### Twitter / X
- **Header**: 1500 x 500 px
- **Post Image**: 1200 x 675 px (16:9)
- **Card Image**: 800 x 418 px

### LinkedIn
- **Cover Photo**: 1584 x 396 px
- **Post Image**: 1200 x 627 px
- **Article Image**: 1200 x 627 px

### Facebook
- **Cover Photo**: 820 x 312 px
- **Post Image**: 1200 x 630 px
- **Event Cover**: 1920 x 1005 px

### Instagram
- **Post (Square)**: 1080 x 1080 px
- **Post (Portrait)**: 1080 x 1350 px
- **Story**: 1080 x 1920 px
- **Reels Cover**: 1080 x 1920 px

### YouTube
- **Channel Art**: 2560 x 1440 px (safe zone: 1546 x 423 px)
- **Thumbnail**: 1280 x 720 px

## Content Types

- **Profile Images**: Platform-specific profile pictures
- **Cover Photos**: Headers and banners for profiles
- **Post Templates**: Reusable templates for announcements
- **Story Templates**: Templates for stories and ephemeral content
- **Event Graphics**: Promotional graphics for events

## Design Guidelines

### General Principles
- Use platform-appropriate dimensions
- Optimize for mobile viewing (70% of users)
- High contrast for readability on small screens
- Test in both light and dark modes where applicable

### Text Considerations
- Font size: Minimum 30px for body text, 48px+ for headlines
- Keep text within safe zones (avoid edges)
- Use bold, readable fonts
- Limit text to essential information

### File Format
- **Save as**: PNG (with transparency) or JPG
- **Color Mode**: RGB
- **Resolution**: 72 PPI for web (social media standard)

## Organization

Organize files by platform and purpose:
```
social-media/
├── twitter/
│   ├── headers/
│   └── posts/
├── linkedin/
│   ├── covers/
│   └── posts/
├── facebook/
│   ├── covers/
│   └── posts/
└── instagram/
    ├── posts/
    └── stories/
```

## File Naming Convention

```
[platform]-[type]-[description]-[dimensions].[ext]

Examples:
- twitter-header-conference-2024-1500x500.png
- instagram-post-announcement-1080x1080.png
- linkedin-cover-main-1584x396.png
```

## Templates

When creating reusable templates:
- Include source files (PSD, Sketch, Figma)
- Document editable areas
- Provide usage instructions
- Include example outputs

## Contributing

When contributing social media graphics:
1. Use exact platform specifications
2. Test appearance on actual platforms
3. Optimize file size (target < 1MB)
4. Provide templates when applicable
5. Include multiple variations if useful
