# Prompt Engineering Reference

## Prompt architecture

Use this order as a flexible framework:

1. Image format and subject.
2. Reference-image guidance, when applicable.
3. Pose, expression, action, and framing.
4. Wardrobe, styling, and material details.
5. Environment and visual premise.
6. Composition, palette, and lighting.
7. Camera and rendering characteristics.
8. Required exclusions and exact text.

## Be concrete

Prefer:
- "soft directional daylight from camera left, with gentle shadow falloff"
over:
- "beautiful lighting".

Prefer:
- "tailored double-breasted jacket in matte ivory wool, clean shoulder line, narrow lapels"
over:
- "very stylish expensive outfit".

Prefer:
- "low-angle three-quarter portrait with the subject positioned in the right third"
over:
- "amazing cinematic composition".

## Keep prompts coherent

Avoid contradictory directions such as:
- shallow depth of field and every background detail perfectly sharp;
- soft diffused light and extremely hard-edged shadows from the same source;
- full-body framing and a tight facial close-up;
- minimalist styling and dozens of decorative accessories.

If a deliberate visual contradiction is part of the concept, explain how it should appear.

## Length control

The default target is approximately 800–1,000 characters including spaces. This is not a universal platform limit. Follow the user's explicit limit and the selected image tool's actual constraints.

To shorten a prompt:
1. Remove repeated adjectives.
2. Merge related material and styling details.
3. Remove details that do not affect the visible result.
4. Preserve the subject, visual hook, composition, lighting, and critical constraints.

## Exact text in images

When text must appear in the image:
- quote the exact wording;
- specify language and spelling;
- describe placement, size, contrast, and legibility;
- avoid adding extra text unless requested.

Text rendering varies by image model. Do not promise flawless typography unless verified in the actual output.
