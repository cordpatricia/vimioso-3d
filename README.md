# Patrícia Cordeiro – Digital heritage portfolio

**Portfolio page:** https://cordpatricia.github.io/vimioso-3d/
**3D model (Sketchfab):** https://sketchfab.com/3d-models/4ea5c879151446e2ba9f68a1c4b4c1b9

This repository holds my digital heritage portfolio: selected projects with my role in each,
and a hands-on 3D documentation of a cântara (water vessel), MECC.0193, from the ethnographic
collection of the Casa da Cultura de Vimioso (Portugal). The object is linked to community memory
recorded in interviews for the museum.

## The cântara: what I did

- **Capture:** three photogrammetric captures with an iPad (KIRI Engine). The first was a trial;
  the second included a ruler in the scene to give the scale; the third, with the object turned over
  and automatic masking, recorded the base without background and is the published model.
- **Scale:** checked against the ruler in the scene (30 cm between marks = 0.3064 m in the model,
  corrected by a uniform factor of 0.979). Resulting height: 27.3 cm (inventory: 27 cm).
- **Processing:** orientation, scale and checks in Blender 5.1; export to glTF Binary (250,000 faces, 4K texture).
- **Publication:** Sketchfab viewer, embedded in the object page.
- **Documentation:** paradata (`PARADATA.md`) and an EDM record for Europeana (`edm-record.xml`).
- **In progress:** an annotated scene in Smithsonian Voyager Story.

## What this repository contains

| File | Content |
|---|---|
| `index.html` | Portfolio home: selected digital heritage projects and my role in each |
| `cantara.html` | Object page: the 3D model (Sketchfab embed) and its context |
| `PARADATA.md` | Record of how the model was made and the decisions taken |
| `edm-record.xml` | Metadata in the Europeana Data Model (EDM), following Europeana's guidelines for 3D content |
| `Cantara_MECC0193_Europeana_Academy.xlsx` | Europeana Academy mapping template, with semantic enrichment (Wikidata, Getty AAT, GeoNames) |
| `images/` | Project images (own photos, or used with permission) – to add |

## Standards

The metadata follows the [Europeana Data Model](https://europeana.atlassian.net/wiki/spaces/EF/pages/3255468048/Providing+3D+content+in+EDM+guidelines),
the standard required for the Casa da Cultura de Vimioso project: the object (`edm:ProvidedCHO`),
its 3D representations (`edm:WebResource`, `edm:type` = 3D), with the Sketchfab embed as
`edm:isShownBy`, and the aggregation that links them (`ore:Aggregation`). The paradata record is
linked from the model through `rdfs:seeAlso`.

## My role

I carried out every step of the cântara documentation myself: planning, photographic capture,
reconstruction, scaling and checks in Blender, publication, metadata and paradata.
This is a personal learning exercise, separate from the professional 3D digitisation
of the Casa da Cultura collection. For the other projects in the portfolio, each card states my role.

## Credits and permissions

- Object: Museu Etnográfico da Casa da Cultura de Vimioso (MECC.0193) – published with the permission of the Município de Vimioso.
- Community testimony: interview with Ema Vila-Chã, basket maker, Vale de Pena, 8 June 2026 (MUVIP project; interviewers Matilde Gomes, Patrícia Cordeiro and João Marques; signed consent).
- Viewer: Sketchfab (embed); next version: [Smithsonian Voyager](https://smithsonian.github.io/dpo-voyager/) (open source).
- Author: Patrícia Cordeiro – [ORCID 0000-0003-4086-392X](https://orcid.org/0000-0003-4086-392X)

## Licence

[To decide with the Município, e.g. CC BY-NC 4.0 for the model and the texts.]
