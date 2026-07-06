# Deploy to GitHub Pages

## One-time setup (2 minutes)

### 1. Create the GitHub repository

1. Go to **https://github.com/new**
2. Repository name: `MCCall-NEMT-`
3. Visibility: **Public**
4. **Do NOT** check "Add a README"
5. Click **Create repository**

### 2. Push the code

```powershell
cd "C:\Leads\NEMT Website"
git push -u origin main
```

Sign in with GitHub if prompted.

### 3. Enable GitHub Pages

1. Open **https://github.com/zoruhammah-cmyk/MCCall-NEMT-/settings/pages**
2. Under **Build and deployment** → **Source**: select **GitHub Actions**
3. Save (no other settings needed)

### 4. Wait for deploy (~2 min)

1. Go to **https://github.com/zoruhammah-cmyk/MCCall-NEMT-/actions**
2. Wait for the green checkmark on "Deploy to GitHub Pages"

## Live URL

**https://zoruhammah-cmyk.github.io/MCCall-NEMT-/**

## Local development

```powershell
npm run dev
```

Local dev runs without the `/mccall-ambulance` base path. Production build uses it automatically via GitHub Actions.