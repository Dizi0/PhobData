# Diagnostic de manettes avec SmashScope

## Pré-requis
Pour diagnostiquer vos manettes, vous aurez besoin de trois choses :

1) **Une Wii**, OU un émulateur (**Dolphin**) avec votre adaptateur GC préféré.
2) **La ROM SmashScope**, trouvable ici : [SmashScope](https://compendium.dol-003.info/smashscope).
3) **Dans certains cas, un tournevis TryWing**, si vous devez démonter votre manette.

## Utilisation de SmashScope
Une fois la ROM lancée, vous aurez accès à trois menus :

### 1) Affichage des Inputs
Ce premier menu permet de voir les entrées de votre manette en temps réel. C'est un excellent outil visuel pour identifier rapidement un problème éventuel avec votre manette, qu'il s'agisse d'une **PHOB** ou d'une manette non modifiée.

### 2) Visualisation des Angles (Melee)
Ce second menu est principalement destiné à **Super Smash Bros. Melee**. Il permet d'observer la position du stick analogique afin de trouver les angles parfaits pour ajouter des **notches** à votre manette.
> **Note :** Ce guide étant axé sur **Smash Ultimate**, nous n'approfondirons pas cette section.

### 3) Oscilloscope et Analyse des Entrées
Ce dernier menu est **le plus utile pour notre diagnostic**. Ce module permet d'analyser en détail les entrées de votre manette et de tester divers aspects tels que :
- **Snapback**
- **Dashback**
- **Pivots**
- **Ledgedashes**

Il offre une visualisation précise des mouvements des sticks analogiques, ce qui facilite l'évaluation et l'ajustement de votre manette pour des performances optimales dans **Super Smash Bros**.

> **Note :** Nous nous tournerons plutôt vers l'outil **Snapback** pour **Smash Ultimate**.

## Comprendre le Snapback Viewer
Dans le **Snapback Viewer**, plusieurs informations sont affichées :

- Une courbe allant de **+128 à -128**, qui représente l'amplitude "théorique" du stick. Bien qu'encodée jusqu'à 256, cette valeur est avant tout **informatrice**.
- Deux **lignes vertes** situées à **+23 et -23**. Ces lignes marquent le **seuil de détection du snapback**. Un input est enregistré uniquement si ces valeurs sont dépassées.
- Les courbes affichées en **ROUGE** correspondent à l'axe **X (horizontal)**, tandis que celles en **BLEU** correspondent à l'axe **Y (vertical)**.

Voici un exemple visuel :  
![Exemple Snapback Viewer](https://raw.githubusercontent.com/Dizi0/PhobData/refs/heads/main/Diagnostic/imgs/smashscope.png)

Voici a quoi ressemble du Snapback
![Exemple Snapback Viewer](https://raw.githubusercontent.com/Dizi0/PhobData/refs/heads/main/Diagnostic/imgs/snapback.png)
### Détection du Snapback
Le **snapback** est caractérisé par un mouvement où le stick passe :
1. **D'une position d'input**
2. **À une position neutre**
3. **Puis de nouveau à une position d'input**, alors que le stick est **relâché**

> **Un snapback est considéré comme présent UNIQUEMENT si les valeurs dépassent les lignes vertes.**

Avec la **PHOB**, il est possible d'atténuer ce problème **sans démonter la manette**, grâce à une **combinaison de touches simple** permettant d'ajuster dynamiquement la réponse du stick.

## Vidéo Explicative
Une vidéo détaillant l'utilisation de SmashScope est disponible ici : [Vidéo explicative](https://www.youtube.com/watch?v=YR8d3tp5KLU).