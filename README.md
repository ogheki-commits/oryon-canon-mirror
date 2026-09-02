# Oryon — miroir canon pour IA

Base canon publique du manga **Ao dans Oryon**.

> ⚠️ Spoilers complets : ce dépôt contient des secrets auteur, des événements futurs et des informations non révélées au lecteur.

## Ressources directes

- [Contexte IA compact](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/ai-context.txt)
- [Corrections et ajouts prioritaires v1.2](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/canon-overrides-v1.2.json)
- [Index et règles d’utilisation](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/llms.txt)
- [Lore structuré complet historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore)
- [Copie JSON du lore historique](https://raw.githubusercontent.com/ogheki-commits/oryon-canon-mirror/main/api/lore.json)

## Ordre de lecture canon

1. `ai-context.txt`
2. `canon-overrides-v1.2.json`
3. `api/lore` / `api/lore.json`

En cas de contradiction, les corrections validées de `canon-overrides-v1.2.json` priment sur les formulations plus anciennes du lore principal. Le fichier d’override permet d’éviter de réécrire brutalement le gros JSON historique tant que les corrections n’ont pas encore été fusionnées dans une future reconstruction complète de la base.

## Organisation actuelle

GitHub sert désormais de **base canon opérationnelle prioritaire** pour le travail avec ChatGPT. Le site `oryon-archives-canon.ogheki.chatgpt.site` peut rester temporairement en retard et être resynchronisé plus tard depuis ce dépôt.

Le dépôt est public afin que les ressources puissent être lues sans compte, cookie, session ou JavaScript. Le fichier `robots.txt` demande aux robots de ne pas indexer le miroir, sans pouvoir garantir l’absence totale de référencement du dépôt GitHub lui-même.

## Mise à jour

Une information proposée n’est jamais automatiquement canonique. Après validation explicite de l’auteur, elle peut être ajoutée au dépôt puis devenir prioritaire pour les reprises suivantes.
