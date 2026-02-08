# 🎮 PAC-MAN MOBILE

Un jeu Pac-Man moderne et interactif, optimisé pour mobile et desktop avec des pouvoirs spéciaux et un système de niveaux progressifs.

🕹️ **[JOUER MAINTENANT](https://urlr.me/ebMSPR)**

---

## 📋 Table des matières

- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Comment jouer](#-comment-jouer)
- [Pouvoirs spéciaux](#-pouvoirs-spéciaux)
- [Contrôles](#-contrôles)
- [Système de scoring](#-système-de-scoring)
- [Installation](#-installation)
- [Technologies utilisées](#-technologies-utilisées)
- [Captures d'écran](#-captures-décran)

---

## 🎯 Aperçu

PAC-MAN MOBILE est une version revisitée du célèbre jeu d'arcade classique, enrichie de fonctionnalités modernes. Mangez tous les points, évitez les fantômes, et utilisez des pouvoirs spéciaux pour survivre le plus longtemps possible !

Le jeu propose une interface tactile intuitive pour mobile, tout en restant parfaitement jouable au clavier sur desktop.

---

## ✨ Fonctionnalités

- 🎮 **Interface responsive** - S'adapte parfaitement aux mobiles, tablettes et ordinateurs
- 👻 **4 fantômes intelligents** - Chacun avec sa propre stratégie de poursuite
- ⚡ **Pouvoirs spéciaux** - 4 types de power-ups pour pimenter le gameplay
- 🎵 **Effets sonores** - Ambiance sonore immersive
- 🏆 **Système de scoring** - Combos et multiplicateurs de points
- 📊 **Niveaux progressifs** - Difficulté croissante à chaque niveau
- 💾 **Sauvegarde du high score** - Votre meilleur score est conservé
- 🎨 **Design moderne** - Interface élégante avec effets visuels

---

## 🎮 Comment jouer

### Objectif
Mangez tous les points jaunes sur le plateau tout en évitant les fantômes. Collectez les power-ups pour gagner des pouvoirs temporaires et augmenter votre score.

### Règles de base
1. **Points normaux** 🟡 : +10 points
2. **Super points** 🔵 : +50 points + invincibilité temporaire
3. **Pouvoirs spéciaux** 💎 : Activent des capacités uniques
4. **Fantômes** 👻 : 
   - Les toucher = perte d'une vie
   - En mode invincible : +100/200/400/800 points selon le combo
5. **Vies** ❤️ : Vous commencez avec 3 vies
6. **Niveaux** 🎯 : Complétez le niveau en mangeant tous les points

---

## ⚡ Pouvoirs spéciaux

Le jeu propose 4 pouvoirs spéciaux qui apparaissent aléatoirement :

| Pouvoir | Icône | Durée | Description |
|---------|-------|-------|-------------|
| **Invincibilité** | ⚡ | 8s | Mangez les fantômes pour gagner des points bonus |
| **Vitesse** | 🚀 | 6s | Déplacez-vous 2x plus vite |
| **Bouclier** | 🛡️ | 10s | Protection contre une collision avec un fantôme |
| **Freeze** | ❄️ | 5s | Immobilise tous les fantômes |

**Conseil** : Combinez les pouvoirs pour maximiser vos points ! Par exemple, utilisez la vitesse après avoir obtenu l'invincibilité pour attraper plus de fantômes.

---

## 🎯 Contrôles

### Sur mobile/tactile 📱
- Utilisez les **flèches directionnelles** à l'écran
  - ▲ Haut
  - ▼ Bas
  - ◄ Gauche
  - ► Droite
- Bouton **⏸ Pause** pour mettre le jeu en pause
- Bouton **🔄 Recommencer** pour relancer une partie

### Sur ordinateur ⌨️
- **Flèches du clavier** : Déplacer Pac-Man
  - ↑ Haut
  - ↓ Bas
  - ← Gauche
  - → Droite
- **Espace** : Mettre en pause
- **R** : Recommencer la partie

---

## 🏆 Système de scoring

### Points de base
- Point normal : **10 points**
- Super point : **50 points**
- Pouvoir spécial : **100 points**
- Compléter un niveau : **500 points**

### Fantômes (en mode invincible)
Les fantômes rapportent de plus en plus de points dans un combo :
1. Premier fantôme : **100 points**
2. Deuxième fantôme : **200 points**
3. Troisième fantôme : **400 points**
4. Quatrième fantôme : **800 points**

**Astuce** : Essayez de manger les 4 fantômes pendant une seule session d'invincibilité pour maximiser votre score !

### Multiplicateur de niveau
Chaque niveau augmente la vitesse des fantômes, rendant le jeu plus difficile mais aussi plus gratifiant.

---

## 💻 Installation

### Option 1 : Jouer en ligne (recommandé)
Cliquez simplement sur le lien : **[https://urlr.me/ebMSPR](https://urlr.me/ebMSPR)**

### Option 2 : Installation locale
1. Téléchargez le fichier `pacman.html`
2. Ouvrez-le dans votre navigateur web préféré
3. Aucune installation supplémentaire requise !

### Compatibilité navigateurs
- ✅ Chrome / Edge (recommandé)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ⚠️ Internet Explorer (non supporté)

---

## 🛠️ Technologies utilisées

- **HTML5 Canvas** - Rendu graphique du jeu
- **JavaScript ES6** - Logique du jeu et animations
- **CSS3** - Interface utilisateur et effets visuels
- **Web Audio API** - Effets sonores
- **Responsive Design** - Adaptation multi-plateformes

### Architecture du code
- Système de grille pour le labyrinthe
- Algorithmes de pathfinding pour les fantômes
- Gestion d'états pour les pouvoirs
- Système de détection de collisions optimisé
- LocalStorage pour la sauvegarde du high score

---

## 📸 Captures d'écran

### Interface de jeu
Le jeu présente :
- Un labyrinthe classique en bleu néon
- Des statistiques en temps réel (score, niveau, vies)
- Une liste des pouvoirs disponibles (à gauche)
- Des contrôles tactiles (à droite)
- Des effets visuels pour chaque pouvoir

### Disposition
```
┌────────────────────────────────────────┐
│         PAC-MAN MOBILE                 │
├──────┬──────┬──────────┬──────┬────────┤
│SCORE │NIVEAU│  RECORD  │ VIES │        │
├──────┴──────┴──────────┴──────┴────────┤
│                                        │
│  📋        🎮              🎮          │
│ Pouvoirs   Labyrinthe    Contrôles    │
│ (colonne)  (canvas)      (flèches)    │
│            + Fantômes                  │
│                                        │
└────────────────────────────────────────┘
```

---

## 🎯 Astuces et stratégies

1. **Planifiez votre route** - Ne foncez pas tête baissée, anticipez les déplacements des fantômes
2. **Utilisez les tunnels** - Les passages sur les côtés permettent de semer les fantômes
3. **Économisez les super points** - Attendez d'être en danger pour les utiliser
4. **Maîtrisez les combos** - Essayez de manger tous les fantômes pendant l'invincibilité
5. **Connaissez vos ennemis** - Chaque fantôme a un comportement différent :
   - **Blinky** (rouge) : Vous poursuit directement
   - **Pinky** (rose) : Tente de vous couper la route
   - **Inky** (cyan) : Stratégie hybride
   - **Clyde** (orange) : Alterne entre poursuite et dispersion

---

## 🐛 Problèmes connus

Si vous rencontrez des problèmes :
- Actualisez la page (F5)
- Vérifiez que JavaScript est activé dans votre navigateur
- Essayez un autre navigateur
- Désactivez les bloqueurs de publicités qui pourraient interférer

---

## 📝 Changelog

### Version actuelle
- ✅ Contrôles tactiles et souris fonctionnels
- ✅ Disposition optimisée (pouvoirs à gauche, contrôles à droite)
- ✅ 4 pouvoirs spéciaux uniques
- ✅ Système de niveaux progressifs
- ✅ Sauvegarde automatique du high score
- ✅ Design responsive pour tous les écrans
- ✅ Effets sonores et visuels

---

## 👨‍💻 Crédits

Inspiré du jeu d'arcade classique **Pac-Man** créé par Toru Iwatani pour Namco en 1980.

Cette version moderne a été développée avec des technologies web modernes pour offrir une expérience de jeu fluide sur tous les appareils.

---

## 📄 Licence

Ce projet est à usage personnel et éducatif. Pac-Man est une marque déposée de Bandai Namco Entertainment.

---

## 🎮 Bonne chance !

Prêt à battre votre high score ? **[Jouez maintenant !](https://urlr.me/ebMSPR)**

N'oubliez pas de partager votre meilleur score avec vos amis ! 🏆

---

*Dernière mise à jour : Février 2026*