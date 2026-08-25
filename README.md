# G.P Films — Plataforma completa (MVP)

**G.P Films — By Grigor Pinheiro | Filmmaker & Fotografia**

Inclui interface premium responsiva, catálogo de eventos, galeria, carrinho, checkout, fluxo Pix de demonstração, página de downloads e painel do fotógrafo com criação de eventos e upload de fotos/vídeos.

## Rodar localmente
1. Instale Node.js 20+.
2. No terminal, entre nesta pasta.
3. `npm install`
4. Copie `.env.example` para `.env` e ajuste as variáveis.
5. `npm start`
6. Abra `http://localhost:3000`.

## Importante para produção
O Pix desta versão está em modo de demonstração. Para cobrar dinheiro real e liberar arquivos automaticamente, conecte um provedor Pix (Mercado Pago, Asaas, Stripe etc.), configure webhook assinado, banco de dados, armazenamento privado (S3/R2), URLs de download temporárias e autenticação real. O servidor já deixa pontos de integração separados em `/api/orders` e `/api/orders/:id/approve`.

Login do protótipo anterior: `admin@gpfilms.com` / `123456`.
