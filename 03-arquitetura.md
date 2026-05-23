# Arquitetura planejada

## Visão geral

O Zap Finance será estruturado inicialmente como um assistente financeiro via WhatsApp, usando automações para receber mensagens, IA para interpretação e banco de dados para armazenamento.

## Fluxo do MVP

```text
WhatsApp
↓
Evolution API
↓
n8n
↓
Gemini API
↓
PostgreSQL
↓
Appsmith
