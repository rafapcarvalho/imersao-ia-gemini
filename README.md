# Chatbot de Receitas

Este é um projeto de um chatbot que fornece receitas com base em perguntas feitas pelo usuário. O chatbot utiliza o modelo de linguagem de inteligência artificial Gemini 1.5 Pro da Google para gerar respostas e a biblioteca `docx` para extrair as páginas de documentos DOCX que contêm as receitas.

## Uso

Execute o script no google colab para iniciar o chatbot. O chatbot solicitará ao usuário que digite uma pergunta sobre uma receita. Com base na pergunta, o chatbot fornecerá uma resposta contendo informações sobre a receita solicitada, como título, página no documento e número de ingredientes.

Ao digitar `fim`, o chatbot será encerrado.

## Arquivos

- `chatBot_withDocuments.ipynb`: Script principal do chatbot.
- `Receitas Diversas.docx`: Documento contendo diversas receitas.
- `Receitas Incriveis.docx`: Documento contendo receitas incríveis (para expansão futura).
- `README.md`: Este arquivo.

## Notas

- Certifique-se de ter configurado a variável de ambiente `GOOGLE_API_KEY` corretamente para que o chatbot funcione adequadamente.
- Os documentos `Receitas Diversas.docx` e `Receitas Incriveis.docx` devem estar presentes no mesmo diretório que o script `chatBot_withDocuments.ipynb`.
- Este chatbot é um projeto simples e pode ser expandido com mais funcionalidades e inteligência artificial mais avançada no futuro.


