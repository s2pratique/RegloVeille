# RégloVeille

Application mobile de veille réglementaire pour formateurs sécurité (CACES, habilitations électriques, travail en hauteur, AIPR).

## Démo

Déployer sur GitHub Pages :

1. Créer un dépôt GitHub (ex: `regloveille`)
2. Uploader tous les fichiers de ce dossier
3. Activer GitHub Pages : **Settings → Pages → Branch: main → / (root)**
4. Accéder à `https://[votre-login].github.io/regloveille/`

## Sur mobile (Android / iOS)

**Android Chrome :**
Ouvrir l'URL → Menu (⋮) → "Ajouter à l'écran d'accueil"

**iOS Safari :**
Ouvrir l'URL → Bouton partage (↑) → "Sur l'écran d'accueil"

L'app fonctionne ensuite hors connexion (PWA).

## Fonctionnalités de la démo

- 8 alertes réelles sourcées (avr. 2025 → avr. 2026)
- Filtrage par domaine (CACES, Électricité, AIPR, Hauteur)
- Marquage lu / non lu (persistant dans le navigateur)
- Compteur Qualiopi en temps réel
- Liens vers les textes officiels (Légifrance, INRS, CNAM)
- Onglet "À propos" avec pitch complet
- Fonctionne hors connexion (service worker)
- Installable comme app native (PWA)

## Alertes incluses (réelles et vérifiées)

1. Décret 2025-355 — fin du SIR CACES et habilitations élec (18 avr. 2025)
2. Arrêté 26 sept. 2025 — abrogation arrêté 1998, autorisation de conduite
3. Recommandation R482A — remplacement R482 engins de chantier (1 déc. 2025)
4. Décret 2024-552 — risque électrique travaux non électriques (19 déc. 2024)
5. Arrêtés 5 juil. 2024 — équivalence AIPR / habilitation BF-HF (7 janv. 2025)
6. FAQ CACES édition 7 — clarifications (janv. 2026, applicable mars 2026)
7. Rappel INRS — absence de validité légale formation hauteur
8. Q/R Ministère du Travail — modalités attestation médicale (6 nov. 2025)

## Stack technique

- HTML/CSS/JS vanilla — aucune dépendance externe
- PWA (manifest + service worker)
- localStorage pour persister les lectures
- Compatible iOS 14+ et Android 8+
