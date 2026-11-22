# How to Get and Use Your Personal Gemini AI Key (Hindi + English Guide)
## MAHAINDUSTRIES MOVIE STUDIO V4

---

## Step 1: Apni Free Gemini API Key kaise banayein? (How to Get a Free Key)
1. Browser mein Google AI Studio kholein: **https://aistudio.google.com/apikey**
2. Apni **Gmail ID** se Sign In karein.
3. **"Create API key"** button par click karein.
4. Koi bhi project select karein aur **"Create API key in existing/new project"** dabaye.
5. Aapko `AIzaSy...` se shuru hone wali ek key milegi — use **Copy** kar lein.
   - *Note:* Google Gemini API ke **Free Tier** ke liye koi credit/debit card add nahi karna hota.

---

## Step 2: App ke andar Personal Key kaise use karein? (Bina Vercel / Render ke)
Ye tareeka **personal use** (sirf aapke apne phone/PC) ke liye sabse aasaan hai:
1. **MAHAINDUSTRIES MOVIE STUDIO V4** kholein.
2. Left sidebar (ya Android mein **All Tools**) se **AI Studio** tab kholein.
3. **"🔑 Personal Gemini Key (Device-Only)"** box mein apni copied `AIzaSy...` key paste karein.
4. **"💾 Save Key"** button dabaye.
   - Aapki key sirf aapke device ke browser mein save hoti hai — kabhi GitHub par upload nahi hoti.
5. Upar Script box mein apna movie idea likhein (jaise: *"Ramayan war trailer in Hindi"*).
6. **"✨ Gemini AI Write Movie Script"** button dabaye — 3 second mein live Gemini AI poori 3-scene script likh dega!
7. Ab **"🎬 Script → Movie"** button dabakar us script se automatically poori multi-track movie timeline par bana lein!

---

## Step 3: Public Website (Vercel) par Key kaise lagayein? (Recommended for Sharing)
Agar aap apni website ka link **doosre logon** ke saath share karna chahte hain:
1. Apne GitHub repo (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, aur `api/` folder) ko **Vercel.com** par import karein.
2. Vercel Project → **Settings → Environment Variables** mein add karein:
   - **Key:** `GEMINI_API_KEY`
   - **Value:** `aapki_AIzaSy_key`
3. **Deploy / Redeploy** dabaye — ab sabhi users bina apni key dale aapke Vercel link par fast Gemini AI use kar payenge!

---

## Security Rules (Suraksha Niyam)
- Apni `AIzaSy...` key kabhi bhi seedhe `index.html` code mein hardcode karke GitHub par upload **na** karein.
- Kisi doosre ke phone/PC par use karne ke baad **🗑 Clear** button dabakar apni personal key hata dein.
