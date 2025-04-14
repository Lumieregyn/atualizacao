## Agente de Atualização de Estoque na Nuvem

### ✅ Como usar:
1. Faça upload da planilha de estoque (extraída do PDF)
2. Faça upload da planilha de produtos
3. Clique em "Atualizar Estoque"
4. O sistema aplicará as regras:
   - Ignora prefixo "PEDIDO"
   - Só atualiza se "Dias para preparação" ≠ 0 ou 2
5. Você receberá a planilha pronta para download!

### 🚀 Como hospedar no Render:
1. Crie um repositório no GitHub com esses arquivos
2. Acesse https://render.com e clique em "New Web Service"
3. Conecte seu GitHub e selecione o repositório
4. Configure:
   - **Environment:** Python 3
   - **Build command:** pip install -r requirements.txt
   - **Start command:** uvicorn main:app --host 0.0.0.0 --port 10000
5. Clique em "Deploy"

Pronto! Sua aplicação estará no ar 🎉