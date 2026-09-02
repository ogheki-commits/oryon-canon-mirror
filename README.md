# Oryon — miroir canon pour IA

Base canon publique du manga **Ao dans Oryon**.

> ⚠️ Spoilers complets : ce dépôt contient des secrets auteur, des événements futurs et des informations non révélées au lecteur.

## Structure simple

- [Contexte IA compact](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/ai-context.txt)
- [Canon opérationnel consolidé](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/canon-current.json)
- [Protocole médical d’Asteria](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/docs/protocole-medical-asteria.md)
- [Index et règles d’utilisation](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/llms.txt)
- [Lore structuré historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore)
- [Copie JSON du lore historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore.json)

## Ordre de lecture normal

1. `ai-context.txt`
2. `canon-current.json`
3. `api/lore` / `api/lore.json` uniquement si un détail historique supplémentaire est nécessaire
4. document spécialisé éventuel, par exemple `docs/protocole-medical-asteria.md`

Les anciennes couches canoniques versionnées ont été retirées de la racine et conservées dans `archive/canon-layers/` pour traçabilité. Elles ne sont plus à lire en routine.

## Canon actuel

`canon-current.json` est désormais l’unique fichier de consolidation prioritaire. Il reprend les corrections et ajouts utiles des anciennes couches, notamment : monde et puissance, magie, Guilde, économie, géographie, bestiaire, armes, personnages, Uniques, chapitres 1 à 3, secrets auteur, protocole médical et Vely Flower.

La règle d’inscription actuelle suit la continuité des chapitres : **Pierre Noire = rang global ; cristaux séparés = affinités élémentaires**.

Vely Flower et sa Compétence Unique Flower sont intégrées au canon consolidé. **Flower n’est pas un pouvoir de régénération** : c’est un outil exceptionnel de diagnostic et de chirurgie intracorporelle.

## Maintenance future

À partir de maintenant, les nouvelles informations validées doivent être intégrées directement dans `canon-current.json`. On évite de créer une suite de fichiers `v1.5`, `v1.6`, etc.

`ai-context.txt` reste volontairement compact et sert de point d’entrée rapide. Les anciennes versions archivées restent disponibles uniquement si une vérification de provenance ou la récupération d’un détail ancien devient nécessaire.

Le site `oryon-archives-canon.ogheki.chatgpt.site` peut rester temporairement en retard et être resynchronisé plus tard depuis ce dépôt.
