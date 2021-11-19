# TP numéro 10

## Objectif:

Générer un fichier de configuration depuis un template

## Besoin:

- Créer un répertoire *templates*
- Créer un fichier *index.html.j2* dans *templates* avec le contenu suivant:

```
  Hello from {{ ansible_facts.hostname }}
```

- Créer un Playbook *index.yaml* tel que:
  - S’exécute sur les hosts *front*
  - Génere le fichier **index.html** dans `/usr/share/nginx/html/` à partir du template
- Exécuter le Playbook
- Réaliser un curl de vérification sur *server-0* et *server-1*

