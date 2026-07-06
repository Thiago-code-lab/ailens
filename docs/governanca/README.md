# Governança de IA

Governança de IA é o conjunto de processos, papéis, controles e evidências usado para orientar sistemas com IA desde a ideia inicial até o monitoramento em produção.

Ela deve ajudar equipes a tomar decisões melhores, não apenas produzir documentos. Uma boa governança reduz ambiguidade sobre quem aprova, quem revisa, quais riscos são aceitos e quais evidências precisam ser mantidas.

## Ciclo de vida de governança

1. **Definição do problema**: registrar objetivo, usuários, pessoas afetadas e alternativas sem IA.
2. **Classificação de risco**: estimar impacto, probabilidade, severidade e necessidade de revisão especializada.
3. **Análise de dados**: verificar origem, qualidade, representatividade, consentimento, privacidade e limitações.
4. **Desenvolvimento ou integração**: documentar modelo, prompts, ferramentas, dependências e decisões técnicas.
5. **Avaliação**: medir desempenho, fairness, robustez, segurança, explicabilidade e limites de uso.
6. **Aprovação**: registrar responsáveis, critérios de aceite e pendências conhecidas.
7. **Deploy**: controlar versão, permissões, logs, fallback e comunicação para pessoas usuárias.
8. **Monitoramento**: acompanhar métricas, incidentes, drift, reclamações e revisões periódicas.
9. **Descontinuação**: planejar retirada segura, preservação de evidências e comunicação de mudanças.

## Papéis e responsabilidades

- **Pessoa responsável pelo produto**: define objetivo, escopo e critérios de sucesso.
- **Equipe técnica**: documenta dados, modelos, prompts, métricas, limitações e mudanças.
- **Governança, risco e compliance**: avaliam controles, evidências, rastreabilidade e aderência a políticas internas.
- **Segurança e privacidade**: revisam exposição de dados, ameaças, permissões e retenção de informações.
- **Pessoas usuárias ou operadoras**: informam falhas, ambiguidades, impactos e dificuldades de uso.
- **Revisão humana qualificada**: avalia decisões sensíveis e casos de contestação.

## Documentação mínima recomendada

- Descrição do sistema e do problema.
- Mapeamento de pessoas afetadas.
- Classificação inicial de risco.
- Fontes de dados e restrições de uso.
- Model card ou ficha técnica equivalente.
- Critérios de avaliação e métricas.
- Limitações conhecidas e usos não recomendados.
- Controles de segurança e privacidade.
- Processo de revisão humana.
- Plano de monitoramento e resposta a incidentes.
- Histórico de versões e mudanças relevantes.
