---
weight: 100
date: "2023-05-03T22:37:22+01:00"
draft: false
author: "Joao Martins"
title: "Deployment"
icon: "rocket_launch"
toc: true
description: "A guide to deploy a Hugo Website"
publishdate: "2023-05-03T22:37:22+01:00"
tags: ["Beginners"]
---

# Deploy de um site Hugo com Netlify

Este guia irá ajudá-lo a publicar o seu site Hugo usando o Netlify, uma plataforma para hospedar sites estáticos.

## Antes de começar

Certifique-se de que você tem:

- Um projeto de site Hugo pronto.
- Uma conta registrada no Netlify.
- O Hugo instalado em seu computador.

## Passos

### 1. Registrar-se no Netlify

Se ainda não o fez, crie uma conta no Netlify. É rápido e gratuito.

### 2. Adicionar seu site ao Netlify

Acesse a página "Sites" do Netlify e clique em "Novo site a partir do Git".

Pode aceder à documentação do [Netlify Docs](https://docs.netlify.com/get-started/).

### 3. Conectar seu repositório

Escolha o seu provedor Git (como o GitHub). O Netlify irá guiá-lo através da conexão do seu repositório.

### 4. Configurar as configurações de construção

O Netlify detecta automaticamente o seu site Hugo. Verifique as configurações de construção e ajuste-as, se necessário.

### 5. Publicar seu site

Opção 1: Clique em "Publicar site". O Netlify começará a criar o seu site Hugo.
Opção 2: Acesse a pasta que contém o seu site Hugo. Instale o Netlify com:
```shell
npm install -g netlify-cli
```
Após a instalação, digite: 
```shell 
netlify deploy prod
```
e siga as instruções.

### 6. Acesse seu site

Após a conclusão da construção, o Netlify fornecerá uma URL para visualizar o seu site.

## Conclusão

Você deu Deploy com sucesso ao seu site Hugo com o Netlify! Explore os recursos adicionais do Netlify para aprimorar ainda mais seu site.