# Cours SIO 1B

Site de partage de cours. La liste des documents se met à jour toute seule à partir des dossiers de ce dépôt.

## Structure

```
cours/
  Maths/          ← une rubrique = un dossier
  Réseaux/
  ...
divers/           ← documents non liés aux cours
index.html        ← le site (ne pas toucher)
```

## Ajouter un document

1. Sur le site, clique sur **+ Ajouter un document** (ou sur GitHub : *Add file → Upload files*).
2. Pour mettre le fichier dans une rubrique, tape le chemin du dossier dans le nom du fichier, par exemple `cours/Maths/chapitre1.pdf`. Sinon, glisse le fichier dans un dossier existant (ouvre d'abord le dossier sur GitHub, puis *Add file → Upload files*).
3. Clique sur **Commit changes**. Le document apparaît sur le site au bout d'une minute environ.

## Ajouter une rubrique

*Add file → Create new file*, puis tape dans le nom : `cours/NomDeLaRubrique/.gitkeep`, puis *Commit changes*. La rubrique apparaît dans le menu du site (un dossier vide n'existe pas dans Git, d'où le fichier `.gitkeep`).

## Supprimer une rubrique ou un document

Ouvre le fichier sur GitHub, puis `…` → *Delete file*. Une rubrique disparaît quand son dernier fichier (y compris `.gitkeep`) est supprimé.

## Remarques

- Les PDF et les images s'ouvrent directement dans le navigateur, tous les fichiers peuvent être téléchargés.
- Évite les fichiers de plus de 25 Mo (limite de l'envoi via le navigateur).
