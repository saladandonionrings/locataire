# Contribuer

Merci de vouloir améliorer ce guide ! Il n'est utile que s'il est **exact** et **à jour**.

## Les règles

1. **Toujours sourcer.** Toute règle de droit doit citer son texte (article de loi, décret, code) ou une décision de justice. Les liens vers [Légifrance](https://www.legifrance.gouv.fr), [Service-Public.fr](https://www.service-public.fr) ou l'[ANIL](https://www.anil.org) sont préférés.
2. **Clair et pratique.** On écrit pour des locataires, pas pour des juristes : phrases courtes, exemples chiffrés, « que faire concrètement ».
3. **Gratuit d'abord.** Les solutions proposées doivent être gratuites ou les moins chères possible.
4. **Neutre.** On explique les droits du locataire ; on ne fait pas de procès d'intention aux bailleurs, dont beaucoup respectent la loi.
5. **Pas de données personnelles** ni de nom de bailleur ou d'agence réels dans les exemples.

## Comment proposer une modification

- **Petite correction** : bouton « Modifier cette page » sur le site, ou directement sur GitHub.
- **Signaler une erreur / un changement de loi** : ouvrez une [issue](../../issues/new/choose).
- **Nouvelle page** : ajoutez le fichier dans `docs/<catégorie>/` et référencez-le dans la `nav` de `mkdocs.yml`.

## Tester en local

```bash
pip install -r requirements.txt
mkdocs serve
```

Avant de proposer une pull request : `mkdocs build --strict` doit passer sans avertissement.
