# TP-User-DB


### **Exercice TP : Analyse d'une base de données d'utilisateurs**

**Objectif** : Vous travaillez pour une plateforme e-commerce. Le site dispose d'une base de données d'utilisateurs, et vous devez développer un outil pour analyser cette base.

#### **Énoncé** :

Imaginons la structure suivante pour notre base de données d'utilisateurs:

```
utilisateurs = [
    {"id": 1, "nom": "Martin", "email": "martin@email.com", "achats": [50, 20, 80, 10]},
    {"id": 2, "nom": "Lucie", "email": "lucie@email.com", "achats": [20, 5]},
    {"id": 3, "nom": "Sam", "email": "sam@email.com", "achats": [100]},
    {"id": 4, "nom": "Julie", "email": "julie@email.com", "achats": [200, 50]},
    {"id": 5, "nom": "Max", "email": "max@email.com", "achats": []}
]
```

Vous devez être capable de :

1. Calculer le total des achats pour un utilisateur donné.
2. Trouver l'utilisateur ayant dépensé le plus d'argent.
3. Trouver tous les utilisateurs n'ayant effectué aucun achat.

**Consignes** :

1. **Total des achats** : Créez une fonction pour calculer le total des achats d'un utilisateur spécifié par son "id".
2. **Utilisateur le plus dépensier** : Créez une fonction pour identifier l'utilisateur ayant effectué le plus d'achats en valeur totale.
3. **Utilisateurs sans achats** : Créez une fonction pour lister tous les utilisateurs qui n'ont effectué aucun achat.

Votre réponse doit être rédigée en pseudo-code.
