
# 🧠 MNIST Digit Classification - CNN with Keras

Ce projet implémente un réseau de neurones convolutionnel (CNN) pour reconnaître les chiffres manuscrits du jeu de données MNIST en utilisant **TensorFlow/Keras**. Il comprend le chargement des données, l'entraînement du modèle, l'évaluation et l'affichage des performances.

## 📁 Contenu

- 📦 Chargement des données `MNIST`
- 🧼 Prétraitement (normalisation + encodage one-hot)
- 🧠 Définition d'un modèle CNN simple
- ⚙️ Entraînement du modèle avec validation
- 📊 Évaluation sur le jeu de test
- 📉 Visualisation des courbes `accuracy` et `loss`
- 📈 Matrice de confusion
- 🔮 Affichage des prédictions

## 📷 Exemples

### Images d'entrée
Une série de 10 chiffres du dataset MNIST est affichée au début du notebook pour donner un aperçu visuel.

### Prédictions du modèle
Les 10 premières prédictions du modèle sur le jeu de test sont affichées avec les étiquettes prédites.

### Matrice de confusion
Analyse détaillée de la performance du modèle par chiffre grâce à une heatmap.

## 📦 Dépendances

Ce projet nécessite :

```bash
tensorflow
numpy
matplotlib
seaborn
scikit-learn
```

Installation :

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

## 🚀 Exécution

Ouvre le notebook avec Jupyter :

```bash
jupyter notebook mnist_seg.ipynb
```

## 📈 Résultats

Le modèle atteint une **précision > 98%** sur le jeu de test avec une architecture simple de deux couches `Conv2D` suivies de `MaxPooling2D`, `Dense` et `softmax`.
# mnist-cnn-classifier
