# Azure AI Vision Lab

## Processo

Observação: baseado no roteiro https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html

* Criar um resource **Azure AI services**
* Acessar o [**Vision Studio**](https://portal.vision.cognitive.azure.com)
* Selecionar a resource criada como padrão
* Acesse **Getting started with Vision**, selecione **Optical character recognition** e depois em **Extract text from images**
* Lembre de marcar a caixa de seleção para concordar com os termos
* Suba a imagem desejada e veja o resultado

## Considerações
* O jeito que Vision "lê" a imagem parece ser da esquerda para direita em linhas, não tendo o contexto de uma quebra de linha não sequencial (exemplo livro)
* O Vision conseguiu ler mesmo uma letra não muito bem escrita e ignorar um desenho (exemplo desenho)
