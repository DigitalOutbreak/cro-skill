# Walk the visitor's task

Start on a deep link. Can a first-time visitor identify the organization, page, next action and path back? Use familiar link styling, descriptive destination labels, visible current location and headings that work when read alone. Label a menu opener and expose its expanded state. Keep essential facts reachable without hover.

| Observed difficulty | Intervention | Verify |
| --- | --- | --- |
| Visitors guess which department handles their problem | Group options by recognizable task. Offer “I'm unsure” when routing can happen later. | Ask someone to locate a repair without naming the menu item. Observe first click and recovery. |
| Adjacent actions cause thumb slips | Increase the hit area and separation. Aim for 44×44 CSS px on frequent touch actions. | Tap near edges on a narrow viewport. Inspect the actual interactive element. |
| An unfamiliar format causes re-entry | Accept equivalent phone formats, normalize on submission and preserve input. | Paste a formatted number and retry after a server error. |
| The interface appears frozen | Show pending feedback, prevent duplicate submissions and keep a recovery path. | Throttle the response, double tap and simulate failure. |
| Readers praise appearance but miss the task | Ask them to complete a realistic task without coaching. | Record hesitation, errors and completion independently from satisfaction. |

### Accessibility acceptance checks

- Use native links for destinations, buttons for actions, associated labels and appropriate autocomplete. Provide text alternatives for meaningful images. Inspect landmark and heading order with images disabled.
- Complete the critical path by keyboard alone. Check visible focus, skip navigation, modal containment and return focus, Escape where appropriate, and sticky UI obscuring a focused control. Read field names, errors and success with assistive technology where available.
- Use WCAG AA contrast targets of 4.5:1 for ordinary text and 3:1 for large text. Check required control boundaries and informative graphics at 3:1 where applicable. Check focus and errors independently. Never identify an error by color alone.
- Test text resized to 200% and a 320 CSS px content width. Inspect horizontal scrolling, wrapping and clipped input. Respect reduced motion. Check that the mobile keyboard does not cover submit or error feedback.
- Pair automated checks with manual task completion. State the sampled states and any assistive technology checks still outstanding.

### Performance acceptance checks

Compare the same URL, device profile and cache state before and after. For a slow hero, inspect request discovery, transfer size and render delay before changing the asset. Supply responsive image sources, reserve space, avoid lazy-loading the LCP image and defer below-fold media. Trace main-thread work if inputs lag. Load optional widgets after critical content, preserving call attribution. Use field p75 where available, segmented by device. Good targets are LCP ≤2.5 s, INP ≤200 ms and CLS ≤0.1. A lab run is diagnostic. Field success requires real visitor measurements.
