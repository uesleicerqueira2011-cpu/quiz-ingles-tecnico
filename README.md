# Quiz — Inglês Técnico (Programação & Segurança)

Aplicativo web estático para brasileiros treinarem **inglês técnico** de programação, deploy e segurança (Auto-review, conectores MCP, OAuth, Git/Vercel).

## Como usar

Abra `index.html` no navegador ou acesse o deploy na Vercel.

- Interface em **português**; termos em **inglês**
- Áudio via **Web Speech API** (`speechSynthesis`) — sem backend
- Progresso em **localStorage**
- Modo **só os errados** + **glossário A–Z**

## Blocos

1. **Auto-review** — Auto-approved, User approval card, Standing permission, Blocked
2. **Conectores** — Deploy, Vercel, GitHub, Notion, Firebase, Gmail, Calendar, Canva, Gamma
3. **Segurança** — Token, OAuth, Scope, Revocation, permissões, senha no browser do bot
4. **Termos extras** — Repository, Commit, Branch, Pull request, Webhook, Rate limit, etc.

## Estrutura

```
index.html   — UI
styles.css   — layout mobile-first
data.js      — perguntas e glossário
app.js       — lógica, áudio, localStorage
```

Sem framework e sem build.

## Desenvolvimento local

Qualquer servidor estático, por exemplo:

```bash
npx serve .
```

## Licença

Uso livre para estudo.
