# Mise en place d'un portfolio via un fichier `README` à votre compte  GitHub

Voici l'extrait d'une petite conversation avec **ChatGPT** :

![Définition Github par Chat GPT](./images/GitHubByGPT.png "Définition Github par Chat GPT")

Vous allez donc commencer par créer votre compte GitHub.

Pour cela, rendez-vous sur le site officiel : <https://github.com/>

**Si vous avez déjà un compte github**, vous pouvez passer diretement à l'étape 2, mais avant vous devez absolument **ajouter votre adresse universitaire** à votre compte (il peut y avoir plusieurs adresses mails associées à un même compte).  
Pour cela, une fois connecté à Github, dans la liste des icônes en haut à droite, cliquez sur l'**icone ronde de votre compte** afin de pouvoir sélectionner le menu **`Settings`**.  
Une fois, le menu **`Settings`** ouvert, allez dans la rubrique **`Email`** et dans **Add email address** pour ajouter votre adresse universitaire en `etu.unilim.fr`

## 1. Créer un compte Github

**Si vous n'avez pas encore de compte github**, inscrivez-vous avec votre **adresse email universitaire**, cela vous permettra d'avoir des **avantages** avec le programme Github Education que nous rejoindrons d'ici quelques lignes ;-)

![Définition Github par Chat GPT](./images/emailSignUp.png "Définition Github par Chat GPT")

Et laissez-vous guider :

- Votre **email** doit être votre mail universitaire
- Votre **mot de passe** (**password**) doit être correctement sécurisé 😉
- Votre **identifiant** (**username**) ne doit pas être exotique. Une bonne pratique est de choisir comme username l'initiale de votre prénom suivi de votre nom en minuscule : c'est pour cela que mon username est **iblasquez** 😉
- Vous choisissez votre **préférence concernant l'envoi d'éventuelles annonces par mail**
- Vous devez ensuite **résoudre une énigme pour vérifier que vous n'êtes pas un robot**

…. Et il est enfin temps de cliquer sur le bouton **create account**
et de consulter votre **mail universitaire** pour récupérer le **code à saisir** 😉

<!--Comme le montre la copie d'écran ci-dessous, indiquez ensuite que vous êtes **seul** et que vous êtes **étudiant** :

