# Oryon — miroir canon pour IA

Base canon publique du manga **Ao dans Oryon**.

> ⚠️ Spoilers complets : ce dépôt contient des secrets auteur, des événements futurs et des informations non révélées au lecteur.

## Ressources directes

- [Contexte IA compact](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/ai-context.txt)
- [Audit canon complémentaire v1.3](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/canon-audit-v1.3.json)
- [Corrections et ajouts prioritaires v1.2](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/canon-overrides-v1.2.json)
- [Index et règles d’utilisation](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/llms.txt)
- [Lore structuré complet historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore)
- [Copie JSON du lore historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore.json)

## Ordre de lecture canon

1. `ai-context.txt`
2. `canon-audit-v1.3.json`
3. `canon-overrides-v1.2.json`
4. `api/lore` / `api/lore.json`

En cas de contradiction, l’audit v1.3 prime sur l’override v1.2, qui prime lui-même sur les formulations plus anciennes du lore principal. Ces fichiers prioritaires permettent d’éviter de réécrire brutalement le gros JSON historique tant que chaque correction n’a pas encore été fusionnée dans une future reconstruction complète de la base.

## Audit v1.3

La seconde passe d’audit corrige notamment plusieurs erreurs d’identifiants et de continuité du lore historique : Hetsuga a été vaincu en duel par Trya, pas Vrul ; les anciennes ailes de Râ sont liées à Trya, pas Vrul ; Oryon est une planète ; le Mont Céleste n’est pas une zone juridiquement interdite par définition ; les règles de plusieurs Uniques ont été précisées. Le bestiaire validé et les résumés consolidés des chapitres 1 à 3 sont également conservés dans `canon-audit-v1.3.json`.

## Organisation actuelle

GitHub sert de **base canon opérationnelle prioritaire** pour le travail avec ChatGPT. Le site `oryon-archives-canon.ogheki.chatgpt.site` peut rester temporairement en retard et être resynchronisé plus tard depuis ce dépôt.

Le dépôt est public afin que les ressources puissent être lues sans compte, cookie, session ou JavaScript. Le fichier `robots.txt` demande aux robots de ne pas indexer le miroir, sans pouvoir garantir l’absence totale de référencement du dépôt GitHub lui-même.

## Mise à jour

Une information proposée n’est jamais automatiquement canonique. Après validation explicite de l’auteur, elle peut être ajoutée au dépôt puis devenir prioritaire pour les reprises suivantes.