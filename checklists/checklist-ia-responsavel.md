# Checklist de IA Responsável

Use este checklist para revisar sistemas de IA em fases de descoberta, desenvolvimento, validação, deploy ou monitoramento. Nem todo item se aplica a todos os contextos; registre justificativas quando um item não for aplicável.

## Contexto do sistema

- [ ] O objetivo do sistema está documentado em linguagem clara.
- [ ] A decisão, recomendação ou automação apoiada por IA está descrita.
- [ ] As pessoas usuárias e pessoas afetadas foram identificadas.
- [ ] Alternativas sem IA foram consideradas.
- [ ] O nível de risco foi classificado de forma preliminar.
- [ ] Há responsáveis técnicos e de negócio definidos.

## Dados

- [ ] As fontes de dados foram registradas.
- [ ] Há descrição de período, cobertura, origem e limitações dos dados.
- [ ] Dados pessoais ou sensíveis foram identificados e tratados com cautela.
- [ ] A qualidade dos dados foi avaliada antes do uso.
- [ ] Possíveis vieses de coleta, rotulagem ou representação foram analisados.
- [ ] Existe critério para retenção, exclusão e atualização de dados.

## Modelo

- [ ] O tipo de modelo ou serviço utilizado está documentado.
- [ ] O uso pretendido está alinhado ao objetivo do sistema.
- [ ] Usos não recomendados foram definidos.
- [ ] Métricas de desempenho foram escolhidas de acordo com o risco.
- [ ] Limitações conhecidas foram registradas.
- [ ] Mudanças de versão serão controladas.

## Explicabilidade

- [ ] Existe explicação adequada para pessoas técnicas.
- [ ] Existe explicação adequada para pessoas usuárias ou operadoras.
- [ ] Decisões sensíveis podem ser justificadas com evidências.
- [ ] O nível de transparência é proporcional ao risco.
- [ ] Limitações da explicação foram documentadas.

## Fairness

- [ ] Grupos potencialmente afetados foram identificados.
- [ ] Possíveis impactos desiguais foram analisados.
- [ ] Métricas de fairness foram selecionadas quando aplicável.
- [ ] A análise considera contexto, domínio e consequências reais.
- [ ] Há plano para revisar vieses após mudanças de dados ou modelo.

## Segurança

- [ ] Entradas externas são validadas ou limitadas.
- [ ] O sistema considera riscos de prompt injection quando usa IA generativa.
- [ ] Ferramentas conectadas operam com privilégios mínimos.
- [ ] Há controles para evitar vazamento de dados.
- [ ] Testes adversariais foram planejados para cenários relevantes.
- [ ] Incidentes de segurança serão registrados e revisados.

## Privacidade

- [ ] A necessidade de uso de dados pessoais foi justificada.
- [ ] O sistema minimiza coleta e exposição de dados.
- [ ] Dados sensíveis não são enviados a serviços externos sem avaliação.
- [ ] Logs evitam registrar informações além do necessário.
- [ ] Há processo para tratar solicitações, retenção e exclusão quando aplicável.

## Monitoramento

- [ ] Métricas de qualidade e risco foram definidas.
- [ ] Drift de dados ou comportamento será acompanhado quando aplicável.
- [ ] Reclamações, contestações e falhas terão registro.
- [ ] Há critérios para pausar, corrigir ou descontinuar o sistema.
- [ ] Revisões periódicas foram previstas.

## Documentação

- [ ] Existe model card ou ficha técnica equivalente.
- [ ] A matriz de risco foi preenchida para riscos relevantes.
- [ ] Aprovações, exceções e decisões foram registradas.
- [ ] A documentação tem responsável por atualização.
- [ ] Evidências estão acessíveis para revisão e auditoria.

## Revisão humana

- [ ] Decisões sensíveis possuem revisão humana definida.
- [ ] Pessoas revisoras têm contexto suficiente para questionar a IA.
- [ ] Há processo de contestação ou correção.
- [ ] A automação não elimina responsabilidade humana.
- [ ] Casos incertos são encaminhados para avaliação apropriada.
