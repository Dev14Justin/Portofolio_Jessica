Convention de Développement : Portfolio de Jessica
1. Contexte du Projet
🎯 Présentation du projet

Ce projet a pour objectif de créer un portfolio web minimaliste pour Jessica, communicante et voix-off. Le portfolio doit mettre en valeur son travail de manière professionnelle et élégante, tout en étant facile à naviguer.

L'objectif est de présenter clairement ses compétences, son expérience et de fournir des extraits de sa voix-off, le tout sur une seule page (format "one-page").

✅ Solution proposée

Un portfolio d'une seule page qui inclut :

En-tête : une section "Hero" avec une photo de Jessica, son nom, et une phrase d'accroche.

À propos : une brève biographie et une présentation de ses compétences.

Portfolio / Projets : une section pour présenter ses projets de communication.

Voix-off : une section avec des extraits audio.

Contact : un formulaire de contact minimaliste ou des liens vers ses réseaux sociaux professionnels.

2. Architecture et Stack Technique
🏗️ Stack technique

Frontend : HTML, Tailwind CSS, JavaScript.

Animations : JavaScript natif.

Déploiement : Vercel ou Netlify (gratuit et rapide pour un projet statique).

3. Architecture du Projet
Le projet sera organisé de manière épurée et logique, en utilisant le même principe de séparation claire que pour KpiHub.

jessica-portfolio/
│── public/               # Dossier public
│   ├── assets/           # Contenu statique
│   │   ├── audios/       # Extraits voix-off
│   │   ├── images/       # Photos de Jessica, icônes
│   │   └── fonts/        # Polices personnalisées
│   ├── src/              # Code source (CSS, JS)
│   │   ├── css/          # Fichier CSS final de Tailwind
│   │   │   └── style.css
│   │   └── js/           # Fichier JavaScript
│   │       └── main.js
│   └── index.html        # Point d'entrée principal
│
│── tailwind.config.js
│── package.json
4. Style et Conventions de Code
Nommage
kebab-case pour les dossiers et les fichiers (ex : a-propos.html, jessica-photo.jpg).

camelCase pour les variables et fonctions JavaScript.

HTML
Utiliser la sémantique HTML5 ( <header>, <main>, <section>, <footer>).

Chaque section du site (À propos, Projets, Contact) doit être contenue dans une balise <section> avec un id unique pour faciliter la navigation et les ancres. Par exemple : <section id="a-propos">.

Tailwind CSS
Le style sera entièrement géré par les classes utilitaires de Tailwind CSS.

Nous utiliserons le fichier tailwind.config.js pour configurer la palette de couleurs et la typographie, comme dans le projet KpiHub. Cela garantit une cohérence visuelle.

Le mode sombre sera une option à envisager pour un look plus moderne si le style de Jessica s'y prête.

JavaScript
Le JavaScript sera uniquement utilisé pour les animations minimalistes et les interactions de la page.

Exemples d'utilisation :

Animation des éléments à leur apparition lors du scroll (scroll-reveal).

Gestion du menu de navigation pour le mobile.

Lecture et pause des extraits audio de la section voix-off.

5. Fiche de Style
Je m'inspire de la fiche de style de KpiHub pour proposer une approche similaire, tout en la simplifiant pour un portfolio.

Typographie
Police principale : Une police moderne et élégante comme Poppins ou Montserrat.

Poids : font-normal pour le corps de texte, font-semibold ou font-bold pour les titres.

Palette de couleurs
Primaire : Une couleur distinctive, peut-être liée à la personnalité de Jessica (ex: un bleu ciel doux, un rose poudré).

Secondaire : Une couleur neutre pour les boutons secondaires ou les accents.

Fond : Un gris très clair ou un blanc cassé pour un look épuré et minimaliste.

