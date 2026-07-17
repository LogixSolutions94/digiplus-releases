# Digi+ — Mises à jour

Ce dépôt héberge **uniquement** les installateurs et les manifestes de mise à jour
des logiciels Digi+ (Logix Solutions). **Aucun code source ici.**

Les applications Digi+ installées lisent les fichiers `*.json` de ce dépôt pour
proposer les mises à jour. Chaque binaire est **signé cryptographiquement** :
l'application refuse toute mise à jour dont la signature ne correspond pas à la
clé publique embarquée — un fichier modifié ou non officiel ne s'installera jamais.

Un logiciel Digi+ sans **clé d'activation** est inutilisable. Les licences sont
vendues séparément par Logix Solutions.
