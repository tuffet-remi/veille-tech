# Ma veille technologique

Sources suivies : Blog du Modérateur, Developpez.com, CERT-FR, The Hacker News, JavaScript Weekly.

---

## 2026-11-28 – Six failles de sécurité corrigées dans Git
**Source :** [GitHub Blog](https://github.blog/open-source/git/git-security-vulnerabilities-announced-7)
**Recoupé avec :** [The Hacker News](https://thehackernews.com/2026/11/git-patches-flaw-that-lets-malicious.html)
**Thème :** Sécurité / Outils de développement
**Sujet :** six failles corrigées dans Git dont une permettant d'exécuter du code malveillant au clonage d'un dépôt piégé.
**Ce que j'en retiens :** même les outils de base du développeur doivent être mis à jour régulièrement, et il faut se méfier des dépôts dont on ne connaît pas l'origine.
**Action réalisée :** j'avais Git 2.56.0 vulnérable. J'ai mis à jour vers la version corrigée.
**Lien avec mes projets :** j'utilise Git et GitHub Actions sur tous mes projets.

---

## 2026-11-27 – L'accessibilité dans les projets open source
**Source :** [GitHub Blog](https://github.blog/open-source/maintainers/the-best-things-in-open-source-are-built-together)
**Thème :** Accessibilité / Open source
**Sujet :** GitHub présente un cadre pour rendre les projets open source accessibles construit avec des personnes concernées par le handicap autour d'un fichier ACCESSIBILITY.md.
**Ce que j'en retiens :** l'accessibilité doit être pensée et documentée dès le début d'un projet en précisant aussi ses limites et la manière de signaler un problème.
**Action réalisée :** j'ai ajouté un fichier ACCESSIBILITY.md à mon projet météo qui documente mes choix d'accessibilité (contraste, grandes polices, textes alternatifs, messages d'erreur clairs), leurs limites connues et la manière de signaler un problème. J'ai aussi vérifié le contraste de mes couleurs avec le Contrast Checker de WebAIM. <<<<Lien vers le fichier accessibility>>>>
**Lien avec mes projets :** mon écran météo utilise des textes alternatifs, un fort contraste et de grandes polices. Je pourrais ajouter un fichier ACCESSIBILITY.md pour documenter ces choix.

---

## 2026-11-26 - Attaque sur npm
**Source :** [TanStack](https://tanstack.com/blog/npm-supply-chain-compromise-postmortem)
**Thème :** Sécurité
**Sujet :** Compromission de paquets npm de TanStack via GitHub Actions (post-mortem, mai 2026)
**Ce que j'en retiens :** Se méfier des workflows qui exécutent du code venu de l'extérieur et surveiller soi-même ce qui est publié, au lieu de l'apprendre par d'autres.
**Lien avec mes projets :** j'utilise GitHub Actions et une bibliothèque chargée depuis un CDN, deux points à sécuriser.

---

## 2026-11-18 - La faille Java4Shell
**Source :** [The Hacker News](https://thehackernews.com/2026/11/cisa-urges-immediate-patching-of.html)
**Recoupé avec :** Bleeping Computer
**Thème :** Sécurité
**Sujet :** une faille dans le décodeur Base64 de Java qui touchait Jira, Confluence et Jenkins.
**Ce que j'en retiens :** l'importance de connaître ses dépendances, de les mettre à jour et la recommandation de valider les données reçues.
**Lien avec mes projets :** J'utilise Jira dans mon projet de tests logiciel.

---

## AAAA-MM-JJ - Titre du sujet
**Source :** [Nom de la source](lien)
**Thème :** JavaScript / Sécurité / Tests / Tendances
**Sujet :** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
**Ce que j'en retiens :** Mauris tempor euismod ipsum ut tincidunt.
**Lien avec mes projets :** In auctor, massa vel vestibulum facilisis, turpis urna lobortis ante, at ultricies turpis ex vitae tellus.
