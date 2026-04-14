# Changelog

## v1.1.9 (2026-04)

### Bug Fixes
- Fixed character fade-in overlapping the previous conversation for a brief moment when clicking "New Chat" from inside an active chat

## v1.1.8 (2026-04)

### Bug Fixes
- Fixed character animation freezing when returning to the tab after a long idle period and starting a new chat

## v1.1.7 (2026-04)

### Changes
- Bundled JetBrains Mono font locally (removed Google Fonts CDN dependency)
- Extension now renders mono-spaced UI labels offline and no longer pings Google Fonts at runtime
- Included SIL Open Font License 1.1 for the bundled font (`assets/fonts/OFL.txt`)

## v1.1.6 (2026-04)

### Bug Fixes
- Fixed Tactical_Input label, scroll-to-bottom button, and prompt indicator (`>_`) disappearing when the input area is re-created during SPA transitions
- Fixed loading dots intermittently not appearing on the first message of a new chat due to stale chat-history observer reference
- Cleaned up accumulated scroll listeners and ResizeObservers that were leaking on repeated input area re-creation

## v1.1.5 (2026-04)

### Bug Fixes
- Fixed character appearing on Notebook pages and overlapping with notebook title — character now only displays on the main chat page (`/app`)
- Fixed unnecessary video playback when returning to a tab on non-chat pages

## v1.1.4 (2026-04)

### Bug Fixes
- Fixed injected header decorations (operator name, cyan bars, dots, ticket, persons, gray block) overlapping with the model selector and right-side icons on narrow screens (≤959px)

## v1.1.3 (2026-04)

### Bug Fixes
- Fixed cursor overlapping with placeholder text in input field
- Fixed 1px gap between character and input field

## v1.1.2 (2026-04)

### Bug Fixes
- Fixed character appearing on non-chat pages (My Stuff, etc.) — reported by [@Dotori0309](https://github.com/Dotori0309)

## v1.1.1 (2026-04)

### Bug Fixes
- Fixed character not appearing intermittently on new chat

## v1.1.0 (2026-04)

### New Features
- Chen idle character animation on new chat screen (enter + idle loop)
- Open Gemini tab when clicking the extension icon
- Character auto-scales and hides based on viewport size
- Character hidden on mobile view (960px or below)

### Bug Fixes
- Fixed user avatar clipping when sidebar/canvas is open
- Fixed character flickering on initial load
- Fixed character position/playback bugs on chat transitions

## v1.0.2 (2026-03)

### Changes
- Improved extension description
- Removed hardcoded Korean placeholder (now follows browser language)

### Bug Fixes
- Fixed user avatar position on messages with image attachments

## v1.0.1 (2026-03)

### New Features
- Multi-language support (English / Korean)
- Scroll-to-bottom button
- User avatar with smooth transitions
- Responsive layout for mobile
- Endfield-style loading dot animation

### Changes
- New app icon (Chen face, circular)

### Bug Fixes
- Various UI fixes (toolbar icons, prompt indicator, header layout, etc.)

## v1.0.0 (2026-03)

### Initial Release
- Arknights: Endfield theme for Google Gemini
- Dark mode enforcement
- Operator Chen header styling
- Messenger-style chat UI (bubbles, tails, avatars)
- CRT scanline overlay
- Tactical UI labels
