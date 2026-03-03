# Fix: Can't push to GitHub

## Cause
GitHub returns **"Repository not found"** because the repository  
`https://github.com/momentsbyraya/cheche-and-rayvin-wedding` **does not exist yet** (or this account doesn’t have access).

## Fix (do this once)

### 1. Create the repo on GitHub
- Open: **https://github.com/new?name=cheche-and-rayvin-wedding**
- Owner: **momentsbyraya**
- Repository name: **cheche-and-rayvin-wedding**
- Leave **"Add a README file"** unchecked (you already have local commits).
- Click **Create repository**.

### 2. Push from your project folder
In PowerShell, from this project folder run:

```powershell
git push -u origin main
```

Use **`-u origin main`** (with a space), not `-origin main`.

---

After the repo exists on GitHub, the push should succeed. You can delete this file once you’ve pushed.
