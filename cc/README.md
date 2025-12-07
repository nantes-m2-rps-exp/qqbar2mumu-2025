# Comment se connecter à la plateforme Jupyter du CC-IN2P3

Utilisez votre navigateur préféré pour aller sur https://notebook.cc.in2p3.fr, qui devrait ressembler à :

![](cc-jupyter-platform-landing-page.webp)

Cliquez sur le bouton orange "Launch My Notebooks Server". Cela devrait vous emmener vers la page d'authentification du CC-IN2P3 :

![](cc-authentication-page.webp)

Entrez votre identifiant et votre mot de passe (donnés par vos encadrants à la première séance)

Vous obtenez alors l'écran principal de la plateforme Jupyter

![](cc-jupyter-ui.webp)

# A faire après la première connexion

Aller dans le menu `Git -> Clone a Repository` et entrez l'adresse du dépot git qui contient le point de départ de ce projet :

```shell
https://github.com/nantes-m2-rps-exp/qqbar2mumu-2025.git
```

![](cc-jupyter-clone-a-repo.webp)

Vous devrez à ce stade entrez vos identifiants Github : nom d'utilisateur et "personal access token" (qui est différent de votre mot de passe pour accéder à votre compte Github).

Notez qu'un répertoire `qqbar2mumu-2025` devrait apparaître dans la partie gauche de l'écran (qui est la partie "explorateur de fichiers"). A l'aide de l'explorateur de fichiers naviguez jusqu'au répertoire `qqbar2mumu-2025/notebooks` et double-cliquez sur `01-muon-eta-distribution.ipynl`. Ceci ouvre votre premier notebook qui vous sera présenté lors de la première séance.

![](cc-jupyter-first-notebook.webp)

Enfin, modifiez le mot de passe temporaire qui vous a été fourni pour votre accès au CC-IN2P3, en vous connectant au [portail d'identité](https://id.cc.in2p3.fr) et en cliquant sur "Changement de mot de passe".

![](cc-portail-identite.webp)
