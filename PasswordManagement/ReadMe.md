# Gestion des mots de passe ...
# ... avec un gestionnaire de mots de passe

## Questions / Réponses

### Quoi ?
Pouvoir gérer la __TOTALITE__ de ses mots de passe _"compliqués"_ ...   
... en n'ayant à retenir qu'un __UNIQUE__ mot de passe _"simple"_ !

### Pourquoi ?
1. __Parce qu'il y a maintenant vraiment TROP de mots de passe à se souvenir__
> Car la moindre relation avec une organisation, que se soit une société ou une association, 
un client, un fournisseur, un partenaire, une banque, une assurance, une coopérative, une mutuelle, ...   
... ou encore un simple site de commerce en ligne sur Internet vous ne manquerais pas de devoir 
créer un "compte" pour pouvoir accéder à votre "espace personnel" pour gérer votre relation
avec l'organisation en question.

> Et le compteur grimpe vite, très vite !   
=> Il n'est pas rare en effet de devoir gérer 20, 30, et voire 50 mots de passe ...   
... ou plus encore selon l'intensité de votre activité "Internet"

> NB : Il y fort a parier, que le jour viendra où cette "mécanique diabolique" sera inversée ...   
(se sera alors aux différentes organisations avec qui vous êtes en relation qui devront avoir "compte" chez vous)   
... mais ce jour n'est pas encore arrivé et pour l'heure il faut bien s'adapter à la situation actuelle si absurde soit-elle !!!

> Tous cela pour faire en sorte que la gestion des mots de passe nous simplifie la vie au lieu de nous la compliquer ...

2. __Parce que les mots de passe doivent être FORTS__
> Les attaques les plus fréquentes sont basées soit sur l'utilisation de dictionaires, soit sur l'utilisation de technique de "brute-force" qui consiste à essayer de nombreuses combinaisons aléatoire de mot à chaque seconde. Il va sans dire que les mots de passe fabriqués à partir des prénoms des enfants et de leurs dates de naissance (même "à l'envers" ;-) sont extrèmement vulnérables.   
 => A proscrire donc !!!  

 > C'est pourquoi il est crucial de disposer de mots de passe FORTS, c'est à dire à la fois LONGS et HETEROGENES.  
 => Ce qui implique un mélange de Majuscules, Minuscules, Chiffres et Symbôles (= Caractères "Spéciaux") !

3. __Parce que chaque mot de passe doit être UNIQUE__
> De nombreux sites web, et en particulier les sites qui gère de l'argent ou qui pemettent de faire des achats font l'objet d'attaques ciblées permanentes, mais ce ne sont pas les seuls ...    
... en effet, les pirates informatiques essayent aussi d'attaquer des sites "à priori peu sensibles" uniquement dans le but de récupérer des données personnelles d'utilisateurs qui seront ensuite revendus à bon prix sur le "dark net" à d'autres pirates qui eessayerons à leur tour d'utiliser les informations récupérées et de les tester sur des sites plus critiques.   

> C'est pourquoi il est crucial de ne __PAS__ réutiliser 2 fois le même mot de passe pour ses comptes "en ligne"


