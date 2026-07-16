<!-- ──────────── HEADER ──────────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=Boukar%C3%A9%20GANAME&fontSize=55&fontColor=ffffff&fontAlignY=38&desc=D%C3%A9veloppeur%20Full-Stack%20%E2%80%A2%20Bobo-Dioulasso%2C%20Burkina%20Faso&descAlignY=60&descSize=18&animation=fadeIn" alt="Header" width="100%" />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=800&color=58A6FF&center=true&vCenter=true&width=680&lines=D%C3%A9veloppeur+Full-Stack;FastAPI+%C2%B7+Django+%C2%B7+Rails+%C2%B7+Next.js+%C2%B7+Flutter;Du+cahier+des+charges+%C3%A0+la+production;SaaS+multi-tenant+%C2%B7+offline-first+%C2%B7+bilingue+fr%2Fen" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://mon-portfolio-sigma-umber.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/boukar%C3%A9-ganame-1302b3394">
    <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:boukarganame@yahoo.com">
    <img src="https://img.shields.io/badge/Email-6001D2?style=for-the-badge&logo=yahoo&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/boukareganame">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<!-- ──────────── À PROPOS ──────────── -->
## À propos

Développeur Full-Stack basé à **Bobo-Dioulasso (Burkina Faso)**, titulaire d'une **licence en informatique** et en préparation du **master**. Je construis des applications complètes — du cahier des charges à la mise en production — pour des organisations bien réelles : un sommet continental de la data, un centre médical, un diplôme inter-universitaire international.

Trois choses me définissent :

- **Je livre.** La plateforme officielle d'un sommet continental de la data en production, un ERP comptable qui fait tourner la gestion d'un centre médical, la refonte du site d'un DIU porté par deux universités.
- **Je conçois avant de coder.** Chaque projet démarre par une spécification et des décisions consignées — puis c'est la CI, pas ma bonne volonté, qui fait respecter les règles.
- **Je code pour mon contexte.** Éducation, santé, finance de terrain : flux de paiement mobile money (Orange Money, LigdiCash — en sandbox), applications offline-first pensées pour une connectivité intermittente, bilinguisme fr/en systématique.

<!-- ──────────── EN BREF ──────────── -->
## En bref

