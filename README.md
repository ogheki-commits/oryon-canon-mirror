# Oryon — miroir canon pour IA

Base canon opérationnelle du manga **Ao dans Oryon**.

> ⚠️ Le dépôt contient des spoilers et des informations réservées auteur.

## Lecture recommandée

1. `ai-context.txt` — point d’entrée compact.
2. `canon-current.json` — canon consolidé principal.
3. `docs/` — documents spécialisés validés par domaine.
4. `drafts/` — questions et propositions non entièrement validées ; **ne pas les traiter comme canon**.
5. `archive/` — historique uniquement ; **ne pas l’utiliser pour l’écriture courante**.

## API

`api/lore` et `api/lore.json` pointent désormais sur le même contenu canon que `canon-current.json`. L’ancien gros lore v1.1, qui contenait plusieurs formulations obsolètes, a été retiré de l’API active et conservé dans `archive/historical-lore/api-lore-v1.1.json`.

Cela évite qu’une future IA lise accidentellement comme canon : Oryon = continent, Hetsuga battu par Vrul, ailes de Râ liées à Vrul, ancien déclencheur erroné de Sensor, ancien état de Mina, etc.

## Documents spécialisés actuels

- `docs/protocole-medical-asteria.md`
- `docs/solaria.md`
- `docs/systeme-armes-oryon.md`
- `docs/demi-betes-oryon.md`
- `docs/citoyens-recrutement-oryon.md`
- `docs/lois-justice-securite-oryon.md`

Une fiche spécialisée validée et plus récente prévaut sur une formulation générale plus ancienne de `canon-current.json` lorsqu’elles traitent exactement du même point.

## Brouillons

- `drafts/systeme-uniques-oryon-a-valider.md` : brouillon auteur sur l’algorithme/recyclage des Uniques et le cas Axiome.
- `drafts/points-a-rendre-coherents.md` : liste de décisions encore nécessaires pour verrouiller les zones susceptibles de créer des contradictions.

## Règles de maintenance

- Ne pas créer une nouvelle couche `v1.x` à chaque modification.
- Mettre à jour directement le canon courant ou le document spécialisé concerné.
- Archiver uniquement lorsqu’une ancienne source doit rester consultable pour traçabilité.
- Ne jamais inventer une réponse à un champ explicitement non défini.
- CANON / PRÉVU / IDÉE et publicKnowledge / readerKnowledge / authorKnowledge doivent rester distincts.

Le site miroir externe peut être resynchronisé plus tard ; en cas de différence temporaire, ce dépôt GitHub est prioritaire.
