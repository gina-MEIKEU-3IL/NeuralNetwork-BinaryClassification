# Projet Réseau de Neurones en C

## 🎯 Objectif
Concevoir et implémenter un réseau de neurones artificiels en langage C afin de comprendre les bases de la propagation et des opérations logiques (NOT, AND, OR). Ce projet a été réalisé en 4ᵉ année du cycle ingénieur informatique.

## 🛠️ Choix de conception
- Utilisation des **listes chaînées** pour plus de flexibilité et une gestion dynamique de la mémoire.
- Programmation modulaire avec séparation en fichiers `.h` et `.c`.

## 📂 Organisation du code
- **weight** : gestion des listes de poids
- **neuron** : création et sortie des neurones
- **layer** : construction et propagation des couches
- **network** : création et propagation du réseau complet
- **main.c** : lancement et tests

## ⚙️ Fonctionnalités
- Création de neurones avec biais et poids
- Construction de couches de neurones
- Propagation des données dans un réseau multi-couches
- Simulation des réseaux logiques :
  - NOT
  - AND
  - OR
  - Réseau multi-couche combinant plusieurs opérations

## 🧪 Tests réalisés
- Vérification du fonctionnement des listes et neurones
- Simulation des opérations logiques simples
- Validation d’un réseau multi-couche : `(A ET (NON B)) OU (A ET C)`

## 📊 Résultats
- Les sorties obtenues correspondent aux résultats attendus.
- Le programme démontre la faisabilité d’un réseau de neurones simple en C.
- Base solide pour explorer des réseaux plus complexes.

## 👩‍🎓 Contexte académique
Projet réalisé dans le cadre du module **RN40 – UTBM (2024)**.  
Ce projet m’a permis de :
- Approfondir la manipulation des listes chaînées
- Mettre en pratique la programmation modulaire en C
- Comprendre les bases des réseaux de neurones et leur propagation
