# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T18:05:54+00:00 -- Run `20260528T180023Z-d01c8d01`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie correctement le problème opérationnel et nomme un rôle agentique pertinent, mais il manque de détails chiffrés, de grille d'évaluation et de différenciation organisationnelle. Pour améliorer, ajoutez une fiche organisationnelle comparative PME/Grande, une grille justificative complète et des conditions de succès mesurables.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le document se contente d'indiquer « Morgan Stanley » sans taille, budget ni différenciation PME vs grande entreprise.
- Piste d'amélioration : Ajouter une brève fiche organisationnelle (taille, secteur, budget approximatif) et expliciter comment la recommandation diffère pour une PME vs une grande entreprise.

**Justification criteres**
- Observation : Aucune grille avec critères (impact, faisabilité, risque, coût) et justifications n'est fournie dans le brief.
- Piste d'amélioration : Compléter une grille pour les trois options en remplissant les quatre critères par cellule avec des justifications chiffrées ou hypothèses vérifiables.

**Role specialise identifie**
- Observation : Le rôle est nommé « Agent analyste de recherche », mais la description métier et un exemple concret manquent.
- Piste d'amélioration : Décrire précisément en langage métier ce que fait l'agent (ex. : priorisation des rapports, résumés pour décideurs) et donner un exemple concret d'utilisation.

**Recommandation argumentee**
- Observation : Le brief ne formule pas de recommandation claire ni ne compare explicitement les options ou compromis.
- Piste d'amélioration : Formuler une recommandation distincte (par ex. prioriser un pilote interne) et expliquer pourquoi les autres options sont écartées en termes de valeur et risque.

**Role specialise**
- Observation : Il est suggéré que l'agent réduit le travail des juniors, sans préciser quel expert humain il remplace ou augmente et pourquoi ce rôle est stratégique.
- Piste d'amélioration : Préciser quel expert est remplacé/augmenté (ex. : analyste junior de recherche) et expliquer en quoi ce rôle est stratégique pour les décisions d'investissement.

**Probleme affaires**
- Observation : Le problème est formulé : recherches complexes et travail long souvent confié à des juniors surchargés.
- Piste d'amélioration : Renforcer l'ancrage en ajoutant un indicateur chiffré (ex. : heures/hebdomaire passées en recherches, % d'analyses remises à plus tard).

**Valeur creee**
- Observation : La valeur est décrite qualitativement (réponses immédiates, moins de travail low value pour les juniors) sans quantification.
- Piste d'amélioration : Quantifier la valeur attendue (ex. : réduction estimée du temps de recherche de X %, gain de productivité Y €) et lier ces chiffres au rôle de l'agent.

**Risque mitigation**
- Observation : Risques listés : hallucination, perte de rôles juniors, fuite de données ; mitiga­tions proposées de façon vague (« on entraine le modèle assez », garanties de postes).
- Piste d'amélioration : Proposer mesures concrètes (ex. : pipeline de validation humaine, tests de biais trimestriels, chiffrement des données et clauses contractuelles) et un calendrier d'audit.

**Condition succes**
- Observation : Conditions citées (équipe spécialisée, plan, suivi, qualité des données) mais formulées de manière générique et non mesurable.
- Piste d'amélioration : Définir une ou deux conditions mesurables et temporelles (ex. : adoption ≥ 70 % par les analystes en 6 mois, réduction des tâches manuelles de 50 %).

**Ai disclosure**
- Observation : Rappel de mettre à jour ai-usage.md mais le fichier ou son contenu n'est pas fourni dans le brief.
- Piste d'amélioration : Inclure ou joindre ai-usage.md indiquant les outils utilisés (ou « aucun »), étapes d'utilisation, validation humaine et limites observées.

_Quelques points appellent une attention particulière lors de la prochaine itération : ai_usage_missing._

## 3. Déclaration d'utilisation de l'IA

> L'étudiant indique explicitement n'avoir utilisé aucun outil IA, ce qui couvre l'identification de l'outil. Cependant la déclaration ne décrit pas de méthodes de validation humaine ni les limites/erreurs observées, ces éléments sont manquants.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- comment la sortie a été validée par l'humain
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Réviser le brief en tenant compte des observations par dimension de la section 2.
- Compléter `ai-usage.md` en y ajoutant : comment la sortie a été validée par l'humain.
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T180023Z-d01c8d01`
- **Devoir :** `S01`
- **Étudiant·e :** `FelixD67`
- **Commit analysé :** `46f655e`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T180023Z-d01c8d01/FelixD67/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
