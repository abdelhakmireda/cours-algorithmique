
---

# 🎓📘 **COURS D’ALGORITHMIQUE — VERSION SIMPLE ET TRÈS EXPLIQUÉE**

---

# 🗺️ 1. INTRODUCTION À L’ALGORITHMIQUE

L’algorithmique, c’est **l’art de décrire clairement comment résoudre un problème**, étape par étape.
C’est comme écrire une **recette de cuisine** 🍰 :

* Tu définis les ingrédients → **Données d’entrée**
* Tu expliques les étapes → **Algorithme**
* Tu obtiens le résultat → **Sortie**

---

## 📊 Schéma simple d’un algorithme

```
    PROBLÈME
        │
        ▼
 ANALYSE (Entrées / Règles / Sorties)
        │
        ▼
   ALGORITHME (Étapes)
        │
        ▼
   EXÉCUTION (Code)
        │
        ▼
     RÉSULTAT
```

**Exemple :** Calculer la somme de deux nombres

* Entrées : a, b
* Règle : somme = a + b
* Résultat : afficher la somme

---

# 📦 2. VARIABLES ET CONSTANTES

Une **variable** = un petit espace dans la mémoire qui garde une valeur qu’on peut changer.
Une **constante** = une valeur qui *ne change jamais*.

## 🔹 2.1 Exemple de variable

```
age ← 20
```

Ici `age` contient la valeur **20**.
On peut changer :

```
age ← 25
```

## 🔹 2.2 Exemple de constante

Une constante est définie une fois :

```
PI ← 3.14 (constante)
```

Ici on ne change jamais la valeur de `PI`.

---

## 🧠 Schéma mémoire simplifié (sans Heap)

```
 ┌──────────────┐
 │ age = 20      │  🔢 variable
 └──────────────┘

 ┌──────────────┐
 │ nom = "Sara"  │  📝 variable
 └──────────────┘

 ┌──────────────┐
 │ PI = 3.14     │  🔒 constante
 └──────────────┘
```

---

## ✏️ Exercice

Déclare un nom, un âge et une ville. Affiche-les.

### ✔️ Correction

```
nom ← "Ali"
age ← 21
ville ← "Rabat"

Afficher nom
Afficher age
Afficher ville
```

---

# ❓ 3. CONDITIONS (SI … SINON)

Les conditions permettent de **prendre des décisions**.

## 📊 Schéma simple

```
        Condition ?
          │
     ┌────┴────┐
     ▼         ▼
  Vrai       Faux
```

## Exemple simple

```
Si age >= 18 Alors
    Afficher "Majeur"
Sinon
    Afficher "Mineur"
FinSi
```

---

## ✏️ Exercice

Écris un algorithme pour afficher "Positif" ou "Négatif".

### ✔️ Correction

```
Si x >= 0 Alors
    Afficher "Positif"
Sinon
    Afficher "Négatif"
FinSi
```

---

# 🔁 4. BOUCLES (Répétition)

Les boucles servent à **répéter une action plusieurs fois**.

---

## 🔹 4.1 Boucle POUR

→ Quand on sait **combien de fois** répéter.

```
Pour i ← 1 à 5
    Afficher i
FinPour
```

Résultat : 1 2 3 4 5

---

## 🔹 4.2 Boucle TANTQUE

→ On répète **tant qu’une condition est vraie**

```
x ← 0
TantQue x < 3
    Afficher x
    x ← x + 1
FinTantQue
```

Résultat : 0 1 2

---

## ✏️ Exercice : Afficher les nombres de 1 à 10

### ✔️ Correction

```
Pour i ← 1 à 10
    Afficher i
FinPour
```

---

# 🗃️ 5. TABLEAUX SIMPLES (1 dimension)

Un tableau sert à stocker **plusieurs valeurs du même type**.

---

## 📊 Schéma d’un tableau

```
Index :   1   2   3   4
         ┌───┬───┬───┬───┐
Valeur:  │10 │20 │30 │40 │
         └───┴───┴───┴───┘
```

---

## Exemple simple

```
Tab ← [5, 10, 15]

Pour i ← 1 à 3
    Afficher Tab[i]
FinPour
```

→ Affiche : 5 10 15

---

## Somme d’un tableau

```
somme ← 0
Pour i ← 1 à 3
    somme ← somme + Tab[i]
FinPour
Afficher somme
```

---

## ✏️ Exercice

Tableau = [2, 4, 6]
Afficher chaque valeur.

### ✔️ Correction

```
Pour i ← 1 à 3
    Afficher Tab[i]
FinPour
```

---

# 🔧 6. FONCTIONS ET PROCÉDURES

⚡ **Procédure** : fait une action
⚡ **Fonction** : renvoie une valeur

---

## 🔹 6.1 Procédure (pas de retour)

```
Procédure Saluer(nom)
    Afficher "Bonjour " + nom
FinProcédure
```

Appel :

```
Saluer("Reda")
```

---

## 🔹 6.2 Fonction (retourne quelque chose)

```
Fonction Double(x)
    Retourner x * 2
FinFonction
```

Appel :

```
Afficher Double(5)    → affiche 10
```

---

## 🔹 6.3 Fonction avec explication simple

Une fonction = **machine** :

* Tu lui donnes quelque chose
* Elle travaille
* Elle renvoie une valeur

```
           Entrée
              │
              ▼
        ┌───────────────┐
        │   FONCTION     │
        │  (calcul)      │
        └───────────────┘
              │
              ▼
           Résultat
```

---

## ✏️ Exercice : Fonction qui retourne la somme de deux nombres

### ✔️ Correction

```
Fonction Somme(a, b)
    Retourner a + b
FinFonction
```

---

# 🧠 7. MINI PROBLÈMES DÉBUTANTS

## 🔹 Problème 1 : Calculer un carré

```
Fonction Carre(x)
    Retourner x * x
FinFonction
```

## 🔹 Problème 2 : Afficher les nombres pairs de 1 à 10

```
Pour i ← 1 à 10
    Si i % 2 = 0 Alors
        Afficher i
    FinSi
FinPour
```

## 🔹 Problème 3 : Trouver le plus grand de deux nombres

```
Si a > b Alors
    Afficher a
Sinon
    Afficher b
FinSi
```

---

# 🎉 FIN DU COURS – VERSION SIMPLE ET TRÈS EXPLIQUÉE

