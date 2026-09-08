# Cellule Vidéo — Pilotage des AO

Dépôt de référence pour le pilotage des appels d'offres (AO) et l'expertise marque blanche du Pôle Audiovisuel L'Étudiant.

## Structure

- `/methode/` — la méthode de pilotage AO (ordre des livrables, trames, leçons capitalisées). Document vivant, mis à jour après chaque AO.
- `/ao/<nom-ao>/` — un dossier par AO, toujours les 4 mêmes livrables :
  - `01_FICHE_SYNTHESE.md` — vue d'ensemble en un coup d'œil
  - `02_FICHE_APPROCHE.md` — le raisonnement à défendre en réunion
  - `03_BUDGET.xlsx` (ou `03_BUDGET_BPU.xlsx`) — chiffrage détaillé
  - `04_FICHE_REPONSE_POLE_VIDEO.md` — matière transmise aux OPS (rédigée en dernier)

## Workflow

1. Un AO arrive → Claude prépare les 4 livrables dans une conversation
2. Claude prépare les fichiers et les commits localement
3. Martin pousse les commits vers ce repo depuis son poste
4. La méthode (`/methode/`) évolue par petites retouches au fil des apprentissages — jamais réécrite en bloc

## État au 08/09/2026

Trois AO en première passe : `cyrce-biot2-normandie` (bouclé), `isae-supaero` (condition : réseau prestataire Toulouse), `opco2i` (condition : références commerciales externes + portage Direction).
