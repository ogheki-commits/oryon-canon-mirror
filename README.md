# Oryon — miroir canon pour IA

Base canon opérationnelle du manga **Ao dans Oryon**.

> ⚠️ Le dépôt contient des spoilers et des informations réservées auteur.

## Lecture recommandée

1. `ai-context.txt` — point d’entrée compact.
2. `canon-current.json` — canon consolidé général.
3. `docs/` — documents spécialisés validés par domaine ; ils prévalent lorsqu’ils sont plus récents et plus précis sur leur sujet.
4. `archive/` — historique uniquement ; **ne pas l’utiliser pour l’écriture courante**.

## API

`api/lore` et `api/lore.json` utilisent le canon consolidé général de `canon-current.json`. L’ancien gros lore v1.1 contradictoire a été retiré de l’API active et conservé dans `archive/historical-lore/api-lore-v1.1.json`.

Cela évite qu’une future IA lise accidentellement comme canon : Oryon = continent, Hetsuga battu par Vrul, ailes de Râ liées à Vrul, ancien déclencheur erroné de Sensor, ancien état de Mina, etc.

## Documents spécialisés actuels

- `docs/magie-oryon.md`
- `docs/protocole-medical-asteria.md`
- `docs/solaria.md`
- `docs/systeme-armes-oryon.md`
- `docs/demi-betes-oryon.md`
- `docs/citoyens-recrutement-oryon.md`
- `docs/lois-justice-securite-oryon.md`
- `docs/systeme-uniques-oryon.md`

`docs/magie-oryon.md` corrige une ancienne formulation du canon général : les natifs n'apprennent pas d'abord à « ressentir » puis « déplacer » le mana. Le mana fait naturellement partie d'eux ; une affinité simple se manifeste par image mentale, tandis que la difficulté réelle vient du contrôle et des formes complexes.

Le système des Uniques n’est plus un brouillon : les règles d’attribution, de découverte, de recyclage, l’absence de variantes/évolutions et la compensation des outsiders ont été validées par l’auteur le 2026-09-03.

Les anciennes questions temporaires de cohérence ont été résolues et le fichier de checklist correspondant a été supprimé. Les mécaniques explicitement laissées non définies dans le canon doivent néanmoins rester non inventées tant que l’auteur ne les précise pas.

## Règles de maintenance

- Ne pas créer une nouvelle couche `v1.x` à chaque modification.
- Mettre à jour directement le document spécialisé concerné ou le canon courant.
- Archiver uniquement lorsqu’une ancienne source doit rester consultable pour traçabilité.
- Ne jamais inventer une réponse à un champ explicitement non défini.
- CANON / PRÉVU / IDÉE et publicKnowledge / readerKnowledge / authorKnowledge doivent rester distincts.
- Lorsqu’un document spécialisé dans `docs/` et `canon-current.json` se chevauchent, le document spécialisé validé le plus récent prévaut sur ce domaine.

Le site miroir externe peut être resynchronisé plus tard ; en cas de différence temporaire, ce dépôt GitHub est prioritaire.
