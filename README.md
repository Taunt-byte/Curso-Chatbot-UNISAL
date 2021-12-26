<p align="center">
  <a href="https://unform.dev">
    <img src="img/Logo.png" height="150" width="175" alt="Unform" />
  </a>
</p>
<h1 align="center">Criando e Treinando um Chatbot utilizando técnicas de Machine Learning e Python </h1> 

<p align="center">É um mini curso feito pela UNISAL realizado na semana da computação</p>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Instalação](#Instalação)
   * [Como usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
   * [Tecnologias](#tecnologias)
<!--te-->

<h4 align="center"> 
  🚧  Em desenvolvimento.  🚧
</h4>

## Sobre

É um mini curso feito pela UNISAL realizado na semana da computação
    + A trilha escolhida foi a 3ª

1) Inicialmente, no primeiro dia serão apresentados os fundamentos de Machine Learning e preparado o ambiente de desenvolvimento – também será apresentado um pequeno exemplo. 

2) No segundo dia, serão apresentados os conceitos de Processamento de Linguagem Natural (PLN) e iniciada a preparação do Chatbot, usando biblioteca Chatterbot. 

3) No terceiro e último dia será treinado o Chatbot e implementada a interface para interação usando TKinter.

## Tabela de conteudo

- [x] Primeiro dia
- [x] Segundo dia
- [ ] Terceiro dia

## Instalação

Falar como instalar o programa na maquina
Falar tambem como deve ser instalado bibliotecas ou arquivos adicionais

## Como usar

ABRIR O VISUAL STUDIO CODE COMO ADMINISTRADOR.



Executar este comando no vscode para criar a pasta do ambiente virtual:



python -m venv bot-env



Executar este comando para inicializar o ambiente virtual:



.\bot-env\Scripts\activate.ps1



Caso o comando acima apresente algum erro , executar no windows power shell o seguinte comando:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
Digitar S e fechar o windows power shell.



Executar novamente o comando que ativa o ambiente virtual:
.\bot-env\Scripts\activate.ps1




## Criar arquivo de requirements



requirements.txt



ChatterBot==1.0.8
spacy==2.3.2
SQLAlchemy==1.3.17
ChatterBot-corpus



## Instalar o arquivo de requirements:



pip install -r requirements.txt



## Baixar pacotes auxiliares

python -m spacy download en_core_web_lg
python -m spacy download en_core_web_sm
python -m spacy download en

## Pre Requisitos

Falar sobre o que precisa para rodar o programa e como

## Tecnologias

<table>
    <tr>
    <td>Python</td>
    </tr>
    <tr>
    <td>3.7.8</td>
    </tr>
</table>