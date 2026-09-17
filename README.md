# XMR Stack

Primeira versão do **XMR Stack** — dashboard para acompanhar posições em Monero.

## Estrutura

- `index.html` — aplicação principal.
- `assets/icon-*.png` — ícone do aplicativo, usando a arte com o nome **XMR STACK DASHBOARD**.
- `assets/logo.jpg` — logo interna do aplicativo, sem o nome.
- `manifest.webmanifest` — configuração para instalação como PWA.
- `sw.js` — service worker para cache do app shell.

## GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Em **Settings → Pages**, habilite o deploy a partir da branch principal e da pasta `/ (root)`.
4. Abra o endereço publicado em HTTPS.

O app continua usando as APIs externas já presentes no projeto para dados de mercado. Os dados locais do usuário continuam sendo armazenados pelo navegador conforme a implementação atual.

## Versão

`1.0.0`
