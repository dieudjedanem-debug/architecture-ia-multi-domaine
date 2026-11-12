# architecture-ia-multi-domaine
Comment garantir la portabilité et la gouvernance unifiée des workloads IA face à la dispersion des environnements et des entités ? L'enjeu est de concevoir une architecture réversible cartographiant les briques (orchestration, données, observabilité) pour déployer un même modèle sur plusieurs domaines sans réécriture.
Contexte 
Les entreprises déploient des modèles et des agents d'IA dans des environnements de plus en plus dispersés : clouds publics, cloud souverain, datacenters internes, edge. Ces déploiements relèvent aussi de plusieurs domaines d'administration : filiales, métiers, partenaires, chacun avec ses règles, ses données et ses contrats. Chaque workload IA est souvent conçu pour un seul environnement. Le changer d'environnement coûte cher, et la gouvernance d'ensemble échappe à l'entreprise. La question est la suivante : comment concevoir, du point de vue de l'entreprise utilisatrice, une architecture qui permette de déployer, d'exploiter et de déplacer ses workloads IA d'un domaine à l'autre, sous une gouvernance unifiée ?

« Multi-domaine » se lit dans deux sens, et votre équipe doit dire lequel elle privilégie
- Les environnements d'exécution : la portabilité d'un workload IA entre cloud, on-premise et edge, avec ses données, ses modèles et ses dépendances.
- Les domaines d'administration : l'exploitation de workloads IA par plusieurs entités qui ont chacune leur gouvernance, leurs politiques et leurs responsabilités.

Objectifs
- Cartographier les briques d'une plateforme IA d'entreprise : orchestration, registre de modèles, données, identités, observabilité, coûts.
- Concevoir une architecture unifiée qui rende un workload IA portable et gouvernable sur les domaines retenus, avec les critères de réversibilité.
- Démontrer le déploiement d'un même workload dans au moins deux domaines, sans le réécrire

Livrables attendus
1. La présentation de soutenance.
2. Le dossier d'architecture : exigences (métier, techniques, réglementaires), vues métier, applicative, données et infrastructure, sécurité
3. Une note de synthèse de trois pages pour un décideur : problème, choix, coût, risques.
4. Un POC qui démontre le point dur de votre architecture, par exemple un même workload IA déployé et supervisé dans deux domaines.
5. Le chiffrage de la mise en production, capex et opex, avec des hypothèses explicites, dont le coût de sortie d'un fournisseur.

Réglementation 
Pour votre cas d'usage, identifiez les textes applicables et les exigences de conception qui en découlent. Intégrez-les dans l'architecture et dans le chiffrage, pas en annexe. Les textes pressentis sont l'AI Act, le Data Act (changement de fournisseur cloud), NIS2, le RGPD et, en finance, DORA. Côté qualifications, la question de SecNumCloud se pose aussi.
