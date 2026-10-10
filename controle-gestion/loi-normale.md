# 📘 Chapitre 2 — Contrôle de gestion en avenir incertain et aléatoire

## Introduction
Le contrôle de gestion ne s’exerce jamais dans un environnement parfaitement stable. Les entreprises doivent composer avec des événements incertains, des variations de marché, des comportements de clients ou de fournisseurs difficiles à anticiper. Pour analyser ces situations, on utilise des outils mathématiques fondés sur les probabilités et les variables aléatoires. Ce chapitre présente ces notions et montre comment elles s’appliquent à la gestion.

---

# 1. Les variables aléatoires

## 1.1 Variables aléatoires et probabilités
Une variable aléatoire est un outil mathématique utilisé lorsque l’entreprise doit faire face à une incertitude. Elle permet d’associer une probabilité à un événement dont la réalisation n’est pas certaine. Les ventes, les niveaux d’approvisionnement ou encore le chiffre d’affaires sont des exemples d’événements aléatoires.

Un événement aléatoire est simplement un événement dont la réalisation est incertaine.  
La probabilité représente la chance que cet événement se produise.

## 1.2 Variables aléatoires discrètes
Une variable aléatoire est dite discrète lorsqu’elle ne peut prendre qu’un nombre limité de valeurs. On peut identifier une valeur minimale et une valeur maximale. C’est le cas, par exemple, du nombre de produits vendus lorsqu’il est compté unité par unité.

## 1.3 Variables aléatoires continues
Une variable aléatoire est continue lorsqu’elle peut prendre un nombre illimité de valeurs dans un intervalle. La probabilité ne porte plus sur une valeur précise mais sur un intervalle. Le chiffre d’affaires, le résultat ou la marge sur coût variable sont des variables continues.

## 1.4 Caractéristiques d’une variable aléatoire
L’espérance mathématique représente la valeur moyenne attendue de la variable. Elle se calcule comme la somme des valeurs possibles pondérées par leurs probabilités.

E(X) = Σ [ xᵢ × P(X = xᵢ) ]

L’écart-type mesure la dispersion des valeurs autour de la moyenne. Il correspond à la racine carrée de la variance.

σ(X) = √ Σ [ (xᵢ − E(X))² × P(X = xᵢ) ]

---

# 2. La loi normale

## 2.1 Caractéristiques de la loi normale
La loi normale est la loi de probabilité la plus utilisée en sciences de gestion. Elle se représente graphiquement par une courbe en cloche, symétrique autour de la moyenne. Une variable qui suit une loi normale est caractérisée par deux paramètres : la moyenne \( m \) et l’écart-type \( σ \).

On note généralement :

X ~ N(m ; σ)

La loi normale offre un nombre infini de valeurs possibles. Pour faciliter les calculs, on utilise souvent la loi normale centrée réduite, qui repose sur une variable appelée \( T \). Cette variable permet de lire les probabilités dans la table de la loi normale.

La transformation est la suivante :

T = (X − m) / σ

---

# 3. Lecture de la table de la loi normale

La table de la loi normale centrée réduite permet de déterminer des probabilités à partir de la variable \( T \). Voici les principales relations utilisées en gestion :

Pour un seuil positif \( a \) :


\[
P(T \geq a) = 1 - P(T < a)
\]



Pour un seuil négatif \( a \) :


\[
P(T \leq -a) = P(T \geq a)
\]



Pour un intervalle :


\[
P(a \leq T \leq b) = P(T \leq b) - P(T < a)
\]



Pour retrouver une valeur à partir d’une probabilité :


\[
P(T \leq -a) = 1 - P(T \leq a)
\]



---

# 4. Utilisation de la loi normale en gestion

## 4.1 Propriétés de l’espérance et de la variance
Les transformations linéaires d’une variable aléatoire respectent des règles simples.

Pour une transformation \( Y = aX + b \) :


\[
E(aX + b) = a \cdot E(X) + b
\]




\[
\sigma(aX) = a \cdot \sigma(X)
\]




\[
\sigma(aX + b) = a \cdot \sigma(X)
\]



## 4.2 Somme ou différence de variables indépendantes
Lorsque plusieurs variables indépendantes sont additionnées ou soustraites, leurs espérances et variances s’additionnent.



\[
E(X_1 + X_2 + \dots + X_n) = E(X_1) + E(X_2) + \dots + E(X_n)
\]





\[
V(X_1 + X_2 + \dots + X_n) = V(X_1) + V(X_2) + \dots + V(X_n)
\]





\[
\sigma(X_1 + X_2 + \dots + X_n) = \sqrt{\sigma^2(X_1) + \sigma^2(X_2) + \dots + \sigma^2(X_n)}
\]



## 4.3 Application au volume des ventes, au chiffre d’affaires et au résultat

### Du volume des ventes au chiffre d’affaires
Si \( P \) est le prix unitaire et \( V \) le volume des ventes :



\[
M(CA) = P \cdot m(V)
\]




\[
\sigma(CA) = P \cdot \sigma(V)
\]



### Du volume des ventes au résultat
Si la marge sur coût variable est notée \( MCV \) et les charges fixes \( CF \) :



\[
M(R) = (MCV \cdot m(V)) - CF
\]




\[
\sigma(R) = MCV \cdot \sigma(V)
\]



### Modification de la période d’étude
Pour une période annuelle composée de douze mois :



\[
m(A) = m(V_1) + m(V_2) + \dots + m(V_{12})
\]





\[
\sigma(A) = \sigma(V) \cdot \sqrt{12}
\]



---

# 5. Applications et exercices
(À compléter avec les documents que tu m’enverras : PDF, Sheets, Word. Je les intégrerai ici sous forme de tableaux, d’énoncés et de corrections en Markdown.)

---

# Synthèse du chapitre
Ce chapitre montre comment les probabilités et les variables aléatoires permettent d’analyser des situations incertaines. La loi normale, en particulier, offre un cadre simple pour estimer des résultats, des chiffres d’affaires ou des marges lorsque les données sont soumises à des fluctuations. Ces outils sont essentiels pour anticiper, décider et piloter la performance dans un environnement incertain.

