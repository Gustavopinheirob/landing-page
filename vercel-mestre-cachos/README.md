# Kit Soltura Magia dos Cachos — Landing Page

Página de vendas estática, 100% autônoma. Todas as imagens e fontes já estão embutidas no `index.html`, então **não precisa de build, nem de servidor, nem de configuração**.

## Conteúdo
- `index.html` — a página completa (é só isso que a Vercel precisa)
- `vercel.json` — configuração mínima (opcional)

## Como publicar na Vercel

### Opção A — Arrastar e soltar (mais fácil, sem instalar nada)
1. Acesse https://vercel.com e faça login.
2. Clique em **Add New… → Project** (ou vá em https://vercel.com/new).
3. Em vez de conectar um repositório, procure a área de **Deploy** por upload / arraste a **pasta** `vercel-mestre-cachos` inteira para a janela.
4. Confirme. Em segundos a Vercel te dá a URL pública (ex.: `https://seu-projeto.vercel.app`).

> Dica: se a Vercel pedir um "framework preset", escolha **Other** (é um site estático).

### Opção B — Pela linha de comando (Vercel CLI)
```bash
npm i -g vercel
cd vercel-mestre-cachos
vercel          # publica em uma URL de pré-visualização
vercel --prod   # publica em produção
```

### Opção C — Pelo GitHub
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: **Add New… → Project → Import** o repositório.
3. Framework preset: **Other**. Build command: deixe vazio. Output directory: deixe vazio (`.`).
4. Deploy.

## Domínio próprio
Depois de publicado: **Project → Settings → Domains → Add** e aponte seu domínio (ex.: `promo.mestredoscachos.com`).

## Editar depois
Abra o `index.html` em qualquer editor. O texto está tudo em português dentro do HTML. Para trocar uma imagem, procure por `src="data:image/jpeg;base64,...` — cada `<img>` corresponde a uma foto (hero, antes/depois e produto).

Os botões de compra apontam para:
`https://mestredoscachos.com/produtos/kit-soltura-magia-dos-cachos-mestre-dos-cachos-oficial/`
