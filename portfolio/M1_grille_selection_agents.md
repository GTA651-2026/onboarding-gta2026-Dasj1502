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

**Profil :** PME québécoise du secteur manufacturier/services avec maturité numérique faible à moyenne, budget IA limité (5 000–15 000 $ CAD annuel), équipe IT réduite (1–2 personnes partagées).

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** _(nommez le spécialiste que l'agent remplace/augmente)_ | **Agent Comptable / Trésorier IA** — automatise rapprochements bancaires, suivi des dépenses, alertes de flux de trésorerie | **Agent Gestionnaire de Leads / CRM** — augmente l'équipe ventes (1–2 vendeurs), prédit opportunités, recommande actions | **Agent Assistant Bureautique** — augmente productivité généraliste (RH, admin, support), génère rapports, résume réunions |
| **2. Impact d'affaires** _(1-5 + justification en 1 phrase)_ | **4/5** — Réduit les erreurs de trésorerie et libère le gestionnaire pour tâches stratégiques; ROI rapide si volume transactionnel élevé. | **3/5** — Améliore le suivi client mais dépend de qualité données existantes (CRM peu mature = faible adoption). | **4/5** — Impact immédiat sur productivité; applicable à tous les départements, faible friction à l'adoption. |
| **3. Faisabilité PME** _(1-5 + données, compétences, intégration)_ | **3/5** — Nécessite intégration systèmes comptables (Xero, QuickBooks); dépendance bancaire (Brex compte courant recommandé); IT modérée. | **2/5** — Requiert Salesforce existant (coût supplémentaire ~60 $ USD/mois); formation ventes essentielle; faible expertise interne. | **5/5** — Plug-and-play si Microsoft 365 existant; zéro infrastructure IT; formation utilisateurs simple et autonome. |
| **4. Coût estimé** _(ordre de grandeur annuel + TCO si pertinent)_ | **8 000–12 000 $ CAD/an** — Plan PME Brex ~600 $/mois (services + frais) + intégration comptable ~2 000 $ (one-time). | **6 000–18 000 $ CAD/an** — Sales Cloud ~100 $/user/mois (3 utilisateurs minimum) + Einstein ~50 $/user/mois + formation ~2 000 $. | **3 000–6 000 $ CAD/an** — Copilot 365 ~30 $ CAD/utilisateur/mois (50 employés max nécessaires, focus petit groupe) + déploiement minimal. |
| **5. Risque principal** _(et mitigation concrète)_ | **Risque de dépendance bancaire Brex** — Mitigation : adopter progressivement, garder processus manuel en parallèle, vérifier conformité Loi 25 (données bancaires protégées). | **Risque de mauvaise adoption SI données CRM défaillantes** — Mitigation : audit données pré-déploiement, formation intense ventes, KPIs clairs. | **Risque de surcoûts licences non utilisées** — Mitigation : pilote auprès de 15–20 utilisateurs, puis déploiement progressif; évaluation ROI réelle à 6 mois. |

### Recommandation pour la PME

**Déployer d'abord Microsoft Copilot 365** (T0, 3 mois) pour maximiser ROI rapide et adoption transversale, puis **évaluer Brex** (T+6 mois) si trésorerie devient critère décisionnel. Salesforce Einstein est prématuré : coût + complexité trop élevés pour retour CRM insuffisant. **Raison :** La PME a besoin de productivité immédiate (Copilot), pas de spécialisation (Brex nécessite volume financier élevé) ou de CRM lourd (Salesforce).

---

## Contexte 2 — Grande entreprise de 500+ employés

**Profil :** Entreprise québécoise multi-départements, systèmes ERP/CRM matures (SAP/Salesforce existant), gouvernance stricte (Loi 25, normes ISO 27001), sponsor C-suite (CFO ou VP Ventes), budget IA sans limite stricte (100 000–500 000 $ CAD annuel).

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | **Agent Contrôleur Financier / Trésorier IA** — synchronise multiples flux (comptabilité, trésorerie, prévisions); augmente équipe finance (8–12 FTE) | **Agent VP Commercial / Revenue Ops** — orchestre prédiction pipeline, recommande stratégies tarification, optimise allocation ressources ventes | **Agent Collaborateur Ubiquitaire** — augmente 500 employés, fédère connaissances (intégration Teams, SharePoint, PowerBI) |
| **2. Impact d'affaires** _(1-5 + justification)_ | **4/5** — Réduit cycle prévisions financières de 5 jours à 1 jour; améliore visibilité trésorerie multidevise; libère CFO pour stratégie. | **5/5** — Augmente win-rate pipeline de 5–15%; réduit cycle vente de 30%; impact direct revenue si équipe >50 vendeurs. | **3/5** — Améliore productivité transverse mais impact financier diffus (pas de métrique directe par département). |
| **3. Faisabilité grande entreprise** _(1-5 + intégration systèmes, gouvernance)_ | **4/5** — Intégration native SAP/Oracle possible; conformité auditée (SOC 2, ISO 27001); déploiement 4–6 mois avec CISO sign-off. | **5/5** — Einstein natif Salesforce si Sales Cloud existant; gouvernance données triviale; déploiement 2–3 mois, ROI prévisible. | **4/5** — Intégration Microsoft Graph (Power BI, Teams, Dynamics 365); conformité automatisée; déploiement 3 mois. |
| **4. Coût estimé** _(licences + intégration + formation)_ | **150 000–250 000 $ CAD/an** — Brex Enterprise (API + multi-entity) ~15 000 $/mois + SAP integration ~50 000 $ (one-time) + formation finance ~10 000 $. | **200 000–400 000 $ CAD/an** — Einstein pack ~100 $/user/mois (100+ sales users) + Salesforce premium ~400 $/user/mois (20 admins) + enablement program ~30 000 $. | **120 000–180 000 $ CAD/an** — Copilot Pro + Microsoft 365 Business Premium ~30–50 $ CAD/utilisateur/mois (500 users avg., pas tous day-1) + TAM ~15 000 $. |
| **5. Risque principal** _(et mitigation)_ | **Risque de perte contrôle audit / conformité Loi 25** — Mitigation : governance board Finance-IT-Audit, audit Einstein annuel, chiffrement données sensibles (PIPEDA). | **Risque de transformation ventes chaotique** — Mitigation : sponsor VP Ventes, change management programme 6 mois, mesure adoption hebdo, incentives alignés. | **Risque de shadow IT / données échappant governance** — Mitigation : policy utilisateur strict (Data Loss Prevention), audit Teams mensuel, formation sécurité obligatoire. |

### Recommandation pour la grande entreprise

**Prioriser Salesforce Einstein** (T0, 6–9 mois) car l'entreprise a équipe ventes large (ROI maximal), infrastructure Salesforce existante, et governance mature pour gérer transformation. **En parallèle**, déployer **Microsoft Copilot 365** (T+3 mois, quick-win) pour gains productivité transversaux. **Reporter Brex** à T+12 mois (évaluation post-CFO), sauf si stratégie trésorerie multidevise critique aujourd'hui.

**Différence vs PME :** La grande entreprise peut absorber complexité Salesforce (ROI ventes justifie investissement), a besoin de spécialisation (Einstein), et doit sécuriser transformation changement. La PME, elle, privilégie rapidité et universalité (Copilot).

---

## Synthèse — ce que la grille révèle

La sélection optimale d'une solution IA n'est **pas absolue** : elle dépend de trois leviers critiques :
1. **Rôle orchestré** — Quelle douleur métier est la plus aiguë ? (PME = productivité générale; GE = spécialisation revenu/finance.)
2. **Maturité système** — Qu'avez-vous déjà ? (PME = vierge = go simple; GE = complexe = go native.)
3. **Capacité absorption changement** — Avez-vous sponsor, gouvernance, talent IT ? (PME = non = phasing; GE = oui = accélération.)

**Leçon clé pour Examen-cas 1 :** Ne jamais choisir « la meilleure solution IA générique ». Toujours poser trois questions :
- Quel problème résout-on *réellement* ?
- Qui l'utilise et a-t-il la maturité ?
- Combien ça coûte *en totalité* (licence + intégration + risque) relativement au ROI métier ?

Le contexte québécois (Loi 25, marché petit/talent limité) ajoute une contrainte : une solution non conforme ou trop complexe pour nos équipes IT sera toujours inférieure à une solution "moins puissante" mais déployable en 3 mois.

---

## Liste de contrôle de remise

- [x] Les 3 agents sont comparés sur les mêmes 5 critères dans les deux contextes
- [x] Le rôle spécialisé orchestré est nommé précisément pour chaque agent
- [x] Les scores sont justifiés (pas juste des chiffres)
- [x] La recommandation diffère — ou est explicitement justifiée comme identique — entre PME et grande entreprise
- [x] Le contexte d'une organisation québécoise est pris en compte (Loi 25, marché local, talent)
- [ ] `ai-usage.md` mis à jour à la racine du dépôt

---

## Sources consultées

- **Brex Official Website & AI Features** — https://www.brex.com/, https://www.brex.com/blog/ai-features, https://www.brex.com/product/finance, https://www.brex.com/pricing
- **Brex Developer Documentation** — https://developer.brex.com/, https://support.brex.com/
- **Brex Case Studies** — https://www.brex.com/customers

- **Salesforce Einstein Official** — https://www.salesforce.com/products/einstein/overview/
- **Einstein Sales Cloud & Service Cloud** — https://www.salesforce.com/products/sales-cloud/einstein/, https://www.salesforce.com/products/service-cloud/einstein/
- **Salesforce Trailhead** — https://trailhead.salesforce.com/en/content/learn/trails/learn_einstein
- **Salesforce ROI & Benchmarks** — https://www.salesforce.com/products/sales-cloud/roi/

- **Microsoft Copilot for Microsoft 365** — https://www.microsoft.com/en-us/microsoft-365/business/microsoft-copilot-for-microsoft-365
- **Copilot Admin Guide & Deployment** — https://learn.microsoft.com/en-us/microsoft-365-copilot/microsoft-365-copilot-overview, https://learn.microsoft.com/en-us/microsoft-365-copilot/microsoft-365-copilot-adoption
- **Copilot Studio** — https://learn.microsoft.com/en-us/microsoft-copilot-studio/
- **Microsoft Copilot ROI Study** — https://www.microsoft.com/en-us/microsoft-365/copilot/roistudies

- **Contexte Québécois & Loi 25** — https://www.cnil.fr/fr/rgpd-et-ia, https://www.opc.gouv.qc.ca/
- **Organismes Québécois IA** — https://www.montrealinternational.com/, https://www.quebec.ca/gouvernement/ministeres-organismes/ai

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).
