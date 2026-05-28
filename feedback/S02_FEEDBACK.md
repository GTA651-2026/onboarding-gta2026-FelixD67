# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T21:22:22+00:00 -- Run `20260528T211725Z-bd460c4e`_

Ce document est produit par un pipeline reproductible (validation automatique du livrable + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Rétroaction pédagogique sur le brief

> Le brief présente deux contextes bien définis et une grille comparative convaincante menant à des recommandations contextuelles claires. Il gagnerait à quantifier plus systématiquement les problèmes, les conditions de succès et à fournir le fichier ai-usage.md rempli.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief décrit deux contextes distincts : une PME de 50 employés (agence de communication, budget IA indiqué) et une grande entreprise de 620 employés (distributeur industriel, ERP et CRM en place).
- Piste d'amélioration : Ajouter un montant chiffré non redacté pour le budget IA et préciser le budget IT annuel pour renforcer la comparabilité.

**Justification criteres**
- Observation : La grille présente des justifications pour impact, faisabilité, coût et risque pour chaque agent, mais certaines cellules restent générales (ex. : « gains de productivité » sans métrique précise).
- Piste d'amélioration : Compléter les justifications manquantes par des hypothèses chiffrées ou sources pour chaque cellule (ex. taux d'adoption attendu, temps économisé par tâche).

**Role specialise identifie**
- Observation : Chaque agent est décrit par un rôle métier clair (ex. «Agent CFO virtuel», «Agent analyste commercial», «Agent assistant polyvalent») avec exemples d'activités métier associées.
- Piste d'amélioration : Illustrer pour chaque rôle un cas d'utilisation concret (ex. une tâche quotidienne remplacée) pour renforcer la compréhension métier.

**Recommandation argumentee**
- Observation : Le brief conclut en recommandant Copilot pour la PME et Einstein pour la grande entreprise, en expliquant pourquoi les autres options sont écartées (coût, prérequis de données, redondance).
- Piste d'amélioration : Ajouter un court plan de séquencement et un budget indicatif pour la mise en œuvre afin de rendre la recommandation immédiatement actionnable devant un comité.

**Role specialise**
- Observation : Le document identifie quel expert humain est complété (ex. complément ponctuel à l’équipe finance, directeur commercial adjoint pour les ventes) et pourquoi ces rôles sont stratégiques.
- Piste d'amélioration : Préciser l'impact sur les effectifs ou les responsabilités (ex. réduction du temps passé par l'analyste finance de X %) pour éclairer les enjeux RH.

**Probleme affaires**
- Observation : Le brief présente des besoins opérationnels (manque de CRM pour la PME, optimisation des conversions pour la grande entreprise) mais n'offre pas une formulation concise et chiffrée du problème d'affaires en une phrase.
- Piste d'amélioration : Formuler en une à deux phrases le problème d'affaires pour chaque contexte, avec un indicateur chiffré (ex. délai de facturation, taux de conversion cible).

**Valeur creee**
- Observation : Le document évoque des gains quantifiables (ex. hausse de 25–35 % des conversions, chiffrages de ROI pour Einstein) et des ordres de grandeur pour coûts et économies.
- Piste d'amélioration : Relier explicitement les gains projetés aux métriques financières de l'organisation (ex. impact sur marge ou EBITDA) avec calculs succincts.

**Risque mitigation**
- Observation : Les risques principaux sont nommés (qualité des données, conformité Loi 25, redondance avec ERP) et des mitigations concrètes sont proposées (audit Salesforce, activation résidence des données Canada, Microsoft Purview).
- Piste d'amélioration : Ajouter un calendrier et un responsable pour chaque action de mitigation afin d'en faciliter le suivi opérationnel.

**Condition succes**
- Observation : Le brief ne formule pas d'indicateurs de succès vérifiables (aucun taux d'adoption cible ou horizon temporel n'est précisé).
- Piste d'amélioration : Définir pour chaque contexte une condition de succès mesurable (ex. adoption > 70 % en 6 mois, augmentation du taux de conversion de X % en 12 mois).

**Ai disclosure**
- Observation : Le brief demande de mettre à jour ai-usage.md à la racine du dépôt (obligatoire) mais ne confirme pas son contenu ni les outils effectivement utilisés.
- Piste d'amélioration : Fournir le fichier ai-usage.md rempli précisant outils utilisés (ou « Aucun »), étape d'utilisation, validation humaine et limites observées.

_Quelques points appellent une attention particulière lors de la prochaine itération : ai_usage_non_fourné._

## 2. Déclaration d'utilisation de l'IA

> La déclaration indique qu'aucun outil IA n'a été utilisé, mais elle reste minimaliste et ne détaille pas explicitement les limites ou erreurs potentielles. Merci de remplacer les marqueurs « -- »/« NA » par des affirmations explicites (par ex. « Aucun » pour chaque section) et d'ajouter une ligne sur les limites ou erreurs observées, même si none s'applique.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- limites ou erreurs observées

## 3. Pistes d'action pour la prochaine itération

- Réviser le brief en tenant compte des observations par dimension de la section 1.
- Compléter i-usage.md en y ajoutant : limites ou erreurs observées.

---

## 4. Traçabilité

- **Run ID :** `20260528T211725Z-bd460c4e`
- **Devoir :** `S02`
- **Étudiant·e :** `FelixD67`
- **Commit analysé :** `9a8df16`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T211725Z-bd460c4e/FelixD67/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
