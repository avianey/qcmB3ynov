# QCM Notation fin de cours

Merci de modifier ce fichier en cochant la (les) bonne(s) réponse(s).
Pour les questions sans choix, écrire directement en dessous de la question.
Pour cocher une case remplacer `- [ ]` par `- [x]`
Vous pouvez vous référer aux liens présent dans le README de https://github.com/avianey/SoundMeter

## QCM

  1. Quel(s) élément(s) est (sont) forcément présent(s) dans les _sources_ d'une application Android disposant d'une interface graphique : 
     - [ ] une class Activity
     - [ ] une class Application
     - [ ] une class Service
     - [ ] une class ContentProvider

  2. Classez les éléments ci dessous dans l'ordre dans lequel ils sont créés/instantiés par le Système lors du démarrage d'une application (du premier à être créé au dernier) : 
     - Activity 
     - Application
     - Fragment
     - ContentProvider

  3. Je souhaite crééer des éléments d'UI réutilisables au sein de mon application, quel(s) élément(s) parmis ceux ci dessous sont adapté(s) : 
     - [ ] une classe View personnalisée
     - [ ] une classe Activity personnalisée
     - [ ] une classe Service personnalisée
     - [ ] une classe Fragment personnalisée
     - [ ] un burrin et un marteau
     - [ ] une classe Drawable personnalisée
     - [ ] une classe AsyncTask personnalisée

  4. Parmis les possibilités suivants d'une Activity, le(s)quelle(s) est (sont) recommandée(s) à la gestion/sauvegarde/restauration de l'état des variables de mon activité : 
     - [ ] dans la méthode `onCreate` en utilisant le Bundle passé en argument
     - [ ] en utilisant une base de données et en y récupérant les données dans la méthode `onStart`
     - [ ] en utilisant un objet `SharedPreference` dans le constructeur de mon Activity
     - [ ] en utilisant un `ContentProvider` pour récupérer les données dans la méthode `onResume`

  5. Quelle(s) méthode(s) est (sont) adaptées pour résoudre les problèmes de partage d'une données entre composants d'UI ayant des cycles de vie indépendants (faire en sorte que la modification de la valeur soit répercutée dans tous les composants s'appuyant dessus pour l'affichage de leur UI) : 
     - [ ] Le reactive programming en utilisant la librairie Rx
     - [ ] un `java.lang.Observable` positionné au niveau de la classe Application
     - [ ] Utiliser un objet de type LiveData
     - [ ] Ne pas avoir des composants distincts s'appuyant sur la même donnée

  6. Laquelle (lesquelles) de ces affirmations concernant le AndroidManifest.xml est vraie : 
     - [ ] Je DOIT y déclarer TOUTES les activités de mon application
     - [ ] Je DOIT y déclarer TOUTES les permissions que je souhaite utiliser
     - [ ] C'est le seul endroit où je peux déclarer l'icône utilisée par mon application 
     - [ ] C'est le seul endroit où je peux indiquer le point d'entrée de mon application
     - [ ] Si je veux utiliser une classe Application personnalisée, je DOIT la déclarer à cet endroit
     - [ ] Je peux y définir des meta-données qui seront accessible dans mon application

  7. Le(s)quel(s) de ces éléments est (sont) généré(s) par le plugin gradle au moment du build de l'application : 
     - [ ] une classe `R` dans un package dont le nom correspond à la valeur de la clé `applicationId` de mon `build.gradle`
     - [ ] une classe `BuildConfig` dans un package dont le nom correspond à la valeur de la clé `applicationId` de mon `build.gradle`
     - [ ] une classe par fichier xml du répertoire `src/main/res/layout`
     - [ ] un entier permettant d'identifier de façon unique les vues de mes layout

  8. Comment dois-je m'y prendre pour afficher une interface graphique adaptable à des configurations d'écran différentes selon les téléphones (tailles, densité de pixels, formes), cocher les méthodes adaptées : 
     - [ ] Utiliser des répertoires de resources adaptés et y placer des images de tailles et formes différentes
     - [ ] Utiliser une classe Drawable personnalisée
     - [ ] Utiliser des VectorDrawable
     - [ ] Utiliser des Layout différents en fonction de la taille de l'écran

  9. Laquelle (lesquelles) de ces affirmations concernant une application quitté par son utilisateur est (sont) vraie(s) : 
     - [ ] les méthodes `onPause` de toutes les `Activity` déclarées dans le fichier `AndroidManifest.xml` sont appelées
     - [ ] les méthodes `onDestroy` de tous les `Service` actifs sont appelées
     - [ ] les méthodes `onStop` de toutes les `Activity` actives sont appelées
     - [ ] l'instance de la classe `Application` est supprimée
     - [ ] l'application met à jour son status Facebook

  10. Laquelle (lesquelles) de ces affirmations sont fausses (pour les téléphones récents) : 
      - [ ] N'importe quelle application Android peut accéder à la localisation GPS du téléphone sans que l'utilisateur en soit informé
      - [ ] N'importe quelle application Android peut accéder à la localisation GPS du téléphone en en informant l'utilisateur
      - [ ] N'importe quelle application peut connaitre approximativement la localisation du téléphone sans que l'utilisateur en soit informé
      - [ ] Je dois faire valider mon application par Google pour pouvoir accéder à la localisation de l'utilisateur dans mon application
      - [ ] Un téléphone Android c'est vachement mieux qu'un iPhone

  11. Firebase est un outil permettant de : 
      - [ ] D'obtenir des statistiques sur l'usage faite de mon application Android par les utilisateurs de celle-ci
      - [ ] De mettre à disposition mon application
      - [ ] De chercher des applications à télécharger pour mon téléphone
      - [ ] D'obtenir des analyses sur les problèmes liés à l'utilisation de mon application

  12. A quoi un `Intent` sert-il dans une application Android : 
      - [ ] à démarrer un `Activity`
      - [ ] à démarrer un `Service`
      - [ ] à arrêter un `Service`
      - [ ] à demander des mises à jour régulières au Système Android
      - [ ] à demarrer une autre Application sur le téléphone
      - [ ] à démarrer un `Fragment`

  13. Indiquez si les affirmations suivantes concernant les `layout` et `ViewGroup` sont vraies : 
      - [ ] Ce sont des endroits où les `View` se réunissent pour jouer à la belotte
      - [ ] Ils disposent d'un cycle de vie comme les `Fragment` et `Activity`
      - [ ] Je peux en crééer des personnalisés selon mes besoins
      - [ ] Ils peuvent eux même contenir des `layout` et `ViewGroup` qui eux même...

  14. Je souhaite copier le code d'une application open-source pour la modifier et en faire ma propre application à code source fermé, quelle(s) license(s) puis-je utiliser : 
      - [ ] MIT
      - [ ] Apache 2
      - [ ] GPL
      - [ ] LGPL
      - [ ] La license IV
      - [ ] BSD

  15. Qu'est-ce qu'`androidx` : 
      - [ ] Une faute de frappe
      - [ ] Un ensemble de librairies supplémentaires maintenue par Google pour faciliter le développement d'applications
      - [ ] La prochaine version d'Android
      - [ ] Le package qui regroupe les API obsolètes qui ne doivent pas être utilisées par les développeurs d'applications

## Questions libres

  1. Je souhaite lancer un téléchargement volumineux en permettant à l'utilisateur de continuer d'utiliser mon application ou de la quitter, sans que le téléchargement ne soit interrompu ni que l'utilisateur ne soit bloqué sur une popup de chargement, comment devrais-je m'y prendre ?


  2. Si je devais refaire l'application du TP à partir de zéro, qu'est-ce que je changerais ??
