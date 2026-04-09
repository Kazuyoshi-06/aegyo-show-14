# Aegyo Show 14 — Affiche Officielle

Affiche événementielle au format A4 pour l'**Aegyo Show 14ème Édition**, tournoi officiel Yu-Gi-Oh! organisé à Madagascar en partenariat avec la YDLM (Youth Duel League Madagascar).

---

## Aperçu

| Propriété | Valeur |
|---|---|
| Format | A4 portrait — 794 × 1123 px |
| Dates | 1er – 2 mai 2026 |
| Lieu | Ex-Canal Olympia Andohatapenaka |
| Classement | Tournoi Classé Tier 3 · Qualification WCQ State (South Africa) |

---

## Structure du projet

```
aegyo-show-14/
├── affiche.html          # Source unique — HTML/CSS auto-contenu
└── assets/
    ├── aegyo.png         # Logo Aegyo Show
    ├── ydlm.png          # Logo YDLM
    ├── olympia.png       # Logo Ex-Canal Olympia
    ├── wcq-logo.png      # Logo WCQ officiel
    ├── flag-za.png       # Drapeau Afrique du Sud
    ├── stone-wall.jpg    # Texture de fond
    ├── x.png             # Séparateur "×" central
    ├── deckbox_premium.png   # Prix Champion
    ├── deckbox_300.png       # Prix Finaliste
    ├── sleeves.png           # Prix 3e Place
    ├── ikm.png           # Sponsor IKM Antsahavola
    ├── aegyo (1).png     # Sponsor Aegyo
    ├── mangaxmanga.png   # Sponsor Manga X Manga
    ├── mega_madagame.png # Sponsor Mega Madagame
    ├── Clikeko.png       # Sponsor Clikeko Store
    └── sanseking-1.png   # Sponsor Sanseking
```

---

## Utilisation

L'affiche est un fichier HTML unique, sans dépendances locales (polices chargées via Google Fonts).

**Ouvrir dans le navigateur :**
```
affiche.html → clic droit → Ouvrir avec → Chrome / Edge
```

**Exporter en PDF/image :**
1. Ouvrir dans Chrome
2. `Ctrl + P` → Enregistrer en PDF
3. Format : A4, marges : aucune, échelle : 100 %

> Les polices requièrent une connexion internet au premier chargement (Cinzel Decorative, Cinzel, Rajdhani via Google Fonts).

---

## Design

### Palette

| Rôle | Valeur |
|---|---|
| Or principal | `#FFD700` |
| Or moyen | `#C8960C` |
| Or sombre | `#8B6914` |
| Turquoise (WCQ) | `#2A9D8F` |
| Lapis (WCQ) | `#1B2A6B` |
| Sable clair | `#F0D080` |
| Fond | `#0A0800` |

### Typographie

| Police | Usage |
|---|---|
| Cinzel Decorative | Titres, rangs, numéros |
| Cinzel | Labels, noms de prix, sous-titres |
| Rajdhani | Corps de texte, informations pratiques |

### Composants clés

- **Header** : logos Aegyo × YDLM avec rayons lumineux et halo doré
- **Tagline** : bandeau pleine largeur avec titre principal et sous-titre
- **Date** : section centrale avec logo du lieu
- **Programme** : deux colonnes J1 / J2 en tablettes de pierre
- **Badge WCQ** : mise en avant de la qualification internationale
- **Récompenses** : liste de prix avec colonne rang (Champion ♛ / Finaliste / 3e Place) et visuels produit
- **Sponsors** : logos uniformisés en grille (boîte fixe 90 × 44 px, `object-fit: contain`)
- **Décor** : pyramides SVG bifaces (ombre/lumière) + hiéroglyphes latéraux + lumière divine

---

## Sponsors & Partenaires

- IKM Antsahavola
- Aegyo
- Manga X Manga
- Mega Madagame
- Clikeko Store
- Sanseking

---

## Dépendances

Aucune dépendance locale. Google Fonts en CDN uniquement.

```html
Cinzel Decorative · Cinzel · Rajdhani
https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700;900
  &family=Cinzel:wght@400;600;700;900
  &family=Rajdhani:wght@400;500;600;700
```
