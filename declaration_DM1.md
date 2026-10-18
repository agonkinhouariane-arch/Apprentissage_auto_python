# Déclaration d'usage de l'IA — modèle

> **À copier dans votre dépôt personnel, un fichier par rendu noté :**
> `declaration_E1.md`, `declaration_E2.md`, `declaration_E3.md` (exercices) — et, sur le dépôt
> d'équipe, `declaration_B3.md` pour le projet.
>
> Elle se dépose **avec** le notebook, dans le même commit. Sans elle, le rendu est incomplet :
> la feuille de route de l'IA est 🟠 (autorisée **avec déclaration**) pour les exercices.

Nom et prénom :AGON KINHOU Fifamè Nathalie Ariane
Pseudo Kaggle :arianeagonkinhou
Dépôt (lien) :https://github.com/agonkinhouariane-arch/Apprentissage_auto_python
Rendu : Devoir maison 1
Date :18 octobre 2026

---

## 1. Ce que j'ai produit moi-même
-Questions 1 et 2 : j'ai écrit le code moi-même (référence sur `yval`, balayage `groupby` avec le critère des 500 lignes), puis corrigé certaines phrases après relecture.
- Question 3 : j'ai formulé mes constats sur les doublons et sur `duree_consultation`.
- Questions 4 à 15 : j'ai pris en main l'exécution des cellules sur Kaggle, vérifié la validation de tous les contrôles pédagogiques, reformulé et ajusté les interprétations textuelles (notamment pour la lecture des barres de bruit en Q5 et les biais d'optimisme en Q8).


## 2. Ce que j'ai fait avec un assistant
| Gemini / Claude | Explication de chaque question et de la logique (barre de bruit, référence, fuites) | J'ai relu les explications et posé des questions quand je n'ai pas compris. |
| Gemini / Claude | Code complet des Q4 à Q15 (mesures, tableaux, fonction `suspects`) et brouillons de textes | J'ai exécuté chaque cellule, comparé les sorties à mes chiffres et reformulé les interprétations (Q5, Q7, Q8, Q11). |
| Gemini / Claude | Diagnostic de mes erreurs (NameError, colonne `rappel_envoye`, `modele_base`) | J'ai appliqué les corrections et relancé. |

_Si vous n'avez utilisé aucun assistant, écrivez « aucun » — c'est une réponse complète._

## 3. Ce que je ne saurais pas expliquer
- Pourquoi les barres de la Q5 s'écartent de la formule théorique (rapports mesurés vs théoriques).
- La correction de population finie appliquée en Q6 pour les tirages sans remise.
- Le fonctionnement exact de la fonction `suspects` (la comparaison des parts par valeur).
- Pourquoi un `modele_base` est nécessaire après la feature de la Q10 pour éviter la fuite de la variable créée.

_La question la plus utile, et la moins confortable : quelle ligne de votre rendu ne savez-vous
pas défendre si on vous la montre à l'oral ?_

_Elle est là pour vous, pas contre vous. Un code que vous ne savez pas expliquer n'est pas un
travail rendu (politique du cours, § 8) — et l'oral individuel porte sur **votre** travail._

## 4. Chiffres

_Deux nombres, tirés de votre propre notebook :_

- score interne mesuré :82,51 % (arbres) ; 82,21 % (modèle linéaire)
- score public déclaré : No disponible

---

> **Ce qui arrive à cette déclaration.** L'enseignant peut relancer votre notebook sur un test
> caché : si le score déclaré ne se reproduit pas, il n'existe pas — la composante « rigueur
> expérimentale » passe à 0 et l'oral est convoqué d'office. La déclaration est lue **avec** le
> journal de décisions, pas à part.
