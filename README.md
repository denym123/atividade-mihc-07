# Design centrado no humano — IHC, Aula 03

Site estático (HTML/CSS puro) respondendo às 6 perguntas da atividade sobre design centrado no humano, com base na videoaula "Interfaces Humano-Computador — Aula 03".

## Estrutura
```
index.html
style.css
assets/
  foto-denym-andrade.svg   ← placeholder, trocar pela foto real
  foto-denym-filho.svg     ← placeholder, trocar pela foto real
  foto-lorena-silva.svg    ← placeholder, trocar pela foto real
```

**Antes de entregar:** troque os 3 arquivos SVG em `assets/` pelas fotos reais dos integrantes (pode ser `.jpg`/`.png` — só ajustar o `src` de cada `<img>` no `index.html`).

## Publicar no GitHub
```bash
git init
git add .
git commit -m "Atividade IHC: design centrado no humano"
git branch -M main
git remote add origin https://github.com/<seu-usuario>/<nome-do-repo>.git
git push -u origin main
```

## Publicar no Netlify
1. Acesse [app.netlify.com](https://app.netlify.com) e faça login com a conta do GitHub.
2. "Add new site" → "Import an existing project" → escolha o repositório.
3. Build command: deixe em branco. Publish directory: `.` (raiz).
4. Deploy. O link público gerado é o que deve ser entregue, junto com o link do repositório GitHub.
