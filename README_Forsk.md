# Tests

```
python -m venv .venv
source .venv/bin/activate
pip install tox
tox
```

Tox crée 2 env virtuels, un avec sqlalchemy 1.4 et un autre avec sqlalchemy 2.0
Changer le venv dans .vscode/settings.json  
Ctrl + Maj + P: Python clear cache and reload window

Lancer pytest depuis VSCode **en séquentiel** (filtrer si besoin)

Note : les tests d'autojoin, lazy_load et eager_load sont HS en 2.0 (voir "only_sqlalchemy_1")