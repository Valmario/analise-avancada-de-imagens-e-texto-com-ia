# Análise Avançada de Imagens e Texto com IA na AWS

## Introdução
Este repositório documenta os aprendizados do curso Análise Avançada de Imagens e Texto com Inteligência Artificial na AWS. Durante o curso, explorei a integração de serviços da AWS para realizar análises complexas, como reconhecimento de imagens e processamento de linguagem natural, utilizando Amazon Textract e Amazon Rekognition.

## OCR CNH
Utilizando Amazon Textract, foi possível extrair textos de uma imagem da CNH.
Print e código Python:

### 1. Imagem original da CNH
![Imagem da CNH](https://github.com/karinfaraujo/AWS-Textract/blob/main/cnh.png?raw=true)

### 2. Resultado do OCR extraído da CNH
![Resultado do OCR](ocr_cnh)

## OCR Lista Escolar
A aplicação de OCR foi testada em uma lista escolar para extração automática de itens.
Print e código Python do OCR e como ele foi aplicado à lista escolar:

### 1. Imagem original da lista escolar
![Imagem da Lista Escolar](https://github.com/karinfaraujo/AWS-Textract/blob/main/lista-material-escolar.jpeg?raw=true)

### 2. Resultado do OCR extraído da lista escolar
![Resultado do OCR Lista](ocr_lista_escolar)

## Reconhecimento de Atacantes
Testei Amazon Rekognition para reconhecimento de celebridades em diferentes imagens.
Aqui estão os resultados do reconhecimento de atacantes:

### 1. Atacante 1 Identificado
![Atacante 1](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/bale.jpg?raw=true)

### 2. Atacante 2 Identificado
![Atacante 2](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/cr7.jpg?raw=true)

### 3. Atacante 3 Identificado
![Atacante 3](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/messi.jpg?raw=true)

### 4. Atacante 4 Identificado
![Atacante 4](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/neymar.jpg?raw=true)

### 5. Resultado 5 Atacante Identificado
![Atacante 5](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/resultado_bbc.jpg?raw=true)

### 6. Resultado 6 Atacante Identificado
![Atacante 6](https://github.com/karinfaraujo/AWS-Textract.Rekognition/blob/main/reconhecimento_atacantes/resultado_msn.jpg?raw=true)

### 7. Código Python
![Código Python](reconhecimento_atacantes/pythoncode)

## Reconhecimento de Celebridades
O modelo foi aplicado para reconhecer celebridades em imagens:

### 1. Imagem de Celebridade
![Imagem de Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/bbc.jpg?raw=true)

### 2. Imagem de Celebridade
![Imagem de Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/msn.jpg?raw=true)

### 3. Imagem de Celebridade
![Imagem de Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/neymar-torcedores.jpg?raw=true)

### 4. Resultado do Reconhecimento da Celebridade 1
![Resultado Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/bbc-resultado.jpg?raw=true)

### 5. Resultado do Reconhecimento da Celebridade 2
![Resultado Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/msn-resultado.jpg?raw=true)

### 6. Resultado do Reconhecimento da Celebridade 3
![Resultado Celebridade](https://github.com/karinfaraujo/AWS-Textract/blob/main/reconhecimento_celebridades/neymar-torcedores-resultado.jpg?raw=true)

### 7. Código Python
![Código Python](reconhecimento_celebridades/pythoncode)

## Insights
- Amazon Rekognition permite análise de imagens de forma escalável e eficiente.
- Amazon Textract facilita a extração de texto de documentos escaneados, abrindo possibilidades de automação.
- As soluções da AWS oferecem alto desempenho para tarefas de IA e visão computacional.

## Possibilidades
Com os conhecimentos adquiridos, é possível aplicar essas tecnologias para:
- Automatização documental: extração e interpretação de documentos com OCR.
- Segurança e monitoramento: reconhecimento facial para controle de acesso.
- E-commerce: classificação automática de produtos via reconhecimento de imagens.

## Conclusão
Este repositório documenta experiências práticas com Amazon Textract e Amazon Rekognition, demonstrando como a IA pode ser utilizada para soluções avançadas de análise de imagens e texto na AWS.
