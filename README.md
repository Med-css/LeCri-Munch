# Le Cri de Munch - Expérience 3D Interactive

Une réinterprétation 3D interactive de l'œuvre expressionniste emblématique d'Edvard Munch, réalisée avec Three.js et WebGL.

## Accès au projet

Le projet est accessible en ligne à l'adresse suivante :
**https://bymehd.github.io/LeCri-Munch/**

## À propos du projet

Ce projet propose une expérience immersive et interactive autour de "Le Cri" (1893), l'une des œuvres les plus célèbres d'Edvard Munch. Grâce aux technologies WebGL et Three.js, les visiteurs peuvent explorer cette œuvre iconique sous différents angles et découvrir ses éléments en 3D.

L'objectif est de permettre une nouvelle approche de cette peinture expressionniste, symbolisant l'angoisse existentielle de l'humanité, en offrant une dimension interactive et moderne à cette œuvre d'art intemporelle.

## Fonctionnalités

### Implémentées

- **Modélisation 3D détaillée** : Reproduction fidèle des éléments du tableau
- **Système d'éclairage dynamique** : Lumières ajustables en temps réel
- **Ombres portées réalistes** : Shadow maps haute résolution
- **Contrôle interactif de la caméra** : Navigation fluide avec OrbitControls
- **Effet de brouillard atmosphérique** : Ambiance dramatique configurable
- **Surfaces réfléchissantes** : Effet miroir sur l'eau
- **Textures haute résolution** : Matériaux détaillés et réalistes
- **Skybox immersive** : Ciel tourmenté à 360°
- **Effets spéculaires** : Brillance et reflets réalistes
- **Interface de contrôle GUI** : Panneau dat.GUI intégré
- **Animations fluides** : Bateaux animés et effets dynamiques

### En développement

- Environment mapping avancé

## Technologies utilisées

- **Three.js** (v0.150.1) - Bibliothèque 3D JavaScript
- **WebGL** - Rendu graphique 3D dans le navigateur
- **dat.GUI** - Interface de contrôle interactive
- **OrbitControls** - Contrôle de la caméra
- **GLTFLoader** - Chargement de modèles 3D
- **HTML5 / CSS3** - Structure et design de la page
- **JavaScript ES6+** - Logique applicative

## Structure du projet

```
LeCri-Munch/
├── index.html          # Page principale
├── index.js            # Script principal Three.js
├── styles.css          # Styles de l'application
├── Parisienne.ttf      # Police personnalisée
├── img.jpg             # Image de référence
├── modeles/            # Modèles 3D
│   └── ...
└── textures/           # Textures pour les matériaux
    └── ...
```

## Installation et utilisation

### Prérequis

- Un navigateur web moderne supportant WebGL (Chrome, Firefox, Safari, Edge)
- Une carte graphique récente pour une expérience optimale

### Lancement en local

1. Clonez le dépôt :
```bash
git clone https://github.com/bymehd/LeCri-Munch.git
cd LeCri-Munch
```

2. Ouvrez le fichier `index.html` dans votre navigateur, ou utilisez un serveur local :
```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server
```

3. Accédez à l'application via `http://localhost:8000`

## Contrôles

- **Clic gauche + glisser** : Rotation de la caméra
- **Molette de la souris** : Zoom avant/arrière
- **Clic droit + glisser** : Déplacement latéral
- **Interface GUI** : Ajustement des paramètres de la scène (lumières, effets, etc.)

## Processus créatif

### 1. Analyse artistique
Étude approfondie de "Le Cri" pour comprendre sa composition, sa palette de couleurs et son message émotionnel, afin de traduire l'essence de l'œuvre en 3D.

### 2. Conception 3D
Création des modèles 3D dans Blender, en se concentrant sur la reproduction des formes caractéristiques et des proportions du tableau, optimisés pour le web.

### 3. Développement technique
Intégration dans Three.js avec des shaders personnalisés pour reproduire fidèlement les effets de couleur, de lumière, de transparence et les reflets.

### 4. Tests et ajustements
Sessions de test sur différents appareils pour affiner les détails visuels et garantir une expérience fluide.

### 5. Documentation
Rédaction de la documentation technique et création de la page de présentation.

## Optimisations

- Modèles 3D optimisés pour le web
- Techniques de Level of Detail (LOD)
- Chargement asynchrone des ressources
- Compression des textures
- Gestion efficace de la mémoire

## Compatibilité

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Projet scolaire

Ce projet a été réalisé dans le cadre d'un projet universitaire visant à explorer les possibilités offertes par les technologies WebGL et Three.js pour la création d'expériences artistiques interactives.

## Développeurs

- **byMehd** - [https://bymehd.fr](https://bymehd.fr)
- **ALGUL Sefer**
- **GRANDGIRARD Louis**

## Licence

Ce projet est un projet éducatif. L'œuvre originale "Le Cri" d'Edvard Munch est dans le domaine public.

## Remerciements

- Edvard Munch pour son œuvre inspirante
- La communauté Three.js pour la documentation et les exemples
- Les contributeurs open source des bibliothèques utilisées
