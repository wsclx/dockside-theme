# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Fixed
- card-mod: keyboard focus on tiles gets a ring in the focus blue (border and 2 px outside, 3:1 on the glass). The frontend's own 1 px ring in the tile colour is nearly invisible for yellow or amber lights on light glass (1.1–1.4:1).

## [1.0.1] - 2026-11-25

### Fixed
- Menu bar with card-mod: when the page scrolls and widgets pass under the transparent bar, it now darkens and blurs them, so the white text keeps 4.5:1 (before, white text could sit on light glass).

### Added
- Smaller wallpapers (2560 × 1440) in the release for wall tablets and older phones.
- Without card-mod the menu bar blurs what lies behind it (the frontend's own `app-header-backdrop-filter`).
- card-mod: menu titles 15 px on phones; a lighter shadow for cards on settings pages.
- `rgb-card-background-color` for components that mix the card colour with transparency.
- card-mod: the empty arc of gauge cards uses the slider track colour instead of the window colour (it looked like a hole in dark mode).

### Changed
- README: install steps hidden in the Marketplace view, tips for slow tablets and bright pictures of your own, where the wallpapers come from, two more pictures.

## [1.0.0] - 2026-11-25

### Added
- First release: one theme with light and dark mode.
- Two wallpapers made for this theme, 5120 × 2880: a bay at sunset (light) and the same bay at night (dark), attached to the release; a gradient in the same colours when they are missing.
- Dashboards as a desktop: the picture behind every dashboard, cards as glass widgets with a light rim, dark edge and deep shadow, 20 px radius. Other pages as calm windows.
- Menu bar: translucent without add-ons; with card-mod fully transparent on dashboards, white 13 px text, the current view in bold.
- Text colours measured against the darkest and brightest spots of the pictures behind the glass (WCAG 2.2).
- Green switches, blue accents and focus ring, glass dialogs, system UI font, desktop size steps for titles.
- Optional card-mod rules: blur behind widgets and sidebar, bold widget titles, glass capsules behind section headings, a dock dot beside the active page.
