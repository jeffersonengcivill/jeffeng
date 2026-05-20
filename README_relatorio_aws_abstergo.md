# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 19/05/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Jefferson Vieira  

---

## Introdução

Este relatório apresenta uma proposta de implementação de serviços AWS na empresa **Abstergo Industries**, com foco na **redução imediata de custos operacionais em nuvem**, melhoria do controle financeiro e otimização do uso de recursos computacionais.

O objetivo do projeto é elencar **3 serviços AWS** que possam contribuir diretamente para a diminuição de custos, permitindo maior visibilidade dos gastos, melhor aproveitamento da infraestrutura existente e redução de desperdícios com armazenamento e processamento.

---

## Descrição do Projeto

O projeto de implementação foi dividido em **3 etapas**, cada uma associada a um serviço AWS com foco específico em redução de custos.

---

## Etapa 1: AWS Cost Explorer e AWS Budgets

### Nome da ferramenta
**AWS Cost Explorer** e **AWS Budgets**

### Foco da ferramenta
Monitoramento, análise e controle dos custos da conta AWS.

### Descrição do caso de uso
A Abstergo Industries poderá utilizar o **AWS Cost Explorer** para visualizar os gastos por serviço, período, conta, tag ou centro de custo. Com isso, será possível identificar quais serviços estão gerando maior impacto financeiro e quais recursos apresentam crescimento de custo fora do padrão.

Em conjunto, o **AWS Budgets** será utilizado para criação de orçamentos mensais, alertas de consumo e notificações quando os custos reais ou previstos ultrapassarem limites definidos.

### Aplicação prática
- Criar orçamento mensal para a conta AWS da empresa.
- Configurar alertas para 50%, 80% e 100% do orçamento.
- Analisar os serviços com maior custo mensal.
- Identificar aumentos inesperados de consumo.
- Apoiar decisões de desligamento, redimensionamento ou revisão de recursos.

### Benefício esperado
Redução de desperdícios por meio de maior visibilidade financeira, prevenção de estouro orçamentário e identificação rápida de serviços com custo elevado.

---

## Etapa 2: Amazon S3 Intelligent-Tiering

### Nome da ferramenta
**Amazon S3 Intelligent-Tiering**

### Foco da ferramenta
Otimização automática de custos de armazenamento.

### Descrição do caso de uso
A Abstergo Industries poderá utilizar o **Amazon S3 Intelligent-Tiering** para armazenar arquivos, documentos, relatórios e backups com padrões de acesso variáveis ou desconhecidos.

Esse serviço move automaticamente os objetos entre camadas de armazenamento mais adequadas, conforme a frequência de acesso, contribuindo para a redução dos custos sem necessidade de análise manual constante.

### Aplicação prática
- Migrar arquivos pouco acessados para buckets S3 com Intelligent-Tiering.
- Armazenar relatórios antigos, documentos administrativos e backups.
- Reduzir custos de armazenamento de dados acessados com baixa frequência.
- Evitar pagamento desnecessário por armazenamento padrão quando o acesso aos dados for eventual.

### Benefício esperado
Redução de custos com armazenamento, mantendo os dados disponíveis e organizados conforme a necessidade de acesso da empresa.

---

## Etapa 3: AWS Compute Optimizer

### Nome da ferramenta
**AWS Compute Optimizer**

### Foco da ferramenta
Otimização e redimensionamento de recursos computacionais.

### Descrição do caso de uso
A Abstergo Industries poderá utilizar o **AWS Compute Optimizer** para analisar recursos computacionais, como instâncias Amazon EC2, grupos Auto Scaling, volumes EBS, funções Lambda e outros recursos compatíveis.

A ferramenta gera recomendações de dimensionamento com base no uso real dos recursos, permitindo identificar instâncias superdimensionadas, recursos ociosos ou configurações que podem ser ajustadas para reduzir custos sem prejudicar o desempenho.

### Aplicação prática
- Avaliar instâncias EC2 com baixa utilização.
- Redimensionar recursos superdimensionados.
- Identificar recursos ociosos que podem ser desligados.
- Revisar volumes e cargas computacionais com baixa eficiência.
- Apoiar decisões de melhoria de performance e redução de custo.

### Benefício esperado
Redução de custos com infraestrutura computacional por meio do ajuste correto dos recursos utilizados pela empresa.

---

## Resumo das Etapas

| Etapa | Serviço AWS | Foco principal | Resultado esperado |
|------:|-------------|----------------|-------------------|
| 1 | AWS Cost Explorer e AWS Budgets | Controle e monitoramento de custos | Identificar gastos excessivos e evitar estouro de orçamento |
| 2 | Amazon S3 Intelligent-Tiering | Redução de custos de armazenamento | Armazenar dados em camadas mais econômicas automaticamente |
| 3 | AWS Compute Optimizer | Otimização de recursos computacionais | Redimensionar recursos e eliminar desperdícios |

---

## Conclusão

A implementação dos serviços **AWS Cost Explorer**, **AWS Budgets**, **Amazon S3 Intelligent-Tiering** e **AWS Compute Optimizer** na empresa **Abstergo Industries** tem como resultado esperado a redução imediata de custos, o aumento da visibilidade financeira e a melhoria na eficiência operacional da infraestrutura em nuvem.

A utilização dessas ferramentas permitirá que a empresa acompanhe seus gastos de forma mais detalhada, defina limites orçamentários, otimize o armazenamento de dados e ajuste recursos computacionais conforme a real necessidade do negócio.

Recomenda-se a continuidade do acompanhamento mensal dos custos e a revisão periódica das recomendações geradas pelas ferramentas AWS, garantindo que a empresa mantenha uma operação mais eficiente, econômica e escalável.

---

## Anexos

- Link oficial: AWS Cost Explorer  
  https://aws.amazon.com/aws-cost-management/aws-cost-explorer/

- Link oficial: AWS Budgets  
  https://aws.amazon.com/aws-cost-management/aws-budgets/

- Link oficial: Amazon S3 Intelligent-Tiering  
  https://aws.amazon.com/s3/storage-classes/intelligent-tiering/

- Link oficial: AWS Compute Optimizer  
  https://docs.aws.amazon.com/compute-optimizer/latest/ug/what-is-compute-optimizer.html

---

## Estrutura sugerida para o repositório

```text
relatorio-implementacao-servicos-aws/
│
├── README.md
└── docs/
    └── relatorio-implementacao-aws.md
```

---

## Assinatura do Responsável pelo Projeto

**Jefferson Vieira**
