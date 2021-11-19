# Correction TP 10


## Créer un folder *templates*

```Shell
mkdir templates
```

## Créer un fichier *index.html.j2* dans *templates*

```Shell
vi templates/index.html.j2
```

## Créer un Playbook *index.yaml* 

```Shell
vi index.yaml
```

## Exécuter le Playbook

```Shell
ansible-playbook -i inventory index.yaml
```

## Réaliser un curl de vérification sur *server-0* et *server-1*

```Shell
curl http://server-0.scc-edu
curl http://server-1.scc-edu
```

Lien vers le dossier [corrections](../Correction)