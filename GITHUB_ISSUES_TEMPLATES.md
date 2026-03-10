# Templates d'Issues GitHub pour Sora 2 Pro

## ISSUE 1: Implémentation du Système Cameo (@ID)
**Objectif** : Stabiliser l'identité visuelle du protagoniste sur 10 clips consécutifs.

**Specs** :
- [ ] Extraire le vecteur d'identité (5-8s de capture).
- [ ] Mapper les mouvements de mâchoire pour le Lip-Sync natif.
- [ ] Tester la persistance des vêtements (Texture ID).
- [ ] Valider la cohérence des traits faciaux à travers les scènes.

---

## ISSUE 2: Optimisation de la Physique des Fluides
**Objectif** : Éviter les "téléportations" d'objets lors des interactions complexes.

**Specs** :
- [ ] Implémenter le tag `physics_hint: fluid_interaction` dans les prompts.
- [ ] Vérifier les rebonds de gouttes d'eau sur les surfaces non-planes.
- [ ] Tester les interactions de tissus dans le vent (5 mph breeze standard).
- [ ] Valider la gravité constante à 9.8 m/s².

---

## ISSUE 3: Synchronisation Audio-Visuelle Native
**Objectif** : Atteindre un lip-sync parfait avec dialogue structuré.

**Specs** :
- [ ] Configurer le bloc dialogue séparé sous la description visuelle.
- [ ] Tester la cible de 4.8 syllabes par seconde pour le rendu naturel.
- [ ] Implémenter les cues Foley (footsteps, ambiance, effets sonores).
- [ ] Valider le volume spatial et la distance sonore.

---

## ISSUE 4: Last Frame Stitching pour Continuité
**Objectif** : Assembler des séquences de 25s+ sans rupture visuelle.

**Specs** :
- [ ] Extraire l'End Frame du Clip A.
- [ ] Injecter comme Input Reference pour le Clip B.
- [ ] Rédiger les prompts de continuité ("Maintaining the same subject...").
- [ ] Tester l'invisibilité des transitions (Match cuts).

---

## ISSUE 5: Palette de Couleurs et Cohérence Narrative
**Objectif** : Appliquer une grammaire chromatique stricte sur tous les clips.

**Specs** :
- [ ] Définir les codes HEX pour chaque rôle narratif.
- [ ] Documenter l'usage des couleurs (ex: #B0BEC5 pour Institutionnel).
- [ ] Tester la cohérence visuelle sur 5+ clips avec la même palette.
- [ ] Valider les LUTs (Look-Up Tables) pour le style global.