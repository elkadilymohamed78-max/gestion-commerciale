# 📊 Gestion Commerciale - Fichiers CSV

Ensemble complet de fichiers CSV pour gérer tous les aspects de votre activité commerciale.

## 📁 Fichiers inclus

### 1. **Tableau_de_Bord.csv**
Vue d'ensemble des KPIs importants :
- Total des ventes
- Nombre de clients actifs
- Stock total
- Chiffre facturé
- Commissions à payer

### 2. **Suivi_des_Ventes.csv**
Enregistrement de chaque vente :
- ID Vente, Date, Client
- Montant, Quantité
- Vendeur responsable
- Statut (Complétée, En cours, En attente)

### 3. **Gestion_Clientele.csv**
Base de données clients :
- ID Client, Nom, Email
- Téléphone, Adresse
- Total acheté, Catégorie (VIP, Standard, Nouveau)

### 4. **Inventaire_Stock.csv**
Gestion des produits :
- ID Produit, Nom, Prix Unitaire
- Quantité en stock, Stock minimum
- Valeur stock
- Alerte automatique si stock faible

### 5. **Facturation.csv**
Suivi des factures :
- N° Facture, Date, Client
- Montant HT, TVA (20%), Montant TTC
- Statut (Payée, En attente)

### 6. **Gestion_Commandes.csv**
Suivi des commandes :
- N° Commande, Date, Client
- Produit, Quantité, Prix unitaire
- Total, Statut (Complétée, En cours, En attente)

### 7. **Suivi_Commissions.csv**
Calcul des commissions :
- Vendeur, Total ventes
- Taux commission (5%)
- Montant commission calculé
- Statut et date de paiement

---

## 🚀 Utilisation

### Importer dans Excel :
1. Ouvrir Excel
2. Aller à `Fichier → Ouvrir`
3. Sélectionner chaque fichier CSV
4. Les données s'importsront automatiquement

### Importer dans Google Sheets :
1. Créer un nouveau classeur
2. Aller à `Fichier → Importer une feuille`
3. Charger chaque fichier CSV
4. Créer des liens entre les feuilles pour les calculs

### Convertir en Excel :
Utilisez un script Python :
```python
import pandas as pd
for file in ['Tableau_de_Bord.csv', 'Suivi_des_Ventes.csv', ...]:
    df = pd.read_csv(file)
    # Ajouter à un Excel avec différentes feuilles
```

---

## 📈 Données d'exemple

Les fichiers incluent des données d'exemple :
- **5 clients** avec historique d'achat
- **5 produits** avec stock
- **5 ventes** enregistrées
- **5 commandes** en suivi
- **3 vendeurs** avec commissions

### Totaux d'exemple :
- Total Ventes : 3 700 € HT
- Total Facturé : 4 440 € TTC
- Stock Total : 203 unités (17 600 € de valeur)
- Commissions : 327,50 €

---

## ✏️ Personnalisation

Pour adapter aux besoins de votre entreprise :

1. **Modifier les colonnes** : Ajouter/retirer des champs selon vos besoins
2. **Ajuster les pourcentages** : Changer la TVA, taux de commission
3. **Ajouter des clients/produits** : Ajouter des lignes dans chaque fichier
4. **Intégrer une base de données** : Exporter depuis votre ERP

---

## 💾 Format et encodage

- **Format** : CSV (valeurs séparées par des virgules)
- **Encodage** : UTF-8
- **Séparateur** : Virgule (,)
- **Décimales** : Point (.)

---

## 🔗 Intégration

Vous pouvez facilement intégrer ces données avec :
- **Excel** : Importer et créer des tableaux croisés
- **Google Sheets** : Synchroniser avec les formules
- **Power BI** : Créer des dashboards visuels
- **Python/Pandas** : Analyser et traiter les données
- **Base de données** : Importer dans SQL, MongoDB, etc.

---

## 📞 Support

Pour des questions ou modifications :
1. Créez un fichier d'exemple avec vos données
2. Utilisez Excel ou Google Sheets pour les calculs
3. Exportez en CSV pour l'archivage

---

**Créé le** : 2025-01-20  
**Version** : 1.0  
**Licence** : Libre d'utilisation
