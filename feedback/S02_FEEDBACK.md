# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T17:31:05+00:00 -- Run `20260528T172647Z-afdf4262`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief présente deux contextes bien définis et une grille complète avec justifications chiffrées; les recommandations sont claires et différenciées par profil. Il manque toutefois le fichier ai-usage.md requis et quelques sources pour étayer les chiffres cités.

### Observations par dimension

**Contexte organisationnel**
- Observation : Deux contextes sont décrits: une PME de 50 employés (agence de communication, Google Workspace, budget IA indiqué) et une grande entreprise de 620 employés (distributeur industriel, ERP Oracle, CRM Salesforce).
- Piste d'amélioration : Préciser le montant exact du budget PME (au lieu de [REDACTED]) et ajouter une fourchette budgétaire pluriannuelle pour la grande entreprise.

**Justification criteres**
- Observation : La grille remplit impact, faisabilité, coût et risque pour chaque agent et contexte, avec valeurs chiffrées (ex. coûts annuels, % d'augmentation des conversions) et recommandations liées.
- Piste d'amélioration : Ajouter des sources ou références pour les chiffres cités (ex. étude 'State of Sales, 2024') ou expliciter les hypothèses de calcul du ROI.

**Role specialise identifie**
- Observation : Chaque agent reçoit un rôle métier clair (ex. «Agent CFO virtuel» qui catégorise dépenses; «Agent directeur commercial adjoint» qui priorise opportunités).
- Piste d'amélioration : Fournir un exemple concret d'usage métier pour chaque rôle (ex. un KPI précis suivi après déploiement).

**Recommandation argumentee**
- Observation : Recommandations distinctes par contexte (Copilot pour la PME; Einstein prioritaire pour la grande entreprise) et justification expliquant pourquoi les autres options sont écartées.
- Piste d'amélioration : Inclure un plan de mise en œuvre succinct (phases, indicateurs de succès) pour renforcer la défendabilité devant un comité de direction.

**Ai disclosure**
- Observation : Le document demande de «Mettez à jour ai-usage.md à la racine du dépôt (obligatoire)» mais le fichier ai-usage.md n'est pas fourni avec le brief.
- Piste d'amélioration : Ajouter le fichier ai-usage.md rempli: préciser outils (ou 'aucun'), étapes d'utilisation, validation humaine et limites observées.

_Quelques points appellent une attention particulière lors de la prochaine itération : ai_usage_missing._

## 3. Déclaration d'utilisation de l'IA

> La déclaration indique clairement qu'aucun outil IA n'a été utilisé dans la section outils. Toutefois, plusieurs sections attendues (étape d'utilisation, validation humaine, limites/erreurs) ne sont pas remplies conformément aux consignes.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Réviser le brief en tenant compte des observations par dimension de la section 2.
- Compléter `ai-usage.md` en y ajoutant : à quelle étape l'IA a été utilisée.
- Compléter `ai-usage.md` en y ajoutant : comment la sortie a été validée par l'humain.
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T172647Z-afdf4262`
- **Devoir :** `S02`
- **Étudiant·e :** `FelixD67`
- **Commit analysé :** `c6e5092`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T172647Z-afdf4262/FelixD67/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
