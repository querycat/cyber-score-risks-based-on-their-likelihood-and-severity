# Avaliação de Risco: Registro de Riscos de um Banco Comercial

## Sobre o projeto

Atividade prática de **avaliação de riscos de segurança cibernética** para um banco comercial fictício. O projeto documenta o ambiente operacional, identifica riscos aos fundos do banco e prioriza cada um com base em **probabilidade × gravidade**, seguindo a lógica da etapa de avaliação de riscos do **NIST Cybersecurity Framework (CSF)**.

## Cenário

Uma nova equipe de segurança cibernética realiza uma avaliação de risco do ambiente operacional de um banco comercial. O registro de riscos serve como registro central dos riscos potenciais aos ativos, sistemas de informação e dados da organização, ajudando a equipe a concentrar recursos nos riscos mais críticos.

**Ambiente operacional**
- Localizado em uma área costeira com baixos índices de criminalidade
- 100 funcionários presenciais e 20 remotos
- 2.000 contas de pessoa física e 200 contas empresariais
- Serviços divulgados por um time esportivo profissional e dez empresas locais
- Regulamentações financeiras rígidas, incluindo manter dinheiro suficiente disponível a cada dia para atender aos requisitos do Federal Reserve

## Matriz de risco

| Probabilidade \ Gravidade	| Baixa (1) | Moderada (2) | Catastrófica (3) |
|---|---|---|---|
| Alta (3) | 3 | 6 | 9 |
| Provável (2) | 2 | 4| 6 |
| Rara (1) | 1 | 2 | 3 |

## Resultado em resumo

| Prioridade | Risco | Pontuação | 
|---|---|---
| 1	| Comprometimento de e-mail corporativo (BEC) | 9 |
| 1	| Vazamento de registros financeiros | 9 |
| 2	| Comprometimento do banco de dados de usuários | 6 |
| 3	| Roubo | 3 |
| 4	| Interrupção da cadeia de suprimentos | 2 |

Os dois riscos de pontuação 9 devem ser tratados primeiro.

## Estrutura do repositório e ordem de leitura sugerida

```
├── README.md
├── docs
│   └── example-risk-register.md
└── 
    └── risk-register.md
```

## Metodologia

O risco é calculado com a fórmula:

```text
Probabilidade x Gravidade = Risco (Prioridade)
```

## Habilidades demonstradas

- **Avaliação de riscos**: identificação de vulnerabilidades e cálculo de pontuações com a fórmula Probabilidade x Gravidade
- **Priorização baseada em risco**: ordenação dos riscos para direcionar tempo e recursos da equipe de segurança aos mais críticos
- **Análise do ambiente operacional**: relação entre características do banco (localização, número de funcionários, base de clientes) e a exposição a ameaças
- **Conhecimento de frameworks**: aplicação da lógica de avaliação de riscos do NIST Cybersecurity Framework (CSF)
- **Identificação de diferentes fontes de risco**: ameaças humanas (BEC), técnicas (criptografia fraca, servidor exposto), físicas (roubo) e ambientais (desastres naturais)
- **Consciência regulatória**: consideração de exigências financeiras e do Federal Reserve ao avaliar a gravidade dos impactos
- **Análise de impacto no negócio**: avaliação de perdas financeiras, danos à reputação, perda de clientes e multas regulatórias
- **Comunicação técnica**: justificativas objetivas para cada pontuação e documentação clara em Markdown

## Limitações

As pontuações são estimativas baseadas no cenário fornecido e no conhecimento geral do setor. Avaliações reais usam dados, histórico de incidentes e julgamento de especialistas. O objetivo aqui é praticar o processo de avaliação de risco.

## Aviso

Este projeto é baseado em um cenário educacional e tem finalidade exclusivamente de portfólio/estudo.

## Autoria

querycat — em transição de carreira de desenvolvimento de software para cibersegurança, com foco em unir experiência em pagamentos e antifraude ao conhecimento de segurança.

[GitHub](https://github.com/querycat) · [LinkedIn](https://www.linkedin.com/in/maysa-pereira/)

