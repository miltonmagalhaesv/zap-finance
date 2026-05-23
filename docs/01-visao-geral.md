# Visão geral do Zap Finance

## Problema

Muitas pessoas têm dificuldade de manter o controle financeiro atualizado porque precisam abrir aplicativos, preencher formulários, categorizar despesas manualmente e revisar informações depois.

Além disso, gastos acontecem em momentos diferentes e muitas vezes ficam registrados apenas em notas fiscais, faturas, comprovantes, conversas ou memória.

## Proposta

Criar um assistente financeiro conversacional via WhatsApp, permitindo que o usuário registre entradas, despesas, metas e lembretes por mensagem, áudio, imagem ou documento.

No MVP inicial, o foco será registrar entradas e saídas por texto, confirmar os dados interpretados pela IA e salvar tudo em um banco PostgreSQL.

## Público inicial

O primeiro usuário do MVP será o próprio criador do projeto, para validação pessoal do fluxo.

No futuro, o projeto poderá evoluir para:

- uso familiar;
- contas compartilhadas;
- organização financeira de casais;
- controle de reembolsos;
- pequenos negócios;
- BPO financeiro;
- produto SaaS via WhatsApp.

## Princípios do projeto

- Começar simples.
- Usar WhatsApp como interface principal.
- Não salvar nada definitivo sem confirmação no início.
- Separar dados por usuário e, futuramente, por workspace.
- Proteger informações sensíveis.
- Evitar dependência de aplicativo mobile no MVP.
- Manter documentação pública sem expor dados privados.
