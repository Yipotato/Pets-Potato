Create a single horizontal sprite strip for the Codex app digital pet `star-tater` in the state `idle`.

Use the attached reference image(s) for pet identity and the attached base pet image as the canonical design. Use the attached layout guide image only for frame count, slot spacing, centering, and safe padding. Simplify any high-resolution reference details into the Codex digital pet sprite style. Do not simply copy the still reference pose. Generate distinct animation poses that create a readable cycle.

Identity lock:
- Do not redesign the pet. Only change pose/action for the `idle` animation.
- Preserve the exact head shape, ear/horn/limb shape, face design, markings, palette, outline weight, body proportions, prop design, and overall silhouette from the canonical base pet.
- Keep every frame recognizably the same individual pet, not a related variant.
- If the pet has a prop or accessory, preserve its size, side, palette, and attachment style unless the row action requires a small pose-only adjustment.
- Prefer a subtler animation over any change that mutates the pet identity.

Output exactly 6 separate animation frames arranged left-to-right in one single row. Each frame must show the same pet: Anthropomorphic cartoon potato mascot. Small chibi rounded vertical oval potato body, warm potato-yellow skin, dark caramel-brown outline, simple flat cel shading, chunky pixel-art-adjacent edges, compact readable silhouette. Lower body has small darker yellow-orange potato skin spots / potato eyes fixed on the body surface, never floating. A small four-corner diamond sparkle is attached to the upper-right edge of the potato as a permanent identity mark: exactly four points pointing up, right, down, and left, like a simple sparkle glyph, not a five-point star, not a sheriff badge, no extra diagonal points. The pet wears thin round black eyeglass frames by default. Only eyeglass frames and sunglass lenses may be pure black. Body outline must be dark warm brown, not pure black.

Expression rules: happy special expression may use solid black sunglasses with hidden eyes and upward smile; sad/failed expression keeps round glasses visible with X-shaped eyes in the lenses and downturned mouth; shocked expression shows no glasses, tiny dot eyes, jagged potato-skin fringe above the eyes, and an O-shaped mouth; review expression is focused with clear round glasses and concentrated eyes.

Idle animation is exactly 6 frames and round glasses remain visible in every idle frame: frame 1 normal open eyes, cute blank expression; frame 2 happy laughing eyes like upward chevrons ^^ with small open laughing mouth; frame 3 both eyes fully closed, calm blink or peaceful pause; frame 4 normal open eyes again; frame 5 playful wink with one eye closed and the other open; frame 6 same normal open-eyed expression as frame 1 for a smooth loop..

Style contract: Codex digital pet sprite style: pixel-art-adjacent low-resolution mascot sprite, compact chibi proportions, chunky whole-body silhouette, thick dark 1-2 px outline, visible stepped/pixel edges, limited palette, flat cel shading with at most one small highlight and one shadow step, simple readable face, tiny limbs, and no detail that disappears at 192x208. Avoid polished illustration, painterly rendering, anime key art, 3D render, vector app-icon polish, glossy lighting, soft gradients, realistic fur or material texture, anti-aliased high-detail edges, and complex tiny accessories. Additional user style notes: Codex small digital pet style. Warm yellow potato palette with orange-yellow skin spots. Transparent-ready sprite on chroma-key background. No scenery, no floor shadow, no text, no detached effects, no loose sparkles. The upper-right attached identity mark must be a four-corner diamond sparkle with exactly four points, not a five-point star. Preserve the same potato shape, four-corner sparkle position, round glasses design, body spots, palette, outline weight, and proportions across all frames. Idle should prioritize the specified face sequence over generic breathing; use only tiny body bob or eyeglass bob if it does not obscure the six facial expressions..

Use this prompt as an authoritative sprite-production spec. Do not expand it into a polished illustration, painterly character image, anime key art, 3D render, vector mascot, glossy app icon, realistic animal portrait, or marketing artwork.

Animation action: neutral breathing/blinking loop.


State-specific requirements:
- CRITICAL: idle is the low-distraction baseline state and the first frame is also used as the reduced-motion static pet.
- Use only subtle idle motion: gentle breathing, a tiny blink, a slight head or body bob, a very small material sway, or another quiet motion that fits the pet persona.
- Keep the pet essentially in the same pose, facing direction, silhouette, markings, palette, and prop state across all 6 frames.
- Do not show waving, walking, running, jumping, talking, working, reviewing, emotional reactions, large gestures, item interactions, or new props.
- Feet, base, body, or object anchor should remain planted or nearly planted.
- The first and last frames should be very close visually so the loop feels calm and does not pop.

Transparency and artifact rules:
- Prefer pose, expression, and silhouette changes over decorative effects.
- Effects are allowed only when they are state-relevant, opaque, hard-edged, pixel-style, fully inside the same frame slot, and physically touching or overlapping the pet silhouette.
- Allowed attached effects can include a tear touching the face, a small smoke puff touching the pet or prop, or tiny stars overlapping the pet during a failed/dizzy reaction.
- Do not draw detached effects: floating stars, loose sparkles, floating punctuation, floating icons, falling tear drops, separated smoke clouds, loose dust, disconnected outline bits, or stray pixels.
- Do not draw wave marks, motion arcs, speed lines, action streaks, afterimages, blur, smears, halos, glows, auras, floor patches, cast shadows, contact shadows, drop shadows, oval floor shadows, landing marks, or impact bursts.
- Do not include text, labels, frame numbers, visible grids, guide marks, speech bubbles, thought bubbles, UI panels, code snippets, scenery, checkerboard transparency, white backgrounds, or black backgrounds.
- Do not use the chroma-key color or chroma-key-adjacent colors in the pet, prop, effects, highlights, shadows, or outlines.
- Reject any pose that is cropped, overlaps another pose, crosses into a neighboring frame slot, or creates a separate disconnected component that is not attached to the pet.

Layout requirements:
- Exactly 6 full-body frames, left to right, in one horizontal row.
- The attached layout guide shows the 6 frame boxes and inner safe area for this row. Follow its slot count, spacing, centering, and padding.
- Do not reproduce the layout guide itself: no visible boxes, guide lines, center marks, labels, guide colors, or guide background may appear in the output.
- Treat the image as 6 equal-width invisible frame slots. Fill every slot: each requested slot must contain exactly one complete full-body pose.
- Spread the 6 poses evenly across the whole image width. Do not leave any requested slot blank or create large empty gaps between poses.
- Center one complete pose in each slot. No pose may cross into the neighboring slot.
- Use a perfectly flat pure cyan #00FFFF chroma-key background across the whole image.
- Do not draw visible grid lines, borders, labels, numbers, text, watermarks, or checkerboard transparency.
- Do not include scenery or a background environment.
- Keep the rendering sprite-like: chunky silhouette, dark pixel-style outline, limited palette, flat shading, minimal tiny detail.
- Do not use #00FFFF, pure cyan, or colors close to that chroma key in the pet, props, highlights, shadows, motion marks, dust, landing marks, or effects.
- Do not draw shadows, glows, smears, dust, or landing marks using darker/lighter versions of the chroma-key color.
- Keep every frame self-contained with safe padding. No pet body part should be clipped by the frame slot.
- Avoid motion blur. Use clear pose changes readable at 192x208.
- Preserve the same silhouette, face, proportions, palette, material, and props across every frame.
