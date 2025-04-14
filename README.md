# 💻 Exercices de JavaScript : Variables, Conditions, Boucles & Fonctions

Bienvenue ! Voici une série de petits challenges à réaliser en **JavaScript** pour pratiquer :

- les **variables**
- les **opérations mathématiques**
- les **conditions**
- les **boucles**
- les **fonctions**
- la **saisie utilisateur**

---

## 🔸 Challenge 1 : Affichage des informations personnelles

> Écris un programme qui demande à l’utilisateur :
- son **nom**
- son **prénom**
- son **âge**
- son **sexe**
- son **adresse email**

Et qui affiche ensuite ces informations dans la console.

---

## 🔸 Challenge 2 : Conversion de température (Celsius → Kelvin)

**Formule :**  
`K = C + 273.15`

---

## 🔸 Challenge 3 : Conversion de distance (Km → Yards)

**Formule :**  
`Yards = Km * 1093.61`

---

## 🔸 Challenge 4 : Conversion de vitesse (km/h → m/s)

**Formule :**  
`m/s = km/h * 0.27778`

---

## 🔸 Challenge 5 : État de l’eau selon la température

> Demande une température en Celsius et affiche :
- **Solide** si C < 0
- **Liquide** si 0 <= C < 100
- **Gaz** si C >= 100

---

## 🔸 Challenge 6 : Opérations de base entre deux nombres

> Demande deux nombres réels à l’utilisateur (a et b), puis affiche :
- a + b
- a - b
- a * b
- a / b (avec décimales)

---

## 🔸 Challenge 7 : Moyenne pondérée de trois nombres

> Calcule la moyenne pondérée de trois nombres avec les pondérations suivantes :
- 1er nombre : pondération 2
- 2ème nombre : pondération 3
- 3ème nombre : pondération 5

---

## 🔸 Challenge 8 : Moyenne géométrique

**Formule :**  
`Moyenne = (a * b * c)^(1/3)`

---

## 🔸 Challenge 9 : Distance entre deux points en 3D

**Formule :**  
`Distance = √((x2 - x1)² + (y2 - y1)² + (z2 - z1)²)`

---

## 🔸 Challenge 10 : Volume d'une sphère

**Formule :**  
`Volume = (4/3) * π * r³`

---

## 🔸 Challenge 11 : Surface d’un rectangle

**Formule :**  
`Surface = longueur * largeur`

---

## 🔸 Challenge 12 : Inverser un entier à 4 chiffres (sans boucle)

> Exemple : si l’utilisateur entre `1234`, le programme doit afficher `4321`.

---

## 🔸 Challenge 13 : Afficher la valeur binaire et hexadécimale d’un entier

> Saisir un entier et afficher ses représentations en :
- **binaire**
- **hexadécimal**

---

## 🔹 Challenge 14 : Vérification de majorité (Condition)

> Demande l’**âge** de l’utilisateur, puis affiche s’il est :
- **Mineur** (< 18)
- **Majeur** (≥ 18)

---

## 🔹 Challenge 15 : Plus grand de trois nombres (Condition)

> Demande trois **nombres** à l’utilisateur, puis affiche le **plus grand** d’entre eux.

---

## 🔹 Challenge 16 : Affichage des nombres pairs de 1 à N (Boucle)

> Demande un **nombre N** à l’utilisateur. Affiche ensuite tous les **nombres pairs** de 1 jusqu’à N.

📌 Exemple : si N = 10 → affiche : 2, 4, 6, 8, 10

---

## 🔹 Challenge 17 : Somme des entiers de 1 à N (Boucle)

> Demande un **nombre N** à l’utilisateur. Calcule et affiche la **somme de tous les entiers** de 1 à N.

📌 Exemple : si N = 5 → 1 + 2 + 3 + 4 + 5 = 15

---

## 🔹 Challenge 18 : Création d’une fonction de salutation

> Crée une fonction appelée `saluer(nom)` qui prend un **nom** en paramètre et affiche :
```
Bonjour, [nom] !
```

📌 Exemple :  
```js
saluer("Ahmed"); // Bonjour, Ahmed !
```

---

## 🔹 Challenge 19 : Fonction avec boucle et condition – Table de multiplication filtrée

> Crée une fonction `afficherMultiplesDe(n, max)` qui :
- Utilise une **boucle** pour parcourir les nombres de `1` à `max`
- Affiche uniquement les **multiples** de `n` (condition avec `%`)
- N’affiche rien pour les autres

📌 Exemple :  
```js
afficherMultiplesDe(3, 10);
// Résultat attendu :
// 3
// 6
// 9
```

---
