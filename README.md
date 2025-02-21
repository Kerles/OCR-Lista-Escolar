<p align="center">
<a href="https://en.wikipedia.org/wiki/Artificial_intelligence"><img src="https://img.shields.io/badge/AI-Project-FED564?logo=openai" alt="AI - Project"></a>
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=vimeo" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Vá para a página inicial do Bash"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Feito com Bash"></a>
 <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Code-Project-FED564?logo=Python " alt="Python - Project"></a>

# Transcrevendo uma Imagem em Texto com AWS Textract

Este projeto demonstra a utilização do AWS Textract para a extração de texto de uma imagem de uma lista escolar. O objetivo é mostrar como o AWS Textract pode ser utilizado para transcrever informações de documentos de forma eficiente.

## Objetivo

O projeto visa exemplificar o uso do AWS Textract na extração de texto de imagens simples, destacando a facilidade e a eficácia do serviço em processar documentos.

Estrutura do Projeto
```
OCR-Lista-Escolar/
│
├── input/          
│   └── Lista-de-Material.png
│
├── output/         
│   └── terminal.md
│ 
└── scripts/        
    └── extract_text.py
```

## Imagem Utilizada

Abaixo está a imagem da lista escolar que foi utilizada para a extração de texto:

![Lista Escolar](../input/Lista-de-Material.png)

## Código Python

O código Python utilizado para realizar a extração de texto da imagem está em `output`.

## Resultado da Extração

Após a execução do AWS Textract, o texto extraído da imagem foi salvo no arquivo `terminal.md`. O conteúdo do arquivo é o seguinte:

Resultado no Terminal
Após a execução do código, o resultado no terminal foi:
```
Texto extraído:
Lista de Material

Quantidade:

- Até 01 (unidade) - Colar

- Até 04 (unidades) - Brinquedo

- Até 02 (unidades) - Pasta suspensa

- Até 04 (unidades) - Pincéis para pintura
- Até 01 (unidade) - Envelopes

- Até 02 (unidades) - Algodao

- Até 02 (unidades) - Colas Coloridas

- Até 01 (unidade) - Colas de Isopor

- Até 01 (unidade) - Fita Decorativa

- Até 01 (unidade) - Fitilho

- Até 02 (unidades) - Folhas de cartolina
- Até 01 (unidade) - Folhas de isopor

- Até 03 (unidades) - Livro infantil

- Até 02 (resmas) - Massa para modelar
- Até 01 (unidade) - Papel A4 ou Similar
- Até 04 (unidades) - Palito de Picolé

- Até 01 (rolo pequeno) - Tubos de Tintas
- Barbante

www.ieducacao.com


```
## Conclusão
Este projeto demonstrou como o AWS Textract pode ser utilizado para transcrever informações de uma imagem de forma eficiente. A experiência adquirida ao trabalhar com este serviço pode ser aplicada em diversos contextos, desde a automação de tarefas até a análise de dados.
