# Fiche pratique — Cataloguer un jeu de données

*Mise à jour : 23 novembre 2026*

> **Atlas Bercy est un prototype.** Il est accessible à l'adresse [https://proto-catalogue-donnees.lab.miweb.run](https://proto-catalogue-donnees.lab.miweb.run). Les données qu'il contient sont fictives : l'application l'indique par le badge « Prototype — données fictives ». Pour vous connecter, vous recevez un lien par courriel (voir « Se connecter »). **Seules les adresses électroniques en @…gouv.fr peuvent recevoir ce lien.**

## À quoi sert Atlas Bercy ?

Atlas Bercy est le catalogue des données des ministères économiques et financiers (MEF). Il permet de décrire, de retrouver, de qualifier et de demander les jeux de données produits par les bureaux et directions.

Il répond à trois enjeux :

- **Découvrabilité** : un consommateur doit pouvoir trouver vos données en cherchant par mot-clé, thématique ou bureau producteur.
- **Conformité** : inventaire du patrimoine documentaire (RIP, art. L322-6 CRPA), registre des traitements (RGPD, art. 30).
- **Confiance** : chaque fiche indique qui produit, qui contacter, quelle est la sensibilité et la fraîcheur des données.

**Décrire une donnée n'est pas l'ouvrir.** Une fiche dit qu'une donnée existe et à qui la demander. Une donnée fermée reste fermée. Le catalogue ne publie pas les données.

## Se connecter

1. Ouvrez Atlas Bercy et cliquez sur **Se connecter**.
2. Saisissez votre adresse électronique professionnelle, puis cliquez sur **Recevoir un lien de connexion**. Seules les adresses en @…gouv.fr (par exemple @finances.gouv.fr) reçoivent un lien.
3. Ouvrez le courriel reçu et cliquez sur le lien. Il est valable 30 minutes (durée par défaut) et ne sert qu'une fois.
4. Vous restez connecté 8 heures (durée par défaut). Ensuite, demandez un nouveau lien.

Sans connexion, le menu ne propose que la recherche et l'aide.

Ce que vous pouvez faire dépend de vos droits : consulter, saisir, valider. Ouvrez le menu de votre nom, puis **Mes droits**, pour les voir. Si un droit vous manque, ouvrez **Demander des droits**. Vous pouvez la déposer pour vous ou pour un collaborateur. La mission AMDAC instruit la demande.

## Rechercher une donnée

Ouvrez **Rechercher une donnée**. La recherche porte sur le titre, la description et les mots-clés des fiches que vous avez le droit de lire.

- **Filtres** : direction productrice, thème principal, accès à la donnée (statut de publication), année de mise à jour de la donnée. Seules les valeurs présentes dans les fiches que vous pouvez lire sont proposées. Cliquez sur **Appliquer les filtres**, ou sur **Réinitialiser**.
- **Affichage** : les boutons **Cartes** et **Tableau** changent la vue. Dans le tableau, un clic sur le titre d'une colonne trie les résultats.
- **Export** : le bouton d'export télécharge les résultats au format CSV.
- **Proche par le sens** : ce badge signale une fiche trouvée par proximité de sens, et non par ses mots exacts. La recherche par le sens complète automatiquement la recherche par mots-clés. Si elle ne répond pas, Atlas Bercy l'indique et n'utilise que les mots-clés.

Vous ne trouvez pas votre donnée ? Utilisez **Faire une demande** (voir « Demander une donnée »).

## Saisir une fiche

Il faut un droit de saisie. Cliquez sur **Saisir une fiche** dans le menu. Quatre champs suffisent pour enregistrer une première version. Vous complétez le reste maintenant ou plus tard.

### L'essentiel

| Libellé | Obligatoire | Conseil |
|---------|:-----------:|---------|
| **Titre du jeu de données** | Oui | 5 à 10 mots, 200 caractères au plus. |
| **Bureau producteur** | Oui | Seuls les bureaux de votre périmètre d'écriture sont proposés. |
| **Description** | Oui | Environ un paragraphe : ce que contient la donnée, sa maille, ce qu'elle permet de faire. |
| **Mots-clés** | Oui | Au moins un, séparés par des virgules. |
| **URL du jeu de données** | Non | Page qui présente la donnée (intranet, portail métier). |

