# Tutoriel tensorflow
## Réalisation d'un perceptron multicouche et utilisation sur la base MNIST

La vidéo du tutoriel se trouve à l'adresse suivante:
https://www.youtube.com/watch?v=WeotsGN_138

Si vous souhaitez me soutenir: <https://fr.tipeee.com/l42-project>

Le code de cette vidéo est écrit pour la version 1.X de tensorflow (je recommande la version 1.13.1), pour l'installer, il suffit de taper la commande suivante :

`# pip install tensorflow==1.13.1`

ou la version GPU:

`# pip install tensorflow-gpu==1.13.1`

Pour utiliser ce programme, vous devez récuperer les fichiers MNIST sur le site suivant:
http://yann.lecun.com/exdb/mnist/
et les placer dans le repertoire ./mnist

La courbe d'erreur après 200 cycles d'apprentissage est la suivante :

![alt text](https://github.com/L42Project/Tutoriels/blob/master/Tensorflow/tutoriel1/graph_error.png)

Cet apprentissage prend environ 6 minutes sur une GeForce 1080

