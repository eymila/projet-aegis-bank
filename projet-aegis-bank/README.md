
## 📌 Contexte du projet

> ⚠️ **Note importante** : Namcod, Remolut & Aegis Bank sont des entreprises fictives créées dans le cadre d'un exercice pédagogique.

### Le défi

Face aux récentes controverses concernant la collecte de données abusives des néobanques, Aegis souhaite incarner une finance numérique responsable, centrée sur la confidentialité et l'anonymat optionnel.

**L'objectif** : Développer une landing page dédiée aux **créateur·rice·s de contenu, streamers et artistes digitaux**, en alliant :
- 🔒 Une approche **confiante, sérieuse et sécurisante**
- 🎮 Un univers **moderne et dynamique** qui parle aux créateurs
- 📱 Une expérience **zero-scroll** optimisée pour mobile

---

## 🎯 Objectifs du projet

### Objectif UX/UI

Créer une interface qui inspire **confiance et sécurité** tout en restant **attractive pour la génération des créateurs de contenu**.

| Valeur | Traduction dans l'interface |
|--------|----------------------------|
| **Confiance** | Design épuré, couleurs sobres (noir + rose vif), transparence des informations |
| **Sérieux** | Police Montserrat élégante, espacements maîtrisés, absence d'éléments superflus |
| **Sécurisant** | Image de fond rassurante, banderole promotionnelle claire, liens légaux visibles |

### Objectif technique

- ✅ Mobile-first avec **zero-scroll** (hauteur unique sur mobile)
- ✅ HTML/CSS pur (0 framework, 0 JavaScript)
- ✅ Validation **W3C** (0 erreur HTML/CSS)
- ✅ **Lighthouse** scores ≥ 90 sur toutes les catégories
- ✅ Accessibilité **WCAG 2.1 AA**

---

## 📊 Résultats des tests de qualité

### Lighthouse (Mobile)

| Catégorie | Score | Statut |
|-----------|-------|--------|
| **Performance** | 99/100 | ✅ Excellent |
| **Accessibilité** | 95/100 | ✅ Excellent |
| **Meilleures pratiques** | 100/100 | ✅ Parfait |
| **SEO** | 100/100 | ✅ Parfait |

### Validation W3C

| Validateur | Résultat |
|------------|----------|
| **HTML Validator** | ✅ 0 erreur |
| **CSS Validator** | ✅ 0 erreur |

### Accessibilité (WCAG 2.1 AA)

| Critère | Statut |
|---------|--------|
| Navigation clavier (Tab) | ✅ Fonctionnelle |
| Balises sémantiques | ✅ `header`, `main`, `footer`, `nav`, `section` |
| Attributs ARIA | ✅ `aria-label` sur éléments interactifs |
| Contraste des couleurs | ✅ Respecté |
| `prefers-reduced-motion` | ✅ Animations adaptables |

---

## 🎨 Direction artistique - Univers créateur

### Le choix d'un univers confiant et sécurisant

Pour cibler les créateurs de contenu tout en conservant une approche **sérieuse et professionnelle**, j'ai fait les choix suivants :

| Élément | Choix | Justification |
|---------|-------|---------------|
| **Couleur principale** | Noir (`#0a0a0a`) | Sérieux, élégance, professionnalisme |
| **Couleur d'accent** | Rose vif (`#ff00aa`) | Dynamisme, modernité, reconnaissable |
| **Police** | Montserrat | Lisible, élégante, caractère professionnel |
| **Boutons** | Arrondis, animations douces | Fluidité, confiance en l'interaction |

### Pourquoi cet univers ?

Les créateurs de contenu sont :
- **Exigeants** sur la transparence des frais
- **Soucieux** de la protection de leurs données
- **Habitués** aux interfaces modernes et fluides

→ Le design équilibre **sérieux bancaire** et **modernité créative** pour répondre à ces attentes.

---

## 📱 Spécifications fonctionnelles

### Navigation

| Élément | Description |
|---------|-------------|
| **Navbar Desktop** | Logo + 3 liens fonctionnels |
| **Menu mobile** | Burger menu 100% CSS (sans JavaScript) |
| **Authentification** | Boutons "Se connecter" / "S'inscrire" |

### Hero Section

| Élément | Contenu |
|---------|---------|
| **Titre** | "La néobanque éthique & transparente" |
| **Sous-titre** | "Tes revenus de créateur, gérés en toute transparence. Zéro frais cachés, zéro revente de données." |
| **CTA** | "Téléchargez l'app" |
| **Promotion** | "20€ offerts pour toute inscription avant le 31 mars 2026" |
| **Réseaux sociaux** | Telegram, Mastodon, BlueSky |

### Footer

- Mentions Légales
- Politique de Confidentialité
- Conditions d'Utilisation

---

## ⚡ Contrainte technique : ZERO SCROLL sur mobile

L'interface propose une expérience **zero-scroll sur mobile** avec une hauteur de vue unique s'adaptant dynamiquement :

