# Modifications des gâchettes pour manette GameCube

## ⚙️ Difficulté : Facile à Moyenne
⏳ Durée estimée : 5 - 30 minutes (selon l'option choisie)

## Introduction

Les gâchettes de la manette GameCube ont une course relativement longue, ce qui peut être un inconvénient pour les jeux nécessitant des inputs rapides et précis. Heureusement, plusieurs solutions existent pour **raccourcir leur course et améliorer la réactivité**.

Ce guide présente **trois principales options** pour modifier vos gâchettes en fonction de vos besoins :

> **⚠️ Remarque importante :** En fonction du comportement de gâchette souhaité, il est possible de **configurer sa PHOB** (notamment sur le mode 6) afin de garantir que la réponse des gâchettes soit conforme aux attentes. Référez-vous à la **documentation officielle de la PHOB** pour les détails de configuration : [Guide de calibration PHOB](https://github.com/PhobGCC/PhobGCC-doc/blob/main/For_Users/Phob_Calibration_Guide_v0.24.md#analog-trigger-modes).

---
## 📌 Navigation rapide
- [1️⃣ Gâchettes raccourcies avec Trigger Plugs](#1️⃣-gâchettes-raccourcies-avec-trigger-plugs)
- [2️⃣ Gâchettes optimisées pour switches de souris](#2️⃣-gâchettes-optimisées-pour-switches-de-souris)
- [⚙️ Configuration avancée avec PHOB](#configuration-avancée-avec-phob)
- [📚 Ressources supplémentaires](#ressources-supplémentaires)

---
## 1️⃣ Gâchettes raccourcies avec **Trigger Plugs**

🔗 [Short Trigger Plugs STL](https://github.com/FIRESCustom/GCC_Trigger_Plugs/blob/master/FIRES%20SHORT%20Trigger%20Plugs%20v7.STL)  
🔗 [Long Trigger Plugs STL](https://github.com/FIRESCustom/GCC_Trigger_Plugs/blob/master/FIRES%20LONG%20Trigger%20Plugs%20v7.STL)

### Présentation
Ces modifications permettent de **réduire ou supprimer la course** des gâchettes avant d’atteindre le clic final.
- **Short Trigger Plugs** : Réduction légère de la course tout en conservant le Light Shield.
- **Long Trigger Plugs** : Suppression totale de la course, offrant une réactivité maximale.

> **⚠️ Remarque :** Les **Long Trigger Plugs** ne sont **pas recommandés pour les manettes non PHOB**. Pour une meilleure compatibilité, il est recommandé de **passer la PHOB en mode 6 via le Debug Mode**.

### Installation
1. **Démonter la manette** et accéder aux gâchettes.
2. **Insérer les Trigger Plugs** imprimés en 3D.
3. **Tester et ajuster** si nécessaire.
4. **Remonter la manette** et vérifier en jeu.

✅ Réduction ou suppression de la course.  
✅ Compatible avec les gâchettes GameCube (⚠️ sauf Long Trigger sans PHOB).

---
## 2️⃣ Gâchettes optimisées pour **switches de souris**

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
## 📚 Ressources supplémentaires
- [🔗 Documentation PHOB](https://github.com/PhobGCC/PhobGCC-doc)
- [🔗 STL et autres fichiers de modification](https://github.com/Dizi0/PhobData)
- [🔗 Guide complet de calibration](https://github.com/PhobGCC/PhobGCC-doc/blob/main/For_Users/Phob_Calibration_Guide_v0.24.md#analog-trigger-modes)

Si vous souhaitez explorer d'autres améliorations, consultez nos guides sur les **switches ABXY**, le **D-Pad indépendant** et les **capteurs à effet Hall** pour une personnalisation optimale de votre manette GameCube !

