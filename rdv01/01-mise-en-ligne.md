# découverte de github

## organisation dans mon ordinateur

- créer un dossier `tutorat` => dossier que je veux partager
- créer un sous dossier `rdv01` => organiser dans le dossier

## installer git sur ton ordinateur 

- <https://git-scm.com/downloads/win> 
- 64-bit Git for Windows Setup
- restart Visual Studio

## partager tutorat et tout son contenu dans github 

- dans Visual Studio => terminal > new terminal

```sh
# je veux pouvoir partager le contenu du dossier tutorat 
git init
# Initialized empty Git repository in C:/Users/harri/Documents/formateur/h3online/Youssef MANKOURI/tutorat/.git/
git add .
git commit -m "rdv01"
# je veux tout envoyer sur internet QUOI (mais c'est pas encore fait)
```

## créer un dépôt sur internet (sur github) et l'associer au dépot local

- je veux sur <https://github.com/webdevproformation> mon profil qu'il faut avoir déjà créé au préalable
- créer un nouveau réposirtory (distant)
- donne un nom => `tutorat youssef h3`

```sh
## associer mon dépot local avec le dépôt sur github
git remote add origin https://github.com/webdevproformation/tutorat-youssef-h3.git
```

## envoyer des fichiers de mon ordinateur vers dépôt distant

```sh
git push -u origin main
```

## lien pour le partage

<https://github.com/webdevproformation/tutorat-youssef-h3>

## envoyer au fur et à mesurer les modifications / ajout dans le github 

```sh 
git add .
git commit -m "coucou Youssef"
git push 
```