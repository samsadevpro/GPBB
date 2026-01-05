🧪 Breaking Prompt Generator

Générateur de Prompt — Breaking Bad 

🎯 Description du projet

Ce projet est une interface web immersive inspirée de l’univers visuel de Breaking Bad, permettant de générer automatiquement des prompts structurés.

L'utilisateur remplit différents champs, et un script assemble automatiquement une "formule de prompt" prête à être copiée.

Le design reprend :

L’esthétique chimique (tableau périodique, couleurs vert/toxicité)

Le thème laboratoire (étiquettes, warnings, formules chimiques)

Les animations lumineuses émeraude typiques de la série

🧩 Fonctionnalités principales
🧪 Saisie des paramètres

L’outil propose plusieurs sections modifiables :

Rôle

Objectif

Contexte

Livrables

Format

Préambule

Validation

⚗️ Calibration avancée

Un panneau « Chemical Calibration » permet d’ajuster :

Reasoning effort

Verbosity

Mode de génération

Limites

Eagerness

Temperature

📋 Génération automatisée

Affichage du prompt en temps réel dans l’encadré Lab Results

Mise en forme structurée (#Titres et valeurs)

☑️ Actions

Cook It → copie le prompt généré dans le presse-papier

New Batch → réinitialise entièrement les champs

🖥️ Structure du projet

📄 HTML

Organisé en plusieurs zones :

En-tête avec éléments du tableau périodique (Br, Ba)

Header animé

Formulaire de saisie divisé en sections

Panneau de résultats

Boutons de contrôle

🎨 CSS

Style inspiré Breaking Bad :

Dégradés vert toxique

Effet "laboratoire chimique"

Boîtes périodiques stylisées

Glow animation sur le titre

Scrollbars custom

Effets de survol chimiques

⚙️ JavaScript

Le script permet :

De surveiller tous les champs (input + change)

D’assembler dynamiquement le prompt

De gérer le copier-coller

De réinitialiser toutes les valeurs

Fonctions incluses :

generatePrompt()
copyPrompt()
resetForm()

📦 Installation

Télécharger ou cloner le fichier :

index.html

Ouvrir simplement le fichier dans un navigateur :
➡️ Aucun serveur n’est nécessaire.

Personnaliser si besoin :

Les labels

Les champs de calibration

Le style CSS

🚀 Utilisation

Remplis les champs du laboratoire.

Observe le résultat instantané dans Lab Results.

Clique 📋 Cook It pour copier le prompt.

Utilise 🔄 New Batch pour recommencer une nouvelle "cuisine".

🧪 Exemple de prompt généré

#Rôle
Expert en alchimie narrative

#Objectif
Créer une description immersive de laboratoire clandestin

#Contexte
Nuit, lumière verte, vapeur s’échappant des fioles

#Livrables
Texte descriptif de 3 paragraphes

#Format
Narration immersive + ton dramatique

#Validation
Doit respecter la cohérence chimique et stylistique

#Calibrage
Reasoning effort: high
Verbosity: medium
Mode: thinking
Temperature: 1.2

📜 Licence

Projet libre d’utilisation pour tout usage personnel ou créatif.
Aucune affiliation avec Breaking Bad ou AMC.

👍 Contribution

Tu veux améliorer le style, ajouter des options ou créer une version.
N’hésite pas à demander 😄
