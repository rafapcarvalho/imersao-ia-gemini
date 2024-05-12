# Chatbot de Receitas

Este é um projeto de um chatbot que fornece receitas com base em perguntas feitas pelo usuário. O chatbot utiliza o modelo de linguagem de inteligência artificial Gemini 1.5 Pro da Google para gerar respostas e a biblioteca `docx` para extrair as páginas de documentos DOCX que contêm as receitas.

## Instalação

Para executar este projeto, é necessário instalar as dependências listadas no arquivo `requirements.txt`. Você pode fazer isso executando o seguinte comando:

```
pip install -r requirements.txt
```

Além disso, é necessário configurar a variável de ambiente `GOOGLE_API_KEY` com a chave de API do Google necessária para utilizar o modelo de linguagem da Google.

## Uso

Execute o script `chatbot.py` para iniciar o chatbot. O chatbot solicitará ao usuário que digite uma pergunta sobre uma receita. Com base na pergunta, o chatbot fornecerá uma resposta contendo informações sobre a receita solicitada, como título, página no documento e número de ingredientes.

Ao digitar `fim`, o chatbot será encerrado.

## Arquivos

- `chatbot.py`: Script principal do chatbot.
- `requirements.txt`: Arquivo contendo as dependências do projeto.
- `Receitas Diversas.docx`: Documento contendo diversas receitas.
- `Receitas Incriveis.docx`: Documento contendo receitas incríveis (para expansão futura).
- `README.md`: Este arquivo.

## Notas

- Certifique-se de ter configurado a variável de ambiente `GOOGLE_API_KEY` corretamente para que o chatbot funcione adequadamente.
- Os documentos `Receitas Diversas.docx` e `Receitas Incriveis.docx` devem estar presentes no mesmo diretório que o script `chatbot.py`.
- Este chatbot é um projeto simples e pode ser expandido com mais funcionalidades e inteligência artificial mais avançada no futuro.

---

Espero que isso te ajude a começar! Se precisar de mais alguma coisa, estou aqui para ajudar.
