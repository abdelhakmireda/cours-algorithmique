
---

# 🎯 **EXERCICES + CORRECTIONS PAR PARTIE**

---

# 🧩 **1. VARIABLES & CONSTANTES**

## 📝 **Exercice 1**

Déclare une variable `nom`, une variable `age`, et une constante `PI = 3.14`.
Affiche-les.

### ✔️ Correction

```
nom ← "Youssef"
age ← 22
PI ← 3.14

Afficher nom
Afficher age
Afficher PI
```

---

## 📝 **Exercice 2**

Déclare deux variables `a` et `b`, affecte-leur des valeurs, échange-les.

### ✔️ Correction

```
a ← 5
b ← 10
temp ← a
a ← b
b ← temp
Afficher a, b      → (10, 5)
```

---

## 📝 **Exercice 3**

Déclare une constante `TAUX = 0.2` et calcule la TVA d’un prix donné.

### ✔️ Correction

```
prix ← 100
TAUX ← 0.2
tva ← prix * TAUX
Afficher tva       → 20
```

---

# ❓ **2. CONDITIONS**

## 📝 **Exercice 1**

Demande un nombre et affiche :
"Pair" si divisible par 2, sinon "Impair".

### ✔️ Correction

```
Si nombre % 2 = 0 Alors
    Afficher "Pair"
Sinon
    Afficher "Impair"
FinSi
```

---

## 📝 **Exercice 2**

Afficher le plus grand entre deux nombres.

### ✔️ Correction

```
Si a > b Alors
    Afficher a
Sinon
    Afficher b
FinSi
```

---

## 📝 **Exercice 3**

Demander l’âge.
Si < 12 → "Enfant"
12–17 → "Adolescent"

> = 18 → "Adulte"

### ✔️ Correction

```
Si age < 12 Alors
    Afficher "Enfant"
SinonSi age < 18 Alors
    Afficher "Adolescent"
Sinon
    Afficher "Adulte"
FinSi
```

---

# 🔁 **3. BOUCLES**

## 📝 **Exercice 1**

Afficher les nombres de 1 à 10.

### ✔️ Correction

```
Pour i ← 1 à 10
    Afficher i
FinPour
```

---

## 📝 **Exercice 2**

Afficher la somme des nombres de 1 à 5.

### ✔️ Correction

```
somme ← 0
Pour i ← 1 à 5
    somme ← somme + i
FinPour
Afficher somme    → 15
```

---

## 📝 **Exercice 3**

Tant que l’utilisateur tape un nombre > 0, l’afficher.
Si l’utilisateur tape 0 → arrêter.

### ✔️ Correction

```
Lire x
TantQue x > 0
    Afficher x
    Lire x
FinTantQue
```

---

# 🗂️ **4. TABLEAUX**

## 📝 **Exercice 1**

Créer un tableau : [4, 8, 12].
Afficher chaque élément.

### ✔️ Correction

```
Pour i ← 1 à 3
    Afficher Tab[i]
FinPour
```

---

## 📝 **Exercice 2**

Calculer la somme d’un tableau [2, 5, 7].

### ✔️ Correction

```
somme ← 0
Pour i ← 1 à 3
    somme ← somme + Tab[i]
FinPour
Afficher somme     → 14
```

---

## 📝 **Exercice 3**

Trouver le plus grand élément du tableau [3, 9, 2, 11].

### ✔️ Correction

```
max ← Tab[1]
Pour i ← 2 à 4
    Si Tab[i] > max Alors
        max ← Tab[i]
    FinSi
FinPour
Afficher max     → 11
```

---

# 🔧 **5. FONCTIONS & PROCÉDURES**

## 📝 **Exercice 1**

Créer une procédure `Bonjour(nom)` qui affiche :
"Bonjour + nom".

### ✔️ Correction

```
Procédure Bonjour(nom)
    Afficher "Bonjour " + nom
FinProcédure

Bonjour("Reda")
```

---

## 📝 **Exercice 2**

Créer une fonction `Double(x)` qui retourne 2 × x.

### ✔️ Correction

```
Fonction Double(x)
    Retourner x * 2
FinFonction

Afficher Double(6)   → 12
```

---

## 📝 **Exercice 3**

Créer une fonction `Somme(a, b, c)` qui retourne la somme des 3.

### ✔️ Correction

```
Fonction Somme(a, b, c)
    Retourner a + b + c
FinFonction
```

---

## 📝 **Exercice 4**

Créer une fonction qui retourne le maximum de deux nombres.

### ✔️ Correction

```
Fonction Maximum(a, b)
    Si a > b Alors
        Retourner a
    Sinon
        Retourner b
    FinSi
FinFonction
```

---

# 🎯 **6. PETITS PROBLÈMES COMPLETS**

## 📝 **Problème 1 : Moyenne de 3 notes**

### ✔️ Correction

```
Lire n1, n2, n3
moy ← (n1 + n2 + n3) / 3
Afficher moy
```

---

## 📝 **Problème 2 : Nombre de voyelles dans un mot**

### ✔️ Correction

```
v ← 0
Pour i ← 1 à longueur(mot)
    Si mot[i] est dans {a, e, i, o, u} Alors
        v ← v + 1
    FinSi
FinPour
Afficher v
```

---

## 📝 **Problème 3 : Table de multiplication d’un nombre**

### ✔️ Correction

```
Lire x
Pour i ← 1 à 10
    Afficher x * i
FinPour
```

---

