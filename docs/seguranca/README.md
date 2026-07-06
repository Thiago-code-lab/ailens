# Segurança em sistemas de IA

Segurança em IA envolve prevenir falhas, abusos e impactos indevidos em sistemas que usam modelos preditivos, IA generativa, agentes, RAG, ferramentas conectadas ou automações baseadas em dados.

## Riscos em sistemas de IA

- Entrada maliciosa ou manipulada.
- Respostas incorretas apresentadas com confiança.
- Vazamento de dados pessoais, confidenciais ou estratégicos.
- Uso indevido de ferramentas conectadas a sistemas internos.
- Dependência excessiva de respostas automatizadas.
- Falhas de autorização, registro e rastreabilidade.
- Exploração de prompts, contexto ou documentos recuperados.

## Segurança em IA generativa

Aplicações com LLMs exigem atenção a instruções conflitantes, dados sensíveis no contexto, alucinações, jailbreaks, prompt injection, abuso de ferramentas e respostas que possam causar dano.

Controles úteis incluem delimitação de escopo, validação de entradas, filtragem de dados sensíveis, políticas de ferramentas, logs auditáveis, revisão humana em ações críticas e testes adversariais recorrentes.

## Red teaming

Red teaming é uma prática estruturada de teste adversarial. O objetivo é descobrir falhas antes que elas causem impacto real.

Um exercício responsável deve definir:

- Escopo do sistema.
- Riscos priorizados.
- Tipos de ataques permitidos.
- Dados que não podem ser usados.
- Critérios de severidade.
- Forma de registro das evidências.
- Plano de correção e reteste.

## Prompt injection

Prompt injection ocorre quando uma entrada tenta alterar instruções, contornar políticas ou induzir o modelo a executar ações não previstas. Em sistemas com RAG ou ferramentas conectadas, esse risco pode surgir em documentos recuperados, mensagens de usuários, páginas externas ou metadados.

Mitigações possíveis incluem separar instruções de sistema de conteúdo recuperado, validar ações antes da execução, reduzir privilégios de ferramentas, registrar decisões e aplicar revisão humana em operações sensíveis.

## Vazamento de dados

Sistemas com IA devem tratar dados externos como potencialmente malformados e dados internos como potencialmente sensíveis. O desenho deve reduzir exposição desnecessária, retenção excessiva e acesso amplo demais.

Antes de enviar dados a modelos ou provedores externos, avalie necessidade, base de uso, anonimização, retenção, logs, contrato, política interna e impacto para pessoas afetadas.

## Monitoramento

Segurança não termina no deploy. Monitore incidentes, padrões de abuso, mudanças de comportamento, drift, aumento de rejeições, reclamações, falhas de ferramenta e respostas inseguras. Registre correções e revise controles periodicamente.
