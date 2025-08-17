# Site da Personal Trainer - Nicole Suzin

Este pacote contém o arquivo `index.html` pronto para publicar no **GitHub Pages**.

## Publicar no GitHub Pages (passo a passo)

1. Acesse https://github.com/new e crie um repositório (ex.: `site-nicole`).
2. Envie estes arquivos para o repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. No GitHub, vá em **Settings → Pages**:
   - **Source**: *Deploy from a branch*
   - **Branch**: *main* e */(root)*
   - Clique em **Save**
4. O site ficará disponível em:
   - `https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/`

> Dica: se quiser abrir diretamente em `https://SEU_USUARIO.github.io/`, crie o repositório com este nome exato.

## Publicar via Git (opcional)

```bash
git init
git add index.html .nojekyll README.md
git commit -m "Publicar site Nicole Suzin"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
git push -u origin main
```

Gerado em 2025-08-17 17:02:22.
