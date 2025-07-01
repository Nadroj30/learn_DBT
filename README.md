# Structure d'un projet DBT

Vous pouvez maintenant revenir au dossier créé lors de `dbt init` et inspecter son contenu.

| Dossier/Fichier         | Description                                                                                             |
| :---------------------- | :------------------------------------------------------------------------------------------------------ |
| **`./dbt_project.yml`** | Le fichier de **configuration principal** du projet dbt, contenant les paramètres globaux.              |
| **`./models`** | Contient les **modèles SQL** définissant les transformations de données pour créer des vues ou des tables. |
| **`./macros`** | Contient les **macros Jinja**, des fonctions réutilisables pour simplifier le code SQL.                 |
| **`./tests`** | Dossier dédié aux **tests personnalisés** pour vérifier la validité et l'intégrité des données.       |
| **`./analyses`** | Stocke les fichiers SQL pour les **analyses exploratoires** qui ne créent pas d'objets dans le data warehouse. |
| **`./snapshots`** | Contient les fichiers de **snapshots** pour suivre les changements d'une table au fil du temps.      |
| **`./seeds`** | Contient des **fichiers CSV** à intégrer directement dans le data warehouse (données statiques).        |
| **`./logs`** | Stocke les **fichiers de logs** générés lors de l'exécution des commandes `dbt`.                          |

---

## Challenge

Maintenant que vous avez compris comment initialiser un projet DBT, faites la même chose sur votre machine, puis hébergez le dossier du projet sur un **dépôt GitHub**.

Mettez le lien du dépôt GitHub en solution de ce challenge.

---

## Critères de validation

* Le lien du dépôt est **accessible**.
* Tous les **dossiers requis** sont bien présents.
* Le fichier **`dbt_project.yml`** est présent.
