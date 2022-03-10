
# Setup

- Quelques commandes utiles pour installer correctement ce projet
- A lancer depuis "/<nomRepository>/project"




## Créer un environnement virtuel

Windows 

```bash
python -m venv env
env/Scripts/activate
```
Mac 

```bash
python -m venv env
source env/bin/activate
```
## Installer les dépendances / packages

```bash
pip install -r requirements.txt
```
## Migration BDD

```bash
python manage.py migrate
```
## Lancer le serveur

```bash
python manage.py runserver
```
