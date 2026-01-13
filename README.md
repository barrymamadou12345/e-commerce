# 🛒 E-Shop - Projet Atelier Tailwind CSS v4

## 📋 Description

Projet e-commerce simple pour pratiquer Tailwind CSS v4 avec Flexbox et la responsivité.

## 🎯 Objectifs pédagogiques

- Maîtriser Flexbox avec Tailwind CSS
- Comprendre la configuration `@theme` de Tailwind v4
- Travailler en équipe avec Git (branches, merge)
- Créer des layouts responsives

## 📁 Structure du projet

```
e-commerce/
├── tailwind-config.css   # Référence configuration @theme
├── index.html            # Page d'accueil
├── hommes.html           # Vêtements hommes
├── femmes.html           # Vêtements femmes
├── accessoires.html      # Accessoires
├── about.html            # Qui sommes-nous
├── favoris.html          # Mes favoris
├── contact.html          # Page contact
└── README.md
```

## 👥 Répartition des équipes (14 devs - 7 binômes)

| Page               | Section 1                  | Section 2                    |
| ------------------ | -------------------------- | ---------------------------- |
| `index.html`       | DEV 1 : Hero               | DEV 2 : Catégories           |
| `hommes.html`      | DEV 3 : Produits Vedettes  | DEV 4 : Nouveautés           |
| `femmes.html`      | DEV 5 : Collection Été     | DEV 6 : Tendances            |
| `accessoires.html` | DEV 7 : Sacs               | DEV 8 : Montres & Bijoux     |
| `about.html`       | DEV 9 : Notre Histoire     | DEV 10 : Nos Valeurs         |
| `favoris.html`     | DEV 11 : Favoris Vêtements | DEV 12 : Favoris Accessoires |
| `contact.html`     | DEV 13 : Formulaire        | DEV 14 : FAQ                 |

## 🚀 Instructions

### 1. Cloner le projet

```bash
git clone <url-du-repo>
cd e-commerce
```

### 2. Créer sa branche

```bash
git checkout -b feature/nom-section
```

### 3. Travailler sur sa section

Cherchez les commentaires `<!-- TODO DEV X -->` dans votre fichier.

### 4. Commit et push

```bash
git add .
git commit -m "feat: ajout section X"
git push origin feature/nom-section
```

### 5. Créer une Pull Request

Fusionnez votre travail avec la branche principale.

## 🎨 Classes Tailwind à utiliser

### Flexbox essentielles

- `flex`, `flex-col`, `flex-row`
- `flex-wrap`, `flex-nowrap`
- `justify-center`, `justify-between`
- `items-center`, `items-start`
- `gap-4`, `gap-6`

### Responsivité

- `sm:` (≥640px), `md:` (≥768px), `lg:` (≥1024px)
- Exemple : `flex-col sm:flex-row`

### Classes personnalisées (@theme)

- Couleurs : `bg-primary`, `text-primary`, `bg-accent`
- Shadows : `shadow-card`, `shadow-hover`
- Bordures : `rounded-card`, `rounded-button`

## ✅ Critères de validation

- [ ] Layout responsive (mobile → desktop)
- [ ] Utilisation de Flexbox
- [ ] Utilisation des classes @theme
- [ ] Code propre et commenté
- [ ] Merge sans conflits
