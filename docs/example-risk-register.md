# Registro de riscos

## Ambiente operacional:
O banco está localizado em uma área costeira com baixos índices de criminalidade. Muitas pessoas e sistemas lidam com os dados do banco: 100 funcionários presenciais e 20 funcionários remotos. A base de clientes do banco inclui 2.000 contas de pessoa física e 200 contas empresariais. Os serviços do banco são divulgados por um time esportivo profissional e por dez empresas locais da comunidade. Há regulamentações financeiras rígidas que exigem que o banco proteja seus dados e fundos, como manter dinheiro suficiente disponível a cada dia para atender aos requisitos do Federal Reserve.

| Ativo | Risco(s) | Descrição | Probabilidade | Gravidade | Prioridade |
|---|---|---|---|---|---|
| Fundos | Comprometimento de e-mail corporativo (BEC) | Um funcionário é induzido a compartilhar informações confidenciais. | | | |
| | Comprometimento do banco de dados de usuários | Os dados dos clientes estão mal criptografados. | | | |
| | Vazamento de registros financeiros | Um servidor de banco de dados com dados de backup está acessível publicamente. | | | |
| | Roubo | O cofre do banco é deixado destrancado. | | | |
| | Interrupção da cadeia de suprimentos | Atrasos nas entregas devido a desastres naturais. | | | |

**Observações**: Como eventos de segurança são possíveis, considerando os riscos que o ativo enfrenta em seu ambiente operacional?

**Ativo**: O ativo em risco de ser prejudicado, danificado ou roubado.

**Risco(s)**: Um risco potencial para os sistemas de informação e os dados da organização.

**Descrição**: Uma vulnerabilidade que pode levar a um incidente de segurança.

**Probabilidade**: Pontuação de 1 a 3 das chances de uma vulnerabilidade ser explorada. 1 significa baixa probabilidade, 2 significa probabilidade moderada e 3 significa alta probabilidade.

**Gravidade**: Pontuação de 1 a 3 do dano potencial que a ameaça causaria ao negócio. 1 significa impacto de baixa gravidade, 2 é um impacto de gravidade moderada e 3 é um impacto de alta gravidade.

**Prioridade**: Com que rapidez um risco deve ser tratado para evitar o incidente potencial. Use a seguinte fórmula para calcular a pontuação geral: Probabilidade x Gravidade do impacto = Risco

## Exemplo de matriz de risco

| Probabilidade \ Gravidade	| Baixa (1) | Moderada (2) | Catastrófica (3) |
|---|---|---|---|
| Certa (3) | 3 | 6 | 9 |
| Provável (2) | 2 | 4| 6 |
| Rara (1) | 1 | 2 | 3 |

**Duas observações**: as colunas de Probabilidade, Gravidade e Prioridade estão em branco no original, pois o documento é um modelo para ser preenchido. A fórmula da prioridade também aparece cortada no PDF ("= Risk"), e eu a traduzi exatamente assim. Se quiser, posso gerar uma versão em Word ou PDF, ou até preencher a tabela com pontuações sugeridas.