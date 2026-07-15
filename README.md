# Formulaire de demande

Deux versions du même formulaire selon la plateforme.

## GitHub (formulaire interactif)
- `.github/ISSUE_TEMPLATE/demande.yml` : formulaire avec champs, listes déroulantes, champs obligatoires.
- `.github/ISSUE_TEMPLATE/config.yml` : désactive les issues vides pour ouvrir le formulaire directement.

Pour tester : onglet Issues > New issue.

## GitLab interne (Markdown)
- `.gitlab/issue_templates/demande.md` : GitLab ne lit pas le YAML, il faut la version Markdown.

À la création d'une issue sur GitLab, le template apparaît dans le menu « Choose a template ».
Pour l'appliquer par défaut : Settings > General > Default description template for issues.
