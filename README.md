# Examen civique CSP — Quiz FR/JP

Site statique d'entraînement non officiel avec :
- QCM en français, 4 choix et une seule bonne réponse
- traduction japonaise activable
- correction immédiate et score
- mode examen blanc de 40 questions
- toutes les questions et liste de révision
- fonctionnement sans serveur ni base de données

## Publication sur GitHub Pages
1. Créez un dépôt GitHub vide.
2. Ajoutez `index.html` et `README.md` à la racine.
3. Dans Settings > Pages, choisissez `Deploy from a branch`, branche `main`, dossier `/root`.

## Publication sur Vercel
1. Importez le dépôt GitHub dans Vercel.
2. Framework Preset : `Other`.
3. Build Command : laissez vide.
4. Output Directory : laissez vide.
5. Cliquez sur Deploy.

## Avertissement
Le site est un outil pédagogique non officiel. Les questions de mise en situation de l'examen réel ne sont pas publiques.

## Fonctions audio et vocabulaire
- Lecture audio de la question en français
- Lecture de chaque choix et de la question complète
- Réglage de vitesse (lente, normale, rapide)
- Affichage des mots importants avec leur sens japonais
- Prononciation individuelle des mots

L'audio utilise la synthèse vocale intégrée au navigateur (Web Speech API). La voix disponible dépend de l'appareil et du navigateur.

## Mise à jour
- L’ordre des quatre réponses est mélangé à chaque nouvelle session.
- La traduction japonaise est affichée pour les quatre choix, y compris les mauvaises réponses.
