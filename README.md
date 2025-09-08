# OctoLab Frontend

Frontend React pour OctoLab - Site vitrine du laboratoire d'étude des octopouces.

## 🚀 Installation

```bash
npm install
```

## 🛠️ Développement

```bash
npm run dev
```

L'application sera disponible sur `http://localhost:5173`

## 📦 Build

```bash
npm run build
```

## 🌐 Déploiement sur Vercel

1. **Connecter le repository à Vercel**
   - Aller sur [vercel.com](https://vercel.com)
   - Importer le projet depuis GitHub/GitLab

2. **Configuration Vercel**
   - **Root Directory**: `.` (racine du projet)
   - **Build Command**: `npm run build` (auto-détecté)
   - **Output Directory**: `dist` (auto-détecté)
   - **Install Command**: `npm install` (auto-détecté)

3. **Variables d'environnement**
   - Aucune variable requise (backend URL hardcodée)

## 🔧 Configuration

- **Backend URL**: Hardcodée dans `src/config/axios.js`
- **Vercel**: Configuration SPA dans `vercel.json`
- **Tailwind CSS**: Thème cyberpunk/aquatique personnalisé

## 📁 Structure

```
src/
├── components/     # Composants réutilisables
├── pages/         # Pages de l'application
├── contexts/      # Contextes React
├── config/        # Configuration (axios, etc.)
├── App.jsx        # Composant principal
└── main.jsx       # Point d'entrée
```

## 🎨 Technologies

- **React 18** - Framework frontend
- **Vite** - Build tool
- **Tailwind CSS** - Framework CSS
- **React Router** - Routing
- **Axios** - Client HTTP
- **Vercel** - Déploiement

## 🔗 Backend

Le frontend communique avec le backend déployé sur Render:
`https://octopouce-lab-uyly.onrender.com`