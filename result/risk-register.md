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

**Ativo**: O ativo em risco de ser prejudicado, danificado ou roubado.

**Risco(s)**: Um risco potencial para os sistemas de informação e os dados da organização.

**Descrição**: Uma vulnerabilidade que pode levar a um incidente de segurança.

**Probabilidade**: Pontuação de 1 a 3 das chances de uma vulnerabilidade ser explorada. 1 significa baixa probabilidade, 2 significa probabilidade moderada e 3 significa alta probabilidade.

**Gravidade**: Pontuação de 1 a 3 do dano potencial que a ameaça causaria ao negócio. 1 significa impacto de baixa gravidade, 2 é um impacto de gravidade moderada e 3 é um impacto de alta gravidade.

**Prioridade**: Com que rapidez um risco deve ser tratado para evitar o incidente potencial. Use a seguinte fórmula para calcular a pontuação geral: Probabilidade x Gravidade do impacto = Risco

## Notas

Como o banco é regulado e depende de dados de muitas pessoas, erros humanos e falhas técnicas são mais prováveis que crimes físicos. Funcionários podem ser enganados por golpes de e-mail, e dados mal protegidos ficam expostos. Por ser costeiro, desastres naturais podem atrasar a reposição de fundos e violar exigências regulatórias.

## Matriz de risco

| Probabilidade \ Gravidade	| Baixa (1) | Moderada (2) | Catastrófica (3) |
|---|---|---|---|
| Alta (3) | 3 | 6 | 9 |
| Provável (2) | 2 | 4| 6 |
| Rara (1) | 1 | 2 | 3 |

## Ordem de prioridade

1. BEC e vazamento de registros financeiros (9)
2. Banco de dados de usuários (6)
3. Roubo (3)
4. Cadeia de suprimentos (2)

## Justificativas
- **BEC (3 x 3 = 9)**: Com 120 funcionários (20 deles remotos) e um banco com visibilidade pública, o phishing é frequente. Um golpe bem-sucedido pode causar perdas financeiras diretas e vazamento de informações confidenciais.
- **Banco de dados de usuários (2 x 3 = 6)**: Criptografia fraca só é explorada se um atacante obtiver acesso aos dados, por isso a probabilidade é moderada. Se ocorrer, o impacto é alto: dados de 2.200 contas expostos e violação regulatória.
- **Vazamento de registros financeiros (3 x 3 = 9)**: Um servidor de backup acessível publicamente pode ser encontrado por varreduras automatizadas a qualquer momento, e o impacto envolve multas, perda de clientes e dano à reputação.
- **Roubo (1 x 3 = 3)**: A região tem baixa criminalidade, então a probabilidade é baixa. A gravidade é alta porque o cofre guarda os fundos exigidos pelo Federal Reserve.
- **Cadeia de suprimentos (1 x 2 = 2)**: Furacões afetam a região apenas a cada poucos anos, e o banco pode ter alternativas para se reabastecer, o que limita o impacto.