# quad-Template
Template pour un kata en Python avec pytest

## Mise en place
- Ajouter le projet dans Pycharm
- déclarer un ``venv``
- ajouter un fichier ``requirements.txt``
- ajouter une dépendance vers ``pytest`` et ``pytest-cov``
- créer un répertoire pour les tests unitaires
- créer un package pour le code 
- créer un premier test (stupide), qui import le package et l'utilise
- vérifier dans un terminal que le ``venv`` est fonctionnel (``. activate ou activate.bat`` + éventuellement ``pip install -r requirements.txt``)
- dans l'hypothèse où Pycharm ne génère pas correctement le venv, le créer en ligne de commande avec ``virtualenv venv``
- vérifier que les tests passent : ``python -m pytest tests/unitaires``
- modifier le readme en ajoutant votre prénom/nom
- pousser votre premier commit
```
git status
# vérifier que tout est correct !!!
git add .
git commit -m "Premier commit"
git push
```

## se lancer dans le kata...
- Test en échec > Test vert > refactor > Test vert > commit
