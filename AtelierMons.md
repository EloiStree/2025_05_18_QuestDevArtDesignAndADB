
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

Git du groupe de Mons: https://github.com/EloiStree/2025_05_22_MonsCookieFactoryXR

---

## Jour 1

**Étape par étape** :
- [ ] Sortir les casques de leurs boîtes
- [ ] Comment on l'allume et comment on l'éteint
- [ ] Le bouton menu de la main droite
- [ ] Le menu principal et la connexion WiFi
- [ ] Faire son premier guardian en roomscale
- [ ] Activer et désactiver le guardian en mode développeur
- [ ] Installer SideQuest
  - [ ] Connecter le casque et menu unauthorized
  - [ ] Installer des applications ?
    - [ ] Installer MRTK, VRTK, XRTK
    - [ ] Installer Magic Room 24
  - [ ] Lancer les applications en sources inconnues depuis le Quest
  - [ ] Lancer et forcer l'arrêt depuis SideQuest
- [ ] Comment enregistrer une vidéo dans le Quest ?
  - [ ] Comment récupérer la vidéo depuis SideQuest ?
- [ ] SideQuest c'est pourri ;(
  - [ ] Stream l'image avec 2000:2000:0:0 de crop, 1024 Résolution et 10 images par seconde
- [ ] Téléchargeons SCRCPY pour voir si on peut pas faire mieux
- [ ] Utiliser SCRCPY et ADB sans `.bat`
  - [ ] Une commande de base `ADB devices -l`
  - [ ] Une commande de base `scrcpy`
  - [ ] Essayons de croper l'œil de gauche
  - [ ] Essayons d'avoir la caméra de notre téléphone
  - [ ] Essayons d'avoir la caméra du Quest3
  - [ ] On peut streamer l'écran en WiFi ?
    - [ ] Comment tuer le serveur ADB ?
- [ ] Geek time : On aurait pas une commande pour installer sur tous les casques en même temps ?
  - [ ] `adb -s install` et python
  - [ ] De fait, on peut pas lancer les jeux chez tous les joueurs en même temps ?
  - [ ] On pourrait pas les forcer à rester sur une application
    - [ ] Mode Kiosk version MDM https://arborxr.com/?
    - [ ] Aurait pas moyen avec ADB ?
- [ ] C'est quoi OBS ?
  - [ ] Ajouter la fenêtre de ADB ?
  - [ ] Utiliser un Shortcut pour lancer l'enregistrement facilement.

Exercice de fin d'atelier : En groupe de deux, lancer MRTK sur un casque et enregistrer des micro-séquences d'outils que vous trouvez stylés et que vous voudriez utiliser dans votre projet de demain.
Si on, vous, a fini plus tôt. Je vous invite à essayer d'installer des applications gratuites de SideQuest de refaire l'exercice sur ces applications.

---

# Jour 2

Premier objectif de la journée, prendre des mesures d'une partie du bâtiment de Technocité Mons.
Deuxième objectif, prototyper de manière filaire en groupe une usine à cookies fun et minimaliste avec les éléments de XRTK.
Via Git et le Package Manager dans un groupe de 12.

Rester sur du simple car c'est les développeurs qui en juillet continueront votre usine pour pratiquer XRTK.
Fournir des vidéos et de la documentation sur ce que vous demandez au développeur pour la partie de l'usine que vous implémentez.
(Vous êtes des GD, vous savez rédiger des bibles et GCD clairs 😉📕:RTFM.
Vous ne serez pas autorisés à rectifier le tir en classe en juillet.)

**Étape par étape** :
- [ ] Aller sur ce Git et créer un issue "Peux-tu m'ajouter"
  - [ ] https://github.com/EloiStree/2025_05_22_MonsCookieFactoryXR
- [ ] Sur le tableau répartissez-vous les mesures à faire durant la journée
- [ ] Installer MRTK, VRTK, XRTK depuis SideQuest et SCRCPY
  - [ ] https://youtu.be/GzbojUrInOg
- [ ] Essayer MRTK, VRTK, XRTK
  - [ ] https://github.com/EloiStree/2024_07_16_MonsXrDesign/releases/tag/V0/
  - [ ] MRTK https://www.youtube.com/watch?v=LKohEluBk4k
  - [ ] VRTK https://www.youtube.com/watch?v=Hm55CR_Ubjc
  - [ ] XRTK https://www.youtube.com/watch?v=eDicfcAgJB4
- [ ] Variante de cet exercice https://github.com/EloiStree/2025_05_18_QuestDevArtDesignAndADB/blob/main/StepByStep.md
- [ ] Tester rapidement les XRTK
- [ ] Tester rapidement au minimum un ou deux démos de MRTK
- [ ] Tester une première fois Open Brush pour découvrir.
  - [ ] Dessinez un brouillon filaire en 2-5 minutes max d'une des machines à cookies
    - [ ] Un gros "red button"
    - [ ] Structure a taille d adolescent 1.65m 
    - [ ] Une zone d'apparisions du cookie
  - [ ] Sauver et trouver le menu exporter
- [ ] Mesurer avec Open Brush la zone qui vous est attribuée
  - [ ] Ajouter au moins deux triangles d'accroche entre les pièces au début du scan
  - [ ] Importer les fichiers avec SideQuest sur votre PC
  - [ ] Tourner le glb en obj avec Blender
  - [ ] Pivoter et réhabiliter le mesh si vous connaissez un peu Blender
  - [ ] Créer un projet vide de "quarantaine" pour travailler sur le package git
  - [ ] Cloner les projets dans `Assets/P`
  - [ ] Dans `Assets/P/[nomdugit]/Team` ajouter votre `NOM_PRENOM`
  - [ ] Exporter dans Unity3D dans votre espace personnel `NOM_PRENOM` le scan de la pièce
  - [ ] Déposer votre objet dans la scène et créer lui un parent prefab `P_ROOM_MONS_NOM_CONTEXT`
    - [ ] C'est celui que votre intégrateur bougera de place
  - [ ] Créer un prefab en 0:0:0 avec une taille de 1:1:1 `ROOT_NOM_PRENOM`
  - [ ] Un petit Add Commit Pull Push sur Git avec CMD ou Fork et on essaie que tout le monde ait un scan.
  - [ ] On regarde en groupe comment rassembler les prefabs dans un prefab unique à drag and drop
  - [ ] Allez, temps de s'essayer au design de 1/12 de la machine à cookies.
    - [ ] Fabriquer tous une partie de l'étape de production d'une machine à cookies utilisant au moins 2 outils de VRTK.
    - [ ] Reproduire les étapes d'export de Open Brush vers le git de groupe.
  - [ ] Voila !!

Si tout se passe bien, en fin de journée on devrait avoir une esquisse d'une usine en filaire avec un peu de documentation et des vidéos pour les développeurs.

Le but ici est d'apprendre à utiliser sur les deux jours :
- [ ] Comprendre ce qu'est un Quest3 pour ceux qui n'auraient jamais testé
- [ ] ADB, SCRCPY, OBS, SideQuest, Open Brush pour esquisser du design VR
- [ ] Pratiquer le travail de groupe via Git en format package manager.
- [ ] Vous faire pratiquer une communication indirecte grâce à vos cours précédents.

En espérant que cet atelier vous plaise 😁🍪.
