# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T20:50:30+00:00 -- Run `20260528T204526Z-4170164e`_

Ce document est produit par un pipeline reproductible (validation automatique du livrable + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Rétroaction pédagogique sur le brief

> Le brief identifie un problème d'affaires pertinent pour Morgan Stanley et nomme un rôle d'agent, mais il manque de précisions organisationnelles, de justifications chiffrées et d'une recommandation argumentée. Pour améliorer, fournissez une grille de critères justifiée, quantifiez la valeur attendue et formalisez des mitigations et conditions de succès mesurables.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief se contente d'indiquer « Morgan Stanley » sans taille, budget ou différenciation PME vs grande entreprise.
- Piste d'amélioration : Précisez le profil organisationnel (taille, secteur, budget) et donnez une recommandation distincte pour PME et grande entreprise.

**Justification criteres**
- Observation : Aucune grille de sélection ni justification factuelle des scores (impact, faisabilité, risque, coût) n'est fournie.
- Piste d'amélioration : Fournissez une grille avec les trois agents évalués et une justification chiffrée ou hypothèse vérifiable pour chaque critère.

**Role specialise identifie**
- Observation : L'étudiant nomme « Agent analyste de recherche », mais la description reste minimale et en termes génériques.
- Piste d'amélioration : Développez le rôle en langage métier (ex. : quelles décisions spécifiques il supporte) et illustrez par un exemple concret.

**Recommandation argumentee**
- Observation : Aucune recommandation finale claire ou compromis entre options n'est formulé dans le document.
- Piste d'amélioration : Formulez une recommandation par contexte (PME vs grande entreprise), expliquez pourquoi elle est retenue et pourquoi les autres options sont écartées.

**Role specialise**
- Observation : Le texte évoque la réduction du travail des juniors mais n'explique pas quel expert humain est remplacé/augmenté ni pourquoi c'est stratégique.
- Piste d'amélioration : Indiquez précisément quel expert est affecté (ex. : chercheur financier senior, analyste crédit) et pourquoi ce rôle est stratégique pour Morgan Stanley.

**Probleme affaires**
- Observation : Le problème est formulé clairement : recherches complexes et travail fastidieux souvent confié à des juniors.
- Piste d'amélioration : Ajoutez un ancrage chiffré ou un exemple concret (p. ex. temps moyen passé par rapport à un objectif) pour renforcer l'argument exécutif.

**Valeur creee**
- Observation : La valeur est décrite qualitativement (réponses immédiates, moins de travail low value pour les juniors) sans quantification.
- Piste d'amélioration : Quantifiez la valeur attendue (ex. : réduction du temps de recherche de X %, ou gain de productivité estimé pour les juniors).

**Risque mitigation**
- Observation : Les risques (hallucination, perte de postes, fuite de données) sont identifiés et des mitigations générales sont proposées (entraînement, garanties pour les juniors).
- Piste d'amélioration : Rendez les mitigations actionnables (ex. : protocole de validation des réponses, audits réguliers, clauses contractuelles de sécurité).

**Condition succes**
- Observation : La condition de succès mentionne une équipe spécialisée, un plan et une qualité de données élevée, mais reste formulée de façon non-mesurable.
- Piste d'amélioration : Transformez ces éléments en indicateurs observables (ex. : adoption >80% en 6 mois, réduction des recherches manuelles de 50%).

**Ai disclosure**
- Observation : ai-usage.md n'est pas fourni dans le brief et n'est pas renseigné ici.
- Piste d'amélioration : Ajoutez un ai-usage.md mentionnant les outils utilisés (ou « aucun »), l'étape d'utilisation, la validation humaine et les limites observées.

_Quelques points appellent une attention particulière lors de la prochaine itération : ai_usage_missing._

## 2. Déclaration d'utilisation de l'IA

> La déclaration indique clairement qu'aucun outil d'IA n'a été utilisé pour ce livrable. Toutefois, elle ne mentionne pas explicitement les limites ou erreurs observées (même pour préciser qu'il n'y en a pas), ce qui était requis.

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

- **Run ID :** `20260528T204526Z-4170164e`
- **Devoir :** `S01`
- **Étudiant·e :** `FelixD67`
- **Commit analysé :** `69c18b4`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T204526Z-4170164e/FelixD67/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
