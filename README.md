# INF8225_projet

Projet d'intelligence artificielle du cours INF8225 à Polytechnique Montréal.

Auteurs : Augustin BARRUOL, Ilan BASTA, Lamia SALHI, Andrey SOBOLEVSKY


Ce GitHub est composé de 2 dossiers :

- le dossier `GAN` comporte : 
  - Un jupyternotebook pour entrainer un DCGAN et visualiser les images générées, les interpolations linéaires et sphériques ainsi qu'une pojection T-SNE       d'un modèle au choix. Le code du DCGAN est inspiré du gitub https://github.com/csinva/gan-vae-pretrained-pytorch/tree/master/mnist_dcgan.
  - Un dossier comportant les poids pour différents modèles entrainés :
      -  "" contient les poids d'un DCGAN de dimension 2 et de fonction d'activation ReLU
      -  "" contient les poids d'un DCGAN de dimension 100 et de fonction d'activation ReLU
      -  "" contient les poids d'un DCGAN de dimension 200 et de fonction d'activation ReLU
      -  "" contient les poids d'un DCGAN de dimension 100 et de fonction d'activation Tanh

- le dossier `VAE` comporte : 
  - Un jupyter notebook (`VAE.ipynb`) pour entrainer un VAE et visualiser les images générées, les interpolations linéaires et sphériques ainsi qu'une pojection T-SNE d'un modèle au choix. Le code du VAE est inspiré du gitub https://github.com/csinva/gan-vae-pretrained-pytorch/tree/master/mnist_vae.
  - Un jupyternotebook (`VAE_interactif.ipynb`) qui utilise un modèle de VAE pour effectuer une représentation interactive de l'espace latent.
  - Un dossier `Models` comportant les poids pour différents modèles entrainés


## Modèle interactif d'exploration du VAE
<p align="center">
  <img src="https://user-images.githubusercontent.com/73143008/166080801-4e44d55e-1fa0-4807-89cc-f79209de9199.gif" width="800" height="600" />
</p>