## Quel périmètre ?
En __théorie__, les gestionnaires de mots de passe gèrent - comme leur nom l'indique - l'ensemble des mots de passe des comptes Internet (qui nous permettent d'avoir accès aux __"espaces personnels__ des différentes organisations avec lesquelles nous sommes en contact) ...   
... mais en __pratique__ ils peuvent gérer de nombreux autres types d'information, comme par exemple : 
- Les mots de passe et/ou codes de nos différents ordinateurs et smartphones (PIN, PUK, ICCID, ...)
- Les mots de passe de certains logiciels installés sur nos ordinateurs et smartphones
- Les informations de nos cartes de crédits (vous permettant ainsi de remplir automatiquement les formulaires de payement des site de commerces en ligne)
- Les autres informations bancaires / monétaires / financières comme les RIB, les "graines crytographiques", ...
- Les informations d'état civil : CNI, Passeport, Permis de conduire, ...
- Les licences logicielles 
- Etc ...

![Scope](https://github.com/iPlumb3r/About/blob/master/images/PasswordManager_Scope.jpg)

## Quels types d'information ?
Cette section est relatives aux différents types d'informations qu'un gestionnaire de mot de passe à besoin pour être vraiment efficasse.
Il s'agit des types suivants : 
* __Informations Clefs__ : Obligatoires, elles représentent le "minimum syndical" d'une fiche de connection
* __Informations de Session__ : Optionelles, elles permettent de satisfaire au mécanisme d'authentification "à double facteur" imposé par certains sites
* __Informations de Récupération__ : Optionelles, ce sont les informations devant être fournies en cas de perte du mot de passe pour en générer un nouveau
* __Informations de Gestion__ : Optionelles, elles incarnent les données potentiellement associées à un espace personnel (e-mail, n° de tel, ...)

### Informations Clefs 
Elles sont au nombre de 4 :   
- Le __Titre__ (Label) 
- L'__URL de Connection__ (WebSite) 
- Le __Nom d'Utilisateur__ (UserName)
- Le __Mot de Passe__ (PassWord)

De mannière plus détaillé il s'agit de :

<table>
    <thead>
        <tr>
            <th>Information</th>
            <th>Description</th>
            <th>Commentaires</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Titre</td>
            <td>Brève description du compte Internet concerné.</td>
            <td>Il s'agit d'une simple chaîne de caractères qui permet de retrouver la "fiche" relative à ce compte Internet dans le gestionnaire de mots de passe.</td>
        </tr>
        <tr>
            <td>URL de Connection</td>
            <td>Equivalent d'une adresse postale, mais pour le "cyber-espace".</td>
            <td>URL = Unified Resource Locator.</td>
        </tr>
        <tr>
            <td>Nom d'Utilisateur</td>
            <td>C'est généralement une adresse e-mail, mais ce peut-être un n° de téléphone ou bien un n° de Sécu, ou tout autre chose ...</td>
            <td>Il s'agit d'une simple chaîne de caractères alpha-numérique ou numérique.</td>
        </tr>
        <tr>
            <td>Mot de Passe</td>
            <td>Mot "secret" associé à au nom d'utilisateur qui permet d'accéder au compte Internet concerné.</td>
            <td>Il s'agit d'une chaîne de caractères qui idéalement mélange majuscules, minuscules, chiffres et symboles.</td>
        </tr>
    </tbody>
</table>


### Informations de Session
- Code Calculé (Sur une base temporelle, généralement de 30 Secondes) : Code à usage unique permettant de se connecter au compte Internet. Surtout utilisé par les site web en lien avec la gestion de fonds "Fiat" ($EUR, $USD, ...) et/ou Crypto-Actifs($BTC, $USDT, ...)
> Généralement nommé "2FA Key" (Double Factor Authentication) ou TOTP (Time-based One-Time).

### Informations de Récupération
Les informations complémentaires peuvent être diverses et variées ...   
... mais traditionellement ont retrouve les informations suivantes :
- Question(s) Secrête(s) : 1 (ou plusieurs) question(s) permettant de re-initialiser le mot de passe en cas de perte
- Réponse(s) Secrête(s) : Réponse(s) associée(s) à la (aux) question(s)

### Informations de Gestion
Les informations de gestion ne sont pas directement utile pour faire fonctionner le gestionnaire de mots de passe ...   
... mais elle peuvent servir pour organiser les différentes "fiches" (surtout lorsqu'il y en a beaucoup) !   
- Adresse e-mail associée : lorque le nom d'utilisateur n'est pas un e-mail, il peut être intéressant de noter l'adresse e-mail asssocié à ce compte Internet
- Catégorie : Permet de catégorisé les différentes fiches du gestionaire de mot de passe (généralement unique).
- Etiquette (Tag) : Permet de classifier les différentes fiches du gestionaire de mot de passe. (généralement multiple)/

### Illustration
Synthèse des différent types d'informations manipulés par un gestionnaire de mots de passe ...   
![Info](https://github.com/iPlumb3r/About/blob/master/images/PasswordManagement_Info.jpg)


## Fonctionnement
Pour profiter au maximum du support d'un gestionnaire de mots de passe, il convient de systématiser l'enregistrement de chaque mot de passe dans cette "base de données" ...    
... et d'accepter au passager de renoncer à mémoriser le moindre mot de passe, ...   
... à l'exception de ceux qui ne peuvent pas être rempli automatiquement pas ce gestionaire.

> C'est à priori uniquement le cas :   
- des mot de passe "numérique" utilisé par les banques (car leur saisie ne peut se fire que via un "clavier virtuel numérique"
- de l'ID Apple qui sert à la fois pour l'Apple Store (Achats de musique, libre audio, applications, ...) et iCloud (Synchronicaiton de fichiers)

### Mode "Nominal"

__Mode "Tiré"__
Ce mode consiste à préalablement se positioner avec son navigateur Internet préféré sur l'URL de son espace personnel ...   

A ce point il est alors possible d'appeller le gestionnaire de mot passe via le bouton de son navigateur pour automatiquement :
- compléter le champ "Nom d'Utilisateur"
- compléter le champ "Mot de Passe"
- appuyer sur le bouton "Se Connecter / Login"

Et finalement se retrouver connecté à son "espace personnel" !

__Mode "Poussé"__
Ce mode consiste à contrario à rechercher l'espace personnel auquel on souhaite se connecter dans le gestionaire de mots de passe ...   

Une fois la bonne "fiche" trouvée, il suffit généralement de cliquer (ou double-cliquer en fonction des gestionnaires) sur l'URL pour enclencher un processus de connection similaire à celui présenté dans le mode "Tiré"

### Mode "Dégradé"
Dans certain cas de figure, les choses ne se passe pas comme décrit dans le mode "Nominal" 
> En effet, tous les site Internet ne respectent pas les _bonnes pratiques_ de connections ...
... et il est alors nécessaire de s'adapter au contexte particulier de la situation.

Les cas "dégradés" les plus fréquents sont :
- L'invite de connection ne s'affiche pas dans la fenêtre principale, mais dans une fenètre "pop-up"
- La connection s'effectue en 2 étapes
- Le nom d'utilisateur et ou le mot de passe est un nombre et il doit être saisisi via un clavier numérique virtuel

### Comment ?
A. Installer un gestionnaire de mot de passe votre l'ordinateur       
> Optionellement : Installer ce même gestionnaire de mot de passe votre smartphone.  

B. Installer le(s) plug-in(s) correspondant(s) dans votre(vos) navigateur(s) préféré(s) :    
> Safari, Firefox, Chrome, Brave, ...    

## Application(s)
Les applications suivantes sont vivement recommandés : 
- 1Password (Mac) : https://1password.com/ 
> Très convivial
- Enpass (Mac, Windows, Linux) : https://www.enpass.io/
> Nombreuses plateformes : Ordinateur et Smartphone   
> Nombreux modes de synchronication   
> Générateur de mots de passe avec de nombreuses "recettes"   
> Intégration du TOTP   
