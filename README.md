# The People's Sports — Street Love 3x3

Projet pédagogique de site vitrine multipage — M2 STAPS, Communication digitale.

## Contenu
- `index.html` : accueil
- `association.html` : présentation de l'association
- `evenement.html` : présentation de Street Love 3x3
- `programme.html` : déroulé prévisionnel
- `informations.html` : fiche marketing avec les 8 rubriques obligatoires
- `formulaire.html` : page de collecte de leads
- `style.css` : feuille de style externe unique et partagée
- `images/` : illustrations vectorielles originales au format SVG
- `prompts.md` : journal de traçabilité de l'utilisation du LLM

## Ouvrir le site
Décompressez l'archive puis double-cliquez sur `index.html`. Le site fonctionne localement sans serveur et sans framework. La feuille CSS et les images sont chargées depuis le dossier du projet.

## Action humaine obligatoire : créer le Google Forms
La page `formulaire.html` contient volontairement un lien provisoire. Il ne fonctionne pas tant qu'il n'a pas été remplacé par le lien de votre propre formulaire.

Créez un formulaire Google intitulé **Pré-inscription — Street Love 3x3** avec ces 8 questions :

1. **Prénom** — réponse courte — obligatoire.
2. **Adresse e-mail** — réponse courte avec validation e-mail — obligatoire.
3. **Tranche d'âge** — choix multiple : Moins de 18 ans / 18–24 ans / 25–34 ans / 35 ans et plus — obligatoire.
4. **Commune de résidence** — réponse courte — obligatoire.
5. **Votre intérêt** — choix multiple : Jouer / Bénévolat / Partenariat / Recevoir des informations — obligatoire.
6. **Votre niveau en basket** — choix multiple : Débutant / Loisirs / Régulier / Confirmé / Je ne pratique pas — obligatoire.
7. **Comment avez-vous connu le projet ?** — choix multiple : Instagram / TikTok / Recherche Google / Association ou établissement / Bouche-à-oreille / Autre — obligatoire.
8. **Consentement** — case à cocher obligatoire : « J'accepte que les informations transmises soient utilisées uniquement pour répondre à ma demande et me communiquer les informations relatives au projet Street Love 3x3. » 

Ajoutez dans la description du formulaire une information claire sur le responsable du traitement (à compléter), la finalité, la durée de conservation envisagée et un moyen de contact pour exercer les droits. N'activez pas la collecte d'adresses e-mail Google en doublon si la question 2 collecte déjà l'e-mail. La newsletter, si elle existe, doit faire l'objet d'une case facultative séparée. Pour les personnes mineures, ne collectez pas de données réelles sans procédure et autorisation adaptées.

Après création :
1. Cliquez sur **Envoyer** puis copiez le lien répondant.
2. Ouvrez `formulaire.html` dans un éditeur de texte.
3. Remplacez `https://forms.gle/REMPLACER_PAR_VOTRE_LIEN` par le lien réel.
4. Enregistrez et testez le bouton depuis une fenêtre privée ou un autre compte Google.
5. Vérifiez que le formulaire est accessible à toute personne disposant du lien et que les réponses arrivent dans Google Sheets.

## Hypothèses à vérifier / remplacer avant un usage réel
Ce projet est fictif. La zone Nanterre / ouest parisien, le programme 10 h–18 h, la gratuité envisagée, le budget de communication et les objectifs chiffrés sont des hypothèses pédagogiques, pas des informations d'un événement confirmé. Ne communiquez aucune date, adresse précise, prix définitif, disponibilité de terrain, partenariat ou autorisation sans vérification.
Avant tout événement réel, vérifier : disponibilité et autorisation du terrain, assurance, encadrement, sécurité, matériel, règlement, accessibilité, capacité d'accueil, gestion des mineurs, droit à l'image, contact responsable et mentions RGPD.

## Tests techniques à effectuer
- Ouvrir les six pages localement.
- Cliquer sur les six liens du menu depuis chaque page.
- Tester les CTA et le lien Google Forms après remplacement.
- Vérifier l'affichage à environ 375 px de large (mobile) et sur ordinateur.
- Vérifier les images et leurs textes alternatifs.
- Contrôler l'orthographe, les titres, les tableaux et les liens.
- Vérifier que tous les fichiers sont bien dans l'archive ZIP et que `index.html` est à la racine.

## Sources des images
Les trois illustrations de `images/` sont des créations vectorielles originales réalisées spécifiquement pour ce projet avec du code SVG. Elles ne proviennent pas d'une banque d'images externe et ne représentent pas des photographies de personnes réelles.
