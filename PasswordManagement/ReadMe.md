# Gestion des mots de passe

## Questions

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

2. __Parce que les mots passe doivent être FORT__
> Les attaques les plus fréquente sont basé soit sur l'utilisation de dictionaires, soit sur l'utilisation de technique de "brute-force" qui consiste à essayer des combinaison aléatoire de mot. Il va sans dique que les mot de passe fabrique à partir de prénom des enfant et des date de naissant "à l'envers" sont extrèmement vulnérable.   
 => A proscrire donc !!!  

 > Il est crucial de disposer de mot de passe à la fois LONG et HETEROGENE.  
 => Ce qui implique un mélange de Majuscules, Minuscule, Chiffres et Symbôles (= Caractères "Spéciaux") !

3. __Parce que les mots de passe doivent être UNIQUES__
> De nombreux sites web, et en particulier les sites qui gère de l'argent ou qui pemettent de faire des achats font l'objet d'attaques ciblées permanentes, mais ce ne sont pas les seuls ...    
... en effet, les pirates informatiques essayent aussi d'attaquer des sites "à priori peu sensibles" uniquement dans le but de récupérer des données personnelles d'utilisateurs qui seront ensuite revendus à bon prix sur le "dark net" à d'autres pirates qui eessayerons à leur tour d'utiliser les informations récupérées et de les tester sur des sites plus critiques.   

> C'est pourquoi il est crucial de ne __PAS__ réutiliser 2 fois le même mot de passe pour ses comptes "en ligne"


### Comment ?
A. Installer un gestionnaire de mot de passe votre l'ordinateur   
> (Optionellement : Installer ce même gestionnaire de mot de passe votre smartphone)  

B. Installer le plusgin correspondant dans votre navigateur préféré (Safari, Firefox, Brave, ...)  

## Réponses
Cette section est relatives aux différents types d'informations que votre gestionnaire de mot de passe à besoin pour être vraiement efficasse ...

### Informations Clefs
Il s'agit des informations absoluement nécessaires pour pouvoir gérer vos mots de passe !   
> Elles sont au nombre de 4

En bref, il s'agit de :
- Le __Titre__ (Label) 
- L'__Adresse du Site__ (Web Site) 
- Le __Nom d'Utilisateur__ (Username)
- Le __Mot de Passe__ (Password)

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
            <td>Adresse du Site</td>
            <td>Equivalent d'une adresse postale, mais pour le "cyber-espace".</td>
            <td>Il s'agit d'une "URL" (= Unified Resource Locator).</td>
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

### Informations Complémentaires
Les informations complémentaires peuvent être diverses et variées ...   
... mais traditionellement ont retrouve les informations suivantes :
- Question(s) Secrête(s) : 1 (ou plusieurs) question(s) permettant de re-initialiser le mot de passe en cas de perte
- Réponse(s) Secrête(s) : Réponse(s) associée(s) à la (aux) question(s)
- TOTP (Time-based One-Time) : Code à usage unique permettant de se connecter au compte Internet (Surtout utilisé par les site web en lien avec la gestion d'argent)

### Informations de Gestion
Les informations de gestion ne sont pas directement utile pour faire fonctionner le gestionnaire de mots de passe ...   
... mais elle peuvent servir pour organiser les différentes "fiches" (surtout lorsqu'il y en a beaucoup) !   
- Adresse e-mail associée : lorque le nom d'utilisateur n'est pas un e-mail, il peut être intéressant de noter l'adresse e-mail asssocié à ce compte Internet
- Catégorie : Permet de catégorisé les différentes fiches du gestionaire de mot de passe (généralement unique).
- Etiquette (Tag) : Permet de classifier les différentes fiches du gestionaire de mot de passe. (généralement multiple)/

### Illustration
Synthèse des différent types d'informations manipulé par un gestionnaire de mots de passe ...
![synthèse](https://github.com/iPlumb3r/About/blob/master/images/PasswordManagement_Informations.png)

## Périmètre
En __théorie__, les gestionnaires de mots de passe gèrent - comme leur nom l'indique - l'ensemble des mots de passe des comptes Internet (qui vous permettent d'avoir accès aux "espaces personnels" des organisations avec lesquelles vous êtes en contact) ...   
... mais en __pratique__ ils peuvent gérer de nombreux autres types d'information, comme par exemple : 
- Les mots de passe et codes de vos différents ordinateurs et smartphones (PIN, PUK, ICCID, ...)
- Les informations de vos cartes de crédits (vous permettant ainsi de remplir automatiquement les formulaires de payement des site de commerces en ligne)
- Les autres informations bancaires / monétaires / financières comme les RIB, les "graines crytographiques", ...
- Les informations d'état civil : CNI, Passeport, Permis de conduire, ...
- Les licences logicielles 
- Etc ...

## Fonctionnement
### Mode normal
Bla bla ...
### Mode dégradé
Bla bla ...

## Application(s)
Bla bla ...
