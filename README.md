# Documentação — Projetos Integradores

Documentação dos Projetos Integradores (PI) do 1º ao 5º semestre do curso de
**Ciência de Dados para Negócios** da **FATEC Votorantim** (Centro Paula Souza).

## Visão geral

| PI | Tema | Projeto / Empresa | Documento | Status |
|----|------|-------------------|-----------|--------|
| [PI 1](./PI1-Compreendendo-o-Negocio) | Compreendendo o Negócio | G.E.I Flow (empresa fictícia) | PDF | ✅ Disponível |
| [PI 2](./PI2-Visualizacao-de-Dados) | Visualização de Dados | G.E.I Flow (empresa fictícia) | PDF | ✅ Disponível |
| [PI 3](./PI3) | — | — | — | ⏳ Pendente |
| [PI 4](./PI4) | Centralização de dados de importação | Sandinox Biomateriais | — | ⏳ Pendente |
| [PI 5](./PI5-Previsao-de-Estoque-Sandinox) | Previsão de Estoque | Sandinox Biomateriais | DOCX | ✅ Disponível |

## Linha do tempo

- **PI 1 e PI 2 — G.E.I Flow:** concepção de uma plataforma que conecta empresas
  e fornecedores. O PI 1 define o negócio (missão, mercado, concorrentes, SWOT,
  5W2H, BSC); o PI 2 trabalha persona, Design Thinking, marketing (4 P's, 5 A's),
  projeções e dashboard.
- **PI 4 e PI 5 — Sandinox Biomateriais:** projeto com empresa parceira real. O PI 4
  centralizou os processos de importação (ETL, PostgreSQL, Power BI, sistema
  próprio); o PI 5 evolui para a previsão de demanda e estoque com Machine Learning.

## Estrutura do repositório

```
.
├── README.md
├── PI1-Compreendendo-o-Negocio/
│   ├── README.md
│   └── PI1_GEIFlow_Compreendendo_o_Negocio.pdf
├── PI2-Visualizacao-de-Dados/
│   ├── README.md
│   └── PI2_GEIFlow_Visualizacao_de_Dados.pdf
├── PI3/
│   └── README.md            (aguardando documentação)
├── PI4/
│   └── README.md            (aguardando documentação)
└── PI5-Previsao-de-Estoque-Sandinox/
    ├── README.md
    └── PI5_Relatorio_Tecnico_Sandinox.docx
```

## Como adicionar um novo documento

1. Coloque o arquivo na pasta do PI correspondente, usando o padrão de nome
   `PI<n>_<Projeto>_<Tema>.<ext>`.
2. Se o tema do PI ainda não estiver no nome da pasta, renomeie-a
   (ex.: `PI3` → `PI3-<Tema>`) e atualize os links deste README.
3. Atualize o `README.md` da pasta com o resumo e os integrantes.
4. Atualize a tabela **Visão geral** acima.

> ⚠️ Dados brutos das empresas parceiras (ex.: Sandinox) **não** devem ser
> versionados neste repositório.
