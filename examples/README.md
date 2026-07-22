# Exemplos e Referências

Esta pasta contém diretrizes e exemplos de implementação para cada etapa do desenvolvimento do **Templair**, nosso agente de Inteligência Artificial focado em Defesa Cibernética (Blue Team).

## Guias e Implementação

> 🎬 Em breve serão disponibilizados vídeos e materiais demonstrando a implementação completa de cada etapa, com foco no raciocínio de segurança por trás de cada decisão e no tratamento de falsos positivos.

| Etapa | Descrição | Link |
|-------|-----------|------|
| **Documentação** | Como definir o caso de uso (triagem de alertas), a persona do mentor técnico e a arquitetura. | [em breve] |
| **Base de Conhecimento** | Como carregar e cruzar os dados de SOC (alertas SIEM, histórico de incidentes e políticas de firewall). | [em breve] |
| **Prompts** | Como criar prompts eficazes com *Guardrails* éticos (White Hat) e prevenir injeções maliciosas. | [em breve] |
| **Aplicação** | Como criar o dashboard funcional do SOC integrando LLM e a base de conhecimento (RAG). | [em breve] |
| **Métricas** | Como avaliar a assertividade técnica e a segurança ética (bloqueio de geração de malwares) do agente. | [em breve] |
| **Pitch** | Como apresentar a solução focando na redução da fadiga de alertas para um CISO ou Gestor de TI. | [em breve] |

## Exemplo de Implementação Simples

Confira na pasta `src/` um exemplo básico de estrutura de aplicação usando **Streamlit**. O código demonstra como criar uma interface de chat onde o analista pode colar logs de rede para o agente investigar.
