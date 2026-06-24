# Portfolio Personnel - Spécification

## 1. Aperçu du Projet
- **Nom**: Portfolio Personnel Professionnel
- **Type**: Site web mono-page avec navigation smooth scroll
- **Résumé**: Portfolio moderne et attrayant pour attirer les recruteurs, contenant les sections About, Projects, Resume et Contact
- **Utilisateurs cibles**: Recruteurs, responsables RH, managers techniques

## 2. Spécification UI/UX

### Structure des Sections
1. **Header/Navigation** - Navbar fixe avec logo et liens
2. **Hero** - Section d'accueil avec photo, titre professionnel, sous-titre
3. **About** - Présentation personnelle et compétences
4. **Projects** - Galerie de projets avec cartes interactives
5. **Resume** - Expériences professionnelles et formations
6. **Contact** - Formulaire de contact et informations sociales
7. **Footer** - Copyright et liens sociaux

### Design Visuel

#### Palette de Couleurs
- **Primaire**: `#0f172a` (slate-900 - fond sombre élégant)
- **Secondaire**: `#1e293b` (slate-800)
- **Accent principal**: `#06b6d4` (cyan-500 - bleu cyan vif)
- **Accent secondaire**: `#22d3ee` (cyan-400)
- **Texte principal**: `#f8fafc` (slate-50)
- **Texte secondaire**: `#94a3b8` (slate-400)
- **Corps**: `#e2e8f0` (slate-200)

#### Typographie
- **Font principale**: "Outfit" (Google Fonts) - Moderne, géométrique
- **Font accents**: "Space Mono" (Google Fonts) - Pour les effets code/tech
- **H1**: 4rem (64px), font-weight: 700
- **H2**: 2.5rem (40px), font-weight: 600
- **H3**: 1.5rem (24px), font-weight: 600
- **Corps**: 1rem (16px), font-weight: 400
- **Petits**: 0.875rem (14px)

#### Effets et Animations
- **Background**: Dégradé subtil avec particules ou mesh gradient animé
- **Cards projets**: Effet hover avec scale(1.02) et glow cyan
- **Navigation**: Glassmorphism (backdrop-blur)
- **Sections**: Fade-in au scroll
- **Boutons**: Effet glow cyan au hover
- **Hero**: Texte typewriter ou gradient animé

### Layout Responsive
- **Mobile**: < 768px - Stack vertical, menu hamburger
- **Tablette**: 768px - 1024px - 2 colonnes
- **Desktop**: > 1024px - Layout complet, sidebar optional

## 3. Spécification Fonctionnelle

### Composants

#### Navigation
- Logo cliquable retournant au début
- Liens: About, Projects, Resume, Contact
- État actif sur scroll
- Menu mobile hamburger avec animation

#### Hero Section
- Photo de profil ronde avec border cyan
- Titre avec effet gradient
- Sous-titre avec animation typing
- Boutons CTA: "Voir mes projets" et "Me contacter"
- Background: Animated mesh gradient ou particules

#### About Section
- Photo personnelle
- Texte de présentation
- Compétences avec badges/pills animée
- Icônes pour compétences (Tech stack)

#### Projects Section
- Grille de cartes (3 colonnes desktop)
- Chaque carte:
  - Image/thumbnail
  - Titre du projet
  - Description courte
  - Technologies utilisées (badges)
  - Liens GitHub et Demo
- Effet hover avec elevation et glow

#### Resume Section
- Timeline verticale élégante
- Expériences avec date, poste, entreprise
- Formation avec date, diplôme, école
- Design chronologique moderne

#### Contact Section
- Formulaire: Nom, Email, Message
- Informations: Email, Téléphone, Location
- Liens réseaux sociaux avec icônes
- Carte ou embed map optionnel

#### Footer
- Copyright
- Liens sociaux
- Retour en haut

## 4. Critères d'Acceptation

### Fonctionnels
- [ ] Navigation fonctionnelle avec smooth scroll
- [ ] Toutes les sections accessibles
- [ ] Formulaire avec validation HTML5
- [ ] Liens externes fonctionnels
- [ ] Responsive sur tous les écrans

### Visuels
- [ ] Design cohérent avec la palette définie
- [ ] Animations fluides (60fps)
- [ ] Typographie cohérente
- [ ] Effets hover sur tous éléments interactifs
- [ ] Glassmorphism sur la navbar

### Performance
- [ ] Chargement rapide
- [ ] Images optimisées
- [ ] Pas d'erreur console