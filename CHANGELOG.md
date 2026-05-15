# Changelog — DrawingVol

## v1.0.0 — 2025-05

### Première version publique

**Formes**
- Prisme triangulaire, carré, pentagonal, hexagonal (N=3..6)
- Cylindre (N=1) avec peigne de languettes haut/bas
- Vesica piscis (N=2) avec clipping exact (intersection de deux disques)

**Interface**
- Sliders : côté/rayon, hauteur, écart base/sommet, largeur et angle des languettes
- Import SVG par double-clic sur une face (drag, zoom molette, fit automatique)
- Aperçu en temps réel avec calques activables (Contours, Languettes, Pliage, Dessins, Découpe)
- Mode plein écran

**Export SVG**
- Format A3 portrait (297×420 mm), rotation 90°
- Calques Inkscape séparés (Découpe, Contours, Languettes, Pliage, Dessins)
- Clipping vectoriel Sutherland-Hodgman par face (rectangle, cercle, vesica, polygone)
- Progression en temps réel dans la barre de statut
- Paths purs sans clipPath — tracé direct au pen plotter sans post-traitement

**Calque Découpe**
- Périmètre unique fermé (union contours + languettes)
- Pas de traits intérieurs — compatible machine de découpe

**Documentation**
- Manuel d'utilisation complet (7 sections, format .docx)
- Schémas géométriques annotés
- Exemples pen plotter pour les 6 formes
