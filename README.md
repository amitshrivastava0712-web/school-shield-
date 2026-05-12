# 🛡️ SchoolShield — School Management SaaS

## 🚀 Netlify pe Deploy Kaise Karein

### Option 1: Drag & Drop (Sabse Aasaan)
1. Pehle build karo:
   ```
   npm install
   npm run build
   ```
2. `dist/` folder ko Netlify pe drag & drop karo:
   → https://app.netlify.com/drop

### Option 2: Netlify CLI
```bash
npm install -g netlify-cli
npm install
npm run build
netlify deploy --prod --dir=dist
```

### Option 3: GitHub se Connect
1. Ye folder GitHub repo me push karo
2. Netlify Dashboard → "New site from Git"
3. Build command: `npm run build`
4. Publish directory: `dist`

---

## 💻 Local Development
```bash
npm install
npm run dev
```
Open: http://localhost:5173

---

## 🔐 Demo Login Credentials
| Role | Password |
|------|----------|
| 👑 Super Admin | super123 |
| 👩‍💼 Principal | principal123 |
| 👨‍🏫 Teacher | teacher123 |
| 👨‍👩‍👦 Parent | parent123 |
| 🚌 Driver | driver123 |

---

## ✨ AI Features (Anthropic API)
AI features (Notice Generator, Fee Reminder) ke liye Anthropic API key chahiye.
Deploy karne ke baad Netlify environment variables me set karo.

---

Built with React + Vite ⚡
