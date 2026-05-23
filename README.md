# Zap Finance

Assistente financeiro via WhatsApp para registrar entradas, despesas, metas e lembretes com apoio de IA.

## Visão geral

O Zap Finance é um projeto experimental de um assistente financeiro conversacional. A proposta é permitir que uma pessoa registre sua vida financeira diretamente pelo WhatsApp, sem precisar abrir um aplicativo no início.

A ideia central é usar o WhatsApp como interface principal, IA para interpretar mensagens e documentos, e um banco de dados para organizar entradas, saídas, categorias, metas e lembretes.

## Objetivo do MVP

Validar um fluxo simples onde o usuário consegue:

- Enviar uma mensagem pelo WhatsApp informando uma despesa ou entrada.
- A IA interpreta valor, data, descrição e categoria.
- O sistema pede confirmação.
- O lançamento é salvo em um banco de dados.
- O usuário consegue visualizar os lançamentos em um painel simples.

## Exemplo de uso

Usuário:

> Gastei R$ 42,90 no almoço hoje.

Assistente:

> Entendi: saída de R$ 42,90, categoria Alimentação, descrição Almoço, data de hoje. Confirma?

Usuário:

> Confirma.

Assistente:

> Lançamento registrado com sucesso.

## Funcionalidades previstas

### MVP inicial

- Cadastro de usuário pelo número de WhatsApp.
- Registro de entradas e saídas por texto.
- Classificação básica por categoria.
- Confirmação do lançamento antes de salvar.
- Armazenamento em PostgreSQL.
- Painel simples para consulta dos lançamentos.

### Próximas fases

- Metas mensais por categoria.
- Lembretes de contas a pagar.
- Leitura de notas fiscais e comprovantes com IA.
- Importação de faturas de cartão.
- Identificação de cartão pelos últimos 4 dígitos.
- Cadastro de estabelecimentos com nome fantasia.
- Controle de gastos referentes a outras pessoas.
- Possibilidade futura de contas compartilhadas.
- Análises financeiras conversacionais com IA.

## Stack planejada

- WhatsApp / Evolution API
- n8n
- Gemini API
- PostgreSQL
- Appsmith
- Coolify

## Status

Projeto em fase de planejamento e prototipação inicial.

## Roadmap resumido

1. Planejamento e documentação.
2. Infraestrutura isolada.
3. Banco de dados inicial.
4. Recebimento de mensagens pelo WhatsApp.
5. Extração de dados com IA.
6. Confirmação e gravação de lançamentos.
7. Painel simples.
8. Metas, lembretes e leitura de documentos.

## Observação

Este repositório público documenta a visão, arquitetura e evolução do projeto. A implementação real, credenciais, workflows e dados sensíveis devem permanecer em ambiente privado.