**Qu'est-ce qu'un bon titre ?**

*   **Longueur** : 5 à 10 mots, maximum 200 caractères.
*   **Règle** : il doit être explicite pour une personne extérieure à votre bureau. Évitez les acronymes internes non explicités.
*   *Exemple à éviter* : `Base PLF final v2`
*   *Exemple recommandé* : `Dépenses du Projet de Loi de Finances (PLF) par programme budgétaire`

**Qu'est-ce qu'une bonne description ?**

*   **Longueur** : 300 à 500 caractères (environ un paragraphe).
*   **Contenu** : expliquez l'objectif du jeu de données, la population concernée, l'origine de la collecte et les éventuelles limites d'utilisation. Explicitez les termes techniques complexes.
*   **Lecteur visé** : écrivez pour un agent d'une autre direction.
*   *Exemple recommandé* : `Ce jeu de données retrace l'ensemble des crédits de paiement et des autorisations d'engagement votés dans le cadre du Projet de Loi de Finances (PLF) pour l'année civile. Il détaille les montants par programme budgétaire et par ministère, permettant de suivre les orientations budgétaires de l'État.`

**Qu'est-ce qu'un bon ensemble de mots-clés ?**

*   **Quantité** : 3 à 7 mots-clés, séparés par des virgules. Vous pouvez en coller plusieurs d'un coup.
*   **Règle** : utilisez les mots que quelqu'un taperait pour trouver la donnée : termes génériques et synonymes usuels. Choisissez parmi les mots-clés existants ou ajoutez-en.
*   *Exemple recommandé* : `fiscalité, budget de l'Etat, plf, dépenses publiques, comptabilité publique`

**Votre bureau n'est pas dans la liste ?** Deux solutions :

*   Si vous ne connaissez pas le bureau, choisissez la direction ou le service, en tête de liste. La fiche est enregistrée et marquée « bureau à préciser ». Cela ne bloque pas, mais cela baisse un peu la complétude (voir plus bas).
*   Sinon, ouvrez « Ce bureau n'est pas dans la liste : le proposer ». Le bureau est ajouté et sélectionné tout de suite, marqué « à confirmer » jusqu'à sa vérification par la mission AMDAC.

### Compléter la fiche

Le bouton **Compléter la fiche** ouvre les champs facultatifs. Ils sont groupés par ce qu'ils apportent. Rien n'est perdu si vous enregistrez avant : vous pouvez revenir à tout moment.

**Pour qu'on la retrouve**

| Libellé | Remarque |
|---------|----------|
| Statut de publication | « Données ouvertes » se déduit de ce champ. |
| Motif de restriction | Si la donnée n'est pas ouverte : pourquoi, et à quelles conditions elle peut être obtenue. Affiché dans l'encart « Accès à la donnée ». |
| Niveau de sensibilité | Un seul niveau : le plus restrictif qui s'applique. |
| La donnée contient des données à caractère personnel | Case à cocher (RGPD). Indépendante du niveau de sensibilité. |
| Thème principal | Le classement sous lequel un collègue chercherait d'abord la donnée. |
| Thèmes secondaires | Ne répétez pas le thème principal. |
| Langue | |
| Couverture géographique | La maille territoriale : un seul niveau. |
| Période couverte : début | Date. |
| Période couverte : fin | Date. |

Aucun thème ne convient ? Utilisez « Aucun thème ne convient ? Suggérer un thème », sous « Thème principal ». La mission AMDAC traite votre suggestion.

**Qui la produit et la met à jour**

| Libellé | Remarque |
|---------|----------|
| Point de contact : entité | Sa boîte fonctionnelle (BALF) est reprise du référentiel. Sans choix, la BALF du bureau producteur est utilisée. |
| Contact principal | La personne qui sait répondre sur le contenu. Liste tenue par la mission AMDAC. |
| Commanditaire ou propriétaire | Si différent du producteur. |
| Fréquence de mise à jour | Sert à repérer les fiches à actualiser. |
| Système d'information | L'application d'où sort la donnée. Liste tenue par la mission AMDAC. |
| Date de publication | Date. |
| Date de dernière mise à jour de la donnée | Date. |

