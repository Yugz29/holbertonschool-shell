# 🐚 Shell Project – Init Files, Variables and Expansions

Bienvenue dans ce projet Bash ! 🎉  
Ce dépôt contient une série de scripts shell permettant de manipuler :

- les fichiers d’initialisation du shell
- les variables locales et d’environnement
- les alias
- les expansions arithmétiques
- les conversions numériques

---

📂 Description détaillée des scripts
0-alias

🔥 Alias dangereux

Redéfinit la commande ls pour supprimer tous les fichiers du dossier courant sans confirmation.

Attention : ne jamais l’exécuter en production.
1-hello_you

👋 Message de bienvenue

Affiche un message de salutation utilisant le nom de l’utilisateur connecté :

hello $USER

2-path

➕ Ajout au PATH

Ajoute /action à la variable d’environnement PATH.
3-paths

🔢 Compte les répertoires dans PATH

Transforme PATH en liste et affiche le nombre total de dossiers.
4-global_variables

🌍 Variables d’environnement

Liste toutes les variables d’environnement avec printenv.
5-local_variables

🧪 Toutes les variables shell

Affiche toutes les variables (locales + globales) visibles avec set.
6-create_local_variable

🔧 Variable locale BEST

Crée une variable uniquement accessible dans le shell courant.
7-create_global_variable

🌐 Variable d’environnement BEST

Crée et exporte la variable BEST pour tous les processus enfants.
8-true_knowledge

➕ Addition

Affiche 128 + $TRUEKNOWLEDGE (attention à définir TRUEKNOWLEDGE avant).
9-divide_and_rule

➗ Division

Affiche POWER / DIVIDE (variables à définir).
10-love_exponent_breath

🧮 Exponentiation

Calcule et affiche BREATH à la puissance LOVE.
11-binary_to_decimal

🔢 Conversion binaire → décimal

Convertit le contenu binaire de la variable BINARY en nombre décimal.
12-combinations

🔡 Combinaisons de lettres

Affiche toutes les paires {a..z}{a..z} sauf celles contenant oo.
13-print_float

💸 Nombre flottant formaté

Affiche la variable NUM avec deux chiffres après la virgule.
14-decimal_to_hexadecimal

🔠 Conversion décimal → hexadécimal

Affiche la variable DECIMAL en hexadécimal.
