# IIC3633: Sistemas Recomendadores

**Proyecto Final, primer semestre 2026**

### Estudiantes:
* Alonso Casanova
* Bruno Cerda
* Berioska Maureen Contreras

---

Se trabaja con una versión espacialmente reducida del dataset [PixelRec](https://github.com/westlake-repl/PixelRec), la cual puede ser descargada mediante [este enlace de Drive](https://uccl0-my.sharepoint.com/:f:/r/personal/bcmardini_uc_cl/Documents/recsys-pf-01-2026?csf=1&web=1&e=Oxs9ac).

### Descripción de Notebooks

```text
analisis_exploratorio_0.ipynb y analisis_exploratorio_1.ipynb: 
    Contiene código de análisis exploratorio para el dataset PixelRec50k.

analisis_exploratorio_pixelrec.ipynb: 
    Contiene código de análisis exploratorio relacionado al dataset y 
    atributos específicos relevantes para la implementación de SASRec.

baselines.ipynb: 
    Contiene las implementaciones de las baselines: Random, Most Popular y ALS.

efm_rec.ipynb: 
    Contiene implementación de baseline EFMRec.

efm_rec_gated_fusion.ipynb: 
    Contiene implementación de baseline EFMRec con Gated Fusion implementado.

efm_rec_siglip: 
    Contiene implementación de EFMRec con SigLIP en vez de CLIP.

efm_rec_siglip_gated_fusion.ipynb: 
    Contiene implementación de EFMRec con SigLIP y Gated Fusion.

vl_clip.ipynb: 
    Contiene implementación de baseline VL-CLIP.

vl_clip_rank y vl_clip_rank-2.ipynb: 
    Contiene implementación de baseline VL-CLIP con leves modificaciones 
    relacionadas a la metodología de recomendación.
