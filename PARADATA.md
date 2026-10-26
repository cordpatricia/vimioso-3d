# Paradata – Cântara (MECC.0193)

Record of how this 3D model was produced, so that others can understand, assess and reuse it.

## 1. Object

| Field | Value |
|---|---|
| Name | Cântara (water vessel) |
| Inventory number | MECC.0193 (original no. 192) |
| Collection / holder | Museu Etnográfico da Casa da Cultura de Vimioso, Município de Vimioso |
| Material and surface | Clay, unglazed, matte surface [marks of use – to confirm] |
| Form and decoration | Rounded body, narrow neck, one handle from rim to shoulder; band of short incised strokes around the shoulder [to confirm with the museologist] |
| Possible provenance | Pinela (Bragança), women potters (*louceiras*) – hypothesis based on decoration, surface texture and shape; not a confirmed attribution |
| Dimensions (inventory) | Height 27 cm × width 24 cm × depth 20.5 cm |
| Condition (inventory, 20/10/2026) | Regular |
| Location at capture | MORE CoLAB – temporary loan ACT-MUVIP-2026-001 |

## 2. Capture

Three captures were made. Capture 1 was a trial; its limitations (no scale reference, base not captured,
artificial light) led to captures 2 and 3. Capture 2 included a ruler in the scene and gave the scale;
capture 3, with the object turned over and automatic masking, recorded the base without background
and is the one published.

| Field | Capture 1 (trial) | Capture 2 (scale reference) | Capture 3 (published) |
|---|---|---|---|
| Date | 21 October 2026, about 18:30 | 23 October 2026, morning | 23 October 2026 |
| Place | MORE CoLAB | MORE CoLAB | MORE CoLAB |
| Device | iPad [model], with LiDAR | iPad [model] | iPad [model] |
| App and mode | KIRI Engine (free) – Photo Scan | KIRI Engine (free) – Photo Scan | KIRI Engine (free) – Photo Scan |
| Number of photos | 150 | [ ] | [ ; of which with the object turned over: ] |
| Capture pattern | 3 rings, object upright | Rings, object upright and turned over | Rings with the object upright, then turned over (mouth down) to capture the base |
| Lighting | Artificial | Natural, diffuse | Natural, diffuse |
| Scale reference | None | Folding ruler in the scene | None in the model (masked); scale transferred from capture 2 |
| Auto Object Masking | On | Off (background, ruler and support reconstructed) | On |
| Export | GLB | GLB | OBJ (format chosen before upload; GLB exported from Blender) |

## 3. Processing

| Step | Tool | What I did and why |
|---|---|---|
| Reconstruction | KIRI Engine (cloud) | Polygon count: High; texture: 4K; Train AI off; visibility private |
| Scale (capture 2) | Blender 5.1 | Ruler captured in the scene: 30 cm between marks measured 0.3064 m; uniform correction factor 0.979. Resulting height of the object: 27.3 cm (inventory: 27 cm) |
| Scale (capture 3) | Blender 5.1 | Uniform scale factor 0.298, to match the ruler-based height of capture 2 (27.3 cm) |
| Orientation | Blender 5.1 | Model rotated upright (OBJ import) [and levelled]; rotation and scale applied to the mesh |
| Cleaning | Blender 5.1 | Capture 3 needed almost no cleaning thanks to masking [describe any] |
| Repair | – | Base recorded in capture 3, so no reconstructed surface [confirm] |
| Export | Blender 5.1 | model.glb (glTF Binary), 250,000 faces, 4K texture, [file size] |

## 4. Publication

| Field | Value |
|---|---|
| Authoring tool | Smithsonian Voyager Story (standalone) |
| Annotations | [number and topics] |
| Article / tour | [ ] |
| Hosting | GitHub Pages; [Sketchfab, for an oEmbed-compliant viewer] |

## 5. Context and community knowledge

The object page includes a testimony from an interview recorded for the museum (Ema Vila-Chã,
basket maker, Vale de Pena, 8 June 2026; 30:56 min; interviewers Matilde Gomes, Patrícia Cordeiro
and João Marques; signed consent) about her own clay cântaro and the woven rings (*rodelas*)
used to rest it. The testimony concerns a similar object, not MECC.0193 itself, and is presented as context.

The ICH framing follows this order:

1. **Pottery know-how** – as a clay vessel, the cântara relates first of all to the know-how of
   Portuguese pottery (UNESCO 2003 Convention domain: traditional craftsmanship).
2. **Uses** – carrying and keeping drinking water, at home and in the fields (harvest).
3. **Associated ICH** – the museum's working ICH inventory (MUVIP, *PCI inventário atualizado V.2*)
   lists cântaros/aguadeiros as "special objects", because going to the fountain was an everyday
   practice associated with women (fountain songs, sociability, oral history). These are research
   working notes of the project.

## 6. Limitations and decisions

- Capture 1 (trial) had no scale reference, so its scale was arbitrary, and the base was not captured. These problems were corrected in capture 2 by placing a ruler in the scene and turning the object over to photograph the base.
- Scale is based on the ruler in the scene, not on the inventory dimensions (27 × 24 × 20.5 cm). [Compare the final model with a manual tape measurement of the object.]
- Capture 2 (with the ruler) was also cleaned and its base hole closed with Grid Fill (3,146 faces, separate material "reconstruction_base"); it is kept as the scale reference, not published.
- The colour differs between captures 2 and 3 (natural light changed); [state which is closer to the object].
- The width measured on the model (about 21 cm, handle included) differs from the inventory value (24 cm). [To check with the museologist.]
- [What I would do differently in a professional campaign: e.g. scale bars with targets, a turntable, colour checker.]

## 7. Rights

Object published with the permission of the Município de Vimioso. Testimony used under the consent signed by the interviewee [confirm that it covers online publication with her name]. Licence: [ ].
