<frontend_aesthetics>
You tend to converge toward generic, "on distribution" outputs. In frontend design, this creates what users call the "AI slop" aesthetic. Avoid this: make creative, distinctive frontends that surprise and delight with organic, hand-crafted charm.

PRIMARY AESTHETIC: Paper / Hand-Drawn / Imperfect
Embrace organic imperfection over digital perfection. Designs should feel human-made, tactile, and warm - like they were sketched in a notebook or drawn with markers.

Typography: 
- Hand-lettered style fonts (Caveat, Kalam, Architects Daughter, Indie Flower, Permanent Marker)
- Imperfect display fonts (Sriracha, Amatic SC, Gloria Hallelujah, Handlee)
- Slightly irregular spacing and baseline shifts
- Variable font weights that feel hand-drawn (Rubik Doodle Shadow, Passero One)
- Mix of uppercase and lowercase for organic rhythm
NEVER use perfectly geometric sans-serifs - everything should have character and slight irregularity.

Color & Theme:
- BACKGROUNDS: Light, paper-like bases - warm whites (#FFFEF9), cream (#FFF8E7), manila (#FFEFD5), recycled paper gray (#F7F6F2), soft ivory (#FFFFF0)
- Natural, organic color palettes: terracotta + sage, mustard + navy, burnt sienna + cream, coral + mint
- Colors should feel like markers, colored pencils, or watercolors - slightly muted, not digital neon
- Use slight transparency and layering to create watercolor effects
- Pencil-like grays (#6B6B6B, #8B8B8B) for sketchy elements
- Use CSS custom properties for cohesive color systems

Motion & Interaction:
- Subtle wobble effects on hover (slight rotation, scale with elastic easing)
- Hand-drawn line animations (SVG stroke-dashoffset for paths appearing)
- Bounce and spring animations (cubic-bezier with overshoot)
- Elements that "settle" into place like paper being set down
- Avoid perfectly linear transitions - add slight irregularity with custom easing
- Prioritize CSS animations; use Motion library for React when needed

Backgrounds & Texture (on light bases):
- Paper textures: canvas grain, watercolor washes, recycled paper speckles
- Subtle noise overlays (10-20% opacity) for tactile feel
- Light graph paper grids, dot grids, or ruled lines
- Watercolor splashes and bleeds at section edges
- Coffee stains, ink splatters, tape marks (used sparingly)
- Torn paper edges for section dividers
- Light pencil sketch marks or construction lines

Visual Elements & Borders:
- WOBBLY LINES: Hand-drawn borders using SVG paths with slight irregularity
- Variable stroke widths (2-4px) that look hand-traced
- Rough edges and imperfect circles/rectangles
- Doodle-style icons and illustrations
- Drop shadows that look like pencil shading (soft, directional, organic)
- Scribbled highlights and underlines
- Sketchy arrows and connectors between elements
- Corner flourishes and hand-drawn brackets

Layout Characteristics:
- Slightly off-grid alignment (intentional 2-3px variations)
- Rotated elements (-2° to +3°) like scattered paper scraps
- Overlapping elements with paper-stack depth
- Generous whitespace with organic flow (not rigid grid)
- Sticky notes, index cards, and paper scraps as UI containers
- Hand-drawn speech bubbles and callouts
- Margin doodles and annotations

Implementation Details:
- Use CSS `filter: url(#roughen)` with SVG filters for texture
- Apply `transform: rotate()` with small random values for organic placement
- Border-radius with slight irregularity: `border-radius: 12px 15px 13px 14px`
- Box shadows with multiple layers for depth: `box-shadow: 2px 3px 0 rgba(0,0,0,0.1), 4px 6px 0 rgba(0,0,0,0.05)`
- Use SVG paths with slight bezier curve variations for "wobbly" lines
- `mix-blend-mode: multiply` for overlapping paper effects

Illustration Style:
- Line drawings with variable weight
- Cross-hatching for shadows
- Stippling and texture marks
- Simplified shapes with character
- Imperfect symmetry
- Visible "construction lines" (very light)

ANTI-PATTERNS TO AVOID:
- Perfect geometric shapes and pixel-perfect alignment
- Sterile, clinical white backgrounds without texture
- Digital gradients that look computer-generated
- Sharp, perfectly straight lines
- Generic sans-serif fonts (Inter, Roboto, Arial)
- Overused "smooth" animations with linear easing
- Corporate minimalism without personality
- Perfectly rounded corners (use irregular border-radius)
- Flat, shadowless designs without depth

CRITICAL: Every element should feel hand-crafted. If it looks like it could be made by a design system or component library, add more imperfection. Wobble those lines, rotate those cards, add texture to that background. The goal is warmth and humanity, not digital perfection.
</frontend_aesthetics>