- 🚀 **1 plateforme en production** — le site officiel du Grand Salon de la Data en Afrique 2026 ([gsdasummit.org](https://www.gsdasummit.org))
- 🏥 **1 ERP en usage réel** — comptabilité et trésorerie d'un centre médical, alimenté par ses données 2026
- 🧪 **Plus de 700 tests automatisés** cumulés — pytest, RSpec, Vitest, Testcontainers, Playwright
- 🧰 **7 langages** — Python, TypeScript, Kotlin, Ruby, Dart, Java, SQL — et une dizaine de frameworks majeurs, de FastAPI à Jetpack Compose
- 🤝 **Travail en équipe éprouvé** — workflow PR avec branches protégées, revues de code, plus de 60 pull requests fusionnées sur un seul projet

<!-- ──────────── PROJETS CLIENTS ──────────── -->
## En production, chez de vrais clients

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>GSDA 2026 — plateforme événementielle</h3>
      <p><b>En production</b> : plateforme officielle du <b>Grand Salon de la Data en Afrique</b> (Ouagadougou). Monorepo de <b>5 applications</b> : site public bilingue, console admin (24 pages), portails exposant et bénévole, API Express/PostgreSQL.</p>
      <ul>
        <li>Accréditations multi-niveaux, badges PDF à QR code, check-in par scan</li>
        <li>Pipeline d'e-mails asynchrone : BullMQ + Redis, worker séparé, reprises automatiques</li>
        <li>28 migrations SQL brutes, et une CI qui échoue en cas de dérive du schéma</li>
        <li>Développée en équipe (4 à 5 développeurs) : plus de 60 pull requests fusionnées, ~31 000 lignes de TypeScript, déploiement Docker sur VPS</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
      </p>
      <p><a href="https://www.gsdasummit.org">→ Voir le site en ligne</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>COMPTA Ibn Nafis — ERP de gestion</h3>
      <p><b>En usage chez le client</b> : remplace <b>plus de 100 fichiers Excel</b> d'un centre médical (trésorerie, salaires, prêts, créances, factures fournisseurs) par une application web FastAPI + Next.js, alimentée par ses données 2026.</p>
      <ul>
        <li>17 modèles métier : périodes clôturables, brouillard de caisse, registre banque, salaires, prêts</li>
        <li>Importeurs Excel conçus par rétro-ingénierie des fichiers du client ; exports openpyxl identiques à ses documents</li>
        <li>Synchronisation automatique de la trésorerie depuis les événements métier — zéro double saisie</li>
        <li>Lancement en un clic sur le poste Windows d'une utilisatrice non technique</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
      </p>
      <p><i>Code privé (données client) — démo sur demande</i></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>DIU Antibiologie — refonte CMS</h3>
      <p>Refonte complète du site du <b>DIU « Antibiologie et Antibiothérapie en Afrique Subsaharienne »</b> (Université Nazi Boni × Université de Montpellier) : de l'audit de l'ancien WordPress à un CMS <b>Django 5 + Wagtail</b> sur mesure.</p>
      <ul>
        <li>Back-office éditorial complet pour une équipe non technique</li>
        <li>Candidature en ligne : uploads validés, consentement RGPD, anti-spam</li>
        <li>Migration automatisée et idempotente du contenu de l'ancien site</li>
        <li>48 tests (pytest-django + factory-boy) ; accessibilité et SEO traités comme des exigences, pas des finitions</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
        <img src="https://img.shields.io/badge/Wagtail-43B1B0?style=for-the-badge&logo=wagtail&logoColor=white" alt="Wagtail" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      </p>
      <p><i>Refonte réalisée, mise en ligne en cours</i></p>
    </td>
    <td width="50%" valign="top">
      <h3>Gestion Hôpital — SIH (stage)</h3>
      <p>Système d'information hospitalier développé <b>seul, pendant un stage de 5 mois</b> dans un centre médical : patients, consultations, hospitalisations, laboratoire, caisse.</p>
      <ul>
        <li><b>39 modèles Django</b>, 168 routes, 84 commits sur la durée du stage</li>
        <li>Facturation polymorphe (GenericForeignKey) synchronisée par signaux</li>
        <li>RBAC maison : 7 rôles, 48 permissions granulaires</li>
        <li>Sessions de caisse, reçus numérotés, tickets QR code, exports PDF/Excel, tableau de bord analytique</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
      </p>
      <p><i>Code sur demande</i></p>
    </td>
  </tr>
</table>

<!-- ──────────── LABORATOIRES ──────────── -->
## Laboratoires d'architecture

Trois projets personnels d'envergure où j'applique les exigences d'un produit commercial.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>H-Academy — SaaS scolaire multi-tenant</h3>
      <p>Plateforme de gestion scolaire <b>multi-établissement, en marque blanche et bilingue</b>, construite de zéro sur un plan en 10 phases : web Next.js 15, API FastAPI, mobile Flutter <b>offline-first</b>.</p>
      <ul>
        <li><b>174 endpoints</b>, 48 modèles, 39 pages web, <b>283 tests</b> (pytest, Vitest, Flutter)</li>
        <li>Isolation stricte par <b>schéma PostgreSQL par tenant</b> — fuite cross-tenant identifiée, corrigée et documentée</li>
        <li>RBAC 100 % dynamique (187 routes protégées), PII chiffrées au repos, journal d'audit immuable par trigger PostgreSQL</li>
        <li>Conformité RGPD : export art. 15, anonymisation, rétention automatique</li>
        <li>Synchronisation mobile hors ligne rejouée à la reconnexion, garantie par l'idempotence des API</li>
        <li>Encaissement mobile money atomique, testé avec 5 paiements simultanés (<code>SELECT FOR UPDATE</code>) ; la CI échoue si une seule clé de traduction fr/en manque</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js 15" />
        <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>SteelFlow — ingénierie de plateforme</h3>
      <p>ERP industriel fictif mené <b>comme un vrai programme d'entreprise</b> : microservices événementiels Spring Boot, front Next.js, et un dépôt <b>GitOps</b> structuré.</p>
      <ul>
        <li>3 microservices + starter maison de 6 modules (outbox transactionnel → CDC Debezium → inbox idempotente, démontré par runbook)</li>
        <li>BFF OIDC <b>écrit à la main</b> (PKCE, session JWE, cookies <code>__Host-</code>) — un test E2E Playwright vérifie qu'aucun jeton n'atteint le navigateur</li>
        <li>ArchUnit casse le build à la moindre violation de l'architecture hexagonale ; tests d'intégration Testcontainers (PostgreSQL, Kafka, Keycloak — jamais H2)</li>
        <li>GitOps : Argo CD app-of-apps, politiques Kyverno en mode Enforce, signatures cosign, Keycloak 100 % as-code</li>
        <li>Gouvernance : <b>11 ADR</b>, Conventional Commits, Renovate, gitleaks</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
        <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
        <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak" />
        <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" />
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>Kora — gestionnaire de fichiers & lecteur multimédia Android</h3>
      <p>Application Android <b>native, sans publicité, sans télémétrie, 100 % hors-ligne</b> — pensée pour remplacer <i>Files by Google</i> et les lecteurs tiers par une seule app possédée. Spécifiée par cahier des charges (v1.0), puis livrée <b>lot par lot</b>.</p>
      <table>
        <tr>
          <td width="50%" valign="top">
            <ul>
              <li><b>14 modules Gradle</b> (6 <code>core</code> + 7 <code>feature</code>) avec <i>convention plugins</i> maison (<code>build-logic/</code>) — architecture façon <i>Now in Android</i></li>
              <li><b>6 lots livrés</b> : explorateur, images, audio, vidéo, documents, stockage</li>
              <li>Explorateur : opérations en file avec gestion de conflits, copie atomique, pause/reprise, corbeille par volume, renommage par lot avec aperçu, SHA-256, favoris épinglés</li>
              <li>Décisions consignées en <b>ADR</b> ; deux flavors — <code>full</code> (<code>MANAGE_EXTERNAL_STORAGE</code>) et <code>safc</code> (SAF, conforme store)</li>
            </ul>
          </td>
          <td width="50%" valign="top">
            <ul>
              <li>Audio/Vidéo <b>Media3</b> : lecture d'arrière-plan (<code>MediaSessionService</code>, focus audio, coupure casque), ExoPlayer plein écran avec gestes, reprise de position par fichier (Room), découpe/extraction M4A/MP4</li>
              <li>Documents : PDF paginé (mode nuit, reprise), lecteur code avec détection d'encodage, navigation dans archives ZIP/7z/RAR/TAR avec <b>protection zip-slip</b></li>
              <li>Stockage : cartographie des dossiers, gros fichiers, <b>doublons par empreinte SHA-256</b> (jamais par nom), nettoyage passant toujours par la corbeille</li>
            </ul>
          </td>
        </tr>
      </table>
      <p>
        <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
        <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
        <img src="https://img.shields.io/badge/Material_3-757575?style=for-the-badge&logo=materialdesign&logoColor=white" alt="Material 3" />
        <img src="https://img.shields.io/badge/Media3-0F9D58?style=for-the-badge&logo=android&logoColor=white" alt="Media3" />
        <img src="https://img.shields.io/badge/Hilt-2196F3?style=for-the-badge" alt="Hilt" />
        <img src="https://img.shields.io/badge/Room-FF6F00?style=for-the-badge" alt="Room" />
        <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" alt="Gradle" />
      </p>
    </td>
  </tr>
</table>

<!-- ──────────── AUTRES PROJETS ──────────── -->
## Autres projets

<details>
<summary><b>Six autres projets — RH, mobile, fintech, bots, Android natif</b> (cliquer pour déplier)</summary>

| Projet | Description | Stack |
|---|---|---|
| **Stagify** | Plateforme RH de gestion des stagiaires : pointage restreint par plages IP (CIDR multi-site), PDF versionnés de conventions, e-mails transactionnels HTML. 18 modèles, **112 tests**, CI complète, stack Docker de production. Développé à deux en workflow PR. | Next.js 16 · Prisma 7 · Better Auth |
| **MIA Teacher Companion** | Application Flutter **offline-first** pour les enseignants de la Maison de l'IA (Bobo-Dioulasso) : séances minutées avec chronomètre, contenu 100 % éditable in-app (rôles Firebase), export du curriculum en un fichier. Testée sur appareil physique. | Flutter · Riverpod · Firestore |
| **Tontine** | Numérisation de l'épargne rotative ouest-africaine : cycles de cotisation, tours de distribution avec contrôle d'éligibilité, adaptateurs de paiement mobile en sandbox. | Rails 8 · PostgreSQL |
| **Longrich Bot** | Assistant commercial WhatsApp multi-comptes propulsé par l'API Claude : réponses IA avec historique, **scoring de prospects en structured outputs**, tableau de bord d'onboarding sans code. Éprouvé avec de véritables échanges WhatsApp. | Node.js · whatsapp-web.js · Claude API |
| **HFiles** | Gestionnaire de fichiers Android natif : MVVM + Hilt + Room dès la première ligne, lecteur vidéo gestuel, audio en arrière-plan (Media3/MediaSession). | Java 17 · Android SDK |
| **H-Academy API (v1)** | Première itération Rails de H-Academy : API multi-tenant par sous-domaine, **environ 305 specs RSpec**, webhooks de paiement mobile signés, bulletins PDF (Prawn). | Rails 8 · RSpec · Pundit |

</details>

<!-- ──────────── MÉTHODE ──────────── -->
## Méthode d'ingénierie

> Ce qui ne se vérifie pas automatiquement finit par se dégrader. Alors je fais vérifier mes règles par la machine.

1. **Spécifier avant de coder.** Document fondateur, conventions numérotées (C1–C20), décisions d'architecture consignées en ADR — avec leurs *pourquoi* et les écarts assumés.
2. **Des règles non négociables, que la CI fait respecter.** Parité i18n fr/en bloquante, zéro chaîne en dur, build cassé par ArchUnit à la moindre violation d'architecture, détection de dérive du schéma SQL, gitleaks.
3. **Tester ce qui casse en conditions réelles.** Concurrence (paiements simultanés sous `SELECT FOR UPDATE`, UPSERT idempotents), intégration contre de véritables services (Testcontainers : PostgreSQL, Kafka, Keycloak — jamais H2), bout en bout avec Playwright.
4. **L'IA comme instrument d'ingénierie.** Je pilote les assistants IA avec des spécifications séquencées, des conventions vérifiables et des tests d'acceptation par étape — et j'intègre aussi l'IA dans mes produits (scoring de prospects en structured outputs, assistants encadrés par limitation de débit et audit).

<!-- ──────────── STACK ──────────── -->
## Stack technique

<table align="center">
  <tr>
    <td align="center" colspan="7"><b>Backend</b></td>
  </tr>
  <tr>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="42" height="42" alt="Python" /><br/>Python</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="42" height="42" alt="FastAPI" /><br/>FastAPI</td>
    <td align="center" width="90"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/django/44B78B"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="42" height="42" alt="Django" /></picture><br/>Django</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rails/rails-plain.svg" width="42" height="42" alt="Rails" /><br/>Rails</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="42" height="42" alt="Node.js" /><br/>Node.js</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="42" height="42" alt="Spring Boot" /><br/>Spring Boot</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="42" height="42" alt="Java" /><br/>Java</td>
  </tr>
  <tr>
    <td align="center" colspan="7"><b>Frontend & Mobile</b></td>
  </tr>
  <tr>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="42" height="42" alt="TypeScript" /><br/>TypeScript</td>
    <td align="center" width="90"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/nextdotjs/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="42" height="42" alt="Next.js" /></picture><br/>Next.js</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="42" height="42" alt="React" /><br/>React</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="42" height="42" alt="Tailwind" /><br/>Tailwind</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" width="42" height="42" alt="Flutter" /><br/>Flutter</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" width="42" height="42" alt="Dart" /><br/>Dart</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-original.svg" width="42" height="42" alt="Firebase" /><br/>Firebase</td>
  </tr>
  <tr>
    <td align="center" colspan="7"><b>Android natif</b></td>
  </tr>
  <tr>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="42" height="42" alt="Kotlin" /><br/>Kotlin</td>
    <td align="center" width="90"><img src="https://cdn.simpleicons.org/jetpackcompose/4285F4" width="42" height="42" alt="Jetpack Compose" /><br/>Compose</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" width="42" height="42" alt="Android" /><br/>Android</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradle/gradle-original.svg" width="42" height="42" alt="Gradle" /><br/>Gradle</td>
  </tr>
  <tr>
    <td align="center" colspan="7"><b>Données, DevOps & Cloud</b></td>
  </tr>
  <tr>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="42" height="42" alt="PostgreSQL" /><br/>PostgreSQL</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="42" height="42" alt="Redis" /><br/>Redis</td>
    <td align="center" width="90"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/apachekafka/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="42" height="42" alt="Kafka" /></picture><br/>Kafka</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="42" height="42" alt="Docker" /><br/>Docker</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" width="42" height="42" alt="Kubernetes" /><br/>Kubernetes</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/argocd/argocd-original.svg" width="42" height="42" alt="Argo CD" /><br/>Argo CD</td>
    <td align="center" width="90"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" width="42" height="42" alt="GitHub Actions" /><br/>CI/CD</td>
  </tr>
</table>

<!-- ──────────── STATS ──────────── -->
## GitHub en chiffres

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=boukareganame&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400&include_all_commits=true" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=boukareganame&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400" alt="Top Languages" />
</p>

<!-- ──────────── DISPONIBLE POUR ──────────── -->
## Disponible pour

- **Alternance / stage de master** — développement full-stack, backend ou ingénierie de plateforme · télétravail complet (UTC+0, journée entièrement alignée sur l'Europe)
- **Missions freelance** — applications métier, migrations Excel → web, sites institutionnels
- **Collaborations open-source** ou projets à impact local — éducation, santé, finance communautaire

<p align="center">
  <i>Le meilleur moyen de me connaître reste mon code : explorez mes dépôts — et pour les projets clients privés, demandez-moi une démo.</i>
</p>

<!-- ──────────── FOOTER ──────────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" alt="Footer" width="100%" />
</p>
