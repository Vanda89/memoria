# Parcours de montée en compétence IA sur 8 semaines

> Objectif : passer d'une utilisation assistée de l'IA à une posture d'architecte capable de cadrer, évaluer, sécuriser et industrialiser des solutions IA dans un contexte professionnel.

## Finalité

Ce parcours n'est pas centré sur le "vibe coding". L'objectif est de devenir meilleur pour :
- comprendre ce que fait réellement un modèle,
- poser le bon problème,
- choisir la bonne architecture,
- mesurer la qualité,
- gérer les risques,
- et prendre de bonnes décisions en contexte pro.

## Semaine 1

### Fondamentaux IA / LLM

- Comprendre ce qu'est un LLM.
- Comprendre tokens, contexte, latence, coût, température et top-p.
- Distinguer chat, complétion, embeddings, tools et RAG.
- Identifier les limites structurelles : hallucination, biais, non-déterminisme.

### Livrable

- Une fiche de synthèse : "ce que l'IA sait faire / ne sait pas faire".

### Exercice

- Prendre 5 cas d'usage et décider si un LLM est pertinent ou non, avec justification.

## Semaine 2

### Prompting professionnel

- Structurer un prompt : rôle, objectif, contexte, contraintes, format, critères.
- Écrire des prompts robustes et testables.
- Produire des sorties strictes : JSON, tableaux, étapes, décisions.

### Livrable

- Une bibliothèque de 10 prompts réutilisables.

### Exercice

- Réécrire un prompt vague en 3 versions : simple, structurée, production.

## Semaine 3

### Cas d'usage et cadrage

- Transformer une demande métier en problème d'architecture.
- Définir utilisateurs, données, risques, valeur et limites.
- Déterminer si on fait un assistant, un automate, un moteur de recherche, un copilote ou un workflow.

### Livrable

- 3 fiches de cadrage de cas d'usage réels.

### Exercice

- Pour chaque cas, écrire : objectif, données, sortie attendue, échec acceptable, risque critique.

## Semaine 4

### RAG et connaissance métier

- Embeddings, chunking, indexation, recherche sémantique.
- Métadonnées, filtrage, reranking, citations.
- Gestion des sources de vérité et de la fraîcheur.

### Livrable

- Un schéma d'architecture RAG simple.

### Exercice

- Concevoir un mini-système documentaire avec une stratégie de découpage et de récupération.

## Semaine 5

### Évaluation et qualité

- Définir une méthode de test.
- Construire des jeux de questions/réponses.
- Mesurer précision, pertinence, couverture, stabilité, coût, latence.
- Comparer des variantes de prompt ou de modèle.

### Livrable

- Un plan d'évaluation avec critères mesurables.

### Exercice

- Créer un benchmark sur 20 cas tests et noter les résultats de manière répétable.

## Semaine 6

### Sécurité, conformité, gouvernance

- Données sensibles, anonymisation, rétention, secrets.
- Prompt injection, exfiltration, jailbreak.
- Validation humaine sur les cas à risque.
- Gouvernance d'usage en entreprise.

### Livrable

- Une grille des risques par type de cas d'usage.

### Exercice

- Auditer un cas d'usage et lister les menaces, impacts et garde-fous.

## Semaine 7

### Architecture de production

- API, orchestration, retries, timeouts, fallback.
- Observabilité, logs, traçabilité.
- Résilience et dégradation gracieuse.
- Arbitrage qualité / coût / performance.

### Livrable

- Un blueprint d'architecture cible pour un projet IA.

### Exercice

- Décrire le passage prototype -> production, étape par étape.

## Semaine 8

### Posture d'architecte IA

- Prendre des décisions d'architecture.
- Dire non à un mauvais usage.
- Construire une stratégie d'adoption.
- Industrialiser la gouvernance et l'amélioration continue.

### Livrable

- Ton référentiel personnel d'architecte IA.

### Exercice final

- Présenter un dossier complet sur un cas d'usage : valeur, architecture, risques, évaluation, coût, gouvernance, plan de déploiement.

## Méthode de travail recommandée

- 30 % théorie, 70 % pratique.
- Un cas réel par semaine.
- Une fiche de synthèse à chaque étape.
- Un rituel d'évaluation systématique : ce qui est prouvé, ce qui est supposé, ce qui est risqué.

## Ce que tu dois viser

- Semaine 1 à 2 : comprendre et manipuler correctement.
- Semaine 3 à 5 : concevoir et vérifier.
- Semaine 6 à 8 : sécuriser, industrialiser, piloter.
