# Roadmap de Engenharia de IA — 40 semanas

Trilha prática, gratuita sempre que possível, voltada a profissionais de desenvolvimento de software que desejam projetar, construir, avaliar e operar sistemas baseados em modelos de linguagem (LLMs).

## Ritmo sugerido

- **Duração:** 40 semanas.
- **Carga:** aproximadamente 1 hora por dia, 6 dias por semana.
- **Total estimado:** 240 horas.
- **Método:** estudar, implementar, testar, registrar aprendizados e revisar semanalmente.

A duração é uma referência, não um prazo obrigatório. Ajuste o ritmo à sua disponibilidade e aos pré-requisitos.

## Módulos

| Semanas | Módulo | Entrega prática |
|---|---|---|
| 1–4 | Fundamentos de IA e LLMs | Glossário e experimentos documentados |
| 5–7 | Prompt engineering e saídas estruturadas | Prompts versionados e validação de JSON |
| 8–11 | APIs e integração com aplicações | Serviço de API com tratamento de erros |
| 12–16 | Retrieval-Augmented Generation (RAG) | Busca com respostas fundamentadas e citações |
| 17–20 | Ferramentas, workflows e agentes | Fluxo com ferramentas e limites explícitos |
| 21–23 | Model Context Protocol (MCP) | Servidor ou cliente MCP experimental |
| 24–28 | Arquitetura de sistemas de IA | ADRs, diagramas e análise de trade-offs |
| 29–32 | Avaliação, observabilidade e operação | Dataset de avaliação, métricas e logs |
| 33–35 | Fine-tuning e adaptação de modelos | Análise de decisão e experimento opcional |
| 36–38 | Segurança, privacidade e governança | Threat model e checklist de controles |
| 39–40 | Projeto integrador | Versão consolidada do AI Operations Assistant |

## Projeto integrador: AI Operations Assistant

Evolua um assistente experimental para apoiar tarefas operacionais de engenharia. O projeto deve avançar gradualmente:

1. Receber uma solicitação e produzir uma saída estruturada validada.
2. Consultar uma base de conhecimento com respostas fundamentadas e referências.
3. Usar ferramentas com permissões mínimas e entradas validadas.
4. Exigir aprovação humana para ações de impacto.
5. Integrar-se a ferramentas por meio de MCP, quando fizer sentido.
6. Incluir avaliação, observabilidade, testes de segurança e documentação de limitações.

Comece com dados sintéticos e ambientes de teste. Não conecte o protótipo a sistemas de produção nem forneça credenciais reais sem controles adequados.

## Critérios de conclusão

Cada módulo deve gerar um artefato verificável: código, experimento, relatório, diagrama, ADR, conjunto de testes ou retrospectiva. A conclusão é baseada em evidências práticas, não apenas em horas assistidas ou conteúdo lido.

Veja também:
- [Metodologia de estudo](docs/learning-methodology.md)
- [Framework de OKRs](docs/okr-framework.md)
- [Política de recursos gratuitos](docs/free-resources-policy.md)
- [Como contribuir](CONTRIBUTING.md)
