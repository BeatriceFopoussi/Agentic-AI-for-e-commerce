## Création d’un Agent Chatbot E-commerce avec LangChain

![](ca.jpg)
### Présentation du projet
**Dans ce projet, nous allons développer un chatbot e-commerce en exploitant la bibliothèque LangChain à partir d’une base de code préexistante. L’agent conversationnel que nous allons concevoir sera capable de** :

* Rechercher des produits via un index vectoriel.
* Gérer un panier d’achat (ajout, suppression, mise à jour).
* Interpréter les requêtes des utilisateurs pour offrir une expérience de navigation fluide et interactive.
* Ce projet mettra également en avant des concepts clés comme le prompting, la personnalisation des réponses et l’intégration de plusieurs composants techniques (FAISS, SQLite, Memory) afin de rendre le chatbot plus robuste et performant.

* **Objectifs du projet**


Exploiter des outils avancés dans un agent conversationnel pour effectuer diverses actions :
Recherche de produits dans une base de données.
Gestion d’un panier d’achat.
Expérimenter le prompting afin de guider le modèle de langage dans des tâches complexes et garantir une conversation fluide.
Intégrer des composants supplémentaires pour enrichir les capacités du chatbot :
FAISS pour l’indexation vectorielle des produits.
SQLite comme base de données.
Memory pour assurer un suivi du contexte conversationnel.

* **Structure du  projet**

Ce Projet repose sur une base de code déjà fournie, qui inclut :

Une fonction de recherche de produits basée sur un index vectoriel (FAISS).
Un système de panier permettant l’ajout, la suppression et la mise à jour des produits sélectionnés.
Un agent LangChain configuré pour comprendre les requêtes des utilisateurs et activer les outils appropriés.


* **Plan du projet**

Chargement des données.
Intégration des données dans une base SQLite.
Vectorisation des titres des produits et indexation avec FAISS.
Construction des outils et implémentation de l'agent conversationnel.