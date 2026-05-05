# RZI CAMP — ERP GIS Industriel
## Application de gestion géospatiale pour camp minier

---

## 🚀 HÉBERGEMENT RAPIDE

### Option 1 — GitHub Pages (recommandé, GRATUIT)
1. Créer un repo GitHub (ex: `rzi-camp-erp`)
2. Uploader `index.html` à la racine
3. Settings → Pages → Source: main → /root
4. URL : `https://[username].github.io/rzi-camp-erp/`

### Option 2 — Netlify (GRATUIT, le plus simple)
1. Aller sur https://netlify.com
2. Drag & drop le dossier `rzi-camp-deploy/` sur le dashboard
3. URL générée automatiquement en 30 secondes

### Option 3 — Vercel (GRATUIT)
1. Aller sur https://vercel.com
2. Import → drag & drop → Deploy
3. URL générée automatiquement

### Option 4 — Hébergement local (test)
```bash
# Python
python3 -m http.server 8080
# Ouvrir : http://localhost:8080
```

---

## 📁 FICHIERS
- `index.html` — Application complète (tout-en-un, 128 KB)

## 🔐 CONNEXION
Cliquer sur un des rôles : Admin / Manager / Terrain / Resto

## 🗺️ DONNÉES SHAPEFILE
- Source : Rox_RZEI.shp (Camp RZI)
- 204 bâtiments · 19 blocs · EPSG:4326
- Intégré directement dans index.html

## ⚠️ PRÉREQUIS RÉSEAU
L'application charge depuis CDN :
- Leaflet.js (cartographie) → unpkg.com
- Polices → fonts.googleapis.com
→ Connexion internet requise pour la carte et les polices

## 📞 MODULES
- Dashboard KPI temps réel
- Carte GIS interactive (Shapefile)
- Gestion Résidences (204 bâtiments)
- Restauration Anti-Fraude (QR dynamique)
- Maintenance industrielle
- Audit Trail complet
- IAM (RBAC 4 rôles)
