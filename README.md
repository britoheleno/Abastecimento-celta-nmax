# Abastecimento Seguro — Celta e NMAX

Aplicativo estático preparado para GitHub Pages.

## Arquivos
- `index.html` — aplicativo principal
- `manifest.json` — configuração PWA
- `sw.js` — funcionamento offline/cache
- `icon.svg` — ícone do aplicativo
- `.nojekyll` — evita processamento do GitHub Pages

## Publicação rápida pelo celular

1. Entre em https://github.com e faça login.
2. Toque em **+** > **New repository**.
3. Nome sugerido: `abastecimento-celta-nmax`
4. Deixe o repositório como **Public**.
5. Toque em **Create repository**.
6. No repositório, use **Add file** > **Upload files**.
7. Envie TODOS os arquivos desta pasta:
   - index.html
   - manifest.json
   - sw.js
   - icon.svg
   - .nojekyll
8. Role até o final e toque em **Commit changes**.
9. Abra **Settings** do repositório.
10. Entre em **Pages**.
11. Em **Build and deployment**, escolha:
    - Source: **Deploy from a branch**
    - Branch: **main**
    - Folder: **/(root)**
12. Toque em **Save**.
13. Aguarde alguns minutos.
14. O GitHub mostrará o endereço publicado.

O endereço costuma ficar assim:

`https://SEU-USUARIO.github.io/abastecimento-celta-nmax/`

## Instalar no Android

1. Abra o endereço publicado no Chrome ou Samsung Internet.
2. Abra o menu do navegador.
3. Toque em **Instalar app** ou **Adicionar à tela inicial**.
4. Depois, abra sempre pelo ícone criado.

## Importante sobre os dados

Os dados dos abastecimentos permanecem salvos no navegador/aparelho.
Publicar no GitHub Pages NÃO envia seus abastecimentos para o GitHub.

Faça backup pelo botão **Fazer backup agora** dentro do aplicativo, principalmente:
- antes de trocar de celular;
- antes de limpar dados do navegador;
- antes de reinstalar o navegador;
- periodicamente.

## Atualizar o aplicativo no futuro

Se receber uma nova versão:
1. Faça backup JSON dentro do app.
2. No GitHub, abra o repositório.
3. Substitua os arquivos do aplicativo.
4. Faça o commit.
5. Aguarde o GitHub Pages atualizar.
6. Abra o app e restaure o backup apenas se necessário.
