# Portfolio – Data Scientist / Machine Learning

👋 Bonjour ! Je me forme et me spécialise en **Data Science & Machine Learning**, avec une approche orientée **projets concrets** et **mise en production** (API, CI, déploiement).

📌 **Liens** : [LinkedIn](https://www.linkedin.com/in/yacine-ould-abdel-vetah-2364a62a3/) · [GitHub](https://github.com/Vagaboss) · [CV](LIEN_CV_OPTIONNEL)


## 🗺️ Carte mentale – compétences & parcours

<a href="assets/Steps of Problem Solving.png">
  <img src="assets/Steps of Problem Solving.png" alt="Carte mentale – cliquer pour zoomer" width="650">
</a>

*Cliquer sur l’image pour l’agrandir.*

---

## [Projet personnel – Prévision des ventes à J+7 (M5 Forecasting – CA)](https://github.com/Vagaboss/P13-perso-predictions)

**Objectif :** prédire les ventes à **J+7** à partir de données historiques et calendaires, sur un périmètre volontairement simplifié (**Californie – CA**).  
**Approche :** baseline + modèles ML (régression linéaire retenue), features temporelles + historiques, validation temporelle.  
**Mise en production :** API FastAPI + app Streamlit, tests + CI, monitoring léger (logs + métriques).

✅ **Voir / tester :**
- Repo : [GitHub](https://github.com/Vagaboss/P13-perso-predictions)
- Démo Streamlit : [Application](https://p13-perso-predictions-gjuillggcfzc9nwaby6fvj.streamlit.app/)
- Rapport (PDF) : [Rapport](LIEN_RAPPORT_PDF)

![](/images/P13IMG.PNG)
---

## 📄 Rapport de formation Openclassrooms

👉 **[Consulter le rapport (PDF)](assets/Rapport_synthetique.pdf)**


## [Projet : Analyse de données éducatives](https://github.com/Vagaboss/P2-EDU)

**Objectif :** identifier des pays à **fort potentiel** pour **l’expansion internationale** d’une EdTech, à partir des données éducatives de la Banque mondiale.

**Approche :** analyse exploratoire guidée, réduction du périmètre des données, sélection d’indicateurs pertinents, analyse univariée et visualisations orientées enjeux business.

**Livrable :** notebook Jupyter structuré, insights exploitables et recommandations de pays (notamment États-Unis et Chine).

![](/images/p2img.PNG)

## [Projet : Cycle Mlops](https://github.com/Vagaboss/Projet-8-MLOPS2)

**Objectif :** concevoir et déployer une solution de machine learning industrialisable, permettant de prédire un score métier (scoring crédit) tout en intégrant les enjeux de coût business, de traçabilité et de performance en production.

**Approche :** structuration complète d’un projet MLOps : préparation et fusion des données, entraînement et comparaison de plusieurs modèles de classification, optimisation des hyperparamètres et du seuil de décision selon un coût métier pondéré, puis mise en place d’une API de prédiction, du tracking des expériences, du versioning des modèles et du monitoring (dérive des données, performances).

**Livrables :** pipeline d’apprentissage robuste, modèle déployé via API (FastAPI), base de données de logs (inputs/outputs), rapports de monitoring (drift), CI/CD fonctionnelle et documentation technique permettant une mise en production fiable et évolutive.

![](/images/p8img.PNG)


## [Projet : Mise en place RAG LLM](https://github.com/Vagaboss/Projet-9-RAG)

**Objectif :**
Développer un agent conversationnel basé sur une architecture RAG capable de recommander des événements culturels pertinents à partir de données externes, accessible via une API.

**Approche :**
Collecte et préparation de données OpenAgenda, vectorisation sémantique, construction d’une base FAISS, génération de réponses augmentées par un LLM (Mistral), exposition du système via FastAPI et évaluation automatique avec RAGAS.

**Livrables :**
API REST fonctionnelle, base vectorielle persistée, conteneur Docker exécutable localement, script d’évaluation RAGAS et documentation technique 

![](/images/p9img.PNG)

## [Projet : Evaluation LLM](https://github.com/Vagaboss/Projet-10-eval-LLM)

**Objectif :**
Développer un assistant conversationnel basé sur une architecture RAG enrichie par une base SQL, capable d’analyser et d’expliquer des statistiques NBA en combinant données textuelles (Reddit) et données chiffrées (PostgreSQL), avec visualisation automatique.

**Approche :**
Indexation de documents textuels (PDF Reddit) via FAISS, intégration d’une base SQL NBA, orchestration RAG + SQL avec Mistral, génération de graphiques dynamiques (PlotTool) et évaluation des performances à l’aide de RAGAS et Pydantic Logfire.

**Livrables :**
Application Streamlit fonctionnelle, base vectorielle FAISS persistée, base PostgreSQL exploitée par SQL Tool, scripts d’évaluation RAGAS, monitoring Logfire et documentation complète 

![](/images/p10img.PNG)

## [Projet : Recommandation AGRITECH](https://github.com/Vagaboss/P12)

**Objectif :**
Développer une application d’aide à la décision agricole capable de prédire le rendement des cultures et de recommander les cultures les plus rentables selon les conditions climatiques et agronomiques.

**Approche :**
Analyse exploratoire et ACP, entraînement et comparaison de modèles de régression, optimisation des performances et interprétation métier des résultats.
Déploiement du modèle via une API FastAPI, création d’une interface Streamlit et automatisation complète avec Docker et CI/CD.

**Livrables :**
API FastAPI de prédiction et recommandation, application Streamlit interactive, modèle entraîné et évalué avec MLflow.
Pipeline CI/CD GitHub Actions, image Docker déployée, documentation technique et rapport métier

![](/images/p12img.PNG)
