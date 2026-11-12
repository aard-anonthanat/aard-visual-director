# Reference Image Workflow

## Before writing the prompt

Identify what the user wants to preserve and what may change.

Typical preservation targets:
- recognizable facial identity;
- face shape and proportions;
- hairstyle and hairline;
- brows and other visible defining features;
- skin tone as shown in the source;
- body proportions or other visible characteristics, when explicitly requested.

Typical editable targets:
- outfit and accessories;
- pose and expression;
- location and background;
- lighting, camera angle, and crop;
- visual genre or art direction.

## Prompt pattern

"Use the supplied reference image as the primary visual reference for the subject. Preserve the subject's recognizable facial identity and the visible defining facial characteristics. Change only [requested changes]. Do not introduce unrelated changes to [features the user wants preserved]."

Adapt the wording to the user's actual constraints. Do not blindly paste every preservation phrase into every prompt.

## Important limitations

- Reference-image features vary by generator and model version.
- A text prompt cannot guarantee exact identity preservation.
- Some tools support multiple references, masks, character references, or image-editing controls; others do not.
- If the result drifts, recommend using the tool's reference-strength, image-editing, or masking controls where available.
- Do not infer sensitive traits, identity, or biography from the image.
