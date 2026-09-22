# Academia Nepofit Performance — Site + App

Publicado automaticamente no **GitHub Pages** a cada `git push` (workflow em `.github/workflows/pages.yml`).

- 🌐 Site: `https://SEU-USUARIO.github.io/NOME-DO-REPO/`
- 📱 App do aluno: `https://SEU-USUARIO.github.io/NOME-DO-REPO/app/`

## Publicar (primeira vez)

```powershell
cd nepofit-publish
gh auth login          # só na primeira vez
gh repo create NOME-DO-REPO --public --source=. --push
```

Depois ative o Pages: **Settings → Pages → Source: GitHub Actions**.

## Atualizar depois

```powershell
git add -A; git commit -m "atualiza site"; git push
```

O deploy acontece sozinho em ~1 minuto.
