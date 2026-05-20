# M1 — Grille de sélection et évaluation de solutions IA

> Comparez **Brex** (CFO virtuel), **Salesforce Einstein** (aide à la décision commerciale)
> et **Microsoft Copilot 365** (productivité) sur 5 critères, pour **deux contextes** :
> une PME de 50 employés et une grande entreprise de 500+ employés.
> Concluez par une **recommandation argumentée par contexte**.
>
> Exportez en PDF et déposez `M1_grille_selection_agents.pdf` dans ce dossier.
> Mettez à jour `ai-usage.md` à la racine du dépôt (obligatoire, même si « Aucun »).

---

## Contexte 1 — PME de 50 employés

Agence de communication, Montréal. Suite Google Workspace en place, aucun CRM ni CFO dédié. Budget IA estimé à
10 000-20 000 $/an. Pas d'équipe IT interne. Contraintes Loi 25 applicables.

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré**  |Agent CFO virtuel : catégorise les dépenses, génère des rapports budgétaires et alerte sur les anomalies.|Agent analyste commercial : prédit la probabilité de fermeture des opportunités et priorise les leads.|Agent assistant polyvalent : résume les réunions, rédige des courriels et produit des ébauches de documents.|
| **2. Impact d'affaires**  |3/5. Comble un manque réel, mais le volume de transactions reste trop faible pour rentabiliser pleinement l'outil.|1/5. Sans données CRM historiques, l'agent n'a rien à analyser. La valeur est nulle à court terme.|5/5. Impact immédiat sur les 50 employés sans aucun prérequis. Les gains de productivité sont visibles dès la première semaine.|
| **3. Faisabilité PME**  |3/5. Déploiement rapide, mais il faut migrer les comptes bancaires vers la plateforme Brex.|1/5. Nécessite un CRM Salesforce actif avec données propres. Coût d'entrée hors budget pour une PME.|5/5. Infrastructure déjà en place. Activation en quelques clics, formation légère.|
| **4. Coût estimé**  |10 000 à 15 000 $/an. Pas de frais d'intégration importants.|40 000 à 80 000 $/an en licences, plus 15 000 à 25 000 $ pour l'implantation. Hors budget.|Environ 7 200 $/an (12 $/utilisateur/mois x 50). TCO minimal.|
| **5. Risque principal**  |Dépendance aux décisions financières automatisées. Conserver un comptable externe pour valider les états trimestriels.|Déploiement sans données utiles. Ne pas activer avant d'avoir 12 mois de saisie CRM structurée.|Conformité Loi 25 sur les données clients. Activer la résidence des données Canada dans les paramètres|




### Recommandation pour la PME

Microsoft Copilot 365 est le premier déploiement à faire : l'infrastructure est déjà là, le coût est le plus bas et l'impact
touche tout le monde immédiatement. Brex vient ensuite pour couvrir le vide financier, à condition d'accompagner la
migration avec un comptable externe. Salesforce Einstein est à mettre de côté pour l'instant : sans données CRM en
amont, l'investissement ne produit rien.

---

## Contexte 2 — Grande entreprise de 500+ employés

Distributeur industriel québécois, 620 employés, présence dans trois provinces. ERP Oracle actif, CRM Salesforce
déployé depuis 4 ans avec environ 70 % de complétude. Équipe IT de 18 personnes. Conformité Loi 25 et ISO 27001.
Sponsor : VP Ventes

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** |Agent analyste financier de support : complément ponctuel à l'équipe finance pour les analyses de dépenses par division.|Agent directeur commercial adjoint : orchestre la priorisation des opportunités pour 45 représentants répartis dans trois régions.|Agent assistant d'entreprise : productivité des 620 employés pour les réunions, courriels et documents internes.|
| **2. Impact d'affaires**  |2/5. L'ERP Oracle et le CFO en poste couvrent déjà ces besoins. L'apport marginal ne justifie pas le déploiement.|5/5. Avec 4 ans de données Salesforce, Einstein peut augmenter les taux de conversion de 25 à 35 % selon les données Salesforce (State of Sales, 2024).|4/5. Gains de productivité mesurables à grande échelle, mais moins différenciants que Einstein dans ce contexte commercial.|
| **3. Faisabilité grande entreprise**  |1/5. L'intégration avec Oracle est complexe et coûteuse pour un bénéfice qui n'existe pas dans cet environnement.|5/5. Tout est en place : Salesforce actif, équipe IT compétente, sponsor exécutif. Activation directe dans l'environnement existant.|4/5. Faisable si Microsoft 365 est déployé. Demande une politique de gouvernance et une formation pour 620 personnes.|
| **4. Coût estimé**  |100 000 à 150 000 $/an en licences et intégration Oracle. Aucun ROI démontrable.|180 000 à 280 000 $/an. ROI fort : une hausse de 25 % des conversions sur un pipeline de 5 M$ rapporte 1,25 M$ additionnel.|Environ 91 000 $/an (12 $/utilisateur/mois x 620) plus 25 000 à 50 000 $ en formation. TCO compétitif sur 3 ans.|
| **5. Risque principal**  |Redondance totale avec Oracle. Ne pas déployer et réorienter le budget vers Einstein ou Copilot.|Qualité des données : le 30 % de saisie manquante biaise les prédictions. Faire un audit Salesforce avant l'activation.|Conformité Loi 25 et ISO 27001 à grande échelle. Activer Microsoft Purview et rendre la formation obligatoire.|

### Recommandation pour la grande entreprise

Salesforce Einstein est la priorité dans ce contexte parce que tous les prérequis sont réunis et que le retour sur
investissement est directement mesurable via les taux de conversion. L'étape préalable est un audit de qualité des
données Salesforce avant l'activation. Microsoft Copilot 365 suit en second pour les gains de productivité à l'échelle des
620 employés. Brex est exclu : Oracle et l'équipe finance couvrent déjà tout ce qu'il apporterait, et l'intégration coûterait
plus qu'elle ne rapporterait.

---

## Synthèse — ce que la grille révèle

Le critère qui a fait basculer les deux décisions est la faisabilité organisationnelle, pas l'impact potentiel de l'agent.
Salesforce Einstein score le plus haut en impact dans les deux contextes, mais il est inutilisable pour la PME faute de
données en amont. Ce que la grille enseigne, c'est qu'évaluer un agent sans définir le contexte ne produit aucune
information utile. La Loi 25 s'applique dans les deux cas et impose une couche de gouvernance sur les solutions cloud
américaines qui ne peut pas être ignorée, même si elle ne change pas le choix final ici. Une bonne recommandation doit
justifier ce qu'on écarte autant que ce qu'on choisit.

---

## Liste de contrôle de remise

- [x] Les 3 agents sont comparés sur les mêmes 5 critères dans les deux contextes
- [x] Le rôle spécialisé orchestré est nommé précisément pour chaque agent
- [x] Les scores sont justifiés (pas juste des chiffres)
- [x] La recommandation diffère — ou est explicitement justifiée comme identique — entre PME et grande entreprise
- [x] Le contexte d'une organisation québécoise est pris en compte (Loi 25, marché local, talent)
- [x] `ai-usage.md` mis à jour à la racine du dépôt

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).
