# Cântara (MECC.0193) – 3D documentation

**Live viewer:** https://cordpatricia.github.io/vimioso-3d/

A small end-to-end 3D digital heritage exercise: a cântara (water vessel) from the ethnographic
collection of the Casa da Cultura de Vimioso (Portugal), captured, processed and published by me
online (Sketchfab viewer), and linked to community memory recorded in interviews for the museum.
Work in progress: cleaning in Blender and an annotated scene in Smithsonian Voyager.

## What this repository contains

| File | Content |
|---|---|
| `index.html` | Web page that displays the model (Sketchfab embed) and its context |
| `model.glb` | 3D model (photogrammetry, iPad, KIRI Engine) |
| `scene.svx.json` | Voyager scene: annotations, article and tour (in progress) |
| `PARADATA.md` | Record of how the model was made and the decisions taken |
| `edm-record.xml` | Metadata in the Europeana Data Model (EDM), following Europeana's guidelines for 3D content |
| `Cantara_MECC0193_Europeana_Academy.xlsx` | Europeana Academy mapping template, with semantic enrichment (Wikidata, Getty AAT, GeoNames) |

## Standards

The metadata follows the [Europeana Data Model](https://europeana.atlassian.net/wiki/spaces/EF/pages/3255468048/Providing+3D+content+in+EDM+guidelines),
the standard required for the Casa da Cultura de Vimioso project: the object (`edm:ProvidedCHO`),
its 3D representations (`edm:WebResource`, `edm:type` = 3D) and the aggregation that links them
(`ore:Aggregation`), with the paradata record linked from the model through `rdfs:seeAlso`.

## My role

I carried out every step myself: planning, photographic capture, reconstruction,
scaling, metadata, paradata and publication on GitHub Pages.
This was a personal learning exercise, separate from the professional 3D digitisation
of the Casa da Cultura collection.

## Credits and permissions

- Object: Museu Etnográfico da Casa da Cultura de Vimioso (MECC.0193) – published with the permission of the Município de Vimioso.
- Community testimony: interview with Ema Vila-Chã, basket maker, Vale de Pena, 8 June 2026 (MUVIP project; interviewers Matilde Gomes, Patrícia Cordeiro and João Marques; signed consent).
- Viewer: Sketchfab (embed); next version: [Smithsonian Voyager](https://smithsonian.github.io/dpo-voyager/) (open source).
- Author: Patrícia Cordeiro – [ORCID 0000-0003-4086-392X](https://orcid.org/0000-0003-4086-392X)

## Licence

[To decide with the Município, e.g. CC BY-NC 4.0 for the model and the texts.]
