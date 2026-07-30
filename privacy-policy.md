# Politique de confidentialité — Modmail

**Dernière mise à jour : 30 juillet 2026**

Ce document décrit les données que le bot Discord **Modmail** (« le Bot ») collecte,
pourquoi il les collecte, combien de temps il les conserve, et comment en demander
la suppression.

Le Bot est un système de **ModMail** : il permet à un joueur de contacter l'équipe
de modération d'un serveur Discord par message privé, et relaie la conversation
dans un salon dédié côté équipe.

---

## 1. Responsable du traitement

Le Bot est opéré par l'administrateur du serveur communautaire qui l'a installé.

- **Contact :** contact.aparnstudios@gmail.com

---

## 2. Données collectées

### 2.1 Fournies volontairement par l'utilisateur

Lors de l'ouverture d'un ticket, un formulaire demande :

| Donnée | Obligatoire | Usage |
|---|---|---|
| Pseudo en jeu | Oui | Identifier le joueur sur le serveur de jeu |
| Pays | Oui | Orienter la demande vers l'équipe ou la langue appropriée |
| Raison de la demande | Oui | Traiter le ticket |

À la clôture d'un ticket, l'utilisateur peut **facultativement** laisser une note
de 1 à 5 et un commentaire libre sur la qualité du support.

### 2.2 Collectées automatiquement

- **Identifiant Discord** de l'utilisateur, des joueurs ajoutés au ticket, et des
  membres de l'équipe intervenant dessus.
- **Contenu des messages** échangés dans le cadre d'un ticket (messages privés
  envoyés au Bot et réponses de l'équipe), ainsi que les **pièces jointes**.
- **Métadonnées du ticket** : support concerné, numéro, horodatages, historique
  des transferts entre équipes, prise en charge.

### 2.3 Ce que le Bot ne collecte pas

Le Bot ne lit **aucun** message en dehors des messages privés qui lui sont
directement adressés et des salons de ticket qu'il a lui-même créés. Il ne
collecte ni adresse e-mail, ni adresse IP, ni donnée de paiement, ni historique
de navigation.

---

## 3. Base légale

Le traitement repose sur l'**intérêt légitime** de l'exploitant du serveur à
assurer la modération et le support de sa communauté, et sur le **consentement**
de l'utilisateur, qui choisit librement de contacter le Bot et de remplir le
formulaire. Un joueur invité à rejoindre le ticket d'un autre utilisateur doit
explicitement accepter avant que ses messages y soient reliés.

---

## 4. Conservation

| Donnée | Durée |
|---|---|
| État du ticket (fichier interne) | Supprimé **immédiatement** à la clôture |
| Salon Discord du ticket et son contenu | Supprimé **immédiatement** à la clôture |
| Ticket actif / dernier ticket clôturé (session) | Écrasé à chaque changement |
| Entrée dans le salon de logs (ouverture / clôture / transferts) | **Conservée** tant que l'exploitant ne la supprime pas |
| Note et commentaire d'évaluation | **Conservés** dans le salon de logs |

Les entrées de logs contiennent l'identifiant Discord de l'utilisateur, le support
concerné et les horodatages. Elles ne contiennent pas le contenu de la conversation.

---

## 5. Partage des données

Aucune donnée n'est vendue, louée, ni transmise à un tiers.

Les données sont hébergées sur **l'infrastructure de Discord** (salons, messages)
et sur le **serveur qui exécute le Bot** (fichiers de configuration et d'état).
L'usage de Discord est par ailleurs soumis à la
[politique de confidentialité de Discord](https://discord.com/privacy).

Le contenu d'un ticket est visible par les membres de l'équipe disposant des
permissions sur le salon concerné, ainsi que par les joueurs ayant accepté d'être
ajoutés au ticket.

---

## 6. Vos droits

Vous pouvez à tout moment demander :

- l'**accès** aux données vous concernant ;
- leur **rectification** ;
- leur **suppression** ;
- la **limitation** ou l'**opposition** au traitement.

Pour exercer ces droits, contactez l'adresse indiquée en section 1. Une demande de
suppression est traitée dans un délai raisonnable ; les données déjà supprimées
automatiquement à la clôture d'un ticket ne peuvent pas être restituées.

---

## 7. Sécurité

L'accès aux salons de ticket est restreint par les permissions Discord aux seuls
rôles de l'équipe concernée. Les fichiers d'état résident sur le serveur hébergeant
le Bot et ne sont pas exposés publiquement.

---

## 8. Mineurs

Le Bot suit les
[conditions d'utilisation de Discord](https://discord.com/terms), qui imposent un
âge minimum. Il n'est pas destiné aux personnes n'ayant pas l'âge requis pour
utiliser Discord dans leur pays de résidence.

---

## 9. Modifications

Cette politique peut évoluer. La date de dernière mise à jour figure en tête de
document. Toute modification substantielle sera annoncée sur le serveur
communautaire.
