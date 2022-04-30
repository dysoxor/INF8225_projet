# INF8225_projet

Projet d'intelligence artificielle du cours INF8225 à Polytechnique Montréal.

Auteurs : Augustin BARRUOL, Ilan BASTA, Lamia SALHI, Andrey SOBOLEVSKY


Ce GitHub est composé de 2 dossiers :

- le dossier `DCGAN` comporte : 
  - Un jupyternotebook pour entrainer un DCGAN et visualiser les images générées, les interpolations linéaires et sphériques ainsi qu'une pojection T-SNE       d'un modèle au choix. Le code du DCGAN est inspiré du github https://github.com/csinva/gan-vae-pretrained-pytorch/tree/master/mnist_dcgan.
  - Un dossier `DCGAN_models ` comportant les poids pour différents modèles entrainés :
      -  `output_ReLU_2D` contient les poids d'un DCGAN de dimension 2 et de fonction d'activation ReLU
      -  `output_ReLU_100D` contient les poids d'un DCGAN de dimension 100 et de fonction d'activation ReLU
      -  `output_ReLU_200D` contient les poids d'un DCGAN de dimension 200 et de fonction d'activation ReLU
      -  `output_tanh_100D` contient les poids d'un DCGAN de dimension 100 et de fonction d'activation Tanh
      -  `output_sigmoid_100D` contient les poids d'un DCGAN de dimension 100 et de fonction d'activation Sigmoïde
  
  **Il est à noter que les chemins permettant de charger les modèles que nous avons entraîné doivent être mis à jour selon le chemin dans lequel vous téléchargerez les modèles.**
  -  Le fichier lenet.py définissant un classifier pour la base de donnée MNIST ainsi que les poids lenet_epoch=12_test_acc=0.991.pth pour un modèle pré-     entrainé pris du GitHub https://github.com/harit7/torch-fl/tree/baea1e013267d564620cc17fe6f99589018417ee/src/models

- le dossier `VAE` comporte : 
  - Un jupyter notebook (`VAE.ipynb`) pour entrainer un VAE et visualiser les images générées, les interpolations linéaires et sphériques ainsi qu'une pojection T-SNE d'un modèle au choix. Le code du VAE est inspiré du gitub https://github.com/csinva/gan-vae-pretrained-pytorch/tree/master/mnist_vae.
  - Un jupyternotebook (`VAE_interactif.ipynb`) qui utilise un modèle de VAE pour effectuer une représentation interactive de l'espace latent.
  - Un dossier `Models` comportant les poids pour différents modèles entrainés. Il est à noter que les chemins permettant de charger les modèles que nous avons entraîné doivent être mis à jour selon le chemin dans lequel vous téléchargerez les modèles.
  - Le fichier lenet.py définissant un classifier pour la base de donnée MNIST ainsi que les poids lenet_epoch=12_test_acc=0.991.pth pour un modèle pré-     entrainé pris du GitHub https://github.com/harit7/torch-fl/tree/baea1e013267d564620cc17fe6f99589018417ee/src/models


## Modèle interactif d'exploration du VAE
<p align="center">
  <img src="https://user-images.githubusercontent.com/73143008/166080801-4e44d55e-1fa0-4807-89cc-f79209de9199.gif" width="800" height="600" />
</p>
