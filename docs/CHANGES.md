## v0.1.1

- CI: adopt the canonical BLU-pattern release workflow (tag-vs-TOC version validation, per-version changelog extraction, dev/alpha-branch channels).
- Media: standardized to `media/` folder (from `images/`).
- Minimap icon: consistent pattern across RGX Mods (WHITE8X8 backdrop + TempPortraitAlphaMaskSmall + MiniMap-TrackingBorder overlay).

## v0.1.0

- Updated for retail Midnight with a current retail ToC and Traveler's Log naming.
- Reworked activity row hooks to use ScrollBox acquired-frame callbacks so recycled rows keep their progress bars while scrolling.
- Simplified progress tracking to use live requirement text parsing plus requirement completion fallback instead of the old override table.
- Added a draggable minimap icon that opens the Traveler's Log, supports Ctrl+Right-click hide, and responds to `/etl`, `/etl icon on`, `/etl icon off`, `/etl status`, and `/etl help`.
