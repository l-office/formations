# Écoconception web (ou Green IT)

## Introduction

L’éco-conception est une approche qui vise à intégrer les préoccupations environnementales dès la phase de conception d’un produit ou d’un service, afin de réduire son impact sur l’environnement tout au long de son cycle de vie. Contrairement à des démarches correctives appliquées après la production, l’éco-conception s’inscrit en amont, dans une logique proactive, et considère tous les aspects liés à l’empreinte écologique : extraction des ressources, fabrication, utilisation et fin de vie.

Dans le domaine du numérique, l’éco-conception (ou Green IT) cherche à répondre à des enjeux croissants liés à la consommation énergétique et aux ressources utilisées par les solutions technologiques. Avec l’essor des services digitaux, des centres de données et des équipements connectés, le secteur IT est aujourd’hui responsable d’environ 4 % des émissions mondiales de gaz à effet de serre, et ce chiffre est en constante augmentation.

Adopter une démarche d’éco-conception dans le numérique permet non seulement de limiter cet impact, mais aussi de concevoir des solutions plus performantes, durables et économiquement viables, tout en répondant aux attentes des utilisateurs et des entreprises en matière de responsabilité sociétale.

---

## Les 115 bonnes pratiques

Ces informations sont issues du livre ["Écoconception web / les 115 bonnes pratiques" des éditions Eyrolles](https://www.eyrolles.com/Informatique/Livre/ecoconception-web-les-115-bonnes-pratiques-9782416006272/), de Frédéric Bordage.

### Spécification

* [Éliminer les fonctionnalités non essentielles](chapitres/BP_001_fr.md)
* [Quantifier précisément le besoin](chapitres/BP_002_fr.md)
* [Éliminer les fonctionnalités non utilisées](chapitres/BP_4018_fr.md)
* [Privilégier une approche "mobile first", à défaut un chargement adaptatif](chapitres/BP_006_fr.md)

### Conception

#### _FRONT_

* [Optimiser le parcours utilisateur](chapitres/BP_003_fr.md)
* [S'assurer que les parcours utilisateurs permettent de réaliser leur action prévue](chapitres/BP_4014_fr.md)
* [Proposer un traitement asynchrone lorsque c'est possible](chapitres/BP_008_fr.md)
* [Respecter le principe de navigation rapide dans l’historique](chapitres/BP_007_fr.md)
* [Éviter les animations JavaScript / CSS](chapitres/BP_039_fr.md)
* [Limiter le recours aux carrousels](chapitres/BP_4030_fr.md)
* [Avoir un titre de page et une metadescription pertinents avec le contenu de la page](chapitres/BP_4015_fr.md)
* [Favoriser un design simple, épuré, adapté au web](chapitres/BP_005_fr.md)
* [Préférer la pagination au défilement infini](chapitres/BP_4035_fr.md)
* [Préférer la saisie assistée à l'autocomplétion](chapitres/BP_004_fr.md)
* [N'utilisez que les portions indispensables des librairies JavaScript et frameworks CSS](chapitres/BP_040_fr.md)
* [Mettre en cache les données calculées souvent utilisées](chapitres/BP_064_fr.md)
* [Éviter le transfert d'une grande quantité de données pour réaliser un traitement](chapitres/BP_076_fr.md)
* [Favoriser les pages statiques](chapitres/BP_013_fr.md)
* [Préférer une PWA à une application mobile native similaire au site web](chapitres/BP_4019_fr.md)

#### _BACK_

* [Afficher des pages d'erreur statiques](chapitres/BP_096_fr.md)
* [Limiter le nombre d'appels aux API HTTP](chapitres/BP_4022_fr.md)
* [Favoriser un développement sur-mesure à l'usage d'un CMS](chapitres/BP_011_fr.md)
* [Réduire le volume de données stockées au strict nécessaire](chapitres/BP_4011_fr.md)
* [Ne se connecter à une base de données que si nécessaire](chapitres/BP_073_fr.md)
* [Favoriser le "Request collapsing"](chapitres/BP_4033_fr.md)
* [Mettre en place un "Circuit breaker"](chapitres/BP_4032_fr.md)
* [Mettre en place une architecture élastique](chapitres/BP_4021_fr.md)
* [Créer une architecture applicative modulaire](chapitres/BP_014_fr.md)
* [Utiliser la version la plus récente du langage](chapitres/BP_4016_fr.md)

### Réalisation

#### _FRONT_

* [Fournir une alternative textuelle aux contenus multimédias](chapitres/BP_4005_fr.md)
* [Fournir une CSS print](chapitres/BP_027_fr.md)
* [Favoriser les polices standards](chapitres/BP_029_fr.md)
* [Ne pas afficher les documents à l'intérieur des pages](chapitres/BP_4039_fr.md)
* [Utiliser le rechargement partiel d'une zone de contenu](chapitres/BP_038_fr.md)
* [Limiter le nombre de CSS](chapitres/BP_022_fr.md)
* [Découper les CSS](chapitres/BP_021_fr.md)
* [Préférer les CSS aux images](chapitres/BP_023_fr.md)
* [Éviter d'utiliser des images matricielles pour l'interface](chapitres/BP_035_fr.md)
* [Utiliser les compartiments CSS](chapitres/BP_4004_fr.md)
* [Modifier plusieurs propriétés CSS en 1 seule fois](chapitres/BP_045_fr.md)
* [Grouper les déclarations CSS similaires](chapitres/BP_025_fr.md)
* [Écrire des sélecteurs CSS efficaces](chapitres/BP_024_fr.md)
* [Utiliser les notations CSS abrégées](chapitres/BP_026_fr.md)
* [Externaliser les CSS et JavaScript](chapitres/BP_032_fr.md)
* [Valider votre code avec un Linter](chapitres/BP_046_fr.md)
* [Ne pas faire de modification du DOM lorsqu’on le traverse](chapitres/BP_041_fr.md)
* [Rendre les éléments du DOM invisibles lors de leur modification](chapitres/BP_042_fr.md)
* [Ne charger des données/du code que lorsqu'elles sont/il est nécessaire](chapitres/BP_4017_fr.md)
* [Limiter le nombre de requêtes HTTP](chapitres/BP_009_fr.md)
* [Ne pas redimensionner les images coté navigateur](chapitres/BP_034_fr.md)
* [Optimiser les images](chapitres/BP_080_fr.md)
* [Préférer les glyphs aux images](chapitres/BP_030_fr.md)
* [Utiliser le chargement paresseux](chapitres/BP_037_fr.md)
* [Réduire au maximum le repaint (appearence) et le reflow (layout)](chapitres/BP_043_fr.md)
* [Éviter les temps de blocages par des traitements JavaScript trop longs](chapitres/BP_4020_fr.md)
* [Mettre en cache les objets souvent accédés en JavaScript](chapitres/BP_049_fr.md)
* [Limiter le recours aux canvas](chapitres/BP_4013_fr.md)
* [Utiliser la délégation d'évènements](chapitres/BP_044_fr.md)
* [Réduire les accès au DOM via JavaScript](chapitres/BP_054_fr.md)
* [Assurer la compatibilité avec les plus anciens appareils et logiciels du parc](chapitres/BP_4009_fr.md)
* [Remplacer les boutons officiels de partage des réseaux sociaux](chapitres/BP_019_fr.md)
* [Économiser de la bande passante grace à un Service Worker](chapitres/BP_4007_fr.md)
* [Valider les pages auprès du W3C](chapitres/BP_031_fr.md)

#### _BACK_

* [Optimiser la taille des cookies](chapitres/BP_082_fr.md)
* [Choisir un format de données adapté](chapitres/BP_017_fr.md)
* [Stocker les données statiques localement](chapitres/BP_010_fr.md)
* [Éviter d'effectuer des requêtes SQL à l’intérieur d’une boucle](chapitres/BP_072_fr.md)
* [Optimiser les requêtes aux bases de données](chapitres/BP_075_fr.md)
* [Choisir les technologies les plus adaptées](chapitres/BP_015_fr.md)
* [Utiliser certains forks applicatifs orientés "performance"](chapitres/BP_016_fr.md)
* [Limiter le nombre d'extensions dans un CMS](chapitres/BP_4037_fr.md)
* [Sécuriser l'accès à l'administration](chapitres/BP_4038_fr.md)

### Production

#### _OPTIMISATIONS_

* [Utiliser un CDN](chapitres/BP_098_fr.md)
* [Utiliser tous les niveaux de cache du CMS](chapitres/BP_057_fr.md)
* [Mettre en cache les réponses Ajax](chapitres/BP_102_fr.md)
* [Mettre les caches entièrement en RAM (opcode et kvs)](chapitres/BP_092_fr.md)
* [Utiliser un cache HTTP](chapitres/BP_099_fr.md)
* [Ajouter des entêtes Expires ou Cache-Control](chapitres/BP_101_fr.md)
* [Compresser les fichiers CSS, JavaScript, HTML et SVG](chapitres/BP_078_fr.md)
* [Minifier les fichiers CSS, JavaScript, HTML et SVG](chapitres/BP_077_fr.md)
* [Combiner les fichiers CSS et JavaScript](chapitres/BP_079_fr.md)
* [Mettre en place une politique d'expiration et suppression des données](chapitres/BP_4012_fr.md)
* [Stocker les données dans le cloud](chapitres/BP_093_fr.md)
* [Héberger les ressources (CSS/JS) sur un domaine sans cookie](chapitres/BP_094_fr.md)
* [Limiter le nombre de domaine servant les ressources](chapitres/BP_018_fr.md)
* [Privilégier HTTP/2 à HTTP/1](chapitres/BP_4006_fr.md)
* [Favoriser HSTS Preload list aux redirections 301](chapitres/BP_084_fr.md)
* [Désactiver le DNS lookup d’Apache](chapitres/BP_104_fr.md)
* [Utiliser un serveur asynchrone](chapitres/BP_097_fr.md)
* [Réduire au nécessaire les logs des serveurs](chapitres/BP_103_fr.md)
* [Apache Vhost : désactiver le AllowOverride](chapitres/BP_105_fr.md)
* [Supprimer tous les warning et toutes les notices](chapitres/BP_070_fr.md)
* [Mettre en place un sitemap efficient](chapitres/BP_4008_fr.md)
* [Adapter la qualité de service et le niveau de disponibilité](chapitres/BP_088_fr.md)

#### _HÉBERGEMENT_

* [Utiliser des serveurs virtualisés](chapitres/BP_089_fr.md)
* [Optimiser l'efficacité énergétique des serveurs](chapitres/BP_090_fr.md)
* [Installer le minimum requis sur le serveur](chapitres/BP_091_fr.md)
* [Privilégier un fournisseur d'électricité écoresponsable](chapitres/BP_087_fr.md)
* [Choisir un hébergeur "éco-responsable"](chapitres/BP_086_fr.md)
* [S’appuyer sur les services managés](chapitres/BP_4034_fr.md)

### Utilisation

#### _IMAGES_

* [Optimiser et générer les médias avant importation sur un CMS](chapitres/BP_058_fr.md)
* [Limiter l'utilisation des GIFs animés](chapitres/BP_4002_fr.md)
* [Optimiser les images vectorielles](chapitres/BP_036_fr.md)

#### _E-MAIL_

* [N'utiliser que des fichiers double opt-in](chapitres/BP_110_fr.md)
* [Limiter la taille des e-mails envoyés](chapitres/BP_111_fr.md)
* [Limiter les e-mails lourds et redondants](chapitres/BP_109_fr.md)

#### _MULTIMEDIA_

* [Encoder les sons en dehors du CMS](chapitres/BP_060_fr.md)
* [Adapter les sons aux contextes d'écoute](chapitres/BP_112_fr.md)
* [Éviter la lecture et le chargement automatique des vidéos et des sons](chapitres/BP_4003_fr.md)
* [Adapter les vidéos aux contextes de visualisation](chapitres/BP_114_fr.md)

#### _DOCUMENTS ET PDF_

* [Compresser les documents](chapitres/BP_107_fr.md)
* [Optimiser les PDF](chapitres/BP_108_fr.md)

#### _AUTRES_

* [Adapter les textes au web](chapitres/BP_113_fr.md)
* [Limiter les outils d'analytics et les données collectées](chapitres/BP_4001_fr.md)

### Maintenance et fin de vie

#### _SUPPORT_

* [Éviter les redirections](chapitres/BP_095_fr.md)
* [Désactiver les logs binaires](chapitres/BP_106_fr.md)
* [Entretenir son site régulièrement](chapitres/BP_4036_fr.md)

#### _FIN DE VIE_

* [Avoir une stratégie de fin de vie des contenus](chapitres/BP_4031_fr.md)
* [Mettre en place un plan de fin de vie du site](chapitres/BP_085_fr.md)

---


## Tester son application web

Tester si votre application web est bien éco-conçue implique d'évaluer son impact environnemental à travers plusieurs indicateurs liés à la consommation d'énergie, de ressources, et aux performances. Voici les étapes et outils à utiliser pour effectuer une analyse.

---

### Mesurer la performance globale
- **Google Lighthouse** ([lighthouse](https://developer.chrome.com/docs/lighthouse/overview?hl=fr)): Fournit un score de performance, d'accessibilité, et d’optimisation.
    - Ajoutez l'extension Chrome ou utilisez-le dans les DevTools de votre navigateur.
    - Regardez particulièrement la section "Performance" et "Best Practices".
- **WebPageTest** ([webpagetest.org](https://www.webpagetest.org)) : Mesure le temps de chargement, le poids des ressources, et l’efficacité du cache.

### Évaluer l'empreinte carbone

- **Website Carbon Calculator** ([websitecarbon.com](https://www.websitecarbon.com)) : Estime l'empreinte carbone d'une page web en fonction de son poids et de la source d’énergie des serveurs.
- **GreenFrame.io** ([greenframe.io](https://greenframe.io)): Un outil avancé pour mesurer l’impact énergétique d’une application complète.

### Analyser l'impact réseau

- **EcoIndex** ([ecoindex.fr](https://www.ecoindex.fr/)) : Analyse l'impact environnemental d'une page en fonction de sa structure (HTML, JS, CSS) et de son poids.
- **Pingdom** ([tools.pingdom.com](https://tools.pingdom.com/)) : Analyse les performances réseau et l'efficacité des requêtes.

### Vérifier l’utilisation des ressources

### Outils
- **PageSpeed Insights** ([pagespeed.web.dev](https://pagespeed.web.dev)) : Recommande des améliorations pour réduire la consommation de ressources.
- **ImageOptim** ([imageoptim.com](https://imageoptim.com)): Vérifie et optimise le poids des images utilisées.


### Mesurer la consommation d’énergie côté client

### Outils
- **Carbonalyser** ([carbonalyser](https://addons.mozilla.org/fr/firefox/addon/carbonalyser/)) : Mesure la consommation d'énergie et les émissions de CO₂ générées par l’utilisation d’un site (Extension Firefox).
- **PowerAPI** ([powerapi.org](https://powerapi.org)): Suit la consommation d’énergie des processus locaux (utile pour tester un PWA ou une application web locale).

---

### Automatiser les tests éco-responsables

- **GreenIT Analysis** ([greenit-analysis](https://ecoresponsable.numerique.gouv.fr/publications/boite-outils/fiches/greenitanalysis/)) : Plateforme dédiée à l’analyse énergétique des sites web et applications.
- **Lighthouse CI** ([lighthouse-ci](https://googlechrome.github.io/lighthouse-ci/)): Automatisation des audits Lighthouse pour surveiller les performances dans le temps.

---

### Vérifier la conformité avec les critères d'éco-conception

- **Accessibilité** : Une application inclusive améliore l'expérience utilisateur et réduit les actions inutiles.
- **Dark Mode** : Peut réduire la consommation sur les écrans OLED.
- **Effet rebond** : Éviter les fonctionnalités inutiles ou redondantes qui sur-sollicitent le système.

---

En intégrant ces outils et analyses dans votre développement, vous pourrez identifier les points à améliorer pour réduire l'impact environnemental de votre application web et aligner votre démarche avec les principes du **Green IT**. 🌿

