# L3 — Risques du cycle de vie d'un agent IA

**Étudiant·e** : FelixD67 - Félix Desrochers

**Séance** : S03 — Déployer et gérer un agent IA  
**Date limite** : avant le début de S04

---

## Contexte

Un agent IA comporte des risques à chaque phase de son cycle de vie : conception,
déploiement et opération. Ce livrable vous demande d'identifier **3 risques distincts**
associés à un agent IA de votre choix et de proposer une mitigation concrète pour chacun.

Précisez l'agent et le contexte organisationnel en tête de document (½ ligne suffit).

**Agent choisi** : Agent IA de présélection de candidatures pour une PME de services-conseils de 80 employés, utilisé par l’équipe RH pour classer les CV avant la révision humaine.

---

## Risque 1 — Biais dans la présélection des candidatures

**Phase du cycle de vie** : Conception

**Description** :
L’agent IA peut reproduire des biais présents dans les données historiques de recrutement, par exemple en favorisant certains profils scolaires, parcours professionnels ou mots-clés déjà associés aux employés actuels. Ce risque est particulièrement important si l’organisation définit mal les critères de sélection ou si elle utilise des données passées sans vérifier leur représentativité.

**Impact potentiel** :
L’organisation pourrait écarter de bons candidats atypiques, réduire la diversité des profils retenus et s’exposer à des enjeux d’équité ou de conformité en matière de recrutement.

**Mitigation proposée** :
Définir dès le départ des critères de sélection clairs, justifiables et liés au poste, puis tester l’agent avec un jeu de données diversifié et anonymisé. Les résultats devraient être validés par l’équipe RH avant le déploiement, avec une vérification des écarts de recommandation entre différents types de profils.

---

## Risque 2 — Mauvaise intégration au processus RH existant

**Phase du cycle de vie** : Déploiement

**Description** :
Lors du déploiement, l’agent IA pourrait être mal intégré au système de suivi des candidatures ou aux habitudes de travail de l’équipe RH. Par exemple, les recruteurs pourraient recevoir des classements sans explication claire, ou encore devoir faire des doubles saisies entre l’outil IA et le système RH existant.

**Impact potentiel** :
Le projet pourrait perdre en crédibilité auprès des utilisateurs, ralentir plutôt qu’améliorer le processus de recrutement et créer une résistance au changement de la part des recruteurs.

**Mitigation proposée** :
Déployer l’agent progressivement avec un projet pilote sur quelques postes seulement, tout en recueillant les commentaires des recruteurs. Il faut aussi prévoir une formation courte, documenter le rôle exact de l’agent et s’assurer que ses recommandations sont compréhensibles et faciles à réviser.

---

## Risque 3 — Surconfiance envers les recommandations de l’IA

**Phase du cycle de vie** : Opération

**Description** :
Une fois l’agent utilisé régulièrement, les recruteurs pourraient accorder trop de confiance aux recommandations de l’IA et accepter les candidats classés en tête sans exercer suffisamment leur jugement professionnel. Ce risque peut augmenter avec le temps si l’outil semble performant et que les utilisateurs oublient ses limites.

**Impact potentiel** :
L’organisation pourrait prendre des décisions de recrutement moins nuancées, passer à côté de candidats pertinents et créer une dépendance excessive envers l’outil plutôt qu’un réel soutien à la décision.

**Mitigation proposée** :
Maintenir une supervision humaine obligatoire pour toute décision finale et effectuer un suivi régulier des recommandations de l’agent. Des audits mensuels devraient comparer les choix de l’IA avec les décisions finales des recruteurs afin de détecter les erreurs récurrentes, les biais ou une baisse de qualité dans le temps.

---

*Longueur cible : ½ page. Remettez ce fichier complété (Markdown ou PDF) sous
`portfolio/L3_risques_cycle_vie.pdf` avant le début de S04.*
