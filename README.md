### 🌍 Langue  
🇫🇷 Français • [🇬🇧 English](./README.en.md)

# 🗺️ MY_WORLD - Éditeur de terrain isométrique (CSFML)

## 🎯 Description du projet

**My_World** est un éditeur de carte isométrique développé en **C** avec **CSFML** (binding C de SFML).  
Le but n’est pas de “gagner”, mais de **modeler dynamiquement une carte** : élever ou abaisser le terrain, modifier la texture des tuiles, zoomer, pivoter... Le joueur peut ainsi expérimenter un rendu pseudo-3D librement.

Deux modes principaux sont disponibles :
- **Terraform** : modifie la hauteur des tuiles
- **Layers** : applique différentes textures aux tuiles

---

## 🎮 Contrôles & Gameplay

### 🕹️ Contrôles communs :

- **Molette** ou touches **Z / D** : zoom / dézoom de la vue
- **Flèches gauche / droite** : rotation de la carte
- **F5** : activer / désactiver les sons
- **Clic gauche** : cliquer sur un bouton

### 🛠️ Mode Terraform :

- **Clic gauche** : augmenter la hauteur d’une tuile
- **Clic droit** : abaisser la hauteur d’une tuile
- **+ / -** : augmenter ou réduire la taille de la carte
- **R** : réinitialiser le terrain

### 🎨 Mode Layers :

- **Clic gauche** : sélectionner une texture avec un bouton ou appliquer une texture sur une tuile

>💡 Note personnelle :  
>Ce projet est l’un de mes **premiers projets graphiques avancés**.  
>Il m’a permis de comprendre les bases de l’affichage isométrique, la gestion des événements complexes, et la création d’un éditeur d’environnement interactif.  
>Des ajouts sont prévus dans le futur :  
>- meilleure ergonomie,  
>- sauvegarde de carte,  
>- export d’image,  
>- et amélioration du système de textures.

---

## 🛠️ Installation & Compilation

### 📦 Prérequis

```bash
sudo apt-get install libcsfml-dev
```  
▶️ Lancer l'application  
```bash
make
./my_world
```
## 👨‍💻 Auteurs
  - Arthur Vignes -> https://github.com/4rthurV  
  - Eros Delianne Le Boucher

Étudiants en 1ʳᵉ année à EPITECH Lille (Promo 2029)  
Ce projet a été réalisé dans le cadre du module B-MUL-200 (programmation graphique avancée en C avec CSFML).  

> 📌 Ce dépôt est personnel, non officiel, et publié dans un objectif pédagogique.
