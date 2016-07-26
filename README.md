Zap Freebox
===========

http://github.com/kilbith/zap-freebox

Description
-----------

Simple menu dans le terminal pour visionner les chaînes TV proposées par la Freebox à l'aide de VLC.

Capture d'écran
---------------

![Screenshots](http://i.imgur.com/GaXcOxM.png)

Installation
------------

Dépendances :

  * VLC
  * curl
  * whiptail (inclus dans la librairie `newt`, dont NetworkManager utilise)

Téléchargez l'archive :

    git clone https://github.com/kilbith/zap-freebox.git

Enfin, exécutez le script :

    cd zap-freebox
    ./zapper

Problèmes
---------

VLC s'exécutant en tâche de fond, il est préférable de clore la vidéo via le menu de Zap Freebox (`Quitter`).

