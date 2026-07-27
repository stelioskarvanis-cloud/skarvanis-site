# Skarvanis — Site institucional

Site institucional da Skarvanis (Gestão Contábil e Financeira), publicado via GitHub Pages.

## Como publicar

1. Vá em **Settings → Pages** neste repositório
2. Em "Source", selecione a branch `main` e a pasta `/root`
3. Salve. Em alguns minutos o site fica disponível em:
   `https://<seu-usuario>.github.io/<nome-do-repositorio>/`

## Como atualizar o site

Sempre que quiser publicar uma nova versão:

1. Substitua o arquivo `index.html` pela versão atualizada
2. Faça commit e push para a branch `main`
3. O GitHub Pages atualiza automaticamente em 1–2 minutos

## Domínio próprio (opcional)

Se quiser usar `skarvanis.com.br` em vez do link do GitHub:

1. Crie um arquivo chamado `CNAME` (sem extensão) na raiz do repositório, contendo apenas:
   ```
   skarvanis.com.br
   ```
2. No painel do seu domínio (ex: registro.br), aponte os registros DNS para o GitHub Pages:
   - Registro tipo `A` apontando para: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Ou um registro `CNAME` apontando para `<seu-usuario>.github.io`
3. Em Settings → Pages, adicione `skarvanis.com.br` no campo de domínio customizado
