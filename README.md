# Modèle Three.js

Ce projet est un modèle `three.js` préconstruit qui permet de lancer rapidement un projet `three.js`. Il utilise `webpack` pour faciliter le développement et la construction du projet.

## Comment commencer

> [!IMPORTANT]
> Vous aurez besoin de [Node.js](https://www.python.org/) et [Git](https://git-scm.com/) installée sur votre système.

Pour commencer avec ce modèle, suivez les étapes ci-dessous:

1. Créez un nouveau dossier pour votre projet:
    ```cmd
    mkdir NameProject
    cd NameProject
    ```

2. Clonez le dépôt du modèle:
    ```cmd
    git clone https://github.com/xen0r-star/ModelThree.js.git
    ```

3. Copiez le contenu du modèle dans votre dossier de projet:
    ```cmd
    xcopy /s ModelThree.js\* .
    ```

4. Supprimez le dossier du modèle cloné:
    ```cmd
    rmdir /s /q ModelThree.js
    ```

5. Installez les dépendances du projet:
    ```cmd
    npm i
    ```

- command complète:
    ```cmd
    mkdir NameProject && cd NameProject && git clone https://github.com/xen0r-star/ModelThree.js.git && xcopy /s ModelThree.js\* . && rmdir /s /q ModelThree.js && npm i
    ```

## Commandes NPM

Ce modèle fournit les commandes NPM suivantes:

- `npm run dev`: Lance le serveur local pour le développement.
- `npm run build`: Construit le projet pour la production.

## Licence

Ce projet est sous licence MIT.

## Contact

Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une issue sur GitHub.

[@xen0r-star](https://github.com/xen0r-star) - Création et développement 
