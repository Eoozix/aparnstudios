# Politique de confidentialité — NatMail, NatGuard, NatUtils

**Dernière mise à jour : 4 octobre 2026**

Ce document décrit les données que les bots Discord **NatMail**, **NatGuard** et
**NatUtils** (« les Bots ») collectent, pourquoi ils les collectent, combien de
temps elles sont conservées, et comment en demander la suppression.

Les Bots sont un projet communautaire indépendant. Ils ne sont **ni édités ni
approuvés par NationsGlory**.

---

## 1. Responsable du traitement

Les Bots sont développés et hébergés par **Aparn Studios**.

- **Contact :** contact.aparnstudios@gmail.com

L'équipe de chaque serveur Discord qui installe un Bot accède aux données de
**son propre serveur** (tickets, journaux) et décide de l'usage qu'elle en fait.

---

## 2. Données collectées, bot par bot

### 2.1 NatMail — tickets et demandes

**Fournies volontairement.** À l'ouverture d'un ticket, un formulaire demande :

| Donnée | Usage |
|---|---|
| Pseudo en jeu | Identifier le joueur sur le serveur de jeu |
| Raison de la demande | Traiter le ticket |

Si le joueur a lié un compte Recube (section 2.2), le pseudo n'est pas redemandé :
il vient, avec le pays, du compte de jeu qu'il choisit.

À la clôture, l'utilisateur peut **facultativement** laisser une note de 1 à 5 et
un commentaire.

**Collectées automatiquement.**

- **Identifiant Discord** de l'utilisateur, des joueurs ajoutés au ticket et des
  membres de l'équipe qui interviennent.
- **Contenu des messages** échangés dans un ticket (messages privés envoyés au
  Bot et réponses de l'équipe) et **pièces jointes**.
- **Métadonnées du ticket** : support concerné, numéro, horodatages, historique
  des transferts, prise en charge.
- **Préférences** : langue choisie, notifications en attente de lecture.

### 2.2 Liaison d'un compte Recube (facultative)

Un joueur peut choisir de lier son compte Discord à son compte **Recube**. Sont
alors enregistrés :

- l'identifiant Discord, l'identifiant et le nom du compte Recube, la date et la
  méthode de liaison ;
- les **comptes de jeu** rattachés à ce compte Recube (pseudo, serveur,
  identifiant de joueur), tels qu'ils figurent sur le profil Recube.

Cette liaison est **commune aux trois Bots** : un joueur lié une fois est reconnu
par chacun d'eux. Elle se supprime à tout moment (voir section 6).

La tête du personnage d'un joueur peut être affichée à côté de son pseudo ; elle
est mise en cache au plus **24 heures**.

### 2.3 NatGuard — protection

À la date de ce document, NatGuard n'enregistre **aucune donnée personnelle**. Il
ne conserve que la configuration du serveur sur lequel il est installé.

### 2.4 NatUtils — tutoriels et wiki

À la date de ce document, NatUtils n'enregistre **aucune donnée personnelle**. Il
ne conserve que la configuration du serveur sur lequel il est installé.

Si NatGuard ou NatUtils venaient à collecter d'autres données, cette politique
sera mise à jour **avant** la mise en service de la fonctionnalité concernée.

### 2.5 Données de jeu publiques

Les Bots peuvent interroger l'**API publique de NationsGlory** pour afficher des
données de jeu publiques (pays d'un joueur, grade, fiche d'un pays, classements…).
Ces données sont déjà publiques sur le site de NationsGlory ; les Bots les lisent
sans rien y écrire.

### 2.6 Ce que les Bots ne collectent pas

NatMail ne lit **aucun** message en dehors des messages privés qui lui sont
directement adressés et des salons de ticket qu'il a lui-même créés. Les Bots ne
collectent ni adresse e-mail, ni adresse IP, ni donnée de paiement, ni mot de
passe, ni historique de navigation.

---

## 3. Base légale

Le traitement repose sur :

- le **consentement** de l'utilisateur, qui choisit librement de contacter un Bot,
  de remplir un formulaire ou de lier un compte. Un joueur invité à rejoindre le
  ticket d'un autre doit explicitement accepter avant que ses messages y soient
  reliés ;
- l'**intérêt légitime** de l'équipe d'un serveur à assurer le support et la
  protection de sa communauté.

---

## 4. Conservation

| Donnée | Durée |
|---|---|
| État d'un ticket en cours | Supprimé à la clôture |
| Salon Discord du ticket | Supprimé à la clôture |
| **Transcription** du ticket (texte de la conversation) | **Conservée** après la clôture, rattachée à l'entrée de journal, tant que l'équipe ou Aparn Studios ne la supprime pas |
| Entrée dans le salon de journal (ouverture, clôture, transferts) | **Conservée** tant que l'équipe du serveur ne la supprime pas |
| Note et commentaire d'évaluation | **Conservés** dans le salon de journal |
| Notifications en attente | Supprimées une fois lues |
| Liaison Recube et comptes de jeu | Conservés jusqu'à la déliaison ou une demande de suppression |
| Code de liaison en attente | Expire automatiquement |
| Tête de personnage en cache | 24 heures au plus |

---

## 5. Partage des données

Aucune donnée n'est vendue, louée, ni cédée à un tiers.

Les données transitent ou résident chez :

- **Discord** (salons, messages, journaux), dont l'usage est soumis à la
  [politique de confidentialité de Discord](https://discord.com/privacy) ;
- le **serveur qui exécute les Bots** (fichiers d'état, transcriptions, base des
  liaisons), qui n'est pas exposé publiquement ;
- **Recube** et l'**API publique de NationsGlory**, auxquels les Bots envoient
  uniquement le pseudo ou l'identifiant à consulter, pour lire des informations
  publiques.

Le contenu d'un ticket et sa transcription sont visibles par les membres de
l'équipe du serveur concerné, et par les joueurs ayant accepté d'être ajoutés au
ticket.

---

## 6. Vos droits

Vous pouvez à tout moment demander :

- l'**accès** aux données vous concernant ;
- leur **rectification** ;
- leur **suppression** ;
- la **limitation** ou l'**opposition** au traitement.

La liaison d'un compte Recube se supprime directement depuis Discord, avec la
commande de déliaison de NatMail. Pour le reste, écrivez à l'adresse indiquée en
section 1 ; la demande est traitée dans un délai raisonnable. Les entrées de
journal et les transcriptions d'un serveur peuvent aussi être supprimées par
l'équipe de ce serveur.

Vous pouvez enfin saisir l'autorité de protection des données de votre pays (en
France, la CNIL).

---

## 7. Sécurité

L'accès aux salons de ticket est restreint par les permissions Discord aux seuls
rôles de l'équipe concernée. Les fichiers d'état et la base des liaisons résident
sur le serveur hébergeant les Bots, accessible uniquement par clé, et ne sont pas
exposés publiquement.

---

## 8. Mineurs

Les Bots suivent les
[conditions d'utilisation de Discord](https://discord.com/terms), qui imposent un
âge minimum. Ils ne sont pas destinés aux personnes n'ayant pas l'âge requis pour
utiliser Discord dans leur pays de résidence.

---

## 9. Modifications

Cette politique peut évoluer. La date de dernière mise à jour figure en tête de
document. Toute modification substantielle sera annoncée avant son entrée en
vigueur.
