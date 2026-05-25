# Révisions UE2 — Tracker

Application web mobile pour suivre mon planning de révision UE2 (Électromagnétisme & Physique moderne) pour les rattrapages FGE2-S4.

## Fonctionnalités

- 12 jours de planning détaillé (du 26 mai au 10 juin 2026)
- Suivi par tâche avec sauvegarde automatique (localStorage)
- Notes par jour
- Mise en avant du jour en cours
- Mode standalone iOS (ajouter à l'écran d'accueil)

## Déploiement sur GitHub Pages

### Étape 1 — Créer le dépôt

1. Sur GitHub, crée un nouveau dépôt public (ex. `revisions-ue2`)
2. Upload le fichier `index.html` à la racine du dépôt

### Étape 2 — Activer GitHub Pages

1. Va dans **Settings** → **Pages** (menu de gauche)
2. Sous **Source**, choisis :
   - Branch : `main`
   - Folder : `/ (root)`
3. Clique **Save**
4. Attends 30 sec à 2 min — l'URL apparaîtra en haut de la page :
   `https://<ton-pseudo>.github.io/revisions-ue2/`

### Étape 3 — Installer sur le téléphone

**iPhone (Safari)** :
1. Ouvre l'URL dans Safari
2. Appuie sur le bouton de partage (carré avec flèche)
3. « Sur l'écran d'accueil » → « Ajouter »
4. L'icône Ψ apparaît, l'app se lance en plein écran

**Android (Chrome)** :
1. Ouvre l'URL dans Chrome
2. Menu ⋮ → « Ajouter à l'écran d'accueil »
3. Confirme

## Notes techniques

- **Stockage** : `localStorage` du navigateur. La progression est liée à l'appareil + au navigateur. Pas de synchronisation entre appareils.
- **Pas de backend** : 100% statique, un seul fichier HTML.
- **Polices** : chargées depuis Google Fonts (Fraunces, DM Sans, JetBrains Mono).

## Reset

Bouton « Réinitialiser » en bas de l'app pour tout effacer.