![utilisation seul et en tant qu'étudiant](./images/meStudent.png "Utilisation seul et en tant qu'étudiant")

Cochez les **fonctionnalités  (features)** qui vous intéressent  (pourquoi pas toutes les features 😉)

![Liste des fonctionnalités à cocher](./images/features.png "Liste des fonctionnalités à cocher")

Vous découvrez alors ce que vous permet votre compte Github :

![Caractéristiques du compte Github](./images/githubAccount.png "Caractéristiques du compte Github")

A cette étape-là, il est intéressant de cliquer sur **`Apply for your Github student benefits`**

Vous arrivez sur la page <https://education.github.com/pack>-->

## 2. Rejoindre le programme Education de Github

**Une fois le compte créé, cliquez sur le lien suivant :
<https://education.github.com/pack>**

Vous voyez sur cette page tous les outils auxquels vous pourrez avoir accès gratuitement en tant qu'étudiant (et notamment les fameux profuits de la suite JetBrains : IntelliJ pour Java, PhpStorm pour php, ...)

Pour cela il ne vous reste plus qu'à cliquer sur le bouton suivant (**`Sign up for Student Developer Pack`**)

![Bouton sign up for Student Developer Pack](./images/signUpButtonStudentDP.png "Bouton sign up for Student Developer Pack")

puis cliquer sur le bouton vert **`Start an application`**

Et continuer à suivre les consignes ...

`Pending` signifie que votre adhésion au programme Github Education est ***en attente***.  
Votre adhésion au programme Github Education ne sera effective que lorsque vous verrez ***`Approved`***.  
Si vous voyez *`Denied`*, vous devez **consulter votre mail universitaire** pour savoir quelle manipulation vous devez effectuer sur votre compte github pour que votre adhésion puisse être acceptée (bien souvent vous devez mettre en place une double authentification, écrire de manière explicite votre prénom et nom dans votre profil, renseigner des informations dans Billing, etc ...)
Une fois les erreurs indiquées dans le mail corrigées, vous devez relancer une demande et recommencer le processus jusqu'à ce que votre **`Pending`** se transforme en **`Approved`**.

## Bien vérifier que vous avez rejoint le programme Github Education

Dans la liste des icônes en haut à droite, cliquez sur l'**icone ronde de votre compte** afin de pouvoir sélectionner le menu **`Settings`**.  
Une fois, le menu **`Settings`** ouvert, allez dans la rubrique **`Access`** et ouvrir **`Billing and licensing`**.
A la fin de la rubrique **`Billing and licensing`**, cliquez sur **`Education benefits`** : c'est là que vous pouvez vérifier que votre inscription à Github Education a bien été ***`Approved`***.

## 3. Personnaliser le profil de votre compte Github

### 3.1 Créer un nouveau repository (dépôt)

Maintenant, vous allez personnaliser le **profil de votre compte github**.

Pour cela, vous devez **créer un nouveau dépôt**.  
Sous Github on parle de **dépôt** (en français) ou de **repository** (en anglais).

Pour cela, dans la liste des icônes en haut à droite, cliquez sur  l'icône  **`+`** puis sur **`New repository`**.

![New repository](./images/newRepository.png "New repository")

Vous allez créé un repository spécial.

- **le nom de ce repository doit strictement être identique au nom de votre compte github.**  
Si vous avez bien nommé votre repository, Github vous indiquera surement par le message suivant qui indique pourquoi ce repository est un repository spécial :

*`votreCompte/votreDepotNommeCommeVotreCompte` is a ✨ *special* ✨ repository because its `README.md` (this file) appears on your GitHub profile.*

- Vérifiez que ce repository soit bien **`Public`**.

- Faites en sorte que **`add a README file`** soit bien activé (**ON**).

- Terminez par **`Create repository`**.

![Create a new repository](./images/createNewRepository.png "Create a new repository")

### 3.2 Ajouter un `README` *préformaté* à ce repository special

Cliquez maintenant à droite sur le bouton vert **EDIT README** pour ajouter un fichier `README` *préformaté* et arriver sur la vue **Edit** qui devrait afficher en **Markdown** un contenu similaire au contenu suivant.

```markdown

### Hi there 👋

- 👋 Hi, I'm @iblasquez
- 👀 I'm interested in ...
- 🌱 I'm currently learning ...
- 💞️ I'm looking to collaborate on ...
- 📫 How to reach me ...

<!---
iblasquez/iblasquez is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

```

- Notez bien qu'en markdown **`<!--`** et **`-->`** permettent de mettre du texte en **commentaires**.

Dans le `README` que vous avez sous les yeux, vérifiez bien que le texte que vous voulez afficher n'est pas entre **`<!--`** et **`-->`** si vous voulez le voir s'afficher dans votre profil.

### 3.3 Enregistrer les modifications apportées au `README`

 Complétez le texte écrit dans le `README` en le personnalisant avec vos informations personnelles.

 Pour ***enregistrer*** le contenu (et/ou les modifications apportées à ce fichier), vous devrez cliquer sur le bouton  à droite de votre écran :

![Bouton Commit changes](./images/commitChanges.png "Bouton Commit changes")

> 📢 Le commit est un ***enregistrement*** un peu spécial comme vous le verrez dans le cours sur les gestionnaires de version, qui **doit absolument contenir un message** qui indique ce qui est *commité* 📢

![Commit initial](./images/commitInitial.png "Commit initial")

- Une fois le message de commit correctement renseigné, vous pouvez cliquer sur **`Commit changes`**.

## 4. Visualiser le profil de votre compte Github

Votre profil est maintenant visible pour tout internaute arrivant sur votre compte github c-a-d sur la page : **`https://github.com/votrenomutilisateur`**  

Depuis votre compte, vous pouvez afficher rapidement cette page à tout moment en procédant de la manière suivante : cliquez sur l'**icone ronde de votre compte** et sélectionnez le menu **`Profile`** qui vous amènera directement à l'adresse **`https://github.com/votrenomutilisateur`**

Par exemple, mon profil est visible sur <https://github.com/iblasquez> comme premier contenu de cette page, tout comme le vôtre sur votre page 😉

![Mon Portfolio](./images/myPortfolio.png "Mon Portfolio")

## 5. Mettre à jour le profil de votre compte Github à la manière d'un portfolio

### 5.1 Editer votre `README`

Pour mettre à jour votre profil, cliquez sur **Repositories** dans la barre de menu en haut à gauche pour visualiser tous les repos que vous avez créés.
Cliquez sur le repo qui contient votre profil (celui que nous venons juste de créer et qui porte le même nom que votre compte).  

Vous voyez le `README`, pour modifier son contenu, cliquez sur le petit stylo pour entrer dans le mode d'edition du `README`.

### 5.2 Voir le code d'un `README` existant

Vous ne savez pas quoi mettre dans votre `README`, inspirez-vous d'un `README` existant.

Par exemple allez sur le profil suivant <https://github.com/njacquet87>

- Cliquez sur le menu **Repositories**.
Comme vous savez maintenant que le profil se trouve dans un dépôt qui a le même nom que le compte, dans la recherche `Find a repository`, tapez **`njacquet87`**

- Cliquez sur le repository **`njacquet87`** pour l'ouvrir.

- Cette fois-ci, ne cliquez pas sur le stylo !!!
Mais cliquez sur `README.md`.  
Vous voyez alors 3 boutons :  **Preview**, **Code** et **Blame**.

- Cliquez sur **Code** pour visualiser le code Markdown écrit dans ce fichier `README` et vous en inspirer.

Pour meettre à jour votre profil, il ne vous reste plus qu'à être créatif et/ou de vous inspirer de profils déjà existants sur github, comme par exemple ceux d'(anciens) étudiants de DUT/BUT Informatique :

- <https://github.com/njacquet87>
- <http://github.com/GamoTune>
- <https://github.com/Anton-Hladyshev>
- <https://github.com/Vexcited>
- <https://github.com/Rayzeq>
- <https://github.com/hugoheml>
- <https://github.com/AzarioCossa>
- <https://github.com/Axel230303>
- <https://github.com/fortyup>  
- <https://github.com/Maksew>
- <https://github.com/gaiailou>
- <https://github.com/NeikoStream>
- <https://github.com/nelpats>
- <https://github.com/ByrmGkcn>
- <https://github.com/ThomasBreil>
- <https://github.com/Anthony-AUDOIN>
- <https://github.com/FredericCanaud>

- Ou de professionnels :

  - <https://github.com/ythirion>
  - <https://github.com/k33g>
  - <https://github.com/SelimHorri>
  - <https://github.com/anmol098/anmol098>
  - <https://github.com/aatwi>

- et tous ceux que vous trouvez intéressant lors de votre navigation sur Github ...

### 5.3 Utiliser un générateur de profil Github

Pour personnaliser votre profil github, vous pouvez aussi, si vous le souhaitez, utiliser un générateur de profil.  

Par exemple, n'hésitez pas jeter un petit coup d'oeil à **GPRM : GitHub Profile ReadMe Maker** à l'adresse suivante : <https://gprm.itsvg.in/> et à jouer avec 😉

### 5.4 D'autres ressources pour personnaliser son profil Github

- La documentation Github Education sur le profil README : <https://education.github.com/experiences/launchpad_profile_readme>

- Sous Github, les dépôts intitulés ***`awesone`*** regroupent de nombreux liens vers d'autres dépôts sur une thématique donné.  
Ainsi un dépôt nommé **`awesome-github-profile-readme`** regroupera un certain nombre de liens vers des ressources ou des `README` inspirants.  
C'est le cas par exemple pour le dépôt suivant : <https://github.com/abhisheknaiidu/awesome-github-profile-readme>

- Quant aux ressources pour personnaliser vos profils, vous pouvez :

  - récupérer des icones sur : <https://simpleicons.org/>
  - faire des badges sur : <https://shields.io/>

- Pour en savoir plus sur le Markdown :

  - une présentation rapide du markdown : <https://docs.framasoft.org/fr/grav/markdown.html>
  - une présentation plus détaillée sur la documentation Github en consultant les rubriques suivantes :
    - Prise en main de la rédaction et de la mise en forme sur GitHub : <https://docs.github.com/fr/get-started/writing>
    - Utilisation de la mise en forme avancée : <https://docs.github.com/fr/get-started/writing-on-github/working-with-advanced-formatting>

L'article suivant **Comment se créer un portfolio avec le `README` GitHub** a des références intéressantes et pourrait également vous aider :  
<https://talks.freelancerepublik.com/comment-se-creer-un-portfolio-avec-le-readme-github/>
