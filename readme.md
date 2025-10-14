# Examen 2 – Logique de programmation et sécurité  
## Instructions 
- Il s’agit d’un travail individuel.
- La durée prévue de l’examen est de 2h (2 x 1h), mais tout le monde a droit à 4h (2 x 2h).
- C’est un examen à livre ouvert, vous avez le droit à tout sauf internet et l’IA.
- Le notes de cours et Omnivox sont autorisées.

## Critères d’évaluation 


| Question                               |Critères d’évaluation	                                                                            | Points  |
|----------------------------------------|----------------------------------------------------------------------------------------------------  |---------|
| **Résolution de problème (vendredi)**	 |Production d’un algorithme adéquat qui répond à un problème donné.	                                | /6      |
| 	                                      |Production d’un programme fonctionnel conforme aux normes et standards du cours.	                | /6      |
| 	                                      |Production d’une documentation de qualité respectueuse des normes du cours et des règles d’orthographe et de grammaire  | 	    /3 |
| **Tests et débogage   (jeudi)**	       |Repérage complet des erreurs et corrections pertinentes du code fourni                             | /6      |
| 	                                      |Production d’un plan de tests	                                                                    | /3      |
| 	                                      |Production de tests unitaires adéquats                                                             | 	/6     |

## Partie 1 : Tests et débogage

1. Commencer par faire un fork pour avoir votre propre copie du projet d'examen
2. Inviter l'enseignante comme collaboratrice
3. Faire un clône de votre _repository_ dans PyCharm
4. Faire des commit-push régulièrement
5. Vous êtes responsable de vérifier que votre dernier push contient tout votre code.

## Sujet : Calcul des notes d’une compétition de patinage

### Objectifs
- Production de plan de tests
- Production de tests adéquats selon le plan de tests 
- Repérage complet des erreurs et correction du code fourni 
---

## Énoncé
Les deux fonctions fournies permettent d’analyser une liste de mots. 
La première, mot_plus_long, identifie le mot ayant le plus de lettres, 
en ignorant les éléments qui ne sont pas des chaînes de caractères. 
La seconde, pourcentage_mots_max, calcule le pourcentage de mots dont 
la longueur dépasse une valeur donnée.

## Questions
1.	Complétez le plan de tests et les tests unitaires de la fonction mot_plus_long.
2.	Exécutez tous les tests unitaires pour relever les bogues.
3.	Corrigez le code selon les tests unitaires qui échouent. Vous trouverez des commentaires # TODO pour vous indiquer où corriger. Un indice est également fourni.
4.	Complétez les tests unitaires ayant un # TODO.
5.	Refaire les étapes 2 et 3 jusqu’à ce que tous les bogues soient corrigés.


## Structure du projet : 

### Plan de tests: `tableau_tests_mot_long.md`
- Plan de test à compléter
### Tests unitaires: `test_debogage_mot_long.py`
- Fichier pour programmer vos tests unitaires
- Les 2 fonctions doivent être testées
- Utilisez les donneés du plan de tests
### Programme: `debogage_mot_long.py`
- La documentation des fonctions est correcte
- Le code contenu dans les fonctions doit être corrigé
```python
def mot_plus_long(liste_mots):
    """
    Retourne le mot le plus long d'une liste.
    Ignore les éléments qui ne sont pas des chaînes de caractères.

    :param liste_mots: liste de mots
    :return: le mot le plus long ou None si la liste est invalide ou vide
    """
    
def pourcentage_mots_max(mots, taille):
    """
    Calcule le pourcentage de mots ayant une longueur supérieure à une valeur donnée.

    :param mots: liste de mots
    :param taille: longueur minimale à comparer
    :return: pourcentage (float) de mots dépassant la taille, ou None si impossible
    """

if __name__ == "__main__":
    # programme principal : rien à faire ici.
``` 