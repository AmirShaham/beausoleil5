# 🏡 Maison Beausoleil 5 — Version 2 (devis signés)

## Ce qui est nouveau dans cette version

- **8 devis signés intégrés** avec leurs montants TTC réels (total engagé : 123 812,71 €)
- **Nouvel onglet "Devis & Lots"** : suivi des paiements par entreprise (acomptes + factures)
- **Nouvel onglet "Financement"** : vos 8 sources d'argent, avec montant disponible + virement prévu pour chacune
- **Fiches artisans pré-remplies** avec les vrais contacts extraits des devis
- **Tâches ajustées** aux prestations réelles des devis (ITE façade, Velux, motorisation volets, etc.)

---

## Mettre à jour votre application (vous avez déjà GitHub Pages)

Comme votre dépôt existe déjà, il suffit de **remplacer les 3 fichiers** :

1. Décompressez le ZIP `beausoleil5-v2`
2. Allez sur votre dépôt : `https://github.com/VOTRE_NOM/beausoleil5`
3. Cliquez **"Add file" → "Upload files"**
4. Glissez-déposez les 3 fichiers (`index.html`, `manifest.json`, `sw.js`) — ils écrasent les anciens
5. Cliquez **"Commit changes"**
6. Attendez 2 minutes, puis **Ctrl + Shift + R** sur l'app

Vos données existantes (JSONBin) sont **conservées** — la mise à jour ne touche que le code, pas vos données.

---

## Renseigner vos montants

### Onglet Financement
Pour chacune de vos 8 sources, deux champs :
- **Disponible maintenant** — ce que vous avez déjà sur ce compte
- **Virement prévu** — ce qui doit arriver prochainement

Le total mobilisable et la couverture du budget se calculent automatiquement.

### Onglet Devis & Lots
Pour chaque lot, entrez le **montant déjà payé** (acompte versé + factures réglées). La barre de progression et le "total payé" du tableau de bord se mettent à jour.

---

## Rappel des acomptes indiqués sur les devis signés

| Entreprise | Total TTC | Acompte demandé |
|---|---|---|
| La Petite Maçonnerie Rennaise | 34 170,75 € | 30% (~10 251 €) |
| J. VIDAL | 25 916,33 € | 7 774,90 € |
| AEROCHAUFFE | 23 474,94 € | 30% (~7 042 €) |
| BIZEUL Carrelage | 19 081,36 € | 5 724,41 € |
| M2T Électricité | 11 985,06 € | — |
| LEMOINE Benjamin | 4 691,41 € | 1 407,42 € |
| SAB Volets | 3 324,96 € | 1 329,98 € |
| SAB Porte/Fenêtre | 1 167,90 € | 467,16 € |

> Vérifiez vos relevés pour savoir exactement ce qui est déjà parti, puis reportez les montants dans l'onglet Devis & Lots.

---

## Note sur le budget

- **Total engagé (devis signés) : 123 813 €**
- **Reste sur 150 000 € : ~26 187 €** pour couvrir : cuisine équipée, parquets, peinture intérieure, mobilier, honoraires MOE et imprévus.

C'est serré mais gérable. L'onglet Financement vous aidera à visualiser si vos sources couvrent bien l'ensemble.

---

## Reconnexion sur un appareil

Rien ne change : même URL, même Master Key, même Bin ID (dans Réglages → Synchronisation).
