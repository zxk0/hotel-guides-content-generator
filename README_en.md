# Hotel Guides Content Generator

> A WorkBuddy skill for automatically generating hotel experience blog posts — smart titles, structured content, tags, photo analysis, and beautiful HTML output.

[English](README_en.md) | [中文](README.md)

---

## Features

- **Smart Title Generation** — Overview, pain point, suspense, personalized styles
- **Structured Writing** — Overview → Room → Dining → Facilities → Memorable Moments
- **Auto Tag Matching** — Precise combinations to boost visibility
- **Photo Intelligence** — Analyze user photos, auto-generate precise descriptions
- **Dual Format Output** — `.md` plain text + `.html` illustrated version (open in browser/share directly)

## HTML Output

The generated HTML includes:

- 🎨 **Dark theme + gold accents**, matching upscale hotel aesthetics
- 📷 **Card-style image display** with rounded corners, shadows, and hover effects
- ⭐ **Prominent rating card** with numeric score + star display
- 🏷️ **Tag wall**, rounded tag cloud
- 📱 **Responsive layout**, perfect mobile adaptation

## Quick Start

### Method 1: Direct Generation (No Photos)

```
Generate a hotel guide about [topic]
```

### Method 2: Provide Photo Directory (Recommended)

```
Photos are in D:\WaldorfPhotos, help me generate a guide for Waldorf Astoria
```

> 💡 Put hotel photos in a folder with the naming convention below, and AI will auto-recognize and embed them in the right sections.

### Photo File Naming Convention

| Filename Keyword | Maps To |
|-----------------|---------|
| 外观 / building / facade | Hotel exterior |
| 大堂 / lobby | Hotel lobby |
| 客房 / room / overall | Room overall |
| 局部 / detail / closeup | Room details |
| 卫生间 / bathroom | Bathroom |
| 餐厅 / breakfast / HappyHour | Dining |
| 健身房 / pool / facilities | Facilities |
| 难忘瞬间 | Memorable moments |

### Method 3: Specify Style

```
Write content in [hotel experience/hotel guide/hotel review] style about [topic]
```

## Output File Structure

```
workspace/
├── [Hotel Name] Hotel Guide.html    ← Open directly in browser
├── [Hotel Name] Hotel Guide.md      ← Plain text editable version
└── images/                          ← Photo copies
    ├── hotel-exterior-photo.jpeg
    ├── hotel-lobby-photo.jpeg
    └── ...
```

## Tech Stack

- WorkBuddy Skill Framework
- HTML5 + CSS3 (responsive design)
- Image multimodal recognition

## Version History

| Version | Date | Description |
|---------|------|-------------|
| v1.2.0 | 2026-04-24 | Added photo directory workflow, dual-format output |
| v1.1.0 | 2026-04-24 | Added HTML illustrated output |
| v1.0.0 | 2026-04-23 | Initial release |

## Notes

1. **Provide photos via folder path**, not drag-and-drop in chat
2. Recommended photo resolution 1080p+, file size under 10MB
3. AI-generated content should be reviewed and personalized before publishing
4. Avoid sensitive words ("most", "first", prices, etc.)

## Disclaimer

This tool is for content creation assistance only. Please review and personalize AI-generated content before publishing.
