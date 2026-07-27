# PersonaFolio — Privacy Policy

Standalone public site for the **PersonaFolio** privacy policy (for Google Play / App Store listings).

## Public URL (after GitHub Pages is enabled)

`https://mbfarhanm1998.github.io/personafolio-privacy/`

## Before you publish

1. Open `index.html` and `PRIVACY_POLICY.md`
2. Replace `[REPLACE_WITH_YOUR_EMAIL]` with your real support email
3. Follow the setup steps below

## Setup steps

### 1. Create a new GitHub repository

1. Go to [https://github.com/new](https://github.com/new)
2. **Repository name:** `personafolio-privacy`
3. Set visibility to **Public**
4. Do **not** add a README, `.gitignore`, or license (this folder already has files)
5. Click **Create repository**

### 2. Push this folder to GitHub

Open Terminal and run:

```bash
cd ~/Desktop/personafolio-privacy
git init
git add .
git commit -m "$(cat <<'EOM'
Add PersonaFolio privacy policy site.

EOM
)"
git branch -M main
git remote add origin https://github.com/mbfarhanm1998/personafolio-privacy.git
git push -u origin main
```

Sign in to GitHub if prompted.

### 3. Enable GitHub Pages

1. Open the repo: `https://github.com/mbfarhanm1998/personafolio-privacy`
2. Go to **Settings → Pages**
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes, then open:

`https://mbfarhanm1998.github.io/personafolio-privacy/`

### 4. Use the link in Google Play

In Play Console → your app → **App content → Privacy policy**, paste:

`https://mbfarhanm1998.github.io/personafolio-privacy/`

## Files

| File | Purpose |
|------|---------|
| `index.html` | Live privacy policy page (GitHub Pages) |
| `PRIVACY_POLICY.md` | Same policy in markdown |
