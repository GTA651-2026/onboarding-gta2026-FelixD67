# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T20:16:39+00:00 -- Run `20260528T200936Z-acdfcf6a`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie un problème métier pertinent pour Morgan Stanley et nomme un rôle spécialisé, mais reste trop général et manque de quantification, de justification par critères et de recommandations argumentées. Pour améliorer, ajoutez des chiffres concrets, une grille d'évaluation avec justifications et une recommandation contextuelle explicitant les compromis.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief indique seulement «Morgan Stanley» sans préciser taille, budget ni différenciation PME vs grande entreprise.
- Piste d'amélioration : Ajouter une brève fiche contextuelle (taille, secteur, budget approximatif) et expliciter comment la recommandation diffère pour une PME vs une grande entreprise.

**Justification criteres**
- Observation : Aucune grille avec critères (impact, faisabilité, risque, coût) ou justifications factuelles n'est fournie dans le document.
- Piste d'amélioration : Présenter une grille pour les trois agents avec les quatre critères et fournir au moins une justification chiffrée ou une hypothèse vérifiable pour chaque cellule.

**Role specialise identifie**
- Observation : Le rôle est nommé «Agent analyste de recherche», ce qui exprime la fonction métier ciblée.
- Piste d'amélioration : Préciser pour un des agents un exemple concret d'activité métier (ex. : «produit un résumé exécutif de 1 page pour le gestionnaire») et chiffrer la valeur attendue.

**Recommandation argumentee**
- Observation : Le brief décrit le problème et les risques mais ne formule pas de recommandation finale ni n'expose les compromis entre options.
- Piste d'amélioration : Formuler une recommandation claire (par contexte) et expliciter pourquoi les autres options sont écartées en termes de valeur et risque.

**Role specialise**
- Observation : Le document indique que les recherches sont «remises à des juniors» et mentionne une possible perte de rôle, sans détailler quel expert est remplacé ou augmenté.
- Piste d'amélioration : Identifier précisément l'expert humain concerné (ex. : analyste junior en recherche actions), expliquer comment l'agent l'augmente ou le remplace et pourquoi ce rôle est stratégique.

**Probleme affaires**
- Observation : Le problème est formulé de façon exécutive: «Recherche complexe... Travail long et fastidieux souvent remise à des juniors».
- Piste d'amélioration : Ajouter un ancrage chiffré (ex. : heures par mois perdues, nombre de rapports traités) pour renforcer l'urgence et la portée du problème.

**Valeur creee**
- Observation : La valeur est décrite qualitativement («réponses immédiates», «moins de travail low value pour les juniors») sans quantification.
- Piste d'amélioration : Quantifier l'impact attendu (ex. : réduction du temps de recherche de X%, ou réaffectation de Y heures/mois) et relier directement ces chiffres au rôle de l'agent.

**Risque mitigation**
- Observation : Les risques sont nommés (hallucination, fuite de données, perte d'emplois) et la mitigation citée est vague («on entraine le modèle assez», garanties de postes juniors).
- Piste d'amélioration : Proposer des mesures concrètes et actionnables (ex. : validation humaine systématique, audits périodiques, clauses contractuelles sur la sécurité des données).

**Condition succes**
- Observation : La condition de succès liste composants (équipe spécialisée, plan, suivi, qualité de données) mais sans indicateur mesurable ni horizon temporel.
- Piste d'amélioration : Formuler une condition observable et chiffrée (ex. : adoption utilisateur > 70% en 6 mois, réduction des tâches manuelles de 40% en 12 mois).

**Ai disclosure**
- Observation : Le brief rappelle de mettre à jour ai-usage.md, mais n'indique pas la présence ou le contenu du fichier.
- Piste d'amélioration : Inclure un fichier ai-usage.md précisant outils utilisés (ou «aucun»), étapes d'utilisation, validation humaine et limites observées.

## 3. Déclaration d'utilisation de l'IA

> L'étudiant a clairement déclaré qu'aucun outil d'IA n'a été utilisé et a signé la déclaration de responsabilité. Cependant, certaines sections restent très génériques (par ex. « -- » ou « NA ») plutôt que des phrases explicites confirmant l'absence d'usage dans chaque rubrique.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Aucune correction technique nécessaire. Voir la section 2 pour des pistes d'approfondissement.

---

## 5. Traçabilité

- **Run ID :** `20260528T200936Z-acdfcf6a`
- **Devoir :** `S01`
- **Étudiant·e :** `FelixD67`
- **Commit analysé :** `051afe0`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T200936Z-acdfcf6a/FelixD67/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
