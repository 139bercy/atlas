# 📘 Trame de Guide Local — Catalogage de Bureau

*Ce document est une trame personnalisable. Chaque bureau ou sous-direction peut l'éditer en 5 minutes pour fixer ses propres consignes locales avant de le transmettre aux collaborateurs.*

---

# Consignes locales pour le catalogage des données — [Nom du Bureau / Direction]

## 1. Contacts et rôles locaux

*   **Commanditaire / Validateur métier** : [Nom du chef de bureau / adjoint] — (Valide la cohérence métier des fiches)
*   **Correspondant Data principal** : [Nom du référent technique/data s'il existe] — (Aide technique de premier niveau)
*   **Boîte fonctionnelle (BALF) du Bureau** : [Adresse email fonctionnelle] — (Reprise comme point de contact si le champ « Point de contact : entité » reste vide)

---

## 2. Périmètre et liste des données du bureau

Voici la liste des principaux jeux de données de notre bureau que nous devons cataloguer en priorité :

1.  **[Nom du Jeu de Données 1]** : [Brève description - ex. : Base des indicateurs de performance]
2.  **[Nom du Jeu de Données 2]** : [Brève description - ex. : Référentiel des bénéficiaires d'aides]
3.  **[Nom du Jeu de Données 3]** : [Brève description]

---

## 3. Choix des valeurs par défaut pour notre bureau

Pour assurer la cohérence de nos fiches, merci d'utiliser par défaut les valeurs suivantes :

*   **Bureau producteur** : Sélectionner `[Saisir le nom exact tel qu'il apparaît dans la liste d'Atlas Bercy]`
*   **Thème principal** : `[Sélectionner le domaine principal du bureau - ex. : Finances publiques]`
*   **Couverture géographique** : `[maille habituelle du bureau - ex. : National]` (sauf cas particulier)
*   **Langue** : `[langue habituelle - ex. : Français]`

---

## 4. Sensibilité et publication (règles internes)

*   Nos données étant majoritairement `[restreintes / ouvertes]`, merci de veiller aux réglages suivants :
    *   Si le jeu de données contient des données personnelles (ex. : noms, emails, identifiants agents) : cocher « La donnée contient des données à caractère personnel », choisir un statut de publication non ouvert et renseigner le « Motif de restriction ».
    *   Si le jeu de données est destiné à l'open data : sélectionner le statut de publication `Données ouvertes` et utiliser la licence `Licence Ouverte v2.0 (Etalab)`.

---

## 5. Circuit de validation du bureau

Une fois la saisie d'une fiche terminée dans Atlas Bercy :
1.  Ne pas la valider soi-même.
2.  Cocher **« Demander la validation de cette fiche »**, ou cliquer sur **Demander la validation** sur la fiche. Le statut devient **`À vérifier (métier)`**.
3.  Prévenir **[Nom du validateur]** que la fiche est prête. Il la retrouve dans « Mon espace », onglet « À valider ».
4.  Après relecture, il clique sur **Valider la fiche** (statut `Qualifié`). La mission AMDAC peut ensuite cliquer sur **Certifier la fiche** (statut `Certifié`).
