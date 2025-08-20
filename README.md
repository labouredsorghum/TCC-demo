# TCC — Protótipos (GitHub Pages)
Data: 2025-08-20T17:14:44

## Como publicar (GitHub Pages)
1. Cria um repositório no GitHub, por ex.: `tcc-prototipo`.
2. Faz upload destes ficheiros para a **branch `main`**, na raiz.
3. No repositório: *Settings* → *Pages* → **Build and deployment** → *Source*: `Deploy from a branch` → *Branch*: `main` / `/ (root)`.
4. Aguarda o deploy e abre o link que o GitHub mostra (ex.: `https://teu-user.github.io/tcc-prototipo/`).

## Como instalar como app
- **Android (Chrome)**: abre o link → Menu ⋮ → *Adicionar ao ecrã principal* → OK.
- **iOS/iPadOS (Safari)**: abre o link → Partilhar → *Adicionar ao ecrã principal*.

## Ficheiros principais
- `driver.html` — app do motorista (login demo, tarefas, envio simulado de CMR).
- `dashboard.html` — dashboard do escritório (gerar cargas internacionais, simular uploads).
- `manifest.webmanifest` + `service-worker.js` — suporte PWA básico (offline/cache) no Android.

> Nota: isto é um protótipo estático (sem backend). No produto final ligaríamos ao Supabase/Firebase.
