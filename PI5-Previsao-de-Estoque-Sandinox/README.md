# PI 5 — Previsão de Estoque para Apoio às Decisões de Compra

**Empresa parceira:** Sandinox Biomateriais
**Documento:** [PI5_Relatorio_Tecnico_Sandinox.docx](./PI5_Relatorio_Tecnico_Sandinox.docx) (relatório técnico)
**Ano:** 2026

## Equipe

- Bruno Vinicius Urias Queiroz
- Gislaine Oliveira Takushi
- Mariana Borges Curvêlo
- Victor Perillo Rodrigues Sampaio
- Vinicius Montanini Pierote

## Resumo

Continuação do trabalho do PI 4 (centralização dos dados de importação, compras,
estoque e pedidos), agora com foco em **análise preditiva** para o planejamento
de estoque. A Sandinox lida com demanda variável e prazos de reposição que podem
passar de 200 dias.

**Pergunta de negócio:** como estimar a demanda e apoiar a reposição considerando
a variabilidade do consumo, a procura comercial e os prazos de produção e
importação, reduzindo rupturas sem imobilizar capital em excesso de estoque?

### Primeiro experimento de modelagem

| Item | Valor |
|------|-------|
| Base | 8.820 registros, 330 produtos, out/2016 a out/2026 (produto × mês) |
| Modelo | Random Forest Regressor |
| Variáveis | Consumo dos 3 meses anteriores (defasagens) |
| Separação | Temporal: 5.744 registros de treino e 1.352 de teste |
| Métrica | WMAPE de **82,86%** no teste (resultado preliminar) |

**Tecnologias:** Python (pandas, numpy, scikit-learn, statsmodels, matplotlib,
seaborn), Jupyter, SQLAlchemy/PostgreSQL.

## Conteúdo do relatório

1. Introdução — problema de negócio e objetivos
2. Contexto do projeto e reuniões com a empresa (ago a out/2026)
3. Dados e preparação
4. Fundamentação e método de modelagem
5. Resultados e discussão
6. Protótipo técnico e reprodutibilidade
7. Planejamento de implantação (arquitetura proposta para o PI 6)
8. Conclusão
9. Próximas etapas
10. Inventário de códigos, notebooks e artefatos técnicos
11. Apêndices (notebook, README, dicionário de dados, estratégia de modelagem, requirements e resumo do projeto)
