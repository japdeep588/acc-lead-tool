# DataReadyTest — by Analytics Career Connect

> Free Data Analyst Career Assessment Tool — generates leads via SEO + Gmail counselling flow.

---

## 🚀 How to Make This Live (Step-by-Step)

### Step 1 — Create a GitHub Account
1. Go to **https://github.com**
2. Click **Sign up**
3. Enter your email, create a password, choose a username
   - Suggested username: `acc-japdeep` or `analyticscareerconnect`
4. Verify your email → you're in

---

### Step 2 — Create a New Repository
1. After login, click the **"+"** icon (top-right) → **"New repository"**
2. Fill in:
   - **Repository name:** `acc-lead-tool`
   - **Description:** Free Data Analyst Career Assessment Tool by ACC
   - **Visibility:** ✅ Public (required for free GitHub Pages)
   - **Add a README file:** ✅ Check this box
3. Click **"Create repository"**

---

### Step 3 — Upload Your Files
1. Inside your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop BOTH files:
   - `index.html`
   - `README.md`
3. Scroll down → in the **"Commit changes"** section, write:
   - `Add ACC lead generation tool`
4. Click **"Commit changes"**

---

### Step 4 — Enable GitHub Pages (Makes It Live)
1. In your repository, click **"Settings"** (top tab)
2. In the left sidebar, click **"Pages"**
3. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 1–2 minutes
6. Refresh the page → you'll see:

   ✅ **"Your site is live at https://YOUR-USERNAME.github.io/acc-lead-tool/"**

---

### Step 5 — Update the Canonical URL in index.html
1. Open `index.html` in the repository
2. Click the **pencil icon** (Edit)
3. Find this line (line ~12):
   ```
   <link rel="canonical" href="https://YOUR-USERNAME.github.io/acc-lead-tool/"/>
   ```
4. Replace `YOUR-USERNAME` with your actual GitHub username
5. Click **"Commit changes"** → **"Commit directly to main"** → **"Commit changes"**

---

### Step 6 — Test Everything
Open your live URL and verify:

- [ ] Hero page loads correctly
- [ ] "Start Free Assessment" button starts the quiz
- [ ] All 10 questions work with Back/Next navigation
- [ ] After Q10, gate form appears asking Name, Mobile, Email
- [ ] After submitting details, report loads with score, skill bars, roadmap
- [ ] Both CTA cards (Course + Placement) open ACC website
- [ ] "Open Gmail & Book My Free Session" button opens Gmail with pre-filled email
- [ ] Press **Ctrl+L** → Lead dashboard opens showing submitted leads

---

## 📋 How to View Leads

Press **Ctrl + L** on the live tool page to open the internal lead dashboard.

Leads are stored in the **browser's localStorage** of the device viewing the tool.

> ⚠️ Important: Leads are stored per-browser. If someone fills the form on their phone, you won't see it on your laptop. To collect centrally, share only ONE device/browser for demo, or upgrade to a backend later.

---

## 🔗 Links Configured in the Tool

| Element | Destination |
|---|---|
| AI Course CTA button | https://analyticscareerconnect.com/ |
| Placement Program CTA button | https://analyticscareerconnect.com/ |
| Gmail counselling button | japdeep.data.acc@gmail.com (pre-filled) |

---

## 📣 How to Get Traffic (Share Strategy)

Once live, share the URL in:
1. **WhatsApp groups** — college groups, DA learning communities
2. **LinkedIn post** — "I built a free tool to check if you're DA job-ready"
3. **Quora answers** — answer "how to become data analyst India" with tool link
4. **Reddit** — r/developersIndia, r/learnprogramming
5. **Telegram groups** — data analytics, placement prep groups

---

## ⚙️ Tech Stack

- Pure HTML + CSS + Vanilla JavaScript
- No frameworks, no dependencies, no backend
- Hosted free on GitHub Pages
- Leads stored in browser localStorage (no database needed)

---

Built by **Japdeep Singh** · Analytics Career Connect Intern · 2026
