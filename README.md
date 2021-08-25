
# Envoi de mails automatisés pour le piaulage de la maison des mines

## Installation

### Prérequis

L'écriture de cette partie reprend grandement la documentation Google Sheets : https://developers.google.com/sheets/api/quickstart/python#step_2_configure_the_sample

Il faut que les programmes suivants soient installés :

- python (version 2.6 minimum)
- pip
- virtualenv *(facultatif, pour ne pas faire de dégâts sur sa machine)*

### Installation de l'environnement

Tout va se faire dans un dossier projet, à créer.

```
virtualenv .
source bin/activate
  pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
``̀`
