# Research Presentation

Convert research documents into interactive slide-based presentation websites with hover tooltips.

**Single-file HTML** — no build tools, no dependencies. Just open in a browser.

## Features

- Slide-based navigation (keyboard arrows, scroll, touch swipe, click dots)
- Hover tooltips with detailed supporting text from source documents
- Staggered reveal animations
- Responsive layout (desktop + tablet)
- Multiple slide layouts: standard, thesis grid, scenario comparison, risk register

## Design: "The Research Folio"

Clean, professional aesthetic inspired by medical journals and consulting decks.

- **Light theme** with warm ivory paper texture
- **Typography:** Fraunces (serif headlines) + DM Sans (body) + JetBrains Mono (data)
- **Colors:** Teal (#0D7C66) + Coral (#D94F3B) + Gold (#C4972A)
- Fonts loaded via Google Fonts CDN

## Usage

1. Open `index.html` in any modern browser
2. Navigate with arrow keys, Space, scroll, or click dots
3. Hover on any item with `i` badge to see detailed data

## Creating Your Own Presentation

The presentation is a single HTML file. To customize:

1. Edit slide content directly in HTML
2. Each `<div class="slide">` is one slide
3. Add `data-detail="..."` attribute to any element for hover tooltips
4. Update `totalSlides` and `sectionNames` in the `<script>` section

### Slide Layouts

- **Standard** (`content-grid`): 3-column bullets + 2-column stats
- **Thesis** (`thesis-grid`): 5-column card grid for key theses
- **Scenarios** (`scenario-grid`): 3-column comparison cards
- **Risk Register**: 2-column severity cards with color coding

## Demo

The included `index.html` contains a full STEP analysis of the Russian private healthcare market (2025-2026) as an example.

## License

MIT
