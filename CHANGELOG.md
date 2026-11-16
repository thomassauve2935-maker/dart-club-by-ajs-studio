# Notes de version

## V0.14 — 16 novembre 2026

Version de test `0.14.0-languages-test`, code 15, Android 8.0 minimum.

- Français, anglais et espagnol : 278 entrées complètes, dont les règles des quinze jeux, les dialogues, les statistiques et le partage.
- Choix de langue dans les réglages, détection de la langue du téléphone et persistance du choix manuel.
- Pluriels, moyennes et descriptions d’accessibilité localisés.
- Noms de profils et journal de lancers préservés lors d’un changement de langue.
- Choix de langue inclus dans les sauvegardes, avec compatibilité des fichiers V0.13.
- Quatre thèmes et publicités désactivées conservés.
- 49 tests réussis, Android Lint sans erreur ni avertissement ; signature identique à la V0.13 pour mettre à jour sans désinstallation.
- Rendus Android vérifiés ; essai sur téléphone physique restant à effectuer.

## V0.13 — 16 novembre 2026

Version de test `0.13.0-club-test`, code 14, Android 8.0 minimum.

- Quatre thèmes mémorisés : Club clair, Sisal, Vert tournoi et Club nuit.
- Boutons et cartes animés, retours sur le score et le joueur actif, 180 et fin du match.
- Sons, volume et vibrations réglables ; mode silencieux respecté et option de réduction des animations.
- Reprise avec scores, derniers réglages et résumé fixe avant Commencer.
- Partage d’une carte PNG du résultat pour 1 à 8 joueurs via le sélecteur Android.
- Export/import des profils, statistiques, réglages et partie en cours, avec validation avant restauration et journal de récupération.
- Logo et règles conservés ; publicités désactivées ; statistiques doubles/triples inchangées.
- 39 tests réussis, Android Lint sans erreur ni avertissement ; signature de test conservée pour mettre à jour sans désinstallation.
- Rendus et vérifications automatisées ; essai sur téléphone physique restant à effectuer.

## V0.12 — 14 novembre 2026

Version de test `0.12.0-club-test`, code 13, Android 8.0 minimum.

- Nouveau logo plus explicite : cible traditionnelle, anneaux de score et fléchette dans le centre.
- Logo intégré aux en-têtes, à l’accueil des profils et à l’icône Android.
- Variante monochrome dédiée et marges adaptées aux masques d’icônes Android.
- Logos complets PNG/SVG disponibles ; palette claire et publicités désactivées conservées.
- 22 tests réussis, rapport Android Lint sans erreur ni avertissement, signature identique à la V0.11.

## V0.11 — 14 novembre 2026

Version de test `0.11.0-club-test`, code 12, Android 8.0 minimum.

- Palette claire bleutée, cartes de jeux colorées et statistiques en bleu, vert, violet et ambre.
- Publicités de démonstration retirées ; annonces désactivées dans toutes les variantes.
- Initialisation automatique AdMob et App ID de démonstration retirés du manifeste final.
- Future politique préparée : bandeau et une occasion d’annonce après chaque match terminé et sauvegardé, jamais entre deux legs. Annulation/reprise sans doublon.
- 22 tests réussis et rapport Android Lint sans erreur ni avertissement.
- Signature de test conservée depuis la V0.10 pour permettre la mise à jour sans désinstallation.

## V0.10 — 14 novembre 2026

Version de test `0.10.0-club-test`, code 11, pour Android 8.0 et versions ultérieures.

- Catalogue : 501 en vedette, illustration vectorielle et accès direct à la préparation ; quinze modes conservés.
- Finition : anthracite, surfaces et bordures affinées, navigation active rouge.
- Profils : statistiques sans cartes imbriquées, avatar avec initiale et menu Renommer/Supprimer.
- Match : score du joueur actif agrandi et accentué, sur téléphone et tablette.
- Cible statistique : simples, doubles, triples, 25 et bull conservés séparément.
- 20 tests réussis et rapport Android Lint sans erreur ni avertissement. Signature de test identique à la V0.9.

## V0.9 — 14 novembre 2026

Version de test `0.9.0-club-test`, code 10, pour Android 8.0 et versions ultérieures.

- Finition club noir mat et rouge, avec identité Dart Club By AJS Studio.
- Profils : création, validation du nom, renommage et conservation de la saisie après rotation.
- Résultats : sauvegarde immédiate, annulation du résultat lors de la reprise du lancer décisif et revanche.
- Ergonomie : bouton Commencer fixe, grandes commandes et match en deux colonnes sur tablette.
- Statistiques : simples, doubles, triples, 25 et bull distincts.
- Vérification : 18 tests réussis et contrôle Android Lint sans erreur ni avertissement.

L’APK est signée pour les tests. Les essais automatisés ne remplacent pas un essai sur téléphone physique.
