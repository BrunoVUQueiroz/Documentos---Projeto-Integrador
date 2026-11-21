# PI 4 — Sandinox Biomateriais

⏳ **Documentação pendente.**

## O que se sabe (a partir do relatório do PI 5)

O PI 4 centralizou os processos de importação da Sandinox, que antes eram
controlados em planilhas Excel descentralizadas (781 processos):

- **Pipeline ETL** no KNIME — extração das planilhas e do câmbio do BACEN, limpeza e carga no PostgreSQL.
- **Banco de dados** PostgreSQL com as tabelas Processos, Estoque, Fiscal e Tarefas, integrado ao ERP Oracle.
- **Dashboards** em Power BI — custos, logística e prazos, níveis de estoque e câmbio USD/BRL.
- **Sistema próprio** em FastAPI com interface HTML — módulos de Importação, Materiais, Fiscal e Integrações (ERP Oracle, Siscomex/MDIC).

Quando o documento estiver disponível, adicione-o nesta pasta, renomeie a pasta
para `PI4-<Tema>` e atualize os READMEs.
