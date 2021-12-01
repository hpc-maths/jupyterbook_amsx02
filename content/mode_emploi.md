# Mode d'emploi pour l'exécution des notebooks Jupyter

Afin de pouvoir exécuter les notebooks mis à disposition pour les cours et les pc, trois possibilités sont possibles :

## Utiliser son environnement personnel

Pour ce mode, il suffit de télécharger les notebooks Jupyter depuis ce site et les exécuter sur sa machine. Pour installer l'environnement logiciel nécessaire à l'exécution des notebooks du cours, suivre la procédure suivante :
  
```{admonition} Procédure pour installer Jupyter Notebook

- Installer la dernière version de miniconda contenant Python 3 (disponible sur https://conda.io/miniconda.html) sauf si vous avez déjà installé une version de miniconda ou d'anaconda.  

- Créer un nouvel environnement pour le cours en tapant dans un terminal ou dans l’Anaconda Prompt :

`conda create -n amsx02 python=3`


- Activer l'environnement amsx02 :

`conda activate amsx02` 


-  Installer les packages python nécessaires pour le cours :

`conda install jupyter jupyterlab numpy scipy plotly mpmath`

-  Lancer le serveur Jupyter :

`jupyter notebook` ou `jupyter lab`
```

## Utiliser le JupyterHub de l'école

Pour ce mode, il suffit de télécharger les notebooks Jupyter depuis ce site et les copier vers le serveur `JupyterHub` de l'école (cf. procédure suivante).

``````{admonition} Utilisation du JupyterHub de l'école

- Dans un navigateur, se rendre sur le site https://jupytercloud.idcs.polytechnique.fr/ et cliquer sur le lien `jupyter` puis sur le bouton `Sign in with CNRS/INSMI/Mathrice OpenID-Connect Provider`.


- Sélectionnez votre établissement puis utiliser vos identifiants pour vous connecter sur la plateforme.


- Sur la page Server Options, cliquer dans le rectangle  `Python scientific environment` qui permet de lancer un `JupyterLab` avec un noyau Python et les modules nécessaires au cours.


- Pour exécution des notebooks Julia, cliquer sur le rectangle `Python scientific environment` qui permet de lancer un `JupyterLab` avec un noyau Python et les modules nécessaires au cours.


- Cliquer sur l'icone `Upload files` du menu de la barre latérale gauche pour téléverser un notebook depuis votre machine vers le `JupyterLab` puis l'exécuter.

```{admonition} Remarque
Pour récupérer un notebook depuis la plateforme vers votre machine, cliquer avec le bouton droit sur le nom du notebook dans la barre latérale gauche puis en choisir `download`.
```

```{admonition} Attention
:class: warning
Penser à déplacer vos notebooks dans le répertoire `persistent` afin qu'ils soient conserver pour une prochaine session.
```
``````

## Utiliser Binder

Binder propose de déployer un environnement Jupyter accessible en ligne, sans aucune installation, à partir d’un dépôt git contenant des notebooks.
Pour lancer les notebooks du cours, il suffit de cliquer sur le lien binder présent sur chaque page du site proposant un notebook. 

```{admonition} Remarque
L'environnement Jupyter est supprimé lorsque que la session se termine, pensez à télécharger le notebook sur votre machine si vous souhaitez le garder.
``` 