**Pour qu'on y accède**

| Libellé | Remarque |
|---------|----------|
| URL de téléchargement direct | Lien vers le fichier lui-même. Laissez vide si la donnée n'est pas diffusable. |
| Formats des données | Plusieurs choix possibles. |
| Licence juridique | Par défaut, la Licence Ouverte v2.0 (Etalab) pour les données ouvertes. |
| Volumétrie (Mo) | Taille approximative, en mégaoctets. |
| URL open data | Page du jeu sur [data.economie.gouv.fr](https://data.economie.gouv.fr), la plateforme open data ministérielle, ou sur data.gouv.fr, si la donnée y est déjà publiée. |

**Avant d'enregistrer**

| Libellé | Remarque |
|---------|----------|
| Commentaires | Ce qu'un lecteur doit savoir : limite d'interprétation, précaution d'usage. |
| Demander la validation de cette fiche | Case à cocher. Cochez quand la fiche est prête (voir « Faire valider et certifier »). |

Le statut de la fiche n'est pas saisi : il est calculé.

Si votre bureau, un contact ou un système d'information manque dans une liste, écrivez à la mission AMDAC, qui tient ces listes. Enregistrez la fiche sans ce champ et complétez-la ensuite.

### Trois adresses différentes

*   **URL du jeu de données** (dans « L'essentiel ») : la page qui présente la donnée.
*   **URL de téléchargement direct** : le fichier lui-même.
*   **URL open data** : la page du jeu sur data.economie.gouv.fr ou data.gouv.fr.

### Documents joints

Une fois la fiche créée, vous pouvez joindre des documents qui la **décrivent** : dictionnaire des variables, note méthodologique, convention d'accès, guide de lecture. Le bloc « Documents joints » se trouve dans le formulaire de modification de la fiche.

*   5 documents au maximum, 10 Mo par document (valeurs par défaut).
*   Formats acceptés : PDF, CSV, TSV, texte, Markdown, Word, Excel, OpenDocument et images courantes. Les archives, exécutables, HTML et SVG sont refusés.
*   **Ne déposez jamais de données réelles.** Retirez les valeurs d'exemple d'un dictionnaire de variables. Les documents ne sont pas analysés par un antivirus.
*   Si la fiche décrit des données sensibles ou personnelles, aucun document ne peut être joint.

### Enregistrer

Cliquez sur **Enregistrer la fiche**. Pour une fiche existante, ouvrez-la puis **Modifier cette fiche** et cliquez sur **Enregistrer les modifications**. La modification ne crée jamais de nouvelle fiche. **Annuler** quitte le formulaire sans enregistrer. Vos fiches se retrouvent dans **Mon espace**, sous **Mes fiches**.

## Utiliser l'assistant

L'assistant s'appuie sur [Albert](https://ia.numerique.gouv.fr/outils-ia/albert-api/), l'IA de l'État. Une fois connecté, le bouton **Assistant** est en bas à droite de chaque page. Il ouvre un panneau. Il ne s'ouvre jamais seul. Le bouton **Plein écran** l'ouvre en pleine page.

Il sait :

*   répondre à vos questions sur les fiches que vous avez le droit de voir, sur vos droits et sur le fonctionnement d'Atlas Bercy ;
*   vous aider à décrire un jeu de données, en commençant par les quatre champs obligatoires ;
*   pré-remplir une fiche à partir d'un échantillon de votre fichier, si vous avez un droit de saisie. Formats acceptés : CSV, TSV, TXT, JSON ou NDJSON, 2 Mo au plus. Déposez un échantillon représentatif, **sans données personnelles ni données sensibles**.

Dans le formulaire, les boutons **Proposer une description** et **Proposer des mots-clés** s'appuient aussi sur l'assistant.

**L'assistant n'enregistre jamais seul.** Il affiche un récapitulatif avec deux boutons : **Enregistrer la fiche** et **Ouvrir le formulaire pour relire**. Rien n'est enregistré sans votre clic. Ses réponses peuvent être inexactes : relisez-les. Les fiches préparées et non enregistrées apparaissent dans l'onglet « Brouillons » de **Mon espace**. Elles expirent après quelques heures.

## Faire valider et certifier

Une fiche a un statut parmi quatre.

| Statut | Signification |
|--------|---------------|
| **En cours** | La fiche est en cours de saisie. Aucune validation n'est demandée. |
| **À vérifier (métier)** | Une validation a été demandée. Un valideur de la direction relit la fiche. |
| **Qualifié** | La fiche est validée (visa de qualification). La mission AMDAC peut la certifier. |
| **Certifié** | La mission AMDAC a certifié la fiche, après la validation. |

Le parcours :

1.  **Demander la validation.** Quand la fiche est prête, cochez « Demander la validation de cette fiche » dans le formulaire. Vous pouvez aussi cliquer sur **Demander la validation** sur la page de la fiche. Le statut devient « À vérifier (métier) ».
2.  **Valider.** Un valideur de la direction (souvent le chef de bureau) relit la fiche. Il clique sur **Valider la fiche**. Son nom et la date sont enregistrés. Il faut avoir un droit de validation sur la direction. Ce droit ne suppose pas le droit de modifier la fiche.
3.  **Certifier.** La mission AMDAC clique sur **Certifier la fiche**. Ce bouton n'est disponible qu'après une validation.

Une fiche ne vous convient pas ? Il n'y a pas de refus à enregistrer. Utilisez le lien « Signaler un problème au saisisseur » sur la fiche.

### Quand un visa devient périmé

Un visa est conservé dans l'historique. Mais si vous modifiez une **métadonnée essentielle**, il ne porte plus sur le contenu actuel : il est marqué **périmé** et une nouvelle validation est demandée automatiquement. Les champs essentiels sont :

*   Titre
*   Description
*   Mots-clés
*   Niveau de sensibilité
*   Statut de publication
*   Licence
*   Bureau producteur

Les autres modifications ne touchent ni le statut ni les visas. Après une validation périmée, utilisez **Valider de nouveau**. Pour la certification, utilisez **Certifier de nouveau**.

## Complétude et mise à jour

### Le score de complétude

Le score se calcule à partir de 15 champs :

```
Titre, Description, Mots-clés, Statut de publication,
Niveau de sensibilité, Thème principal, Langue,
Couverture géographique, Bureau producteur,
Système d'information, Fréquence de mise à jour,
Contact principal, URL de téléchargement direct,
Formats des données, Licence juridique
```

| Score | Signification |
|-------|---------------|
| **< 50%** | Fiche incomplète. À enrichir rapidement. |
| **50%-99%** | Fiche correcte mais perfectible. |
| **100%** | Fiche complète. Statut recommandé : `Qualifié` ou `Certifié`. |

Chaque champ rempli fait monter le pourcentage. Le score mesure le remplissage, pas la qualité de la donnée.

**Bureau à préciser** : une direction ou un service en bureau producteur compte pour un demi-champ sur 15, soit 3 points de moins.

### Fiches à mettre à jour

Atlas Bercy ajoute à la date de dernière mise à jour de la donnée une période, selon la fréquence de mise à jour déclarée. Il obtient une échéance. Si elle est dépassée, la fiche apparaît dans l'onglet **À mettre à jour** de **Mon espace**.

Le calcul est impossible sans date de dernière mise à jour, sans fréquence, ou avec une fréquence sans période fixe (ponctuelle, temps réel, par exemple). La fiche indique alors le champ à compléter.

## Demander une donnée

Cliquez sur **Demander une donnée**. Vous choisissez ce que vous demandez.

| Type de demande | Quand l'utiliser |
|-----------------|------------------|
| **Je cherche une donnée qui n'est pas au catalogue** | Vous ne savez pas forcément qui la produit. La mission AMDAC oriente la demande. Elle apparaît dans « Besoins exprimés » pour les agents qui y ont accès. |
| **Je sais qui produit cette donnée et je veux qu'elle soit décrite** | Indiquez la direction ou le bureau producteur : il est invité à décrire la donnée au catalogue. |

Sur une fiche d'une donnée non ouverte, **Demander l'accès à cette donnée** ouvre une demande d'accès à ce jeu.

Les champs :

*   **De quelle donnée avez-vous besoin ?** (obligatoire, 200 caractères au plus) ;
*   **À quoi va-t-elle servir ?** : note, étude, tableau de bord… ;
*   **Pour quand ?** (facultatif) ;
*   **Direction ou bureau supposé** : obligatoire si vous savez qui produit la donnée, sinon laissez « Je ne sais pas ».

Cliquez sur **Déposer ma demande**. Le bureau concerné, ou la mission AMDAC à défaut, vous répond sous 5 jours ouvrés. Vous recevez un courriel à chaque réponse.

**Suivre ma demande** ouvre le détail. Vous retrouvez toutes vos demandes dans **Mon espace**, sous **Mes demandes**.

| Statut | Signification |
|--------|---------------|
| Réceptionnée | La demande est enregistrée. |
| Routée | Elle a été transmise à un destinataire. |
| En cours de traitement | Le destinataire l'instruit. |
| Acceptée | Elle est acceptée. |
| Refusée | Elle est refusée. |
| Traitée | Elle est traitée. |
| Annulée | Vous l'avez annulée. |

**Routage.** Un traitement quotidien cherche le destinataire dans cet ordre : la boîte fonctionnelle (BALF) du producteur visé, la BALF du bureau producteur de la fiche liée, la BALF d'une entité parente, le contact de la fiche, puis, à défaut, la mission AMDAC. Un seul courriel récapitulatif part par destinataire.

**Annuler.** Tant que la demande n'a pas reçu de réponse définitive (statuts « Réceptionnée », « Routée » ou « En cours de traitement »), cliquez sur **Annuler ma demande** depuis son détail.

**Côté producteur.** Avec un droit de saisie, **Demandes reçues** (dans **Mon espace**) liste les demandes qui vous sont adressées. Cliquez sur **Répondre**, choisissez un statut et rédigez la réponse. Le compteur **À traiter**, dans l'en-tête, regroupe ce qui vous attend : demandes reçues, fiches à valider, fiches à certifier.

## Pour le commanditaire (chef de bureau, direction)

Cette section s'adresse au responsable de la publication de l'entité. Elle fixe le périmètre de la saisie et l'organisation interne.

### Qu'est-ce qu'un « jeu de données » (périmètre) ?

Un **jeu de données (dataset)** est une collection cohérente de données structurées (lignes et colonnes, fichiers connexes) répondant à une même thématique ou à un même processus métier (ex : *Dépenses PLF 2025*, *Annuaire des entités*).

*   **À cataloguer** : les tables de données pérennes, les référentiels métiers, les bases de production ou d'études.
*   **À ne pas cataloguer** : les documents bureautiques de travail temporaire, les présentations, les rapports d'analyse textuels (sauf s'ils accompagnent un jeu de données en pièce jointe).

### Qui désigner dans mon équipe pour la saisie ?

La saisie demande avant tout une **connaissance métier** de la donnée, pas des compétences techniques.

*   **Profil recommandé** : un chargé d'études, un gestionnaire d'application ou un assistant administratif familier du sujet.
*   **Compétences requises** : savoir d'où vient la donnée, qui l'utilise, sa fréquence de mise à jour et son niveau de sensibilité.
*   **Droits** : la personne désignée a besoin d'un droit de saisie. Écrivez à la mission AMDAC en indiquant son adresse, sa direction et le droit souhaité (consulter, saisir, valider), ou laissez-la utiliser **Demander des droits**.

### Circuit de validation et gouvernance

1.  **Désignation** : le commanditaire désigne la personne qui saisit et lui transmet le kit d'embarquement.
2.  **Saisie** : elle remplit la fiche (idéalement les champs essentiels et les accès). Elle laisse la fiche « En cours ».
3.  **Demander la validation** : elle coche « Demander la validation de cette fiche », ou clique sur **Demander la validation**. Le statut devient « À vérifier (métier) ».
4.  **Valider la fiche** : un valideur de la direction relit les métadonnées métier et clique sur **Valider la fiche**. La fiche est « Qualifié ». Le commanditaire peut être ce valideur, avec un droit de validation.
5.  **Certifier la fiche** : la mission AMDAC audite la qualité et clique sur **Certifier la fiche**. La fiche est « Certifié ».

Fiches à relire : **Mon espace** (onglets « À valider » et « À certifier »), ou le filtre « À valider » de la recherche.

## Bonnes pratiques

### Ce qu'il faut faire

- **Une fiche = un dataset**. Une fiche par jeu de données logique, pas par fichier ou par année (sauf si pertinent).
- **Soyez précis dans la description**. C'est le texte qui permet aux autres de comprendre ce que vous produisez.
- **Mettez au moins 3 mots-clés**. C'est le principal levier de découverte.
- **Renseignez le bureau producteur**. C'est ce qui rattache la fiche à votre organisation.
- **Mettez à jour la date de dernière mise à jour de la donnée** à chaque actualisation.
- **Indiquez la fréquence de mise à jour**. Un dataset « mensuel » est plus fiable qu'un dataset sans fréquence déclarée.

### Ce qu'il faut éviter

- **Laisser le titre vide ou trop générique**. `dataset-2025` n'est pas un titre utile.
- **Oublier les mots-clés**. Sans mots-clés, personne ne trouvera vos données.
- **Déposer des données réelles en pièce jointe**. Le catalogue décrit les données, il ne les héberge pas.
- **Renseigner un champ dont vous ne connaissez pas la réponse**. Laissez-le vide.
- **Confondre URL du jeu de données et URL de téléchargement**. La première est une page d'information. La seconde est le fichier lui-même (CSV, JSON, etc.).

## Foire aux questions

### 1. Statut de publication ou niveau de sensibilité : quelle différence ?

*   **Statut de publication** : le statut de la donnée vis-à-vis de sa mise à disposition générale. « Données ouvertes » se déduit de ce champ.
*   **Niveau de sensibilité** : ce qui limite la diffusion. Un seul niveau : le plus restrictif qui s'applique.
*   La présence de données personnelles a sa propre case : « La donnée contient des données à caractère personnel ».
*   *Exemple* : un jeu contenant des données personnelles se décrit avec la case cochée, un niveau de sensibilité adapté et un statut de publication non ouvert. Les listes de valeurs proposées sont tenues par la mission AMDAC.

### 2. Si la donnée n'est pas ouverte, qui voit la fiche ?

Une fiche est visible des agents qui ont un droit de lecture sur la direction productrice, ou sur toutes les directions. Ils voient alors tous ses champs. Les autres ne la voient pas.

Pour une donnée non ouverte, l'encart « Accès à la donnée » indique le statut de publication, le niveau de sensibilité et le motif de restriction. Il propose **Demander l'accès à cette donnée**. Les données elles-mêmes ne sont jamais publiées par le catalogue.

### 3. Pourquoi me demande-t-on plusieurs URL ?

*   **URL du jeu de données** : la page d'information, le portail ou l'application métier d'origine.
*   **URL de téléchargement direct** : le lien vers le fichier brut (`.csv`, `.xlsx`, API). Si la donnée n'est pas téléchargeable en un clic, laissez ce champ vide.
*   **URL open data** : la page du jeu sur data.economie.gouv.fr ou data.gouv.fr, si elle existe.

## Conventions de nommage (Charte Open Data)

La [Charte Open Data des ministères économiques et financiers](https://139bercy.github.io/charte-open-data-mef/) fixe des règles précises pour les noms et identifiants des jeux de données publiés sur **[data.economie.gouv.fr](https://data.economie.gouv.fr)** (plateforme Huwise).

### Identifiant technique

L'identifiant technique est l'identifiant unique du dataset sur data.economie.gouv.fr et sur data.gouv.fr (qui le moissonne quotidiennement).

- Défini **avant** la publication, **ne pas le changer** après mise en production.
- Ne pas contenir de notions techniques propres à la plateforme (ex : `copie`, `nom_du_dataset0`).
- Préférer le **tiret court** (`-`) au **tiret bas** (`_`).
- En français courant.

### Préfixes d'environnement et de périmètre

| Préfixe | Usage | Exemple |
|---------|-------|---------|
| `test-` | Jeu de données de test | `test-prix-carburants-v2` |
| `preprod-` | Jeu de données de préproduction | `preprod-prix-carburants-v2` |
| `-restreint-` | Diffusion restreinte | `test-restreint-prix-carburants-v2` |
| `-interne-` | Diffusion interne | `test-interne-prix-carburants-v2` |

L'absence de préfixe désigne la **production**.

### Structure cohérente pour un ensemble de datasets

Si les datasets appartiennent à un même ensemble, utiliser le même préfixe :

- `plf-2025-autorisations-decouverts-comptes-speciaux`
- `plf25-depenses-2025-comptes-speciaux-non-dotes`

### Versionnement

La charte demande d'associer un numéro de version à chaque jeu publié et préconise le standard SemVer 2.0.0 (`<majeure>.<mineure>.<patch>`). Les modifications de chaque version se documentent dans la description ou dans un fichier `CHANGELOG.txt` joint. Les mises à jour peuvent aussi être horodatées par l'option « Afficher la date de modification » de la plateforme.

### Datasets millésimés

Préférer **un seul dataset** contenant l'historique sur plusieurs années (avec un champ `année`) plutôt que de créer un dataset par année. Cela facilite les comparaisons interannuelles.

Si le schéma évolue trop entre les années, il est acceptable de créer un dataset par année, avec une page référençant tous les datasets de la série.

### Licence par défaut

La licence par défaut est la **Licence Ouverte v2.0 (Etalab)**. Elle est recommandée pour tous les datasets ouverts.

---

## Pour aller plus loin (profils expérimentés)

Cette section s'adresse aux administrateurs de données, correspondants data et agents habitués aux concepts d'architecture de données.

*   Les métadonnées saisies suivent le standard **DCAT-AP**, qui sert à échanger entre catalogues.
*   Les données ouvertes sont publiées sur [data.economie.gouv.fr](https://data.economie.gouv.fr), que data.gouv.fr moissonne. Le champ « URL open data » relie la fiche à la page de publication.
*   Avec un droit de lecture sur toutes les directions, le bouton **Ouvrir dans Grist** de la recherche ouvre le document Grist du catalogue.
*   Pour proposer un nouveau champ, une nouvelle liste ou une intégration, écrivez à la mission AMDAC.

---

## Suivi qualité

Un jeu de données mis à jour à une fréquence bi-hebdomadaire permet de suivre le taux de remplissage de vos métadonnées :

- [Admin : qualité des jeux de données publiés](https://data.economie.gouv.fr/explore/dataset/admin-qualite-des-jeux-de-donnees-publies)

Le `quality_score` est indicatif mais constitue un bon repère pour identifier les fiches à enrichir.

---

## Besoin d'aide ?

*   **Mission AMDAC** : [amd@finances.gouv.fr](mailto:amd@finances.gouv.fr).
*   **Donner un avis** : le bouton est dans l'en-tête d'Atlas Bercy.
*   **Aide** : la page Aide du menu explique les parcours, avec des démonstrations commentées.

Vous pouvez aussi demander un rendez-vous de 30 minutes pour remplir une fiche ensemble ou faire le point sur votre catalogue.

---

## Glossaire

| Terme | Définition |
|-------|-----------|
| **Dataset** | Jeu de données. Ensemble structuré d'informations sur un sujet métier donné. |
| **Métadonnées** | Données qui décrivent les données : titre, description, format, sensibilité, etc. |
| **DCAT-AP** | European Data Catalogue Application Profile. Standard européen pour les catalogues de données. |
| **AMDAC** | Administrateur ministériel des données, des algorithmes et des codes sources. La mission AMDAC tient les listes de référence et certifie les fiches. |
| **BALF** | Boîte fonctionnelle. Adresse électronique professionnelle associée à un bureau. |
| **Visa** | Trace d'une validation (qualification) ou d'une certification. Il porte un nom et une date. |
| **Complétude** | Pourcentage de champs renseignés parmi 15. Il mesure le remplissage, pas la qualité. |
| **RIP** | Répertoire des informations publiques. Inventaire des informations publiques. |
| **data.economie.gouv.fr** | Plateforme open data des ministères économiques et financiers, opérée avec la solution Huwise. |
| **data.gouv.fr** | Portail national des données publiques ouvertes. Moissonnage quotidien de data.economie.gouv.fr. |
