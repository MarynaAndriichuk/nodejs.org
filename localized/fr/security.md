---
layout: hbs
title: Sécurité
---

# Sécurité

## Signaler un bug dans Node.js

Signalez des bugs de sécurité dans Node.js via [HackerOne](https://hackerone.com/nodejs).

Votre rapport sera reconnu dans les 24 heures et vous recevrez une réponse plus détaillée à votre rapport dans les 48 heures indiquant les prochaines étapes dans la gestion de votre soumission.

Après la réponse initiale à votre rapport, l'équipe de sécurité s'efforcera de tenir au courant des progrès en cours vers une correction et une annonce complète, et peut demander des informations supplémentaires ou des conseils entourant le problème signalé.

### Programme Node.js Bug Bounty

Le projet Node.js s'engage dans un programme officiel de récompenses pour les chercheurs en sécurité et les divulgations publiques responsables. Le programme est géré par la plate-forme Hackerone. Voir <https://hackerone.com/nodejs> pour plus de détails.

## Signaler un bug dans un module tiers

Les bogues de sécurité dans les modules tiers devraient être signalés à leurs responsables respectifs et devraient également être coordonnés par l'intermédiaire du nœud. s Écosystème Équipe de sécurité via [HackerOne](https://hackerone.com/nodejs-ecosystem).

Les détails concernant ce processus peuvent être trouvés dans le dépôt [du groupe de travail Security](https://github.com/nodejs/security-wg/blob/master/processes/third_party_vuln_process.md).

Merci pour l'amélioration de la sécurité de Node.js et de son écosystème. Vos efforts et la divulgation responsable sont grandement appréciés et seront reconnus.

## Politique de divulgation

Voici la politique de divulgation de sécurité pour Node.js

* Le rapport de sécurité est reçu et reçoit un gestionnaire principal. Cette personne coordonnera le processus de correction et de publication. Le problème est confirmé et une liste de toutes les versions affectées est déterminée. Le code est audité pour trouver des problèmes similaires potentiels. Les corrections sont préparées pour toutes les versions qui sont encore en maintenance. Ces correctifs ne sont pas validés dans le dépôt public , mais plutôt tenus localement en attente de l'annonce.

* Une date d'embargo suggérée pour cette vulnérabilité est choisie et un CVE (Vulnérabilités et expositions courantes (CVE®)) est demandé pour la vulnérabilité.

* À la date de l'embargo, la liste de diffusion de Node.js sur la sécurité est envoyée une copie de l'annonce . Les changements sont poussés vers le dépôt public et les nouvelles versions sont déployées sur nodejs.org. Dans les 6 heures suivant la notification de la liste de diffusion, une copie de l'avis sera publiée sur le blog Node.js.

* Typiquement, la date de l'embargo sera fixée 72 heures à partir de la date d'émission de la CVE . Cependant, cela peut varier en fonction de la gravité du bogue ou de la difficulté à appliquer une correction.

* Ce processus peut prendre un certain temps, surtout lorsque la coordination est requise avec les responsables d'autres projets. Tous les efforts seront faits pour traiter le bogue de manière aussi opportune que possible ; cependant, il est important que nous suivions le processus de publication ci-dessus pour nous assurer que la divulgation est gérée d'une manière cohérente.

## Réception des mises à jour de sécurité

Les notifications de sécurité seront distribuées via les méthodes suivantes.

* <https://groups.google.com/group/nodejs-sec>
* [https://nodejs.org/fr/blog/](https://nodejs.org/en/blog/)

## Commentaires sur cette politique

Si vous avez des suggestions sur la façon dont ce processus pourrait être amélioré, veuillez soumettre une demande d'ajout [](https://github.com/nodejs/nodejs.org) ou [un fichier un problème](https://github.com/nodejs/security-wg/issues/new) pour discuter.
