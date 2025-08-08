# Publicando uma página com GitHub Pages

Este guia mostra como publicar um site estático (ou apenas uma página) usando **GitHub Pages**.

---

##  Pré-requisitos

- Conta no GitHub
- Repositório público (ou privado com plano compatível)

---

## Passo a Passo

### 1. Crie o repositório  
No GitHub, clique em **New repository**, defina o nome e, se desejar, marque **Initialize this repository with a README** :contentReference[oaicite:7]{index=7}.

### 2. Adicione sua página  
Inclua na raiz do repositório um arquivo `index.html`, `index.md` ou `README.md`, que servirá como entrada principal :contentReference[oaicite:8]{index=8}.

### 3. Configure a publicação  
Vá em **Settings → Pages** ou **Settings → Code and automation → Pages**, escolha a branch e, se aplicável, a pasta de origem, e salve :contentReference[oaicite:9]{index=9}.

### 4. Acesse seu site  
Após salvar, o GitHub gerará uma URL no formato `https://<usuário>.github.io/<repositório>` ou, no caso de repositório especial, apenas `https://<usuário>.github.io/<repositório>` :contentReference[oaicite:10]{index=10}.

- A publicação pode levar alguns segundos ou até minutos :contentReference[oaicite:11]{index=11}.

---

## Alternativas avançadas

Você também pode publicar usando:

- Um branch `gh-pages` dedicado :contentReference[oaicite:12]{index=12}.
- O pacote npm `gh-pages` (útil em projetos com `build`) :contentReference[oaicite:13]{index=13}.
- Fluxo automatizado com **GitHub Actions** para construir e publicar o site automaticamente em cada commit :contentReference[oaicite:14]{index=14}.

---

## Dicas finais

- Mantenha o arquivo `index.html` ou `README.md` atualizado, pois será a página inicial do site.
- Se quiser usar domínio próprio, configure no mesmo painel **Pages** em **Custom domain** :contentReference[oaicite:15]{index=15}.
- Para evitar problemas com o Jekyll, você pode adicionar um arquivo vazio `.nojekyll` :contentReference[oaicite:16]{index=16}.

---

### Exemplo resumido

1. Crie repositório  
2. Adicione `index.html` ou `README.md`  
3. Vá em **Settings > Pages**, selecione a branch/folder e salve  
4. Acesse a URL publicada  

---  
Feito por [Pedro Maciel]
