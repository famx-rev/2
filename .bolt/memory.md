# Project memory

## Product intent & audience

- CloudPlatform web application with dashboard-style navigation and a collapsible sidebar.
- Users need clear, persistent Famx branding across expanded and collapsed navigation states.

## Brand personality & voice

- Professional, polished, and production-oriented.
- Branding should remain recognizable and balanced in compact navigation.

## Visual design & UX direction

- Sidebar supports expanded and collapsed states.
- Expanded state displays the full Famx wordmark.
- Collapsed state should also display the full Famx wordmark at a medium, readable size rather than a single cropped “F” mark.
- The collapsed rail is approximately 68px wide; the current compact logo treatment is approximately 64px wide with reduced side padding.
- Keep the compact wordmark centered, unclipped, and visually balanced with the sidebar controls.
- Preserve the existing Tailwind/React/Lucide conventions and overall sidebar styling.
- Check the logo at the actual collapsed rail width and during sidebar transitions, including overflow and spacing around adjacent controls.

## Decisions, constraints & rationale

- Replaced the cropped “F” treatment with the full Famx wordmark in the collapsed sidebar.
- Retained the full wordmark in the expanded sidebar.
- The collapsed logo area uses minimal side padding so the full wordmark can fit at a useful medium size within the narrow rail.
- Project uses Vite + React and is maintained in StackBlitz.
- Latest reported build is clean; browser-level visual verification remains pending.

## Open questions & assumptions

- Confirm in-browser that the full compact wordmark is centered, readable, and not clipped.
- Confirm it does not crowd, shift, or overlap the navigation icons below it.
- Confirm consistent appearance across viewport sizes and expanded/collapsed transitions.
- If the wordmark still feels cramped, revisit the compact rail width or provide a dedicated compact brand asset.