# Compteur de dépendance numérique

Site interactif et pédagogique qui estime ce que la France et l'Union européenne versent chaque année aux fournisseurs numériques extra-européens, surtout américains.

- **Compteur en temps réel** depuis le 1er janvier, par seconde, par habitant
- **Par catégorie** : IaaS, PaaS, SaaS, licences, IA / tokens, puces, matériel, publicité, abonnements grand public
- **Par société et par produit** : Microsoft, AWS, Google, Meta, Oracle, Broadcom / VMware, Palantir, Atlassian, NVIDIA, OpenAI, Anthropic… avec risques et alternatives européennes
- **Projection 2026-2035**, calculateur pour votre organisation, simulation de « kill switch », quiz et glossaire

Point d'ancrage : l'étude Asterès pour le Cigref (avril 2025), 264 Md€ par an d'achats de cloud et de logiciels des entreprises de l'UE au profit de l'économie américaine. Les montants par produit sont des estimations (marge d'erreur d'au moins ±25 %) ; la méthode et les sources sont détaillées en bas de page.

## Déploiement

Un seul fichier, `index.html`, sans dépendance de build. Le workflow `.github/workflows/pages.yml` le publie sur GitHub Pages à chaque push sur `main`.
Réglage unique : *Settings → Pages → Source : GitHub Actions*.

Réalisé pour A la French.
