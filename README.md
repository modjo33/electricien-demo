# Site vitrine – Électricien (démo)

Site vitrine **one-page**, moderne et responsive, réalisé comme **démonstration professionnelle** pour un artisan électricien.

👉 Objectif : servir de **template réutilisable** pour des sites vitrines d’artisans (électriciens, plombiers, etc.).

---

## 🔧 Présentation du projet

**Client (démo)**  
Cédric Founau – Électricien  
📍 1 rue du Lavoir, 33640 Isle-Saint-Georges  
📞 06 99 72 86 07  

**Type de site**
- Site vitrine one-page
- Design dark moderne
- Responsive (mobile / tablette / desktop)
- Déploiement via GitHub Pages

---

## 🧱 Structure du site

Sections présentes :

1. Hero (accroche + CTA)
2. Services détaillés
3. Process d’intervention (4 étapes)
4. Réalisations (cartes + modales)
5. Offres
6. FAQ (accordéon accessible)
7. Contact (formulaire prêt pour Formspree)
8. Footer + mentions légales

---

## ✨ Fonctionnalités

- Menu mobile (burger)
- Scroll fluide
- Animations légères au scroll (`IntersectionObserver`)
- FAQ accordéon (accessible avec `aria-expanded`)
- Modales pour les réalisations
- Bouton “Appeler” fixe sur mobile
- Focus visibles (accessibilité)
- Code simple, sans framework

---

## 🛠️ Stack technique

- **HTML5**
- **CSS3** (sans framework)
- **JavaScript vanilla**
  - JS uniquement dans `index.html`
- **Git / GitHub**
- **GitHub Pages** pour le déploiement

Aucune dépendance externe.

---

## 📁 Arborescence

```text
electricien-demo/
├── index.html
├── styles.css
└── README.md
2️⃣ Cloner le projet électricien depuis GitHub
git clone git@github.com:modjo33/electricien-demo.git

3️⃣ Entrer dans le projet
cd electricien-demo

4️⃣ Vérifier que tout est là
ls


Tu dois voir :

index.html  styles.css  README.md  images/ (si présent)

▶️ Lancer le site en local

Depuis la racine du projet :

python3 -m http.server 5500

🌍 Ouvrir dans le navigateur

Local :

http://localhost:5500/


En ligne (GitHub Pages) :

https://modjo33.github.io/electricien-demo/