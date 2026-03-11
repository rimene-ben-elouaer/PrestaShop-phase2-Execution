# rojet PrestaShop - Phase 2 : Exécution des Tests

Ce dépôt présente les résultats de la phase d'exécution des tests réalisée sur la boutique de démonstration PrestaShop.

## Résumé de l'exécution
Après avoir exécuté les **22 cas de test** conçus en Phase 1, voici le bilan :
* **Tests réussis (OK) :** 18
* **Tests en échec (KO) :** 4
* **Taux de succès :** 82%

## Gestion des Anomalies(MantisBT)
Les 4 échecs ont fait l'objet de rapports d'anomalies détaillés sur **MantisBT**. Ces anomalies bloquent des fonctionnalités critiques comme l'authentification et la persistance des données.

### Liste des tickets créés :
1. **Bug #00001 :** Erreur lors de l'envoi de l'email de réinitialisation.
2. **Bug #00002 :** Perte des modifications et déconnexion forcée (F5).
3. **Bug #00003 :** Perte totale de persistance (Sessions / DB).
4. **Bug #00004 :** Échec de la reconnexion client après déconnexion.

---

## 📂 Livrables de la phase
* **[Lien vers la Matrice mise à jour](./Matrice_tracabilite_Prestashop_Exécution.xlsx)** : Inclut désormais les colonnes **Statut (OK/KO)** et les **ID des anomalies**.
* **Preuve d'enregistrement Mantis :**
![Capture d'écran Mantis](./image_9992a1.png)

---
*Travail réalisé par Rimene Ben Elouaer - Mars 2026*
