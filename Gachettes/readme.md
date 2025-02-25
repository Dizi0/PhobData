# Modifications des gâchettes pour manette GameCube

## ⚙️ Difficulté : Facile à Moyenne
⏳ Durée estimée : 5 - 20 minutes (selon l'option choisie)

## Introduction

Les gâchettes de la manette GameCube ont une course relativement longue, ce qui peut être un inconvénient pour les jeux nécessitant des inputs rapides et précis. Heureusement, plusieurs solutions existent pour **raccourcir leur course et améliorer la réactivité**.

Ce guide présente **trois principales options** pour modifier vos gâchettes en fonction de vos besoins :

> **⚠️ Remarque importante :** En fonction du comportement de gâchette souhaité, il est possible de **configurer sa PHOB** (notamment sur le mode 6) afin de garantir que la réponse des gâchettes soit conforme aux attentes. Référez-vous à la **documentation officielle de la PHOB** pour les détails de configuration : [Guide de calibration PHOB](https://github.com/PhobGCC/PhobGCC-doc/blob/main/For_Users/Phob_Calibration_Guide_Latest.md#analog-trigger-modes-ab--lr).

---
## 1️⃣ Gâchettes raccourcies avec des **Short Trigger Plugs**

🔗 [Short Trigger Plugs STL](https://github.com/FIRESCustom/GCC_Trigger_Plugs/blob/master/FIRES%20SHORT%20Trigger%20Plugs%20v7.STL)

### Présentation
Cette modification permet de **réduire légèrement la distance** que la gâchette doit parcourir avant d’atteindre le clic final. Elle offre un bon équilibre entre réactivité accrue et conservation des fonctionnalités d'origine.

### Installation
1. **Démonter la manette** et accéder aux gâchettes.
2. **Insérer les Short Trigger Plugs** imprimés en 3D.
3. **Tester et ajuster** si nécessaire.
4. **Remonter la manette** et vérifier en jeu.

✅ Réduction de la course sans altérer le fonctionnement global.  
✅ Compatible avec toutes les gâchettes GameCube.

---
## 2️⃣ Gâchettes raccourcies avec des **Long Trigger Plugs**

🔗 [Long Trigger Plugs STL](https://github.com/FIRESCustom/GCC_Trigger_Plugs/blob/master/FIRES%20LONG%20Trigger%20Plugs%20v7.STL)

### Présentation
Cette option **élimine complètement la distance** avant d’atteindre le clic, rendant la gâchette instantanée. Toutefois, cela **désactive le Light Shield sur Melee**, ce qui peut être un inconvénient selon votre utilisation.

### Installation
1. **Démonter la manette** et retirer les gâchettes.
2. **Insérer les Long Trigger Plugs** pour bloquer toute distance avant le clic.
3. **Ajuster via le Debug Mode Phob** si nécessaire.
4. **Remonter la manette** et tester en jeu.

✅ Réactivité maximale pour les inputs instantanés.  
⚠️ **Désactive le Light Shield sur Melee**.  
⚠️ Peut nécessiter un réglage spécifique via **Debug Mode Phob**.

---
## 3️⃣ Gâchettes optimisées pour **switches de souris**

🔗 **Nécessite l'achat de** [StarPaddle](https://github.com/PhobGCC/PhobGCCv2-HW/releases/tag/v2.0.5)

### Présentation
Cette modification **nécessite des outils, de la patience et d’être à l’aise avec le bricolage**. Elle est plus complexe mais permet d'obtenir **une réactivité extrême**, proche des boutons de souris.

En plus des **triggers plugs allongés**, cette option remplace complètement le système d’origine par **des switches de souris**, assurant une activation ultra-rapide.

### Installation (ordre optimisé)
1. **Se procurer les pièces nécessaires** :
    - [Imprimez les fichiers 3D](https://github.com/adorablesoft/gcc-triggermodbrackets/tree/main/Mouseclick) : mcbracketleftv3spring, mcbracketrightv3spring, SlimGuardLeft et SlimGuardRight.
    - Acheter les **switches de souris** et le **StarPaddle**.
2. **Démonter la manette** et retirer les gâchettes d’origine.
3. **Installer les triggers plugs adaptés** et fixer les supports imprimés en 3D.
4. **Configurer le Debug Mode Phob** pour un calibrage précis.
5. **Tester en jeu et ajuster si nécessaire**.

✅ Idéal pour les joueurs recherchant **une activation ultra-rapide**.  
✅ Offre un clic mécanique précis similaire aux boutons de souris.  
⚠️ **Requiert du matériel spécifique et une installation minutieuse**.  
⚠️ **Nécessite un calibrage précis via Debug Mode Phob**.

---
## Conclusion

En fonction de votre besoin et de votre style de jeu, vous pouvez choisir parmi ces trois modifications :
- **[Short Trigger Plugs](https://github.com/FIRESCustom/GCC_Trigger_Plugs/blob/master/FIRES%20SHORT%20Trigger%20Plugs%20v7.STL)** : Réduction légère de la course, facile à installer.
- **[Long Trigger Plugs](https://github.com/Dizi0/PhobData/blob/main/Gachettes/EXTRA%20LONG%20Trigger%20Plugs%20v1.stl)** : Suppression totale de la course, idéale pour les inputs instantanés (⚠️ désactive le Light Shield).
- **[Triggers Plugs pour switches de souris](https://github.com/Dizi0/PhobData/blob/main/Gachettes/EXTRA%20LONG%20Trigger%20Plugs%20v1.stl)** : Solution la plus réactive, mais **difficile à mettre en place**, nécessitant du matériel supplémentaire (Vérifiez que vous ayez bien des supports **[Star Paddles](https://github.com/PhobGCC/PhobGCCv2-HW/releases/tag/v2.0.5)**).

Si vous souhaitez explorer d'autres améliorations, consultez nos guides sur les **switches ABXY**, le **D-Pad indépendant** et les **capteurs à effet Hall** pour une personnalisation optimale de votre manette GameCube !