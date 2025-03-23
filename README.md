# Marp Presentation

This repository contains a presentation created using [Marp](https://marp.app/), a Markdown presentation ecosystem.

## Structure

- `slides/` - Contains the presentation files
  - `Slides.md` - Main presentation file (Markdown)
  - `themes/` - Custom CSS themes for the presentation
  - `img/` - Images used in the presentation

## How to Use

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Marp CLI](https://github.com/marp-team/marp-cli)

### Installation

1. Clone this repository
2. Install Marp CLI globally:
   ```bash
   npm install -g @marp-team/marp-cli
   ```

### Viewing the Presentation

To preview the presentation in your browser:

```bash
marp -s slides/Slides.md
```

### Exporting the Presentation

To export the presentation to PDF:

```bash
marp --pdf slides/Slides.md
```

To export the presentation to PowerPoint:

```bash
marp --pptx slides/Slides.md
```

## Customization

You can customize the presentation by editing the Markdown file (`slides/Slides.md`) and the CSS theme files in the `slides/themes` directory.

## License

This project is licensed under the terms of the included LICENSE file. 