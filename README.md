# Hopper · Hub Services Decathlon

Prototype du **Projet 3 – The Bridge** (groupe 2 : Hugues-Olivier, Irmela, Mehdi, Nadine).
Cas fictif Decathlon : « la relation client augmentée par l'IA ».

Hopper est l'assistant conversationnel du hub : il guide chaque client vers le bon service
(**réparation, location, conseil produit, magasin**) et peut mettre un produit au panier.

## Ce que contient le dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Le hub complet et Hopper (version V45 du 18/11/2026), en un seul fichier |
| `.nojekyll` | Permet à GitHub Pages de servir le fichier tel quel |

## Voir le site en ligne (GitHub Pages)

1. Dans le dépôt : **Settings → Pages**.
2. *Source* : **Deploy from a branch**, branche **main**, dossier **/ (root)** → **Save**.
3. Après 1 à 2 minutes, le site est visible à l'adresse indiquée en haut de la page Pages.

## Bon à savoir

- Hébergé hors de Claude, Hopper fonctionne en **mode guidé** (sans IA générative) ;
  les vraies photos produits decathlon.fr s'affichent.
- Les tarifs viennent de decathlon.fr (relevé de novembre 2026). Les offres de Noël,
  les packs ski/camping/nautique et les coordonnées de magasins sont des **valeurs de démonstration**.
- Le panneau « Coulisses » simule les scénarios Make (webhook → router → Airtable → e-mail).
- Projet pédagogique, non affilié à Decathlon.
