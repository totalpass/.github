<!-- 
**********************************************************************
📖 Guia de Code Review da TotalPass: https://www.notion.so/totalpass/Guia-de-Code-Review-352e4e306e06810c9929f5841716016f 
**********************************************************************
-->

<!-- 📝 TÍTULO DO PR
     Siga o padrão: [{tag-do-time}-{numero-da-task}] - {Título em português}
     Exemplo: [ENG-123] - Adiciona validação de CPF no cadastro de usuário -->

<!-- 🏷️ LABELS — Selecione ao menos uma antes de mover para Review:
     bug-fix | feature | refactoring | performance | migration | dependencies | infra | docs | maintenance -->

<!-- 👤 RESPONSÁVEL — Atribua-se como Assignee na sidebar antes de mover para Review -->

## Descrição
<!-- O que foi alterado e, principalmente, POR QUÊ essa mudança é necessária.
     Exemplo: "Adicionamos validação de CPF pois o campo aceitava entradas inválidas,
     causando erros silenciosos no serviço de pagamento." -->

Ops, ainda não tem uma descrição aqui 👀

## Motivação
<!-- O contexto de negócio ou produto por trás dessa mudança — o que não está no código.
     Exemplo: "Usuários estavam conseguindo se cadastrar com CPFs inválidos, gerando falhas
     no processamento de pagamento e aumento de tickets no suporte." -->

## Tipo de alteração
- [ ] 🐛 Bug fix
- [ ] ✨ Nova feature
- [ ] ♻️ Refatoração
- [ ] ⚡ Melhoria de performance
- [ ] 🗄️ Migration (banco de dados)
- [ ] 📦 Dependências
- [ ] 🏗️ Infra / Terraform
- [ ] 📄 Documentação
- [ ] 🔧 Manutenção

## Testes
<!-- Descreva como as mudanças foram testadas.
     Se fluxos críticos ficaram sem cobertura, justifique aqui. -->

## Evidências
<!-- Se aplicável, adicione evidências que ilustrem o comportamento antes e depois da mudança.
     Exemplos: prints, gravações de tela, respostas de API (JSON), logs, traces, métricas. -->

## Checklist
- [ ] Revisei meu próprio diff antes de abrir para revisão
- [ ] O PR está focado — migrations, dependências e infra estão em PRs separados (se aplicável)
- [ ] Adicionei testes para os fluxos alterados (ou justifiquei a ausência acima)
- [ ] Trechos menos óbvios estão comentados no código
- [ ] Secrets e parâmetros foram cadastrados no Secrets Manager (se aplicável)
- [ ] `atlantis plan` foi executado e revisado (se aplicável a Terraform)

## Links
<!-- Cole o link do card do Jira e qualquer outro documento relevante.
     Destaque aqui pontos que merecem atenção especial do revisor. -->
