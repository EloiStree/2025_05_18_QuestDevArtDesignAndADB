
Bonjour à vous 😁.

Pour rester franc, je ne suis pas un game designer et je ne suis pas qualifié pour donner des cours de game design.
Maintenant, je suis dans la VR depuis le Quest DK1 et les Google Glass 🤗.

Cette année, grâce à l'accès à la caméra du Quest depuis mars 2025, toute la R&D va reposer sur l'utilisation des caméras pour des projets.
Et j'ai depuis vu des projets clients qui demandent :
- d'utiliser l'AR pour calibrer des zones de jeux
- de faire des jeux dans un bâtiment avec le guardian désactivé
- d'utiliser les AI sur les retours caméras
- d'utiliser Vuforia et OpenCV sur le flux de la caméra
- calibrer des multijoueurs utilisant Vuforia Like
- ...

Une très belle année pour trouver des stages et faire de la R&D en AR/XR.

L'atelier que je vous propose, si vous l'acceptez :
- Apprendre à utiliser ADB et SCRCPY pour installer et explorer à deux MRTK, VRTK et XRTK
- En groupe, prendre les mesures avec des points d'ancrage du bâtiment
- Pratiquer le travail de groupe sur Git via Open Brush pour un level designer via le package manager
- Trouver un level design basé sur les outils de XRTK que les développeurs devront implémenter durant leur atelier en juillet.


**La thématique de l'exercice est [🍪👵🏭](https://orteil.dashnet.org/cookieclicker/):**    
"Créer une usine à cookies en XR dans l'étage du bâtiment."  
[Comment sont fait des cookies ?](https://github.com/EloiStree/2025_05_18_QuestDevArtDesignAndADB/blob/main/HowCookieAreMade.md)  

**Note :** Attention ce sont les **développeurs**, avec **XRTK**, qui doivent implémenter le code derrière. Restez simple.


## Day 1

**Step by step**:
- [ ] Sortir les casques de leur boites
- [ ] Comment ton l allume et comment on l etain
- [ ] Le boutton menu de la main droite
- [ ] Le menu principale et la connection Wifi
- [ ] Faire son premier guardiant en roomscale
- [ ] Activer et desactiver le guardian en mode developpeur
- [ ] Installer SideQuest
  - [ ] Connecter le casque et menu unauthorized
  - [ ] Installer des applications ?
    - [ ] Installer MRTK, VRTK, XRTK
    - [ ] Installer Magic Room 24
  - [ ] Lancer les applications en source inconnues depuis le Quest
  - [ ] Lancer et forcer l arret depuis SideQuest
-  [ ] Comment enregistrer une video dans le Quest ?
  - [ ] Comment recuprer la video depuis SideQuest ? 
- [ ] SideQuest c est pourrit ;(
  - [ ] Stream l image avec 2000:2000:0:0 de crop, 1024 Resolut et 10 images par seconds 
- [ ] Telechargons SCRCPY pour voir si on peut pas faire mieux
- [ ] Utiliser SCRCPY et ADB sans `.bat`
  - [ ] Un commande de base `ADB devices -l`
  - [ ] Un commande de base `scrcpy` 
  - [ ] Essayons de croper l oeil de gauche
  - [ ] Essayons d avoir la camera de notre telephone
  - [ ] Essayons d avoir la camera du Quest3
  - [ ] On peut streamer l ecran en Wifi ?
     - [ ]  Comment tuer le server ADB ?
- [ ] Geek time: On aurait pas une command pour installer sur tout les casques en meme temps ?
  - [ ] `adb -s install` et python
  - [ ] De fait, on peut pas lancer les jeux chez tout les joueurs ne meme temps ?
  - [ ] On pourrait pas les forcers a rester sur une application
    - [ ] Mode Kiosk version MDM https://arborxr.com/?
    - [ ] Aurait pas moyen avec ADB ?
- [ ] C est quoi OBS?
  - [ ] Ajouter la fenetre de ADB ?
  - [ ] Utiliser un Shortcut pour lancer l enregistrement facilement.
     
Exercice de fin d atelier: En groupe de deux lancer MRTK sur un casque et enregistrer des micro sequences d outils que vous trouver styler et que vous voudriez utiliser dans votre projet de demain.
Si on, vous, a fini plus tot. Je vous invite a essayer d installer des applications gratuites de SideQuest de refaire l exercice sur ces applications.


# Day 2

Premier objectifs de la journer, prendre des mesures d une partie du batiement de Technocite Mons
Deuxieme objectifs prototyper de maniere fillaire en groupe une uzine a cookies fun et minimaliste avec les elements de XRTK.
Via Git et le Package Manager dans un groupe de 12.

Rester sur du simple car c est les developpeurs qui en Juillet continue votre uzine pour pratiquer XRTK.
Fournisser des videos et de la documentation sur ce que vous demander au developpeur pour la partie de l uzine que vous implementer.
(Vous etes des GD, vous savez rediger des bibles et GCD clair 😉📕:RTFM.
Vous ne serez pas authorizer a rectivier le tire en classe en Juillet. )


**Step by step**:
- Aller sur ce Git et creer un issue "Peux-tu m ajouter"
  - `Ajouter le git ici` 
- Sur le tableau repartister vous les mesures a faire durant la journee
- [ ] Installer MRTK, VRTK, XRTK depuis SideQuest et SCRCPY  
  - [ ] https://youtu.be/GzbojUrInOg  
- [ ] Essayer MRTK, VRTK, XRTK  
  - [ ] https://github.com/EloiStree/2024_07_16_MonsXrDesign/releases/tag/V0/
  - [ ] MRTK https://www.youtube.com/watch?v=LKohEluBk4k
  - [ ] VRTK https://www.youtube.com/watch?v=Hm55CR_Ubjc
  - [ ] XRTK https://www.youtube.com/watch?v=eDicfcAgJB4 
- https://github.com/EloiStree/2025_05_18_QuestDevArtDesignAndADB/blob/main/StepByStep.md
- Tester rapidement les XRTK
- Tester rapidement au minimum un ou deux demo de MRTK
- Tester un premier fois Open Brush pour decouvrir.
  - Dessinez un brouillons fillaire en 2-5 minutes max d une des machines a cookie
  - Sauver et trouver le menu exporter
- Mesurer avec Open Brush la zone qui vous ai attitre
  - Noublier pas d ajouter au moins deux points d accorche entre les pieces 

 