```css
body {
    height: 100vh;        /* Hauteur = 100% de l'écran */
    overflow: hidden;     /* Pas de scroll */
}

main {
    flex: 1;              /* Prend l'espace restant */
    min-height: 0;
    overflow: hidden;
}

.footer {
flex-shrink: 0;
}

---

## 🛠️ Stack technique

| Technologie | Utilisation |
|-------------|-------------|
| **HTML5** | Structure sémantique |
| **CSS3** | Styles, animations, responsive |
| **Flexbox** | Agencement des éléments |
| **Git** | Versionnement |
| **GitHub** | Hébergement du code |
| **Netlify** | Déploiement (pas de Vercel) |

---

=======
## 📌 Contexte du projet

> ⚠️ **Note importante** : Namcod, Remolut & Aegis Bank sont des entreprises fictives créées dans le cadre d'un exercice pédagogique.

### Le défi

Face aux récentes controverses concernant la collecte de données abusives des néobanques, Aegis souhaite incarner une finance numérique responsable, centrée sur la confidentialité et l'anonymat optionnel.

**L'objectif** : Développer une landing page dédiée aux **créateur·rice·s de contenu, streamers et artistes digitaux**, en alliant :
- 🔒 Une approche **confiante, sérieuse et sécurisante**
- 🎮 Un univers **moderne et dynamique** qui parle aux créateurs
- 📱 Une expérience **zero-scroll** optimisée pour mobile

---

## 🎯 Objectifs du projet

### Objectif UX/UI

Créer une interface qui inspire **confiance et sécurité** tout en restant **attractive pour la génération des créateurs de contenu**.

| Valeur | Traduction dans l'interface |
|--------|----------------------------|
| **Confiance** | Design épuré, couleurs sobres (noir + rose vif), transparence des informations |
| **Sérieux** | Police Montserrat élégante, espacements maîtrisés, absence d'éléments superflus |
| **Sécurisant** | Image de fond rassurante, banderole promotionnelle claire, liens légaux visibles |

### Objectif technique

- ✅ Mobile-first avec **zero-scroll** (hauteur unique sur mobile)
- ✅ HTML/CSS pur (0 framework, 0 JavaScript)
- ✅ Validation **W3C** (0 erreur HTML/CSS)
- ✅ **Lighthouse** scores ≥ 90 sur toutes les catégories
- ✅ Accessibilité **WCAG 2.1 AA**

---

## 📊 Résultats des tests de qualité

### Lighthouse (Mobile)

| Catégorie | Score | Statut |
|-----------|-------|--------|
| **Performance** | 99/100 | ✅ Excellent |
| **Accessibilité** | 95/100 | ✅ Excellent |
| **Meilleures pratiques** | 100/100 | ✅ Parfait |
| **SEO** | 100/100 | ✅ Parfait |

### Validation W3C

| Validateur | Résultat |
|------------|----------|
| **HTML Validator** | ✅ 0 erreur |
| **CSS Validator** | ✅ 0 erreur |

### Accessibilité (WCAG 2.1 AA)

| Critère | Statut |
|---------|--------|
| Navigation clavier (Tab) | ✅ Fonctionnelle |
| Balises sémantiques | ✅ `header`, `main`, `footer`, `nav`, `section` |
| Attributs ARIA | ✅ `aria-label` sur éléments interactifs |
| Contraste des couleurs | ✅ Respecté |
| `prefers-reduced-motion` | ✅ Animations adaptables |

---

## 🎨 Direction artistique - Univers créateur

### Le choix d'un univers confiant et sécurisant

Pour cibler les créateurs de contenu tout en conservant une approche **sérieuse et professionnelle**, j'ai fait les choix suivants :

| Élément | Choix | Justification |
|---------|-------|---------------|
| **Couleur principale** | Noir  | Sérieux, élégance, professionnalisme |
| **Couleur d'accent** | Rose vif | Dynamisme, modernité, reconnaissable |
| **Police** | Montserrat | Lisible, élégante, caractère professionnel |
| **Boutons** | Arrondis, animations douces | Fluidité, confiance en l'interaction |

### Pourquoi cet univers ?

Les créateurs de contenu sont :
- **Exigeants** sur la transparence des frais
- **Soucieux** de la protection de leurs données
- **Habitués** aux interfaces modernes et fluides

→ Le design équilibre **sérieux bancaire** et **modernité créative** pour répondre à ces attentes.

---

## 📱 Spécifications fonctionnelles

### Navigation

| Élément | Description |
|---------|-------------|
| **Navbar Desktop** | Logo + 3 liens fonctionnels |
| **Menu mobile** | Burger menu 100% CSS (sans JavaScript) |
| **Authentification** | Boutons "Se connecter" / "S'inscrire" |

### Hero Section

| Élément | Contenu |
|---------|---------|
| **Titre** | "La néobanque éthique & transparente" |
| **Sous-titre** | "Tes revenus de créateur, gérés en toute transparence. Zéro frais cachés, zéro revente de données." |
| **CTA** | "Téléchargez l'app" |
| **Promotion** | "20€ offerts pour toute inscription avant le 31 mars 2026" |
| **Réseaux sociaux** | Telegram, Mastodon, BlueSky |

### Footer

- Mentions Légales
- Politique de Confidentialité
- Conditions d'Utilisation
