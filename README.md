# js-node-project-boilerplate
Apprendre à se servir de npm et de nodejs

## Faire un génèrateur de projet

**BUT :** Faire un programme qui génère un dossier de projet complet en éxécutant une ligne de commande

La ligne de commande final pourrait ressembler à ça:

**```node monprogram.js chemindudossier```**

### Le dossier doit contenir :
* un dossier js
* un dossier css
* un fichier index.html
* un fichier js/index.js
* un fichier css/style.css

NB : vous pouvez adapter votre arborescence à vos besoin quotidien.

### Librairies internes utiles :

> *ces librairies sont internes, c'est à dire qu'elles sont présentes dans le 'core' de nodejs*

* [process](https://nodejs.org/api/process.html)
* [path](https://nodejs.org/api/path.html)
* [console](https://nodejs.org/api/console.html)
* [fs](https://nodejs.org/api/fs.html)
* [globals](https://nodejs.org/api/globals.html)

NB : Cette liste est à titre indicatif. D'ailleurs la plupart des packages présent dans cette liste peuvent remplacer par les packages externes ci-dessous.

### Librairies externes utiles :

> *ces librairies sont externes, c'est à dire que vous devez installer ses libs via npm install ...*

* https://github.com/substack/minimist
* https://github.com/jonschlinkert/write
* https://github.com/substack/node-mkdirp
* https://github.com/zeekay/executive
* https://github.com/sindresorhus/opn
* https://github.com/chalk/chalk (pour les couleurs)

NB : Cette liste est à titre indicatif. Lisez bien leurs description et éventuellement leur documentation afin de comprendre à quoi elles pourrait vous servir dans la réalisation du présent exercice.

### Les étapes : 

  1. créer votre projet sur github OU bitbucket
    * avec un README.md
    * avec un .gitignore => nodejs

  2. créer votre dossier

      ```

      git clone https://...

      ```

  3. accéder à votre projet sur votre machine

      ```

      cd votredossier

      ```

  4. créer votre fichier program.js

      ```

      touch program.js

      ```

  5. ouvrir Atom

      ```

      atom .

      ```

  6. Tester votre environnement en écrivant votre première ligne dans votre program.js

    ```

      console.log('bonjour');
    ```

  7. Réfléchissez et écrivez les ordres vous allez donner à votre programmme afin qu'il lise le chemin passé en paramètre et qu'il écrive dans le dossier correspondant au chemin, les dossiers et fichiers demandés
  
  8. Étudiez les librairies internes et externes qui pourraient vous aider à atteindre votre but.

  9. installer les librairies choisies, par exemple :

      ```
      
      npm i -s minimist write mkdirp executive opn chalk

      ```

  10. écrivez votre programme
