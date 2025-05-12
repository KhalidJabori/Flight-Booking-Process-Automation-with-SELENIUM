# Flight-Booking-Process-Automation-with-SELENIUM
--------------------------------------------------

Projet : Automatisation du Processus de Réservation de Vols avec Selenium
Ce projet vise à automatiser entièrement la recherche et la réservation de billets d'avion sur des plateformes en ligne (comme Expedia, Kayak, ou les sites des compagnies aériennes) en utilisant Selenium pour simuler les interactions d'un utilisateur réel. L'objectif est de réduire le temps passé à comparer manuellement les vols, tout en garantissant la récupération des meilleures offres (prix, escales, horaires) selon des critères personnalisables (dates, budget, préférences de classe).

Fonctionnalités Clés :
1- Navigation Automatisée :

- Remplissage des formulaires (origine, destination, dates).

- Gestion des sélecteurs dynamiques (calendriers, menus déroulants).

- Clique sur les boutons "Voir les résultats" ou "Réserver".

2- Extraction des Données :

- Collecte des prix, horaires, compagnies aériennes, et durée des vols.

- Filtrage des résultats selon des règles prédéfinies (ex : "moins de 2 escales").

3- Réservation Automatique (optionnel) :

- Remplissage des informations passagers (nom, passeport).

- Paiement simulé (si autorisé par le site).

Avantages :
✅ Gain de temps : Comparaison de centaines de vols en quelques minutes.
✅ Flexibilité : Adaptable à plusieurs sites (grâce à la modularité du code).
✅ Alertes personnalisées : Notification lorsque les prix baissent.

Technologies Utilisées :
Langage : Python

Outils :

Selenium WebDriver (pour l'automatisation du navigateur).

BeautifulSoup (pour extraire des données si nécessaire).

Pandas (analyse et stockage des résultats en CSV/Excel).

Optimisations :

Délais aléatoires entre les actions pour éviter le bannissement.

Rotation des User-Agents et proxies (si besoin).
