# Salut, je suis Gabriel Trouvé ! 👋

**Développeur Python / Django Freelance & Mentor**

Passionné par l'écosystème Python, je conçois des applications web robustes et performantes. Je suis spécialisé dans le développement backend avec **Django** et **Wagtail**, tout en créant des interfaces dynamiques modernes grâce à la stack **HTMX + Alpine.js**.

---

### 🛑 Note importante sur mon code

> **À l'attention des recruteurs et clients :**
> Les dépôts publics visibles sur ce profil sont soit des **projets anciens** (datant de mes débuts), soit des **supports de mentorat** pour accompagner des développeurs en formation.
> 
> **Ils ne reflètent pas mes standards professionnels actuels** en termes de :
> - Clean Architecture
> - Qualité et propreté du code
> - Couverture de tests (unitaires, d'intégration, etc.)
> - Bonnes pratiques avancées
>
> 👉 **Mes projets complets et professionnels** avec architecture robuste, code propre et tests sont hébergés dans des **dépôts privés** pour des raisons de confidentialité client.
>
> 💼 **Pour évaluer mon code :** Je peux vous donner accès à des dépôts privés pour lesquels je suis autorisé. N'hésitez pas à me contacter pour une démonstration.

---

### 🛠 Stack Technique

J'aime travailler avec des outils qui allient productivité et performance.

**Backend & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Wagtail](https://img.shields.io/badge/Wagtail-43b1b0?style=for-the-badge&logo=wagtail&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST-ff1709?style=for-the-badge&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend & UI**
![HTMX](https://img.shields.io/badge/HTMX-3D5875?style=for-the-badge&logo=htmx&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpinedotjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Qualité & DevOps**
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Linux VPS](https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)

---

### 🚀 Projets Réalisés

Projets menés de bout en bout, de la conception à la mise en production.

| Projet | Description & Détails techniques |
| :--- | :--- |
| **<a href="https://cartooneo.com/" target="_blank">Cartooneo</a>**<br><sub><a href="https://www.pygab.dev/projets/cartooneo/" target="_blank">Étude de cas</a></sub> | **Boutique en ligne de jeux et de livres personnalisés**, développée from scratch. C'est l'un de mes plus gros projets.<br>• *Stack :* Django REST Framework, Nuxt.<br>• *Périmètre :* boutique côté client et outil de production côté équipe, de la photo envoyée par le client jusqu'à la livraison du colis.<br>• *Réalisation :* en partenariat avec <a href="https://hc-digitaliz.com/" target="_blank">hc-digitaliz</a>. |
| **<a href="https://cdf-onsenbray.fr/" target="_blank">Comité des Fêtes v2</a>**<br><sub><a href="https://www.pygab.dev/projets/comit%C3%A9-des-f%C3%AAtes-v2/" target="_blank">Étude de cas</a> · Code : <a href="https://github.com/gabigab117/cdf2-back" target="_blank">API</a> · <a href="https://github.com/gabigab117/cdf2-front" target="_blank">Front</a></sub> | **Refonte complète de l'application de gestion associative**, en production depuis octobre 2026 et livrée par phases.<br>• *Stack :* Python 3.13, Django 6.1, **Django Ninja** 1.7 + Pydantic 2, PostgreSQL 17, Nuxt 4 / Vue 3 / TypeScript strict, Pinia, Tailwind CSS 4.<br>• *Architecture :* API et front en deux dépôts reliés par le schéma **OpenAPI** (types TypeScript générés, vérifiés en CI), vues fines et services épais, SSR pour le site public, SPA pour l'espace bureau, origine unique sans CORS.<br>• *Métier :* agenda public avec abonnement ICS, organisation d'événements (tâches, bénévoles, réservations), documents avec étape de validation, prêts de matériel avec disponibilités calculées jour par jour.<br>• *Qualité :* **100 % de couverture** lignes et branches côté API, plus de 1 000 tests (pytest, Vitest) et parcours Playwright, déploiement continu avec retour automatique à la version précédente si le contrôle de santé échoue.<br>• *Sécurité & RGPD :* API privée par défaut, JWT avec refresh token en cookie httpOnly renouvelé à chaque usage, purge nocturne selon les durées de conservation. |
| **<a href="https://carnetia.fr/" target="_blank">Carnetia</a>**<br><sub><a href="https://www.pygab.dev/projets/carnetia/" target="_blank">Étude de cas</a></sub> | **Plateforme éditoriale freemium sur l'IA** pour le public francophone : radar d'outils avec verdicts, guides tenus à jour, édition hebdomadaire et glossaire.<br>• *Stack :* Django 6 + Django REST Framework, Python 3.13, PostgreSQL, Nuxt 4 / Vue 3 / TypeScript, Nuxt UI v4, Tailwind v4, VPS (Nginx, Gunicorn, systemd).<br>• *Rendu :* SSR route par route pour les pages à enjeu SEO, rendu client pour l'espace membre.<br>• *Auth :* django-allauth en mode headless + JWT avec refresh rotatif, vérification e-mail obligatoire, Cloudflare Turnstile.<br>• *Business :* adhésion **Stripe** par paliers à prix verrouillé à vie, attribution transactionnelle du palier, webhooks idempotents, statut répercuté sur Brevo et sur le rôle **Discord**.<br>• *Contrôle d'accès :* le contenu premium n'est jamais envoyé à un non-membre, l'extrait reste indexable. |
| **Application SAV biomédicale**<br><sub><a href="https://www.pygab.dev/projets/application-sav-biom%C3%A9dicale/" target="_blank">Étude de cas</a></sub> | **Application métier pour une entreprise de maintenance d'équipements biomédicaux**, qui remplace les rapports d'intervention papier.<br>• *Stack :* Django 5.2 LTS + DRF 3.18, Python 3.13, PostgreSQL, Nuxt 4 en SPA (TypeScript strict) servie en statique par Nginx, Pinia, Tailwind v4.<br>• *Architecture :* contrat OpenAPI (drf-spectacular, types TypeScript générés), services métier typés, trois rôles avec données filtrées par client, JWT avec refresh token en cookie httpOnly.<br>• *Métier :* parc de machines identifié par **QR codes**, interventions multi-machines saisies sur mobile, espace client en lecture seule, exports CSV / Excel.<br>• *Rapports :* clôture électronique, **numérotation transactionnelle sans trou**, PDF WeasyPrint généré dans la transaction à partir d'un instantané figé, puis verrouillé. |
| **<a href="https://www.capsulorama.com/" target="_blank">Capsulorama v2</a>**<br><sub><a href="https://www.pygab.dev/projets/capsulorama-v2/" target="_blank">Étude de cas</a></sub> | **E-commerce de capsules de champagne** en ligne depuis 2011 — refonte complète.<br>• *Stack :* Django 5.2 / Python 3.13, PostgreSQL, Celery + Redis, HTMX, Bootstrap 5, Gunicorn + Nginx (VPS).<br>• *Migration legacy :* passage de Django 1.3 / Python 2.7, reprise de 15 ans de données (utilisateurs, capsules, paniers) et de ~160 000 fichiers médias, **hasher SHA1 custom** pour connexion sans reset avec upgrade auto vers PBKDF2.<br>• *Moteur de recherche maison :* multi-mots indépendants, tolérance aux accents (`unicodedata` + extension PostgreSQL `unaccent`), tokenisation regex, recherche multi-champs, autocomplete HTMX temps réel, filtres combinables.<br>• *Intégrations :* Stripe Checkout, PayPal, Brevo, reCAPTCHA v3, django-import-export, django-celery-beat.<br>• *Divers :* panier en session transféré en base à la connexion, multi-domaines avec redirections 301, redirections SEO Nginx. |
| **<a href="https://chronoscola.fr/" target="_blank">ChronoScola</a>**<br><sub><a href="https://www.pygab.dev/projets/chronoscola/" target="_blank">Étude de cas</a></sub> | **SaaS éducatif gamifié** (RPG scolaire, CP → Terminale) — en alpha depuis décembre 2025.<br>• *Stack :* Django 5.2, PostgreSQL, HTMX, django-cotton, Bootstrap 5.3 compilé en Sass, pytest-django.<br>• *IA :* correction automatique des exercices via **DeepSeek**, génération audio des dictées via **OpenAI TTS**, avec quotas IA configurables par utilisateur.<br>• *Business :* abonnements **Stripe** (2 €/mois par bénéficiaire) avec suivi des statuts (active, canceled, past_due), gestion des bénéficiaires par abonnement.<br>• *Métier :* comptes multi-rôles (parents / élèves / enseignants) via django-allauth, système d'invitation, classes virtuelles, partage public/classe/privé, historique des tentatives et analytics de progression. |
| **Comité des Fêtes v1**<br><sub><a href="https://www.pygab.dev/projets/comite-des-fetes/" target="_blank">Étude de cas</a></sub> | **Gestion associative** : événements, documents officiels et comptes-rendus centralisés. Version archivée, remplacée par la v2.<br>• *Stack :* Django 6.0, **Wagtail 7.3**, PostgreSQL, Tailwind CSS 4, Wagtail TestCase.<br>• *Architecture :* hiérarchie de pages Wagtail (`EventIndex` > `Event`), contenu en **StreamField**, modèle `EventImage`, `CustomDocument` étendant la gestion documentaire native.<br>• *Recherche IA :* **OCR via l'API Mistral** au dépôt des documents, puis interrogation des archives en langage naturel.<br>• *Sécurité :* `PageViewRestriction` et visibilité conditionnelle public / membres. |
| **<a href="https://dailyquestionapp.com/fr/" target="_blank">Daily Question</a>**<br><sub><a href="https://www.pygab.dev/projets/daily-question/" target="_blank">Étude de cas</a></sub> | **Sondages quotidiens géolocalisés** avec carte mondiale interactive et gamification.<br>• *Stack :* Django 5.2, MySQL en production, HTMX, Bootstrap 5, pytest-django.<br>• *Cartographie :* **Folium / Leaflet** pour la visualisation des votes par localisation.<br>• *i18n :* bilingue FR/EN via **django-modeltranslation**, admin multilingue, détection des préférences utilisateur.<br>• *Métier :* questions programmées à l'avance, choix et couleurs configurables, **système de badges** attribués automatiquement selon les conditions de vote, statistiques de participation. |
| **<a href="https://artisancouvreur60.fr/" target="_blank">JW Weiss Couverture</a>**<br><sub><a href="https://www.pygab.dev/projets/jw-weiss-couverture/" target="_blank">Étude de cas</a></sub> | **Site vitrine d'artisan couvreur** avec back-office de gestion des prestations.<br>• *Stack :* Django 6.0, SQLite, Bootstrap 5.3 compilé via Sass, django-environ, tests unittest.<br>• *Médias :* **django-imagekit + Pillow** — conversion WebP automatique et variantes multiples (card 4:3, medium, comparaison), django-cleanup pour purger les fichiers orphelins.<br>• *UX :* sliders avant/après avec le Web Component `img-comparison-slider`, menus dynamiques injectant les services dans tous les templates.<br>• *SEO & sécurité :* sitemaps XML, slugs dynamiques, méta-descriptions, formulaire de devis protégé par honeypot. |
| **<a href="https://onsenbray.fr/" target="_blank">Mairie d'Ons-en-Bray</a>**<br><sub><a href="https://www.pygab.dev/projets/site-de-la-commune-de-ons-en-bray/" target="_blank">Étude de cas</a> · <a href="https://github.com/gabigab117/onsenbray" target="_blank">Code</a></sub> | **Site officiel d'une commune**, développé sur mesure.<br>• *Stack :* Django + **Wagtail**, MySQL en production, Tailwind CSS et DaisyUI.<br>• *Administration :* interface Wagtail unifiée intégrant l'ensemble des modèles Django, avec **permissions granulaires** — accès complet pour les administrateurs, droits restreints à leur domaine pour les conseillers municipaux. |
| **<a href="https://pygab.dev/" target="_blank">PyGab.dev</a>**<br><sub><a href="https://www.pygab.dev/projets/pygabdev-un-projet-django-wagtail/" target="_blank">Étude de cas</a> · <a href="https://github.com/gabigab117/pygabdev3" target="_blank">Code</a></sub> | **Mon portfolio, mon blog et mon outil de gestion d'activité.**<br>• *Stack :* **Wagtail 7.0** + Django 5.2, MySQL, TailwindCSS, HTMX, pytest / pytest-django, VPS avec déploiement maison.<br>• *Librairies :* crispy-forms + crispy-tailwind, django-recaptcha, wagtailcodeblock, django-cleanup, django-cookie-consent.<br>• *Back-office :* **facturation**, gestion des clients / projets / services, suivi des paiements, interface Wagtail personnalisée, système de tags, design responsive mobile-first. |
| **Portail connecté**<br><sub><a href="https://www.pygab.dev/projets/portail-connect%C3%A9/" target="_blank">Étude de cas</a></sub> | **Ouverture d'un portail motorisé à distance depuis un téléphone**, pour un habitant du village.<br>• *Matériel :* relais Wi-Fi **Shelly 1 Gen3** ajouté à une motorisation Extel Bora existante (carte ATB 3), alimenté en 12 V depuis le bornier.<br>• *Intégration :* sortie relais câblée en parallèle de l'entrée de commande, en mode impulsion (~1 s) pour reproduire l'appui d'un bouton poussoir, pilotage via l'application Shelly.<br>• *Résultat :* plus de limite de portée, motorisation intacte et télécommande d'origine toujours fonctionnelle. |

👉 <a href="https://pygab.dev/projets/" target="_blank">Voir tous les projets sur mon portfolio</a>

---

### 👨‍🏫 Communauté & Transmission

Je ne fais pas que coder, je partage aussi ma passion :

*   🎓 **Mentor sur <a href="https://www.docstring.fr/" target="_blank">Docstring.fr</a>** : J'accompagne les développeurs dans leur montée en compétences Python.
*   🎤 **Speaker** : Intervenant au **Django Meetup Paris** et co-animateur de workshop à la **PyCon FR**.
*   🐍 **Membre de la Django Software Foundation** (DSF).
*   🏆 **Certifié TOSA Python** (Score : 955/1000).
*   ✍️ **Auteur** : Je rédige régulièrement des articles techniques sur <a href="https://pygab.dev/blog/" target="_blank">mon blog</a> et sur <a href="https://www.docstring.fr/blog/?sort_by=-publish_date" target="_blank">Docstring</a>.

---

### 📊 Statistiques GitHub

<div align="center">
  <img src="https://raw.githubusercontent.com/gabigab117/gabigab117/main/profile-summary-card-output/github/0-profile-details.svg" alt="Profile Details">
  <img src="https://raw.githubusercontent.com/gabigab117/gabigab117/main/profile-summary-card-output/github/1-repos-per-language.svg" alt="Repos per Language">
  <img src="https://raw.githubusercontent.com/gabigab117/gabigab117/main/profile-summary-card-output/github/2-most-commit-language.svg" alt="Most Commit Language">
  <img src="https://raw.githubusercontent.com/gabigab117/gabigab117/main/profile-summary-card-output/github/3-stats.svg" alt="Stats">
  <img src="https://raw.githubusercontent.com/gabigab117/gabigab117/main/profile-summary-card-output/github/4-productive-time.svg" alt="Productive Time">
</div>

---

### 📫 Me contacter

Je suis ouvert aux opportunités de freelance ou de collaboration sur des projets Django ambitieux.

<a href="https://pygab.dev/" target="_blank"><img src="https://img.shields.io/badge/Site_Web-PyGab.dev-3776AB?style=for-the-badge&logo=firefox"/></a>
<a href="https://www.linkedin.com/in/gabriel-trouv%C3%A9-b6a2bb159/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Gabriel_Trouvé-0077B5?style=for-the-badge&logo=linkedin"/></a>
<a href="https://x.com/GabrielTrouve" target="_blank"><img src="https://img.shields.io/badge/X_(Twitter)-@GabrielTrouve-000000?style=for-the-badge&logo=x"/></a>
<a href="https://www.youtube.com/@gabrieltrouve2801" target="_blank"><img src="https://img.shields.io/badge/YouTube-Gabriel_Trouvé-FF0000?style=for-the-badge&logo=youtube"/></a>