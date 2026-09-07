# Cartes IA — parcours de montée en compétence sur 8 semaines

> Cartes de révision associées à [[Parcours de montée en compétence IA sur 8 semaines]]. Format volontairement simple pour une révision rapide dans Obsidian.

## Semaine 1 — Fondamentaux

### Carte 1

**Question**  
Qu'est-ce qu'un LLM, en une phrase ?

**Réponse**  
Un modèle statistique qui prédit le prochain token à partir d'un contexte textuel.

### Carte 2

**Question**  
Pourquoi un LLM peut-il halluciner ?

**Réponse**  
Parce qu'il optimise une prédiction plausible, pas une vérité garantie.

### Carte 3

**Question**  
Quels sont les 4 paramètres qu'il faut toujours garder en tête avec un LLM ?

**Réponse**  
Contexte, latence, coût, qualité.

### Carte 4

**Question**  
Quelle différence entre embeddings et génération ?

**Réponse**  
Les embeddings servent à représenter et comparer du contenu, la génération sert à produire du texte.

## Semaine 2 — Prompting

### Carte 5

**Question**  
Quels blocs structurent un bon prompt professionnel ?

**Réponse**  
Rôle, objectif, contexte, contraintes, format de sortie, critères de réussite.

### Carte 6

**Question**  
Pourquoi faut-il éviter les prompts vagues ?

**Réponse**  
Parce qu'ils produisent des sorties instables, difficiles à tester et peu fiables en production.

### Carte 7

**Question**  
Quel est l'intérêt d'imposer un format de sortie strict ?

**Réponse**  
Faciliter la validation, l'automatisation et l'intégration dans un système.

## Semaine 3 — Cadrage

### Carte 8

**Question**  
Quel est le premier réflexe d'architecte face à une demande IA ?

**Réponse**  
Reformuler le besoin métier avant de parler de modèle ou de prompt.

### Carte 9

**Question**  
Pourquoi distinguer assistant, automate, moteur de recherche et workflow ?

**Réponse**  
Parce que chaque forme d'usage implique un niveau de risque, d'autonomie et de validation différent.

### Carte 10

**Question**  
Quel document minimal faut-il produire pour cadrer un cas d'usage IA ?

**Réponse**  
Objectif, utilisateurs, données, risques, sortie attendue, critères de succès.

## Semaine 4 — RAG

### Carte 11

**Question**  
À quoi sert un système RAG ?

**Réponse**  
À faire générer une réponse à partir de sources récupérées dans un corpus maîtrisé.

### Carte 12

**Question**  
Quels sont les 3 problèmes classiques d'un RAG mal conçu ?

**Réponse**  
Mauvais découpage, mauvaise recherche, mauvaise hiérarchisation des sources.

### Carte 13

**Question**  
Pourquoi les métadonnées sont-elles importantes en RAG ?

**Réponse**  
Parce qu'elles permettent de filtrer, prioriser et contextualiser les sources.

## Semaine 5 — Évaluation

### Carte 14

**Question**  
Pourquoi faut-il évaluer un système IA avec un jeu de tests ?

**Réponse**  
Pour mesurer de façon répétable la qualité réelle, pas seulement l'impression produite en démo.

### Carte 15

**Question**  
Quelles métriques suivre en priorité pour un système IA ?

**Réponse**  
Pertinence, exactitude, stabilité, latence et coût.

### Carte 16

**Question**  
Que prouve un benchmark de 20 cas tests ?

**Réponse**  
Il donne une base de comparaison fiable entre variantes de prompt, de modèle ou d'architecture.

## Semaine 6 — Sécurité

### Carte 17

**Question**  
Qu'est-ce qu'une prompt injection ?

**Réponse**  
Une consigne malveillante insérée dans les données pour détourner le comportement du modèle.

### Carte 18

**Question**  
Pourquoi faut-il traiter les données sensibles avec prudence dans un projet IA ?

**Réponse**  
Parce qu'elles peuvent fuiter, être loggées, réutilisées ou exposées à des tiers si l'architecture est mal cadrée.

## Semaine 7 — Production

### Carte 19

**Question**  
Qu'est-ce qui différencie un prototype d'une architecture de production ?

**Réponse**  
La gestion des erreurs, de l'observabilité, du coût, de la sécurité et des dégradations.

### Carte 20

**Question**  
Pourquoi prévoir des retries, timeouts et fallback ?

**Réponse**  
Pour rendre le système résilient face aux erreurs et à la variabilité des services IA.

## Semaine 8 — Posture d'architecte

### Carte 21

**Question**  
Quelle est la vraie responsabilité d'un architecte IA ?

**Réponse**  
Choisir, cadrer et faire tenir un système utile, mesurable, sûr et exploitable dans la durée.

### Carte 22

**Question**  
Quand faut-il dire non à une demande IA ?

**Réponse**  
Quand la valeur est faible, le risque est trop élevé, ou qu'une solution plus simple suffit.

### Carte 23

**Question**  
Pourquoi la gouvernance fait-elle partie du travail d'architecte IA ?

**Réponse**  
Parce qu'un système IA sans règles d'usage, de contrôle et de suivi dérive rapidement.

## Cartes transverses

### Carte 24

**Question**  
Quel est le meilleur réflexe quand un cas d'usage semble "impressionnant" mais flou ?

**Réponse**  
Le ramener à un besoin concret, un risque concret et une métrique concrète.

### Carte 25

**Question**  
Quel est l'objectif principal de ce parcours ?

**Réponse**  
Devenir capable de concevoir et piloter des solutions IA professionnelles, pas seulement d'utiliser un chatbot.
