# Painel Financeiro — JG & Morgana

App de controle financeiro familiar hospedado via GitHub Pages.

## Como usar

1. Abra `index.html` no browser ou acesse via GitHub Pages
2. Na aba **Checklist**, cole o Gist ID e o token para sincronizar entre dispositivos

## Configurar sincronização (Checklist compartilhado)

### 1. Criar o Gist
- Acesse [gist.github.com](https://gist.github.com)
- Clique em **+** (novo gist)
- Nome do arquivo: `jg_fin.json`
- Conteúdo: `{}`
- Clique **Create secret gist**
- Copie o ID da URL: `gist.github.com/seu-usuario/**ESTE_É_O_ID**`

### 2. Criar o token
- Acesse github.com → **Settings** → **Developer settings**
- **Personal access tokens** → **Tokens (classic)** → **Generate new token**
- Marque apenas a permissão **gist**
- Gere e copie o token (começa com `ghp_`)

### 3. Configurar no app
- Na aba **Checklist**, cole o Gist ID e o token
- Clique **Salvar** — o checklist passa a sincronizar automaticamente
- A Morgana faz o mesmo no iPhone dela com os mesmos dados

## Hospedar no GitHub Pages

1. Crie um repositório no GitHub (pode ser privado)
2. Suba os arquivos (`index.html`, `README.md`)
3. Vá em **Settings → Pages**
4. Source: **Deploy from a branch** → branch `main` → pasta `/ (root)`
5. A URL do app será `https://seu-usuario.github.io/nome-do-repo`

## Adicionar à tela inicial (iPhone)

1. Abra a URL no Safari
2. Toque no ícone de compartilhar
3. **Adicionar à Tela de Início**
4. O app abre em tela cheia, sem barra do browser
