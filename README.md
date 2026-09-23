# Quiz — Inglês Técnico (Programação & Segurança)

Aplicativo web estático para brasileiros treinarem **inglês técnico** de programação, deploy e segurança (Auto-review, conectores MCP, OAuth, Git/Vercel).

## Como usar

Abra `index.html` no navegador ou acesse: https://quiz-ingles-tecnico.vercel.app

- Interface em **português**; termos em **inglês**
- Áudio via **Web Speech API** (`speechSynthesis`) — sem backend
- Progresso em **localStorage**
- Modo **só os errados** + **glossário A–Z**

## Blocos

1. **Auto-review** (8) — Auto-approved, User approval card, Standing permission, Blocked
2. **Conectores** (12) — Deploy, Vercel, GitHub, Notion, Firebase, Gmail, Calendar, Canva, Gamma
3. **Segurança** (10) — Token, OAuth, Scope, Revocation, permissões, senha no browser do bot
4. **Termos extras** (8) — Repository, Commit, Branch, Pull request, Webhook, Rate limit, etc.

**Total: 38 perguntas**

## Estrutura

```
index.html      — UI
styles.css      — layout mobile-first
data-part1.js   — blocos + perguntas (parte 1)
data-part2.js   — perguntas (parte 2) + montagem de QUIZ_DATA
data.js         — fonte completa (desenvolvimento local)
app.js          — lógica, áudio, localStorage
```

Sem framework e sem build. Push em `main` dispara deploy na Vercel.

## Desenvolvimento local

```bash
npx serve .
```

## Licença

Uso livre para estudo.
