# Infrastructure Terminal V4

## Design tokens

- Background: `#050807`
- Deep black: `#030504`
- Surface: `#0B1110`
- Elevated surface: `#101A16`
- Primary green: `#00FF88`
- Electric green: `#39FF14`
- Soft green: `#8AFFC1`
- White: `#F2FFF8`
- Muted text: `#8FA99B`
- Border: `#1C3B2D`

## Rendering

Visual assets use self-contained SVG primitives, native SVG animation, and system font stacks. Each animation follows its diagram: terminal command reveal and topology signals, packet paths, authentication decisions, device stages, service traces, and project-specific flows. Labels and profile metrics remain static. SVG-local reduced-motion rules hide motion layers while keeping the diagrams readable. No JavaScript, external fonts, iframes, or external stylesheets are used. Responsive scaling is handled by viewBox and Markdown image width.

## Technical boundaries

The resume is the source of truth for professional claims. Public repository contents verify the gym, yoga, and cybersecurity projects. Azure and Linux lab cards are omitted because no verified public implementation was found. Animated signals are symbolic and do not represent live telemetry, production integrations, or employer infrastructure.
