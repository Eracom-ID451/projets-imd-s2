---
layout: page
title: Publier web
permalink: publier-web.html
---

# Publication du spécimen sur le web

Instructions pour la publication des spécimens sur le web.

1. Installer Github Desktop:  
[https://desktop.github.com/download/](https://desktop.github.com/download/)

2. Installer Visual Studio Code.  
[https://code.visualstudio.com/](https://code.visualstudio.com/)

3. Créer votre compte sur Github.com.  
Indiquer votre *Username* [dans ce fichier Excel](https://eduvaud.sharepoint.com/:x:/r/sites/ERACOM_2526_ID451_Teams/Documents%20partages/Projets%20IMD/B-Specimens-Typo/Github-Usernames-ID451.xlsx?d=w1a132b2c1a5a41ad9365632f22aeb32e&csf=1&web=1&e=VBCPP5) 

4. Cloner le projet du site des specimens:  
[https://github.com/eracom/specimens-typo](https://github.com/eracom/specimens-typo)

5. Ouvrir le projet avec Visual Studio Code

6. Trouver votre dossier dans "s4/nom-de-la-typo"

7. Ajouter vos fichiers image (.webp ou .svg) dans ce dossier.

8. Editer votre fichier `index.html`.  
    - Remplacer tous les **EXEMPLE** par le nom de votre typo.
    - Remplacer l'image `exemple.webp` par votre image ou vos images.
    - Vérifier l'ordre des typos sur [https://specimens.eracom.ch/s4/](https://specimens.eracom.ch/s4/)
    - Remplacer les liens `/fonte-precedente/` et `fonte-suivante/` avec les liens corrects.

9. Publier vos changements avec Github Desktop. 
    - Commit
    - Push

FÉLICITATIONS, vous avez publié votre spécimen sur le web!

### Précisions

Pour l'image, voici la ligne à modifier:

```html
<img class="specimen" src="exemple.webp" alt="Spécimen EXEMPLE">
```