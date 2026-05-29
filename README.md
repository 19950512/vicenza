# Vicenza Residencial — Landing Page

Landing page de captação de leads do empreendimento **Vicenza Residencial** (Embraplan), em Osasco/SP.

## Estrutura
- `index.html` — página completa (HTML + CSS + JS em um arquivo)
- `images/` — renders do empreendimento e logo da Embraplan

## Rodar localmente
Abra o `index.html` no navegador, ou sirva a pasta:
```bash
npx serve .
```

## Formulário / CRM
O formulário envia os leads via POST para `https://vendas.gestorimob.com.br/api/public/contato`
(cabeçalho `x-api-key`). Garanta que o domínio de publicação esteja liberado por CORS no painel do Gestor Imob.

## Deploy
Compatível com GitHub Pages, Vercel, Netlify ou qualquer hospedagem estática.
Para GitHub Pages: Settings → Pages → Branch `main` / pasta `/ (root)`.

---
Imagens meramente ilustrativas. © Embraplan — Construção e Incorporação.
