# Francês com Desy — Landing page e quiz

Site estático em HTML, CSS e JS. Não exige Node.js, dependências ou `server.mjs`.

## Publicação no GitHub + Render (recomendado)
1. Crie um repositório GitHub chamado `frances-com-desy`.
2. Faça upload **dos arquivos desta pasta** para a raiz do repositório: `index.html`, `render.yaml`, `.nojekyll`, `README.md`.
3. Em https://dashboard.render.com, escolha **New > Static Site** e conecte o repositório.
4. Se criar como Static Site manual, use:
   - **Branch**: `main` (ou sua branch padrão)
   - **Build Command**: `echo "Site estatico pronto para publicar"`
   - **Publish Directory**: `.`
5. Publique e abra a URL gerada pelo Render (endereço `*.onrender.com`).

Se optar por **Blueprint** no Render em vez de Static Site manual, o arquivo `render.yaml` já configura o site. Escolha **New > Blueprint**, conecte o mesmo repositório e revise os dados antes de aplicar. Não crie dois serviços ao mesmo tempo (manual e Blueprint).

## Alternativa sem Render: GitHub Pages
1. Com os arquivos na raiz do repositório, abra **Settings > Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha `main` e `/ (root)` e salve.
4. A URL será parecida com `https://SEU_USUARIO.github.io/frances-com-desy/`.

## Recursos do site
- Cinco perguntas do quiz, recomendação orientativa A1/A2, exibição de horários.
- Mensagem personalizada para WhatsApp **+55 71 98807-0059** (o visitante precisa tocar em Enviar).
- Fotos do professor incorporadas ao HTML.
- Imagens externas de Paris via Unsplash; precisam de internet e podem falhar caso o provedor bloqueie.

## Importante antes de divulgar
- Revise textos, valores, política de certificado, datas e disponibilidade de vagas.
- A versão estática **não salva respostas em banco de dados**. Elas chegam somente se o visitante confirmar o envio no WhatsApp.
- Teste com celular Android e iPhone após a publicação.
- Para registrar leads automaticamente e obter métricas, será necessária uma integração ou backend.
- A URL `frances-com-desy.onrender.com` é ilustrativa e só existirá se estiver disponível e o deploy for realizado.
