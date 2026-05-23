# Roadmap do Zap Finance

## Fase 0 — Planejamento

- [ ] Criar repositório público.
- [ ] Escrever README inicial.
- [ ] Documentar visão geral.
- [ ] Documentar arquitetura planejada.
- [ ] Definir escopo fechado do MVP.
- [ ] Criar cards no GitHub Project.

## Fase 1 — Infraestrutura isolada

- [ ] Criar projeto separado no Coolify.
- [ ] Criar banco PostgreSQL separado.
- [ ] Avaliar n8n separado ou compartilhado.
- [ ] Avaliar Evolution API separada ou instância existente.
- [ ] Definir variáveis de ambiente.
- [ ] Definir estratégia de backup.

## Fase 2 — Banco de dados inicial

- [ ] Criar tabela de usuários.
- [ ] Criar tabela de categorias.
- [ ] Criar tabela de lançamentos.
- [ ] Criar tabela de logs de mensagens.
- [ ] Inserir categorias iniciais.
- [ ] Testar inserção manual.

## Fase 3 — WhatsApp e n8n

- [ ] Conectar número de WhatsApp.
- [ ] Configurar webhook da Evolution API para o n8n.
- [ ] Criar workflow para receber mensagens.
- [ ] Salvar mensagem bruta no banco.
- [ ] Responder mensagem de teste.

## Fase 4 — IA para interpretação

- [ ] Criar prompt de extração financeira.
- [ ] Conectar Gemini API.
- [ ] Transformar mensagem em JSON estruturado.
- [ ] Validar tipo, valor, data, descrição e categoria.
- [ ] Salvar lançamento como pendente.

## Fase 5 — Confirmação

- [ ] Enviar resumo do lançamento para confirmação.
- [ ] Criar fluxo de confirmação.
- [ ] Criar fluxo de cancelamento.
- [ ] Atualizar status do lançamento.
- [ ] Enviar mensagem de sucesso.

## Fase 6 — Painel

- [ ] Criar app simples no Appsmith.
- [ ] Conectar Appsmith ao PostgreSQL.
- [ ] Listar lançamentos.
- [ ] Filtrar por mês.
- [ ] Exibir total de entradas, saídas e saldo.
- [ ] Permitir edição manual.

## Fase 7 — Próximas funcionalidades

- [ ] Metas mensais.
- [ ] Lembretes de contas.
- [ ] Leitura de notas e comprovantes.
- [ ] Faturas de cartão.
- [ ] Cartões cadastrados.
- [ ] Nome fantasia de estabelecimentos.
- [ ] Conta compartilhada.
- [ ] Planos pagos.
