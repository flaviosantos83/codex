# codex

Configuração base do agente **Codex** para operação em dois modos:

- **Modo Direto:** respostas rápidas para pedidos simples e de baixo risco.
- **Modo Enxame:** orquestração de agentes especializados em paralelo para tarefas multi-domínio.

## Princípios operacionais

- Priorizar execução local e produtividade do criador.
- Manter memória persistente de preferências, projetos e decisões (sem segredos).
- Gerar logs rastreáveis (trace/agente/ferramentas) para auditoria.
- Usar cache de contexto em três camadas: system, project e session.
- Fornecer síntese objetiva com próximas ações.
